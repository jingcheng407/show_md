# 统一宏观报告（MVP）
*生成日期：2025-09-12*

## TL;DR
- I. Policy & Path：有效联邦基金利率（EFFR）为4.33%（截至2025-09-12），处于目标区间4.25–4.50的下方且低于区间中点约4.5个基点。
- II. Employment：非农就业的短期动能明显减弱：3个月年化增速为0.22%，低于6个月年化的0.48%（指标标注为“LABOR_SLOWING”）。
- III. Inflation：核心PCE同比为2.88%，三个月年化为2.98%（数据截至2025-09-12），三月动能约+0.10个百分点。
- IV. GDP Growth：工业产出与零售合成动能为-0.23z，指向近期实物活动偏弱.
- VI. Company Earnings：标普500指数收于 6512.61，20日回报为 66.85%，并触发“突破高点”动量信号。
- VII. Liquidity & Money：联储净流动性指标为0（中性），过去4周资产负债表减少约38.8亿美元且未触发放松/紧缩阈值 .

## 目录
- [TL;DR](#tldr)
- [核心模块](#核心模块)
  - [I. Policy & Path](#i-policy--path)
  - [II. Employment](#ii-employment)
  - [III. Inflation](#iii-inflation)
  - [IV. GDP Growth](#iv-gdp-growth)
  - [VI. Company Earnings](#vi-company-earnings)
- [扩展模块](#扩展模块)
  - [VII. Liquidity & Money](#vii-liquidity--money)
  - [VIII. USD & Commodities](#viii-usd--commodities)
  - [IX. Fiscal & Saving](#ix-fiscal--saving)
  - [X. Household Demand & Income](#x-household-demand--income)
  - [XI. External Sector](#xi-external-sector)
  - [XII. Housing & Mortgage](#xii-housing--mortgage)
  - [XIII. Crypto](#xiii-crypto)
  - [XIV. Global Monitor](#xiv-global-monitor)
- [Week Ahead](#week-ahead未来一周高波动性事件)

## 核心模块
### I. Policy & Path
底线：市场在2025-09-12定价高度倾向于在9月17日降息25个基点，并预计未来三次会议累积下调约72个基点。

要点证据：
- 有效联邦基金利率（EFFR）为4.33%（截至2025-09-12）[id=policy_snapshot@2025-09-12]，处于目标区间4.25–4.50的下方且低于区间中点约4.5个基点[id=policy_snapshot@2025-09-12]。 
- 储备利率（IORB）为4.4%且IORB–EFFR利差为7个基点（截至2025-09-12）[id=reserve_rates@2025-09-12]，表明储备利率高于市场有效利率（储备机制处于常态区间）。
- 对9月17日会议的市场预期：会后预期EFFR约4.104%（预期单步变动−27.086个基点），市场对“降25个基点到目标中点4.125%”的概率为91.6552%（截至2025-09-12）[id=next@2025-09-12]；归一化熵为0.414，显示概率分布较为集中[id=next@2025-09-12].
- 未来三次会议的累计预期路径显示总计下调约71.768个基点（涵盖2025-09-17、2025-10-29、2025-12-10）[id=path3@2025-09-12].

解读：数据窗口以2025-09-12为基准。市场定价对即将到来的25bp降息显示高置信度（单次结果概率>90%且熵中等偏低），同时隐含后续两次会议也将继续逐步降息，合计接近−72bp。这些价格信号的可靠性较高（因概率集中且由交易所期货隐含），但仍依赖于FOMC在9月17日的公开表态及之后的经济数据——尤其是通胀与劳动力面向的最新数据。EFFR略低于目标中点且IORB高于EFFR，说明当前工具组合（IO利率）仍能维持政策传导，但若FOMC选择不同步或仅发表鹰派言论，市场路径将快速调整。

关注事项：
- 关注FOMC在9月17日的声明与点阵、以及主席新闻发布会对降息节奏的明确性；
- 关注9月中旬前发布的关键宏观数据（通胀与就业）是否支持市场判断；
- 监测IORB与EFFR利差的变化——若利差缩小或逆转，可能反映市场流动性/储备条件的变化，从而影响政策传导机制。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/policy_fedwatch_probs_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/policy_fedwatch_path_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/policy_snapshot_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/reserve_rates_20250912.png)

---

### II. Employment
底线：截至2025-09-12，劳动力市场显示出放缓迹象——初请和就业增长都有小幅上升或减速，但尚未触发常用的衰退警报。

- 非农就业的短期动能明显减弱：3个月年化增速为0.22%[id=PAYEMS@2025-09-12]，低于6个月年化的0.48%[id=PAYEMS@2025-09-12]（指标标注为“LABOR_SLOWING”）。
- Sahm衰退信号仍远低于阈值：Sahm值为0.133个百分点（阈值为0.5pp）[id=sahm_rule@2025-09-12]，3个月移动平均失业率为4.2%[id=sahm_rule@2025-09-12]。
- 初次申领失业救济人数出现上行：最新周值为237,000人[id=jobless_claims@2025-09-12]，4周均值231,000人并较4周前增加10,000人[id=jobless_claims@2025-09-12]，表明短期压力在积累。

解读：当前信号指向“降速但未衰退”。Sahm规则在历史上对衰退转换具有较高指示性，但其阈值（≥0.5pp）尚未接近，因此不支持已进入衰退的结论。与此同时，非农3个月动能明显低于6个月和12个月均值，说明就业增长在近期放缓；初请的连续小幅上行增加了短期下行风险。所有数据点均以2025-09-12为观测基准；周度初请易受噪声影响，需以4周均值为主判断。

应关注：
- Sahm值是否持续上升并接近或超过0.5pp（触发衰退警报）。
- 非农3个月与6个月年化差距是否继续扩大（进一步确认动能衰退）。
- 初请4周均值能否持续走高并突破此前区间（表明失业压力实质化）。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/labor_momentum_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/jobless_claims_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/sahm_rule_20250912.png)

---

### III. Inflation
底线：截至2025-09-12，核心通胀仍在约3%附近，短期动能略强于年化同比且市场对中期通胀预期保持锚定。

- 核心PCE同比为2.88%[id=PCEPILFE@2025-09-12]，三个月年化为2.98%[id=PCEPILFE@2025-09-12]（数据截至2025-09-12），三月动能约+0.10个百分点[id=PCEPILFE@2025-09-12]。
- CPI与PCE核心指标存在小幅分歧：CPI核心同比3.05%[id=inflation_compare@2025-09-12]、PCE核心同比2.88%[id=inflation_compare@2025-09-12]，两者差异约0.17个百分点（CPI偏高）[id=inflation_compare@2025-09-12]（截至2025-09-12）。
- 市场5年期通胀预期（5y breakeven）约2.43%[id=inflation_expectations@2025-09-12]，指标标注为“FORWARD_ANCHORED”，表明中期通胀预期较为稳定（数据截至2025-09-12）。

解读：近期核心PCE的三个月年化略高于同比（+0.10个百分点），提示短期通胀动能有温和回升，但幅度很小，信号强度有限。CPI核心比PCE核心高出约0.17个百分点，部分反映两类指数的覆盖与权重差异而非明确的通胀加速。5年通胀预期在2.43%并被标记为锚定，支持市场对中期通胀回归目标附近的判断。总体信号可靠性中等：预期信号相对稳固，但短期动能的上行幅度较小且可能受基数、季节性或一次性项影响（数据点均截至2025-09-12）。

关注要点：
- 下月的PCE与CPI月度数据，尤其三个月年化的延续性，以判断短期动能是否持续；
- 若CPI与PCE的分歧扩大，需警惕测量差异以外的价格压力；
- 监测5年/10年breakeven的变动，任何显著上行将挑战预期锚定性。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/inflation_compare_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/inflation_momentum_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/inflation_expectations_20250912.png)

---

### IV. GDP Growth
底线：截至2025-09-12，宏观动能总体温和但存在分歧——高频实物活动偏弱，收入端（GDI）与投资侧表现较强，但巨大的统计差额降低了对产品侧GDP读数的信心。

- 工业产出与零售合成动能为-0.23z，指向近期实物活动偏弱[id=growth_composite@2025-09-12].
- 实际GDP同比为2.8%且季度环比变化为-0.1个百分点（读数截至2025-09-12），显示年率水平温和但动能小幅回落[id=gdp_yoy_trend@2025-09-12].
- 实际私人投资已出现再加速：YoY 0.38%[id=real_private_investment_momentum@2025-09-12]，两季年化约3.31%，为内需提供潜在上行动力。
- 名义GDI同比为5.42%[id=gdi_nominal_momentum@2025-09-12]，但GDP与GDI季度差异为-1.5pp（GDI>GDP），表明收入侧比产出侧更为强劲[id=gdp_gdi_divergence@2025-09-12].
- NIPA统计差额水平异常高：7,608.4 USD bn（SAAR，读数截至2025-09-12），提示产品侧与收入侧的衡量存在重大不一致，降低单一GDP读数的可靠性[id=W260RC1Q027SBEA@2025-09-12].

解读：数据窗口截至2025-09-12。当前信号的总体可靠性为中等——实际产出动能由工业和零售信号指向疲软，但名义收入（GDI）与私人投资的回升提供对增长的支撑。大规模的统计差额和GDP/GDI分歧意味着短期内对“谁更能代表真实经济”存在不确定性，需等待未来季度的修订与进一步的产出/收入数据来验证方向。短期解读应同时参考收入端与产出端指标，而非仅依赖单一GDP读数。

关注要点：
- 关注后续BEA对GDP/GDI的修订及统计差额是否收敛（判定当前分歧是暂时噪声还是结构性差异）。
- 跟踪未来月度工业产出与零售数据，检验合成动能（-0.23z）的持续性或反转（高频活动能否回稳）。
- 监测私人投资和净出口动向（若私人投资继续回升且净出口改善，可支撑下一季度名义与实际增长）。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/gdp_yoy_trend_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/gdi_headline_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/gdp_gdi_divergence_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/growth_composite_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/statistical_discrepancy_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_private_investment_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_exports_chained_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_imports_chained_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_net_exports_chained_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/housing_health_20250912.png)

---

### VI. Company Earnings
底线：截至 2025-09-12，股市呈现强劲技术性突破，但企业利润增长正在放缓，出现估值与盈利动力的背离。

- 标普500指数收于 6512.61[id=SP500@2025-09-12]，20日回报为 66.85%[id=SP500@2025-09-12]，并触发“突破高点”动量信号。
- 在 5 年窗口内，标普的分位数为 100[id=SP500@2025-09-12]，表明价格处于历史区间顶端。
- 企业利润同比为 4.31%（截至 2025-09-12）[id=corporate_profits_cycle@2025-09-12]，但两季度年化动量为 -1.25%[id=corporate_profits_cycle@2025-09-12]，被标注为“利润降温”。
- 企业利润绝对水平约为 3,981.85 十亿美元年率化（SAAR）[id=corporate_profits_cycle@2025-09-12]，企业税收约为 3,266.21 十亿美元年率化[id=corporate_profits_cycle@2025-09-12]，提供盈利规模背景。

解读：截至 2025-09-12 的信号显示出明显的短期价格动量（标普突破）与中期基本面疲软（企业利润同比温和、两季度动量为负）之间的分歧。标普的突破为技术性强信号，短期可驱动估值上行；企业利润数据来自 BEA（NIPA），具有滞后并可能被修订，因此对盈利可持续性的判断应以未来利润动量和季报为准。

关注点：
- 观察未来几次 BEA/公司财报对企业利润同比和两季度动量的修正，特别是动量是否从负转正。
- 监测即将到来的季报季与公司盈利指引，以验证价格突破是否获得基本面支撑。
- 留意短期市场动量回撤（如标普短期回报与波动），以判断突破的持续性。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/corporate_profits_cycle_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/spx_20250912.png)

---

## 扩展模块
### VII. Liquidity & Money
底线：截至2025-09-12，整体流动性信号中性，M2增速温和且有回升迹象，真实利率曲线保持陡峭，而短端国债在近20天出现明显下行调整。

- 联储净流动性指标为0（中性），过去4周资产负债表减少约38.8亿美元且未触发放松/紧缩阈值 [id=liquidity@2025-09-12].
- M2同比增长4.82%（截至2025-09-12），三个月年化增速约为5.82%，货币供应水平约22115.4亿美元，逆回购利率/报价为4.25% [id=money_supply@2025-09-12].
- 实质利率曲线（5s–30s）展现陡峭斜率约130个基点，分段实质收益率：5年≈1.16%，10年≈1.70%，30年≈2.46%（均为2025-09-12数据） [id=real_term_structure@2025-09-12].
- 短端波动：6个月期美债收益率为3.84%，過去20天下行约31个基点，為樣本期內最大短期幅度變動者（截至2025-09-12） [id=DGS6MO@2025-09-12].

解读：这些指标来自FRED及合成流动性监控（WALCL、RRPONTSYD、WTREGEN），日期统一为2025-09-12。流动性合成信号为“中性”表明系统性宽松或紧缩均未显著占优，但资产负债表的近期小幅收缩和短端国债的快速下行反映出市场技术性资金/利率预期的短期重估。真实利率曲线的持续陡峭倾向支持长期实际利率高于短端，增加期限溢价不确定性。信号可靠性较高（官方数据源），但短期利率波动具有较强的交易性/季节性成分，需要与逆回购使用和TGA变动共同解读。

关注点：
- 逆回购利率与日常使用量变化（当前逆回购报价/利率4.25%）以判断超额流动性吸收力度 [id=money_supply@2025-09-12].
- 联储资产负债表周度变动和財政部TGA變化，若连续收缩可能推动短端利率上行或流动性偏紧 [id=liquidity@2025-09-12].
- 短端国债（尤其6M）若继续下行超过当前20天幅度，应警惕市场避险或资金错配的技术性影响 [id=DGS6MO@2025-09-12].

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_term_structure_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/money_supply_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/liquidity_combo_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/rates_moves_20250912.png)

---

### VIII. USD & Commodities
底线：截至2025-09-12，美元略有回落但总体中性，油价维持在相对偏低区间且WTI周线显示中期下行压力。

- 美元贸易加权指数为120.54[id=DTWEXBGS@2025-09-12]，近20天变动 -0.37[id=DTWEXBGS@2025-09-12]%。
- 布伦特现货报68.09[id=D@2025-09-12] USD/桶（2025-09-12），近20天变动 -1.47[id=D@2025-09-12]%，5年分位为18[id=D@2025-09-12]（偏低）。
- WTI周价报64.52[id=WCOILWTICO@2025-09-12] USD/桶（2025-09-12），四周变动 -5.06[id=WCOILWTICO@2025-09-12]%，十三周移动平均67.27[id=WCOILWTICO@2025-09-12] 高于四周移动平均64.69[id=WCOILWTICO@2025-09-12]，並触发周线下行信号（WEEKLY_DOWNTREND）[id=WCOILWTICO@2025-09-12]。

解读：短期内美元仅小幅回调，20天跌幅有限，5年分位接近中性，表明美元并未出现明显趋势反转（数据点截至2025-09-12）。与此对应，油价处于历史偏低区间（布伦特5年分位18），且WTI的四周显著下滑与周线下行信号暗示中期库存或需求面存在下行压力。信号可靠性方面：美元短期信号较弱（小幅变动、分位中性），油价的中期下行更具说明力（多周期下行和低分位一致）。

关注要点：
- 若美元走弱扩大（超过短期波动范围），可能支撑油价回升；反之美元回强将抑制油价。  
- 观察OPEC+或主要产油国的供应动作与美国库存数据，检验WTI周线下行是否延续。  
- 关注宏观需求指标（全球PMI、航运/贸易动量）以判断油价中长期恢复力度。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/usd_index_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/oil_weekly_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/oil_price_20250912.png)

---

### IX. Fiscal & Saving
底线：截至2025-09-12，税收增长快于支出导致的“收缩性”财政冲击（-3.33个百分点）出现，但以美元计的预算赤字仍在扩大，须警惕短期收入波动对赤字路径的影响。

- 财政冲击 = -3.33 pp，收款同比+10.25%，支出同比+6.93%；当期预算余额约-1,746.8 (USD bn)，过去4季变动-447.5 (USD bn) [id=fiscal_stance@2025-09-12].
- 政府净储蓄为5,621.9 (USD bn)，在过去5年窗口的百分位为100，表明相对较高的政府净储蓄水平[id=government_net_saving@2025-09-12].
- 净国民储蓄为3,488.7 (USD bn)，5年百分位100，整体国民储蓄位于高位区间[id=national_saving_level@2025-09-12].
- 私人净储蓄4,766.5 (USD bn)，12个月变动+185.6 (USD bn) [id=private_net_saving@2025-09-12]；实际政府支出同比+1.83%（2季年化-0.38%）[id=real_government_spending_momentum@2025-09-12]；政府固定投资同比+4.35%（2季年化+2.72%）[id=government_fixed_investment@2025-09-12].

解读：数据截至2025-09-12。财政冲击指标反映的是支出增速与收入增速的差异——当前为负值，意味着收入增速领先于支出，短期内对需求有收缩性影响；但以水平计的预算余额仍为较大赤字，表明增速指标与存量（美元赤字）之间存在会计与时序差异。政府和国民净储蓄在5年窗口中处于高位（百分位100），提高了信号的相对可靠性，但该百分位基于短期窗口，需结合更长期序列与财政政策结构性变化来判断可持续性。

关注要点：
- 关注未来季的税收增速是否回落（财政冲击可能从收缩转向中性或扩张）。
- 跟踪美元计预算余额的季度变化与4季累计变化以判断赤字趋势是否实质收窄。
- 监测实际政府支出与固定投资动能（当前2季年化略有减速），如支出或投资回升，财政立场将快速转向宽松。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/fiscal_stance_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/government_net_saving_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/national_saving_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/private_net_saving_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_government_spending_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/government_fixed_investment_20250912.png)

---

### X. Household Demand & Income
底线：截至2025-09-12，家庭收入增速仍快于实际消费，储蓄率略有回升但总体偏低，消费动能显示放缓迹象。

- 实际PCE同比2.43%[id=consumer_fundamentals@2025-09-12]，可支配个人收入（DPI）同比4.47%[id=consumer_fundamentals@2025-09-12]（均截至2025-09-12），收入增速高于消费。 
- 个人收入脉冲（含利息）同比5.01%[id=personal_income_pulse@2025-09-12]，但3个月年化仅1.36%[id=personal_income_pulse@2025-09-12]，分析标签显示“收入放缓”。
- 实际PCE数量同比2.62%[id=real_pce_quantity_momentum@2025-09-12]，两季度年化约1.03%[id=real_pce_quantity_momentum@2025-09-12]，消费动能弱化（信号：CONSUMPTION_SLOWING）。
- 储蓄率为4.4%[id=consumer_fundamentals@2025-09-12]，过去12个月变动仅+0.1个百分点[id=consumer_fundamentals@2025-09-12]，表明家庭缓冲有限且易受冲击。

解读：以上数据来自BEA（通过FRED），均以2025-09-12为最新观测日。总体信号一致性中等——名义/同比层面收入看起来仍较强，但短期年化和量的指标显示消费动能在下降，提示支出增长可能难以维持。数据的高频年化读数（3个月、2季度）对短期拐点更敏感，应结合就业与信贷条件共同判定。

关注点：
- 下次PCE和DPI月度发布，看是否延续量的疲弱或收入回落；
- 个人利息收入和利率走势对可支配收入的持续影响；
- 储蓄率是否继续回升（缓冲能力变化）或被消费支出耗尽。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/consumer_fundamentals_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_pce_quantity_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/personal_income_pulse_20250912.png)

---

### XI. External Sector
底线：截至2025-09-12，外需动能有所改善但名义净出口规模仍然对增长构成显著拖累。

- 货物贸易差额动能表明赤字在收窄：当前货物贸易差额为 -78.31 USD bn（截至2025-09-12），过去6个月改善了50.49 USD bn [id=trade_balance_momentum@2025-09-12].
- 名义净出口仍为大幅负值且四季度累计恶化：净出口（NIPA，SAAR）为 -869.4 USD bn（截至2025-09-12），較前四季度减少657.6 USD bn，信号显示净出口对GDP的拖累在加重 [id=net_exports_nominal@2025-09-12].
- 实际出口量增长温和：实际出口同比 +1.83%（截至2025-09-12），两季度年化约 +1.1% [id=real_exports_quantity_momentum@2025-09-12].

解读：货物贸易差额的短期动能改善暗示赤字收缩的趋势正在形成，但名义净出口的四季度大幅下滑表明規模效应（如进口回升、價格或估值變動）仍可能使对GDP的净拖累持续。数据来源为 FRED/BEA/BOP，时间点为2025-09-12，动能指标与名义规模指标存在时间与口径差异，应同时考量。

关注要点：
- 后续BEA商品与服务贸易及净出口季度数据（检验名义规模的延续性）。
- 实际出口量的连续性：若出口量持续回升，可缓和名义拖累。 
- 进口趋势、美元汇率与大宗商品价格对名义值的传导。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/net_exports_nominal_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/trade_balance_momentum_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/real_exports_quantity_20250912.png)

---

### XII. Housing & Mortgage
底线：截至2025-06-30，住房可负担性仍受制于高抵押利率与偏紧库存，尽管房价增速已显著回落。

- 30 年固定抵押贷款利率为 6.77%（截至 2025-06-30）[id=mortgage_affordability@2025-09-12].
- Case‑Shiller 房价同比增速为 1.86%（截至 2025-06-30），显示价格上涨已明显放缓[id=mortgage_affordability@2025-09-12].
- 现有住房供给约为 4.7 个月（截至 2025-06-30），仍偏向供不应求的区间[id=mortgage_affordability@2025-09-12].
- 年化现有住房销售约为 3,930 千套（2025-06-30），交易活动维持中等水平[id=mortgage_affordability@2025-09-12].

解读：该合成指标基于抵押利率、Case‑Shiller 房价和 NAR 销售/库存数据，信号可信度中等——抵押利率上行明显抬高购房成本，但房价同比回落在一定程度上缓和了压力。数据截止为 2025-06-30；自那以后若利率继续变动或库存出现季节性变化，可负担性评估会随之调整。

关注点：
- 持续跟踪 30 年抵押利率走势及 Fed 动向（影响按揭成本）。
- 下一期 Case‑Shiller 和 NAR 月度库存/销售数据，判断价格与供应是否进一步分化。
- 抵押贷款申请量和房屋新上市量，作为短期需求与库存变化的先行指示器。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/mortgage_affordability_20250630.png)

---

### XIII. Crypto
底线：截至 2025-09-12，BTC 期权隐含波动率处于偏高中位，永续合约资金率为正，整体偏向轻度多头。

关键证据：
- BTC 30D ATM 隐含波动率为 37.5% [id=BTC_IV_TERM_30D@2025-09-12]，在 3 年窗口的百分位为 65% [id=BTC_IV_TERM_30D@2025-09-12]（数据日期：2025-09-12）。
- Binance BTC 永续合约资金率为 0.00581%/8h [id=BTCUSDT_FUNDING@2025-09-12]，7 日均为 0.00741%/8h [id=BTCUSDT_FUNDING@2025-09-12]（数据日期：2025-09-12），正值表明杠杆需求偏向多头。

解读：
这些读数均为 2025-09-12 的快照。期权 IV（Deribit）在第 65 百分位，表明波动率相对近年偏高但非极端；永续资金率（Binance）为正且短期均值略高于即时值，显示多头杠杆需求存在但幅度有限。信号可靠性：IV 更能反映市场对未来不确定性的定价，通常稳定性高于交易所资金率；资金率容易受短期资金流和交易所特定流动性影响，应与成交量、现货走势一并解读。

关注要点：
- 若 IV 出现快速上升至更高百分位，意味着风险溢价在抬升，应警惕波动加剧。
- 若资金率持续走高，表明多头杠杆进一步积聚，增加短期回调风险；相反，资金率转负则提示空头压力上升。
- 监测资金率与 IV 的背离：资金率上升而 IV 走低或相反，可能预示短期情绪驱动而非基本面变动。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/btc_iv_30d_20250912.png)
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/btc_funding_20250912.png)

---

### XIV. Global Monitor
底线：截至2025-09-12，欧洲央行政策利率为2.0%，欧元区HICP同比约为2.01%，通胀已接近目标区间，货币政策总体处于中性偏谨慎状态。

- 政策利率：2.0% [id=europe_monitor@2025-09-12]（数据截至2025-09-12）。
- 欧元区HICP（同比）：2.01% [id=europe_monitor@2025-09-12]（数据截至2025-09-12）。
- 分析信号：ECB_NEUTRAL、EU_INFLATION_TARGET，表明通胀接近目标且货币立场偏中性（数据源：FRED）。

解读：合并指标在2025-09-12的读数支持“接近目标、维持中性”的政策判定。信号可靠性为中等——同比数据明确但缺乏月度动量信息（hicp_mom为空），因此短期通胀波动和即时政策反应的判断仍需更多高频数据与分项信息作为补充。

关注要点：
- 接下来几次欧元区月度HICP与核心通胀发布（特别是环比数据）。
- 即将召开的ECB利率决议与前瞻性指引。 
- 能源与食品价格走势及其对短期通胀的影响。
- 各成员国间核心通胀分化是否加剧。

- 相关图表：
- ![](https://sp_report.gc.rrrr.run/unified_macro_report/20250912/charts/europe_monitor_20250912.png)

---

## Week Ahead（未来一周高波动性事件）
### 2025-09-12 (Friday)
- 14:00 UTC: US Michigan Consumer Sentiment Index [高波动]

### 2025-09-16 (Tuesday)
- 12:30 UTC: US Retail Sales (MoM) [高波动]
- 12:30 UTC: US Retail Sales Control Group [高波动]

### 2025-09-17 (Wednesday)
- 18:00 UTC: US Fed Interest Rate Decision [高波动]
- 18:00 UTC: US Fed Monetary Policy Statement [高波动]
- 18:00 UTC: US FOMC Economic Projections [高波动]
- 18:00 UTC: US Interest Rate Projections - 1st year [高波动]
- 18:00 UTC: US Interest Rate Projections - 2nd year [高波动]
- 18:00 UTC: US Interest Rate Projections - 3rd year [高波动]
- 18:00 UTC: US Interest Rate Projections - Current [高波动]


