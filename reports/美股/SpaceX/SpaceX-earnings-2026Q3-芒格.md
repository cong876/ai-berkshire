# SpaceX（NASDAQ: SPCX）2026Q3 财报精读 — 芒格视角：竞争格局与死亡路径

> 视角：芒格 / 行业与竞争研究员｜财报期：2026Q3（截至 2026-09-30）｜写作日期：2026-10-21
> 货币：除特别注明外均为美元（USD），表内单位百万美元。
> 资料可得性：B 级。Q3 新闻稿（8-K Ex.99.1）、Q2 电话会官方逐字稿、S-1 为原文；**Q3 电话会仅有第三方摘要（Motley Fool / Investing.com），凡引用均标注"非原始来源"**；竞争对手数据多为 WebSearch 二手摘要（C 级），已在表内逐项标注。
> 本报告 WebSearch 使用 8 次（配额上限 8），另用 WebFetch 抓取 Rocket Lab Q2 8-K 原文 1 次。

---

## 一句话结论

**Q3 是 SpaceX 的"身份翻转季"：SI（AI 算力与应用）首次贡献过半收入（51.9%）和 83.9% 的资本开支——公司正把两条接近垄断的护城河（发射、Starlink）产生的信用与现金，押注到一个竞争最拥挤、定价最依赖稀缺性的赛道上；而这条赛道上最大的外部收入，来自它在模型层的直接竞争对手（Anthropic）。**

---

## 竞争格局判断（分部）

| 分部 | 判断 | 核心依据（事实） | 反面论据 |
|---|---|---|---|
| Space（发射） | **持平** | 主要对手停摆：ULA Vulcan 自 2026-02 起停飞、New Glenn 自 2026-05 试车台爆炸后未复飞、Rocket Lab Neutron 首飞推迟至 2027（均为二手来源）；管理层称占全球入轨质量约 90%（公司口径） | 自身增长停滞：9M 收入 +2.2%，9M 客户发射 -19.4%、总发射 -11.7%、入轨质量 -6.8%；Starship 节奏目标在一个季度内从"每天至少一次"下调为"2027H1 每周一次" |
| Connectivity（Starlink） | **加强** | 订阅 13.6M（同比 +89%），营业利润率 45.1%（同比 +6.7pp）；Amazon Leo 截至 10 月中旬仍未商用、在轨约 396 颗；中国千帆 + 国网合计约 480 颗；GEO 老牌对手（HughesNet 破产、Viasat 承压，二手来源） | ARPU 同比 -16.9%；分部 SG&A 同比 +198%、占收入比 3.5%→6.2%；Q3 毛利率中约 3pp 为一次性关税退款；Amazon Leo 年底商用并计划捆绑 Prime |
| SI（AI） | **持平（内部分化：算力层加强，模型层弱化）** | 算力：铭牌 1.7 GW，年底 2.5–3 GW，已超过 CoreWeave 年底 1.85 GW 的指引；SI 解决方案与基础设施收入同比 +1,856% | 模型：Grok 全球 AI 网页流量份额 2.4%、第 5 位，半年前 3.7%（Similarweb，二手）；Grok 5 错过 Q1、Q2 目标（二手）；最大外部收入来自模型对手 Anthropic；超大规模云厂商 2026 年 capex 合计约 7,300 亿美元，约为 SpaceX 全公司的 8 倍 |

---

## 一、竞争对手同期对比表

### 1.1 卫星宽带：Starlink vs Amazon Leo vs 中国星座

| 指标 | Starlink（SpaceX） | Amazon Leo（原 Kuiper） | 千帆（Qianfan） | 国网（Guowang） |
|---|---|---|---|---|
| 在轨卫星 | 运营中约 10,200 颗（Q2 电话会官方逐字稿，2026-08）；Q3 起"在轨总数"口径扩大，多计约 400 颗待离轨卫星 | 396 颗（Amazon 副总裁接受 Ars Technica 采访，二手转述，2026-10）；已造出 1,000 颗以上 | 约 238–251 颗，其中约 22 颗失效（azmth / KeepTrack / McDowell，2026-09~10，口径不一） | 约 195–258 颗（azmth / KeepTrack / Wikipedia，2026-09~10，是否含试验星口径不同） |
| 规划规模 | 第一代+第二代合计数万颗（含 FCC 已批 15,000 颗 Mobile V2，Q3 电话会，非原始来源） | 首代 3,232/3,236 颗，2026-01 FCC 另批 4,500 颗 | 2026 年目标在轨 324 颗（公司副总裁，2026-07） | 2026 年 310 颗、2027 年 900 颗（来源为未经核实的微博帖，可信度低） |
| 消费者订阅 | 13.6M（8-K，2026-09-30） | 0（未商用，2026-10 中旬） | 数据不足 | 数据不足 |
| 价格 | 消费者 ARPU 69 美元/月（8-K）；美国住宅套餐 39–85 美元/月区间、部分地区硬件 0 元租用（2026-02~03 媒体报道） | 未公布；Jassy 暗示将低于竞争对手；计划与 Prime 等捆绑（Satnews 2026-10-11） | 数据不足 | 数据不足 |
| 商用时间 | 已商用，174 个市场（Q3 电话会，非原始来源） | 称 2026 年底，先高纬度后赤道（二手） | 已在部分海外市场签约（训练知识，未核实） | 数据不足 |

**谁在赢**：数据表明 Starlink 在卫星数量上领先 Amazon Leo 约 25 倍、领先中国两大星座合计约 20 倍，订阅数上对手为零或未披露。**但另一方面**，Amazon Leo 已造星 1,000 颗以上、工厂产能 5 颗/天，一旦 Vulcan 复飞，部署速度的瓶颈是发射而非制造——而 SpaceX 恰恰也是 Amazon 的发射供应商之一。

### 1.2 发射：SpaceX vs Rocket Lab vs ULA vs Blue Origin

| 指标 | SpaceX Space 分部 | Rocket Lab（RKLB） | ULA（Vulcan） | Blue Origin（New Glenn） |
|---|---|---|---|---|
| 最新季度收入 | Q3'26 1,767（+6%）（8-K） | Q2'26 234.1（+62%）；Q3 指引 250–265（RKLB 8-K Ex.99.1，WebFetch 原文） | 非上市，数据不足 | 非上市，数据不足 |
| 利润率 | Q3 营业利润率 -0.4%；Adj. EBITDA 率 20.2% | Q2 GAAP 毛利率约 36.1%（自算）、非 GAAP 41.5%；GAAP 营业亏损 57.5 | 数据不足 | 数据不足 |
| 2026 发射次数 | 9M 113 次（客户 29、内部 84）（8-K） | 数据不足（新闻稿未列） | 2026 年仅 1 次（2 月 USSF-87），SRB 问题后停飞（二手） | 2026 年 1 次（4 月 NG-3），5 月试车爆炸毁坏唯一发射台，称年内复飞（二手） |
| 积压订单 | 公司合计 630 亿（含 SI，电话会，非原始来源）；Q3 新增 18 次 NSSL、3 次 ISS 载人 | 23.6 亿（+137%） | 数据不足 | 数据不足 |
| 下一代重型 | Starship Flight 14 首次入轨并部署 26 颗 V3 | Neutron 首飞推迟至 2027（247wallst 2026-10-15，二手） | — | 复飞时间未定 |

规模对照：SpaceX Space 分部单季收入约为 Rocket Lab Q3 指引的 6.7–7.1 倍。

**谁在赢**：发射市场的竞争者在 2026 年集体"掉线"，SpaceX 份额不受威胁。**但另一方面**，SpaceX 发射收入并未因对手停摆而跳增（9M +2.2%），说明 Space 分部的约束在自身（Falcon→Starship 过渡、内部发射让位），而不在需求端；Rocket Lab 积压订单增速（+137%）表明客户在主动培养第二供应商。

### 1.3 AI 模型与算力：xAI/Grok vs OpenAI vs Anthropic vs 超大规模云 vs CoreWeave

| 指标 | SpaceX SI | OpenAI | Anthropic | CoreWeave | 超大规模云（2026） |
|---|---|---|---|---|---|
| 收入/ARR | SI Q3 收入 7,560；其中解决方案与基础设施 7,022（含 Cursor 608）（8-K）；全公司 2026 年底 ARR 目标 1,000 亿（含三分部，电话会，非原始来源） | 年化约 500 亿（截至 9 月底，FT 经 Bloomberg 转述）；Axios 曾报约 700 亿，差异源于记账口径 | 7 月底 run rate 650 亿（Bloomberg/CNBC 转述）；Q3 收入约 168 亿（环比 +45%，二手）；年底预测 1,100 亿（WSJ 转述） | Q2'26 收入 26 亿（+112%）（8-K 经搜索摘要） | AWS Q2 422 亿（+37%）；Azure 增速 43%；Google Cloud 增速 82%（单一博客来源，存疑，待核实） |
| 算力规模 | 铭牌 1.7 GW（9/30），10 月约 2.2 GW，年底 2.5–3 GW | 数据不足 | 数据不足（部分算力租自 SpaceX） | 活跃电力 1.5 GW（Q2），年底 >1.85 GW | 数据不足 |
| capex | SI Q3 16,444；全公司 9M 48,069 + Q4 指引 350–400 亿 = 2026 年约 830–880 亿（自算） | 数据不足 | 数据不足 | 2026 年 350–390 亿 | Alphabet 1,950–2,050 亿；Amazon 约 2,200 亿（存疑）；Microsoft 约 1,750 亿；Meta 1,300–1,450 亿；合计约 7,300 亿（二手汇总） |
| 客户集中度 | Anthropic 合同 12.5 亿/月至 2029-05，双方 90 天通知可终止（S-1）；FY2025 客户 A 占合并收入 20.9%（S-1） | — | — | 前三大客户占 Q2 收入 72%（36%/26%/10%） | — |
| 模型/产品指标 | Grok 网页流量份额 2.4%、全球第 5（Similarweb 2026-09，二手；半年前 3.7%）；Grok Bot 周付费用户 80 万（电话会，非原始来源）；Grok 5 尚未发布 | 数据不足 | 数据不足 | — | — |

**谁在赢**：
- **算力租赁层**：数据表明 SpaceX 已是全球前列的独立 AI 算力供给方，铭牌功率超过 CoreWeave，收入/GW 显著更高（见第二节 2.3 的口径警示）。
- **模型层**：证据指向 Anthropic 与 OpenAI 领先。Anthropic 单季收入（约 168 亿，二手）是 SpaceX 整个 SI 分部的 2.2 倍，而 SpaceX SI 收入中相当一部分来自向 Anthropic 出租算力。**但另一方面**，Grok 份额数据全部来自第三方流量统计（Similarweb/Apptopia），不反映 API 与企业收入；SpaceX 未单独披露 Grok 模型收入，模型层判断的置信度为中低。

---

## 二、从财报数据推断竞争变化

### 2.1 各分部增速 vs 行业：跑赢还是跑输

| 分部 | SpaceX 同比增速 | 可比对象增速 | 判断 |
|---|---|---|---|
| Space | Q3 +6%；9M +2.2% | Rocket Lab Q2 +62%（小基数，含航天器系统） | 跑输可比公司，但原因主要在自身转型（见 2.4） |
| Connectivity | Q3 +69%；消费者 +57%；企业与政府 +91% | GEO 卫星运营商收缩（HughesNet 破产，二手）；美国运营商整体个位数增长（训练知识，未核实） | 显著跑赢——Starlink 在吃 GEO 卫星和农村固网的份额 |
| SI 基础设施 | 解决方案与基础设施 +1,856%（359→7,022） | CoreWeave +112%；AWS +37%；Azure +43% | 跑赢，但基数极低且含 Cursor 并表（608）与一次性项目 |

### 2.2 Connectivity：45% 营业利润率 + ARPU 下行，是主动扩张还是被迫应对？

**事实**：
- 订阅同比 +88.9%，消费者 ARPU 同比 -16.9%（83→69 美元），消费者收入 +57.2%（8-K）。量的增长约为价格下降的 5 倍。
- 营业利润率 45.1%，Q2 38.6%、Q3'25 38.4%（自算，8-K）。毛利率 54.9%（CFO 称其中约 3pp 为关税退款等一次性项目，非原始来源）——剔除后营业利润率约 42%，仍高于去年同期。
- ARPU 环比 +5%（66→69），Q1、Q2 均为 66，**下行趋势在本季止步**；CFO 称本季净增 1.6M 由发达市场驱动（新闻稿原文）。
- 分部 SG&A 325，同比 +198%，占收入比 3.5%→6.2%。
- 推算（估计）：按期初期末平均订阅 12.8M × 69 美元 × 3 个月 ≈ 26.5 亿服务收入，消费者收入 31.21 亿中约 4.7 亿为硬件/其他（估计，口径以 10-Q 为准）。

**推断（观点）**：证据更支持"主动扩张"而非"被迫应对 Amazon Leo"：
1. 时间线：ARPU 从 2024 年 91 美元开始下滑，S-1 明确预告国际扩张与低价套餐会继续压低 ARPU；Amazon Leo 至今未商用，不可能是 2025–2026 年 ARPU 下滑的直接原因。
2. 利润率在降价同时上升，说明单位成本下降快于单价——这是规模经济，而不是价格战。价格战的典型特征是"量涨、价跌、利润率跌"，本季不符合。

**但另一方面**：
- 2026 年 2–3 月的免费硬件、39 美元促销发生在 Amazon Leo 宣布年内商用之后、IPO 之前，时间上与"抢在对手上线前锁定用户"一致（Musk 否认是对竞争的反应，二手）。
- SG&A 三倍增长是一个"获客变贵"的信号：若主要是广告/渠道补贴，则意味着发达市场的边际用户正在变难获得；若主要是 IPO 后上市公司成本与人员扩张，则不构成竞争信号。新闻稿未拆分，**数据不足**。
- Amazon Leo 计划与 Prime 捆绑——Amazon 的获客成本结构与 Starlink 不同，其竞争压力将在 2027 年才进入财报。本季数据无法检验。

### 2.3 SI：算力租赁的"超额定价"与客户集中

**事实**：
- SI Adj. EBITDA 率 65.5%；剔除 Cursor 并购股权激励后营业利润率 21.8%（自算）。
- 公司整体毛利率 Q3 62.4%、Q2 55.3%（自算）；CFO 指引 Q4 毛利率"更接近 Q2"，原因为 Q3 含客户结构与一次性项目（非原始来源）。**即 Q3 的利润率有约 7pp 管理层自己不认为可持续。**
- Anthropic 合同：12.5 亿美元/月，至 2029-05，**任一方 90 天通知可终止**（S-1）。全额计费时为 37.5 亿/季。
- 推算（估计）：若 Q3 已全额计费，Anthropic 约占 SI 解决方案与基础设施收入（剔除 Cursor 6,414）的 58%、占公司总收入约 26%。实际计费额以 10-Q 集中度披露为准。
- 收入/GW 对照（估计，口径不同）：CoreWeave Q2 年化收入 104 亿 / 1.5 GW 活跃电力 ≈ 69 亿/GW；SpaceX SI 基础设施剔除 Cursor 年化约 257 亿，若按 50% 外租的 0.85 GW 计 ≈ 302 亿/GW。**两者口径（铭牌 GPU 功耗 vs 活跃电力；内外租比例）不可直接比较**，但量级差异提示 SpaceX 当前合同定价处于稀缺溢价区间——Q2 电话会分析师已直接用"premium pricing"提问（官方逐字稿）。
- 管理层表述偏好"短期、接近现货价的租约"，续约价格更高（Q3 电话会，非原始来源）。

**推断（观点）**：SpaceX 的算力业务目前赚的是"稀缺租金"，而短租 + 90 天终止条款意味着这份租金对现货价格的弹性是双向的。当 GPU/内存供给追上需求（Musk 自己在 Q2 指出内存供给年增约 20%、需求年增 200%），价格会最先在短租合同上回落。

**但另一方面**：积压订单 630 亿（含递延收入 175 亿，约 420 亿 12 个月内确认，非原始来源）、9M 递延收入增加 49 亿，说明客户愿意预付锁定容量；管理层称新部署回收期不到一年——若属实，即使租金回落一半，前期投资也已基本回收。

### 2.4 发射收入停滞：产能瓶颈、Starship 转型，还是需求/竞争问题？

**事实**：
- 9M 客户发射 29 次（-19.4%），但 9M 发射服务收入 21.08 亿（+2.5%）；每次客户发射收入 9M 7,270 万 vs 5,710 万（+27%）（自算，8-K）。Q3 单次 9,420 万 vs 6,670 万。
- 9M 内部发射 84 次（-8.7%），入轨质量 -6.8%；全年化约 151 次，低于 FY2025 的 170 次。
- Space 研发 12.25 亿，同比 +44%，相当于 Space 收入的 69%。
- Q3 新签 18 次 NSSL、3 次 ISS 载人、1 份 Starship 月面载荷合同（新闻稿）。

**推断（观点）**：数据不支持"竞争导致"——对手在停飞，单次价格在上升，新合同在增加。更符合的解释是：（1）Falcon 9 的 Starlink V2 发射逐步让位于 Starship 部署 V3，内部发射次数下降是有意为之；（2）客户发射减少可能与客户自身载荷准备、或部分客户（如 Amazon Leo）的发射日历有关，**数据不足以区分**；（3）单次价格上升反映定价权或任务结构（NSSL、Falcon Heavy、载人任务占比上升），两者在财报中无法拆开。

**但另一方面**：Space 分部本季营业亏损 700 万、9M 亏损 12.11 亿，研发吞噬收入的 69%。如果 Starship 的节奏持续低于预期（见 3.2），Space 分部将长期处于"Falcon 现金牛被 Starship 研发抽干"的状态，而 Falcon 本身的增长已经停止。

### 2.5 研发与 capex：主动进攻还是被迫跟进？

| 分部 | Q3 capex | capex/收入 | 研发同比 | 性质判断（观点） |
|---|---|---|---|---|
| Space | 1,606 | 91% | +44% | 主动：对手无同级产品，投入为自身路线（Starship、路易斯安那 Starbase） |
| Connectivity | 1,543 | 29% | +33% | 主动：V3 星座、Mobile V2、800 MHz 频谱收购（约 80 亿，二手），领先者扩大差距 |
| SI | 16,444 | 218% | +145% | **被迫与主动混合**：算力规模对标的是年 capex 1,300–2,200 亿的超大规模云厂商；SpaceX 2026 全年 capex 约 830–880 亿（自算），仍不到 Alphabet 或 Amazon 单家的一半 |

**推断（观点）**：Space 和 Connectivity 的投入是"领先者加宽护城河"；SI 的投入是"追赶者买门票"——SpaceX 在 AI 不具备发射和星座那样的结构性成本优势，Musk 所称的"火箭工程能力降维打击地面数据中心"（Q2 官方逐字稿）是一个尚未被财务数据验证的论断。

**但另一方面**：SpaceX 的 SI 资本结构有别于纯追赶者——它可以用 Starlink 的现金流和投资级评级融资，用 Tesla/Terafab 自研芯片降低长期成本，且算力外租可以对冲自有模型失败的风险（"即使 Grok 输了，算力也能卖给赢家"）。这是一个对冲结构，而不是纯粹的押注。

---

## 三、管理层对竞争的讨论

### 3.1 是否点名对手、语气如何

| 场合 | 点名/涉及对手 | 语气 | 来源 |
|---|---|---|---|
| Q2 电话会 | "我们鼓励竞争对手复制"；"一些竞争对手的火箭确实会爆炸"；把对手比作需要一个像素才能显示的柱子；称赞 Anthropic Claude 4.5 是"对系统的冲击"；点名 AT&T/Verizon/T-Mobile 合计约 6,000 亿年收入为 Starlink Mobile 目标市场 | 极度自信，带轻蔑；对 AI 模型对手罕见地承认其领先 | 官方逐字稿（A 级） |
| Q3 电话会 | 与台积电/ASML 比较（Terafab，回避 EUV 订单与技术细节）；就 Starlink Mobile 与美国运营商竞争作答；连接业务"有清晰路径达到每年数千亿美元" | 自信；目标继续上调（2027 ARR 5,000 亿–1 万亿） | 第三方摘要（非原始来源） |
| S-1 竞争章节 | 发射：ULA、Arianespace、Northrop、Blue Origin、Rocket Lab；连接：Amazon LEO、Blue Origin TeraWave、OneWeb、AST SpaceMobile；AI：OpenAI、Anthropic、Google、Meta、Microsoft，以及 CoreWeave、Nebius 与超大规模云 | 法律文本，承认"部分 AI 对手拥有更多资源" | S-1 原文 |

### 3.2 本季被提及与被回避的竞争议题

**新提及**：美国运营商作为 Starlink Mobile 的直接对手（800 MHz 频谱收购之后，二手报道显示 Piper Sandler 因此下调 AST SpaceMobile 评级）；Terafab 对标台积电。

**在可得的第三方摘要中未见讨论**（由于没有完整逐字稿，"未见"不等于"未讨论"）：
- Amazon Leo 即将商用及 Prime 捆绑；
- 中国星座；
- Grok 模型的竞争位置、Grok 5 进度；
- Anthropic 等外部客户集中度与 90 天终止条款；
- Cursor 被收购后与 Anthropic/OpenAI 模型供应关系的变化（Cursor 此前大量使用外部模型属公开信息，训练知识，未核实）。

**承诺漂移（Q2 官方逐字稿 vs Q3 第三方摘要）**——这是本季最值得注意的"语气外的信号"：

| 指标 | Q2（8 月） | Q3（10 月） | 方向 |
|---|---|---|---|
| Starship 节奏 | 一年后"至少每天一次" | 2027H1 每周一次，2027 年底每周两次以上 | **大幅下调（约 3.5–7 倍）** |
| V3 临界规模 | 约 1,000 颗，约 2027Q2 | "数百颗"，约 2027 年中 | 口径改变，时间略后移 |
| Starlink Mobile 服务 | 2027 年底开始提供 | 2028 年初开通 | 后移 |
| 2027 年底算力 | 累计约 10 GW | 合计约 13 GW | 上调 |
| ARR | 2026 年底 1,000 亿 | 维持，并新增 2027 年 5,000 亿–1 万亿 | 上调 |

**推断（观点）**：硬件时间表（Starship、V3、Mobile）在下调，AI 叙事目标在上调。前者决定 SpaceX 真正护城河的扩张速度，后者是竞争最激烈的赛道。**但另一方面**，Starship Flight 14 首次入轨并部署可运营 V3 卫星（新闻稿原文）是实打实的里程碑，节奏目标的下调也可能只是从"Musk 时间"回到可执行的规划。

---

## 四、行业趋势信号

### 4.1 V3 + Starship：卫星通信经济学的阶跃

- 事实：Flight 14 部署 26 颗 V3，下行容量约等于 10 次 Falcon 9 Starlink 发射（新闻稿）；Musk 称约三年内星座带宽达到现在约 100 倍（非原始来源）；Q2 称即使每比特变现下降 10 倍，Starlink 收入仍可增长 10 倍（官方逐字稿）。
- 含义（观点）：若成立，Starlink 的单位带宽成本将与任何仍依赖 Falcon 级或更小火箭的对手（Amazon Leo 用 Atlas V/Vulcan/Ariane 6/New Glenn/Falcon 9）拉开一个数量级。**卫星宽带的竞争本质是发射成本竞争**，Amazon Leo 的命门在于没有自有的低成本重型复用火箭（New Glenn 属 Bezos 旗下 Blue Origin，但目前停飞）。
- 反面：V3 的经济性完全依赖 Starship 节奏，而节奏目标本季刚被下调；带宽供给 100 倍增长若快于需求，将进一步压低每比特价格——ARPU 下降的趋势是结构性的，不会停止。

### 4.2 直连手机（D2C）与运营商关系：从伙伴变对手

- 事实：Starlink Mobile 月活超过 2,200 万（环比 +37%，非原始来源）；已与 T-Mobile、软银、NTT Docomo、Spark 等合作（Q2 官方逐字稿）；收购 EchoStar 65 MHz（FCC 已批）与 800 MHz 低频段（预计 2027H1 交割）；Q2 电话会公开把美国三大运营商 6,000 亿年收入作为目标、并计划建设地面网络。
- 竞争者：AST SpaceMobile 获 AT&T、Verizon、Vodafone、Google 战略投资，2027 年初目标约 45 颗卫星（二手）。
- 含义（观点）：SpaceX 正从"运营商的卫星供应商"转向"第四家运营商"，这会把现有运营商伙伴推向 AST。批发收入可能被零售野心牺牲。
- 反面：运营商与 AST 的绑定早于 SpaceX 的频谱收购；AST 自身受 New Glenn 停飞拖累、股价年内 -42%（二手），短期内 Starlink Mobile 的领先没有被威胁。T-Mobile 合作是否受影响：**数据不足**。

### 4.3 AI 算力需求的可持续性与"循环交易"风险

把关系画出来（事实来自 S-1、8-K 与公开报道；箭头方向为资金流）：

- Anthropic → SpaceX：12.5 亿/月算力租金（S-1），90 天可终止。
- Google → SpaceX：云服务合同（Q2 电话会官方逐字稿提及）；Google 同时是 SpaceX 既有股东（S-1 投资者权利协议列名）；Google 也是 Anthropic 的投资者、AST SpaceMobile 的投资者（后两者为公开报道/训练知识，未在本次一手材料中核实）。
- SpaceX → Cursor：2026-04 先签算力与期权协议（S-1），8 月以 600 亿收购——收购前 Cursor 是 SpaceX 的算力客户，收购后变为内部交易。
- Valor（董事 Gracias 旗下）→ xAI：三份算力设备租约，合计约 202 亿，由 SpaceX 担保（S-1）。
- 关联方债务：2025 年底 45.07 亿 → 2026-09-30 128.97 亿（8-K，自算）；Q3 关联方利息费用 3.51 亿、关联方其他收入 5.61 亿。关联方身份 8-K 未披露，**数据不足**。
- 投资活动现金流中"产品返利收入"13.72 亿（8-K）——供应商返利，与 capex 采购相关。
- 客户预付：9M 递延收入增加 49.22 亿（8-K），CFO 把"供应商和客户合作"列为 capex 资金来源之一（非原始来源）。

**判断（观点）**：目前没有证据表明 SpaceX 与 Anthropic/Google 之间存在"互相购买以虚增收入"的对等合同——SpaceX 自己宣布只用 NVIDIA（Q2），未见其向 Anthropic 或 Google 采购算力的披露。但存在三种较弱形式的循环：（1）股东即客户（Google）；（2）供应商返利与客户预付共同资助 capex；（3）向模型层竞争对手出租算力，而自己的 Cursor 是该对手的潜在大客户（或前大客户）。这种结构在需求上行时放大收入，在需求转向时同步放大下滑。
**反面**：所有一线 AI 算力供应商（CoreWeave、Oracle）都有类似的客户集中（CoreWeave 前三大客户 72%），这是行业结构，不是 SpaceX 特有问题；Anthropic 的收入增速（Q3 环比 +45%，二手）表明其付款能力在增强而非减弱。

### 4.4 监管与政府依赖

- FCC：本季正面——Mobile V2 15,000 颗获批（非原始来源）、EchoStar 频谱已批；800 MHz 待批。
- 政府依赖：FY2025 客户 A 占合并收入 20.9%（S-1，横跨三个分部，推测为美国政府，S-1 未点名）；Q2 赢得 60 亿以上 Starshield/太空军合同；2025 年承担 12 次 NSSL 中的 11 次。政府业务是护城河也是政治风险敞口——S-1 自己列明政府可单方面定价未定约合同、并存在被认为"与美国军方过于绑定"而影响海外商业客户的风险。
- 反垄断：本季未见针对 SpaceX 的反垄断行动（数据不足）；Tesla 合并若推进，将面对 SEC 关联交易审查与 Tesla 股东诉讼风险（推测）。
- 海外准入：S-1 测算 TAM 时剔除中国与俄罗斯；欧洲 IRIS²、中国星座均为"主权替代"逻辑，其竞争力不取决于价格而取决于政治——这是 SpaceX 成本优势无法击穿的市场。

---

## 五、死亡路径清单与本期证据

芒格："告诉我我会死在哪里，我就永远不去那儿。"

| # | 死亡路径 | 机制 | 本期证据（朝向/远离） | 方向 |
|---|---|---|---|---|
| 1 | **AI capex 陷阱** | 稀缺租金消失 → 短租合同率先降价 → 每季 160 亿+ 的 GPU 资产按 4–6 年折旧但经济寿命更短 → 用 Starlink 现金流和债务填坑 | SI capex 是 SI 收入的 2.2 倍；Q4 全公司 capex 指引 350–400 亿（约为 Q3 的 2 倍）；管理层偏好短期现货租约；CFO 预告 Q4 毛利率回落；关联方债务 9 个月增长 1.9 倍 ／ 远离：回收期<1 年（管理层口径）、630 亿积压、SI Adj. EBITDA 49.5 亿 | **朝向（加速中）** |
| 2 | **护城河资产被抽血** | Starship/V3 延误 → Starlink 容量增长放缓 → Amazon Leo（Prime 捆绑）+ 中国主权星座 + D2C 对手在 2028 前缩小差距；同时资本与管理层注意力被 SI 吸走 | Starship 节奏目标下调 3.5–7 倍、Mobile 服务后移；Connectivity 和 Space 合计 capex 仅占全公司 16% ／ 远离：Flight 14 入轨并部署 V3；Leo 仍未商用；Connectivity 营业利润同比 +99% | **轻微朝向** |
| 3 | **客户即对手的集中风险** | 最大外部算力客户（Anthropic）是模型层对手，90 天可终止；Cursor 并入后可能改用 Grok → 削弱与 Anthropic/OpenAI 的关系；若 Anthropic 自建/转向 Google TPU，SI 收入可能出现断崖 | Anthropic 合同全额计费约占总收入 26%（估计）；Q3 新签更多云合同（新闻稿，未披露客户名） ／ 远离：客户数增加会稀释集中度；Anthropic 增长强劲 | **朝向（有待 10-Q 量化）** |
| 4 | **治理与关联交易** | Musk 85% 投票权（S-1，IPO 前）；Tesla 合并定价若对 SpaceX 少数股东不利、或用 SpaceX 股份收购 Tesla 资产；关联方融资持续增长 | 双方特别委员会已成立，尚未就条款达成一致（Musk 原话转述，二手）；Musk 称合并"是个好主意"；Tesla 3 月购入约 20 亿 SpaceX 股份（二手）；Terafab 财务条款与 IP 归属未定（S-1） ／ 远离：Musk 回避谈判、Tesla 侧需 50% 流通股批准 | **朝向（新出现）** |
| 5 | **监管/地缘** | 美国政府关系恶化或政府预算收缩；海外市场以国家安全为由排斥 Starlink；频谱审批受阻 | 本季 FCC 审批顺利；新增 18 次 NSSL ／ 未见负面事件 | **远离（本季）** |

### 5 年后回看，本期会是"转折点"吗？

**观点**：有较高概率会被视作转折点，但方向取决于一个尚无法证伪的问题——**SI 是第三条护城河，还是第一个吞噬护城河的黑洞**。
- 若转向"好"：Q3 将被记为 SpaceX 从航天公司变为"发射 + 网络 + 算力"垂直一体化平台的起点，第一次 SI 盈利、第一次 Starship 商业载荷同季发生。
- 若转向"坏"：Q3 将被记为资本配置重心从"有结构性成本优势的赛道"（发射、星座）滑向"没有结构性成本优势的赛道"（GPU 租赁），而 Q3 的 SI 利润率恰好处于稀缺定价的峰值附近（CFO 已预告 Q4 毛利率回落）。

**反面**：判断"峰值"需要至少两个季度的数据；Q4 的 2.2–3 GW 新增算力与 69 亿/6 个月新合同（Q2 官方逐字稿）若按期确认，SI 利润绝对额仍会上升。

### Tesla 合并对竞争格局与少数股东的影响（推测）

- 竞争层面：合并可把 Tesla 的 Dojo/AI5 芯片、Optimus 机器人与 SpaceX 的 Terafab、算力、Starlink 合为一体，强化"物理 AI"叙事；也会把 Tesla 汽车业务的价格战暴露（训练知识）并入 SpaceX 的风险敞口。
- 少数股东层面：两家公司由同一控制人主导，换股比例是零和博弈。SpaceX 少数股东已经无法通过投票影响结果（B 类 10 倍投票权），只能依赖特别委员会的独立性——而 Tesla 董事 Ehrenpreis 同时在两家董事会（二手）。
- 证据现状：仅有"委员会已成立、条款未达成"，**数据不足以评估定价**。

---

## 六、竞争格局评分

| 分部 | 评分 | 依据 |
|---|---|---|
| Space | ★★★★★ | 对手集体停飞，约 90% 入轨质量份额（公司口径），NSSL 11/12；扣分项（增长停滞）属自身转型而非竞争 |
| Connectivity | ★★★★★ | 卫星数领先 20 倍以上，订阅对手为零，利润率在降价中上升 |
| SI | ★★ | 模型层非领先者，算力层以稀缺溢价为生，客户集中且客户即对手，capex 规模不足超大规模云厂商的一半 |
| **公司整体** | **★★★** | 观点：两条近乎垄断的护城河（★5）被一个占 52% 收入、84% capex 的 ★2 业务稀释；若只看 Space + Connectivity 应为 ★5，但资本正在流向 SI，竞争格局的加权重心随资本移动 |

---

## 七、芒格式逆向点评

芒格说过："如果你在一场扑克牌局里玩了半个小时还看不出谁是傻瓜，那你就是傻瓜。"

把 SpaceX 拆开看，有两张王牌和一手普通牌。发射业务的对手在 2026 年集体趴窝；Starlink 的对手还停留在"已造好卫星、等火箭"的阶段——这两门生意的竞争格局，Q3 不但没有恶化，反而更好了。

问题在第三张牌。在 AI 牌桌上，SpaceX 的筹码（年化 capex 不到 900 亿）不到 Alphabet 或 Amazon 单家的一半，模型份额在流量数据上落后并下滑，最大的外部收入来自它要打败的对手，而合同允许对手 90 天走人。这张牌目前赚钱，是因为全行业缺 GPU；当牌桌上的每个人都在同一时间建设同一种资产时，稀缺不会持久——这是芒格反复警告的"大宗商品化"陷阱：**一项所有人都能用钱买到的优势，不是护城河。**

逆向看，最大的风险不是某个竞争对手，而是资本配置：一家拥有两项世界级、结构性成本优势资产的公司，选择把 84% 的 capex 投向一个没有结构性成本优势的赛道。Q2 到 Q3，硬件承诺（Starship 节奏、Mobile 上线）在后移，AI 目标（13 GW、2027 年 5,000 亿–1 万亿 ARR）在上调——叙事的重心和护城河的重心正在分离。

但另一方面必须承认：Musk 的历史纪录正是一次次把"商品化赛道"做成"成本断层"（可复用火箭之于发射、相控阵终端之于卫星宽带）。如果 Terafab 和"轨道算力"真能带来地面对手无法复制的电力/芯片成本，SI 也可能成为第三条护城河。本季财报无法证伪这个可能——但也没有提供任何证据支持它。在证据出现之前，芒格式的做法是：为 Starlink 与发射付合理的价钱，对 SI 部分按"拥挤赛道里的租赁商"估值，而不是按"第三条护城河"估值。

> "反过来想，总是反过来想。"——芒格

---

## 八、数据来源清单

**一手（A 级）**
1. SpaceX Q3 2026 8-K Ex.99.1（2026-10-20）：https://www.sec.gov/Archives/edgar/data/1181412/000162828026066482/spaceexplorationtechnologi.htm
2. SpaceX Q2 2026 新闻稿 8-K（2026-08-04）：https://www.sec.gov/Archives/edgar/data/0001181412/000162828026052515/earningsreleaseq22608042.htm
3. SpaceX Q2 2026 电话会官方逐字稿：https://s21.q4cdn.com/184289198/files/doc_financials/2026/q2/SpaceX-Q2-2026-Earnings_Transcript-FINAL.pdf
4. SpaceX S-1（2026-05-20）：https://www.sec.gov/Archives/edgar/data/1181412/000162828026036936/spaceexplorationtechnologi.htm （竞争章节、Anthropic 合同、客户集中度、关联交易）
5. Rocket Lab Q2 2026 8-K Ex.99.1（WebFetch 原文）：https://www.sec.gov/Archives/edgar/data/0001819994/000181999426000061/rklb-08102026ex991.htm

**第三方/非原始来源（B 级：Q3 电话会摘要）**
6. Motley Fool Q3 2026 电话会转写摘要：https://www.fool.com/earnings/call-transcripts/2026/10/20/spacex-spcx-q3-2026-earnings-call-transcript/
7. Investing.com Q3 电话会摘要：https://www.investing.com/news/transcripts/earnings-call-transcript-spacex-tops-q3-2026-estimates-shares-jump-after-hours-93CH-4961292

**竞争对手与行业（C 级：WebSearch 摘要，未逐一抓取原文）**
8. Amazon Leo：[GeekWire](https://www.geekwire.com/2026/amazon-leo-atlas-ula-launch-satellites/)、[How-To Geek](https://www.howtogeek.com/amazon-leo-is-on-track-to-launch-its-satellite-internet-service-later-this-year/)、[Wikipedia 发射列表](https://en.wikipedia.org/wiki/List_of_Amazon_Leo_launches)、[VoIP Review 2026-10-14](https://voip.review/2026/10/14/amazon-leo-readies-2026-satellite-broadband-debut/)、[Satnews 2026-10-11](https://satnews.com/2026/10/11/amazon-leo-plans-prime-subscription-bundling-to-challenge-starlink-in-consumer-satellite-broadband-market/)
9. ULA / Blue Origin：[Spaceflight Now 2026-08-06](https://spaceflightnow.com/2026/08/06/blue-origin-identifies-engine-issue-behind-new-glenn-explosion/)、[WFTV](https://www.wftv.com/news/local/ula-working-toward-vulcan-return-flight-blue-origin-modifies-rockets-be-4-engines/RGGMBZJDDBC7FBCWGOL4KFVL4Y/)、[Advanced Television 2026-10-09](https://www.advanced-television.com/2026/10/09/blue-origin-confirms-2026-launch/)、[Wikipedia New Glenn](https://en.wikipedia.org/wiki/New_Glenn)
10. Rocket Lab Neutron 推迟：[247wallst 2026-10-15](https://247wallst.com/investing/2026/10/15/rocket-lab-tumbles-11-as-neutrons-first-flight-moves-to-2027-spacex-and-ast-spacemobile-pull-back/)
11. 中国星座：[azmth 千帆](https://azmth.space/tracker/qianfan)、[azmth 国网](https://azmth.space/tracker/guowang)、[KeepTrack](https://keeptrack.space/live-count/how-many-chinese-satellites-are-in-orbit)、[Wikipedia Guowang](https://en.wikipedia.org/wiki/Guowang)
12. 超大规模云 capex 与增速：[CNBC 2026-07-28](https://www.cnbc.com/2026/07/28/hyperscalers-face-higher-capex-scrutiny-after-alphabet-report-panned.html)、[Digital Applied](https://www.digitalapplied.com/blog/ai-capex-scorecard-earnings-week-july-2026)、[ValueAddVC Alphabet](https://valueaddvc.com/blog/alphabet-205b-ai-capex-guidance-2026-what-googles-q2-earnings-raise-actually-buys)、[Third Pole Markets](https://thirdpolemarkets.com/the-big-fours-combined-2026-ai-capex-guidance-hit-700-billion-two-of-the-four-now-have-negative-free-cash-flow/)（Google Cloud 82% 与 Amazon 2,200 亿为单源，存疑）
13. CoreWeave Q2 2026：[SEC 8-K](https://www.sec.gov/Archives/edgar/data/0001769628/000176962826000362/coreweave2q26earningspress.htm)（经搜索摘要）、[CNBC 2026-08-11](https://www.cnbc.com/2026/08/11/coreweave-crwv-q2-earnings-report-2026.html)
14. Grok 份额与模型：[BenchLM](https://benchlm.ai/best/xai-models)、[Shakudo](https://www.shakudo.io/blog/top-9-large-language-models)、[Panto](https://www.getpanto.ai/blog/grok-ai-statistics)
15. OpenAI / Anthropic 收入：[Bloomberg 2026-10-08](https://www.bloomberg.com/news/articles/2026-10-08/openai-s-annualized-revenue-nears-50-billion-ft-says)、[Axios 2026-10-08](https://www.axios.com/2026/10/08/openai-50-billion-arr-anthropic-revenue-accounting)、[Axios 2026-08-17](https://www.axios.com/2026/08/17/anthropic-revenue-run-rate-ipo-openai)（资料包第 8 节转引）
16. Starlink 降价与 D2C：[5Gstore 2026-02-26](https://5gstore.com/blog/2026/02/26/starlink-free-hardware-2026/)、[Mobile Internet Resource Center](https://www.rvmobileinternet.com/summer-2026-satellite-mobile-internet-update-starlink-mobile-targets-cell-carriers-hughesnet-goes-bankrupt-viasat-struggles-ast-spacemobile-slips/)、[247wallst AST 2026-10-20](https://247wallst.com/investing/2026/10/20/ast-spacemobile-lost-40-in-2026-a-wall-street-pro-says-its-going-to-double-by-2027/)
17. Tesla–SpaceX 特别委员会：[TechCrunch 2026-10-20](https://techcrunch.com/2026/10/20/spacex-and-tesla-boards-form-special-committees-to-review-merger/)、[NBC News](https://www.nbcnews.com/business/business-news/elon-musk-spacex-tesla-merger-rcna604685)、[CNBC live updates](https://www.cnbc.com/2026/10/20/spacex-spcx-earnings-live-updates-q3-2026html.html)

**自算说明**：利润率、增速、单次发射收入、收入/GW、Anthropic 占比、2026 全年 capex 均基于上述 8-K/S-1 数字用 Python 计算；Anthropic 占比假设 Q3 全额计费，为估计值，待 10-Q 客户集中度披露核实。

**未能取得/待核实**：Q3 电话会完整逐字稿；Q3 10-Q（客户集中度、关联方身份）；Amazon Q3 2026 财报（预计 10 月底发布）；超大规模云 Q3 2026 财报；Rocket Lab Q3 2026 财报；Grok 模型独立收入；T-Mobile 与 Starlink Mobile 合作现状。
