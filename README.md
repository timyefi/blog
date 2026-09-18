# 研究工程笔记

把研究之外的判断写下来。这里收录的是关于 AI 如何落到个人与组织研究工作里的观察、实践与方法论：Skill 工程化、本地数据与记忆系统、研究工作流的自动化与工程化。

在线阅读（按栏目与时间归档）：<https://timyefi.github.io/>

## 理念与方法论

### [把 AI 风险分散到 AI 之外](https://timyefi.github.io/posts/ai-risk-beyond-ai.html)

*2026-09-18*

名义八个资产的有效风险源只有 2.79 个；分散的空间上界等于权重乘类内波动跨度，按这条公式，AI 内部分散能起多大作用取决于相关性与权重，不取决于名字多少。

[阅读全文](https://timyefi.github.io/posts/ai-risk-beyond-ai.html) · [Markdown 原文](posts/ai-risk-beyond-ai.md)

### [缓存字节数正在取代单价](https://timyefi.github.io/posts/cache-bytes-over-price.html)

*2026-09-17*

Agent 成本的一等指标正从每百万 token 单价换到每 token 缓存字节数；前缀被击穿时命中量会钉在常数上，这个指纹不依赖任何口径。

[阅读全文](https://timyefi.github.io/posts/cache-bytes-over-price.html) · [Markdown 原文](posts/cache-bytes-over-price.md)

### [回测框架为什么要分三层](https://timyefi.github.io/posts/three-layer-backtest-framework.html)

*2026-09-16*

把回测写成一段脚本，数字变了却说不出为什么变；拆成数据层、逻辑层、判断层之后，六类常见错误各自有了明确的落点，改一个阈值不必重跑取数，策略能不能发布也第一次有了统一的出口。

[阅读全文](https://timyefi.github.io/posts/three-layer-backtest-framework.html) · [Markdown 原文](posts/three-layer-backtest-framework.md)

### [检索为什么比重新读一遍便宜](https://timyefi.github.io/posts/retrieval-cheaper-than-reread.html)

*2026-09-13*

研究员的长期记忆不该放在模型权重里，而应是一个能被秒级检索的本地文档库：1341 篇、2390 万字的三份语料统一检索，一次查询返回不到全库的万分之一点二，五十毫秒出结果——省下的不只是查找时间，还有不去核实的借口。

[阅读全文](https://timyefi.github.io/posts/retrieval-cheaper-than-reread.html) · [Markdown 原文](posts/retrieval-cheaper-than-reread.md)

### [把一份 Excel 数据库复刻成一个能跑的东西](https://timyefi.github.io/posts/excel-model-to-runnable-skill.html)

*2026-09-12*

从一张没人敢动的 Excel 数据库出发：先解剖公式与真值再写代码，把数据、逻辑、判断拆成三层，把不能猜的口径问清楚，最后用可重跑的对账证明迁移完成。

[阅读全文](https://timyefi.github.io/posts/excel-model-to-runnable-skill.html) · [Markdown 原文](posts/excel-model-to-runnable-skill.md)

### [这不是答案](https://timyefi.github.io/posts/this-is-not-the-answer.html)

*2026-09-10*

Skill 不是答案，AGI 也不是答案。答案在使用过程中产生——每个人的机器、每个人的数据都需要被单独训练，通用模型解决不了智能在个人这一侧落地的问题。

[阅读全文](https://timyefi.github.io/posts/this-is-not-the-answer.html) · [Markdown 原文](posts/this-is-not-the-answer.md)

---

## 关于

这里的文字全部来自本机实践中的一次具体观察，尽量写得可以照着做。

工具、架构手册与研究框架见 [GitHub 主页](https://github.com/timyefi)。

## 许可

文章内容采用 CC BY-NC 4.0 许可：**转载请注明来源链接**（不署个人名）、非商业使用。商业用途需另行授权。
