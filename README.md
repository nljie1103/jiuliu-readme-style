<div align="center">

# 🎨 Jiuliu README Style

**让每一份 README，都成为项目的第一张名片。**

从 [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard) 的文档设计出发，  
用统一的视觉语言与灵活的组件系统，写出**中文优先、结构精致、内容可信**的 GitHub 项目首页。

[![Version](https://img.shields.io/badge/JRS-v0.0.2-7356d8?style=for-the-badge)](SKILL.md)
[![Stars](https://img.shields.io/github/stars/nljie1103/jiuliu-readme-style?style=for-the-badge&logo=github&color=f4c542)](https://github.com/nljie1103/jiuliu-readme-style/stargazers)
[![Forks](https://img.shields.io/github/forks/nljie1103/jiuliu-readme-style?style=for-the-badge&logo=github&color=4493f8)](https://github.com/nljie1103/jiuliu-readme-style/forks)

**统一而不雷同 · 丰富而不臃肿 · 美观而不失真**

</div>

---

## 📖 不只是 README 模板

README 是访问者认识开源项目的第一站。它既要让普通用户快速上手，也要让开发者看懂工程结构，还要让部署者知道数据保存在哪里、有哪些安全限制。

**Jiuliu README Style（JRS）** 是一份可以交给 AI 编程助手执行的单文件 Skill：以 JIE-Clipboard 的页面美学为基准，先理解真实项目，再从组件库中**选择、组合、排版**合适的区域，而不是把固定模板逐项填满。

> **设计原则：** 统一的是视觉与质量，不是把每个项目写成相同长度、相同章节的说明书。

---

## ✨ 它能做什么

| 设计能力 | 实际作用 |
|:---|:---|
| 🎨 **统一视觉语言** | 居中 Hero、协调徽章、Emoji 标题、清晰分隔与克制留白 |
| 🧩 **自由组合模块** | 从多类别组件中选择适合项目的内容，不生成空章节 |
| 🏗️ **深入技术表达** | 支持项目结构、技术栈、架构、数据存储、API、测试与部署说明 |
| 🧭 **四级约束机制** | 明确必须、条件必须、可选与禁止，兼顾完整性和简洁感 |
| 🛡️ **事实和安全优先** | 不虚构功能、版本、截图、测试结果、许可证或安全能力 |
| 🇨🇳 **中文优先** | 以中文 README 为首页，需要时同步维护真实的英文文档 |

---

## 🧱 有规则，也有自由

不是所有模块都必须出现。JRS 会先评估项目的规模、能力、目标读者和风险，再为每个区域确定优先级。

| 等级 | 含义 | 典型情况 |
|:---|:---|:---|
| **MUST** | 每个正常项目都需要 | 项目身份、核心用途、明确的开始入口 |
| **CONDITIONAL** | 满足条件就需要 | 有删除风险则说明安全边界，有持久化数据则说明相关存储与保留要求 |
| **OPTIONAL** | 有价值才添加 | 截图、技术栈、项目结构、架构图、FAQ、贡献指南 |
| **FORBIDDEN** | 无论项目类型都禁止 | 假功能、死链、空章节、无意义徽章、虚构许可证 |

**复杂项目可以很完整，简单项目也应该足够简洁。** 这两件事并不矛盾。

---

## 🧩 丰富的 README 组件库

JRS v0.0.2 内置 **47 个候选模块**，分为六组。它们是可使用的积木，而不是每个 README 的必填清单。

| 组件类别 | 典型区域 | 组合思路 |
|:---|:---|:---|
| 🎨 **品牌与导航** | 项目 Hero、徽章、语言切换、目录、重要提示 | 让访问者迅速辨认项目 |
| ✨ **产品与功能** | 项目概述、功能特性、核心优势、截图、演示、使用场景 | 先说明价值，再展示体验 |
| 🚀 **安装与使用** | 系统要求、下载、快速开始、使用指南、命令、配置、环境变量 | 降低第一次使用的门槛 |
| 🏗️ **工程技术** | 技术栈、项目结构、系统架构、数据存储、数据模型、API、测试 | 帮助开发者理解真实实现 |
| 🚢 **部署与运维** | 部署、服务管理、日志、安全、备份、更新、迁移、故障排查 | 让服务更易于维护 |
| 🤝 **维护与社区** | 兼容性、FAQ、路线图、更新记录、贡献、许可、致谢、反馈 | 说明项目现状与协作方式 |

完整的选用条件、布局样式和检查要求，均写在 **[SKILL.md](SKILL.md)** 中。

---

## 🛠️ 技术内容，也可以很优美

下面是三种常见工程组件的**排版示例**。这些技术与数据均为教学演示，不代表本仓库使用了数据库或运行服务。

### 技术栈 · 信息清楚，不堆技术名词

| 层级 | 示例技术 | 示例用途 |
|:---|:---|:---|
| 前端 | Vue | 交互界面 |
| 服务端 | FastAPI | 业务接口 |
| 数据库 | SQLite | 本地数据持久化 |

### 项目结构 · 只展示关键目录

```text
example-project/          # 示例项目（非本仓库）
├── frontend/              # 用户界面
├── backend/               # 业务服务
├── tests/                 # 自动化测试
└── README.md              # 项目入口
```

### 数据存储 · 说明数据去向与用途

| 示例数据类型 | 示例存储方式 | 示例说明 |
|:---|:---|:---|
| 用户配置 | JSON 文件 | 保存本地设置 |
| 业务记录 | SQLite | 持久化数据 |
| 临时数据 | 缓存目录 | 可重新生成的文件 |

这些组件**只会在真实项目确实有相应内容时出现**；尤其是路径、保留期限、加密方式和备份机制，必须依据项目代码核实。

---

## 🧭 不同项目，自然适配

| 项目类型 | 更值得优先呈现的区域 |
|:---|:---|
| 🖥️ **桌面应用** | 核心功能、安装、真实界面、快捷键、项目结构、数据存储 |
| ⌨️ **命令行工具** | 快速开始、参数说明、权限要求、安全边界、恢复方式 |
| 🌐 **Web / 自托管** | 技术架构、配置、数据存储、部署、升级、备份与网络安全 |
| 📦 **库 / SDK** | 安装方式、最小示例、API、兼容范围、测试与源码构建 |
| 📚 **学习 / 衍生项目** | 学习目标、上游来源、修改范围、技术说明与授权边界 |

> 没有 GUI，就不必硬放截图；没有数据库，就不要写数据模型；有真实数据删除风险，就不能为了美观省略警告。

---

## 📥 快速开始

本仓库只需要一个 `SKILL.md`，无需脚本、构建或额外依赖。将它放进 AI 编程助手的 Skill 目录即可；以下为 Codex 用户级安装示例。

### Windows · PowerShell

```powershell
$dir = Join-Path $HOME '.agents\skills\jiuliu-readme-style'
New-Item -ItemType Directory -Force -Path $dir | Out-Null
Invoke-WebRequest 'https://raw.githubusercontent.com/nljie1103/jiuliu-readme-style/main/SKILL.md' -OutFile (Join-Path $dir 'SKILL.md')
```

### macOS / Linux

```bash
mkdir -p ~/.agents/skills/jiuliu-readme-style
curl -fL 'https://raw.githubusercontent.com/nljie1103/jiuliu-readme-style/main/SKILL.md' \
  -o ~/.agents/skills/jiuliu-readme-style/SKILL.md
```

安装后，可在 Codex 中直接调用：

```text
$jiuliu-readme-style
检查当前仓库的真实功能、技术栈、项目结构和数据存储，
按需组合 README 组件，中文优先，保持统一的视觉风格。
不要生成空章节，不要编造功能、链接或技术细节。
```

安装前也可以直接阅读 [Skill 完整规范](SKILL.md)；若未立即识别，可重新启动 Codex 会话。其他 AI 编程助手能否自动发现该文件，取决于各自的 Skill 机制。

---

## 📁 两个文件，刚刚好

```text
jiuliu-readme-style/
├── README.md      # 项目介绍，也是设计风格的实际展示
└── SKILL.md       # 完整的单文件设计与执行规范
```

没有附加模板、脚本或配置目录。**README 负责展示，SKILL 负责定义。**

---

## 🔖 版本记录

| 版本 | 内容 |
|:---|:---|
| **v0.0.2** | 新增四级组件规范、47 个模块的组件库、展示形式规则与动态组合流程 |
| v0.0.1 | 首次发布 JIE-Clipboard 风格的 README Skill |

版本号仅随 **Skill 规范的实质更新**递增；发布脚本或上传流程的修复不构成新版本。

---

## 🌍 English · At a Glance

**Jiuliu README Style (JRS)** is a Chinese-first, modular README design skill inspired by [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard). Its component library and four-level rules help AI coding assistants build readable, accurate GitHub project pages tailored to each repository—not copy a fixed template.

The repository contains only this showcase `README.md` and the [complete `SKILL.md`](SKILL.md).

---

## 🙏 灵感与致谢

- **视觉原点：** [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard)
- **项目维护：** [nljie1103](https://github.com/nljie1103)

> **授权说明：** 本仓库目前未声明开源许可证。可公开阅读不等于自动获得复制、修改或再分发的许可；是否开放这些权限应由维护者明确决定。

---

<div align="center">

**Made with ❤️ by [nljie1103](https://github.com/nljie1103)**

*让每个认真做出来的项目，也拥有值得认真阅读的首页。*

如果你喜欢这套规范，欢迎点亮 ⭐ **Star**。

</div>
