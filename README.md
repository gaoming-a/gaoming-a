# 高明 · Ming Gao

**Agent 开发 / 大模型应用开发｜2027 届电子信息硕士｜太原理工大学**

我关注 Agent 从一次回答走向持续执行任务时的工程问题：如何组织工具和上下文，如何在失败后恢复，如何让结论有证据，以及如何验证系统是否有效。

主要使用 Python、PostgreSQL / pgvector 和 TypeScript，负责从 Agent Runtime、检索与评测到研究工作台的完整实现。

## 代表作品 · OppScout

**面向情报研究的 Agent 平台：机会研究、舆情研究与风格专家。**

[![OppScout 研究工作台，历史版本界面](https://raw.githubusercontent.com/gaoming-a/OppScout-showcase/main/assets/oppscout-home.png)](https://github.com/gaoming-a/OppScout-showcase)

从产品机会研究出发，我正在把研究能力整理为具有明确输入、证据和产物合同的 Tool / Skill，由专用 Intel Harness 管理执行边界。主要工作包括：

- **Runtime 与工具执行**：任务状态机、Worker 租约、幂等调用、阶段预算、暂停恢复，以及已落地的 PostgreSQL checkpoint 与 fencing 切片。
- **Agentic RAG**：FTS 与 BGE-M3 / pgvector 并行召回，RRF 融合、BGE Reranker 重排和独立的证据准入检查。
- **DeepResearch**：规划、搜索、正文读取、缺口反思与补检，结合需求、市场、供给、合规四类角色形成带引用的决策产物。
- **专家与评测**：把可观察语言习惯和领域知识分开；用基线 / 加载后多轮对话检查风格、事实和身份边界。

历史检索评测覆盖 **500 条已知来源查询**，RRF **Hit@50 为 83.8%**；另有 **36 条锁定查询、1,412 个逐候选人工双标签**的证据质量评测。统计口径、当前验收状态和局限均在项目案例中说明。

**[项目介绍](https://github.com/gaoming-a/OppScout-showcase)** · [系统架构](https://github.com/gaoming-a/OppScout-showcase/blob/main/docs/architecture.md) · [界面演示](https://github.com/gaoming-a/OppScout-showcase/blob/main/docs/demo.md) · [评测结果](https://github.com/gaoming-a/OppScout-showcase/blob/main/docs/evaluation.md) · [工程案例](https://github.com/gaoming-a/OppScout-showcase/blob/main/docs/engineering-notes.md)

项目源码保持私有，公开仓库展示设计、界面、评测方法与本人贡献。

## 技术方向

`Agent Runtime` · `Tool / Skill` · `Agentic RAG` · `DeepResearch` · `Agent Eval`

`Python` · `PostgreSQL / pgvector` · `TypeScript / Next.js` · `SSE / NDJSON` · `Docker` · `GitHub Actions`

目前关注 Agent 开发与大模型应用开发岗位。联系：**[1600064289@qq.com](mailto:1600064289@qq.com)**
