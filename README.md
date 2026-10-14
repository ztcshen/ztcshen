# 你好，我是 ztcshen

**软件工程硕士 · Java 后端与全栈开发 · 自动化测试与开发工具**

我主要从事 Java 后端和全栈开发，做过账户与交易系统、异步任务、系统集成和数据管理相关工作。除了业务系统开发，我也在持续维护接口测试、数据库建模和 AI 辅助开发方面的开源工具。

我关注从需求、数据模型和接口设计，到部署、联调、测试与故障排查的完整工程过程，希望把复杂业务做成可维护、可验证的软件。

## 我做什么

- **后端与系统集成**：使用 Java、Spring Boot / Spring Cloud、MyBatis 和 Dubbo 开发服务，处理账户、交易和外部系统对接流程。
- **并发与数据一致性**：结合多线程、线程池、Redis 调度和消息队列处理异步任务；关注数据库事务、幂等、补偿与故障恢复。
- **全栈与工程交付**：使用 Vue 3 / React、TypeScript / JavaScript 构建管理页面和工具界面，结合 Linux、Docker、自动化脚本与 CI 完成部署和验证。
- **测试与 AI 工具**：使用 Go、Python、TypeScript 开发接口与工作流测试工具，结合 Playwright、执行记录和报告，让自动化结果可以复现和检查。

常用数据组件：**MySQL · PostgreSQL · SQLite · Redis · RabbitMQ · Kafka**。

## 公开项目

### [AgentTestBench](https://github.com/ztcshen/agent-testbench)

面向测试工程师和 AI Agent 的接口与工作流测试工作台。通过 API 发现可运行的测试目标，执行用例、工作流和测试场景图，并把请求、响应、断言和执行结果保存为可查看的记录与报告。

- **关注的问题**：测试资产分散、流程回归难复用、失败结果缺少排查上下文。
- **技术栈**：Go、React、TypeScript，支持 SQLite / PostgreSQL / MySQL。
- **入口**：[中文说明](https://github.com/ztcshen/agent-testbench/blob/main/README.zh-CN.md) · [源码](https://github.com/ztcshen/agent-testbench)

### [ER Wiki](https://github.com/ztcshen/er-wiki)

离线数据库建模与 ER 关系可视化工具。基于 drawDB、ELK、libavoid 等开源组件，让复杂表关系更容易阅读和追踪，支持本地 SQL 导入、模型编辑与 SVG / PNG 导出。

- **关注的问题**：表与关系增多后，字段映射、连线和跨域关系难以看清。
- **技术栈**：React、Electron、JavaScript，结合正交布局与避障布线。
- **入口**：[在线演示](https://ztcshen.github.io/er-wiki/demo.html) · [中文说明](https://github.com/ztcshen/er-wiki/blob/main/README.zh-CN.md) · [桌面版下载](https://github.com/ztcshen/er-wiki/releases/latest)

### 其他工具

| 项目 | 用途 |
| --- | --- |
| [markdown-gate](https://github.com/ztcshen/markdown-gate) | TypeScript CLI 与 Hook 工具，检查 AI 生成的 Markdown；结合 promptfoo 做规则回归与质量评估。 |
| [github-feature-radar](https://github.com/ztcshen/github-feature-radar) | 按具体功能检索和整理开源参考，维护功能索引，支持模糊查询、数据校验和自动更新。 |

## About me

I am a software engineer with a master's degree in Software Engineering. My work spans Java backend and full-stack development, account and transaction workflows, asynchronous processing, and system integration.

I build open-source tools for API testing, database modeling, and developer automation. I care about maintainable systems, reproducible tests, and clear evidence of how software behaves.

---

项目使用、问题反馈与技术讨论，欢迎在对应仓库的 Issues 中交流。
