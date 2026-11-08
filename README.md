### ljw-serch 的项目

全栈方向，主要技术栈：**Vue 3 + FastAPI + MySQL + Redis**，近期在做 LLM 应用（RAG、Tool-Calling Agent）。

---

#### 🔹 AI 新闻资讯平台
前后端分离的新闻资讯 + AI Agent 平台。AI 助手通过受控工具直接查询数据库，不靠模型编造内容；未配置模型时自动降级为本地规则引擎。

- 仓库：[news-agent](https://github.com/ljw-serch/news-agent)
- 技术栈：Vue 3 / Vite / Pinia / Vant · FastAPI · SQLAlchemy 2.0 全异步 · MySQL · Redis · OpenAI 兼容大模型
- 技术点：Agent 多轮工具调用、SSE 流式输出、AI 摘要与每日简报、Redis 缓存降级、JWT 双重权限校验

#### 🔹 智能实验室预约系统
面向高校实验室的预约与管理平台，学生端 / 管理端分离。在传统 CRUD 之上接入 RAG 知识库问答与 Tool-Calling Agent，可用自然语言完成预约的查询、创建与取消。

- 仓库：[lab-agent](https://github.com/ljw-serch/lab-agent)
- 技术栈：Vue 3 / Vite · FastAPI · SQLAlchemy · MySQL · Chroma · LangGraph
- 技术点：BGE 中文向量检索（RAG）、Agent 工具集 + 写操作二次确认、预约时段冲突检测、SSE 流式对话、待审核超时自动取消

---

📫 联系方式：可以通过仓库 Issues 联系
