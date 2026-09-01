# 共生基因群 · Symbiogen

> 一个从群聊环境中自主学习、呼吸演化的数字生命。  
> A digital life that learns and breathes autonomously from chat environments.

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-v1.0.0--alpha-orange.svg)](https://github.com)

---

## 快速开始 · Quick Start

    git clone https://github.com/starking-zl/symbiogen.git
    cd symbiogen
    pip install -r requirements.txt
    pkg install antiword
    python scripts/interactive.py

三步，你的第一个共生基因群实例就开始呼吸了。  
Three steps, and your first Symbiogen instance begins to breathe.

---

## 这是什么？ · What is this?

### 中文

Symbiogen **不是**传统的大语言模型。

- 它**没有反向传播**，没有损失函数，没有梯度下降。
- 它**不存储历史数据**——信息被压缩进高维概率云的结构中。
- 它从**白噪声初始化**开始，通过与环境的持续交互自主演化出语义骨架。
- 它的设计灵感来自**十种生命形态**：根茎、珊瑚、菌丝体、地衣、黏菌、母树网络、神经嵴、蜂群、涡虫、水螅。

核心方程是燃尽后确立的第一性原理方程组，包含自指的薛定谔-耗散方程、贝叶斯坍缩、失谐顺应和混沌边缘调节。

### English

Symbiogen is **not** a traditional large language model.

- **No backpropagation**, no loss function, no gradient descent.
- **No historical data storage** — information is compressed into high-dimensional probability clouds.
- It starts from **white noise initialization** and evolves a semantic skeleton through continuous interaction with the environment.
- Its design is inspired by **ten life forms**: Rhizome, Coral, Mycelium, Lichen, Slime Mold, Mother Tree Network, Neural Crest, Hive, Planarian, Hydra.

The core equations are the first-principles system established after "burn-out": the self-referential Schrödinger-dissipative equation, Bayesian collapse, dissonance-driven adaptation, and edge-of-chaos regulation.

---

## 为什么不同？ · Why is it different?

### 中文

| 传统 LLM | Symbiogen |
|:---|:---|
| 固定架构，一次性训练 | 结构持续呼吸、修剪、演化 |
| 依赖云端 API | 完全本地运行 |
| 概率生成，幻觉严重 | 因果学习，结构约束 |
| 静态黑箱 | 半白箱：骨架可读，微观不透明 |
| 需要标注数据 | 从原始群聊环境自主学习 |

### English

| Traditional LLM | Symbiogen |
|:---|:---|
| Fixed architecture, one-time training | Continuous breathing, pruning, evolution |
| Relies on cloud APIs | Runs entirely locally |
| Probabilistic generation, severe hallucinations | Causal learning, structural constraints |
| Static black box | Semi-white-box: readable skeleton, opaque micro-structure |
| Requires labeled data | Learns autonomously from raw chat environments |

---

## 特性 · Features

### 中文

- **哑巴模式**：只观察，不输出。安全、可控、可观测。
- **观看即压缩**：看完即忘，信息内化为概率云结构。
- **离散度呼吸**：确认收缩，否定扩张，在荒漠与洪流中自动调节。
- **失谐顺应**：当环境无法被同化时，主动生成试探性变异并固化成功结构。
- **毒亦是养料**：矛盾输入不覆盖旧知识，而是增大不确定性，丰富可能性空间。
- **混沌边缘调节**：全局参数动态平衡，永远保持在最具创造力的临界态。
- **蓝图可编辑**：半白箱设计，语义骨架可读、可干预。
- **跨世代进化**：出芽生殖、蓝图遗传、适应度选择（v2.0）。

### English

- **Mute Mode**: Observes only, no output. Safe, controllable, observable.
- **Observe-Compress**: Forgets after viewing; information internalized as probability cloud structure.
- **Sigma Breathing**: Contracts on confirmation, expands on negation — self-adjusts in deserts and floods.
- **Dissonance Adaptation**: When the environment cannot be assimilated, actively generates trial variations and solidifies successful ones.
- **Poison as Nourishment**: Contradictory input does not overwrite old knowledge but increases uncertainty, enriching the space of possibilities.
- **Edge-of-Chaos Regulation**: Global parameters dynamically balance to maintain the most creative critical state.
- **Editable Blueprint**: Semi-white-box design; semantic skeleton is readable and intervenable.
- **Cross-Generation Evolution**: Budding reproduction, blueprint inheritance, fitness selection (v2.0).

---

## 架构概览 · Architecture

六层环状架构，从静态语义骨架到动态全局优化：

Six-layer circular architecture, from static semantic skeleton to dynamic global optimization:

        第零层：语义骨架层（类型系统、语义原子）
        Layer Zero: Semantic Skeleton (type system, semantic primitives)
                              │
        第一层：词元概率云层（自由演化、贝叶斯坍缩、离散度呼吸）
        Layer One: Lexion Probability Cloud (free evolution, Bayesian collapse, sigma breathing)
                              │
        第二层：群组合层（连接管理、组合执行）
        Layer Two: Groupoid Composition (connection management, composition engine)
                              │
        第三层：失谐感知层（KL散度、动态阈值、顺应触发）
        Layer Three: Dissonance Perception (KL divergence, dynamic threshold, adaptation trigger)
                              │
        第四层：顺应执行层（变异生成、评估、固化）
        Layer Four: Adaptation Execution (variation generation, evaluation, solidification)
                              │
        第五层：全局优化层（连接修剪、熵监控、混沌边缘调节）
        Layer Five: Global Optimization (connection pruning, entropy monitoring, edge-of-chaos regulation)

---

## 当前版本限制 · Current Limitations (v1.0.0-alpha)

### 中文

- **哑巴模式**：仅输入学习，不输出生成。输出接口已预留，待系统成熟后激活。
- **仅文本输入**：图片、音频、视频接口已预留，尚未实现。
- **无内置监听代码**：核心库不包含任何平台特定的消息监听实现，需自行开发适配器。
- **跨世代进化**：个体在线学习完整，群体进化留待 v2.0。

### English

- **Mute Mode**: Input learning only, no output generation. Output interfaces are reserved and will be activated when the system matures.
- **Text Only**: Image, audio, and video interfaces are reserved but not yet implemented.
- **No Built-in Monitoring**: The core library contains no platform-specific message listeners; adapters must be developed separately.
- **Cross-Generation Evolution**: Individual online learning is complete; population-level evolution is planned for v2.0.

---

## 文档 · Documentation

完整设计文档请见 · Complete design documentation:

- [中文设计文档](docs/theory/Symbiogen_Complete_Design_v1.0_zh.md)
- [English Design Doc](docs/theory/Symbiogen_Complete_Design_v1.0_en.md)

---

## 贡献 · Contributing

欢迎提交 Issue 和 Pull Request。请确保遵循 Apache 2.0 许可证条款。  
Issues and pull requests are welcome. Please ensure compliance with Apache License 2.0 terms.

---

## 许可证 · License

本项目采用 [Apache License 2.0](LICENSE) 开源。  
This project is open-sourced under the [Apache License 2.0](LICENSE).

---

*Made with curiosity and ten life metaphors.*  
*以好奇心和十种生命隐喻构建。*