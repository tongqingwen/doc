<h1 align="center"> TUI系统的所有说明文档 </h1>


## TUI详细说明
👉`TUI API使用说明.pdf`👈，详细的描述了TUI内核结构，以及所有API接口的说明和使用demo。

#### TUI框架特性：
* 独立的模块化，支持完美释放资源后退出。（目前市面上的GUI都不能做到这点）
* 独立封装了各个跨平台函数，代码包含`#include "tui.h"`就可以。
* 视图、资源（支持压缩，节约ROM）和逻辑分离，互不干扰。
* 所有事件都通过回调函数相应。

#### TUI控件特性：
* 支持gif动画
* 支持二维码
* 支持多路声音混播
* 支持各种动画
* 支持多国语言
* 支持点阵字体和矢量字体
* 支持中文输入法

<br>

## UIStudio详细说明
👉`UIStudio操作手册.pdf`👈，详细的描述了UIStudio‘所见即所得’工具的所有操作细节。

#### UIStudio工具特性：
* 界面简洁，所有功能都呈现在界面。
* 操作方便，实时显示。
* 运行速度快，无卡顿。
* 支持逆向工程，通过镜像文件`res.disk`逆向，并且支持密码保护。
