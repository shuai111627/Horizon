---
layout: default
title: "Horizon Summary: 2026-09-02 (ZH)"
date: 2026-09-02
lang: zh
---

> 从 27 条内容中筛选出 14 条重要资讯。

---

**AI 创作者雷达**
1. [Anthropic 发布 Claude Fable 5.1 与 Mythos 5.1](#item-ai-creator-1) ⭐️ 9.0/10
2. [开发者自称：1.5 小时训练的小型 Transformer 在 ARC 上超越许多 LLM](#item-ai-creator-2) ⭐️ 8.0/10
3. [Codex 桌面版被发现捆绑 LibreOffice 等本地工具](#item-ai-creator-3) ⭐️ 7.0/10
4. [Python 3.15.0 RC2 发布，官方呼吁第三方项目提前适配](#item-ai-creator-4) ⭐️ 7.0/10
5. [Ed Zitron 的 AI 怀疑论预测准不准？一篇回顾引发的争论](#item-ai-creator-5) ⭐️ 6.0/10
6. [Simon Willison 发布 AI 辅助生成的 GeoJSON 地图查看器](#item-ai-creator-6) ⭐️ 5.0/10
7. [《留住 Firefox》：一场关于浏览器引擎多样性的呼吁](#item-ai-creator-7) ⭐️ 4.0/10
8. [Google Play 不再允许 AnkiDroid 的 Open Collective 捐赠链接](#item-ai-creator-8) ⭐️ 4.0/10
9. [Firefox for iOS 测试广告拦截：灰度、遥测与搜索广告限制](#item-ai-creator-9) ⭐️ 4.0/10
10. [Tarn Adams：AI 一词被抢走，只能叫“矮人行为”](#item-ai-creator-10) ⭐️ 3.0/10
11. [社区批评 Ambient CSS v3 实现粗糙](#item-ai-creator-11) ⭐️ 2.0/10
12. [HN 九月招聘帖：常规技术岗位汇总，无 AI 专题信息](#item-ai-creator-12) ⭐️ 2.0/10
13. [Jujutsu 创建者加入 GitHub 竞争对手 ERSC](#item-ai-creator-13) ⭐️ 1.0/10
14. [Play Store 阻止 AuroraStore，GrapheneOS 用户受影响程度待确认](#item-ai-creator-14) ⭐️ 1.0/10

---

## AI 创作者雷达

<a id="item-ai-creator-1"></a>
### [Anthropic 发布 Claude Fable 5.1 与 Mythos 5.1](https://www.anthropic.com/claude-fable-and-mythos-5-1) ⭐️ 9.0/10

Anthropic 发布了 Claude Fable 5.1 和 Claude Mythos 5.1，并在官方页面提供了“Fable 5.1 新功能”文档与系统卡链接。发布材料显示，该版本主要带来写作风格改进、更强的科学性能，以及缓存读取价格下调。受影响的场景主要是使用 Claude 的创作者和开发者；更完整的能力差异需以官方文档和系统卡为准。

hackernews · denysvitali · 9月1日 17:53 · [社区讨论](https://news.ycombinator.com/item?id=49525378)

**「为什么现在关注」** 这不是一次单纯的模型版本更新，还伴随了缓存读取价格调整。社区已经开始猜测降价是否反映 Fable 5.1 首发定价的市场接受度，但这一猜测尚未得到官方证实。

**「内容切入角度」** 可做角度：从“写作风格改进”的宣传与“缓存读取价格下调”同时出现切入，比较官方发布口径与开发者社区对价格信号的解读，呈现“降价是否等于市场遇冷”的分歧，不做结论。

**「社区讨论」** 社区讨论主要围绕两点：写作风格与定价。一位自称在 Anthropic 工作的评论者认为 Fable 5.1 的写作风格更自然且更听风格指令；另一位开发者测试后认为最高思考档位改进明显但耗时近 14 分钟。定价方面，有评论指出缓存读取价格从 1 美元/百万 token 降至 0.25 美元，使 Fable 5.1 的缓存成本为 Opus 的一半，也有评论认为剔除某项基准后看不出明显提升；此外有评论注意到官方文档建议在复杂异步任务中提示模型不要提前结束回合。

**标签**: `#Claude`, `#Anthropic`, `#model release`, `#writing quality`, `#pricing`

---

<a id="item-ai-creator-2"></a>
### [开发者自称：1.5 小时训练的小型 Transformer 在 ARC 上超越许多 LLM](https://mvakde.github.io/blog/44-on-arc-1/) ⭐️ 8.0/10

一位开发者（作者）在 Hacker News 上发帖称，自己用一个从零训练的小型自回归（AR）transformer，仅用 1.5 小时，就在 ARC 推理基准上超过了多个大型 LLM。作者强调这不是 LLM，并认为复杂问题不一定需要超大模型。目前这只是作者的自述和博客结果，没有独立验证，“超过”的具体范围也不明确。

hackernews · porridgeraisin · 9月1日 09:52 · [社区讨论](https://news.ycombinator.com/item?id=49519939)

**「为什么值得注意」** 作者称，该基准此前主要由 LLM 或微调模型以巨大训练成本占据，其他尝试要么架构复杂，要么训练算力极高。如果这一结果能独立复现，可能对“复杂推理必须依赖大模型”的常规思路构成挑战；但目前仍是未经验证的个案。

**「可做内容角度」** 可做角度：从“1.5 小时小模型 vs 大型 LLM 训练成本”的对比入手，拆解作者公开的方法细节（如从零训练、非 LLM、架构选择），并明确说明这只是自报成绩，避免把“超越许多 LLM”当成定论。

**「社区讨论」** 评论中，作者本人回应了质疑：模型不是 LLM，而是小型 AR transformer；“训练测试”批评不成立，因为并未训练测试标签。其他用户也提到现代架构调整和数据多样性属于“挤柠檬”式优化，认为应先在新方法上逼近当前最优；这类讨论反映了社区对“小模型超过大模型”的谨慎态度。

**标签**: `#ARC`, `#transformer`, `#efficient AI`, `#small models`, `#benchmark`

---

<a id="item-ai-creator-3"></a>
### [Codex 桌面版被发现捆绑 LibreOffice 等本地工具](https://simonwillison.net/2026/Sep/1/codex-libreoffice/) ⭐️ 7.0/10

开发者 Simon Willison 在检查缓存目录时发现，OpenAI Codex 桌面应用（现已改名为 ChatGPT 桌面版）在 ~/.cache/codex-runtimes/codex-primary-runtime 中占用了约 1.7GB 空间，里面包含完整的 Python、Node.js 安装，以及 Poppler、git 和 LibreOffice 的原生二进制。该目录下还有名为“documents”的插件和技能，用于指导 Codex 使用这些工具处理文档。目前这只是对本地缓存结构的观察，OpenAI 官方尚未说明这些依赖的具体用途。

rss · Simon Willison · 9月1日 19:03 · [社区讨论](https://news.ycombinator.com/item?id=49527396)

**「为什么现在值得注意」** 这个发现揭示了 OpenAI 桌面应用在本地处理文档时可能采用的技术栈：直接内置完整办公套件和运行时，而不是完全依赖云端转换。这属于已经发生的缓存事实，但官方未确认其作用，因此尚不能断定它一定用于本地渲染或编辑文档。

**「内容角度」** 可做角度：从“AI 助手偷偷内置了一个办公套件”切入，盘点桌面 AI 工具为了本地处理文档付出了多大的依赖体积，并讨论这对普通用户意味着什么——比如安装包膨胀、隐私边界、以及对开源组件 LibreOffice 的依赖。避免夸大性能或下结论，聚焦于可观察的缓存与文件结构。

**「社区讨论」** 评论中有几种不同看法：有人表示自己也捆绑 LibreOffice，主要为了可靠读取旧版 xls 等文件；有人质疑这些依赖是默认捆绑还是按需下载；还有人猜测它被用于渲染和操作 Office 文档，并可能解释某些文件渲染效果不佳。也有用户抱怨新版应用整体体验混乱。这些观点来自少量评论，并非广泛共识。

**标签**: `#OpenAI`, `#Codex`, `#ChatGPT桌面应用`, `#LibreOffice`, `#内置运行时`

---

<a id="item-ai-creator-4"></a>
### [Python 3.15.0 RC2 发布，官方呼吁第三方项目提前适配](https://simonwillison.net/2026/Sep/1/python-315-rc-2/) ⭐️ 7.0/10

Python 3.15.0 发布了第二个候选版本（RC2），由 Python 3.14 和 3.15 的发布经理 Hugo van Kemenade 宣布。官方表示进入候选版本阶段后，只会合并明确的 bug 修复；正式版预计在 10 月发布。官方强烈鼓励第三方项目维护者在 RC 阶段提前测试，并在 PyPI 上发布面向 Python 3.15 的 wheel，且基于 Python 3.15.0 RC 构建的二进制 wheel 可兼容未来的 Python 3.15 版本。Simon Willison 还提示，该 RC 尚未在 GitHub Actions 中直接可用，但可以通过 allow-prereleases 和 check-latest 配置在测试矩阵中使用。

rss · Simon Willison · 9月1日 14:59

**「为什么值得现在关注」** Python 3.15 已经进入正式发布前的候选版本阶段，这是第三方项目适配和测试的关键时间窗口。值得注意的是，RC2 发布是已经发生的变化，而正式版 10 月发布是官方安排，GitHub Actions 尚未支持该 RC 则是作者在文章中的提示。

**「内容切入角度」** 可做角度：从 Simon Willison 在 2021 年因未在 RC 阶段测试而错过 Python 3.10 bug 的亲身经历出发，介绍开发者如何用 GitHub Actions 的 allow-prereleases 与 check-latest 配置，把 Python 3.15 RC 加入现有测试矩阵，尽早发现兼容性问题。

**标签**: `#Python`, `#3.15`, `#发布候选`, `#开发者生态`, `#编程语言`

---

<a id="item-ai-creator-5"></a>
### [Ed Zitron 的 AI 怀疑论预测准不准？一篇回顾引发的争论](https://danluu.com/zitron/) ⭐️ 6.0/10

一条 Hacker News 讨论指向一篇针对 AI 怀疑论者 Ed Zitron 预测准确度的回顾文章。文章试图评估他的判断，并给出了反驳，但评论者对这些反驳是否有效存在激烈分歧。目前材料中没有提供可验证的新事实或具体数据，只呈现了围绕该话题的立场之争。

hackernews · jatins · 9月1日 18:35 · [社区讨论](https://news.ycombinator.com/item?id=49526069)

**「内容角度」** 可做角度：从“怀疑论者与鼓吹者是否都落入立场驱动”的张力出发，梳理评论区提出的批评——例如 Zitron 可能因受众期待而拒绝认错，同时 AI 行业领袖同样不断给出夸张时间表——并以此探讨 AI 公共讨论中的极化现象。避免得出“谁对谁错”的结论，而是呈现双方论证方式的问题。

**「社区讨论」** 评论区存在明显分歧：有用户认为 Zitron 和 AI 行业领袖同样夸大，并希望看到对 Altman、Amodei 等预测的同类验证；有用户认为反驳 Zitron 的帖子只是重复“错了”而不给证据，反而可能印证他的判断；还有用户批评 Zitron 已成为他所嘲讽的鼓吹者的镜像，因受众期待而无法承认自己可能犯错。另有人指出，大型云厂商把对 Anthropic、OpenAI 的投资增值计入“其他收入”，推高了报表利润，这一点未被文章讨论。

**标签**: `#AI-skepticism`, `#prediction-accuracy`, `#Ed-Zitron`, `#AI-hype`, `#tech-blogging`

---

<a id="item-ai-creator-6"></a>
### [Simon Willison 发布 AI 辅助生成的 GeoJSON 地图查看器](https://simonwillison.net/2026/Sep/1/geojson/) ⭐️ 5.0/10

Simon Willison 发布了一个 AI 辅助构建的 GeoJSON Map Viewer（https://tools.simonwillison.net/geojson），用于在浏览器中显示 GeoJSON 文件并导出为 PNG。该工具最初由 GPT-5.6-Sol 在收到需求后主动构建，随后经过 Claude Code for web 和 Fable 5.1 的多轮迭代完成。页面说明中标注“Your GeoJSON stays in this browser”，即数据只留在浏览器本地。Willison 还展示了用 ChatGPT Work 从政府数据源生成两个地方选区边界 GeoJSON 的示例，并将它们同时叠加在同一张地图上。

rss · Simon Willison · 9月1日 18:05

**「为什么现在值得注意」** 当下值得注意的不是地图查看器本身，而是它作为一次公开的 AI 辅助开发案例：Willison 在真实需求中让 GPT-5.6-Sol 先搭出工具，再经 Claude Code for web 和 Fable 5.1 迭代。它展示的“一句话需求→可用工具”路径是已发生的演示，但该工具是否会被广泛采用、对开发者日常有多大影响，目前没有证据。

**「可做内容角度」** 可做角度：以 Simon Willison 这个 GeoJSON 查看器为案例，讨论“用自然语言让 AI 建一个小工具”的实际体验——从需求描述、AI 初稿、Claude Code/Fable 迭代到最终成品都发生在一次真实任务中；同时区分“工具生成”与“数据获取”两个环节，因为边界数据本身来自 ChatGPT Work 对政府数据源的提取和合并，其可靠性与边界精度仍需由使用者核对。

**标签**: `#GeoJSON`, `#AI-assisted development`, `#Simon Willison`, `#mapping`, `#dev tools`

---

<a id="item-ai-creator-7"></a>
### [《留住 Firefox》：一场关于浏览器引擎多样性的呼吁](https://www.newsonaut.com/articles/hang-on-to-your-firefox) ⭐️ 4.0/10

这是一篇署名 speckx 的评论文章，发布在 newsonaut.com，后被分享到 Hacker News。文章标题“Hang on to Your Firefox”本身即点明主张：呼吁用户继续使用 Firefox，以维持浏览器引擎的多样性。文章背景是 Firefox 当前是为数不多不属于 Chrome 或 WebKit 阵营的主要浏览器，但 Mozilla 自身也存在争议，例如收购广告技术公司、收集用户数据、推送个性化广告等行为。

hackernews · speckx · 9月1日 20:30 · [社区讨论](https://news.ycombinator.com/item?id=49527748)

**「内容角度」** 可做角度：从“为什么即使对 Mozilla 不满，仍应保留 Firefox”这一张力出发，梳理浏览器引擎垄断对 Web 开发者的影响，以及 Mozilla 商业决策与用户信任之间的矛盾。

**「社区讨论」** Hacker News 评论中，有用户称 Firefox 是“浏览器引擎多样性和竞争的最后希望”，也有人强调虽不认同 Mozilla 的许多做法，但为了非 Chrome/WebKit 引擎仍选择使用 Firefox；另一部分评论则提到 Mozilla 收购广告技术公司、收集数据、推送个性化广告等“反功能”正在推开用户。还有用户询问 Firefox 是否是唯一拥有高质量广告拦截器的浏览器，另有评论将部分责任归咎于 Web 开发者。

**标签**: `#Firefox`, `#浏览器引擎`, `#Mozilla`, `#Web开发`

---

<a id="item-ai-creator-8"></a>
### [Google Play 不再允许 AnkiDroid 的 Open Collective 捐赠链接](https://github.com/ankidroid/Anki-Android/issues/21656) ⭐️ 4.0/10

据 GitHub issue \#21656 的标题，Google Play 不再允许 AnkiDroid 放置 Open Collective 捐赠链接。目前尚不清楚 Google 的具体政策条款，以及该决定是否仅影响 AnkiDroid。评论区将此事与 2019 年 WireGuard 被 Play Store 移除类比，并讨论开源项目捐赠的免税资格问题。受影响的是在 Google Play 上分发并通过捐赠获得收入的开源应用开发者。

hackernews · hexa555 · 9月1日 10:11 · [社区讨论](https://news.ycombinator.com/item?id=49520022)

**「内容角度」** 可做角度：从 AnkiDroid 捐赠链接被 Google Play 下架这件事切入，讨论应用商店支付政策对开源项目可持续性的影响。保持事实叙述，避免推断 Google 的意图或给出具体对策建议。

**「社区讨论」** 评论中有人认为这不是 Google 第一次这么做，并提到 2019 年 WireGuard 的遭遇，借此批评应用商店的垄断控制；也有人解释 501\(c\)\(6\) 身份意味着捐赠不自动免税，Google 所说的“tax-exempt”可能指捐赠本身而非组织身份。还有用户表达了对 AnkiDroid 的感谢，借此提醒大家它可以接受捐赠。

**标签**: `#Google Play`, `#开源捐赠`, `#AnkiDroid`, `#应用商店政策`, `#开发者影响`

---

<a id="item-ai-creator-9"></a>
### [Firefox for iOS 测试广告拦截：灰度、遥测与搜索广告限制](https://blog.mozilla.org/en/firefox/ad-blocker-on-ios/) ⭐️ 4.0/10

Mozilla 官方博客宣布为 Firefox for iOS 引入实验性广告拦截功能，但根据公告信息，该功能尚未全面开放，仍处于灰度测试阶段。用户需要开启遥测才能使用，并且该功能不会拦截搜索引擎结果页上的广告，因此实际覆盖范围有限。目前尚不清楚该功能何时会向所有用户正式推出。

hackernews · HieronymusBosch · 9月1日 13:46 · [社区讨论](https://news.ycombinator.com/item?id=49521973)

**「为何值得关注」** 这条公告把广告拦截作为 Firefox for iOS 的官方实验功能提上日程，但它更多是产品路线图的信号，而非已经全面上线的功能。当前最值得注意的并不是“能拦截广告”本身，而是它的限制条件——灰度、遥测要求、不拦截搜索广告——这些都会直接影响用户实际体验。

**「内容角度」** 可做角度：从 Firefox for iOS 广告拦截实验的上线方式，看浏览器默认广告拦截的边界问题——例如为什么要强制遥测、为什么放过搜索引擎广告、灰度 rollout 是否拉高了用户预期。这个角度不评价功能好坏，而是讨论产品决策和用户期待之间的张力。

**「社区讨论」** 评论中有用户对功能未全面开放、必须开启遥测表示不满，也有用户引用官方说明指出它不拦截搜索引擎结果页广告。还有用户提到可用 wBlock 等替代方案，因此社区对 Mozilla 这一实验的接受度并不一致。

**标签**: `#Firefox`, `#iOS`, `#广告拦截`, `#Mozilla`, `#浏览器`

---

<a id="item-ai-creator-10"></a>
### [Tarn Adams：AI 一词被抢走，只能叫“矮人行为”](https://simonwillison.net/2026/Sep/1/tarn-adams/) ⭐️ 3.0/10

《矮人要塞》联合创作者 Tarn Adams 在 PC Gamer 的采访中开玩笑说，行业已经占用了“AI”这个词，所以他不能再谈“矮人 AI”，只能改称“矮人行为”（dwarf behavior），并补充说矮人有时会不听话。这是一段针对术语的调侃，不是产品更新或技术发布。

rss · Simon Willison · 9月1日 17:01

**「内容切入角度」** 可做角度：从“矮人行为”这个梗切入，讨论 AI 术语膨胀后，游戏开发者如何重新描述游戏内的智能系统。可以对比游戏 AI 与当前行业泛化 AI 的差异，但应避免把 Tarn Adams 的个人调侃当成行业共识。

**标签**: `#dwarf-fortress`, `#ai-terminology`, `#game-design`, `#commentary`

---

<a id="item-ai-creator-11"></a>
### [社区批评 Ambient CSS v3 实现粗糙](https://ambientcss.vercel.app/) ⭐️ 2.0/10

Ambient CSS v3 是一个宣称将 Blender 风格与 CSS 结合的 3D 效果库，已在 Vercel 上发布。目前没有官方项目说明，但社区评论指出其多个示例失效、性能卡顿、光照控制异常，材质和颜色效果也明显与预期不符。受影响的场景是 Web 开发中的 3D 视觉效果实验，但项目本身的成熟度和可用性仍有较大不确定性。

hackernews · kikkupico · 9月1日 15:35 · [社区讨论](https://news.ycombinator.com/item?id=49523387)

**「内容角度」** 可做角度：从 Ambient CSS v3 的争议出发，盘点现代 CSS 实现 3D 效果的真实边界，并对比早期 Web 2.0 时代的 hack 与当下原生能力的差距，避免被“Blender meets CSS”这类宣传语误导。

**「社区讨论」** 评论整体对项目持负面态度：有开发者指出光照方向仅作用于局部区域且卡顿，示例无法运行，玻璃材质和颜色表现不佳；也有人将它类比为 Web 2.0 时代的 PNG/GIF hack，认为 CSS 演进后的效果并不理想。

**标签**: `#CSS`, `#3D效果`, `#Web开发`, `#开发者工具`

---

<a id="item-ai-creator-12"></a>
### [HN 九月招聘帖：常规技术岗位汇总，无 AI 专题信息](https://news.ycombinator.com/item?id=49522897) ⭐️ 2.0/10

这是 Hacker News 上每月固定发布的“Who is hiring?”招聘帖（标题为 2026 年 9 月），由 whoishiring 账号发布。帖内汇集了多家公司的技术岗位，例如 Black Canyon Consulting 的平台系统工程师、Fastly 的软件工程师，以及 Relativity Space 的软件工程师等，方向以平台工程、边缘云和航天制造为主。整条帖子没有包含 AI 产品、模型或研究相关的新增信息，因此对关注 AI 动态的博主来说，它本身不是一个具体的 AI 新闻线索。

hackernews · whoishiring · 9月1日 15:01

**标签**: `#hiring`, `#hacker-news`, `#job-board`, `#tech-jobs`

---

<a id="item-ai-creator-13"></a>
### [Jujutsu 创建者加入 GitHub 竞争对手 ERSC](https://ersc.io/blog/martin-joins-ersc) ⭐️ 1.0/10

据 ERSC 官方博客消息，Jujutsu 版本控制系统的创建者 Martin 已加入 ERSC——一个被描述为 GitHub 竞争对手的公司。博客作者 steveklabnik 在 HN 评论中表示，与 Martin 合作愉快，并称“很快会有更多内容发布”。目前公开信息仅有人事变动本身，Martin 的具体职位、任期或产品计划尚未披露。

hackernews · steveklabnik · 9月1日 17:46 · [社区讨论](https://news.ycombinator.com/item?id=49525297)

**「为什么现在值得关注」** Jujutsu 是近年受到关注的 Git 替代或增强工具，其创建者加入一家 GitHub 竞品，可能影响 ERSC 未来在版本控制方向上的产品策略。不过，人事变动已经发生，它对 ERSC 功能或行业格局的具体影响尚无公开细节，属于待观察事项。

**「内容切入角度」** 可做角度：从“Jujutsu 作者加入 ERSC”这一人事变动切入，梳理 ERSC 想挑战 GitHub 的差异点，以及 Jujutsu 的“撤销”“变更式提交”等设计理念，能否成为新一代代码托管平台的卖点。

**「社区讨论」** HN 评论看法明显分歧：有用户认为 Git 已够用，Jujutsu 的“杀手级功能”只在复杂分支和频繁切换场景才体现价值；也有用户强调 jj 的“可撤销”体验和更聪明的设计值得尝试，用后“非常不错”。还有人质疑 ERSC 作为 GitHub 竞品能提供什么额外价值——这些讨论更多停留在个人使用体验，缺少对 ERSC 产品路线的实证信息。

**标签**: `#jujutsu`, `#version control`, `#ersc`, `#developer tools`

---

<a id="item-ai-creator-14"></a>
### [Play Store 阻止 AuroraStore，GrapheneOS 用户受影响程度待确认](https://gitlab.com/AuroraOSS/AuroraStore/-/work_items/1566) ⭐️ 1.0/10

据报道，Play Store 开始阻止第三方客户端 AuroraStore 正常工作，有用户反映应用无法更新。该问题直接波及部分 GrapheneOS 用户，但 GrapheneOS 官方其实推荐直接使用 Play Store 而非 AuroraStore。目前具体封堵原因和影响范围尚未得到确认。

hackernews · erikvanoosten · 9月1日 15:55 · [社区讨论](https://news.ycombinator.com/item?id=49523754)

**「为何现在值得关注」** 这条消息在隐私和 Android 社区中引发讨论，因为它触及了“没有 Google 账户如何安装应用”这一长期痛点。目前仅有用户报告和初步猜测，实际影响还未证实。

**「内容角度」** 可做角度：从“Android 无 Google 账户安装应用”的现状出发，梳理第三方应用商店被封堵后的替代路径和用户困境。材料显示有用户坚持不登录 Google 账户，也有人代管老人手机时依赖 AuroraStore，这些具体场景可以支撑一篇克制的观察。

**「社区讨论」** 评论区观点存在分歧：一方指出 GrapheneOS 官方并不推荐 Aurora，因此影响有限；另一方表示自己仍因不喜欢 Play Store 的界面和暗黑模式而坚持使用 Aurora，并已有多款应用无法更新。另有用户提醒说标题有些过度推断，因为目前只确认了 bug，尚未确认封堵原因。

**标签**: `#GrapheneOS`, `#AuroraStore`, `#Play Store`, `#Android`, `#privacy`

---