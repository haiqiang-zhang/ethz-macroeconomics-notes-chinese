---
Types:
  - 📔 Lecture
Finished: false
base: "[[ETH MacroEco Knowledge.base]]"
---
> A country’s standard of living depends on its ability to produce goods and services
# How Productivity is Determined
- **[[Physical capital]] per worker**: Physical capital is a produced [[Factors of Production]]
    * It is an input into the production process that in the past was an output from that process
- **Human capital per worker**: is the economist’s term for the knowledge and skills that workers acquire through education, training, and experience 
    * Like physical capital, human capital raises a nation’s ability to produce goods and services
    * [[Factors of Production#Labour vs. Human Capital]]
- **Natural resources**: are inputs used in production that are provided by nature
    * Renewable resources include trees and forests 
    * Nonrenewable resources include petroleum and coal 
> [!Warning]
> **Natural resources** can be important but are not necessary for an economy to be highly productive
- **Technological knowledge**: includes society’s understanding of the best ways to produce
    Technical Knowledge ≠ Human Capital
    - Technical Knowledge:
        - Formulas
        - Processes
        - Management Methods
        - Production Flows
    - Human Capital:
        - The educational and training resources spent on transferring this knowledge to workers.

# Production Function
- $Y$ = quantity of output ^output
- $A$ = available production technology ^production-technology
- $L$ = quantity of labour
- $K$ = quantity of physical capital
- $H$ = quantity of human capital
- $N$ = quantity of natural resources
- $F()$ is a function that shows how the inputs are combined
$$
Y = A F(L, K, H, N)
$$
- **constant returns to scale**: A production function has constant returns to scale if, for any positive number $x$, 
    $$xY = A F(xL, xK, xH, xN)$$
    - A doubling of all inputs causes the amount of output to double as well
    - This implies that capital and labour are each subject to ***diminishing marginal returns***
        - diminishing marginal returns: 如果把所有生产投入（资本和劳动力）都翻倍，那么总产出也会正好翻倍。但如果只增加其中一种投入（比如只增加机器而不增加工人），那么每新增一台机器带来的产量增长会越来越少。
            - More capital, but holding labor fixed → smaller additional output
            - More labor, but holding capital fixed → smaller additional output
# Saving and Investment

> [!NOTE] Terminology
> - $S$ = Saving
> - $I$ = Investment
>     - Note: “Investment” means the creation of new productive assets by firms and households, e.g. ==building a **new** factory or a **new** house==
>     - Buying an old house or a share in an existing company is only a financial transaction
> - $D$ = Depreciation
>     - Firms invest in order to raise future productivity, or to replace depreciated capital 
> - $s$ = **Saving rate**: A constant fraction of income is saved and therefore invested: $S = sY$ ^saving-rate

- For the economy as a whole, **saving must be equal to investment**: $(Y - C) \equiv S = I$
# Solow growth model

> [!summary] Summary
> - Long-run per capita growth is driven entirely by exogenous technological progress, at rate $g$. 长期人均增长率完全由外生技术进步决定，等于技术进步率 $g$。
> - Capital exhibits diminishing returns, so capital accumulation alone cannot sustain long-run per capita growth. The economy converges to a steady state in which per capita capital and output are constant. 资本存在递减报酬，因此单靠资本积累不能实现长期人均增长。经济会收敛到一个稳态（steady state），在稳态中人均资本和人均产出不再增长。
> - A higher saving (investment) rate raises the level of income, but does not affect the long-run growth rate. 提高储蓄率或投资率 **只能提高长期收入水平**，**不能提高长期增长率**。


- GDP in any country can be assumed to be an extension of a firm’s production function where the level of output is dependent on the [[Factors of Production]] employed. 
- <u>Assumptions</u>:
    - Two production factors: labour ($L$) and capital ($K$) (next to technology: $A$)
        - Output (GDP) = $Y = AF(K,L)$
        - ==Technology $A$ is ***exogenous***==
    - Constant returns to scale: $xY = AF(xK,xL)$, see [[#Production Function]]
    - A closed economy and no government ($G=0$ & $NX=0$)
        - Therefore, $Y = C + I + G + NX$ simplifies to $Y = C + I$
    - Capital depreciates with a constant rate: $D = \delta K$
* **Net investment**: The difference between total investment ($I$) and depreciation ($D$) is called net investment. i.e.
    $$\Delta K = I - D$$
* 投资率高的国家，往往拥有更高的人均收入水平（但不一定有更高的长期增长率）。
## Steady-state equilibrium
> The point at $D=I$  is called *steady-state equilibrium*.
> *Steady-state equilibrium* is the point in a growing economy where investment is the same as spending on depreciation and the [[capital-output ratio]] remains constant
> - $A$ is constant, see [[#^production-technology]]

- $K$ 在变，$s$ 不变: This model implies that at a given saving rate with positive net investment, the capital stock (and hence output) will grow until $D=I$. 
    ![[Screenshot 2025-12-16 at 22.54.50.png | 350]]
- saving rate ([[#^saving-rate]]) 增加 = $I$ 曲线整体上移: If the saving rate is increased, the capital stock and output grow further, again until $D=I$. 
    ![[Screenshot 2025-12-16 at 23.08.02.png | 350]]
- **Steady state consumption**: 
    $$
    C = Y(K) - D = Y(K) - I = Y(K) - S = Y(K) - sY = Y(K) - \delta K
    $$
    ![[Screenshot 2025-12-17 at 03.04.55.png | 350]]
- **An optimum saving rate**: 储蓄率该定多少，才能让steady-state consumption($C$)最大？
    - The optimum (Golden Rule) saving rate($s$) is defined as the saving rate that maximizes steady-state consumption($C$).
    
    ![[Screenshot 2025-12-17 at 03.06.46.png |350]]
    
## Allow for technological progress
If we allow for technological progress, the growth rate in the steady state doesn’t have to be zero
- Increasing $A$ -> shift curve upward  $Y_1 \rightarrow Y_2$ 
    ![[Screenshot 2025-12-17 at 03.26.45.png | 400]]
- Because saving rate($s$) is the same, so shift curve upward  $I_1 \rightarrow I_2$
    ![[Screenshot 2025-12-17 at 03.27.32.png | 400]]
- Move ***Steady-state*** from $h$ to $n$

    ![[Screenshot 2025-12-17 at 03.21.31.png | 400]]
## Increasing saving rate($s$)
![[Screenshot 2025-12-17 at 03.38.01.png | 400]]

Noting that the Y-axis(Output) is [[#^output]]
# Endogenous Growth Theory

> [!summary] Summary
> 反驳 Solow Model

- Production function:  $Y = AK$
    - $A$ is still exogenous & constant
- Equation of motion:
$$
\Delta K = I - D = sY - \delta K
$$
$$
\frac{\Delta K}{K} = sA - \delta
$$

    - So, if $sA > \delta$,  then income will grow forever, and investment is the “engine of growth”
    - the permanent growth rate depends on $s$ 
        - in the Solow model, it does not

The Solow model:

![[solow.png | 400]]

The Endogenous Growth model:

![[endogenous.png | 400]]

| 关键点            | Solow          | AK                    |
| -------------- | -------------- | --------------------- |
| 生产函数           | 凹：递减报酬         | 线性：无递减报酬              |
| 是否有稳态（人均/有效劳动） | 有              | 没有（除非$sA=\delta$）     |
| 长期人均增长率        | $g$（外生技术）      | $sA-\delta$（由储蓄/投资决定） |
| 提高 $s$         | 提高水平，增长率只是暂时更快 | 永久提高增长率               |
