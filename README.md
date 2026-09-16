<div align="center">

# 🗺️ AIPM 入门地图

### 零基础进阶 AI 产品经理的第一站

**概念扫盲 · 方法实操 · 行业坐标 · 职业认知 · 闯关式学习路径**

*不需要先学会训练模型，先建立一套完整的认知地图。*

[![在线访问](https://img.shields.io/badge/在线访问-GitHub%20Pages-brightgreen)](https://sjx-design.github.io/aipm-starter-map/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE)
![内容时效](https://img.shields.io/badge/内容时效-2026--09-orange)
![Pages Build](https://github.com/sjx-design/aipm-starter-map/actions/workflows/deploy.yml/badge.svg)

</div>

---

## 🎯 这个仓库能帮你做什么

> 适合所有想真正搞懂 AI 产品与 AIPM 这个职业的人——零基础入门者、感兴趣的旁观者、考虑转行或跳槽的大厂打工人。沿着站内路线从「听懂黑话」走到「亲手做出作品」，建立完整的认知框架。

- 🌱 **零基础入门？** 从 [概念篇](https://sjx-design.github.io/aipm-starter-map/#/concepts) 开始——每个概念配一个可以复述给别人听的比喻
- 🚀 **考虑入行 / 转行 / 跳槽？** 直接进 [职业篇](https://sjx-design.github.io/aipm-starter-map/#/career)——JD 解读、作品集打法、开放问题思考骨架
- 🛠️ **想动手做项目？** 看 [实操室](https://sjx-design.github.io/aipm-starter-map/#/practice)——从零做一个知识库每日自动质检机器人 MVP，直接成为作品集素材
- 📅 **想要完整计划？** 跟 [闯关式进阶路径](https://sjx-design.github.io/aipm-starter-map/#/roadmap)——五个 Stage 各有过关标准，节奏自己掌握，产出直接变作品集

![站点首页](assets/screenshot-home.png)

## 📖 内容导航

| 板块 | 内容 | 适合谁 |
|------|------|--------|
| 🧠 [概念篇](https://sjx-design.github.io/aipm-starter-map/#/concepts) | Transformer / RAG / Agent / MCP / 评测 / Prompt 注入防御，全部讲成人话 | 补齐技术认知 |
| 🔬 [方法篇](https://sjx-design.github.io/aipm-starter-map/#/methods) | Prompt 工程、知识库搭建与评测、召回率、拒答边界、引用溯源 | 上手实际工作 |
| 🌐 [行业篇](https://sjx-design.github.io/aipm-starter-map/#/industry) | 模型公司格局、Claude Code / Cursor / GPT / GLM 等名词谱系、企业实践水平、前沿难题 | 建立行业坐标 |
| 💼 [职业篇](https://sjx-design.github.io/aipm-starter-map/#/career) | JD 解读、作品集策略、「你怎么评价各家 AI」等开放问题拆解 | 入行 / 转行 / 跳槽 |
| 📅 [学习路径](https://sjx-design.github.io/aipm-starter-map/#/roadmap) | 五 Stage 闯关路径，含任务清单、交付物与自测标准 | 所有新人的第一站 |
| 🧪 [实操室](https://sjx-design.github.io/aipm-starter-map/#/practice) | 完整的自动化场景 MVP：知识库每日质检机器人 | 积累项目经历 |
| 📚 [资源导航](https://sjx-design.github.io/aipm-starter-map/#/resources) | 精选书、课、社区与工具 | 持续学习 |

![概念篇内页](assets/screenshot-concepts.png)

## ✨ 内容特色

- **说人话**：每个概念配比喻和图解——RAG 是「给 AI 配资料柜」、Prompt 注入是「AI 时代的 SQL 注入」
- **PM 视角**：不堆公式，只讲「能做什么、边界在哪、成本如何、产品上怎么用」，以及「学到哪里算够」的深度刹车线
- **学以致用**：概念页附 3 分钟自测表，方法页附排查框架，职业页附开放问题的思考骨架
- **可动手**：实操室给出从语料、评测脚本到报告的完整 MVP 流程，配套开源的 [RAG 评测实验仓库](https://github.com/sjx-design/rag-eval-lab)（私有模板，可 fork 思路）
- **持续更新**：行业篇数据与前沿动态核实至 2026 年 9 月

## 🗺️ 建议使用路径

```
学习路径页（10 分钟，了解全貌）
   ↓
概念篇（建立技术认知，配自测表检验）
   ↓
方法篇 + 实操室（边学边做 MVP）
   ↓
行业篇（持续，培养行业 sense）
   ↓
职业篇（准备入行 / 转行时集中看）
```

## 🛠️ 本地开发

技术栈：React 18 + Vite 5 + Tailwind CSS 3，纯前端静态站点，无后端依赖。

```bash
npm install
npm run dev          # 开发预览，默认 http://localhost:5173
npm run build        # 构建产物输出到 dist/
npm run build:single # 构建单文件离线版到 dist-single/（双击即可打开）
```

仓库已内置 GitHub Actions 工作流，push 到 `main` 后自动部署到 GitHub Pages。

## 💻 在另一台电脑上继续开发

本站没有后端，**Git 仓库就是全部**。换电脑只需四步：

```bash
# 1. 装好 Node.js（>= 18）和 Git，然后克隆
git clone https://github.com/sjx-design/aipm-starter-map.git
cd aipm-starter-map

# 2. 安装依赖，启动开发预览
npm install
npm run dev

# 3. 改完内容后，本地构建 + 导出语料（导出同时是全页渲染自检，8 个 OK 才算过）
npm run build
node scripts/export-md.mjs

# 4. 提交推送（首次 push 需要 Personal Access Token，见下）
git add -A && git commit -m "你的修改说明" && git push origin main
```

push 后 GitHub Actions 会在约 30 秒内自动把 `dist/` 部署上线，无需手动操作。

**首次 push 的认证**：GitHub 已不支持密码 push，需要在 [github.com/settings/tokens/new](https://github.com/settings/tokens/new) 生成一个 classic token（勾选 `repo` 和 `workflow` 两个权限），push 时用户名填 GitHub 用户名、密码栏粘贴 token 即可，系统钥匙串会记住它。

**配套语料仓库**：`scripts/export-md.mjs` 会把 8 个页面导出为 Markdown 到 `../rag-eval-lab/corpus/`（即与本仓库并列的 [rag-eval-lab](https://github.com/sjx-design/rag-eval-lab) 目录）。如果也需要同步语料，把该仓库一并 clone 到同级目录：

```bash
git clone https://github.com/sjx-design/rag-eval-lab.git ../rag-eval-lab
```

## 🤝 参与贡献

- 🐛 发现内容错误或过时的行业信息 → 提 Issue
- ✍️ 有好的概念比喻、问题拆解 → 欢迎 PR
- ⭐ 如果这个仓库帮到了你，点个 Star，让更多转行路上的同学看到它

## 📄 版权说明

本站内容采用 [CC BY-NC-SA 4.0](LICENSE) 协议：允许署名转载与二次创作，禁止商用。代码部分可自由参考。
