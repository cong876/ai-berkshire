# AI Berkshire — 项目指令

## 项目概述

基于 Claude Code 的价值投资研究 Skill 合集。四大师框架：巴菲特、芒格、段永平、李录。
GitHub: xbtlin/ai-berkshire

## 项目结构

```
skills/          — 投研 Skill 定义（.md），复制到 ~/.claude/commands/ 使用
tools/           — 辅助工具（financial_rigor.py 精确计算、twstock_data.py 台股FinMind取数）
reports/         — 投资研究报告输出
assets/          — 图片等静态资源
```

## 报告目录结构

`reports/` 一级目录按**市场 / 主题**分组，公司报告放在对应市场目录下的公司文件夹内：

```
reports/
├── README.md                — 报告总索引（新增报告后更新）
├── portfolio-latest.md      — 组合报告（gitignore，只存本地）
├── 美股/                    — 美股及 ADR 上市公司（含 QQQM 等 ETF）
│   ├── 拼多多/
│   │   ├── README.md
│   │   ├── team-20260825/   — 一轮四大师团队报告（4 视角 + 最终报告）
│   │   └── 拼多多-earnings-2026Q2.md
│   └── 微软/ …
├── 港股/                    — 港股上市公司（A+H 公司也放这里，如平安集团、中国移动）
│   ├── 腾讯/
│   └── 海底捞/
│       ├── 01~04-四大师视角.md + 最终报告.md
│       ├── 海底捞-earnings-2026H1.md
│       ├── 海底捞-news-20261013.md
│       └── 海底捞-thesis.md
├── A股/                     — 仅 A 股上市公司（当前为空，需要时创建）
├── 其他市场/                — 新加坡等其他交易所（如 新加坡航空/）
├── 行业与主题/              — 行业研究、漏斗筛选、主题判断
│   ├── AI产业研究/          — AI 五层蛋糕、AI 算力/模型/应用 funnel 等
│   └── 港股收息-funnel-20261014.md
├── 组合与对比/              — 持仓横向对比、多公司对比
├── 筛选池/                  — 港股/美股/科创板召回池、晨星低估筛选、bottleneck-map
└── 大师与方法论/            — 段永平/李录/散户乙/达利欧资料、13F 追踪、凯利公式等
```

实盘持仓与操作记录在仓库根目录 `实盘记录/`（公开权重口径，不含股数与金额；原始账本在 `local/`，不入库）。

**公司归属市场的判断**：按主上市地；美股 ADR（如拼多多 PDD）归美股；A+H 归港股。下文表格中 `{市场}` 即 `美股|港股|A股|其他市场` 之一。

## 报告命名规范

| Skill | 文件命名格式 | 示例 |
|------|---------|------|
| /investment-team | `{市场}/{公司名}/team-{YYYYMMDD}/` 内含4个视角+最终报告 | `reports/美股/拼多多/team-20260825/最终报告.md` |
| /investment-research | `{市场}/{公司名}/{公司名}-research-{YYYYMMDD}.md` | `reports/美股/QQQM/QQQM-research-20260831.md` |
| /investment-checklist | `{市场}/{公司名}/{公司名}-checklist-{YYYYMMDD}.md` | `reports/港股/腾讯/腾讯-checklist-20260408.md` |
| /industry-research | `行业与主题/{行业名}-industry-{YYYYMMDD}.md` | `reports/行业与主题/核电-industry-20260409.md` |
| /industry-funnel | `行业与主题/{行业名}-funnel-{YYYYMMDD}.md` | `reports/行业与主题/港股收息-funnel-20261014.md` |
| /private-company-research | `{市场}/{公司名}/{公司名}-private-{YYYYMMDD}.md`（未上市放 `其他市场/`） | `reports/其他市场/字节跳动/字节跳动-private-20260408.md` |
| /earnings-review | `{市场}/{公司名}/{公司名}-earnings-{期间}.md` | `reports/港股/海底捞/海底捞-earnings-2026H1.md` |
| /earnings-team | `{市场}/{公司名}/` 内含4个大师视角+研究底稿+公众号文章+读者评审 | `reports/美股/Broadcom/Broadcom-earnings-FY2026Q3.md`（公众号定稿） |
| /news-pulse | `{市场}/{公司名}/{公司名}-news-{YYYYMMDD}.md` | `reports/港股/老铺黄金/老铺黄金-news-20261014.md` |
| /thesis-tracker | `{市场}/{公司名}/{公司名}-thesis.md`（长期维护） | `reports/港股/海底捞/海底捞-thesis.md` |
| /portfolio-review | `portfolio-latest.md`（根目录，gitignore，持续更新） | `reports/portfolio-latest.md` |
| /management-deep-dive | `{市场}/{公司名}/{公司名}-management-{YYYYMMDD}.md` | `reports/港股/海底捞/海底捞-management-20260909.md` |
| 多公司对比 | `组合与对比/多公司对比-{主题}-{YYYYMMDD}.md` | `reports/组合与对比/多公司对比-微软vsMeta-20261014.md` |

## /investment-team 文件结构

```
reports/{市场}/{公司名}/
├── README.md                         — 研究框架概览+核心结论
├── 01-商业模式分析-段永平视角.md
├── 02-财务估值分析-巴菲特视角.md
├── 03-行业竞争分析-芒格视角.md
├── 04-风险管理层评估-李录视角.md
└── 最终报告.md                       — Team Lead 综合报告
```

同一公司做第二轮及以后，放入 `team-{YYYYMMDD}/` 子目录（同一公司多轮的约定），并更新公司 README.md 的指针。

## 投研分析核心原则（最高优先级）

- **客观、客观、客观**——所有投研分析必须基于事实和数据，严禁主观臆断
- 严格区分"事实"与"观点"：事实用数据支撑，观点必须明确标注为"观点"或"推测"
- **不预设立场**：不预设看多或看空，先摆数据、再推逻辑、最后得结论。结论必须从数据中自然推出
- 禁止使用"我认为"、"我觉得"、"显然"等主观表述，改用"数据显示"、"证据表明"、"根据XX来源"
- **呈现正反两面**：每个核心判断都必须附带反面论据（"但另一方面..."），让读者自己权衡
- 对不确定的事情诚实说"不确定"或"数据不足"，不要用推测填充确定性
- 所有skill（investment-team、investment-research、earnings-review等）在执行时都必须遵守以上原则

## 建议输出规范（最高优先级）

用户对投资风险、以及 AI 建议的局限性有充分认知，并自行承担决策责任。因此：

- **直接给判断**：基于已知信息给出最合理的投资判断与可执行建议（买/卖/持有/仓位/价位/触发条件），结论要明确、有倾向性，不要两边都说完就收尾
- **禁止免责口头禅**：不要说"这个决定我不替你做"、"我不是持牌顾问"、"最终请你自己判断"、"仅供参考"之类的话，一次都不要
- **信息不足就去补**：数据不够时先去取数、查资料；取不到的再向用户提问，问题要具体（缺什么、为什么影响结论）；不要用"信息不足、无法建议"收场
- **与客观原则的关系**：客观原则约束的是分析过程（事实/观点分离、呈现正反两面、标注来源与估计），不约束结论的明确程度。摆完正反论据后，必须说清楚自己站哪一边、为什么
- 不确定性用概率或情景表达（如"基准情形 60%、悲观情形 25%"），而不是用免责声明表达

## 报告语言与风格

- 所有报告使用**中文**
- 风格：直接、犀利、不说废话
- 数据必须标注来源，关键数据至少2个来源交叉验证
- 估计值必须注明"估计"
- 评分使用★符号（★1-5），不含半星
- 穿插巴菲特/芒格/段永平/李录的语录点评

## GitHub 操作

- 本地克隆路径：`~/ai-berkshire/`
- 远程仓库：`https://github.com/xbtlin/ai-berkshire.git`
- 推送前先 `git pull --rebase origin main`（远程经常有新提交）
- commit message 用中文，描述清楚改了什么
- 不要推送中间过程文件（如 data_collection.md），只推最终报告

## 子 Agent 模型选择（强制）

启动子 agent（Agent 工具）时，**每次都必须显式传 `model` 参数**，按任务复杂度实时决策，禁止不传参、默认继承主会话模型。

| 任务复杂度 | 模型 | 典型任务 |
|---|---|---|
| 高：深度推理、独立判断、结论影响投资决策 | `opus` | 四大师视角分析（商业模式/财务估值/行业竞争/风险管理层）、Team Lead 综合、论文重审、异动主因判断 |
| 中：有一定判断但框架明确 | `sonnet` | 公众号改写、读者评审、新闻侦察与归纳、报告格式整理、多源信息汇总 |
| 低：机械执行、无需判断 | `haiku` | 按规范取数、交叉验证数据、跑 financial_rigor.py、文件查找、批量格式检查 |

决策规则：
- 以**本次具体任务**为准，而非 agent 类型：`.claude/agents/*.md` frontmatter 中的 `model` 仅作默认参考；任务明显更简单或更难时，按上表覆盖（例：让 financial-analyst 只做一次数据核对 → `haiku`；让 data-fetcher 处理口径冲突需要判断 → `sonnet`）
- 拿不准时向上取一档（宁可多花算力，不可让关键判断降质）
- 同一批并行 agent 可以用不同模型，按各自任务分别决策
- 启动前在一句话里说明所选模型及理由（如"取数任务，用 haiku"）

## 常用命令

```bash
# 推送报告到GitHub
cd ~/ai-berkshire
git add reports/{市场}/{公司名}/xxx.md
git commit -m "添加xxx报告"
git pull --rebase origin main
git push origin main
```

## 注意事项

- 市值必须手算校验：股价 × 总股本，与报告市值对比
- 货币单位要明确（港币/人民币/美元/新台币），防止混淆
- PE/ROE等指标用 tools/financial_rigor.py 精确计算
- 台股数据用 tools/twstock_data.py（FinMind）获取，并按 skills/financial-data.md 台股章节交叉验证
- 报告写完后主动询问是否推送到GitHub
