# liquid-glass-react

React library for Apple's Liquid Glass effect.

## gstack

本项目使用 gstack AI builder framework。所有网页浏览必须使用 `/browse` 技能，切勿使用 `mcp__claude-in-chrome__*` 工具。

### 可用技能

| 技能 | 用途 |
|------|------|
| `/office-hours` | YC Office Hours，创业产品咨询 |
| `/plan-ceo-review` | CEO/founder 模式计划审查 |
| `/plan-eng-review` | 工程架构计划审查 |
| `/plan-design-review` | 设计计划审查 |
| `/design-consultation` | 设计系统咨询 |
| `/design-shotgun` | 生成多个 AI 设计变体 |
| `/design-html` | Pretext HTML/CSS 最终化 |
| `/review` | Pre-landing PR 审查 |
| `/ship` | 合并 PR、部署工作流 |
| `/land-and-deploy` | 着陆和部署工作流 |
| `/canary` | 部署后金丝雀监控 |
| `/benchmark` | 性能回归检测 |
| `/browse` | 快速无头浏览器 QA 测试 |
| `/connect-chrome` | 启动 GStack Browser |
| `/qa` | 系统性 QA 测试并修复 bug |
| `/qa-only` | 只读 QA 测试报告 |
| `/design-review` | 设计质量检查 |
| `/setup-browser-cookies` | 导入浏览器 cookies |
| `/setup-deploy` | 配置部署设置 |
| `/retro` | 每周工程回顾 |
| `/investigate` | 系统性调试调查 |
| `/document-release` | 发布后文档更新 |
| `/codex` | OpenAI Codex CLI 包装器 |
| `/cso` | 基础安全审计 |
| `/autoplan` | 自动审查流程 |
| `/plan-devex-review` | 开发者体验计划审查 |
| `/devex-review` | 开发者体验审查 |
| `/careful` | 危险命令安全警告 |
| `/freeze` | 限制文件编辑范围 |
| `/guard` | 完整安全模式 |
| `/unfreeze` | 清除冻结边界 |
| `/gstack-upgrade` | 升级 gstack |
| `/learn` | 管理项目学习记录 |

## 项目结构

- `src/` — 核心库代码
- `liquid-glass-example/` — 示例应用
- `assets/` — 静态资源

## 开发

```bash
bun install
bun run build
```
