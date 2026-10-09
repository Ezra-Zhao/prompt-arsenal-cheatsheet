# 🎯 提示词武器库（中文版 · 中英双语）

> 12 个高频场景，每行：场景 + 可直接复制的提示词（中英双语）+ 一句效果说明。
> 提示词全部原创，不搬运任何提示词库。用法：把 [括号] 换成你的内容，直接粘贴。

---

| # | 场景 | 提示词（复制即用） | 为什么有效 |
|---|---|---|---|
| 1 | 代码 debug | 这段代码报错[粘贴报错+代码]，先告诉我根因，再给最小改动修复，不要重写整个文件。<br>EN: This code throws [paste error + code]. Tell me the root cause first, then give the minimal fix. Don't rewrite the whole file. | 逼模型先诊断后动手，杜绝"看起来修好了"的幻觉修复 |
| 2 | 改简历 | 你是 tech recruiter，用 30 秒扫这份简历，列出 3 个让你想关掉它的原因，再逐条改。<br>EN: Act as a tech recruiter. Scan this resume in 30 seconds, list 3 reasons you'd close it, then fix each one. | 用面试官视角倒逼简历改到点子上 |
| 3 | 数据清洗 | 把这份 CSV 的问题列出来（空值、格式、重复），修完再输出，不要直接给结果。<br>EN: List this CSV's problems (nulls, formats, duplicates) first, fix them, then output. Don't give results directly. | 先审计后处理，避免脏数据污染结论 |
| 4 | 画图 / PPT 大纲 | 先给我 3 种叙事结构（一句话版），我选一种你再展开成 10 页大纲。<br>EN: Give me 3 narrative structures (one line each) first. I'll pick one, then expand it into a 10-slide outline. | 先定结构再填内容，返工少一半 |
| 5 | 学英语 | 用这 10 个单词编一个 120 词的职场小故事，标出每个单词的常用搭配。<br>EN: Write a 120-word workplace story using these 10 words, marking each word's common collocations. | 语境记忆比背单词表牢得多 |
| 6 | 工作邮件 | 把这封邮件改成 3 句话：结论先行，每句不超过 20 字，语气坚定不卑微。<br>EN: Rewrite this email in 3 sentences: conclusion first, max 20 words each, firm but not servile. | 结论先行是职场邮件的通用最优解 |
| 7 | 读书 / 论文总结 | 用"一句话观点+三个论据+一个反例"总结这篇文章，并标出作者没说透的假设。<br>EN: Summarize with "one-line thesis + three arguments + one counterexample", and flag the author's unstated assumptions. | 逼出批判性阅读，而不是复述 |
| 8 | 翻译 | 把这段翻成英文，要求：短句、不套话，翻完回译一遍检查意思走样。<br>EN: Translate to English: short sentences, no clichés, then back-translate once to check for drift. | 回译自检是抓翻译走样的最便宜方法 |
| 9 | 面试准备 | 你当面试官，针对这个 JD 连问 5 个追问，每个都要我拿数字回答，答不上来就逼问。<br>EN: Interview me for this JD. Ask 5 follow-ups, each demanding a numeric answer. Press harder when I can't answer. | 压力面试模拟；数字回答是技术面试的硬通货 |
| 10 | 学新技术 | 用"先给心智模型，再给最小可用例子，最后列 3 个最容易踩的坑"教我[技术名]。<br>EN: Teach me [tech] with: mental model first, then a minimal working example, then the 3 most common pitfalls. | 心智模型+坑位表是最快的上手路径 |
| 11 | 写周报 | 把这 5 条流水账压缩成 3 条：做了什么（数字）、卡在哪（需要谁）、下周干什么。<br>EN: Compress these 5 lines into 3: what I did (numbers), what's blocked (needs whom), next week. | 周报只回答这三个问题，领导才看得下去 |
| 12 | 头脑风暴 / 起名 | 给[产品]起 10 个名字：2 个音节内、有商标感、无负面谐音，先发散再收敛到 3 个。<br>EN: Name [product]: 10 options, ≤2 syllables, trademarkable feel, no bad puns. Diverge first, then narrow to 3. | 先发散后收敛，避免被第一个想法锚定 |

---

**通用技巧（所有提示词都适用）：**
- 把约束写进提示词（字数、句数、格式），输出质量翻倍。
- 先让模型"列出方案"再"展开执行"，两步走比一步到位好。
- 凡是重要输出，加一句"做完自己检查一遍再发给我"。
