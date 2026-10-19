<h1 align="center">Hi, I'm hy123 👋</h1>

<p align="center">
  高级计算机视觉工程师 · Senior Computer Vision Engineer<br />
  深圳 · Shenzhen
</p>

<p align="center">
  <a href="https://bytewize.cc/">个人网站</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/hy123-pixel?tab=repositories">全部项目</a>
</p>

---

### About

专注计算机视觉与工程实践，也喜欢把日常开发中的小问题做成好用的工具。最近主要在做 Swift / macOS 应用、Apple 平台开发工具和跨平台桌面应用。

### Selected projects

| Project | What it does | Built with |
| --- | --- | --- |
| [MemoryBar](https://github.com/hy123-pixel/MemoryBar) | macOS 菜单栏内存监视器：按应用查看用量，按需结束占用较高的应用 | Swift, SwiftUI |
| [CodexQuotaMenu](https://github.com/hy123-pixel/CodexQuotaMenu) | 在 macOS 菜单栏查看 Codex 额度与重置时间 | Swift, SwiftUI |
| [MdPreviewApp](https://github.com/hy123-pixel/MdPreviewApp) | 面向 macOS 与 Windows 的 Markdown 桌面编辑器，支持实时预览、目录导航、数学公式和 Mermaid 图表 | Tauri, Vue, TypeScript |
| [ChronoKit](https://github.com/hy123-pixel/ChronoKit) | 日期、时区、时间戳与业务日处理工具库 | Swift |

### MemoryBar

点击菜单栏即可查看系统内存和应用占用；应用辅助进程会按应用归组，内存数据只在本机采集。

<p align="center">
  <a href="https://github.com/hy123-pixel/MemoryBar">
    <img src="https://raw.githubusercontent.com/hy123-pixel/MemoryBar/main/docs/images/product-overview-en.svg" alt="MemoryBar macOS menu bar memory monitor" width="800" />
  </a>
</p>

<p align="center"><sub>Usage: check menu bar memory → open the app list → select an app → end it from the context menu.</sub></p>
<p align="center">
  <a href="https://github.com/hy123-pixel/MemoryBar">
    <img src="https://raw.githubusercontent.com/hy123-pixel/MemoryBar/main/docs/images/how-it-works-en.svg" alt="Four-step MemoryBar usage flow" width="800" />
  </a>
</p>

### MdPreviewApp

用于写作、阅读和整理 Markdown 文档。可在源码编辑、实时预览和分屏模式之间切换，并支持文件树、文章目录、代码高亮、数学公式与 Mermaid 图表。提供 macOS 和 Windows 安装包。

```mermaid
flowchart LR
    File[Markdown 文件] --> Editor[源码编辑]
    Editor --> Render[Markdown 渲染]
    Render --> Preview[实时预览]
    Editor --> Save[保存文件]
    App[Tauri 桌面应用] --> System[macOS / Windows 系统文件能力]
```

### Technologies

`Swift` · `SwiftUI` · `Computer Vision` · `macOS` · `iOS` · `Tauri` · `Vue` · `TypeScript`

---

<p align="center"><sub>Build useful things, keep making them better.</sub></p>
