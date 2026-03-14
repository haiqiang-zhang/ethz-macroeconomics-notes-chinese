---
Types:
  - 📔 Lecture
Finished: false
base: "[[ETH MacroEco Knowledge.base]]"
---
[[2025Lecture06.pdf]]
# Definition of Money
- ***Bartering*** is the exchange of one good for another.
    - Bartering requires a double coincidence of wants.
- ***Money*** is the set of assets in an economy that people regularly use to buy goods and services from other people.

## The Three Functions of Money
1. Medium of Exchange 
    - A medium of exchange is an item that buyers give to sellers when they want to purchase goods and services.
    - A medium of exchange is anything that is readily acceptable as payment.
2. Unit of Account
    - A unit of account is the yardstick people use to post prices and record debts.
3. Store of Value 
    - A store of value is an item that people can use to transfer purchasing power from the present to the future.
## The Kinds of Money
- Commodity money takes the form of a commodity with intrinsic value.
    - Examples: Gold, silver, cigarettes. 
- Fiat money is used as money because of government decree. 
    - It does not have intrinsic value. 
    - 法定货币之所以是钱，是因为政府规定它是钱（legal tender / government decree），而不是因为它本身有用途。
    - Examples: Coins, currency, check deposit
## Money supply
![[money-suply-definition.png]]
As we move from *M0* to *M3*, the definition of money becomes broader, but liquidity decreases.
- ==Bank reserves== only belong to Monetary Base, neither M0 nor M1-M3.

- A ***repurchase agreement*** is an agreement between the central bank and a commercial bank whereby a bond or other non-monetary asset is sold by one to the other with an agreement to reverse the transaction a short time later.
    - If the central bank has bought some assets from a commercial bank with an agreement that the commercial bank will buy them back at a later date, then this would be called a *repo*(i.e. repurchase agreement).


# Banks
- Commercial banks may borrow from and lend to each other and the interest rate at which they do this is called *Interbank Rate* (or *Interbank Lending Rate*)
## The Money Multiplier
![[Screenshot 2025-12-30 at 22.08.15.png|400]]

The money multiplier is the reciprocal of the reserve ratio:
$$\text{Money Multiplier} = \frac{1}{R}$$
> [!info] Example
> Original deposit = $100.00
> - 1st  Natl. Lending =    $90.00 (= 0.9 x $100.00) 
> - 2nd Natl. Lending =   $81.00  (= 0.9 x $90.00) 
> - 3rd Natl. Lending =    $72.90  (= 0.9 x $81.00) 
> - … and on until there are just pennies left to lend! 
> 
> So:
> - Total money created by this $100.00 deposit in the banking sector is $900.00 
>     - ($= 1/0.10 \times \$100.00 - \$100.00$) 
>     - Total money in the system is $1’000.00


# Central Bank (CB)
## Money Market
- money market the market in which the commercial banks lend money to one another on a short-term basis
    - If there is a general shortage of liquidity in the money market (because the banks together have done a lot of lending), then the short-term interest rate at which they lend to one another will begin to rise
    - while it will begin to fall if there is excess liquidity among banks.
- The central bank closely monitors the money market and may intervene in it to affect the supply of liquidity to banks, which in turn affects their lending and hence the money supply.
## The CB's Tools of Monetary Control - Conventional Policy Instruments
- ==Reserve requirements== are regulations on the minimum amount of reserves banks must hold against deposits
    - Increasing (decreasing) the reserve requirement decreases (increases) the money supply.
    - **Problems**
        - The Central Bank’s control of the money supply is not precise.
        - The Central Bank must wrestle with two problems that arise due to fractional-reserve banking.
            1. The Central Bank does not control the amount of money that households choose to hold as deposits in banks. 
            2. The Central Bank does not control the amount of money that bankers choose to lend and/or the private sector chooses to borrow
- ==Open-Market Operations== (in the ECB case using the Main Refinancing Rate as “price”)
    - The CB conducts open-market operations when it buys government bonds from or sells government bonds to the **public**: 
        - When the CB buys (sells) government bonds, the money supply increases (decreases)
- ==Main refinancing operations rate==
    - The main refinancing operations rate is the interest rate banks pay when they borrow money from the ECB for one week.
    - The difference between the price at which a commercial bank sells an asset to the central bank and the price it agrees to buy it back can be expressed as an annualized percentage of the selling price, and this is called the refinancing rate.
- The ==Discount Rate== (ECB terminology: the ==Marginal Lending Rate==) 
    - The discount rate is the interest rate the CB charges banks for loans in US (CB is Federal reserve)
    - The marginal lending facility rate is the interest rate banks pay when they borrow from the ECB overnight.
    - **Increasing (decreasing) the discount rate decreases (increases) the money supply** 

| Feature      | Main Refinancing (MRO)                                   | Marginal Lending Rate                                         | Discount Rate                                                 |
| ------------ | -------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- |
| Central Bank | 🇪🇺 ECB (Europe)                                        | 🇪🇺 ECB (Europe)                                             | 🇺🇸 Fed (USA)                                                |
| Duration     | 1 Week (Weekly)                                          | Overnight (1 Day)                                             | Overnight (Short-term)                                        |
| Function     | Primary Policy Tool<br><br>  <br><br>(Regular Liquidity) | Ceiling / Emergency<br><br>  <br><br>(Liquidity Safety Valve) | Ceiling / Emergency<br><br>  <br><br>(Liquidity Safety Valve) |
| Cost         | Baseline Rate                                            | Higher (Penalty Rate)                                         | Higher (Penalty Rate)                                         |
| Access       | Via Auction                                              | On Demand (Standing Facility)                                 | On Demand (Discount Window)                                   |


- The ==Deposit Rate== is the interest rate the CB pays commercial banks for (some of the) deposits they hold at the CB
    - **Increasing (decreasing) the deposit rate decreases (increases) the money supply**
        - Because a higher deposit rate (interest on reserves at the central bank) raises the return banks get from holding reserves, so it reduces their incentive to lend those funds out. Less lending → fewer deposit-creation rounds in the banking system → a smaller money supply.

![[Screenshot 2025-12-30 at 23.38.59.png]]

## Effective Lower Bound, ELB
ELB（有效下限）：指央行的名义政策利率（nominal policy rate）在现实中能降到的“最低附近”，再往下降息的边际效果会变得非常弱，或者会引发明显副作用（金融稳定、银行盈利、现金替代等），所以央行“实际上”很难继续降。
- 不是数学上不能更低，而是“再低就不划算/不好用/代价太大”，所以政策上相当于到头了。
- The CB is hard to reduce nominal interest rates below zero (or slightly below zero) because people would just hold cash instead of keeping money in the bank.

![[effective-lower-bound.png]]
## Quantitative Easing (QE) - Unconventional Policy Instrument
Having exhausted the use of lowering the price of money (i.e. lowering the interest rate) during the financial crisis of 2007–09, central banks used ***quantitative easing*** to try and support the economy
- The central bank injects money into the system 
    - It buys assets (like government and corporate bonds) from private sector institutions such as banks, pension and insurance companies 
    - So the reserves of the private sector institutions increase 
        ![[Screenshot 2025-12-31 at 01.32.58.png | 450]]
    - In theory these institutions should have more money to lend
### Money supply in the euro area during the Great Financial Crisis
![[Screenshot 2025-12-31 at 01.17.44.png | right figure: zoom in the crisis]]
- CB move money from M3 to M1: moved out of these financial products, and moved into cash (simplify)


# Quantity Theory of Money

> [!warning] Long-run Theory

- **The *Quantity Theory of Money* explaining how the price level is determined and why it might change over time**
- The _Quantity theory of money_ states that the general price level of goods and services is directly proportional to the amount of money in circulation (=money supply).
- The quantity of money available in the economy determines the value of money
- The primary cause of inflation is the growth in the quantity of money
## The Classical Dichotomy and Monetary Neutrality
- In the long run, real economic variables do not change with changes in the money supply. 在长期中，货币供给的变化只影响名义变量（nominal variables），不影响真实变量（real variables）。
- Monetary Neutrality: 
    - The irrelevance of monetary changes for real variables is called monetary neutrality
    
    **钱变多了，只会让价格整体变贵，不会真的让社会“更富”**。
    - 多印钱 → 标价变高, 但：
        - 真实产出（real GDP）不变
        - 就业不变
        - 真实工资不变
        
    这就叫 **货币是“中性的”**。
## Velocity of money
- nominal value of output ($P \times Y$) :
    - real output $Y$ = units of goods and services
    - Price level $P$ = money / unit of output
$$V = \frac{P \times Y}{M}$$
## Quantity equation
$$M \times V = P \times Y$$
- M is quantity of money (= money supply)

> [!summary] The Quantity Theory of Money
> - The velocity of money ($V$) is relatively stable over time 
> - When money ($M$) changes, it causes proportionate changes in the nominal value of output ($P \times Y$) 
> - Because money is (in the long-run) neutral ($Y$ is determined on goods and service markets), money ($M$) does not affect output ($Y$)

# Inflation

> [!warning] The quantity theory of money is used to explain the **long-run** determinants of the price level and the inflation rate

When the overall price level rises, the value of money falls
Inflation is an economy-wide phenomenon that concerns the value of the economy’s medium of exchange
## Money Supply, Money Demand, and Monetary Equilibrium
- ==Money demand== has several determinants, including interest rates and the average level of prices in the economy
    - People hold money because it is the medium of exchange
    - The amount of money people choose to hold depends on the prices of goods and services
    - Therefore the lower the value of money the higher the demand
- In the long run, the overall level of prices adjusts to the level at which the demand for money equals the supply
- why the demand for money is downward sloping?
    - The demand for money is downward-sloping, because a lower real interest rate lowers the cost of holding money and, thus, increases the quantity of money demanded.

![[monetary-equilibrium.png|450]]
### An Increase in the Money Supply
![[Screenshot 2025-12-31 at 02.06.21.png|450]]

## The Inflation Tax
- When the government raises revenue by printing money, it is said to levy an inflation tax
- An ==inflation tax== is like a tax on everyone who holds money
- The inflation ends when the government institutes fiscal reforms such as cuts in government spending
## The Fisher Effect
The Fisher effect refers to a one-to-one adjustment of the nominal interest rate to the inflation rate

nominal interest rate = real interest rate + inflation rate
$$i = r + \pi$$
## The Costs of Inflation
### Inflation and real wage (❌ Common misperception: inflation reduces real wages)
Real income/Real wage (real purchasing power):
$$\text{real income} = \frac{\text{nominal income}}{P}$$
Inflation does not in itself reduce people’s real purchasing power. As prices rise, so do incomes


> [!error] Common misperception: inflation reduces real wages
> - This is true only in the short run, when nominal wages are fixed by contracts
> - In the long run, real wages are determined by labour supply and the marginal product of labour, not the price level or the inflation rate

![[Wage-development-in-Switzerland–a-short-run-perspective.png | Wage development in Switzerland – a short-run perspective|500]]

### ✅ Shoeleather Costs
- Shoeleather costs are the resources wasted when inflation encourages people to reduce their money holdings
- Inflation reduces the real value of money, so people have an incentive to minimize their cash holdings
- Less cash requires more frequent trips to the bank to withdraw money from interest-bearing accounts
- The actual cost of reducing your money holdings is the time and convenience you must sacrifice to keep less money on hand
- Also, extra trips to the bank take time away from productive activities
### ✅ Menu costs 
- Menu costs are the costs of adjusting prices
- During inflationary times, it is necessary to update price lists and other posted prices
- This is a resource-consuming process that takes away from other productive activities
### ✅ Relative-Price Variability and the Misallocation of Resources
- Inflation distorts relative prices
- If prices of some goods are “sticky” (e.g. because of menu costs) relative to other goods, then inflation is creating changes in relative prices that lead to decisions of market participants that are economically inefficient in the sense that it deviates from the optimal allocation of resources
    - 在现实里，很多价格不能随时调整（菜单成本、合同、惯例、监管等）。
    - 当总体价格水平在涨时：
        - 有些商品价格已经跟着涨了
        - 有些商品价格还没来得及涨（暂时“偏便宜”）
    - 消费者和企业看到的相对价格就“失真”，做出不够有效率的选择：买了“看起来更便宜但其实只是没来得及涨价”的商品
- Hence, markets are less able to allocate resources to their best use

### ✅ Inflation-Induced Tax Distortion
- Inflation exaggerates the size of *capital gains* and increases the tax burden on this type of income
- With progressive taxation, capital gains are taxed more heavily
- The income tax treats the nominal interest earned on savings as income, even though part of the nominal interest rate merely compensates for inflation
- The after-tax real interest rate falls, making saving less attractive
![[Screenshot 2026-01-01 at 18.37.53.png]]
### ✅ Confusion and inconvenience
- When the Central Bank increases the money supply and creates inflation, it erodes the real value of the unit of account
- Inflation causes dollars at different times to have different real values
- Therefore, with rising prices, it is more difficult to compare real revenues, costs, and profits over time
### ✅ A Special Cost of Unexpected Inflation: Arbitrary redistribution of wealth
- Unexpected inflation redistributes wealth among the population in a way that has nothing to do with either merit or need
- These redistributions occur because many loans in the economy are specified in terms of the unit of account—money
如果通胀突然比预期高：
- 借款人用“更不值钱的货币”去还债 → **borrower受益**
- 放贷人收到的还款购买力变低 → **lender受损**


## Short-run: Two causes of rising and falling inflation
Until now, we all talked about the long-run inflation. Now we talk about the short-run


[[2025Lecture13.pdf#page=23&selection=0,0,0,42|2025Lecture13, page 23]]

- Demand-pull inflation:
    - Inflation resulting from *demand shocks*: Positive shocks to aggregate demand cause unemployment to fall below its natural rate, which “pulls” the inflation rate up
- Cost-push inflation:
    - inflation resulting from *supply shocks*: Adverse supply shocks typically raise production costs and induce firms to raise prices, “pushing” inflation up
# Deflation 
> Deflation where the price level actually falls

> [!danger] Deflation can be as damaging as inflation

