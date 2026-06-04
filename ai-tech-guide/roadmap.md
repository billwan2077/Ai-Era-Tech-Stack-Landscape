# AI 时代软件开发技术地图与学习指南开发路线图 (Roadmap)

此文件为我们的**本地自定义 Skill 记忆/指令集**。当您在未来的对话中开启新会话时，只需让我读取此文件，我即可瞬间恢复上下文，知道我们的整体目标以及写到了第几篇文章。

---

## 🎯 整体开发目标
把 **AI 时代软件开发技术地图** 中的每个技术、语言、框架，分别写成独立的、深入剖析的知识分析文档，汇总成为一本 **《AI 时代全栈与 Agent 开发指南》**。

每一篇文章都将提供 **简体中文 (ZH)** 和 **英文 (EN)** 两个独立版本：
1. **发展背景与前景**：此技术为什么在 AI 时代变得如此重要？
2. **与其他技术的关系**：它在全栈中扮演什么角色，与相邻技术如何配合？
3. **与 AI 的深层关系**：AI 如何使用它（例如 Tool Call），或者它如何辅助 AI（例如 pgvector 向量库）？
4. **核心技术详解**：精选最重要、最核心的机制进行技术剖析。
5. **初学者学习 Guide**：为网络工程师/初学者量身定制的学习路径与关键学习内容。

---

## 📝 编写进度追踪表 (Checklist)

### 第一部分：核心编程语言篇 (Programming Languages)
- [x] 01. **Python**：AI 时代的“通用语”与网络自动化利器 (ZH & EN)
- [ ] 02. **JavaScript & TypeScript**：全栈 AI 产品界面与前端控制中心
- [ ] 03. **Go 语言**：AI 基础设施与高并发微服务的云原生选择
- [ ] 04. **Rust 语言**：高性能、安全底座与本地 AI 推理的未来
- [ ] 05. **SQL 语言**：从关系数据库到 Text-to-SQL 的企业级事实桥梁

### 第二部分：现代前端技术层 (Frontend Layer)
- [ ] 06. **HTML/CSS/JS 基础**：AI 自动生成界面的基本骨架与交互底座
- [ ] 07. **React**：基于组件化的声明式 UI 与 AI 对话面板构建
- [ ] 08. **Next.js**：全栈式 React 框架、Server Actions 与 AI 流式响应的最佳搭档
- [ ] 09. **Vue & Nuxt**：企业级后台管理与轻量化全栈开发的另一选择
- [ ] 10. **Tailwind CSS**：原子化 CSS 与 AI 页面生成的完美结合
- [ ] 11. **UI 组件库（shadcn/ui, MUI）**：规范化标准组件与 Agent 页面渲染的契合

### 第三部分：现代后端技术层 (Backend Layer)
- [ ] 12. **Node.js**：JS 全栈后端、实时长连接与 AI 网关路由
- [ ] 13. **FastAPI**：基于 Python 的现代异步 API 与零代码 Tool-Call 对接
- [ ] 14. **Django**：Python 经典全功能框架在企业管理与权限系统的应用
- [ ] 15. **Java & Spring Boot**：企业核心业务系统与 Python/AI 服务的双引擎架构
- [ ] 16. **Go Web 后端**：高并发 API、云原生基础设施与模型路由控制面

### 第四部分：数据库与数据存储层 (Databases & Vector Memory)
- [ ] 17. **PostgreSQL & pgvector**：关系型业务数据与向量检索的完美混合体
- [ ] 18. **MySQL**：经典关系型数据库的 Text-to-SQL 查询与分析
- [ ] 19. **SQLite & FTS5**：轻量级本地存储、全文检索与端侧 Agent 记忆库
- [ ] 20. **Redis**：高并发缓存、任务队列与 Agent 短期记忆管理
- [ ] 21. **向量数据库（Qdrant, Chroma 等）**：AI 长期语义记忆检索的原理与选型

### 第五部分：AI 应用基础篇 (AI Foundations)
- [ ] 22. **LLM 全景剖析**：商业 API、开源权重与本地模型的能力边界
- [ ] 23. **提示词工程 (Prompt Engineering)**：从基础提问到系统角色、结构化约束与 Few-Shot
- [ ] 24. **RAG (检索增强生成)**：解决大模型幻觉与实时企业知识获取的核心架构
- [ ] 25. **Text Embeddings**：将文本映射为高维向量的语义表征原理
- [ ] 26. **Fine-Tuning 与 RAG**：何时微调？何时检索？企业应用落地决策指南

### 第六部分：Agent 与智能体篇 (Agentic Systems)
- [ ] 27. **AI Agent 核心概念**：从单一问答到规划、记忆、工具与执行的自主系统
- [ ] 28. **LangChain**：LLM 编排、数据链连接与 Agent 工具调用库
- [ ] 29. **LangGraph**：有状态循环图编排与复杂工作流的 Flow Engineering
- [ ] 30. **LlamaIndex**：面向复杂数据源索引、查询与 Agentic RAG 的利器
- [ ] 31. **Model Context Protocol (MCP)**：AI 时代的“USB-C”标准化工具连接协议
- [ ] 32. **Tool/Function Calling**：大模型调用外部 API 的决策、执行与纠错机制

### 第七部分：DevOps、平台与基础设施篇 (DevOps & Platform)
- [ ] 33. **Git & Code Version Control**：管理 AI 生成代码、查看 Diff 与人工审核工作流
- [ ] 34. **Docker & Podman**：容器化隔离、Agent 运行沙盒与环境安全边界
- [ ] 35. **Kubernetes**：企业级复杂 AI 系统、微服务及模型推理服务的容器编排
- [ ] 36. **CI/CD Pipelines**：自动化构建、静态格式检查、单元测试与人工验证网关

### 第八部分：架构模式层 (Architectural Patterns)
- [ ] 37. **单体与微服务架构**：AI 时代业务系统与大模型服务的集成设计
- [ ] 38. **Serverless 架构**：Vercel/AWS Lambda 在 AI 应用冷启动与流量适配中的应用
- [ ] 39. **事件驱动架构 (EDA)**：文档处理管道、实时告警分析与 Agent 异步任务
- [ ] 40. **RAG 系统架构设计**：数据接入、清洗、分块、检索、重排(Rerank)与生成的生产级链路
- [ ] 41. **Agentic 架构设计**：Planner、Memory、Executor、评估器与安全网关的配合

### 第九部分：AI 工具、趋势与自我定位篇 (Tools & Trends)
- [ ] 42. **AI-Native IDEs (Cursor/Windsurf)**：如何利用项目全局感知实现跨文件协同开发
- [ ] 43. **Vibe Coding 趋势**：从 Code-First 到 Intent-First 的开发范式改变与开发者转型
- [ ] 44. **端侧 SLM 与混合架构**：本地 Ollama 离线推断与云端大模型的高效融合
- [ ] 45. **安全与合规治理 (Agentic Governance)**：企业 Agent 操作审计、工具白名单与 Secret 防泄露

---

## 🛠 开发指令与指南

### 1. 写作受众与质量标准 (Target Audience & Quality Standards)
*   **受众定位**：不局限于网络工程师，必须面向**技术小白、新手甚至普通人**。概念讲解必须通俗易懂，多使用生活中的比喻，避免堆砌晦涩难懂的专业术语。
*   **内容充实度**：文章内容必须详实丰富，拒绝精简版或大纲版。
*   **元素要求**：每篇文章必须包含**小技巧 (Tips)**、**避坑指南 (Pitfalls)**、**真实行业应用案例**与**相关知识点引用/参考资料 (References)**。

### 2. 自动化审核机制 (Subagent Review Flow)
每篇文章（中英文版）撰写完毕后，必须调用专门的审查 Subagent (`editor_reviewer`) 进行独立双语评审：
1.  **评审维度**：专业性 (Professionalism)、易读性 (Readability)、丰富度 (Depth/Richness)、趣味与吸引力 (Engagement)。
2.  **评分机制**：总分 10 分。
3.  **门槛限制**：**评分必须达到 8 分或以上**才能执行 Git Push 推送到 GitHub。若低于 8 分，必须根据评审意见进行修改重写，直至评分达到 8 分以上。

### 3. 文件命名与执行规则
1.  所有文章保存在：`/Users/billwan/code/ai-learning-path/token-optimization/ai-tech-guide/`。
2.  双语命名规则：`XX_tech_name_zh.md` 与 `XX_tech_name_en.md`。
3.  写完一篇文章并通过审核后，将进度追踪表中的 `[ ]` 更新为 `[x]`，然后 commit 并 push。
