
_(请关注 [@Go100and1](https://twitter.com/go100and1)了解此页面的更新以及 Go 的各种详细信息和事实)._

----

# Go GUI/图形/图像相关项目列表

### 本机 GUI 和实用程序绑定

[dlgs](https://github.com/gen2brain/dlgs) 是一个用于显示对话框和输入框的跨平台库。

[gamen](https://github.com/rajveermalviya/gamen) 是 Go 语言跨平台的 GUI 窗口创建和管理库。

[gform](https://github.com/AllenDang/gform) 是一个易于使用的 Go Windows GUI 工具包。
* [winc](https://github.com/tadvi/winc) 是 Windows 上 Go GUI 应用程序的通用库（基于 gform）。

[glfw](https://github.com/go-gl/glfw) 是 GLFW 3 的 Go 绑定。

[go-fltk](https://github.com/pwiecz/go-fltk) 是一个简单的包装器 [FLTK 1.4 library](https://www.fltk.org/), 它是一个轻量级的 GUI 库，允许创建小型、独立且快速的 GUI 应用程序。

[go-gtk](https://github.com/mattn/go-gtk) 是 GTK2 的 Go 绑定。
* [RenderView](https://github.com/TheGrum/renderview) 是一个简单的 Go GUI 包装器，用于交互式操作可视化算法/后端代码。支持 go-gtk（默认）、gotk3 和 shiny 后端。

[go-mobile](https://github.com/golang/mobile) 增加了对移动平台（Android 和 iOS）的支持，并提供了构建移动应用程序的工具。(包括[Go bindings for OpenGL ES 2.0 and ES 3.0](https://godoc.org/golang.org/x/mobile/gl))

[go-sdl2](https://github.com/veandco/go-sdl2) 是专为 Go 用户包装的 SDL2。

[go-sfml](https://github.com/teh-cmc/go-sfml) 是 [SFML](https://www.sfml-dev.org/)的 Go 绑定。

[gothic](https://github.com/nsf/gothic) 是 tcl/tk 的 Go 绑定。

[gotk3](https://github.com/gotk3/gotk3) 为 GTK+3 和​​相关项目 (包括 [cairo](https://github.com/gotk3/gotk3/tree/master/cairo)) 提供 Go 绑定。
* 另外一个: [gobbi](https://github.com/pekim/gobbi) (包括 [cairo](https://github.com/pekim/gobbi/tree/master/lib/cairo))。

[gotk4](https://github.com/diamondburned/gotk4) 是 Go 的 GTK4 绑定生成器。

[GoVCL](https://github.com/ying32/govcl) 是一个基于 [Lazarus](https://www.lazarus-ide.org/)的本机 GUI 库。

[GXUI](https://github.com/google/gxui) 是一个 Go 跨平台 UI 库。

[iup-go](https://github.com/gen2brain/iup-go) 是 [IUP](https://www.tecgraf.puc-rio.br/iup/)的 Go 绑定

[MacDriver](https://github.com/progrium/macdriver) 是一个用于在 Go 中使用 Apple/Mac API 和框架的工具包。

[nuxui](https://github.com/nuxui/nuxui) 是一个跨平台的 GUI 库，用于制作 macOS、window、linux、IOS、android 应用程序。

[qt](https://github.com/therecipe/qt) 允许您完全用 Go 编写 Qt 应用程序，并使以后部署它们变得非常容易。

[qt.go](https://github.com/kitech/qt.go) 是 Qt5 绑定，它使用 FFI 而不是 CGO。

[shiny](https://github.com/golang/exp/tree/master/shiny) 是一个 Go 跨平台 UI 包。

[Spot](https://github.com/roblillack/spot) 是一个反应灵敏的跨平台桌面 GUI 工具包。

[systray](https://github.com/getlantern/systray) 是一个跨平台的 Go 库，用于在通知区域放置图标和菜单。已在 Windows 8、Mac OSX、Ubuntu 14.10 和 Debian 7.6 上测试。

[trayhost](https://github.com/shurcooL/trayhost) 是一个跨平台的 Go 库，用于在主机操作系统的任务栏中放置图标。

[ui](https://github.com/andlabs/ui) 旨在使用 c 库 [libui](https://github.com/andlabs/libui)，用 Go 提供简单的 GUI 软件开发。

[w32.go](https://gist.github.com/nathan-osman/18c2e227ad00a223b61c0b3c16d452c3) 是一个简单的示例，展示了如何使用syscall包创建 Windows GUI。

[Windigo](https://github.com/rodrigocfd/windigo) 采用 Go 编写的 Win32 API 和 GUI。

[Walk](https://github.com/lxn/walk) 是 Go 编程的“Windows 应用程序库套件”。

[wui](https://github.com/gonutz/wui) 是一个使用 [the native Win32 API](https://github.com/gonutz/w32)的 Windows GUI 库, 它是 [this one](https://github.com/AllenDang/w32)分叉而来的.

[XGB](https://github.com/BurntSushi/xgb) 是 X 的 Go 绑定，它是用于与核心 X 协议和许多 X 扩展进行通信的低级 API。

[xgbutil](https://github.com/BurntSushi/xgbutil) 是一个旨在与[XGB](https://github.com/BurntSushi/xgb)配合使用的实用程序库。

[zenity](https://github.com/ncruces/zenity) 是一个跨平台包，提供类似[Zenity](https://help.gnome.org/users/zenity/stable/)的对话框。

### 基于 HTML 的 GUI

[Go-app](https://github.com/maxence-charriere/go-app) 是一个使用 Go 编程语言（Golang）和 WebAssembly（Wasm）构建渐进式 Web 应用程序（PWA）的软件包。

[go-astilectron](https://github.com/asticode/go-astilectron) 帮助使用 GO 和 HTML/JS/CSS 构建跨平台 GUI 应用程序。它是 astilectron 的官方 GO 绑定，由 Electron 提供支持。

[go-sciter](https://github.com/sciter-sdk/go-sciter) 是 Sciter 的 Golang 绑定：用于现代 UI 开发的可嵌入 HTML/CSS/脚本引擎。

[gowd](https://github.com/dtylman/gowd) 帮助我们使用 GO 和 HTML/JS/CSS (由 nwjs 提供支持) 构建跨平台 GUI 应用程序。

[Gowut](https://github.com/icza/gowut) 是一个纯 Go 编写的 Web UI 工具包。应用程序以 HTML 页面的形式呈现。它不捆绑浏览器。

[Lorca](https://github.com/zserge/lorca) 是一个非常小的库，用于用 Go 构建现代 HTML5 桌面应用。它不捆绑 Chrome，但会重复使用您机器上已安装的 Chrome。

[Muon](https://github.com/ImVexed/muon) 是 Electron 的轻量级替代品，用 Golang 编写，使用[Ultralight](https://ultralig.ht/)而不是 Chromium。

[Qlovaseed](https://github.com/qlova/seed) 是使用 Golang 编写的 Electron 的轻量级替代品。应用程序以 HTML 页面的形式呈现。它不捆绑浏览器。

[Wails](https://github.com/wailsapp/wails) 是一个使用 Go 和 Web 技术构建桌面应用程序的框架。

[webview](https://github.com/webview/webview) 是一个小型跨平台 webview 库，用于 C/C++/Golang 构建现代跨平台 GUI。

### 自定义 GUI

[duit](https://github.com/mjl-/duit) 是一个纯 go、跨平台、MIT 许可的开发人员 UI 工具包。

[Fyne](https://github.com/fyne-io/fyne) 是一个用 Go 编写的易于使用的 UI 工具包和应用程序 API。我们使用 OpenGL（通过 go-gl 和 go-glfw 项目）来提供跨平台图形。

[gi](https://github.com/goki/gi) 是 Go 中基于场景图的 2D 和 3D GUI/图形界面 (Gi)。

[Gio](https://git.sr.ht/~eliasnaur/gio) 使用 Go 语言实现了可移植的立即模式 GUI 程序。Gio 程序可在所有主流平台上运行：iOS/tvOS、Android、Linux (Wayland)、macOS、Windows 和浏览器 (Webassembly/WebGL)。

[goey](https://bitbucket.org/rj/goey) 为 Go 语言提供了声明式、跨平台的 GUI。控件的范围及其支持的属性和事件应与 HTML 中提供的大致相同。但是，属性和事件可能会受到限制以支持可移植性。此外，控件的样式将受到限制，控件的外观与本机平台相匹配。

[go-flutter](https://github.com/go-flutter-desktop/go-flutter) 是一个将 Flutter 应用到桌面的包。

[gui](https://github.com/faiface/gui) 为 Go 中的并发 GUI 提供了极简、坚如磐石的基础。

[imgui-go](https://github.com/inkyblackness/imgui-go) 是 Dear ImGui 的 Go 包装器。
* [giu](https://github.com/AllenDang/giu) 是一个基于 imgui-go 的 GUI 框架。（另一个类似的框架来自同一作者， [gimu](https://github.com/AllenDang/gimu)，但适用于 nucular。）

[NanoGUI.go](https://github.com/shibukawa/nanogui-go) 是 [NanoGUI](https://github.com/wjakob/nanogui) 的 Go 端口

[nk](https://github.com/golang-ui/nuklear) 为 nuklear.h 提供 Go 绑定。
* 另一个: [nucular](https://github.com/aarzilli/nucular)，它使用 gio 或 shiny 后端而不是 cgo。

[Unison](https://github.com/richardwilkes/unison) 是用于 Go 桌面应用程序的统一图形用户体验工具包。支持 macOS、Windows 和 Linux。Unison 建立在 glfw 之上。Unison 为小部件定义了自己的外观和感觉。这样做是为了在所有支持的平台之间提供尽可能高的一致性。

### 3D 图形和计算 API 绑定

[d3d9](https://github.com/gonutz/d3d9) 是 Microsoft Direct3D9 API 的纯 Go 包装器。

[gl](https://github.com/go-gl/gl) 存储库包含 Go 与各种 OpenGL 版本的绑定。它们是使用 Glow 自动生成的。
* 还有 [GLHF](https://github.com/faiface/glhf)，一个 gl3.3 包装器。
* 还有上面提到的来自 go-mobile 项目的[OpenGL ES 2.0 and ES 3.0 bindings](https://godoc.org/golang.org/x/mobile/gl)
* 还有 [android-go](https://github.com/xlab/android-go) 项目中的 OpenGL ES 实现。

[vulkan](https://github.com/vulkan-go/vulkan) 为 Vulkan 提供 Go 绑定——一种低开销、跨平台的 3D 图形和计算 API。
* 另一个: [vkngwrapper](https://github.com/vkngwrapper)
* 还有一个: [go-vk](https://github.com/bbredesen/go-vk)

### 2D矢量图形和计算API

[draw2d](https://github.com/llgcode/draw2d) 是一个 Go 2D 矢量图形库，支持多种输出，如图像（draw2d）、pdf 文档（draw2dpdf）、opengl（draw2dgl）和 svg（draw2dsvg）。

[gg](https://github.com/fogleman/gg) 是一个用 Go 渲染 2D 图形的库。

The [Gio](https://git.sr.ht/~eliasnaur/gio) 项目包括一个基于 [the Pathfinder project](https://github.com/servo/pathfinder)项目的高效矢量渲染器，该渲染器在 OpenGL ES 和 Direct3D 11 上实现。
* [giocanvas](https://github.com/ajstarks/giocanvas) is a canvas API built on top of Gio.

[go-cairo](https://github.com/ungerik/go-cairo) 是一个基于 Gio 构建的画布 API。
* 以及上面提到的 [gotk3](https://github.com/gotk3/gotk3/tree/master/cairo) [gobbi](https://github.com/pekim/gobbi/tree/master/lib/cairo) [cairo](https://github.com/golang-ui/cairo).

[Go canvas](https://github.com/tfriedel6/canvas) 是一个 Go 库，提供与 HTML5 canvas API 尽可能相似的绘图功能，在 OpenGL 后端（和软件后端）上实现。

[go-chart](https://github.com/wcharczuk/go-chart) 是一个非常简单的 golang 原生图表库，支持时间序列和连续折线图。

[gonum/plot](https://github.com/gonum/plot) 提供了用 Go 构建和绘制图表的 API

[go-p5](https://github.com/go-p5/p5) 是一个简单的包，它提供类似于 [p5/processing](https://p5js.org/) 库公开的原语。

[go-skia](https://github.com/go101/go-skia) 是一个通过 cgo 基于 skia C 库的 Go skia 绑定。

[NanoVGo](https://github.com/shibukawa/nanovgo) 是 [NanoVG](https://github.com/memononen/nanovg) 的 golang 实现. 同一作者维护着上面提到的 NanoGUI.go 项目。
* [NanoVG](https://github.com/memononen/nanovg)的 CGO 绑定版本[nanovgo](https://github.com/beta/nanovgo)。

[svgo](https://github.com/ajstarks/svgo) 按照可缩放矢量图形 1.1 规范定义生成 SVG。

### 字体处理相关

[freetype](https://github.com/golang/freetype) 是 Go 编程语言中的 Freetype 字体光栅化器。

这个[golang.org/x/image/font/sfnt](https://godoc.org/golang.org/x/image/font/sfnt)包解析 SFNT 字体文件格式，包括 TrueType 和 OpenType 

[pixfont](https://github.com/pbnjay/pixfont) 是一个简单、轻量级的 Go 像素字体（又名位图字体）包，可与标准 image/draw 包配合使用

### CAD 相关

[sdfx](https://github.com/deadsy/sdfx) 是一个用 Go 编写的简单 CAD 包。 [sdf](https://github.com/soypat/sdf)是它的重写版

### game development related

[ebiten](https://github.com/hajimehoshi/ebiten)  一款非常简单的 Golang 2D 游戏库
* [ebitenui](https://github.com/ebitenui/ebitenui) 基于 ebiten 的 UI 库

[godot-go](https://github.com/ShadowApex/godot-go) 是 [Godot Engine](https://godotengine.org/)'s 的 [GDNative API](https://github.com/GodotNativeTools/godot_headers) 的 Go 绑定。

[raylib-go](https://github.com/gen2brain/raylib-go) 是 [raylib](https://www.raylib.com) 的 Go 绑定。

请访问 [Awesome Go](https://github.com/avelino/awesome-go#game-development) 以了解更多。

### 图像处理相关

标准的 Go [image](https://golang.org/pkg/image/) 包.

[image](https://github.com/golang/image/) 存储库包含补充的 Go 图像库。

请访问 [Awesome Go](https://github.com/avelino/awesome-go#images) 以了解更多。

### 终端界面

顺便说一句，如果您对开发终端 UI Go 程序感兴趣，请查看
[tcell](https://github.com/gdamore/tcell), [tview](https://github.com/rivo/tview) (依赖于 tcell), [cview](https://gitlab.com/tslocum/cview/) (tview 的一个分支 [a fork](https://gitlab.com/tslocum/cview/blob/master/FORK.md)), 以及[Awesome Go](https://github.com/avelino/awesome-go#advanced-console-uis)上列出的更多内容。

