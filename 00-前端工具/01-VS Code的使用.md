

## 前言

VS Code  本来是前端人员专用，但由于它实在是太好用了，于是，各种开发方向的码农也正在用 VS Code 作为他们的主力编程工具。甚至是一些写作的同学，也把 VS Code 作为 markdown 写作工具。

写下这篇文章，是顺势而为。

### VS Code 的介绍

VS Code 的全称是 Visual Studio Code，是一款开源的、免费的、高性能的、跨平台的、轻量级的代码编辑器。它在性能、语言支持、开源社区方面，都做的很不错。

### 编辑器 与 IDE

`IDE`和`编辑器`是有区别的：

- **IDE** ：对代码会有较好的智能提示，同时侧重于工程项目，对项目的开发、调试工作有较好的图像化界面的支持，因此比较笨重。比如 Eclipse 的定位就是 IDE。

- **编辑器**：要相对轻量许多，侧重于文本的编辑。比如 Sublime Text 的定位就是编辑器。再比如 Windows 系统自带的「记事本」就是最简单的编辑器。

需要注意的是，VS Code 的定位是`编辑器`，而非`IDE`。但 VS Code 又比一般的编辑器的功能要丰富许多。

### VS Code的一些补充

- VS Code 的使命，是让开发者在编辑器里拥有 IDE 那样的开发体验，比如代码的智能提示、语法检查、图形化的调试工具、插件扩展、版本管理等。

- VS Code 的源代码以MIT协议开源。

- VS Code 自带了 TypeScript 和 Node.js 的支持。也就是说，你在书写 JS 和 TS 时，是自带智能提示的。

### 前端利器之争： VS Code 与 idea

- **哪个更酷**：显然 VS Code 更酷。

- **内存占用情况**：根据我的观察，VS Code是很占内存的（尤其是当你打开多个窗口的时候），但如果你的内存条够用的话，使用起来是不会有任何卡顿的感觉的。相比之下，idea 不仅非常占内存，而且还非常卡顿。

- **使用比例**：当然是 VS Code 更胜一筹。


## VS Code 的安装

- VS Code 官网：<https://code.visualstudio.com>

VS Code 的安装很简单，直接去官网下载安装包即可。

![](http://img.smyhvae.com/20190313_1750.png)

上图中，直接点击 download 下载安装即可。


## VS Code的基本功能


### 命令面板

Mac用户按住快捷键 `Cmd+Shift+P` （Windows用户按住快捷键`Ctrl+Shift+P`），可以打开命令面板。效果如下：

20190329_1750.png


如果们需要搜索各种设置项，就可以用到命令面板。比如说，在命令面板输入“字体”，效果如下：

20190329_2110.png

再比如说，在命令面板输入“快捷键”，就可以进入快捷键的设置。

### 插件扩展

### 文件对比

VS Code 默认支持**对比两个文件的内容**。选中两个文件，然后右键选择“将已选项进行比较”即可，效果如下：

20190329_1756.png

VS Code自带的对比功能并不够强大，我们可以安装插件`compareit`，进行更丰富的对比。比如说，安装完插件`compareit`之后，我们可以将「当前文件」与「剪切板」里的内容进行对比：

20190329_1757.png

## VS Code快捷键

### 移动光标

| Mac快捷键 | Win快捷键 | 作用 | 备注 |
|:-------------|:-------------|:-----|:-----|
| Cmd + ← |   | 将光标定位到当前行的最左侧 |  |
| Cmd + → |   | 将光标定位到当前行的最右侧 |  |
| Cmd + ↑ | Ctrl + Home |  将光标定位到文章的第一行|  |
| Cmd + ↓ | Ctrl + End | 将光标定位到文章的最后一行 |  |


根据上面的快捷键，我们可以举一反三。补充如下：

- `方向键`：在`单个字符`之间移动光标

- `option + 左右方向键`：在**单词**之间移动光标

- `Cmd + 左右方向键`：在**整行**之间移动光标。

- `Cmd + Shift + \`：在**代码块**之间移动光标。


### 删除操作

| Mac快捷键 | Win快捷键 | 作用 | 备注 |
|:-------------|:-------------|:-----|:-----|
| **option + delete** |   | 删除光标之前的一个单词	 | 英文有效 |
| option + backspace |   | 删除光标之后的一个单词 |  |
| **Cmd + delete** |   | 删除光标之前的整行内容 |  |
| Cmd + backspace |   | 删除光标之后的整行内容 |  |


备注：上面所讲到的移动光标、删除操作的快捷键，在其他编辑器里，也是同样的操作。


### 自定义快捷键

按住快捷键「Cmd + Shift + P」，弹出命令面板，在命令面板中输入“快捷键”，可以进入快捷键的设置。

当然，我们也可以选择菜单栏“偏好设置 --> 键盘快捷方式”，进入快捷键的设置：

20190329_2120.png


## 常用插件推荐

### Settings Sync

- 地址：<https://github.com/shanalikhan/code-settings-sync>

- 作用：多台设备之间，同步 VS Code 配置。[荐]


### vscode-syncing
--
- 地址：<https://github.com/nonoroazoro/vscode-syncing>

- 作用：多台设备之间，同步 VS Code 配置。

## 常见主题推荐

## 常用快捷键

### 编辑


**删除文字**：


| 快捷键 | 作用 | 备注 |
|:-------------|:-----|:-----|
|delete|删除光标的前一个字符|相当于 Windows 键盘上的退格键|
|fn + delete|删除光标的后一个字符||
|**option + delete**|删除光标之前的一个单词|英文有效|
|**command + delete**|删除光标之前的整行内容|【荐】|


## 参考链接





