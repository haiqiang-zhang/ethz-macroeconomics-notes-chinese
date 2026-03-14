---
Types:
  - 📔 Lecture
Finished: false
base: "[[ETH MacroEco Knowledge.base]]"
---
🎦 [Recording 1](https://video.ethz.ch/lectures/d-mtec/2025/autumn/363-0565-00L/v/H8bJCdqxihi?t=47m44s) [Recording 2](https://video.ethz.ch/lectures/d-mtec/2025/autumn/363-0565-00L/v/HMoYV5twsIZ?t=04m49s)
# Finance
**Finance** is the field of economics that studies how people make decisions regarding the ==allocation of resources over time([[inter-temporal trade]])== and the ==handling of risk==.
把它翻成大白话就是两件事：
1. 跨时间分配资源（allocation over time）
    你今天有 100 块钱，你可以：
    - 现在就花掉（消费）
    - 存起来/投资，让未来变成更多钱（延迟消费）
    金融体系的作用就是：让“今天愿意少花、想存钱的人”把钱更有效地转给“今天需要钱、想做投资的人”，从而让未来产出更高。
2. 处理风险（handling of risk）
    现实里未来不确定：公司可能赚也可能亏、借款人可能违约、利率可能变、房价可能跌……
    金融体系提供工具来：
    - 分散风险（比如买基金而不是押一只股票）
    - 转移风险（比如保险）
    - 定价风险（风险高→通常要求更高回报/利率）
# Finance System & Financial institutions
#review 
**The financial system** is made up of ***institutions*** that coordinate the actions of **savers** and **borrowers**

Financial institutions can be grouped into two different categories:
- ==**Financial markets**== are the institutions through which savers can **directly provide funds to borrowers**
    - Bond Markets
        - A **==bond==** is a certificate of [[indebtedness]] that specifies [[obligations]] of the borrower to the bond holder. The associated credit risk is the probability that the borrower will fail to pay some of the interest or principal 
        - **==Government bonds==** are often considered to be safe and therefore carry lower interest rates 
    - Stock Markets 
        - A **==stock==** represents a claim to partial ownership in a firm and is a claim to the rprofits that the firm makes 
        - The issuing of stocks by a firm to raise money is called [[equity financing|equity financing]] 
        - Compared to bonds, stocks offer both higher risk and potentially higher returns
- ==**Financial intermediaries**== are financial institutions through which savers can **indirectly provide funds to borrowers**
    - Banks 
        - … take deposits from people who save and use these to lend to those who want to borrow 
        - help create a medium of exchange by providing non-cash payment methods 
    - Mutual Funds or Investment Funds 
        - These funds are vehicles that allows the public to invest in a portfolio of various types of shares and/or bonds. 
        - These funds sell shares to the public and use the [[proceeds]] to buy such portfolios. They allow people with small amounts of money to easily [[diversify]]
    - Other Financial Institutions 
        - Credit unions, Pension funds, Insurance companies, Loan sharks

## The Great Financial Crisis of 2007-2009
### Structured Finance (Introduce to the basic concept to understand the crisis)
#### Securitization
Securitization involves packaging up loans (e.g. residential mortgages, car loans, credit card debt obligations) and selling them (typically via a [[Special Purpose Vehicle]]) to investors.
#### [[Collateralized Debt Obligations (CDOs)]]
These financial products are referred to as [[Collateralized Debt Obligations (CDOs)]].
- CDO = 一池“资产支持证券（ABS）”
- They are pools of asset-backed securities which are dependent on..
    - .. the value of the assets that back them up.
    - .. the stream of income that flows from these assets (e.g. the interest paid on the mortgages).
#### Tranches + Credit Rating
The issued securities(同一池贷款) are often split into ==***tranches***== and ***rated according to their risk***. 
- Lower-risk tranches attract lower interest rates.
- Credit rating agencies analyse the packages of debt and give them a ==credit rating== (AAA, AA, BBB ...).
![[Screenshot 2025-12-29 at 00.31.32.png]]
#### CDO Repackaged
![[Screenshot 2025-12-29 at 00.36.21.png]]This section illustrates how risk was repeatedly repackaged and obscured, creating the illusion of safety while amplifying systemic risk.
# Saving and Investment
## The Meaning of Saving and Investment
### National saving ^national-saving

> [!info] Recall [[2 National Accounting#^expenditure-approach-GDP]]

National saving is total income that remains after paying for consumption and government purchases
$$
S = Y - C - G = \underbrace{(Y-T-C)}_{\text{Private Saving}} + \underbrace{(T-G)}_{\text{Public Saving}}
$$
- Where $T$ stands for taxes
### Private Saving
The part of income that households have left after paying taxes and paying for their consumption.

$$
\text{Private saving} = (Y - T - C)
$$

### Public Saving
Public saving is the amount of tax revenue that the government has left after paying for its spending.

$$
\text{Public saving} = (T - G)
$$

- Surplus and deficit:
    - If $T > G$, the government runs a ==budget surplus== because it receives more money than it spends.
    - If $G > T$, the government runs a ==budget deficit== because it spends more than it receives.
- The accumulation of past budget deficits is called ==the government debt==.

> [!note]- Government Budget Balances ($T-G$) and Gross Government Debt in selected countries
> ![[Screenshot 2025-12-29 at 01.40.33.png]]

# The Market for Loanable Funds in close market 

^close-market-for-loanable-funds
[[2025Lecture05.pdf#page=43&selection=0,0,0,29|2025Lecture05, page 43]]

> [!warning] The price for a loanable fund is the [[real interest rate]]


- We will assume for simplicity that the economy has only one financial market 
- **Supply and Demand**: This market for loanable funds is the market in which those who want to save *supply* funds and those who want to borrow to invest *demand* funds
- **Loanable funds** refers to all income that people have chosen to save and lend out ($S$), rather than use for their own consumption
    也就是：
    - Loanable Funds=Saving $S$
    - 你赚了钱：
        - 花掉 → Consumption $C$
        - 不花 → Saving $S$
    - 这些储蓄被：
        - Put money in a bank
        - Buy bonds
        - Buy mutual funds
    - 👉 本质上：借给别人用
- ==The price for a loanable fund is the ***[[real interest rate]]***==
    - It reflects the amount borrowers pay for loans and lenders receive on their saving
- The equilibrium of the supply ($S$) and demand ($I$) for loanable funds determines the real interest rate
![[market-for-loanable-funds.png | 400]]
## Government Policies to affect Savings and Investment
1. Taxes and saving
    - Taxes on interest income substantially reduce the future payoff from current saving and, as a result, reduce the incentive to save 
    - A tax decrease increases the incentive for households to save at any given interest rate
        - The supply of loanable funds curve shifts right 
        - The equilibrium interest rate decreases 
        - The equilibrium quantity of loanable funds increases 
    ![[loanable-fund-taxes-saving.png | 450]]
    
2. Taxes and investment 
    - An investment tax credit 投资税收优惠
        - increases the incentive to borrow 
        - increases the demand for loanable funds 
        - shifts the demand curve to the right 
        - results in a higher interest rate and a greater quantity saved
    ![[loanable-fun-taxes-investment.png | 450]]
3. Government budget deficits ^government-budget-deficits-affect-loanable-funds-market
    - Government borrowing to finance its budget deficit reduces the supply of loanable funds available to finance investment by households and firms
    - A budget deficit decreases the supply of loanable funds
        - Shifts the supply curve to the left 
        - 在封闭经济里：(see [[#^national-saving]])
$$
S = Y - C - G = \underbrace{(Y-T-C)}_{\text{Private Saving}} + \underbrace{(T-G)}_{\text{Public Saving}}
$$
            - if government budget deficits increasing：($G$) 上升或 ($T$) 下降
                - → ($T-G$) 变小（甚至为负）
                - → national saving $S$ 下降
            - 而在The Market for Loanable Funds里：Supply = Saving ($S$)
            - So：✅ Government budget deficits increasing → national saving($S$) ↓ → Shifts the supply curve to the left 
    - Increases the equilibrium interest rate and reduces the equilibrium quantity of loanable funds 
    - The associated fall in investment is referred to as ==crowding out== 
        - The deficit borrowing crowds out private borrowers who are trying to finance investments
        
    ![[Screenshot 2025-12-30 at 00.21.26.png | 450]]
