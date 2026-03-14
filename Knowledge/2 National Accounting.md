---
Types:
  - 📔 Lecture
base: "[[ETH MacroEco Knowledge.base]]"
Finished: false
---
🎞 [[2025Lecture02.pdf]]
# GDP: Gross Domestic Product
* Gross domestic product (GDP) is a measure of the income and [[expenditures]] of an economy.
* Because for the total economy income equals expenditure, we can calculate GDP by adding up total expenditure in the economy, or by adding up total income in the economy.
* GDP is the total market value <u>of all</u>(1) <u>final</u>(2) <u>goods and services</u>(3) produced <u>within a country</u>(4) <u>in a given period of time</u>(5).
	1. <u>of all final goods and services</u>: Includes all items produced in the economy and legally sold in markets
		* What Is Not Counted in GDP?
			* GDP excludes most items that are produced and consumed at home and that never enter the marketplace.
			* It often excludes items produced and sold illicitly, such as illegal drugs.
	2. <u>final</u>: It records only the value of final goods and services, not intermediate goods (the value is counted only once).
	3. <u>Goods and Services</u>: It includes both
		* **tangible** goods (food, clothing, cars) and 
		* **intangible** services (haircuts, housecleaning, doctor visits).
	4. <u>within a country</u>: It measures the value of production within the geographic confines [[confine]] of a country.
	5. <u>In a Given Period of Time</u>: It measures the value of production that takes place within a specific interval of time, usually a year or a quarter (three months). (i.e. **produced this period**)
## How to measure GDP? Three main approaches
![[Circular-Flow-Diagram.png | 500]]
### Expenditure Approach (demand side) ^expenditure-approach-GDP
- ==GDP== ($Y$) **Normally $Y$ means real GPD = real output = real income**
- ==Consumption== ($C$) 
    The spending by **households** on goods and services (**without the purchases of new housing**)
    - More Specifically: Consumption ($C$) is household spending on final goods and services produced in the current period, including durable goods (e.g., cars), nondurable goods (e.g., food), and services (e.g., rent, healthcare), but excluding purchases of new housing (which are counted as investment, $I$ [[#^new-house]]).
    - 只统计当期生产的最终商品与服务的支出 (i.e. **produced this period**)
        - The *used* (second-hand) good itself is generally not counted in C), because it was **produced in an earlier period** and the sale is mainly just a transfer of ownership， i.e. without second-hand housing, car transaction .....
    - 国内人消费完全在国外生产的设备也算$C$，但是请注意他最终会被Import 减掉，所以不影响GDP，看下面的公式([[#^gdp-expenditure-formula]])
* ==Investment== ($I$)
    The spending on capital equipment, inventories and structures (**including new housing**)
    - strictly refers to **private sector** spending
    Example:
    - **Fixed nonresidential expenditures**: Fixed nonresidential expenditures are firms’ purchases of plant, equipment, and structures used in production.
    - **Fixed residential expenditures**: Fixed residential expenditures are spending on new residential housing that adds to the economy’s capital stock and is therefore counted as investment (I), not consumption. ^new-house
    - Change in inventories
* ==Government Purchases== ($G$)
    The spending on goods and services by local, state and federal governments (without transfer payments [[transfer payments]] because they are not made in exchange for goods or services)
* ==Net Exports== ($NX = X-M$)
    Exports minus imports


$$\begin{align}
Y &= C + I + G + NX \\
&= C_{\text{dom}} + C_{\text{for}}
+ I_{\text{dom}} + I_{\text{for}}
+ G_{\text{dom}} + G_{\text{for}}
+ X - (C_{\text{for}} + I_{\text{for}} + G_{\text{for}}) \\
&= C_{\text{dom}} + I_{\text{dom}} + G_{\text{dom}} + X
\end{align} 
$$
* $C_{\text{for}}$ = 居民消费的**外国**产品
* $I_{\text{for}}$​ = 国内投资中买**外国**生产的
* $G_{\text{for}}$ = 本国政府买**外国**生产的
 ^gdp-expenditure-formula

> [!question] Sample Question
> - T or F: A new car produced in 2004, but first sold in 2005, should be counted in 2005 GDP because that is when it was first sold as a final good. <u>(❌ F: Since the car was produced in **2004**, it contributes to the GDP of **2004**, not 2005.)</u>
> - T or F: When the city council of Southampton purchases a new school building, the investment component of GDP increases.  <u>(❌ F: count as $G$)</u>
> - How is your purchase of a €40,000 BMW automobile that was produced entirely in Germany recorded in the UK GDP accounts? <u>(Answer: a)</u>
>     - a. Consumption increases by €40,000 and net exports decreases by €40,000.
>     - b. Net exports increases by €40,000.
>     - c. There is no impact because this transaction does not involve domestic production.
>     - d. Investment increases by €40,000 and net exports increases by €40,000.
>     - e. Net exports decreases by €40,000.

### Production Approach (supply side)
$$\text{GDP} = \sum(\text{Gross Output} - \text{Intermediates})$$
### Income Approach (income side)
$$\text{GDP} = \text{Wages}+\text{Rents}+\text{Interest}+\text{Profits}$$
* <u>Rents</u> : 地租 / 租金, i.e. Land得到的收入
* <u>Interest</u>: Capital 得到的收入
* <u>Profits</u>: 企业家（Entrepreneurship）得到的收入, i.e. 企业剩下的收益 after paying wages, rents, interest

Belong to national income:
- Rental income 
- Net interest 
- Taxes, foreign income, and miscellaneous adjustments
- Corporate profits
- Proprietors' income 〔企业等的〕业主，老板
- Compensation of employees
- Product subsidies / production subsidies

**Do not include:**
- any second-hand transaction(income)
- Transfer payments
    - Unemployment benefits
    - Student grants / Student financial aid
    - Pensions
    - Cash transfers to low-income households

[[National income]]

## REAL vs. NOMINAL GDP
* **Nominal GDP** values the production of goods and services at current prices.
* **Real GDP** values the production of goods and services at constant prices.
    ![[real_nominal_gdp.png]]
### The GDP Deflator
$$
\text{GDP Deflator} = \frac{\text{Nominal GDP}}{\text{Real GDP}} \times 100
$$


> [!warning] Various practical difficulties in measuring GDP
> * Under-reporting in order to avoid tax 
> * Changes in the goods and services produced over time render the use of base years problematic. --> Solved by [[2 National Accounting#Annual Chain Linking]]

## Annual Chain Linking
Instead of using one fixed base year (like “all prices measured in 2010 prices”),  
**chain linking** updates the base year _every single year_.
How it works:
1. Compute real growth using last year’s prices.
2. “Chain” these yearly growth rates together.
This avoids [[distortion]] caused by using outdated price structures.
# NDP: Net Domestic Product
$$\text{NDP} = \text{GDP} - \text{Depreciation}$$

Depreciation = Capital Consumption Allowance
# CPI: Consumer Price Index ^CPI
## How the CPI is Calculated
1. Fix the basket (**including import!**)
2. Find the prices
3. Compute the basket's cost
4. Choose a base year and compute the ***index***
    $$
    \text{Consumer price index in year } t = \frac{\text{Price of basket in year } t}{\text{Price of basket in base year}} \times 100
    $$
5. Compute the ***consumer price inflation rate***
    $$
    \text{Inflation rate in year 2}
    = \frac{\text{CPI in year 2} - \text{CPI in year 1}}
       {\text{CPI in year 1}} \times 100
    $$
    ![[cpi_example.png]]![[cpi_example_2.png]]
## CPI overstate the true cost of living
1. **Substitution bias**
    <u>CPI uses a fixed basket of goods.</u> It assumes consumers buy the same items every year, in the same quantities.
   > [!tip] But in real life… 
   > When prices change, consumers substitute:
   > * If beef becomes expensive, people buy more chicken.
   > * If apples get cheaper, people buy more apples instead of bananas.
   > 
   > **CPI does not update the basket**, so it incorrectly assumes people still buy the expensive item. 

   >[!warning] 
   >The CPI incorporates substitutions within a category of goods and services, but it fails to accommodate substitution between categories. [[Problem Set 1 - National Accounting]]

2. **Introduction of new goods**
3. **Unmeasured quality changes**
    Goods often change in quality, not just price.
    Examples:
    * A 2024 laptop is much better than a 2010 laptop, even if prices are similar.
    * A car with better safety features gives more value even at same price.
    The statistical office tries to adjust for quality, but measuring quality is extremely difficult.
## GDP Deflator vs. CPI
- **Only Domestic or not**: the *GDP deflator* reflects the prices of all goods and services produced domestically, whereas...
    …the *consumer price index* reflects the prices of all goods and services bought by consumers.
- **fixed basket or currently produced**: The *consumer price index* compares the price of a fixed basket of goods and services to the price of the basket in the base year (only every five years does the SFSO change the basket)...
    …whereas the *GDP deflator* compares the price of currently produced goods and services to the price of the same goods and services in the base year.

|                  | **CPI**      | **GDP deflator** |
| ---------------- | ------------ | ---------------- |
| What is measured | 消费者买什么       | 国内生产什么           |
| **是否包含进口？**      | ✔ 包含         | ✘ 不包含            |
| **篮子是否固定？**      | ✔ 是（固定）      | ✘ 否（会变）          |
| **出现差异的原因**      | 替代偏差、新品、质量变化 | 商品构成随生产变化而自动调整   |

> [!info]- Two measures of inflation in Switzerland
> ![[Screenshot 2025-12-07 at 04.43.02.png]]

The largest category of goods and services in the CPI is Housing
## PPI: Producer Price Index
which measures the cost of a basket of goods and services **bought by firms** rather than **consumers**. 
Because firms eventually [[pass on]] higher costs to consumers in the form of higher prices on products, the *producer price index* is believed to be **helpful in predicting changes in the CPI**.

## Convert the salary
- In 1947 MPs earned £1,000 
- Assume in 2020 that MPs earned £74,000 but prices have risen since 1947.
- CPI index in 1947 = 28.9 
- CPI index in 2020 = 1,018.6
$$
\begin{align}
\text{Salary}_{2020}
&= \text{Salary}_{1947} 
    \times \frac{\text{Price level in 2020}}{\text{Price level in 1947}} \\
&= £1{,}000 \times \frac{1{,}018.6}{28.9} \\
&= £35{,}246
\end{align}
$$
## [[Indexation]]
When some money amount is automatically corrected for inflation by law or contract, the amount is said to be indexed for inflation.

# Real and Nominal Interest Rates
- The nominal interest rate is the interest rate usually reported and not corrected for inflation. 
    - It is the interest rate that a bank pays.
- The real interest rate is the nominal interest rate that is corrected for the effects of inflation.
- Example 
    - You borrowed €1,000 for one year.
    - Nominal interest rate was 15%. 
    - During the year inflation was 10%.
    $$
    \begin{align}
        \text{Real interest rate} 
        &= \text{Nominal interest rate} - \text{Inflation} \\
        &= 15\% - 10\% = 5\%
        \end{align}
    $$
