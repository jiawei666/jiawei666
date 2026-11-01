<div align="center">

# 袁嘉炜 · beConfident

**Go 后端工程师 / AI Agent 开发者**

9 年服务端研发经验，关注 Agent Runtime、Local-first 工具与 Coding Agent 的产品化。

[GitHub](https://github.com/jiawei666) · [Email](mailto:beconfident666@gmail.com)

![Go](https://img.shields.io/badge/Go-Backend-00ADD8?style=flat-square&logo=go&logoColor=white)
![AI Agent](https://img.shields.io/badge/AI-Agent-111111?style=flat-square)
![Local-first](https://img.shields.io/badge/Local--first-Enabled-2ea44f?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

</div>

---

## 最近在做

我正在把 Coding Agent 从命令行带进三个不同的工作场景：

- **桌面**：Rambo，一台长期待在本机的个人 Agent
- **移动端**：wecode，在微信里继续使用本机 Codex
- **终端**：CODESK，把会话、代码与 Git 变更收进同一个工作台

> 我关注的是 Local-first、可组合的工具权限、原生 Agent 会话，以及真正能进入日常工作流的交互方式。

## 精选项目

### 01 · [Rambo](https://github.com/jiawei666/Rambo) <sub>`2026.10.31`</sub>

> **一台真正待在自己 Mac 上的个人 AI Agent。**

[![GitHub](https://img.shields.io/badge/GitHub-Rambo-181717?style=flat-square&logo=github)](https://github.com/jiawei666/Rambo)
[![Latest Release](https://img.shields.io/github/v/release/jiawei666/Rambo?style=flat-square&label=release)](https://github.com/jiawei666/Rambo/releases/latest)
![Platform](https://img.shields.io/badge/platform-macOS%20arm64-111111?style=flat-square)
![License](https://img.shields.io/github/license/jiawei666/Rambo?style=flat-square)

**为什么做它**

Rambo 不是为了再做一个浏览器里的聊天框，而是把 Codex App Server 接成一个长期运行在本机、拥有独立记忆和工具权限的个人助手。

**项目亮点**

- **Local-first**：Bot、聊天、Routine、设置和记忆全部保存在本机，并通过隔离的 Codex Home 管理运行时。
- **多 Bot 协作**：每个 Bot 保留各自的上下文、模型、Skills、MCP、Apps 和 Plugins，同时可以在群聊中协作。
- **主动执行**：支持用自然语言创建一次性或周期 Routine，包含提醒、执行历史、重试和补跑。
- **连接真实应用**：接入 QQ 邮箱、Gmail、微信以及电脑/浏览器自动化能力，并按 Bot 独立授权。
- **完整交互面**：实时语音、文件预览、代码高亮、Mermaid、结构化结果卡和 MCP 内容共用一套聊天工作区。

**技术栈**<br>
`Electron` · `React` · `TypeScript` · `Codex App Server` · `MCP` · `Skills`

**入口**<br>
[GitHub](https://github.com/jiawei666/Rambo) · [最新 Release](https://github.com/jiawei666/Rambo/releases/latest)

---

### 02 · [wecode](https://github.com/jiawei666/wecode) <sub>`2026.10.28`</sub>

> **在微信里，继续使用本机 Codex。**

[![GitHub](https://img.shields.io/badge/GitHub-wecode-181717?style=flat-square&logo=github)](https://github.com/jiawei666/wecode)
[![npm](https://img.shields.io/npm/v/%40jiawei666%2Fwecode?style=flat-square&logo=npm&label=npm)](https://www.npmjs.com/package/@jiawei666/wecode)
![Node.js](https://img.shields.io/badge/Node.js-%E2%89%A522-339933?style=flat-square&logo=node.js&logoColor=white)
![License](https://img.shields.io/github/license/jiawei666/wecode?style=flat-square)

**为什么做它**

离开电脑后，Coding Agent 不应该只能停在那里。wecode 把微信变成本机 Codex 的远程入口，同时保留 Codex 原生会话历史。

**项目亮点**

- **原生会话，不是另一套聊天记录**：Codex App Server 保存原生 threads，wecode 只维护本地绑定和运行状态。
- **自然语言会话管理**：通过“小微”列出最近会话、按项目查找或新建会话，并兼容多种语音同音词。
- **真正移动端输入**：微信图片直接作为 Agent 图片输入，文件下载到本机后把路径交给当前会话。
- **长任务反馈**：执行期间显示微信原生“正在输入”，长回答自动生成适合手机阅读的临时分享页。
- **完整后台生命周期**：支持登录、重启、状态、日志和停止；通过 npm 分发并可在本机后台运行。

**技术栈**<br>
`TypeScript` · `Node.js` · `Codex App Server` · `微信 iLink` · `Cloudflare Tunnel`

**入口**<br>
[GitHub](https://github.com/jiawei666/wecode) · [npm](https://www.npmjs.com/package/@jiawei666/wecode) · [Release](https://github.com/jiawei666/wecode/releases/latest)

---

### 03 · CODESK <sub>`2026.10.25`</sub>

> **为 Codex 打造的三栏终端工作台。**

[![npm](https://img.shields.io/npm/v/%40jiawei666%2Fcodesk?style=flat-square&logo=npm&label=npm)](https://www.npmjs.com/package/@jiawei666/codesk)
![Rust](https://img.shields.io/badge/Rust-2024%20edition-000000?style=flat-square&logo=rust&logoColor=white)
![Ratatui](https://img.shields.io/badge/TUI-Ratatui-5e5086?style=flat-square)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux%20%7C%20Windows-111111?style=flat-square)

**为什么做它**

Coding Agent 越来越像一个持续工作的开发搭档，但会话、代码和 Git 变更仍散落在不同窗口。CODESK 把它们收进一个终端工作台。

**项目亮点**

- **保留 Codex 原生体验**：通过 PTY 承载本机 Codex CLI，不重编译也不嵌入，保留输入、颜色、审批和鼠标协议。
- **三栏并行**：左侧项目与会话，中间原生 Codex，右侧文件树、Git changes、diff 和受限编辑器。
- **面向大仓库的检索**：后台 ripgrep 搜索会取消旧任务、流式返回结果，不阻塞正在运行的 Agent。
- **语义代码导航**：为 Go、Python、JavaScript/TypeScript 和 Vue 接入语言服务，支持定义/引用跳转和前进后退。
- **明确的安全边界**：编辑器限制在当前工作区，拒绝符号链接、二进制和超大文件，保存前检测磁盘快照。

**技术栈**<br>
`Rust` · `Ratatui` · `PTY` · `Codex App Server` · `ripgrep` · `Language Server`

**快速开始**

```bash
npm install -g @jiawei666/codesk
codesk
```

**入口**<br>
[npm](https://www.npmjs.com/package/@jiawei666/codesk)

---

<div align="center">

**桌面、移动端、终端，三条路径，同一个目标：让 Agent 真正参与日常开发。**

[GitHub](https://github.com/jiawei666) · [Email](mailto:beconfident666@gmail.com)

</div>
