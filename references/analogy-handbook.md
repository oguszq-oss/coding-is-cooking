# 餐厅类比手册索引：按任务取材

本文件只负责分流，不收录完整词典。先看主 `SKILL.md` 的高频映射；仍不够时，只选当前任务需要的一份领域手册：

| 当前概念 | 读取 |
|---|---|
| 软件产品、开发、IDE、泛化语言或框架 | 先用主 `SKILL.md` 的高频映射；需要领域细节再选前端或后端手册 |
| 裸词“沙箱”“Token”或“react” | 先按执行隔离 / 平台测试环境、模型计量 / 访问凭据、前端 React / Agent ReAct 消歧，再只读对应一页 |
| 网页、React、前端框架、组件、构建、移动端 | [frontend-analogy.md](frontend-analogy.md) |
| SDK、第三方或支付平台接入、Webhook、OAuth、回调、签名、平台测试沙箱、限流 | [external-platform-integration.md](external-platform-integration.md) |
| schema、JSON Schema、TypeBox、运行时校验、断言、Base64、endpoint | [data-contracts.md](data-contracts.md) |
| 后端、数据库、迁移、API、部署、排错、安全、认证授权、访问令牌、架构 | [backend-analogy.md](backend-analogy.md) |
| AI 对话、AI Token、上下文、模型、提示词 | [ai-basics.md](ai-basics.md) |
| steering、followUp、prepareNextTurn、shouldStopAfterTurn、stopReason、Agent 轮次钩子 | [agent-loop-controls.md](agent-loop-controls.md) |
| Agent、工具调用、MCP、RAG、评测、验收、执行沙箱、ReAct | [agent-tools.md](agent-tools.md) |
| 请求响应、角色物流、AI 协作线、长故事时间线，或 Git、成本、用户数据、网络、系统性 bug 的失真边界 | [restaurant-workflow.md](restaurant-workflow.md) |
| 新编类比、复核失败、正误例、文风深查 | [quality-checks.md](quality-checks.md) |

跨域问题才加第二份；不要例行通读全部 reference。类比只帮助建立直觉，安全、架构、成本或产品判断仍回到代码、测试、配置和官方资料。
