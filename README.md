# mvu-studio
A multi-agent 2D vector combat engine powered by MVU architecture with decoupled reach and independentEuclidean combat
# MVU Studio V10.2: Decoupled Reach & Independent Euclidean Combat

A multi-agent 2D vector combat engine powered by the Model-View-Update (MVU) architecture, featuring fully decoupled reach and independent Euclidean combat rules.

---

## Introduction

MVU Studio is an experimental engine designed for LLM-driven generative 2D game loops. It is implemented with zero external dependencies in a pure unidirectional MVU architecture.

### Key Capabilities

* **Three-Tier Multi-Agent Pipeline**:
  * **Agent 1 (Spatial Topology Architect)**: Compiles dynamic terrain zones and obstacle layouts.
  * **Agent 2 (Entity & Action Synthesizer)**: 16k token allocation producing layered SVG entities and dynamic skill FX.
  * **Agent 3 (Combat Rules Evolver)**: Generates and balances independent combat metrics for bosses and players.
* **Decoupled Euclidean Combat**: Attack reach, aggro sensing radius, and movement speeds are evaluated independently with slide collision and anti-stuck fail-safes.
* **Four-Tier Fault-Tolerant JSON Pipeline**: Combines native JSON parsing, trailing comma sanitization, relaxed object evaluation, and stack-balanced bracket healing.
* **Zero Dependencies**: Pure HTML5, SVG, and Vanilla JavaScript inside a single portable runtime.

### Controls

| Key | Action |
| :--- | :--- |
| **W / A / S / D** (or Arrow Keys) | Move Hero Unit |
| **1 / 2 / 3** (or **J / K / L**) | Trigger Action Skills |
| **Tab** | Toggle Inference Control Panel |

---
---

# MVU Studio V10.2：解耦攻击距离与独立欧氏空间战斗引擎

基于 MVU（Model-View-Update）架构与独立欧氏空间几何判定的多智能体 2D 矢量战斗引擎。

---

## 项目介绍

MVU Studio 是一个探索大语言模型驱动 2D 游戏动态世界生成的原型系统。整个项目采用严格的单向数据流 MVU 架构，单文件原生运行，零第三方依赖。

### 核心特性

* **三层 Agent 动态生成管线**：
  * **Agent 1（空间拓扑架构师）**：负责中立活动区域与环境障碍物拓扑编译。
  * **Agent 2（实体与动作合成器）**：16k Token 分配，输出高精度分层矢量实体及动态技能特效。
  * **Agent 3（战斗规则演化器）**：自适应计算数值平衡，解耦对手与玩家的攻防及感知指标。
* **欧氏几何解耦判定**：攻击命中距离、警戒索敌半径与移动速度完全解耦计算，内置多轴滑动与防卡位自动脱困机制。
* **四级容错 JSON 解析管道**：集成原生解析、尾逗号修复、松弛对象反序列化及栈平衡自动括号补全。
* **零依赖纯前端架构**：基于原生 HTML5、SVG 与 Vanilla JavaScript 构建。

### 操作指南

| 键盘按键 | 操作说明 |
| :--- | :--- |
| **W / A / S / D**（或方向键） | 控制英雄单位移动 |
| **1 / 2 / 3**（或 **J / K / L**） | 触发对应槽位的动作技能 |
| **Tab** | 呼出 / 隐藏多智能体推理控制面板 |

#---

## ⚖️ Intellectual Property & Fair Use Disclaimer / 知识产权与合理使用声明

### English
- **Non-Commercial Research & Demonstration**: This project is an academic and technical demonstration of LLM-driven generative vector mechanics and the MVU architectural pattern.
- **Fair Use Notice**: Any visual elements, designs, or naming resembling "Gundam" or related mecha franchises are fan-made procedural tributes created under Fair Use for non-commercial, educational, and technical presentation purposes only.
- **Trademarks**: All copyrights, trademarks, and registered assets of the Gundam franchise remain the exclusive property of **Bandai Namco Holdings Inc.** and **Sotsu / Sunrise**. This project is completely unaffiliated with, unauthorized by, and unendorsed by the original copyright holders.

### 中文
- **非商业研究与技术演示**：本项目系探索大语言模型（LLM）驱动生成式矢量渲染与 MVU 状态架构的个人学术研究与开源技术展示，不含有任何商业营利目的。
- **合理使用（Fair Use）说明**：项目中展示的机甲矢量图形及相关视觉元素仅为个人致敬与算法渲染能力的同人效果演示。
- **商标与版权归属**：所有关于“高达（Gundam）”及相关机甲概念的著作权、商标权及知识产权均归原版权方 **日本万代南梦宫控股（Bandai Namco Holdings Inc.）** 及 **创通 / 日升社（Sotsu / Sunrise）** 完全所有。本项目与原版权方无任何关联、商业合作或授权关系。
# Demo Video / 演示视频
https://github.com/user-attachments/assets/2c93b75e-ead1-4127-973a-df6b53b8390e
---

## 📄 License / 开源许可协议

- **English**: This project is licensed under a **Dual-Licensing Model**. Free for non-commercial, educational, and open-source use under AGPL-3.0. Any commercial use or closed-source integration requires a separate commercial license from the author.
- **中文**: 本项目采用**双重许可协议（Dual-Licensing）**。个人学习、学术研究及非商业开源使用完全免费（遵循 AGPL-3.0 协议）；任何涉及商业盈利、商业闭源集成或收费服务的使用，均须取得原作者的书面商业授权。
