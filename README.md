### AI不止语

做 AI 工具，也讲 AI 实战。
公众号 / 抖音 / 视频号同名 **AI不止语**，X（Twitter）[@jnMetaCode](https://x.com/jnMetaCode) —— 聊 AI 编程、Agent、工具实战。

[![开源项目累计](https://img.shields.io/badge/开源项目累计-⭐%2033k+-2b7489?style=flat-square)](https://github.com/jnMetaCode?tab=repositories&sort=stargazers)
[![followers](https://img.shields.io/github/followers/jnMetaCode?style=flat-square&label=关注&color=2b7489)](https://github.com/jnMetaCode?tab=followers)

---

#### 🚀 主线：让 AI 真正会干活

给它**专家角色**、教它**工作方法**、帮你**一句话调度**、再加一层**合规兜底**。

| 项目 | 它能帮你干嘛 | |
|------|------------|---|
| [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | **277 个即插即用的 AI 专家**：产品 / 架构 / 营销 / 小红书 / 抖音运营，拿来就用 | [![](https://img.shields.io/github/stars/jnMetaCode/agency-agents-zh?style=flat&label=⭐)](https://github.com/jnMetaCode/agency-agents-zh) |
| [superpowers-zh](https://github.com/jnMetaCode/superpowers-zh) | 教 AI **怎么把活干好**：TDD、调试、代码审查等 20 个工作方法，装上就生效 | [![](https://img.shields.io/github/stars/jnMetaCode/superpowers-zh?style=flat&label=⭐)](https://github.com/jnMetaCode/superpowers-zh) |
| [agency-orchestrator](https://github.com/jnMetaCode/agency-orchestrator) | **一句话 → 多个 AI 专家自动接力**，几分钟出完整方案（15 种大模型，11 种免 key） | [![](https://img.shields.io/github/stars/jnMetaCode/agency-orchestrator?style=flat&label=⭐)](https://github.com/jnMetaCode/agency-orchestrator) |
| [shellward](https://github.com/jnMetaCode/shellward) | AI 项目**合规体检**：数据出境 / 硬编码密钥 / 个人信息暴露，一行命令扫出来 | [![](https://img.shields.io/github/stars/jnMetaCode/shellward?style=flat&label=⭐)](https://github.com/jnMetaCode/shellward) |

#### 🆕 最近在做

| 项目 | 它能帮你干嘛 | |
|------|------------|---|
| [openshorts · 开片](https://github.com/jnMetaCode/openshorts) | **文案进，成片出**：脚本 / 配音 / 字幕 / 成片 / 发布文案一条龙，**第一条 0 元、0 个付费 key** 跑通，全程本地 | [![](https://img.shields.io/github/stars/jnMetaCode/openshorts?style=flat&label=⭐)](https://github.com/jnMetaCode/openshorts) |
| [codepet · 码宠](https://github.com/jnMetaCode/codepet) | 桌面养成桌宠：你写代码 / 用 Claude Code，它就涨经验、升级、换状态、跳舞。全本地、隐私优先 | [![](https://img.shields.io/github/stars/jnMetaCode/codepet?style=flat&label=⭐)](https://github.com/jnMetaCode/codepet) |

<a href="https://github.com/jnMetaCode/openshorts"><img src="https://raw.githubusercontent.com/jnMetaCode/openshorts/main/docs/cases/koubo-onion/onion-12s.gif" width="220" alt="openshorts 生成的短视频"></a>

<sub>👆 开片跑出来的《为什么切洋葱会流眼泪》—— **0 元、0 个付费 key**，6 镜里 2 镜是素材库没货时本机现画的</sub>

#### 🛠️ local-agent-toolkit · 本地三件套

> agent 最缺的三样东西，各做一个小工具。**单独用也行，一起用更强。**
> 都是 `npx` 一条命令就跑，不在你电脑里装一堆东西；想全装，Claude Code 里一条命令搞定。

| 工具 | 解决什么问题 | 单独试一下 |
|---|---|---|
| 🧠 [engram](https://github.com/jnMetaCode/engram) | **记忆**：让 AI 记住你的笔记和决定，带出处回答，而且越用越准 | `npx @jnmetacode/engram ingest ~/notes` |
| 🍳 [skillet](https://github.com/jnMetaCode/skillet) | **技能**：像 npm 一样给 agent 装技能，一条命令（[在线技能库](https://jnmetacode.github.io/skillet/)） | `npx @jnmetacode/skillet add pdf` |
| 🔭 [tracelet](https://github.com/jnMetaCode/tracelet) | **眼睛**：实时看 AI 每步干了啥、花了多少钱，像浏览器的 Network 面板 | `npx @jnmetacode/tracelet` |

> 想一次全装（在 Claude Code 里）：`/plugin marketplace add jnMetaCode/local-agent-toolkit`

#### 🧪 评估驱动的 AI 应用工程

> 三套**用数据说话**的 AI 应用系统。不是 demo：每个技术决策都由自建评估集的实测推导，指标与复现命令都写在 README 首屏。

| 项目 | 做什么 | 实测 |
|---|---|---|
| [repo-rag](https://github.com/jnMetaCode/repo-rag) | 中文知识库 RAG：结构分块 + 混合检索 + **两层拒答** + 引用溯源 | hit@1 **95.8%** · faithfulness **0.981** · 拒答 6/6 |
| [orchestrator-lg](https://github.com/jnMetaCode/orchestrator-lg) | 把 agency-orchestrator 引擎重写为 **LangGraph**：checkpoint 断点续跑 + 可持久化审批中断 | 7/7 测试 · YAML 零改动兼容 |
| [llm-gateway](https://github.com/jnMetaCode/llm-gateway) | 多模型网关：SSE 流式取消链 + **三态熔断**（按 provider 隔离）+ token 计费 | 10/10 测试 · Docker |

> 最反直觉的一条：混合检索 RRF 在这个语料上**反而拖低了 hit@1**，所以我把它关了；BM25 基线看着够用，但 miss **全是跨语言**——这才是换 bge-m3 的真正理由。
> 完整数据、复现命令和踩坑记录都在 [repo-rag](https://github.com/jnMetaCode/repo-rag)。

#### 📖 教程 · 创作

| | |
|---|---|
| [ai-coding-guide](https://github.com/jnMetaCode/ai-coding-guide) | AI 编程实战指南：66 个 Claude Code 技巧 + 10 款工具最佳实践 |
| [ai-coding-trilogy](https://github.com/jnMetaCode/ai-coding-trilogy) | AI 编程三卷书（入门 / 工作流 / 架构，中英双语 PDF） |
| [ai-shortfilm-prompts](https://github.com/jnMetaCode/ai-shortfilm-prompts) | AI 短片《丧尸清道夫》方法论 + 提示词（Sora / 可灵 / 即梦通用） |

#### 🎓 免费课程 · [aiOlaOla](https://aiolaola.com/?utm_source=github&utm_campaign=profile)

**13 门实操课、648 节，全部 ¥0，登录即学。**

| 课程 | 节数 | 讲什么 |
|---|:--:|---|
| [从零学会 AI 编程](https://aiolaola.com/?utm_source=github&utm_campaign=profile) | 182 | 主线课：从不会写代码到能用 AI 交付项目 |
| [从零构建 AI 智能体](https://aiolaola.com/course/ai-agent?utm_source=github&utm_campaign=profile) | 40 | Agent 从原理到落地 |
| [AI 应用开发·专业版](https://aiolaola.com/course/ai-app-pro?utm_source=github&utm_campaign=profile) | 54 | 把大模型做成能上线的产品 |
| [AI 专家团队实战](https://aiolaola.com/course/ai-agency?utm_source=github&utm_campaign=profile) | 35 | 把 agency-agents-zh 的 277 位专家用成一支团队 |
| [AI 内容流水线](https://aiolaola.com/course/ai-pipeline?utm_source=github&utm_campaign=profile) | 31 | 用 AO 产线真实生产两门课的全过程留档，含七类翻车现场 |
| [AI 量化实战·专业版](https://aiolaola.com/course/ai-quant-pro?utm_source=github&utm_campaign=profile) | 65 | 量化从策略到实盘 |

其余 7 门：[AI 绘画从 0 到能用](https://aiolaola.com/course/ai-art?utm_source=github&utm_campaign=profile)（46）· [深度专注](https://aiolaola.com/course/deep-focus?utm_source=github&utm_campaign=profile)（48）· [用 AI 写小说](https://aiolaola.com/course/ai-novel?utm_source=github&utm_campaign=profile)（42）· [AI 漫剧实战](https://aiolaola.com/course/ai-comic-drama?utm_source=github&utm_campaign=profile)（42）· [看懂 AI 量化](https://aiolaola.com/course/ai-quant?utm_source=github&utm_campaign=profile)（26）· [DeepSeek 快上手](https://aiolaola.com/course/deepseek?utm_source=github&utm_campaign=profile)（22）· [国内怎么用 AI 编程](https://aiolaola.com/course/ai-cn-tools?utm_source=github&utm_campaign=profile)（15）

<sub>两门「专业版」定价同样是 ¥0，前几节免登录试看，其余章节需邀请 1 位朋友解锁 · 🌍 [English](https://aiolaola.com/en?utm_source=github&utm_campaign=profile) / [日本語](https://aiolaola.com/ja?utm_source=github&utm_campaign=profile) / [Español](https://aiolaola.com/es?utm_source=github&utm_campaign=profile) / [한국어](https://aiolaola.com/ko?utm_source=github&utm_campaign=profile) / [繁體中文](https://aiolaola.com/zh-Hant?utm_source=github&utm_campaign=profile) 六语可选</sub>

#### 🌍 也在贡献

[OpenClaw](https://github.com/openclaw/openclaw)（260k+ ⭐）—— 错误分类、守护进程可靠性、Ollama 集成等多个 PR。

---

<sub>💼 合作 / 赞助：**jnMetaCode@qq.com** ｜ `TypeScript` · `Python` · `Node.js` · `AI / LLM` · `MCP`</sub>
