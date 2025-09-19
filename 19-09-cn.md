# 宏观经济研究报告
*生成于: 2025-09-19*

## 摘要
- I. 政策与路径：EFFR = 4.33% 于 2025-09-19，高于目标区间中点（4.125%）及 4.00–4.25% 目标区间（EFFR 减中点 = +20.5 基点）。
- II. 就业：薪资仍在扩张但动能放缓：年化 3 个月薪资增长为 0.22%，而 6 个月为 0.48%（数据截至 2025-09-19）；已标记 LABOR_SLOWING 信号。
- III. 通胀：核心 PCE（同比）2.88%，3 个月年化 2.98% 于 2025-09-19；三个月动量 = +0.10 个百分点（略为正向）。
- IV. GDP 增长：实际 GDP 同比 2.8%（最新 2025-09-19）；季度变动 -0.1 个百分点。
- VI. 公司盈利：标准普尔 500 指数于 2025-09-19 为 6,631.96，标记为高位突破并处于过去五年第 100 百分位；短期（20 日）变动报 +261.79%。
- VII. 流动性与货币：截至 2025-09-19，美联储流动性综合指标为中性（指标 = 0）；美联储资产负债表在前 4 周大约下降 98 亿美元，财政部一般账户上升约 2 亿美元。

## 目录
- [摘要](#tldr)
- [核心模块](#core-modules)
  - [I. 政策与路径](#i-policy--path)
  - [II. 就业](#ii-employment)
  - [III. 通胀](#iii-inflation)
  - [IV. GDP 增长](#iv-gdp-growth)
  - [VI. 公司盈利](#vi-company-earnings)
- [扩展模块](#extended-modules)
  - [VII. 流动性与货币](#vii-liquidity--money)
  - [VIII. 美元与大宗商品](#viii-usd--commodities)
  - [IX. 财政与储蓄](#ix-fiscal--saving)
  - [X. 家庭需求与收入](#x-household-demand--income)
  - [XI. 对外部门](#xi-external-sector)
  - [XII. 住房与抵押贷款](#xii-housing--mortgage)
  - [XIII. 加密货币](#xiii-crypto)
  - [XIV. 全球观察](#xiv-global-monitor)
- [未来一周](#week-ahead-high-volatility-events-for-next-week)

## 核心模块
### I. 政策与路径
要点：截至 2025-09-19，市场定价为前置式宽松——预计 2025-10-29 会议将降息约 25 基点，并在接下来的三次 FOMC 会议中累计约 -57.5 基点——同时有效联邦基金利率（EFFR）略高于目标中点，且准备金压力已使 IORB–EFFR 利差收窄。

关键证据：
- EFFR = 4.33% 于 2025-09-19，高于目标区间中点（4.125%）及 4.00–4.25% 目标区间（EFFR 减中点 = +20.5 基点）。
- IORB–EFFR 利差 = -18 基点 于 2025-09-19，标记为准备金压力，并注意到在此前 20 天内大约收窄了 25 基点。
- CME FedWatch（2025-09-19）显示 2025-10-29 会议降息 25 基点的概率为 94.07%（预期会后 EFFR ≈ 3.89%；最可能的目标中点 3.875%）。
- 预计在接下来的三次会议中的累计政策路径为 -57.517 基点（会议日期：2025-10-29、2025-12-10、2026-01-28），特征为前置式宽松。

解读：这些读数结合了高频市场价格（CME 联邦基金期货）和 FRED 报告的利率；数据日期为 2025-09-19，来源为 CME/FRED（经 ETL）。市场隐含概率和短期路径是对近期美联储行动预期的高置信度指标，而 EFFR 与 IORB 利差反映了可能快速变化的操作性资金状况。EFFR 略高于中点且 IORB–EFFR 利差收窄，表明存在临时结算或准备金效应，这可能在政策预期走向降息的同时影响日常 EFFR 波动性。

关注点：
- 2025-10-29 的 FOMC 结果及是否出现被定价的 25 基点降息。
- IORB–EFFR 利差和 IORB 本身的变动（准备金压力逆转将降低 EFFR 波动性）。
- 在 12 月 10 日和 1 月 28 日会议前 FedWatch 概率的重定价以及任何改变前置式宽松叙事的美联储沟通。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/policy_fedwatch_path_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/policy_fedwatch_probs_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/policy_snapshot_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/reserve_rates_20250919.png" width="48%" style="margin-left:1%">
</p>

---

### II. 就业
要点：截至 2025-09-19，美国劳动力市场仍有弹性但明显显示出动能放缓，而非转入衰退。

- 薪资仍在扩张但动能已放缓：年化 3 个月薪资增长为 0.22%，而 6 个月为 0.48%（数据截至 2025-09-19）；已标记 LABOR_SLOWING 信号。
- 初请失业金人数处于低位并相对近期均值略有改善：最新周度初请为 231,000（2025-09-19），4 周移动平均为 240,000，四周下降 3,000，但同比上升 9,000。
- Sahm 规则远低于衰退触发值：Sahm = 0.133 个百分点 截至 2025-09-19（历史上衰退信号为 ≥0.5 个百分点）；失业率 3 个月移动平均为 4.2%，12 个月最低为 4.07%。
- 十二个月背景显示薪资加速低于平均水平（12 个月平均年化 3 个月增幅约 0.95%）。

解读：周度初请提供及时的高频信号，而薪资（按月）易被修正；Sahm 规则是判断衰退启动的可靠经验法则但具滞后性，需要失业率大幅上升才能触发。综合（数据截至 2025-09-19）这些指标表明就业仍呈正增长但动能降温，而非劳动力市场陷入即刻困境。

关注点：
- 未来几个月 3 个月薪资动能是否进一步放缓或企稳。
- 初请 4 周均值的趋势——若持续高于近期均值将提高下行风险。
- 失业率 3 个月移动平均的显著上升，若推动 Sahm 指标接近 0.5 个百分点需要关注。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/jobless_claims_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/sahm_rule_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/labor_momentum_20250919.png" width="48%">
</p>

---

### III. 通胀
要点：截至 2025-09-19，核心通胀运行在约 2.8–3.0% 区间，短期动量小幅为正，市场通胀预期总体在 2.3–2.4% 左右保持锚定。

关键证据：
- 核心 PCE（同比）2.88%，3 个月年化 2.98% 于 2025-09-19；三个月动量 = +0.10 个百分点（略为正向）。
- 核心 CPI（同比）3.11% 相较 PCE 核心 2.88% 高出 0.23 个百分点（截至 2025-09-19）。
- 5 年通胀补偿 2.44%，5y/5y 远期 2.32%（2025-09-19）；市场信号标记为前期锚定，并处于五年窗口第 60 百分位。

解读：这些为 FRED 读数，日期为 2025-09-19；总体对头条和核心指标的可靠性为中高，但短期变动可受能源、季节性住房流动等波动成分影响，以及 CPI 与 PCE 在权重与编制上的差异。核心 PCE 小幅正向动量（+0.10 个百分点）表示过去三个月有温和回升，而非持续再加速；CPI–PCE 的差距（约 0.23 个百分点）更多反映度量与构成差异而非大的基本分歧。5y 和 5y/5y 的补偿在 2.3–2.4% 附近表明通胀预期总体保持锚定。

关注点：
- 下一次核心 PCE 月度公布，观察三个月年化增幅是否持续或消退。
- CPI 与 PCE 的差距及驱动核心差异的组成项（住房、服务等）。
- 5y 与 5y/5y 补偿的变动以及可能改变预期锚定的美联储沟通。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/inflation_momentum_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/inflation_compare_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/inflation_expectations_20250919.png" width="48%">
</p>

---

### IV. GDP 增长
要点：截至 2025-09-19，美国增长为正但结构不一——实际 GDP 同比增长 2.8%，季度略有回落，GDI 与私人投资显示更强的动能，而住房疲软且净出口仍是显著拖累。

- 实际 GDP 同比 2.8%（最新 2025-09-19）；季度变动 -0.1 个百分点。
- 名义 GDI 同比 5.42%（2025-09-19），GDP 与 GDI 的差异为 -1.5 个百分点（GDP 季环比年率 3.3% vs GDI 4.8%），暗示收入端增长强于产出端。
- NIPA 统计差异升高至 $7,608.4 十亿美元 SAAR（2025-09-19），意味着测量的 GDI 超过测量的 GDP，提示测量不确定性。
- 实际私人投资再加速（同比 +0.38%，2 季年化 +3.31%，2025-09-19），而住房活动疲弱（住房综合指数 -8.4% 同比，库存 9.2 个月，2025-09-19）。
- 对外部门混合：实际出口同比 +2.05%，进口同比 +1.27%（2025-09-19），但实际净出口仍深度为负，- $1,029.0 十亿美元（以 2017 链值美元 SAAR 计），四季仅小幅改善。

解读：总体为温和的潜在增长但内部构成不均。较强的 GDI 与私人投资动能显示需求具弹性，但巨大的统计差异降低了对 GDP 产品端读数的信心——应谨慎看待产品端增长读数。住房疲软与持续的净出口拖累限制上行空间。数据源为 FRED/BEA，日期截至 2025-09-19；多数序列为年率化或同比，如前所述。

关注点：
- BEA 的 GDP/GDI 修订及统计差异在未来发布中是否收窄。
- 私人投资季度路径（资本支出细项）以确认再加速是否持续。
- 住房许可、销售与库存趋势，以寻找资产负债表驱动需求变化的迹象。
- 下一次出口/进口公布和贸易价格变动，可能改变净出口拖累程度。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/gdp_yoy_trend_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/gdi_headline_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/gdp_gdi_divergence_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/statistical_discrepancy_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_private_investment_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/growth_composite_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/housing_health_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_exports_chained_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_imports_chained_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_net_exports_chained_20250919.png" width="48%" style="margin-left:1%">
</p>

---

### VI. 公司盈利
要点：截至 2025-09-19，股市处于多年高位，而企业利润增长正在降温，形成市场水平与盈利动能之间的背离。

- 标准普尔 500 指数 6,631.96 于 2025-09-19，标记为高位突破并处于过去五年第 100 百分位；短期（20 日）变动报 +261.79%。
- 公司利润同比 = 4.31%（数据截至 2025-09-19），但两季年化动能 = -1.25%，标记为 PROFITS_COOLING。
- 公司利润水平（SAAR）= $3,981.85 十亿美元，企业税（SAAR）= $3,266.21 十亿美元，动能差异为 -5.56 个百分点。

解读：市场在 2025-09-19 显示强烈信心——反映为标普 500 的突破——而基础利润周期显示增长放缓且近期动能为负。信号来自不同频率与时序：股价为高频且前瞻性，企业利润为季度 BEA NIPA 数据，反映已实现的盈利和税收流。利润动能信号提示在估值高位下对盈利扩张保持谨慎。

关注点：
- 即将公布的季度利润与 BEA 更新，确认或逆转近期利润动能下滑。
- 若价格行为与利润动能长期分化，可能预示估值重定价或由盈利驱动的市场回调。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/spx_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/corporate_profits_cycle_20250919.png" width="48%" style="margin-left:1%">
</p>

---

## 扩展模块
### VII. 流动性与货币
要点：截至 2025-09-19，流动性基本中性——无明显宽松/紧缩信号——同时货币增长适中且实际收益率曲线仍然陡峭。

- 美联储流动性综合指标在 2025-09-19 为中性（指标 = 0）；美联储资产负债表在此前 4 周约下降 98 亿美元，财政部一般账户上升约 2 亿美元。
- M2 同比增长 4.82%，3 个月年化速度 5.82%，M2 总量为 $22,115.4 十亿美元（截至 2025-09-19）；逆回购利率为 4.0%。
- 短端波动：6 个月国债收益率为 3.8%，在此前 20 日出现大幅下跌 31 个基点（截至 2025-09-19），表明短端近期承压缓解。
- 长端实际收益率仍然抬高且近期有所回落：实际 5 年 1.19%、10 年 1.68%、30 年 2.40%，5s–30s 实际利差为 121 基点（均为 2025-09-19），在此前 20 日内各期限大约下降 20–26 基点。

解读：一系列指标（基于 FRED 的资产负债表、RRP、TGA 和货币总量）指向 2025-09-19 的中性流动性背景，而非明显宽松或紧缩。M2 增长适中且短期动能为正（3 个月年化 = 5.82%），在没有抵消性政策动作时可支持名义支出。与此同时，短端最近有所放松（6 个月利率 20 日大幅下降），但长端实际收益率与 5s–30s 的实际坡度仍陡，暗示期限溢价或实际利差在长端仍然存在。数据为标准 FRED 系列的及时读数，但 RRP/TGA 的周度波动和短端国债走动可能产生瞬时信号。

关注点：
- 美联储资产负债表 4 周变动与 RRP 使用情况，留意是否偏离中性。
- TGA 余额变动对流动性的临时收紧。
- 在大幅 20 日波动后短端国债的走势与做市商资金状况。
- M2 动能（3 个月年化）作为名义需求变化的信号。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/money_supply_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/liquidity_combo_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_term_structure_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/rates_moves_20250919.png" width="48%" style="margin-left:1%">
</p>

---

### VIII. 美元与大宗商品
要点：截至 2025-09-19，美元在过去 20 天略有走软，而油价在其五年分布中仍处于低位——布伦特短期略有走高但 WTI 呈周度下行并在过去三个月大幅下跌。

- 美元贸易加权指数 120.49（2025-09-19）；20 日变动 −0.56%；五年百分位约 48（FRED）。
- 布伦特现货美元 67.88/桶（2025-09-19）；20 日变动 +0.58%；五年百分位约 17（EIA）。
- WTI 现货美元 63.06/桶（周度，2025-09-19）；标记为 WEEKLY_DOWNTREND。四周 −1.28%，十二周 −11.88%，五十二周 −5.76%（FRED）。
- WTI 短期均线：4 周均线 63.95 vs 13 周均线 66.84， 与近期下行动能一致。

解读：这些为官方 FRED 与 EIA 读数，日期为 2025-09-19；信号可靠性为中等——价格序列及时但受临时供需与库存波动影响。美元小幅走弱通常会支持大宗商品价格，但布伦特的温和短期上涨与 WTI 的明显周度下跌及低位五年百分位表明油市存在个别动态（区域供给、库存流向或需求疲软）在抑制价格。两大基准的低百分位排名意味着油价在短期内对通胀构成上行压力的可能性有限。

关注点：
- 美元方向，尤其围绕重要美国数据与美联储评论（可改变大宗商品进口成本）。
- OPEC+/供给信号与每周美国原油库存报告，以观察供需平衡变化。
- WTI 周度下行的延续或逆转以及下一次月度需求指标。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/usd_index_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/oil_price_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/oil_weekly_20250919.png" width="48%">
</p>

---

### IX. 财政与储蓄
要点：截至 2025-09-19，财政刺激正在收紧（−3.33 个百分点），因为税收增速快于支出增长，尽管名义赤字仍然很大且有所恶化。

- 财政脉冲 = −3.33 个百分点 于 2025-09-19：税收同比 +10.25% vs 支出同比 +6.93%；头条预算余额 −$1,746.8 十亿美元（四季度变动 −$447.5 十亿美元）。
- 政府净储蓄 $5,621.9 十亿美元（SAAR）和国民净储蓄 $3,488.7 十亿美元——在五年窗口中均处于第 100 百分位，表明相对近期历史水准偏高。
- 私人净储蓄 $4,766.5 十亿美元（SAAR），在过去 12 个月增加 $185.6 十亿美元（支持国内需求缓冲）。
- 实际政府支出动能混合：同比 +1.83%，但两季年化 −0.38%；政府固定资本形成同比 +4.35%（2 季年化 2.72%）。

解读：到 2025 年中期强劲的税收增长在机械上产生了负向财政脉冲（收紧），尽管名义赤字依然很大且较去年恶化。政府与国民净储蓄的高百分位反映近期历史上的偏高水平，而私人储蓄小幅上升在一定程度上抵消财政压力。实际支出动能（同比略正但近两季年化为负）与政府固定投资持续走强表明需求效应混合。

数据可靠性与日期：所有序列来自 FRED（实际政府支出来自 GCEC1）；数值以 SAAR 或同比报告，并截至 2025-09-19。

关注点：
- 税收/收入动能是否持续，是否维持当前的收紧信号。
- 预算平衡的季度路径（看近期扩大的趋势是否继续）。
- 实际政府支出两季动能，观察财政需求是否重新增强。
- 私人储蓄与政府固定投资的轨迹，对长期需求/供给影响的作用。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/fiscal_stance_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/government_net_saving_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/national_saving_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/private_net_saving_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_government_spending_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/government_fixed_investment_20250919.png" width="48%" style="margin-left:1%">
</p>

---

### X. 家庭需求与收入
要点：截至 2025-09-19，家庭收入增长快于实际支出，但消费动能已放缓，储蓄缓冲仍然有限。

- 实际 PCE 数量同比为 2.62%（两季年化 1.03%） 于 2025-09-19，表明消费动能走弱。
- 个人收入（含利息）同比上升 5.01%，但 3 个月年化速度放缓至 1.36%（截至 2025-09-19）。
- 可支配个人收入（DPI）同比为 4.47%，而名义 PCE 同比为 4.71%（均截至 2025-09-19）。
- 个人储蓄率为 4.4% 于 2025-09-19，较 12 个月变化不大（+0.1 个百分点），意味着家庭额外缓冲有限。

解读：这些来自 FRED/BEA 的指标（数据截至 2025-09-19）描绘了收入增长暂时领先于实际支出但短期动能在放缓的情形——标注为 CONSUMPTION_SLOWING 和 INCOME_SLOWING，反映最近 3 个月年化率明显低于同比水平。对汇总 BEA/FRED 系列的可靠性较高，但月度/季度平滑可能掩盖短期波动；最新读数同时捕捉了水平（同比）与动量（短期年化）的动态。

关注点：
- 即将公布的 BEA 个人收入与 PCE 数据，以确认 3 个月放缓的趋势。
- 利息收入与工资增长的趋势，看收入支持能否持续。
- 储蓄率轨迹——若进一步上升将缓冲支出，下跌则放大下行风险。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/consumer_fundamentals_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/personal_income_pulse_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_pce_quantity_20250919.png" width="48%">
</p>

---

### XI. 对外部门
要点：截至 2025-09-19，对外部門表现混合——货物贸易动能显示过去六个月外部拖累有所缓解，但名义净出口总体仍为对 GDP 的大幅且恶化的拖累。

- 货物贸易差额（货物）为 -$78.31 十亿美元 于 2025-09-19，六个月改善 +$50.49 十亿美元，十二个月基本不变（+ $0.33 十亿美元），表明近期赤字缩窄。
- 实际出口数量温和增长：同比 +1.83%，两季年化速度 1.1%（截至 2025-09-19）。
- 净出口（NIPA，SAAR）为 -$869.4 十亿美元 于 2025-09-19，四季恶化 -$657.6 十亿美元；该序列被标记为拖累加剧。
- 来源：FRED（BEA/BOP）用于货物与 NIPA 指标；不同序列在覆盖范围和定义上存在差异。

解读：短期图景混合但一致——出口量温和扩张，货物贸易差额在过去六个月改善，然而名义净出口在四季范围内显著恶化。这种分歧很可能反映组合与价格效应（货物与总 NIPA、服务、主要收入及进出口价格/价值的覆盖差异），而非出口量的大幅萎缩。信号可靠性为中等：这些为官方 FRED/BEA/BOP 系列，但覆盖对外部门的不同部分、不同发布时间和季节调整方式；所有数字均为最新发布、截至 2025-09-19。

关注点：
- 下次月度货物贸易公布以确认赤字缩窄是否持续。
- BEA 季度 NIPA 更新与修订，可能会调和名义净出口的趋势。
- 进口价格、大宗商品价格与外汇变动，可能加宽或缩窄名义净出口拖累。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/trade_balance_momentum_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/real_exports_quantity_20250919.png" width="48%" style="margin-left:1%">
</p>
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/net_exports_nominal_20250919.png" width="48%">
</p>

---

### XII. 住房与抵押贷款
要点：截至 2025-06-30，由于 30 年期利率处于高位，抵押贷款可负担性仍然受限，尽管房价上涨已放缓。

- 30 年期抵押贷款利率：6.77%（锚定月份：2025-06-30）。
- Case-Shiller 房价同比：+1.86%（2025-06-30），表明价格涨幅远弱于此前年份。
- 二手房库存供给（月数）：4.7 个月（2025-06-30），暗示库存状况中度偏紧。
- 二手房销售：3.93 百万套 SAAR（2025-06-30），反映交易活动低迷。

解读：数据来源为 FRED（抵押贷款、Case-Shiller、NAR），锚定日期为 2025-06-30。房价增长放缓减轻了可负担性的一部分压力，但 30 年期利率 6.77% 仍是购房者的主要阻力。库存 4.7 个月低于广泛认为的“平衡”阈值，支持价格的韧性，尽管涨幅疲弱；销售依然低迷。总体上这些头条系列可靠性高，但利率与销售的月度波动可快速改变近期可负担性状况。

关注点：
- 未来数月 30 年期抵押贷款利率走向与美联储政策信号。
- 后续 Case-Shiller 发布以确认价格放缓是否持续。
- 库存（月数）与销售趋势，观察市场供需平衡是否放松或收紧。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/mortgage_affordability_20250630.png" width="48%">
</p>

---

### XIII. 加密货币
要点：截至 2025-09-19，比特币 30 天隐含波动率异常偏低，而永续合约资金费率为正——表明短期恐慌程度低但多头偏好持续。

- BTC 30 天 ATM 隐含波动率 = 34.18%（Deribit） 于 2025-09-19；指标标记为 VOL_LOW，并处于所给历史窗口的第 5 百分位。
- 永续合约资金费率 = 每 8 小时 0.00421%（Binance） 于 2025-09-19；正资金费率有利于多头。
- 7 天平均资金费率 = 每 8 小时 0.00638%，高于今日费率，表明过去一周多头需求有所缓和。
- 数据提供者：Deribit（IV）和 Binance（资金费率）。

解读：低 30 天 IV 与仍为正的资金费率结合表明市场参与者对短期尾部风险较为平静，同时投机性多头敞口仍在。IV 读数处于历史低百分位（截至 2025-09-19），因此自满情绪升高——小幅冲击可能导致 IV 快速重定价。资金费率为正但相较 7 天均值有所回落，指向杠杆的温和撤退而非完全平仓。对这些信号的置信度为中等：交易所报告的资金费率与期权 IV 是及时且可靠的指标，但加密市场在流动性或宏观事件围绕时可快速重定价。

关注点：
- 30 天 ATM IV 是否回升至历史中位以上或从 34.18% 大幅上升。
- 资金费率相较 7 天均值的符号或幅度变化（注意持续上升或转为负值）。
- 现货价格变动及链上/流动性指标，可能触发 IV 或资金费率的快速变化。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/btc_iv_30d_20250919.png" width="48%">
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/btc_funding_20250919.png" width="48%" style="margin-left:1%">
</p>

---

### XIV. 全球观察
要点：截至 2025-09-19，欧洲央行政策利率为 2.0%，欧元区 HICP 通胀基本位于欧洲央行 2% 目标（同比 2.03%），且环比小幅上升 0.2%。

关键证据：
- 欧洲央行政策利率 = 2.0%（数据观察日期：2025-09-19）。
- 欧元区 HICP 通胀 = 2.03% 年同比（最新读数 2025-09-19）。
- HICP 环比（季调）= +0.2%（2025-09-19）。
- 分析信号标注为 ECB_NEUTRAL 与 EU_INFLATION_TARGET（来源：FRED）。

解读：在 2025-09-19 的同时读取 2.0% 的政策利率与约 2% 的 HICP 与中性政策立场一致：通胀接近目标且近期月度动能温和正向。信号来自官方汇总系列并及时，但单一快照并不捕捉分项或部门性的通胀动态（例如核心对能源/食品），这些不同项可能改变短期风险。

关注点：
- 后续月度 HICP 发布以观察 +0.2% 的月度趋势是否具持续性。
- 核心通胀与工资增长，作为潜在压力的指标。
- 欧洲央行的沟通和任何在新数据后的政策指引变化。

- 图表：
<p>
  <img src="https://sp_report.gc.rrrr.run/unified_macro_report/20250919/charts/europe_monitor_20250919.png" width="48%">
</p>

---

## 未来一周（下周高波动事件）
### 2025-09-23（星期二）
- 13:45 UTC: 美国 S&P Global 制造业 PMI [高波动]
- 13:45 UTC: 美国 S&P Global 服务业 PMI [高波动]

### 2025-09-25（星期四）
- 12:30 UTC: 美国国内生产总值 年化值 [高波动]