---
hide:
  - toc
---

# 功能特性

智能问答的功能特性参见下表：

| 主要功能 | 细分项 |
| ------- | ------ |
| 对话 | 支持基于已发布的应用关联语料库，实现智能问答功能 |
| | 对AI提供的回答，用户可以进行评价，复制，重新生成，删除对话或提交反馈，高度互动 |
| 应用中心 | 支持创建 RAG 知识问答应用，提供应用的全生命周期管理，以及绑定或解绑工作空间，实现环境隔离 |
| | 支持使用 GLM、Llama 等模型服务作为应用的模型服务，实现 RAG |
| | 提供多种配置选项，包括 AI 配置、关联语料库、检索策略、召回策略和提示词模板，以优化 AI 回答的效果 |
| | 支持创建应用的密钥，用于 OpenAPI 对话，保证安全性 |
| 语料库 | 支持使用北京智源人工智能研究院的 bge-large-zh-v1.5、bge-large-en-v1.5 对语料进行特征提取 |
| | 支持多种导入方式，包括标准导入、格式化导入、手动导入、图文导入 |
| | 支持多种分片方式，包括按照分割符、分片大小进行分片 |
| | 支持使用插件对文件进行自定义分片 |
| | 支持设置语料库的访问级别，保证数据隔离 |
| | 支持 CSV 和 Excel 格式导出语料库分片，方便后续处理和分析 |
| 数据分析 | 提供问答质量、问答次数、分片质量、分片命中率等数据分析 |
| | 收集并处理用户反馈意见，以便改进服务 |
| 我的反馈 | 保存用户提交过的反馈信息，记录用户的使用体验 |
| 系统配置 | 提供配置聊天记忆轮数、提示词模板等系统配置选项 |
