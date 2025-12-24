<div align="center">

# 🌊 易 · 生存哲学交互系统
### Yi: The Philosophy of Survival & Resilience

> **"生生之谓易"** —— 在毁灭性的变局中，建立反脆弱的生存机制。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tech Stack](https://img.shields.io/badge/Tech-Tailwind%20%7C%20Chart.js-blue)]()
[![Build Status](https://img.shields.io/badge/Status-Live-green)]()

[**🚀 立即体验交互系统 (Live Demo)**](https://drkangcode.github.io/yi-philosophy-website/)

</div>

---

## 📖 项目简介 (Introduction)

本项目是一个**单页面交互式网络应用 (SPA)**，旨在通过现代数据可视化技术，解构《周易》中深奥的生存哲学。

我们不谈玄学，而是将“易”视为一套**动态的算法**。在充满不确定性（熵增）的系统中，本项目模拟了生命体如何通过“非常道”（非线性策略）来对抗外部冲击，从而实现“生生不息”。

### 核心探究问题：
1.  **生存基线**：在环境剧烈震荡时，为何有的系统崩溃，有的系统反而更强？
2.  **非常道**：常规逻辑（常道）失效时，如何启动应急与再生机制？
3.  **生机量化**：如何用数据直观呈现“生机（Vitality）”的保存与增强？

---

## ⚡️ 核心功能与交互 (Features)

本项目包含三个高度耦合的交互模块，分别对应认知的三个层面：

### 1. 📊 变局分析仪表盘 (The Resilience Dashboard)
* **可视化引擎**：基于 `Chart.js` 的动态折线图。
* **交互逻辑**：拖动滑块调整“变局烈度（Chaos Level）”。
* **观察点**：直观对比“普通系统”随环境恶化而衰减，与“易之系统”在动荡中维持动态平衡的差异。

### 2. 🕸 策略维度雷达 (Strategy Radar)
* **可视化引擎**：交互式雷达图。
* **数据对比**：
    * 🔴 **常规系统**：侧重刚性结构、资源消耗。
    * 🟢 **易之系统**：侧重灵活性、再生力、预见性。
* **核心洞察**：展示了“柔弱胜刚强”的数据化解释。

### 3. 🎮 生存模拟实验室 (Survival Simulation)
* **交互引擎**：原生 JS 编写的状态机。
* **玩法**：你将扮演系统管理者。
    * ⚠️ **遭遇**：外部冲击（Shock）、结构崩塌（Collapse）。
    * 🛡 **应对**：使用“变通（Adapt）”回避伤害，使用“生生（Regenerate）”重塑根基。
* **目标**：在能量耗尽前，领悟“易”的生存节奏。

---

## 🛠 技术架构 (Tech Stack)

本项目追求**极简主义**与**高性能**，无复杂的构建流程，开箱即用。

* **Core**: HTML5 + Vanilla JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN加载，无需编译)
* **Visualization**: [Chart.js](https://www.chartjs.org/) (Canvas 渲染)
* **Typography**: Noto Serif SC (Google Fonts) 营造东方学术美感

```text
.
├── index.html       # 核心入口（包含所有逻辑、样式与结构）
├── README.md        # 项目说明文档
└── LICENSE          # MIT 开源协议