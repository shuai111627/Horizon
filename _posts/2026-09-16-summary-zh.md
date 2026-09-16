---
layout: default
title: "Horizon Summary: 2026-09-16 (ZH)"
date: 2026-09-16
lang: zh
---

> 从 18 条内容中筛选出 12 条重要资讯。

---

**AI 创作者雷达**
1. [TypeSafe.ai 发布 System One Models 与 Jev，聚焦快速类型化推理](#item-ai-creator-1) ⭐️ 7.0/10
2. [Show HN：会听鸟、并把鸟画成 19 世纪插画的电子墨水屏相框](#item-ai-creator-2) ⭐️ 7.0/10
3. [互联网档案馆更新 Wayback Machine 访问防护，应对高流量自动抓取](#item-ai-creator-3) ⭐️ 7.0/10
4. [Gemini 3.8 Live 系列被指发布：仅有链接与社区讨论，缺少官方细节](#item-ai-creator-4) ⭐️ 7.0/10
5. [据 Strix 博客：AI agent 25 分钟获取 Baseten 生产 GitHub 管理员权限](#item-ai-creator-5) ⭐️ 6.0/10
6. [Capsule：把 HTML 应用与数据打包进单个 SQLite 文件](#item-ai-creator-6) ⭐️ 5.0/10
7. [Simon Willison 发布 Gemini Live 语音试用网页工具](#item-ai-creator-7) ⭐️ 3.0/10
8. [Show HN：把 20 美元 4G 热点改造成短信设备](#item-ai-creator-8) ⭐️ 2.0/10
9. [Hacker News 讨论消费品质量与隐性通胀](#item-ai-creator-9) ⭐️ 1.0/10
10. [美国首次确认部署太空武器](#item-ai-creator-10) ⭐️ 1.0/10
11. [荷兰铁路疑遭破坏致大面积停运](#item-ai-creator-11) ⭐️ 0.0/10

**财经新闻**
1. [中国 8 月零售未达预期、投资下滑加深，工业产出超预期](#item-finance-news-1) ⭐️ 7.0/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [TypeSafe.ai 发布 System One Models 与 Jev，聚焦快速类型化推理](https://typesafe.ai/blog/introducing-system-one-models-and-jev) ⭐️ 7.0/10

TypeSafe.ai 在其博客发布了 System One Models 与 Jev，将其定位为面向快速类型化/结构化推理的模型，相关内容在 Hacker News 上引发讨论。材料中没有可核实的版本、日期或价格信息，公告页面内容也未获取到，因此公告自身的细节无法确认。评论者认为这类模型可能对分类和结构化输出等场景有用，同时质疑其速度对比的基准是否公平，以及它的能力范围是否仅限于结构化输出。

hackernews · albelfio · 9月15日 19:25 · [社区讨论](https://news.ycombinator.com/item?id=49717558)

**「为何当下值得注意」** 该发布目前正伴随 Hacker News 上的活跃讨论，争议集中在速度对比的可比性与适用范围界定上；材料中尚未看到官方对这些质疑的回应，因此相关影响仍属未证实。

**「内容角度」** 可做角度：以“公告 vs 文档”的落差为线索，梳理 System One Models / Jev 究竟做什么——评论者称文档描述其输入为状态加问题（Yes/No、多选或打分）、输出为答案及相应概率或置信度，并指出这些机制只出现在文档而非公告中，由此讨论“结构化推理”与通用生成模型之间的速度对比为什么容易被误读。

**「社区讨论」** 多数评论认可这是一个有新意的方向，并认为对分类、结构化输出等任务可能实用；分歧在于它的速度对比是否具备可比性，以及它只能生成结构化输出、能力范围是否被高估。有评论者指出官方文档比公告解释得更清楚，也有人提到这类模型与契约式（design-by-contract）模式结合的可能。

**标签**: `#System One Models`, `#Jev`, `#structured inference`, `#typed inference`, `#LLM`

---

<a id="item-ai-creator-2"></a>
### [Show HN：会听鸟、并把鸟画成 19 世纪插画的电子墨水屏相框](https://github.com/arnegiacomo/fugleramme) ⭐️ 7.0/10

这是一个发布在 Hacker News 的 Show HN 项目「fugleramme」，代码托管在 GitHub（作者 arnemunthekaas）。它用电子墨水屏做成相框，通过鸟类声音分类识别附近的鸟，再以 19 世纪风格的插画呈现出来。可验证的细节之一是底层分类器为 BirdNET——评论中有人指出它是传统神经网络而非大语言模型，并给出论文 DOI（10.1016/j.ecoinf.2021.101236）。材料未说明插画是如何生成或选取的，这部分仍不确定。

hackernews · arnemunthekaas · 9月15日 12:31 · [社区讨论](https://news.ycombinator.com/item?id=49711544)

**「为什么值得关注」** 材料显示该项目在 Hacker News 上引发了较强兴趣，评论者用「近期最酷的项目」来形容它。同时源内容列出相关条目「Avian Visitors」（标注为 May 2026，20 条评论），评论者也提到近期鸟类相关项目集中出现，并把其中一部分归因于开源项目 birdnet-go——这属于社区观察，并非已证实的影响。

**「内容角度」** 可做角度：以这个电子墨水屏相框为案例，讲一个「边缘 AI 小项目」的完整链路——本地音频采集、BirdNET 这类传统分类模型做识别、再由渲染层输出视觉内容；顺带纠正一个常见误解，即 BirdNET 并不是大语言模型。插画生成环节的具体实现，因材料未说明，可作为待核实的点留白。

**「社区讨论」** 评论区整体偏正面：jadbox 认为它把多种想法融合成了「有魔法感」的作品，thomasfl 称其为开发者 Arne Munthe-Kaas 的纯粹艺术。补充与分歧主要来自技术层面——divbzero 强调 BirdNET 是传统神经网络而非 LLM；theturtletalks 提到近期鸟类项目很多并联系到 birdnet-go；joshstrange 则分享自己用 4 块墨水屏配 ESP32/BTLE 显示书摘的体验，并估算 BTLE 墨水屏单次充电可用一年以上（属个人计算，非实测结论）。

**标签**: `#边缘AI`, `#鸟类识别`, `#电子墨水屏`, `#创意编程`, `#BirdNET`

---

<a id="item-ai-creator-3"></a>
### [互联网档案馆更新 Wayback Machine 访问防护，应对高流量自动抓取](https://blog.archive.org/2026/09/15/an-update-on-wayback-machine-access/) ⭐️ 7.0/10

互联网档案馆官方博客发布《An Update on Wayback Machine Access》，称 Wayback Machine 近期遭遇多轮高流量自动抓取，已部署防护措施以维持服务运行，并提到已有部分站点选择退出存档。博客与讨论中的一个说法是，这些抓取流量可能来自试图绕过原始站点访问限制、转而抓取 Wayback 存档副本的爬虫，但该归因在现有材料中未经独立确认。受影响的是依赖这一非营利基础设施的存档访问方、被存档的站点以及普通用户，评论中已有人反馈在工作网络环境下会反复遇到 429 错误。

hackernews · ChrisArchitect · 9月15日 17:52 · [社区讨论](https://news.ycombinator.com/item?id=49716176)

**「为什么现在值得注意」** 值得注意的已发生变化是：档案馆确认抓取压力上升并已加装访问防护，同时出现站点退出存档的情况，这直接触及开放网络基础设施的可访问性。至于抓取方是否与 AI 数据采集直接相关、防护会带来多大范围的访问影响，材料尚未给出证实。

**「可做角度」** 可做角度：以这次官方更新为切口，梳理“原始站点设限—爬虫转向存档副本—存档服务加防护—站点退出存档”这条链条中各方公开表述与仍属推测的部分，重点讲清 Wayback Machine 作为公共存档在当前抓取压力下如何被使用与消耗，而不预设抓取者的身份或动机。

**「社区讨论」** 评论区整体对互联网档案馆表示支持，有用户提到自己仍可通过 Tor 匿名访问、未遇到中心化网关拦截，也有人建议为其捐款；分歧与疑问集中在访问体验上，例如有人称工作电脑上每次都出现 429、家中和手机上却正常。另有用户分享借存档找回早年个人内容的经历，以及“AI 公司应为访问存档付费”的个人主张，这些均为个别观点而非共识。

**标签**: `#Wayback Machine`, `#Internet Archive`, `#爬虫流量`, `#开放网络`, `#AI 数据采集`

---

<a id="item-ai-creator-4"></a>
### [Gemini 3.8 Live 系列被指发布：仅有链接与社区讨论，缺少官方细节](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/) ⭐️ 7.0/10

Hacker News 上出现一条指向 Google 官方博客的条目，标题为 “Gemini 3.8 Live and 3.8 Live Extended Thinking”，指向 Google 发布两款实时语音相关模型的消息。本次提供的材料只有标题、链接和社区评论，没有公告原文，因此版本号含义、能力边界、可用地区、账号门槛与定价等关键事实均无法核实。评论者提到的使用体验集中在语音自然度、口音识别、延迟以及 Workspace 账号可用性上，属于个人观察，且部分内容可能指更早的 Live 版本。

hackernews · leumon · 9月15日 17:38 · [社区讨论](https://news.ycombinator.com/item?id=49715947)

**「为什么现在值得注意」** 材料显示该条目在 Hacker News 上的讨论热度较高（约 284 分、186 条评论），说明一线厂商的实时语音模型更新仍受关注。但目前能确认的只是“出现了一个指向官方博客的发布链接”，其具体能力与开放范围尚未被材料证实，不能据此判断实际影响。

**「可做角度」** 可做角度：以“公告原文缺失”为切入，先核对 Google 官方博客原文，再决定是否成稿；把评论中可复核的体验点（Workspace 账号能否使用、重口音识别、语音是否自然、延迟感受）整理成一份待验证清单，说明哪些是官方信息、哪些只是用户主观感受。

**「社区讨论」** 评论总体偏正面：Havoc 表示试用后认为重口音识别不错、声音悦耳、延迟较低，并强调能在 Workspace 账号使用；jeanbza 用南非荷兰语做口语练习和语法学习，认为表现超出家人预期。分歧与限制在于，doodlesdev 一方面认为 Live 模式比 GPT Voice 更像真人对话，另一方面指出 Google AI Plus 用户尚未获得 Gemini 3.8；rdtsc 则质疑 Gemini 何时能追赶上竞品，这类比较在现有材料中没有数据支撑。

**标签**: `#Google Gemini`, `#实时语音模型`, `#模型发布`, `#多模态交互`, `#Hacker News 讨论`

---

<a id="item-ai-creator-5"></a>
### [据 Strix 博客：AI agent 25 分钟获取 Baseten 生产 GitHub 管理员权限](https://www.strix.ai/blog/baseten-harbor-github-pat-takeover) ⭐️ 6.0/10

据 Strix 博客，其 AI 渗透测试 agent 在 25 分钟内获取了 Baseten 生产 GitHub 的管理员权限。评论中 swyx 给出时间线：7 月 13 日 23:10 报告了可用的 basetenbot token、公开的 Harbor 项目及仓库权限；7 月 14 日早晨 Harbor 项目被设为私有，但 token 仍有效；同日 16:34 Baseten 安全团队的 Anton 确认该问题为 critical，并称已私有化 Harbor 项目并轮换 token。wxw 引述称，该 token 对 Baseten 主产品仓库、驱动其集群的 GitOps 仓库、Homebrew tap 有 admin/push 权限，并对包括部分客户专属仓库在内的其他私有仓库有读写权限，token 则是在找到 Baseten 镜像仓库后从 Docker 构建历史中发现。影响范围指向 Baseten 的代码仓库与供应链凭证，但来源为厂商博客，且评论对其 AI 特异性存疑。

hackernews · bearsyankees · 9月15日 18:11 · [社区讨论](https://news.ycombinator.com/item?id=49716476)

**「为何值得注意」** 材料中可核实的变化是 Baseten 已确认该问题并轮换 token、Harbor 项目转为私有；至于这类 AI agent 是否带来质变，评论中仍有分歧，材料未提供更广泛的行业数据。

**「内容角度」** 可做角度：以 Strix 披露的事件为案例，梳理一次凭证泄露从 Docker 构建历史到 GitHub 仓库权限的时间线，并并列呈现厂商博客叙述与评论区对“AI 特异性”的质疑，讨论 AI 渗透测试 agent 在供应链安全中的实际增量与验证边界。

**「社区讨论」** 评论区中，swyx 转述了 Baseten 确认问题与轮换 token 的时间线；ivraatiems 和 aatd86 等认为这更像快速发现人类可发现的问题，并质疑这对 Strix 而言是否算有效广告；codemog 则追问此类未授权测试是否合法。讨论共识集中在事件本身及 Baseten 的处理，分歧在于 AI agent 是否具备不可替代的能力。

**标签**: `#AI安全`, `#供应链安全`, `#凭证泄露`, `#AI Agent`, `#Baseten`

---

<a id="item-ai-creator-6"></a>
### [Capsule：把 HTML 应用与数据打包进单个 SQLite 文件](https://withcapsule.app/) ⭐️ 5.0/10

独立开发者在 Hacker News 发布 Capsule（同时是文件扩展名），一个用 Rust 与 Tauri 2.0 编写的工具，可把 HTML 应用及其资源、用户数据打包进单个 SQLite 文件。据作者描述，数据既可用 localStorage 键值方式保存，也可通过类似 MongoDB 的 collections API 存为文档，PDF、图片等资源同样可存入数据库，并支持导出为 CSV 或 JSON。安全方面，文档默认不能访问文件系统，联网需要授权，权限模型作者称仍在改进；文档还可调用本地或远程 AI 模型实现自身功能。作者指出的局限是多人同时使用会产生不同副本，目前依靠每条数据的 UUID 与时间戳支持后续合并，并计划在 1.0 版本开放文件格式规范，且已为每个新版本提供迁移。

hackernews · bashtian · 9月15日 13:31 · [社区讨论](https://news.ycombinator.com/item?id=49712278)

**「为什么现在值得注意」** HN 讨论把这一项目与“用 AI 生成小工具很容易，但装成本地应用或分享出去很难”的现状联系起来，这是它被关注的直接语境。需要区分的是：Capsule 本身是新发布的个人项目，作者自述的功能与计划尚未经过采用或兼容性验证，讨论中提出的同步、更新等需求也仍属未实现的部分。

**「可做角度」** 可做角度：以“AI 写个小工具很容易，装到本地和分享却很难”为切入点，实测 Capsule 这种“HTML 应用加数据打包进单个 SQLite 文件”的方式能否真正解决分发问题，同时如实呈现它的限制——多人协作会各自产生副本、使用前仍需先安装运行器、权限模型仍在改进。

**「社区讨论」** 评论中有人认可这一思路，认为现在用 AI 做小工具很容易，但安装为本地应用或分享很困难，同时提出缺少跨设备同步、应用与数据分离、应用更新等功能（andix）；也有人质疑如果仍需先下载一个运行器，不如直接分发应用本身（nater5000）。另有评论指出浏览器已有 File System Access API 可读写本地文件（mg），并有开发者表示在做类似方案，使用 sqlar 作为格式规范（thederf）。

**标签**: `#AI生成工具`, `#本地优先`, `#SQLite`, `#Tauri`, `#开发者工具`

---

<a id="item-ai-creator-7"></a>
### [Simon Willison 发布 Gemini Live 语音试用网页工具](https://simonwillison.net/2026/Sep/15/gemini-live/) ⭐️ 3.0/10

Simon Willison 发布了一个浏览器端网页工具 Gemini Live audio（tools.simonwillison.net/gemini-live），用于试用语音到语音模型：可选择模型与音色预设、填写可选系统提示词，然后在浏览器里开始语音对话，并支持在模型说话时打断。实现不使用任何库，直接连接 wss://generativelanguage.googleapis.com/ws/google.ai.generativelanguage.v1alpha.GenerativeService.BidiGenerateContent 的 WebSocket 端点，并用 Web Audio API 的 AudioContext 做采集与播放；代码托管在其 GitHub 的 tools 仓库，条目另附一张带转写文本的界面截图。需要注意的是，条目中&quot;Google 今天发布 Gemini 3.8 Live 和 3.8 Live Extended Thinking&quot;这一说法只以一条博客链接带过，条目内没有发布时间、可用范围、能力指标或定价等一手细节，其中出现的 Gemini 3.8、GPT-Live、GPT-6 Astra Extra High 等命名也缺乏可交叉验证的信息，因此这部分目前只能视为待核实。

rss · Simon Willison · 9月15日 22:47

**「为什么现在值得看」** 时间敏感点仅在于条目所称的模型发布，而该说法在条目内缺少一手公告细节，尚未证实。已确凿可查的部分是：现在已有零依赖的浏览器端实现，把实时语音对话的采集、播放与打断放在前端完成，条目还给出了对应的 Gemini Live WebSocket 入门教程链接。

**「内容角度」** 可做角度：以&quot;零依赖网页如何做实时语音对话&quot;为切入口，拆解这个工具用 WebSocket 端点加 Web Audio API 的 AudioContext 完成麦克风采集、音频播放和打断的链路，同时说明它所依据的模型发布信息在条目内仅有一次链接，需要先找到一手公告再决定是否展开。

**标签**: `#语音模型`, `#Gemini Live`, `#实时对话工具`, `#待核实`, `#一手来源缺失`

---

<a id="item-ai-creator-8"></a>
### [Show HN：把 20 美元 4G 热点改造成短信设备](https://bkovac.github.io/modem-thing/) ⭐️ 2.0/10

一名开发者（HN 用户 bobili1234 提交，项目页为 bkovac.github.io/modem-thing/）展示如何把一台 20 美元的 4G 无线热点改造成可以发短信的迷你设备。材料未给出改造所用型号、系统版本、体积、续航等可验证细节，也没有性能对比基线。受影响的是那些用热点代替手机上网、却仍需处理短信和 OTP 的人：按评论描述，他们目前得把 SIM 卡插回手机或打开电脑网页界面才能看到短信。

hackernews · bobili1234 · 9月15日 13:20 · [社区讨论](https://news.ycombinator.com/item?id=49712102)

**「内容角度」** 可做角度：把这条 HN 项目当成一次“选题辨析”的样本——事实主体只是把 20 美元 4G 热点改成短信终端，而评论区“在其上跑 agent 系统”的说法缺少任何 RAM/存储实测数据；可以据此讲清一条硬件改造帖是如何被读成 AI 选题的，以及哪些部分仍属未证实设想。

**「社区讨论」** 评论整体正面：有人表示自己刚花 10 美元买了 4G dongle，打算拆开研究，并提到部分基于 MSM8916 的 dongle 没有屏幕却在运行 Android UI；有人建议并联两节 18650 电池以延长续航；也有人以自带热点代替手机的经验指出，看短信和 OTP 必须插回手机或用电脑网页界面是主要痛点，认为这个改造可当作“哑手机”使用。分歧不大，唯一带 AI 色彩的是个别评论猜测：若 OpenStick 构建的 RAM/存储够用，可在其上跑 Agent 系统，这属于未经证实的设想。

**标签**: `#硬件改造`, `#4G热点`, `#DIY项目`, `#非AI相关`, `#嵌入式设备`

---

<a id="item-ai-creator-9"></a>
### [Hacker News 讨论消费品质量与隐性通胀](https://www.forbrukerradet.no/short-life/) ⭐️ 1.0/10

Hacker News 上出现一条题为《Let&\#x27;s make quality the norm again》的条目，链接指向 forbrukerradet.no/short-life，发布者为 ingve。材料未提供文章正文，因此无法核实文章的具体主张与论据。评论区主要围绕消费品质量是否在下降、这是否是隐性通胀、品牌溢价为何反而激励偷工减料，以及价格容易比较而质量难以验证展开。讨论没有涉及 AI 模型、产品或平台变化。

hackernews · ingve · 9月15日 10:00 · [社区讨论](https://news.ycombinator.com/item?id=49710109)

**「内容角度」** 可做角度：如果要做内容，只能从评论中“价格易比较、质量难验证”这一信息不对称切入，讨论消费者如何在电商描述、品牌信誉和耐用性之间做判断；但材料本身与 AI 无直接关联，若账号定位 AI，需补充额外证据才适合跟进。

**「社区讨论」** 评论中有人把质量下降视为隐性通胀，认为成本上升被通过降低用料或转移生产消化；也有人反驳“质量从来不是常态”，廉价长期胜出。另有评论指出品牌有短期套现动机、无品牌产品增多，并用 Amazon 上把镀锌桶标成不锈钢桶的购物经历说明质量信息难以核验。

**标签**: `#消费者权益`, `#产品质量`, `#通胀`, `#计划性淘汰`, `#Hacker News`

---

<a id="item-ai-creator-10"></a>
### [美国首次确认部署太空武器](https://www.bbc.com/news/articles/ck790xg41ygro) ⭐️ 1.0/10

BBC 报道称，美国首次确认已部署太空武器。现有材料只给出这一确认本身，未提供武器类型、数量、部署时间、轨道位置或官方声明细节，因此无法判断其具体能力与可核查程度。受影响的是太空军事化、战略稳定与低地球轨道使用安全等议题，而非 AI 模型或产品。

hackernews · harporoeder · 9月15日 03:47 · [社区讨论](https://news.ycombinator.com/item?id=49707473)

**「为何此刻值得注意」** 若“首次确认”属实，这会是美方在太空武器部署透明度上的一个公开节点；但材料没有给出时间线、能力参数或国际反应，所以现在值得注意的更多是信息披露本身，而非已被证实的战力变化。

**「可做角度」** 可做角度：把它当作“非 AI 但涉及科技治理”的背景题，围绕公开确认与可核查能力之间的落差、以及轨道碎片风险如何把太空军事化变成公共治理议题来展开；先核实 BBC 原文与官方表述，避免下判断。

**「社区讨论」** Hacker News 评论里，担忧集中在太空军事化与轨道碎片可能触发 Kessler 效应，并援引历史定向能项目、航天器潜在反卫星能力；另有评论讽刺“敦促美国不要为战争作准备”的说法，并回顾冷战核裁军曾因太空武器受阻。这些是评论者个人观点，不构成共识结论。

**标签**: `#space-weapons`, `#geopolitics`, `#military-tech`, `#off-topic`, `#defense-policy`

---

<a id="item-ai-creator-11"></a>
### [荷兰铁路疑遭破坏致大面积停运](https://www.bbc.com/news/articles/c8ly49w9g1edo) ⭐️ 0.0/10

BBC 报道称，荷兰铁路基础设施疑似遭到破坏，造成大范围铁路运营中断，受影响的是荷兰铁路乘客与运营方。现有材料未给出破坏的具体地点、时间、波及车次数或责任方等可验证细节，事件性质仍待确认。该条目在 Hacker News 上获得 428 分、392 条评论。

hackernews · choult · 9月15日 10:22 · [社区讨论](https://news.ycombinator.com/item?id=49710253)

**「为何值得注意」** 评论者提到事发当天正值荷兰年度预算公布日（Prinsjesdag），且多地预期出现抗议活动，使这一时间点受到关注；但破坏行为是否与抗议相关，评论中明确表示尚待确定。另有评论将此事与数天前法国一起导致列车脱轨的事件并列提及，同样属于推测层面。

**「社区讨论」** 一位自称从事相关系统工程的人士认为，铁路的“失效安全”设计在应对单点故障时仍是最佳方案，但可能被大规模利用——很难让两列火车相撞，却很容易让某一区域的所有列车停运。另有评论分别提及法国脱轨事件和波罗的海一艘俄舰向丹麦军用直升机发射照明弹的报道，也有人猜测与当天预算抗议有关，但这些关联均未获证实。

**标签**: `#rail-sabotage`, `#critical-infrastructure`, `#netherlands`, `#not-ai-related`, `#security`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [中国 8 月零售未达预期、投资下滑加深，工业产出超预期](https://www.cnbc.com/2026/09/15/china-august-retail-sales-industrial-output-investment-exports-.html) ⭐️ 7.0/10

据 CNBC 报道，中国 8 月零售销售增长进一步放缓、未达预期，投资下滑加深，而工业产出超出预期。北京方面同时警告存在供需失衡，这加大了政策压力。

rss · CNBC Finance · 9月15日 09:46

**「背景」** 中国经济增长长期依赖制造业和投资，近期决策层警告经济存在供需失衡。据相关报道，8 月规模以上工业增加值同比增长 5.2%，快于 7 月；同期社会消费品零售总额增速放缓至 0.4%，前八个月固定资产投资同比下降 7.2%。

**「影响」** 分析机构 MERICS 指出，供给持续扩张而需求停滞已在中国引发激烈价格战，令不少企业陷入亏损，因此这次“供给强、需求弱”的数据意味着中国制造企业及其出口市场的利润压力可能进一步加大。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://economictimes.indiatimes.com/news/international/business/chinas-factory-output-growth-quickens-in-august-retail-sales-slow/articleshow/134250835.cms">China&#x27;s factory output growth quickens in August, retail sales slow - The Economic Times</a></li>
<li><a href="https://merics.org/en/comment/chinas-overcapacity-threatens-reshuffle-global-industrial-bases">China&#x27;s overcapacity threatens to reshuffle global industrial bases</a></li>

</ul>
</details>

**标签**: `#China economy`, `#macro data`, `#retail sales`, `#fixed asset investment`, `#industrial output`

---