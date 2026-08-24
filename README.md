### AI不止语

做 AI 工具，也讲 AI 实战。
公众号 / 抖音 / 视频号同名 **AI不止语**，X（Twitter）[@jnMetaCode](https://x.com/jnMetaCode) —— 聊 AI 编程、Agent、工具实战。

---

#### 🚀 在做的项目

让 AI 真正会干活：给它**专家角色**、教它**工作方法**、帮你**一句话调度**、再配上**本地记忆和眼睛**。

| 项目 | 它能帮你干嘛 | |
|------|------------|---|
| [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 268 个**即插即用的 AI 专家**：产品 / 架构 / 营销 / 小红书 / 抖音运营，拿来就用 | ⭐ 18.2k |
| [superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) | 教 AI **怎么把活干好**：TDD、调试、代码审查等工作方法，装上就生效 | ⭐ 7.2k |
| [agency-orchestrator](https://github.com/jnMetaCode/agency-orchestrator) | **一句话 → 多个 AI 专家自动接力**，几分钟出完整方案（9 家大模型，6 家免费） | ⭐ 1.9k |
| [local-agent-toolkit](https://github.com/jnMetaCode/local-agent-toolkit) | 给 agent 配上**记忆 + 技能管理 + 运行追踪**，全在本地、数据不出电脑 | 🆕 |
| [aiOlaOla 免费课程](https://aiolaola.com/?utm_source=github&utm_campaign=profile) | **两门免费实操课**：从零学会 AI 编程（180 节）+ 从零构建 AI 智能体（40 节），[English](https://aiolaola.com/en?utm_source=github&utm_campaign=profile)/[日本語](https://aiolaola.com/ja?utm_source=github&utm_campaign=profile)/[Español](https://aiolaola.com/es?utm_source=github&utm_campaign=profile)/[한국어](https://aiolaola.com/ko?utm_source=github&utm_campaign=profile)/[繁體](https://aiolaola.com/zh-Hant?utm_source=github&utm_campaign=profile) 六语可选 | 🌍 |

#### 🛠️ local-agent-toolkit · 本地三件套

> agent 最缺的三样东西，各做一个小工具。**单独用也行，一起用更强。**
> 都是 `npx` 一条命令就跑，不在你电脑里装一堆东西；想全装，Claude Code 里一条命令搞定。

| 工具 | 解决什么问题 | 单独试一下 |
|---|---|---|
| 🧠 [engram](https://github.com/jnMetaCode/engram) | **记忆**：让 AI 记住你的笔记和决定，带出处回答，而且越用越准 | `npx @jnmetacode/engram ingest ~/notes` |
| 🍳 [skillet](https://github.com/jnMetaCode/skillet) | **技能**：像 npm 一样给 agent 装技能，一条命令（[在线技能库](https://jnmetacode.github.io/skillet/)） | `npx @jnmetacode/skillet add pdf` |
| 🔭 [tracelet](https://github.com/jnMetaCode/tracelet) | **眼睛**：实时看 AI 每步干了啥、花了多少钱，像浏览器的 Network 面板 | `npx @jnmetacode/tracelet` |

> 想一次全装（在 Claude Code 里）：`/plugin marketplace add jnMetaCode/local-agent-toolkit`

#### 📖 教程 · 创作

- [ai-coding-guide](https://github.com/jnMetaCode/ai-coding-guide) — AI 编程实战指南：66 个 Claude Code 技巧 + 9 款工具最佳实践
- [ai-coding-trilogy](https://github.com/jnMetaCode/ai-coding-trilogy) — AI 编程三卷书（入门 / 工作流 / 架构，中英双语 PDF）
- [ai-shortfilm-prompts](https://github.com/jnMetaCode/ai-shortfilm-prompts) — AI 短片《丧尸清道夫》方法论 + 提示词（Sora / 可灵 / 即梦通用）
- [shellward](https://github.com/jnMetaCode/shellward) — AI 安全中间件：8 层防御 + 注入检测，零依赖

#### 🌍 也在贡献

[OpenClaw](https://github.com/openclaw/openclaw)（260k+ ⭐）—— 错误分类、守护进程可靠性、Ollama 集成等多个 PR。

#### 🧪 AI 应用工程（2026.08 新开源）

> 三套**评估驱动**的 AI 应用系统。不是 demo：每个技术决策都由自建评估集的实测数据推导，指标与复现命令都在 README 里。

| 项目 | 做什么 | 实测 |
|---|---|---|
| [repo-rag](https://github.com/jnMetaCode/repo-rag) | 中文知识库 RAG：结构分块 + 混合检索 + **两层拒答** + 引用溯源 | hit@1 **95.8%** · faithfulness **0.981** · 拒答 6/6 |
| [orchestrator-lg](https://github.com/jnMetaCode/orchestrator-lg) | 把 agency-orchestrator 引擎重写为 **LangGraph**：checkpoint 断点续跑 + 可持久化审批中断 | 7/7 测试 · YAML 零改动兼容 |
| [llm-gateway](https://github.com/jnMetaCode/llm-gateway) | 多模型网关：SSE 流式取消链 + **三态熔断**（按 provider 隔离）+ token 计费 | 10/10 测试 · Docker |

有三个发现值得单独说：BM25 基线 hit@5 91.7% 看着够用，但 **miss 全是跨语言**——这才是换 bge-m3 的理由；
混合检索 RRF 在这个语料上**反而拖低 hit@1**，所以我把它关了；拒答阈值不是拍的，是跑分数分布校准出来的。
> 三条结论的完整数据、复现命令和踩坑记录都在 [repo-rag](https://github.com/jnMetaCode/repo-rag) 里（指标就在 README 首屏）。

---

#### 👋 Open to Work · 北京

**正在看北京的机会：AI 技术负责人 / 交付负责人 / 技术合伙人**（也看 DevRel 与开发者生态）。

11 年 IT、8 年技术团队管理，做过技术总监，主导过 700 万/月量级平台的技术落地；
这两年专注大模型应用工程，产出就是上面那三个项目 + 一份完整的企业级私有化部署方案。
**能覆盖从需求评估、技术选型到交付的全链路。**

聊聊 → **jnMetaCode@qq.com**

---

<sub>💼 合作 / 赞助：**jnMetaCode@qq.com** ｜ `TypeScript` · `Python` · `Node.js` · `AI / LLM` · `MCP`</sub>
