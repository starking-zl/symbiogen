# 共生基因群 · Symbiogen

> 一个能从群聊环境中自主生长出通用语言骨架的数字生命。  
> A digital life form that autonomously grows a universal language skeleton from chat environments.

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)  
[![Status](https://img.shields.io/badge/Status-v1.0.0--alpha-orange.svg)](https://github.com)

---

## 快速开始 · Quick Start

    git clone https://github.com/starking-zl/symbiogen.git
    cd symbiogen
    pip install -r requirements.txt
    python scripts/init_colony.py

3 步，你的第一个共生基因群实例就开始演化了。  
3 steps and your first Symbiogen instance begins to evolve.

---

## 这是什么？ · What is this?

### 中文

Symbiogen **不是**传统的大语言模型。

- 它**没有反向传播**，没有损失函数，没有梯度下降。
- 它**不存储历史数据**——信息被压缩进高维流形的曲率结构中。
- 它从**白噪声初始化**开始，通过环境交互自主演化出语义骨架。
- 它的设计灵感来自**十种生命形态**：根茎、珊瑚、菌丝体、地衣、黏菌、母树网络、神经嵴、蜂群、涡虫、水螅。

核心方程是一项跨学科的原创综合：

∂R/∂t = α·(∇²R) + β·(J ⊗ J) - γ·(R - R₀) + δ·ξ - ε·Tr(R)·R

该方程融合了微分几何中的里奇流理论（曲率扩散）、神经科学中的赫布学习法则（J ⊗ J 刻蚀）、计算神经科学中的突触巩固机制（R - R₀ 回归）以及随机动力学与生态学约束（ξ 涨落与资源衰减）。它不是任何单一现有模型的复现，而是为构建具有自主学习、记忆与演化能力的数字生命体提出的统一数学框架。

### English

Symbiogen is **not** a traditional large language model.

- **No backpropagation**, no loss function, no gradient descent.
- **No historical data storage** — information is compressed into the curvature structure of a high-dimensional manifold.
- It starts from **white noise initialization** and autonomously evolves a semantic skeleton through environmental interaction.
- Its design is inspired by **ten life forms**: Rhizome, Coral, Mycelium, Lichen, Slime Mold, Mother Tree Network, Neural Crest, Hive, Planarian, Hydra.

The core equation is an original transdisciplinary synthesis:

∂R/∂t = α·(∇²R) + β·(J ⊗ J) - γ·(R - R₀) + δ·ξ - ε·Tr(R)·R

It integrates Ricci flow from differential geometry (curvature diffusion), Hebbian learning from neuroscience (J ⊗ J etching), synaptic consolidation from computational neuroscience (R - R₀ regression), and stochastic dynamics with ecological constraints (ξ fluctuation and resource decay). It is not a reproduction of any single existing model, but a unified mathematical framework for constructing digital life forms capable of autonomous learning, memory, and evolution.

---

## 为什么不同？ · Why is it different?

### 中文

| 传统 LLM | Symbiogen |
|:---|:---|
| 固定架构，一次性训练 | 结构持续生长、修剪、演化 |
| 依赖云端 API | 完全本地运行 |
| 概率生成，幻觉严重 | 因果学习，结构约束 |
| 静态黑箱 | 半白箱：骨架可读，微观不透明 |
| 需要标注数据 | 从原始群聊环境自主学习 |

### English

| Traditional LLM | Symbiogen |
|:---|:---|
| Fixed architecture, one-time training | Continuous growth, pruning, evolution of structure |
| Relies on cloud APIs | Runs entirely locally |
| Probabilistic generation, severe hallucinations | Causal learning, structural constraints |
| Static black box | Semi-white-box: readable skeleton, opaque micro-structure |
| Requires labeled data | Learns autonomously from raw chat environments |

---

## 特性 · Features

### 中文
- **哑巴模式**：只观察，不输出。安全、可控、可观测。
- **观看即压缩**：看完即忘，信息内化为曲率场的几何结构。
- **碎片再生**：任何碎片都可重建完整个体（涡虫机制）。
- **出芽生殖**：成熟模块可分离为独立新个体（水螅机制）。
- **生命体征仪表盘**：7 个序参量实时监控系统健康。
- **蓝图可编辑**：半白箱设计，人类可读、可干预语义骨架。
- **跨世代进化**：支持出芽、突变、选择，蓝图场可跨代遗传。

### English
- **Mute Mode**: Observes only, no output. Safe, controllable, observable.
- **Observe-Compress**: Forgets after viewing; information is internalized as geometric structure.
- **Fragment Regeneration**: Any fragment can rebuild a complete individual (Planarian mechanism).
- **Budding Reproduction**: Mature modules can detach as independent new individuals (Hydra mechanism).
- **Vital Signs Dashboard**: 7 order parameters for real-time health monitoring.
- **Editable Blueprint**: Semi-white-box design; human-readable and intervenable semantic skeleton.
- **Cross-Generation Evolution**: Supports budding, mutation, selection, and heritable blueprint field.

---

## 架构概览 · Architecture

五层环状架构，通过曲率场原语操作高维流形：  
Five-layer circular architecture operating on a high-dimensional manifold via curvature field primitives:

        刻蚀层 (Etching) ←→ 扩散层 (Diffusion)
           ↖                  ↗
             ↘              ↙
        回归层 (Regression) ←→ 涨落层 (Fluctuation)
           ↗                  ↖
        时间层 (Time Layer) 调度所有层

---

## 使用方法 · Usage

    from symbiogen import SymbiogenColony

    # 创建实例
    colony = SymbiogenColony(dimension=128, config={"initial_particles": 200})

    # 观察文本消息
    colony.observe("你好，共生基因群！")

    # 获取状态
    status = colony.get_status()
    print(status["field_summary"])

    # 保存个体
    colony.save("my_colony.sym")

    # 出芽生殖（产生突变后代）
    baby = colony.bud(mutation_rate=0.02)

    # 评估适应度
    fitness = colony.evaluate_fitness()

    # 多代进化
    evolved = colony.evolve_step(environment_inputs=["消息1", "消息2"], generations=3)

---

## 消息接入说明 · Message Ingestion

**共生基因群核心库不包含任何特定平台的监听代码。** 它仅提供标准的 `observe(text)` 接口，接收纯文本输入。接入真实聊天环境需要用户自行实现适配器。

以下为建议的接入方案（仅供设计参考，**不在本仓库提供可执行代码**）：

- **通用文本文件**：将群聊消息导出为文本文件，每行一条，通过脚本循环调用 `colony.observe(line)`。
- **WebSocket / HTTP 服务**：自行搭建一个本地 WebSocket 服务，接收来自聊天框架（如 NapCat、Lagrange 等）推送的消息，解析后调用 `observe()`。
- **Android 通知监听（需开发 Android 应用）**：通过 `NotificationListenerService` 捕获 QQ 通知，提取文本后通过本地 Socket 发送给共生基因群进程。

**重要提醒**：任何消息监听行为都应当遵守相关平台的服务条款与法律法规，仅在获得所有参与者明确同意的私人测试环境中使用。

---

## 当前版本限制 · Current Limitations (v1.0.0-alpha)

### 中文
- 仅支持文本输入（文字消息和文本文件）。
- 视频、图片、GIF 等多媒体实时处理暂不支持（计划于 v2.0）。
- 输出接口已预留但默认禁用（哑巴模式）。

### English
- Only text input is supported (messages and text files).
- Real-time processing of video, images, and GIFs is not yet supported (planned for v2.0).
- Output interface is reserved but disabled by default (Mute Mode).

---

## 文档 · Documentation

完整设计文档请见：
- [中文设计文档](docs/design/Symbiogen_Complete_Design_v1.0_zh.md)
- [English Design Doc](docs/design/Symbiogen_Complete_Design_v1.0_en.md)

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
