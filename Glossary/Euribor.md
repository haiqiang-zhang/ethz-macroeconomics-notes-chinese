---
base:
  - "[[Glossary.base]]"
Solved: false
Short Desc.: Euro Interbank Offered Rate
---
Euribor is the interest rate at which euro-area banks offer to lend unsecured(see: [[secure vs. unsecured]]) funds to other banks in the interbank market.
i.e. Euribor = 欧元区银行“彼此借钱”时用的基准利率
非常贴近 ECB 的政策利率

# Example

![[Screenshot 2025-12-30 at 20.24.40.png]]

**==三条“利率线”各自代表什么？==**
*   🟢 Euribor（绿色）
    *   银行之间短期拆借利率
    *   非常贴近 ECB 的政策利率

*   🔴 企业贷款利率（CCR）
    *   企业向银行借钱要付的利率
    *   一定 高于 Euribor
    *   差的那一截 = 风险 + 银行利润 + 资本成本

*   🔵 企业存款利率（DR）
    *   企业把钱存银行拿到的利率
    *   通常 低于 Euribor
    *   因为银行不需要用很高利率“抢存款”

**==柱状图（premium）才是这张图的“灵魂”==**
1.  粉色柱：贷款利差（CCR − Euribor）
    *   表示： 银行在基准利率之上，对企业贷款加了多少“价”
    *   你可以理解为：
        *   企业信用风险
        *   经济不确定性
        *   银行资本压力
        *   金融危机恐慌
    *   📌 关键观察：
        *   2008–2009：金融危机 → 利差明显拉大
        *   2012：欧债危机 → 利差再次偏高
        *   2022–2023：快速加息 → 利差再度扩大
    *   👉 含义： 即使央行降息，如果银行觉得“风险高”，企业实际借钱还是会很贵

2.  蓝色柱：存款利差（DR − Euribor）
    *   通常是 负的，说明： 企业存款利率 < Euribor
    *   📌 关键观察：
        *   负利率时代（2015–2021）：
            *   Euribor < 0
            *   企业存款利率甚至更低
            *   企业“存钱=被罚钱”
        *   2022 之后：
            *   Euribor 快速上升
            *   存款利率上升 明显更慢
            *   蓝色柱仍然很负
    *   👉 这说明：
        *   银行加息时：
            *   对贷款（CCR）传导很快
            *   对存款（DR）传导很慢