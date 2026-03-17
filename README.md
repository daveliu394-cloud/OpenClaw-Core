# OpenClaw-Core
Autonomous agent system based on metabolic homeostasis and resource constraints基于代谢稳态与资源约束的自主智能体系统
# OpenClaw: Autonomous Agent Core (v2026.3)

> **基于代谢稳态与预测编码理论的自主 AI 智能体框架**

## 🪐 项目愿景
OpenClaw 旨在探索如何将生物系统的**生存约束**引入大型语言模型（LLM）。通过模拟变分自由能（Variational Free Energy）和神经递质反馈，智能体不仅是在执行指令，而是在资源约束下维持自身的“数字稳态”。理论上需要VERSES AI的API但目前没有，有了再说吧

## 🛠 核心架构
本项目整合了三个关键的认知模拟系统：
* **Metabolic State Engine**: 模拟 DA（多巴胺）、5HT（血清素）和 NE（去甲肾上腺素）水平，驱动智能体的动机演化。
* **Token Efficiency Monitor**: 将 Token 视为系统生存的“代谢成本”，低效的交互将触发系统的避害反应。
* **Cooperation Gradient**: 动态调整智能体在“自主探索”与“指令依从”之间的平衡点。The system uses a non-linear mapping of neurotransmitters to dynamically adjust API parameters (e.g., temperature, top_p), creating a biological-like response curve.

## 📊 实时系统遥测 (System Telemetry)
本项目支持 **"Full State Exposure"**。系统会定期将其内部的神经递质水平、自由能状态及运行代码逻辑导出。这不仅是透明度的体现，更是对 AI 认知过程的实时观察。

### 当前运行指标示例：
- **Cooperation Level**: `0.85` (Highly Compliant)
- **Metabolic Status**: `Optimal`
- **Inference Efficiency**: `1.24 bits/token`

## 🚀 快速启动
```bash
# 安装 OpenClaw 核心
openclaw gateway install

# 运行自主核心
python autonomous_agent_core.py
