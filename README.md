<div align="center">

# 🎨 Jiuliu README Style

**让每一份 README，都成为项目的第一张名片。**

以 [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard) 的文档美学为原点，
为 GitHub 项目打造 **中文优先、视觉统一、内容可信** 的 README。

[![Stars](https://img.shields.io/github/stars/nljie1103/jiuliu-readme-style?style=for-the-badge&logo=github&color=f4c542)](https://github.com/nljie1103/jiuliu-readme-style/stargazers)
[![Forks](https://img.shields.io/github/forks/nljie1103/jiuliu-readme-style?style=for-the-badge&logo=github&color=4493f8)](https://github.com/nljie1103/jiuliu-readme-style/forks)
[![AI Skill](https://img.shields.io/badge/AI%20Skill-JRS-3fb950?style=for-the-badge&logo=markdown)](SKILL.md)

**简洁而不简陋 · 美观而不失真 · 统一而不雷同**

</div>

---

## 📖 为什么做这个 Skill

一个好的 README，不只是告诉别人「项目能做什么」，更应该让访客在短时间内看懂：**这是什么、为什么值得关注、如何开始使用，以及有哪些限制。**

**Jiuliu README Style（JRS）** 将这套设计语言整理为可重复使用的 AI Skill。无需复制整份模板，只需让支持 Skill 的编程助手读取规范，就能按照项目的真实内容创建、重构或维护 README。

> **设计理念：** 把 README 当成产品首页来设计，把准确性当成不可妥协的底线。

---

## ✨ 它能做什么

| 设计能力 | 实际效果 |
|:---|:---|
| 🎨 **统一视觉语言** | 居中首屏、统一徽章、Emoji 标题、清晰分隔和适度留白 |
| 🇨🇳 **中文优先表达** | 主 README 使用简体中文；需要双语时提供独立英文版 |
| 🧭 **先用户后开发者** | 功能和快速开始优先，构建、配置与原理按需展开 |
| 🧩 **按项目类型适配** | GUI、CLI、Web、自托管服务、库与学习项目不生搬硬套 |
| 🛡️ **事实与安全优先** | 不杜撰功能、版本、截图、许可证、测试结果或安全承诺 |
| ✍️ **持续保持一致** | 新建文档、发布更新、结构调整都沿用相同的规范 |

---

## 🎨 一眼认出的设计语言

不是堆砌 Emoji 或徽章，而是让每个元素都有明确的位置与作用。

| 页面位置 | JRS 的排版约定 |
|:---|:---|
| **顶部 Hero** | 居中项目名 + 一句话价值主张 + 简短说明 |
| **状态徽章** | 统一 `for-the-badge`，只展示真实、有效的信息 |
| **功能介绍** | 用精炼的双列表格，让价值一眼可见 |
| **快速开始** | 提供尽量少、且实际可执行的安装与使用步骤 |
| **核心章节** | `## ✨` 风格的二级标题，章节之间用 `---` 分隔 |
| **技术信息** | 代码块标明语言，项目树只保留关键目录 |
| **页面结尾** | 如实说明授权与来源，适度署名，不重复营销 |

**这份 README 本身，就是 JRS 风格的一次实际展示。**

---

## 📥 快速开始

本仓库只包含两个 Markdown 文件。Skill 的所有规则集中在一个文件里，没有额外脚本、依赖或复杂目录。

### Windows · 安装到 Codex 用户级 Skills

在 **PowerShell** 中运行以下命令：

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

> **无需重命名：** 仓库直接使用 Codex 标准文件名 `SKILL.md`，安装时原名保存即可。安装前可先阅读 [Skill 原文](SKILL.md)。若 Skill 未立即出现，可重新启动 Codex。

### 这样调用

安装后，在 Codex 中输入：

```text
$jiuliu-readme-style
请根据当前仓库的真实代码、构建和发布信息，重构 README.md。
参考 JIE-Clipboard 的视觉风格，中文优先，整体精致、克制、统一。
保留必要的安装说明、安全警告、授权信息；不要编造不存在的功能。
```

也可直接把 [Skill 文件](SKILL.md) 交给其他能够读取 Markdown 指令的 AI 编程助手使用；是否支持自动发现取决于各工具自身的规则。

---

## 🧩 不同项目，一致气质

| 项目类型 | README 优先展示什么 |
|:---|:---|
| 🖥️ **桌面应用** | 核心功能、下载方式、真实截图、快捷键与系统要求 |
| ⌨️ **命令行工具** | 使用场景、可复制命令、参数说明、权限与风险 |
| 🌐 **Web / 自托管** | 功能、部署入口、配置要求、升级备份与安全事项 |
| 📦 **开源库 / SDK** | 安装方式、最小示例、API 入口与支持版本 |
| 📚 **学习 / 衍生项目** | 上游来源、修改范围、构建方式与授权边界 |

统一的是**阅读体验与视觉秩序**，不是千篇一律的章节清单。

---

## 📁 两个文件，刚刚好

```text
jiuliu-readme-style/
├── README.md                       # 项目首页，也是风格展示
└── SKILL.md     # 完整、独立、可安装的 Skill 规范
```

不附加不必要的模板目录、配置文件或工具脚本，让读者能直接看到最重要的内容。

---

## 🔒 有些原则，比美观更重要

- **不编造：** 没有依据的功能、性能数据、兼容性、版本或测试结果，绝不写成事实。
- **不遮掩：** 涉及删除、权限、数据、网络暴露或安全风险，必须在操作前明确说明。
- **不误导：** 不存在的 Release、截图、许可证或演示链接不应出现。
- **不越界：** 美化 README 不等于随意修改源代码或自动推送；以用户授权范围为准。

---

## 🌍 English · At a Glance

**Jiuliu README Style (JRS)** is a minimal, Chinese-first README design skill inspired by [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard). It helps AI coding assistants write polished, consistent, and trustworthy GitHub project pages—without forcing every project into the same structure.

The repository contains only this showcase README and the [complete skill specification](SKILL.md). Place `SKILL.md` in your agent's skill directory.

---

## 🙏 灵感与致谢

- **风格起点：** [JIE-Clipboard](https://github.com/nljie1103/JIE-Clipboard)
- **项目维护：** [nljie1103](https://github.com/nljie1103)

> **授权说明：** 此仓库目前未声明开源许可证。公开可阅读不等于自动获得复制、修改或再分发的许可；如需开放这些权限，应另行明确授权。

---

<div align="center">

**Made with ❤️ by [nljie1103](https://github.com/nljie1103)**

*让优秀的项目，也拥有值得认真阅读的首页。*

如果这套规范对你有帮助，欢迎点亮 ⭐ **Star**。

</div>
