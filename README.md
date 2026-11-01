<div align="center">

# 你好 👋

**我在做 Local-first 的 AI Agent 和开发工具。**

让 Coding Agent 走出聊天框，进入桌面、微信和终端。

[GitHub](https://github.com/jiawei666) · [邮箱](mailto:beconfident666@gmail.com)

![Codex App Server](https://img.shields.io/badge/Codex-App%20Server-111111?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Tools-2ea44f?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Local-first](https://img.shields.io/badge/Local--first-2ea44f?style=flat-square)

</div>

---

## 最近在做

- **Rambo** —— 一个长期待在本机的个人 Agent。
- **wecode** —— 连接微信和本机 Codex 的桥接工具。
- **CODESK** —— 围绕 Codex 打造的终端工作台。

> 同一个想法，三种入口：Agent 留在本地，保留原生上下文，并真正进入工作流，而不是成为另一个需要专门打开的页面。

## 项目

### Rambo

**一台真正待在自己 Mac 上的个人 AI Agent。**<br>
`2026.10.31` · `Electron` · `React` · `TypeScript` · `Codex App Server`

[![GitHub](https://img.shields.io/badge/GitHub-Rambo-181717?style=flat-square&logo=github)](https://github.com/jiawei666/Rambo)
[![版本](https://img.shields.io/github/v/release/jiawei666/Rambo?style=flat-square&label=%E7%89%88%E6%9C%AC)](https://github.com/jiawei666/Rambo/releases/latest)
![平台](https://img.shields.io/badge/%E5%B9%B3%E5%8F%B0-macOS%20arm64-111111?style=flat-square)

- **从本地出发**：Bot、聊天、Routine、设置和记忆都保存在本机，并通过隔离的 Codex Home 管理运行时。
- **多个 Bot，一个工作区**：每个 Bot 独立保留模型、上下文、Skills、MCP、Apps 和 Plugins，同时也能在群聊中协作。
- **不只是聊天**：Routine、邮箱、微信、电脑/浏览器自动化、语音和本机文件，最终都会回到同一个会话。

[了解 Rambo →](https://github.com/jiawei666/Rambo)

---

### wecode

**在微信里使用本机 Codex。**<br>
`2026.10.28` · `TypeScript` · `Node.js` · `Codex App Server` · `微信 iLink`

[![GitHub](https://img.shields.io/badge/GitHub-wecode-181717?style=flat-square&logo=github)](https://github.com/jiawei666/wecode)
[![npm](https://img.shields.io/npm/v/%40jiawei666%2Fwecode?style=flat-square&logo=npm&label=npm)](https://www.npmjs.com/package/@jiawei666/wecode)
![Node.js](https://img.shields.io/badge/Node.js-%E2%89%A522-339933?style=flat-square&logo=node.js&logoColor=white)

- **原生会话**：Codex App Server 保存真实的 thread 历史，wecode 只维护本地绑定和运行状态。
- **为移动输入设计**：在微信里发送文字、图片或文件，继续同一台机器上的 Codex 会话。
- **长回答适合手机阅读**：显示原生“正在输入”状态，支持自然语言切换会话，并生成临时的移动端分享页。

[了解 wecode →](https://github.com/jiawei666/wecode) · [npm](https://www.npmjs.com/package/@jiawei666/wecode)

---

### CODESK

**面向 Codex 的三栏终端工作台。**<br>
`2026.10.25` · `Rust` · `Ratatui` · `PTY` · `Codex App Server`

[![npm](https://img.shields.io/npm/v/%40jiawei666%2Fcodesk?style=flat-square&logo=npm&label=npm)](https://www.npmjs.com/package/@jiawei666/codesk)
![Rust](https://img.shields.io/badge/Rust-2024%20edition-000000?style=flat-square&logo=rust&logoColor=white)
![平台](https://img.shields.io/badge/%E5%B9%B3%E5%8F%B0-macOS%20%7C%20Linux%20%7C%20Windows-111111?style=flat-square)

- **原生 Codex，不是套壳**：通过 PTY 承载本机安装的 Codex CLI，保留原有输入、颜色、审批和鼠标协议。
- **会话、文件和 Git 集中在一个窗口**：左侧管理项目会话，中间运行 Codex，右侧查看文件、diff 和受限编辑器。
- **为真实仓库设计**：异步 ripgrep 搜索、语义导航、Git 预览，以及有明确安全边界的工作区编辑器。

[在 npm 查看 →](https://www.npmjs.com/package/@jiawei666/codesk)

---

<div align="center">

<sub>桌面。移动端。终端。同一个 Agent，不同的入口。</sub>

</div>

<div>
  <img src="https://i.loli.net/2020/12/17/RQUBWsvJmx4AhGb.gif" title="山猪" alt="山猪" align="right" style="height:90px;width:100px">
  <img src="https://i.loli.net/2020/12/17/xWpfMuiqKLbTkJS.gif" title="善逸" alt="善逸" align="right" style="height:100px;width:100px">
  <img src="https://i.loli.net/2020/12/17/KCbR5QEWqSuTtc3.gif" title="妹妹" alt="妹妹" align="right" style="height:100px;width:100px">
  <img src="https://i.loli.net/2020/12/17/4xR9G1YlqE5Ibym.gif" title="哥哥" alt="哥哥" align="right" style="height:100px;width:100px">
</div>
