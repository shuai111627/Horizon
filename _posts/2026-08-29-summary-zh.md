---
layout: default
title: "Horizon Summary: 2026-08-29 (ZH)"
date: 2026-08-29
lang: zh
---

> 从 16 条内容中筛选出 11 条重要资讯。

---

**AI 创作者雷达**
1. [GLM-5.3 开放权重发布](#item-ai-creator-1) ⭐️ 9.0/10
2. [AI 让漏洞传闻变成可利用代码？维护者披露量激增](#item-ai-creator-2) ⭐️ 8.0/10
3. [观点：GUI 是否应完全键盘驱动](#item-ai-creator-3) ⭐️ 5.0/10
4. [OpenAI Python SDK 迁移至 httpx2，以规避 httpx 1.0 破坏性变更](#item-ai-creator-4) ⭐️ 5.0/10
5. [Htmx 4.0 发布](#item-ai-creator-5) ⭐️ 2.0/10
6. [网传 OpenAI 因 SpaceX 收购 Cursor 做出决定，消息尚未证实](#item-ai-creator-6) ⭐️ 2.0/10
7. [美国制裁意大利托管服务商 Autistici Inventati](#item-ai-creator-7) ⭐️ 2.0/10
8. [《盗梦空间》式弯曲地图导航演示引热议](#item-ai-creator-8) ⭐️ 2.0/10

**财经新闻**
1. [美国上诉法院裁定体育赛事合约不属于掉期交易，为最高法院审理铺路](#item-finance-news-1) ⭐️ 7.0/10
2. [沃什讲话后美联储 9 月加息概率上升](#item-finance-news-2) ⭐️ 7.0/10

**政策资讯**
1. [德桑蒂斯政府拟监管佛罗里达州从学前到博士阶段的人工智能应用](#item-policy-news-1) ⭐️ 7.0/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [GLM-5.3 开放权重发布](https://huggingface.co/zai-org/GLM-5.3) ⭐️ 9.0/10

Z.ai 发布了名为 GLM-5.3 的开放权重模型，入口包括 z.ai/blog/glm-5.3 和 Hugging Face 上的 zai-org/GLM-5.3。材料没有给出具体参数规模、评测分数或价格；可以确认的是，模型已经以 open-weight 形式公开，开发者可以实际下载试用。社区讨论多集中于它和 DeepSeek Flash、Kimi 等开放权重模型的对比。

hackernews · jeudesprits · 8月28日 15:20 · [社区讨论](https://news.ycombinator.com/item?id=49479878)

**「为什么现在值得注意」** GLM-5.3 是刚发布的开放权重模型，Hacker News 讨论中用户已把它放进“能否替代 DeepSeek Flash / 新 GLM Flash”的选项里。需要注意的是，这些评价来自早期上手体验，尚未有独立基准或第三方价格数据来验证。

**「内容切入角度」** 可做角度：从“开放权重的长思考成本”切入，整理社区对 GLM-5.3 在复杂数据分析任务中输出 token 数与准确率之比的观察，并说明这只是个别用户的工作负载体验，不是普遍结论。

**「社区讨论」** 多数参与讨论的开发者给出正面评价，例如认为 GLM-5.3 比 DeepSeek Flash“更有直觉”，用起来“很像 Opus 4.8”，并预期第三方托管的价格和速度会更好。分歧在于，也有人认为它整体能力仍略逊于 Kimi，只是更容易本地运行；因此现在还不能把任何一方观点当作定论。

**标签**: `#GLM-5.3`, `#开放权重`, `#Z.ai`, `#AI模型`, `#开源`

---

<a id="item-ai-creator-2"></a>
### [AI 让漏洞传闻变成可利用代码？维护者披露量激增](https://anil.recoil.org/notes/rumour-is-the-exploit) ⭐️ 8.0/10

avsm 发布文章指出，如今只需一条漏洞传闻，就可能借助 AI 工具生成可利用代码。rclone 维护者 nickcw 在评论中称，项目前 10 年通过 GitHub 收到约 20 份安全披露，而最近一个月就收到超过 40 份，且其中约 75% 有值得检查的内容，这占用了大量维护时间。

hackernews · avsm · 8月28日 15:58 · [社区讨论](https://news.ycombinator.com/item?id=49480466)

**「为什么现在值得关注」** 据维护者 nickcw 描述，安全披露数量在近一个月内急剧增加，与项目早期十年形成鲜明对比，说明 AI 辅助漏洞挖掘对开源维护者带来的压力已经发生，而不是停留在推测层面。

**「内容角度」** 可做角度：从开源维护者的信箱变化切入，梳理 AI 工具如何让“一句传闻”变成需要人工审核的安全披露，并讨论维护者用 AI 工具分流和修复的实践与代价。

**「社区讨论」** 评论中，有的维护者强调披露量激增和审核负担；有人认为这不是 LLM 带来的全新问题，而是利用漏洞的门槛被规模化、民主化；还有人提出部署和供应链更新才是更难解决的环节。

**标签**: `#AI安全`, `#漏洞利用`, `#开源维护`, `#大模型应用`, `#开发者生态`

---

<a id="item-ai-creator-3"></a>
### [观点：GUI 是否应完全键盘驱动](https://ckardaris.com/blog/2026/08/28/keyboard-driven-guis.html) ⭐️ 5.0/10

一篇署名 ckardaris 的博客文章提出“GUI 应该完全由键盘驱动”的主张，并围绕可达性、高级用户需求和包容性展开讨论。文章本身是观点讨论，没有提供具体产品变更、新版本或可验证的开发事实；它在 HN 上引发了评论区的争论。关键可验证细节是文章标题、作者和链接，受影响的人群主要是残障用户、高效操作需求者以及依赖直观图形界面的普通用户。

hackernews · ckardaris · 8月28日 15:17 · [社区讨论](https://news.ycombinator.com/item?id=49479837)

**「为何值得注意」** 它之所以在当下值得注意，是因为评论者将键盘可达性与 ADA 合规、软件民主化等议题联系在一起；但目前只能确认“讨论正在发生”，不能确认它会对实际产品或行业做法产生影响。

**「内容角度」** 可做角度：从评论中“键盘可达性是无障碍基本要求”与“不能把高级用户习惯强加给所有人”的张力切入，讨论 GUI 默认设计是否应把键盘驱动放在首位；可以结合 ADA 工作者的实测建议，但避免把个别评论当成定论。

**「社区讨论」** 评论区存在明显分歧：一方以无障碍工作者的实际经验强调键盘可达性关乎平等访问，另一方则认为不应把高级用户偏好强加给普通用户。还有人区分了“键盘兼容”和“真正键盘驱动”，指出快捷键发现性以及按钮与键盘的适配问题。

**标签**: `#keyboard accessibility`, `#GUI design`, `#UX`, `#accessibility`, `#power users`

---

<a id="item-ai-creator-4"></a>
### [OpenAI Python SDK 迁移至 httpx2，以规避 httpx 1.0 破坏性变更](https://github.com/openai/openai-python/blob/main/httpx2.md) ⭐️ 5.0/10

OpenAI 的 Python SDK 正在迁移到 httpx2 分支，以避开 httpx 官方 1.0 版本可能的破坏性变更。根据分析摘要和社区评论，Anthropic 也在 OpenAI 之后数周做出了同样的迁移选择。该变化主要影响 openai-python 与 anthropic-sdk-python 的开发者，但具体迁移完成时间和对下游项目的影响尚未有更多细节。

hackernews · tosh · 8月28日 11:51 · [社区讨论](https://news.ycombinator.com/item?id=49477212)

**「为何值得注意」** 在 httpx 官方 1.0 可能带来破坏性变更的背景下，OpenAI 和 Anthropic 两家 SDK 都选择了 httpx2 这个兼容性分支，显示大型 SDK 在依赖策略上对稳定性的优先考虑。这一事件正在开发者社区引发关于 fork 维护成本与替代方案的讨论，但它对下游项目的实际影响尚未证实。

**「内容角度」** 可做角度：从 openai-python 与 anthropic-sdk-python 改用 httpx2 的决策切入，梳理主流 SDK 面对上游 HTTP 客户端大版本破坏性更新时的稳定优先策略，并探讨这类 fork 依赖对下游项目升级路径可能带来的长期维护成本。全篇应基于现有事实，不把推测写成结论。

**「社区讨论」** 评论中有观点解释，httpx2 是 httpx 的 fork，承诺不破坏现有 API，因此更适合作为依赖；Anthropic 也在 OpenAI 之后数周做了同样迁移。另有人询问是否评估过 niquests 等替代方案，或质疑这次迁移的实际收益；也有人反映使用中遇到网络错误并表达不满。以上仅属部分评论者看法，并非整体共识。

**标签**: `#openai-python`, `#httpx2`, `#python-sdk`, `#dependency-management`, `#anthropic-sdk`

---

<a id="item-ai-creator-5"></a>
### [Htmx 4.0 发布](https://four.htmx.org/announcements/2026-08-28-htmx-4.0.0-is-released) ⭐️ 2.0/10

Htmx 4.0（版本号 4.0.0）于 2026 年 8 月 28 日发布，公告页面位于 four.htmx.org。它是一个前端超媒体库，主要面向 Web 开发场景。公告未提供具体功能细节，目前也没有与 AI 创作或使用直接相关的内容。

hackernews · rmsaksida · 8月28日 13:28 · [社区讨论](https://news.ycombinator.com/item?id=49478178)

**「社区讨论」** 评论区出现一定分化：有开发者表示喜欢 htmx 并期待新版本，也有人认为在 .NET 与 Angular 背景下 htmx 会让后端重新承担界面呈现职责，反而增加复杂度；还有开发者提到自己在 HTMX 4 项目中改用体积更小的 Alpine Ajax。另有评论自称 HTMX CEO，但未提供进一步背景。整体上看，这些多为个人经验分享，不能代表普遍结论。

**标签**: `#htmx`, `#前端开发`, `#web框架`, `#发布公告`

---

<a id="item-ai-creator-6"></a>
### [网传 OpenAI 因 SpaceX 收购 Cursor 做出决定，消息尚未证实](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/) ⭐️ 2.0/10

一条 Hacker News 帖子称，OpenAI 在 Cursor 被 SpaceX 收购后做出了相关决定，并附有 openai.com 的链接。但目前没有原始公告内容可核实，评论区讨论的是 xAI 而非 SpaceX，因此这条消息很可能属于误传或讽刺。若消息属实，受影响的是 Cursor 用户及他们对 OpenAI 模型的访问；但截至现有材料，尚无任何官方确认。

hackernews · meetpateltech · 8月29日 01:47 · [社区讨论](https://news.ycombinator.com/item?id=49486172)

**「为什么现在值得注意」** 社区讨论把这件事与模型提供商限制被竞争对手收购的编辑器接入联系起来，并提到 Anthropic 此前曾因类似条款问题禁止过 xAI。但这些都是评论者的推测或转述，不是已证实的事实；目前唯一可确认的是该消息正在 Hacker News 上传播。

**「可做角度」** 可做角度：把标题中的“SpaceX”与评论区里的“xAI”对照，做一条事实核查式内容，梳理 OpenAI 是否真对 Cursor 采取行动，以及社区为何把这件事与模型蒸馏、API 转售争议联系起来；避免把未经证实的传言直接当成结论。

**「社区讨论」** 评论区观点不一：有人认为 Cursor 转售第三方 API 的模式本就难以为继，被竞争对手收购后更容易被断供；也有人表示自己会继续使用 Grok/Composer，或转向 Anthropic。少数评论提到 Anthropic 此前已禁止过 xAI，但这一类说法仍需单独核实。

**标签**: `#OpenAI`, `#Cursor`, `#SpaceX`, `#xAI`, `#AI模型接入`

---

<a id="item-ai-creator-7"></a>
### [美国制裁意大利托管服务商 Autistici Inventati](https://www.inventati.org/) ⭐️ 2.0/10

美国将意大利托管服务商 Autistici Inventati 列入制裁名单，并将其指定为“全球恐怖分子”。该服务商托管了 noblogs.org 和 autistici.org 等网站，制裁后部分站点已无法访问。目前公开材料没有提供具体的制裁依据，社区对相关指控存在争议。

hackernews · exiguus · 8月28日 12:58 · [社区讨论](https://news.ycombinator.com/item?id=49477854)

**「内容角度」** 可做角度：从 Autistici Inventati 被制裁事件，讨论依赖第三方托管服务的项目面临的地缘政治风险，以及维护者应如何审视自己的基础设施供应链——无论这些项目是博客、邮件服务还是其他数字工具。

**「社区讨论」** 评论区的关注点主要集中于两点：一是认为把基础设施提供商整体标为“恐怖分子”是前所未有的危险先例，可能对 I2P、Monero 等去中心化技术带来寒蝉效应；二是质疑制裁依据不足，表示找不到该组织直接支持 PKK 的证据。也有评论认为该组织自身信息不透明，难以判断其实际行为。

**标签**: `#美国制裁`, `#互联网自由`, `#托管服务商`, `#数字权利`

---

<a id="item-ai-creator-8"></a>
### [《盗梦空间》式弯曲地图导航演示引热议](https://www.orbify.eu/demo/) ⭐️ 2.0/10

orbify.eu 上有一个《盗梦空间》风格的弯曲地图导航演示，把逐向导航画成弧形地图。该演示由用户 smoser 分享到 Hacker News，并引发讨论。社区反馈主要认为概念有趣，但也指出转弯瞬间及连续转弯时路线信息不足、预测距离不稳定，以及可能引发晕动症等问题。由于没有提供原始正文，目前只能基于分享信息和评论来了解该演示。

hackernews · smoser · 8月28日 12:29 · [社区讨论](https://news.ycombinator.com/item?id=49477564)

**「社区讨论」** Hacker News 评论中，pmkary 称赞这是“纯正的 Bret Victor 式魔法”，表示非常喜欢；sd9 认为概念很棒，但转弯前几乎无法获知前方路线，连续转弯会难以导航；orbital-decay 觉得这种投影会让急转弯后的路段离开屏幕，也没通过旋转视角来补偿，导致有效预测距离不断变化；tantalor 则戏称看到了“晕动症即服务”的新品类。另有评论者提到，类似思路在 Berg 2009 年的“Here and There”海报中已有体现。

**标签**: `#visualization`, `#navigation`, `#demo`, `#ux`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美国上诉法院裁定体育赛事合约不属于掉期交易，为最高法院审理铺路](https://www.cnbc.com/2026/08/28/appeals-court-rules-against-prediction-markets-tees-up-scotus-fight.html) ⭐️ 7.0/10

美国第九巡回上诉法院裁定，与体育赛事相关的事件合约不属于掉期交易，这与今年 4 月第三巡回上诉法院的裁决相矛盾，很可能促使最高法院介入审议预测市场的监管问题。

rss · CNBC Finance · 8月29日 02:23

**「背景」** 此案涉及 Kalshi 等预测市场平台提供体育赛事合约。第九巡回上诉法院裁定这些合约不属于掉期，且 Kalshi 自行认证并挂牌这些合约违法；这与四月第三巡回上诉法院认为只有 CFTC 有权监管体育赛事合约的裁决相矛盾，形成巡回法院分歧，可能促使最高法院介入。

**「影响」** 这一裁决与第三巡回上诉法院 4 月的裁决相矛盾，使最高法院受理相关案件的可能性大增；交易员目前估计，最高法院在 2026 年底前受理体育赛事合同案件的概率为 64%，Kalshi 等预测市场平台在监管归属明确前仍面临不确定性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/08/28/appeals-court-rules-against-prediction-markets-tees-up-scotus-fight.html">U.S. appeals court rules against prediction markets, sets up likely fight at Supreme Court</a></li>
<li><a href="https://arstechnica.com/tech-policy/2026/08/kalshi-cant-evade-nevada-gambling-laws-by-calling-bets-swaps-court-rules/">Court rules Kalshi sports bets aren&#x27;t &quot;swaps,&quot; just gambling with a different name - Ars Technica</a></li>
<li><a href="https://www.cbsnews.com/news/kalshi-appeals-court-nevada-gambling-ruling/">Court hands U.S. states a win in fight over who regulates prediction markets - CBS News</a></li>
<li><a href="https://www.cnbc.com/2026/08/28/appeals-court-rules-against-prediction-markets-tees-up-scotus-fight.html">U.S. appeals court rules against prediction markets, sets up likely fight at Supreme Court</a></li>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/04/federal-appeals-court-cftc-jurisdiction-over-sports-event-contracts">Federal Appeals Court: CFTC Jurisdiction Over Sports Event Contracts Likely Exclusive | Insights | Holland &amp; Knight</a></li>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/02/prediction-markets-at-a-crossroads-the-continued-jurisdictional-battle">Prediction Markets at a Crossroads: The Continued Jurisdictional Battle Over Event Contracts | Insights | Holland &amp; Knight</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#court ruling`, `#regulation`, `#CFTC`, `#Supreme Court`

---

<a id="item-finance-news-2"></a>
### [沃什讲话后美联储 9 月加息概率上升](https://www.cnbc.com/2026/08/28/-september-fed-decision-now-a-coin-flip-as-rate-hike-odds-increase.html) ⭐️ 7.0/10

据 CNBC 报道，美联储理事沃什在杰克逊霍尔表示仍对整体通胀趋势感到不满，此后市场对美联储 9 月加息的预期升温，目前加息概率已接近五五开。

rss · CNBC Finance · 8月28日 15:22

**「背景」** 美联储主席凯文·沃什在杰克逊霍尔央行年会上发表讲话，明确表示通胀仍然过高，今夏的物价数据并不意味着“实质性”改善，并暗示未来几个月可能需要加息。此番表态比他以往的表态更为清晰，市场随之提高了对 9 月加息的押注。

**「影响」** 市场定价显示，美联储 9 月加息概率在沃什讲话后升至约 59%（也有报道称 68%），高于此前的“五五开”预期。若加息落地，房贷、企业贷款等借贷成本将上升，对借款人和股票等风险资产构成压力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/08/28/kevin-warsh-jackson-hole-federal-reserve-inflation.html">Fed Chairman Warsh warns on inflation at Jackson Hole</a></li>
<li><a href="https://www.npr.org/2026/08/28/nx-s1-5947903/federal-reserve-inflation-jackson-hole-interest-rates">Fed&#x27;s Kevin Warsh warns inflation is too high, sparking bets rate hikes are coming</a></li>
<li><a href="https://apnews.com/article/federal-reserve-warsh-interest-trump-inflation-ab896df808df3a5a3fa8b943ac5f3867">Fed Chair Warsh signals rate hikes may be needed with US inflation stubbornly elevated</a></li>
<li><a href="https://www.benzinga.com/markets/prediction-markets/26/08/61499396/fed-hike-odds-warsh-jackson-hole">Fed September Hike Odds Spike to 59% After Warsh’s Jackson Hole Speech - Benzinga</a></li>
<li><a href="https://www.investopedia.com/fed-chair-warsh-in-jackson-hole-speech-12071137">Warsh Talked Tough On Inflation At Jackson Hole, And Markets Believe Him</a></li>

</ul>
</details>

**标签**: `#Federal Reserve`, `#Monetary Policy`, `#Interest Rates`, `#Inflation`, `#Jackson Hole`

---

## 政策资讯

<a id="item-policy-news-1"></a>
### [德桑蒂斯政府拟监管佛罗里达州从学前到博士阶段的人工智能应用](https://news.google.com/rss/articles/CBMipAFBVV95cUxQd3hBWVdrZ05XVmlhZDg2ckM4S0RIRko5cUZDWV9OY1ZENTVnbTB5Z2RpcVA0aGZJR0piRTBJM01ZXzJYY2Q5ZWFxNDFOZmV4c0J6N0FtbmpDal9Yb1RnbW5kNkd2SDltaWVhbm16T2xsY1cycjZqVm12WWdoSkdXdGgtNUJseUU5enZZdW8teXh2NjJlOGJkX2Y0dG5qaHd2VC1URg?oc=5) ⭐️ 7.0/10

据《佛罗里达凤凰报》报道，佛罗里达州德桑蒂斯政府正在推动对人工智能在教育领域的监管，范围覆盖从学前班（Pre-K）到博士（Ph.D.）阶段。目前公开信息仅表明行政当局已启动相关监管进程；具体法律地位、规则文本、生效日期和执行机制尚未披露。受影响对象可能包括佛罗里达州各级教育机构、学生、教师以及提供 AI 教育工具或服务的相关方。由于信息有限，尚不能断定该举措已形成正式法规或行政命令，需关注后续州教育部门或立法机构的正式文件。

rss · AI Regulation News · 8月28日 04:28

**「政策机制解析」** 佛罗里达州教育系统正在推进与人工智能相关的监管规则。根据报道，佛罗里达州教育部（Florida Department of Education）于 2026 年 8 月 27 日提出一项规则，要求该州所有公立学院（public colleges）采纳涉及人工智能的政策（tool-1-2）。此外，管理佛罗里达 12 所州立大学的州董事会（Florida Board of Governors）也计划在“下周”审议相关措施，并与负责公立 Pre-K 至博士阶段的州机构协同实施涉及安全与课堂使用人工智能的政策（tool-1-1）。州长德桑蒂斯（Ron DeSantis）曾表示，尽管特朗普总统发布行政命令试图建立全国性 AI 监管框架，佛罗里达州仍有权自行制定 AI 规则（tool-1-3）。

需要区分官方文本与媒体解读：目前明确可查的官方动作是州教育部提出的“要求公立学院采纳 AI 政策”的规则草案，媒体将其概括为“从 Pre-K 到博士阶段监管 AI”，但官方全文尚未在现有资料中披露。该规则当前处于“拟议”阶段，尚未最终通过；州董事会的“下周”会议是否正式表决该项规则，仍需关注后续官方议程。

对相关方的影响（含推断）：若规则通过，佛罗里达州公立学院及州立大学将被赋予明确义务，需自行制定 AI 使用与安全政策；K-12 学区和高等教育机构可能需在课程、学生数据使用、AI 工具课堂应用等方面作出合规调整。具体执行机制（如审核流程、违规处罚）尚不明确，需等待正式规则文本。

**「影响评估」** 根据来源，美国佛罗里达州 DeSantis 政府正着手对从学前教育（Pre-K）到博士（Ph.D.）的 AI 使用进行监管。目前仅是行政动向，尚未公开具体规则文本、生效日期或执法机制，因此以下影响为基于现有信息的推断。

受影响方：佛罗里达州各级公立和私立教育机构（K-12 学区、大学、职业培训项目）将成为直接监管对象；教师和学生使用 AI 工具（如 ChatGPT、辅助写作、自动评分、学习分析）的行为可能受到限制或要求披露；为佛罗里达提供教育软件、在线课程和学习管理系统的科技公司（edtech 供应商）将面临新的合规义务，例如算法透明度、数据隐私保护、防偏见评估和人工监督要求；开展 AI 研发的大学实验室也可能受到州级伦理审查。

市场影响：在规则落实后，针对佛罗里达市场的 AI 教育产品可能需要调整功能和合同条款，供应商需记录模型使用方式并证明符合州标准；学校采购流程可能放慢，短期抑制部分 AI 工具进课堂，长期推动“可解释、可审计”的教育 AI 产品需求上升。

社会影响：民调显示多数美国选民希望加强对校园 AI 的监管（tool-2-1），该动向与公众预期一致。联合国教科文组织也倡导在教育中伦理使用 AI（tool-2-2），州级规则可能参考这些框架，强调以学习者为中心、公平获取和防止技术替代师生关系。

需要明确的不确定性：本报道仅说“正在监管”，不等于已成法或已生效；实际义务、处罚和过渡期均未公布。DeSantis 政府可能通过行政命令、州教育委员会规则或立法提案推进，不同路径对学校和企业的约束力不同。后续应关注佛罗里达州教育部/州教育委员会的正式规则制定公告。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://floridaphoenix.com/2026/08/28/desantis-administration-moving-to-regulate-ai-from-pre-k-to-phd/">DeSantis administration moving to regulate AI from Pre-K to PhD • Florida Phoenix</a></li>
<li><a href="https://www.floridatrend.com/articles/2026/08/27/florida-proposes-rule-requiring-all-public-colleges-adopt-ai-policies/">Florida proposes rule requiring all public colleges to adopt AI policies</a></li>
<li><a href="https://thehill.com/homenews/administration/5649792-florida-desantis-ai-regulation/">DeSantis: Florida has ‘right’ to regulate AI rules despite Trump’s order</a></li>
<li><a href="https://www.tampabay28.com/us-news/education/poll-americans-want-stronger-rules-for-ai-in-schools">Poll: Americans want stronger rules for AI in schools</a></li>
<li><a href="https://www.unesco.org/en/digital-education/artificial-intelligence">Artificial intelligence in education - AI | UNESCO</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#education`, `#Florida`, `#policy`

---