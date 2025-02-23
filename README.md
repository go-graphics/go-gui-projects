
_(Please follow [@zigo_101](https://twitter.com/zigo_101) for updates on this page, and all kinds of details and facts in Go)._

----

# A list of Go GUI/graphics/image related projects

### native GUI and utility bindings

[DarwinKit](https://github.com/progrium/darwinkit) (old name: MacDriver) lets you work with Apple frameworks and build native Mac applications using Go.

[dlgs](https://github.com/gen2brain/dlgs) is a cross-platform library for displaying dialogs and input boxes.

[gamen](https://github.com/rajveermalviya/gamen) is cross-platform GUI window creation and management library in Go.

[gform](https://github.com/AllenDang/gform) is an easy to use Windows GUI toolkit for Go.
* [winc](https://github.com/tadvi/winc) is a common library for Go GUI apps on Windows (based on gform).

[glfw](https://github.com/go-gl/glfw) is a Go bindings for GLFW 3.

[go-fltk](https://github.com/pwiecz/go-fltk) is a simple wrapper around [FLTK 1.4 library](https://www.fltk.org/), which is a lightweight GUI library which allows creating small, self-contained and fast gui applications.

[go-mobile](https://github.com/golang/mobile) adds support for mobile platforms (Android and iOS) and provides tools to build mobile applications. (A [Go bindings for OpenGL ES 2.0 and ES 3.0](https://godoc.org/golang.org/x/mobile/gl) is included.)

[go-sfml](https://github.com/teh-cmc/go-sfml) is a Go bindings for [SFML](https://www.sfml-dev.org/).

[GoVCL](https://github.com/ying32/govcl) is a native GUI library based on [liblcl](https://github.com/ying32/liblcl).

GTK related:
* [go-gtk](https://github.com/mattn/go-gtk) is a Go binding for GTK2.
* [gotk3](https://github.com/gotk3/gotk3) provides Go bindings for GTK+3 and dependent projects (including [cairo](https://github.com/gotk3/gotk3/tree/master/cairo)).
  * Another one: [gobbi](https://github.com/pekim/gobbi) (including [cairo](https://github.com/pekim/gobbi/tree/master/lib/cairo)).
* [gotk4](https://github.com/diamondburned/gotk4) is a GTK4 bindings generator for Go.

[GXUI](https://github.com/google/gxui) is a Go cross platform UI library.

[iup-go](https://github.com/gen2brain/iup-go) is a Go bindings for [IUP](https://www.tecgraf.puc-rio.br/iup/).

[nuxui](https://github.com/nuxui/nuxui) is a cross-platform GUI library to make macOS, window, linux, IOS, android applications.

QT related:
* [miqt](https://github.com/mappu/miqt) is a MIT-licensed Qt bindings for Go.
* [Qamel](https://github.com/go-qamel/qamel) is a simple QML binding for Go (MIT license)
* [qt](https://github.com/therecipe/qt) allows you to write Qt applications entirely in Go and makes deploying them later very easy (LGPL license).
* [qt.go](https://github.com/kitech/qt.go) is a Qt5 binding which uses FFI instead of CGO (LGPL license).

[RenderView](https://github.com/TheGrum/renderview) is an easy Go GUI wrapper for interactive manipulation of visual algorithms/backend code. Support go-gtk (default), gotk3 and shiny backends.

SDL related:
* [go-sdl2](https://github.com/veandco/go-sdl2) is SDL2 wrapped for Go users.
* [purego-sdl3](https://github.com/JupiterRider/purego-sdl3) is a cgo-free SDL3 binding.

[shiny](https://github.com/golang/exp/tree/master/shiny) is a Go cross platform UI package.

[Spot](https://github.com/roblillack/spot) is a reactive, cross-platform desktop GUI toolkit.

[systray](https://github.com/getlantern/systray) is a cross platfrom Go library to place an icon and menu in the notification area. Tested on Windows 8, Mac OSX, Ubuntu 14.10 and Debian 7.6.

Tcl/Tk related:
* [gothic](https://github.com/nsf/gothic) is a tcl/tk binding.
* [tk9.0](https://gitlab.com/cznic/tk9.0) is a CGo-free (use dynamic lib loading instead), cross platform GUI toolkit for Go.

[trayhost](https://github.com/shurcooL/trayhost) is a cross-platform Go library to place an icon in the host operating system's taskbar.

[ui](https://github.com/andlabs/ui) aims to provide simple GUI software development in Go, based on my c lib [libui](https://github.com/andlabs/libui).

[w32.go](https://gist.github.com/nathan-osman/18c2e227ad00a223b61c0b3c16d452c3) is a simple example on show to create Windows GUI by using the `syscall` package.

[Windigo](https://github.com/rodrigocfd/windigo) - Win32 API and GUI in idiomatic Go.

[Walk](https://github.com/lxn/walk) is a "Windows Application Library Kit" for the Go Programming Language.

[wui](https://github.com/gonutz/wui) is a Windows GUI library that uses [the native Win32 API](https://github.com/gonutz/w32), which is forked from [this one](https://github.com/AllenDang/w32).

[XGB](https://github.com/BurntSushi/xgb) is the X Go Binding, which is a low-level API to communicate with the
core X protocol and many of the X extensions.

[xgbutil](https://github.com/BurntSushi/xgbutil) is a utility library designed to work with the X Go Binding.

[zenity](https://github.com/ncruces/zenity) is a cross-platform package providing [Zenity](https://help.gnome.org/users/zenity/stable/)-like dialogs.

### HTML based GUI

[Apptron](https://github.com/tractordev/apptron) gives you webview windows and common platform APIs for your simple scripts, homebrew utilities, or full applications.

[Go-app](https://github.com/maxence-charriere/go-app) is a package for building progressive web apps (PWA) with the Go programming language (Golang) and WebAssembly (Wasm).

[go-astilectron](https://github.com/asticode/go-astilectron) helps use build cross platform GUI apps with GO and HTML/JS/CSS. It is the official GO bindings of astilectron and is powered by Electron.

[go-sciter](https://github.com/sciter-sdk/go-sciter) is a Golang bindings of Sciter: the Embeddable HTML/CSS/script engine for modern UI development。

[gowd](https://github.com/dtylman/gowd) help us build cross platform GUI apps with GO and HTML/JS/CSS (powered by nwjs)。

[Gowut](https://github.com/icza/gowut) is a Web UI Toolkit written in pure Go. Apps are rendered as HTML pages. It doesn't bundle browsers.

[Lorca](https://github.com/zserge/lorca) is a very small library to build modern HTML5 desktop apps in Go. It doesn't bundle Chrome but reuses the installed Chrome on your machine.

[Muon](https://github.com/ImVexed/muon) is a lightweight alternative to Electron written in Golang, using [Ultralight](https://ultralig.ht/) instead of Chromium.

[Qlovaseed](https://github.com/qlova/seed) is a lightweight alternative to Electron written in Golang. Apps are rendered as HTML pages. It doesn't bundle browsers.

[Wails](https://github.com/wailsapp/wails) is a framework for building desktop applications using Go & Web Technologies.

[webview](https://github.com/webview/webview) is a tiny cross-platform webview library for C/C++/Golang to build modern cross-platform GUIs.

### custom GUI

[Cogent Core](https://github.com/cogentcore/core) is a free and open source framework for building powerful, fast, elegant 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and the web.

[duit](https://github.com/mjl-/duit) is a pure go, cross-platform, MIT-licensed ui toolkit for developers.

[Fyne](https://github.com/fyne-io/fyne) is an easy to use UI toolkit and app API written in Go. We use OpenGL (through the go-gl and go-glfw projects) to provide cross platform graphics.

[Gio](https://git.sr.ht/~eliasnaur/gio) implements portable immediate mode GUI programs in Go. Gio programs run on all the major platforms: iOS/tvOS, Android, Linux (Wayland), macOS, Windows and browsers (Webassembly/WebGL).

[goey](https://bitbucket.org/rj/goey) [mirror](https://gitlab.com/stone.code/goey) provides a declarative, cross-platform GUI for the Go language. The range of controls, their supported properties and events, should roughly match what is available in HTML. However, properties and events may be limited to support portability. Additionally, styling of the controls will be limited, with the look of controls matching the native platform.

[go-flutter](https://github.com/go-flutter-desktop/go-flutter) is a package that brings Flutter to the desktop.

[gui](https://github.com/faiface/gui) provides super minimal, rock-solid foundation for concurrent GUI in Go.

[imgui-go](https://github.com/inkyblackness/imgui-go) is a Go wrapper for Dear ImGui.
* [giu](https://github.com/AllenDang/giu) is a GUI framework based on imgui-go. (Another similar one from the same auther, [gimu](https://github.com/AllenDang/gimu), but for nucular.)

[microui-go](https://github.com/zeozeozeo/microui-go) is a Go port of the tiny immediate-mode UI library [microui](https://github.com/rxi/microui).

[NanoGUI.go](https://github.com/shibukawa/nanogui-go) is a golang port of [NanoGUI](https://github.com/wjakob/nanogui).

[nk](https://github.com/golang-ui/nuklear) provides Go bindings for nuklear.h. 
* Another one: [nucular](https://github.com/aarzilli/nucular), which uses gio or shiny backend instead of cgo.

[Unison](https://github.com/richardwilkes/unison) is a unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported. Unison is built upon glfw. Unison defines its own look and feel for widgets. This was done to provide as much consistency as possible between all supported platforms.

### 3D graphics and computing API bindings

[d3d9](https://github.com/gonutz/d3d9) is a pure Go wrapper for Microsoft's Direct3D9 API.

[gl](https://github.com/go-gl/gl) repository holds Go bindings to various OpenGL versions. They are auto-generated using Glow. 
* And [GLHF](https://github.com/faiface/glhf), a gl3.3 wrapper.
* And the above mentioned [OpenGL ES 2.0 and ES 3.0 bindings](https://godoc.org/golang.org/x/mobile/gl) from the go-mobile project.
* Also the OpenGL ES implemention in the [android-go](https://github.com/xlab/android-go) project.

[vulkan](https://github.com/vulkan-go/vulkan) provides Go bindings for Vulkan — a low-overhead, cross-platform 3D graphics and compute API.
* Another one: [vkngwrapper](https://github.com/vkngwrapper)
* And another one: [go-vk](https://github.com/bbredesen/go-vk)

### 2D vector graphics and computing APIs

[draw2d](https://github.com/llgcode/draw2d) is a Go 2D vector graphics library with support for multiple outputs such as images (draw2d), pdf documents (draw2dpdf), opengl (draw2dgl) and svg (draw2dsvg). 

[gg](https://github.com/fogleman/gg) is a library for rendering 2D graphics in pure Go.

The [Gio](https://git.sr.ht/~eliasnaur/gio) project includes an efficient vector renderer based on [the Pathfinder project](https://github.com/servo/pathfinder), implemented on OpenGL ES and Direct3D 11.
* [giocanvas](https://github.com/ajstarks/giocanvas) is a canvas API built on top of Gio.

[go-cairo](https://github.com/ungerik/go-cairo) is a Go binding for the cairo graphics library.
* And the above mentioned [the](https://github.com/gotk3/gotk3/tree/master/cairo) [other](https://github.com/pekim/gobbi/tree/master/lib/cairo) [ones](https://github.com/golang-ui/cairo).

[Go canvas](https://github.com/tfriedel6/canvas) is a pure Go library that provides drawing functionality as similar as possible to the HTML5 canvas API, implemented on OpenGL backend (and software backend).

[go-chart](https://github.com/wcharczuk/go-chart) is a very simple golang native charting library that supports timeseries and continuous line charts.

[gonum/plot](https://github.com/gonum/plot) provides an API for building and drawing plots in Go

[go-p5](https://github.com/go-p5/p5) is a simple package that provides primitives resembling the ones exposed by the [p5/processing](https://p5js.org/) library.

[go-skia](https://github.com/go101/go-skia) is a Go skia binding based on skia C library through cgo.

[NanoVGo](https://github.com/shibukawa/nanovgo) is pure golang implementation of [NanoVG](https://github.com/memononen/nanovg). The same author maintains the NanoGUI.go project mentioned above.
* [A CGO binding version](https://github.com/beta/nanovgo) of NanoVG.

[svgo](https://github.com/ajstarks/svgo) generates SVG as defined by the Scalable Vector Graphics 1.1 Specification.

### font processing related

[freetype](https://github.com/golang/freetype) is a Freetype font rasterizer in the Go programming language.

The [golang.org/x/image/font/sfnt](https://godoc.org/golang.org/x/image/font/sfnt) package parses SFNT font file formats, including TrueType and OpenType.

[pixfont](https://github.com/pbnjay/pixfont) is a simple, lightweight Pixel Font (aka bitmap fonts) package for Go that works with the standard image/draw package

### CAD related

[sdfx](https://github.com/deadsy/sdfx) is a simple CAD package written in Go. [sdf](https://github.com/soypat/sdf) is a rewritten of it.

### game development related

[ebiten](https://github.com/hajimehoshi/ebiten)  – A dead simple 2D game library for Golang
* [ebitenui](https://github.com/ebitenui/ebitenui) - A UI library on top of ebiten

[godot-go](https://github.com/ShadowApex/godot-go) - Go language bindings for the [Godot Engine](https://godotengine.org/)'s [GDNative API](https://github.com/GodotNativeTools/godot_headers).

[raylib-go](https://github.com/gen2brain/raylib-go) is a Golang binding for [raylib](https://www.raylib.com).

Please visit [Awesome Go](https://github.com/avelino/awesome-go#game-development) for more.

### image processing related

The standard Go [image](https://golang.org/pkg/image/) packages.

The [image](https://github.com/golang/image/) repository holds supplementary Go image libraries.

Please visit [Awesome Go](https://github.com/avelino/awesome-go#images) for more.

### terminal UI

BTW, if you have interests in developing terminal UI Go programs, please check
[tcell](https://github.com/gdamore/tcell), [tview](https://github.com/rivo/tview) (which depends on tcell), [cview](https://gitlab.com/tslocum/cview/) (which is [a fork](https://gitlab.com/tslocum/cview/blob/master/FORK.md) of tview), and [more listed on Awesome Go](https://github.com/avelino/awesome-go#advanced-console-uis).
