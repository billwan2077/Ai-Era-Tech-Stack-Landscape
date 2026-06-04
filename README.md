# AI-Era Native Tech Stack & Tool Landscape / AI 时代原生技术栈与工具全景图

---

### Navigation / 导航按钮
<p align="center">
  <b><a href="#-ai-时代原生技术栈与工具全景图">简体中文 🇨🇳</a></b>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <b><a href="#-ai-era-native-tech-stack--tool-landscape">English 🇺🇸</a></b>
</p>

---

## 🇨🇳 AI 时代原生技术栈与工具全景图

随着 AI 从辅助编码（AI-assisted coding）演进为**自主式 AI 工程（AI-native engineering）**，软件开发范式已经发生了根本性的改变。开发者的核心工作正在从“编写具体语法”转向“设计系统架构、编排 Agent 工作流与校验结果”。

### 1. 核心技术架构层

#### A. AI 原生与优化语言 (Languages)
*   **Mojo**：专门针对 AI 芯片和异构计算进行编译优化的语言，拥有类 Python 语法，性能是 Python 的数万倍。
*   **Rust (Candle, Burn)**：由于高性能和内存安全性，正在成为 AI 运行时、分词器（Tokenizers）和本地推理的首选。
*   **TypeScript / JavaScript**：借助 WebGPU/WASM，可在浏览器端离线直接运行小语言模型（SLM）。

#### B. AI 编排与 Agent 框架 (Orchestration)
*   **LangChain / LangGraph**：引入“状态图”机制，支持复杂的有状态循环和 Flow Engineering。
*   **CrewAI / AutoGen**：支持多 Agent 角色分工与协作，处理复杂的软件工程任务。
*   **LlamaIndex**：专为 RAG 设计的连接器与高级知识检索框架。

#### C. 数据库与记忆体 (Databases)
*   **向量原生库**：Pinecone、Qdrant、Milvus、Chroma。
*   **传统数据库的向量扩展**：pgvector (PostgreSQL)、MongoDB Atlas 等。

#### D. 前端与动态生成 UI (Generative UI)
*   **Vercel AI SDK**：提供了跨主流前端框架（Next.js, React）流式渲染和大模型流输出的标准库。
*   **v0.dev / Bolt.new / Lovable.dev**：自然语言生成全栈网站，实现 “Vibe Coding”。

---

### 📚 《AI 时代全栈与 Agent 开发指南》目录

| 序号 | 简体中文版 (Chinese) | English Version |
| :--- | :--- | :--- |
| **01** | [01. Python：AI 时代的通用语](ai-tech-guide/01_python_zh.md) | [01. Python: The Lingua Franca](ai-tech-guide/01_python_en.md) |
| **02** | 02. JavaScript & TypeScript (未开始) | 02. JavaScript & TypeScript (Pending) |
| **03** | 03. Go 语言 (未开始) | 03. Go Language (Pending) |
| **04** | 04. Rust 语言 (未开始) | 04. Rust Language (Pending) |
| **05** | 05. SQL 语言 (未开始) | 05. SQL Language (Pending) |

*(更多文章链接将随着开发持续更新，完整目录请参考 [路线图 (roadmap.md)](ai-tech-guide/roadmap.md))*

---

## 🇺🇸 AI-Era Native Tech Stack & Tool Landscape

As AI transitions from simple **AI-assisted coding** (line completions) to **AI-native engineering** (autonomous agents), the software development paradigm has shifted. Developers are moving away from manual syntax writing toward system design, workflow orchestration, and result verification.

### 1. Core Technical Layers

#### A. AI-Native & Optimized Languages
*   **Mojo**: A programming language designed for AI hardware acceleration with Python-like syntax but compiled performance.
*   **Rust (Candle, Burn)**: Gaining high popularity for tokenizer engines, safe local model inference runtimes, and agent systems.
*   **TypeScript / JavaScript**: Powering local small language models (SLMs) in-browser via WebGPU and WebAssembly.

#### B. AI Orchestration & Agent Frameworks
*   **LangChain / LangGraph**: Handles stateful multi-agent pipelines with complex logic loops and flow engineering.
*   **CrewAI / AutoGen**: Standard framework for multi-agent collaboration, allowing automated problem solving via specialized roles.
*   **LlamaIndex**: Deep data connectors and search indexes dedicated to Retrieval-Augmented Generation (RAG).

#### C. Vector Databases & Memory Layers
*   **Vector-Native DBs**: Pinecone, Qdrant, Milvus, Chroma.
*   **Hybrid RDBMS / Vector Search**: pgvector (PostgreSQL), Elasticsearch, MongoDB Atlas.

#### D. Generative UI & Full-Stack Builders
*   **Vercel AI SDK**: Multi-model streaming endpoints and dynamic web component generation.
*   **v0.dev / Bolt.new / Lovable.dev**: Build, run, and deploy production-grade websites directly from natural language.

---

### 📚 "AI-Era Fullstack & Agent Guide" Directory

| No. | Chinese Version | English Version |
| :--- | :--- | :--- |
| **01** | [01. Python：AI 时代的通用语](ai-tech-guide/01_python_zh.md) | [01. Python: The Lingua Franca](ai-tech-guide/01_python_en.md) |
| **02** | 02. JavaScript & TypeScript (Pending) | 02. JavaScript & TypeScript (Pending) |
| **03** | 03. Go Language (Pending) | 03. Go Language (Pending) |
| **04** | 04. Rust Language (Pending) | 04. Rust Language (Pending) |
| **05** | 05. SQL Language (Pending) | 05. SQL Language (Pending) |

*(More links will be updated as we proceed. See [roadmap.md](ai-tech-guide/roadmap.md) for details)*
