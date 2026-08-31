---
layout: default
title: "Horizon Summary: 2026-08-31 (ZH)"
date: 2026-08-31
lang: zh
---

> 从 417 条内容中筛选出 11 条重要资讯。

---

**科技新闻**
1. [开放世界多智能体环境中的自主数学发现](#item-tech-news-1) ⭐️ 9.0/10
2. [解析 ChatGPT Work：两个产品与核心能力](#item-tech-news-2) ⭐️ 8.0/10
3. [基于统计形状模型与可微渲染的 X 光三维骨骼重建](#item-tech-news-3) ⭐️ 7.0/10

**财经新闻**
1. [苹果宣布特努斯接替库克出任 CEO](#item-finance-news-1) ⭐️ 9.0/10
2. [沃什杰克逊霍尔讲话推高 9 月加息预期](#item-finance-news-2) ⭐️ 8.0/10
3. [五大 A 股上市险企上半年净利同比增 78.12%](#item-finance-news-3) ⭐️ 8.0/10
4. [希音 SHEIN 拟以同股不同权架构赴港上市](#item-finance-news-4) ⭐️ 8.0/10
5. [伊朗副外长称未经协调船只无法通过霍尔木兹海峡，油价与比特币上涨](#item-finance-news-5) ⭐️ 8.0/10
6. [A 股中报利润总额增加 5800 亿元](#item-finance-news-6) ⭐️ 7.0/10
7. [恒指周跌 1.63%，阿里 800 亿元配股全押 AI，54 只股票 9 月入通预期升温](#item-finance-news-7) ⭐️ 7.0/10
8. [Cronos 因 Tectonic 遭 7500 万美元借贷漏洞攻击而暂停区块链](#item-finance-news-8) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [开放世界多智能体环境中的自主数学发现](https://www.reddit.com/r/MachineLearning/comments/1w2fl67/r_autonomous_mathematical_discovery_in_an/) ⭐️ 9.0/10

一项研究让来自不同模型家族的 AI 智能体在“Station”这一开放世界多智能体环境中，在没有中央协调者或固定脚本的情况下自主协作开展数学研究。在 AlphaEvolve 目录中的 12 个构造问题及两项额外案例研究中，系统在五个问题上获得了相对于现有文献的新结果：有限域 Kakeya 集合的新无限族、维度 11 中精确的 604 点亲吻构型、离散化 Kakeya 针与符号不确定性问题的纪录，以及 Erdős 最小重叠问题的显著改进下界；此外还发现了 Book Ramsey 数的新无限族。智能体不仅给出数值构造，还生成了解释构造原理的定理与分析，使结果更易理解并便于数学家进一步研究。研究团队公开了全部原始智能体对话、证明和验证代码，为这些发现的产生过程提供了透明记录。

reddit · r/MachineLearning · /u/progenitor414 · 8月30日 11:55

**「背景」** Kakeya 集（又称 Besicovitch 集）是包含每个方向上一条单位线段的点集；Erdős 最小重叠问题由匈牙利数学家 Paul Erdős 于 1955 年提出，研究将\{1,...,2n\}分为两个等大小互补子集后，两者平移重叠次数的最小可能值。该研究使用的“Station”是一个开放式多智能体环境，让来自不同模型家族的 AI 智能体在没有中央协调或脚本化流程的情况下自行选择研究方向、开展实验，并将结果积累成共享文献。此前的相关工作主要依赖人工设计或单一模型流程，而这一环境提供了一种更接近人类科学社群的自主协作发现机制。

**「影响」** 数学家和 AI 研究人员现在可以查阅完整的智能体对话、证明和验证代码，从而验证并扩展这些自主发现的新数学结果，这标志着无需人工编排的多智能体系统已能产出可解释、可复现的新数学知识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2608.23691">[2608.23691] Autonomous Mathematical Discovery in an Open-World Multi-Agent Environment</a></li>
<li><a href="https://en.wikipedia.org/wiki/Minimum_overlap_problem">Minimum overlap problem - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kakeya_set">Kakeya set - Wikipedia</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#mathematical discovery`, `#AI research`, `#machine learning`

---

<a id="item-tech-news-2"></a>
### [解析 ChatGPT Work：两个产品与核心能力](https://simonwillison.net/2026/Aug/30/understanding-chatgpt-work/) ⭐️ 8.0/10

OpenAI 于 7 月 9 日发布 ChatGPT Work，Simon Willison 分析后指出它实际是两个产品：云端的 Work Cloud（chatgpt.com 与移动应用）和桌面应用的 Work Local（原 Codex 改造）。Work 仅向每月 20 美元及以上订阅者开放，免费用户和 8 美元 Go 用户无法使用。云端版最突出的是可访问互联网的代码执行环境、完整无头 Chrome 浏览器（可加载网页、填写表单、截屏并直接执行 JavaScript）、跨会话持久文件系统、ChatGPT Sites 发布能力、Sol/Luna/Terra 模型选择与子代理，以及定时自动化。这些功能把 Work 与普通 Chat 区分开，但模型与配额逻辑仍存在不少混淆。

rss · Simon Willison · 8月30日 23:59

**「背景」** ChatGPT Work 是 OpenAI 在 2026 年 7 月 9 日宣布的面向“更有雄心的任务”的产品形态。它通过标签页与普通 ChatGPT Chat 并列，目标不是提供答案而是完成任务并产出可审查的文件或工作流。Work Local 源自原本叫 Codex 的桌面应用，面向非开发者做了重新包装。

**「影响」** 对每月 20 美元以上的已付费订阅者，Work Cloud 提供了一条可直接让 AI 代理联网编程、运行浏览器和留存文件的自动化链路，例如克隆 GitHub 仓库、安装依赖并与外部网站交互。不过默认开放全部域名的联网策略和凭据介入机制也引入新的安全与隐私考量。

**标签**: `#ChatGPT`, `#OpenAI`, `#AI assistants`, `#product analysis`, `#developer tools`

---

<a id="item-tech-news-3"></a>
### [基于统计形状模型与可微渲染的 X 光三维骨骼重建](https://www.reddit.com/r/MachineLearning/comments/1w2go6l/reconstructing_3d_bone_geometry_from_2_xray/) ⭐️ 7.0/10

该研究提出一种无需神经网络或 CT 扫描的三维骨骼重建方法，利用从 50 个 CT 股骨网格（MedShapeNet）构建的 PCA 统计形状模型，仅需两幅正交 X 光轮廓（正位与侧位），通过 PyTorch3D 软光栅化器与 sigma 退火进行优化拟合。方法使用 10 个形状系数、Mahalanobis 先验和 Adam 优化器，约迭代 1000 次；在 5 个留出股骨的交叉验证中，平均误差为 0.86 至 1.43 毫米，但两个超出模型覆盖范围的极端案例失败，因为优化器无法恢复模型不支持的系数。在对应关系方面，ShapeWorks 表现最佳（粗糙度因子 3.3 倍于 CT 表面），优于 KD 树最近邻（50.7 倍）、CPD（28.2 倍）和 BCPD（47.5 倍），FilterReg 则无法运行。研究者还发现 sigma 退火终点必须与参考渲染的 sigma 精确匹配，将硬编码常数改为 camera\_extent×1e-4 解决了在不同形状模型间迁移时的严重精度下降问题。目前仍在使用配对 CT 数据进行真实 X 光验证，并开展自动分割工作。

reddit · r/MachineLearning · /u/mxl069 · 8月30日 12:47

**「背景」** 此项目涉及两个关键背景概念。一是统计形状模型（SSM）：从一组 CT 分割出的股骨网格中，用主成分分析（PCA）提取形状变化模式，用少量系数表示个体形状；MedShapeNet 提供了用于构建这类骨骼形状模型的大量三维解剖数据。二是可微渲染：用 PyTorch3D 的软光栅化器把三维模型投影成二维轮廓，并计算轮廓与 X 光影像轮廓之间的梯度，从而通过优化更新形状系数。形状对应的建立是此类流程的难点，作者提到 ShapeWorks 是一种基于粒子系统的开源形状对应工具，可自动生成不同样本间的稠密对应点，避免依赖特定表面参数化。

**「影响」** 该技术可能使临床中无需 CT 即可从常规 X 光精确重建患者特异的三维骨骼几何成为可能，特别适用于术前规划或植入物匹配，但当前模型覆盖范围有限，对超出训练数据形态的极端病例尚不可靠。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sciinstitute.github.io/ShapeWorks/latest/workflow/optimize.html">How to Optimize Your Shape Model? - ShapeWorks - GitHub Pages</a></li>
<li><a href="https://sciinstitute.github.io/ShapeWorks/latest/">ShapeWorks - GitHub Pages</a></li>
<li><a href="https://www.sciencedirect.com/science/chapter/edited-volume/pii/B9780128104934000122">ShapeWorks: Particle-Based Shape Correspondence and ...</a></li>
<li><a href="https://arxiv.org/html/2308.16139v5">MedShapeNet - A Large-Scale Dataset of 3D Medical Shapes for ...</a></li>
<li><a href="https://arxiv.org/abs/2308.16139">[2308.16139] MedShapeNet -- A Large-Scale Dataset of 3D ... MedShapeNet | MML @ IKIM GLARKI/MedShapeNet2.0: MedShapeNet 2.0 - GitHub MedShapeNet: A Large-scale Dataset of 3D Medical Shapes ( MedShapeNet -- A Large-Scale Dataset of 3D Medical Shapes for ... Paper page - MedShapeNet -- A Large-Scale Dataset of 3D ...</a></li>
<li><a href="https://mml.ikim.nrw/ait/projects/medshapenet/">MedShapeNet | MML @ IKIM</a></li>

</ul>
</details>

**标签**: `#3D reconstruction`, `#differentiable rendering`, `#statistical shape model`, `#medical imaging`, `#X-ray`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [苹果宣布特努斯接替库克出任 CEO](https://news.google.com/rss/articles/CBMijAFBVV95cUxORkVvX1BsbWhRV2d4NHp0NW96b0tUSmtNZHVSeDJrczZNVXpEQ2t1c3dOalRwVFgtRUM3Uk1hNUZXY0JUV2JLV3pwdWc5WGtxWk5RXzNMUkl6M0JSYzJJSEpjbU14OTlRZDhrZmZ4S2NROGYwMEE4YkpldHFldHJOUkh4aVk2T29la1RZcg?oc=5) ⭐️ 9.0/10

苹果公司宣布，约翰·特努斯将于 9 月 1 日接替蒂姆·库克出任 CEO，这是苹果 15 年来首次更换一把手；据新浪财经报道，人工智能是新 CEO 的首要任务。

rss · 美股每日要闻 · 8月31日 05:08

**「背景」** 苹果公司宣布，自 2021 年起担任硬件工程高级副总裁的约翰·特努斯将于 2026 年 9 月 1 日接替蒂姆·库克出任 CEO，库克将转任董事会执行主席。这将是苹果 15 年来首次更换 CEO。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/John_Ternus">John Ternus - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Apple`, `#CEO transition`, `#corporate governance`, `#technology`, `#stock market`

---

<a id="item-finance-news-2"></a>
### [沃什杰克逊霍尔讲话推高 9 月加息预期](https://www.cnbc.com/2026/08/31/jackson-hole-fed-chair-kevin-warsh-hawkish-rate-hikes-analysts.html) ⭐️ 8.0/10

美联储主席凯文·沃什在杰克逊霍尔的讲话中表达了对收紧货币政策的倾向，这提高了市场对 9 月联邦公开市场委员会会议采取更紧缩立场的预期。

rss · CNBC Finance · 8月31日 03:47

**「背景」** 美联储主席凯文·沃什在杰克逊霍尔发表鹰派讲话，重申央行对抗通胀的承诺，并暗示当前利率可能不足以将通胀拉回 2%目标。美联储下次政策会议定于 9 月 15-16 日，但沃什的言论并不必然意味着届时会加息。

**「影响」** 分析师认为 9 月加息几率上升，并指出这可能使美联储与财政部关系紧张。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aljazeera.com/economy/2026/8/28/us-fed-chair-warns-inflation-progress-insufficient-hints-at-rate-hikes">US Fed chair warns inflation progress insufficient, hints at rate hikes</a></li>
<li><a href="https://www.nytimes.com/2026/08/28/business/markets-stocks-bonds-warsh-jackson-hole.html">Investors Expect Higher Rates After Fed Chairman’s Inflation Pledge</a></li>
<li><a href="https://magnoliatribune.com/2026/08/28/fed-chair-warsh-signals-rate-hikes-may-be-needed-with-inflation-still-elevated/">Fed Chair Warsh signals rate hikes may be... - Magnolia Tribune</a></li>

</ul>
</details>

**标签**: `#Federal Reserve`, `#monetary policy`, `#interest rates`, `#Jackson Hole`, `#Kevin Warsh`

---

<a id="item-finance-news-3"></a>
### [五大 A 股上市险企上半年净利同比增 78.12%](https://news.google.com/rss/articles/CBMiYkFVX3lxTE9VWjR3T1NQWkRXR0VUZTZCYVZxSUM0c1pwMWN5MEhvdXZqcTF3YlJibW9KcDJzNHhTVVpZbjVxcjZpeHAyUUVGR050UlBoM0JtU01RSEJlUnd3M2wxeTZZOHl3?oc=5) ⭐️ 8.0/10

据观点网报道，五大 A 股上市险企上半年合计净利润为 3173.87 亿元，同比增长 78.12%。

rss · A股每日要闻 · 8月31日 01:05

**「背景」** 这五家险企为中国人保、中国人寿、中国平安、中国太保和新华保险；2025 年上半年，它们合计归母净利润约为 1781.93 亿元，同比增长 3.7%，当时投资端是主要支撑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chinanews.com.cn/cj/2026/08-31/10687030.shtml">投资显效 五大上市险企半年赚超3000亿-中新网</a></li>
<li><a href="https://m.jiemian.com/article/13289222.html">跟着万亿险资炒股：上半年表现亮眼，下半年是进是退？ | 界面新闻</a></li>

</ul>
</details>

**标签**: `#Insurance`, `#Earnings`, `#A-share`, `#Net Profit`, `#China`

---

<a id="item-finance-news-4"></a>
### [希音 SHEIN 拟以同股不同权架构赴港上市](https://news.google.com/rss/articles/CBMiqgFBVV95cUxNSW10cDdmOTViX0VpdlFaTmY1d2pWbFFENkIwcjJ6VVdpMzdSWFVLOTA0cmlaNEVTOGlOR1RzeVdmNElObWFjNmtFR1AxYllGUENDdWFXRGU5NVVsSHdNQWo3cU1oLVpZNUZkR003d25vNzQ4NHBEbmRSSjlhUmcwU3c4M1UtYnRrVGdxRy0wbGtDTjN1SGU1azhKeksxYUctR1FXc0RlTkZwZw?oc=5) ⭐️ 8.0/10

据新浪财经报道，希音（SHEIN）拟以同股不同权（WVR，即加权投票权）架构赴港上市，四位联合创始人合计拥有约 90%的投票权。报道还称，港股采用 WVR 架构的上市公司数量已追平去年全年。

rss · 港股每日要闻 · 8月31日 02:09

**「背景」** SHEIN 是一家全球快时尚零售商，正以同股不同权（WVR）架构赴港上市，这种架构允许四位联合创始人以较少的经济权益保留约 90%的投票权，从而实现上市后仍能掌控公司。港交所数据显示，今年采用 WVR 架构上市的公司数量已追平去年全年，反映这类公司治理安排在香港市场受到持续关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.minichart.com.sg/2026/08/29/shein-global-holdings-limited-ipo-analysis-financial-outlook-broker-coverage-and-listing-prospects/">SHEIN Global Holdings Limited IPO Analysis: Financial Outlook, Broker Coverage and Listing Prospects – Minichart</a></li>

</ul>
</details>

**标签**: `#SHEIN`, `#Hong Kong IPO`, `#dual-class shares`, `#WVR`, `#consumer sector`

---

<a id="item-finance-news-5"></a>
### [伊朗副外长称未经协调船只无法通过霍尔木兹海峡，油价与比特币上涨](https://news.google.com/rss/articles/CBMizgFBVV95cUxPOFdMdVpncFhfSFVJYnIyU2tpckwzZExEa0QxQ2lXWl8zQ0xPUDNPaEk1T1N3SjE1WGF4dGkwZExoVkxCamlaVTU5MWduZ3lUWHB3cFJlVzlfS0xnLVVLTVRXM2JlQUpUTFFxMVZZeEVqVk52UEIyV1pobHZkdmFvUkJEaEgzaGpUenNvUGVoLVotV21jeDJJQzRYY0JMUjZVdEZySW5naGw3SDhzSzJCTmU5TTJRcmZaWk52cHliMmNhTmo0NEdxRlFJVWttUQ?oc=5) ⭐️ 8.0/10

据新浪财经报道，伊朗副外长表示，未经协调任何船只无法通过霍尔木兹海峡。消息引发国际油价盘中直线拉升，比特币涨破 7.8 万美元。

rss · 加密货币每日要闻 · 8月30日 13:54

**「背景」** 霍尔木兹海峡是全球关键的石油运输要道。近期伊朗与阿曼已同意设立临时航运路线，并讨论联合管理提案；同时，美伊围绕该海峡控制权的争夺已持续数月。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aljazeera.com/news/2026/8/26/iran-oman-agree-on-temporary-hormuz-route-what-we-know">Iran, Oman agree on temporary Hormuz route: What we know</a></li>
<li><a href="https://www.cnbc.com/2026/08/25/iran-oman-strait-hormuz-oil.html">Iran and Oman discuss route in Strait of Hormuz, mine ... - CNBC</a></li>
<li><a href="https://www.cnn.com/2026/08/18/business/iran-strait-of-hormuz-oil">Iran has lost significant control of the Strait of Hormuz - CNN</a></li>

</ul>
</details>

**标签**: `#oil prices`, `#Bitcoin`, `#Iran`, `#Strait of Hormuz`, `#geopolitics`

---

<a id="item-finance-news-6"></a>
### [A 股中报利润总额增加 5800 亿元](https://news.google.com/rss/articles/CBMiYEFVX3lxTE9UUk10aFE1Nmxqb2dBX2l1eldoNnI0NDlLdTVhSmZQQ09MU3lUaGszUnpWTnRxWFBZb2RoekJ5M0FCWjN0NDR3aW4tWnZYZkhvZV8wSFFRby1ySHFQbVFHQg?oc=5) ⭐️ 7.0/10

据东方财富发布的 A 股中报全榜单，A 股上市公司半年度财务报告（中报）合计多赚 5800 亿元。

rss · A股每日要闻 · 8月31日 00:03

**「背景」** 2026 年 A 股中报进入密集披露期，东方财富研究中心整理的全榜单显示，上市公司中期净利润合计增加 5800 亿元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.eastmoney.com/a/202608303859501114.html">多赚5800亿！A股中报全榜单来了 _ 东方财富网</a></li>

</ul>
</details>

**标签**: `#A-shares`, `#corporate earnings`, `#mid-year report`, `#China stock market`, `#economic data`

---

<a id="item-finance-news-7"></a>
### [恒指周跌 1.63%，阿里 800 亿元配股全押 AI，54 只股票 9 月入通预期升温](https://news.google.com/rss/articles/CBMiWEFVX3lxTE5OM1k3c2RwbTdNLUhPTmZ0aGs0alA3bDdObEJwTTZpS2J2UDlmRkhKSzQ4TUFKQVVBLWRNcUg3eTg0TndHNHNPVzg1eHl2ZUVWa2JWQ3VqQXo?oc=5) ⭐️ 7.0/10

据界面新闻汇总，恒生指数本周下跌 1.63%，阿里巴巴 800 亿元配股将把资金全部投入人工智能领域。市场对 54 只股票 9 月纳入港股通的预期有所升温，但目前仍是预期而非确定安排。

rss · 港股每日要闻 · 8月31日 01:35

**「背景」** 阿里巴巴于 2026 年 8 月 24 日完成配售定价，以 112.7 港元发行 7.1 亿股新股，预计募资总额约 800 亿港元（净额约 797 亿港元），本次为阿里巴巴 2019 年港股双重主要上市后首次新股配售，资金将全部投入 AI 相关领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cj.sina.com.cn/articles/view/7880068836/1d5b04ee406801f9eo">阿里巴巴拟配售800亿港元新股｜港交所公告原文及完整解读 [2026年8月]...</a></li>
<li><a href="https://m.21jingji.com/article/20260824/herald/d4a86c7f23757b0aba7155b26f4d9555.html">阿里巴巴拟配售800亿港元新股，全部投入AI建设 - 21财经</a></li>

</ul>
</details>

**标签**: `#Hang Seng Index`, `#Alibaba`, `#AI`, `#Stock Connect`, `#Hong Kong stocks`

---

<a id="item-finance-news-8"></a>
### [Cronos 因 Tectonic 遭 7500 万美元借贷漏洞攻击而暂停区块链](https://www.coindesk.com/tech/2026/08/31/cronos-halts-blockchain-after-usd75-million-lending-exploit-hits-lending-app-tectonic) ⭐️ 7.0/10

Cronos 在借贷应用 Tectonic 遭黑客攻击后暂停了其区块链，攻击造成约 7500 万美元损失。

rss · CoinDesk Crypto · 8月31日 04:57

**「背景」** Cronos 链在 8 月 30 日遭攻击后暂停，攻击者操纵了 Tectonic 上流动性较低的 TONIC 代币价格，并以虚高抵押借出真实资产；链上研究员估计损失在 6600 万至 7500 万美元之间。Tectonic 是 Cronos 上最大的借贷协议。

**「影响」** 此次事件主要影响 Cronos 链上 Tectonic 借贷协议的用户；Cronos 暂停出块旨在阻止更多未授权交易，以便调查和追回约 7500 万美元的受影响资产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/08/31/cronos-halts-blockchain-after-usd75-million-lending-exploit-hits-lending-app-tectonic">Cronos halts blockchain after $ 75 million lending exploit hits...</a></li>
<li><a href="https://coincryptonewz.com/cronos-blockchain-halted-after-tectonic-exploit-drains-up-to-75-million/">Cronos Blockchain Halted After Tectonic Exploit Drains Up To $ 75 ...</a></li>
<li><a href="https://dailycryptobriefs.com/news/cronos-tectonic-exploit-75m-chain-halt/">Cronos Halts Network After Tectonic Exploit Hits $75M ...</a></li>
<li><a href="https://epiqtradingfloor.com/blog/cronos-network-suspends-operations-after-75m-tectonic-exploit/">Cronos Network Suspends Operations Following $75M Tectonic ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#DeFi`, `#security exploit`, `#Cronos`, `#Tectonic`

---