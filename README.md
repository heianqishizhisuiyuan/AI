# AI 开发工具合集

> 收录常用的 AI 辅助开发工具,包括智能编辑器、VS Code 插件和实用工具

## 🎨 AI 编辑器

| 名称         | 链接                                            | 简介                                         |
| ------------ | ----------------------------------------------- | -------------------------------------------- |
| **Cursor**   | [www.cursor.com](https://www.cursor.com/)       | AI 驱动的代码编辑器,支持智能补全和对话式编程 |
| **Trae**     | [www.trae.cn](https://www.trae.cn/)             | 国内 AI 编程助手,支持中文优化                |
| **Windsurf** | [www.windsurf.com](https://www.windsurf.com/)   | 新一代 AI 代码编辑器                         |
| **Lingma**   | [lingma.aliyun.com](https://lingma.aliyun.com/) | 阿里云智能编码助手                           |
| **Codeium**  | [www.codeium.com](https://www.codeium.com/)     | 免费的 AI 代码补全工具                       |

## 🔌 VS Code 插件

| 插件名称                      | 简介                        |
| ----------------------------- | --------------------------- |
| **ROO CODE**                  | 智能代码生成和重构工具      |
| **Cline**                     | AI 编程助手插件             |
| **Codex**                     | 基于 OpenAI 的代码生成插件  |
| **Tencent Cloud CodeBuddy**   | 腾讯云代码助手              |
| **Alibaba Cloud Code Studio** | 阿里云代码工作室            |
| **Lingma**                    | 阿里云通义灵码 VS Code 版   |
| **Claude Code for VS Code**   | Claude AI 官方 VS Code 插件 |
| **Kilo Code AI Agent**        | AI 代理式编程工具           |

## 🛠️ 实用工具

### cc-switch

- **项目地址**: [github.com/farion1231/cc-switch](https://github.com/farion1231/cc-switch)
- **功能**: 管理和切换不同 AI 提供商配置的桌面应用,支持 Claude Code 和 Codex 的 MCP 配置
- **适用场景**: 多 AI 服务切换、配置管理

### Claude Code

- **官网**: [www.claude.com/product/claude-code](https://www.claude.com/product/claude-code)
- **功能**: 直接在终端中使用 Claude AI 的强大能力
- **适用场景**: 命令行开发、自动化脚本编写

### fly-cursor-free

- **项目地址**: [github.com/liqiang-xxfy/fly-cursor-free](https://github.com/liqiang-xxfy/fly-cursor-free)
- **功能**: 自动续期 Cursor Pro 14 天试用
- **注意**: 仅供学习研究使用,请支持正版

## 🧩 MCP

| MCP 名称                | 官方地址                                                                                 | 作用                                                                                   |
| ----------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **memory**              | [进入](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)             | 官方参考 MCP Server,提供基于知识图谱的持久化记忆能力,适合做上下文补充和长期信息存储    |
| **sequential-thinking** | [进入](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | 官方参考 MCP Server,适合复杂问题拆解、多步推理、方案分析和逐步验证                     |
| **context7**            | [upstash/context7](https://github.com/upstash/context7)                                  | Upstash 官方 Context7 MCP,用于查询最新库/框架文档与代码示例,适合技术实现时快速检索资料 |
| **fetch**               | [进入](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)              | 官方参考 MCP Server,用于抓取网页内容并提取适合 LLM 使用的正文内容                      |
| **time**                | [进入](https://github.com/modelcontextprotocol/servers/tree/main/src/time)               | 官方参考 MCP Server,提供当前时间查询和时区转换能力                                     |
| **Chrome DevTools MCP** | [进入](https://github.com/ChromeDevTools/chrome-devtools-mcp)                            | 让 agent 直接做性能 trace、页面调试、前端问题定位                                      |
| **Playwright MCP**      | [进入](https://github.com/microsoft/playwright-mcp)                                      | 让 agent 直接驱动浏览器做页面操作、断言、自动化验证                                    |

## 🪄 Skills

| 名称              | 类型  | 来源             | 定位 / 作用                                                                                    |
| ----------------- | ----- | ---------------- | ---------------------------------------------------------------------------------------------- |
| **skill-creator** | Skill | 本地已安装 Skill | 单个可调用 Skill,用于创建、修改、优化和评估 Codex/Claude Skills,适合沉淀可复用工作流与提示模板 |

## 🚀 Superpowers

- **项目地址**: [obra/superpowers](https://github.com/obra/superpowers)
- **类型**: Skills Framework / Development Methodology / Plugin Bundle
- **定位**: 不是单个 skill,而是一套面向 coding agents 的完整软件开发方法论与技能框架
- **作用**: 由一组可组合 skills、初始指令以及配套插件/脚本组成,核心作用是规范 agent 在需求分析、写计划、TDD、调试、并行执行、代码评审和收尾阶段的工作方式

---

**更新时间**: 2026-04

**贡献**: 欢迎提交 PR 补充更多优质 AI 开发工具
