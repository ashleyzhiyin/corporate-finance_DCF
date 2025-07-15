### Time value of Money
#### 判断标准
- 只有一次性 → 单笔公式
	- 10年后会一次性收到$50,000。
	- 只有第N期？→ 单笔。
- 多期等额现金流 → 年金公式
	- 我每年领$1,000，连续10年，问今天值多少钱。
	- 每年/每月/每期？→ 年金。 
### 现值-单笔未来现金：
$$ PV = FV / （1 + r )^n $$
- present / future value
### Annuity
An annuity is a finite stream of cash flows of identical magnitude and equal spacing
In time.
- 年金：每年领一次
- finite：
$$PV = \frac{CF* (1 - (1 + R)^-T)} {R}$$

- $(1 + R)^-T$ : Discount factor for a cash flow received in period T
- $1-(1 + R)^-T$: Cumulative discount factor for T periods of $1 each
- 除以R: 累加。


### Growing Annuity
Growing Annuity
A growing annuity is a finite stream of cash flows that grow at a constant rate and are evenly spaced through time.
- Income streams, savings strategies, and project revenue/expense streams.

$$PV = CF \times \frac{1 - \left( \frac{1 + R}{1 + g} \right)^{-T}}{R - g}$$

R: 贴现率 discount rate
r: 增长率 growth rate

### Perpetuity 永续
An perpetuity is an infinite stream of cashflows of identical magnitude and equal spacing in time
- infinite
- perpetuities, consol bonds
$$
PV of Perpetuity = \frac{CF}{R}
$$
**永续年金的意思：**
- 每年付同样的钱（CF）
- 一直付下去
- 这个无限现金流的现值（PV）就是你今天要付出的资金
### Growing Perpetuity 永续增长
A growing perpetuity is an infinite stream of cash flows that grow at a constant rate and that are evenly spaced through time
- Dividends streams
$$
PV of Perpetuity = \frac{CF}{R-g}
$$

Saving with Tax 存更多钱
After - tax Discount Rate:
（1） Rt = R * (1-t)
- 5% * (1 - 35%) = 3.25 %
（2）
$$
PV = CF* (1 - (1 + Rt)^-T) / Rt
$$



Assume that a bond makes 10 equal annual payments of $1,000 dollar, starting one year from today. The bond will make an additional payment of $100,000 at the end of the last year, year 10. (This security is sometimes referred to as a coupon bond.)

Annuity:
- PV = 1000 * (1-1.035^(-10))/0.035
- 8317
Present Value & Future
- PV = 100000 / (1.035)^10 = 70892
两者相加：
- 79209

If the discount rate is 3.5% percent per annum, what is the current price of the bond?

###
#### Inflation
- Lesson: Inflation won't affect the money we earned
- taxes affect $
- Inflation affects consumption. not $
- Earn nominal return but can't buy as much

 Real discount rate:
- 1 + RR = (1+R) / (1+pai). pai is expected inflation.
- approximation: RR = R - pai

## 利率：APR and EAR

APR（Annual Percentage Rate）

- 就是**名义年利率**。
- 简单理解：把利率按期数*年，不考虑复利compounding。
- 它告诉你：“每期利率是多少，一年有多少期。”
- 很多贷款（比如信用卡、房贷）只报APR。


**EAR（Effective Annual Rate）**

- 就是**有效年利率**。
- 它考虑了**复利效应**，反映“一年到底滚了多少利息”。
- 如果有分期复利， EAR总是比APR高。

使用时间：

当：
- 比较贷款产品（看成本），用**EAR**更公平。
- 银行对外宣传利率时，很多只说**APR**，显得数字低。
    
如果题目说：
- “每月复利”，要算真实年化，就要换算成**EAR**。
    
#### formula

$$
APR = r_{period} \times m
$$


从APR转换到EAR（考虑复利）：

如果每期利率 = APR / m：

$$
EAR = \left(1 + \frac{APR}{m}\right)^m - 1
$$

或者如果直接已知每期利率：

$$
EAR = \left(1 + r_{period}\right)^m - 1
$$


**假设：**
- APR = 12%
- 每月复利 m=12
    

**每月利率：**
$$
r_{period} = \frac{12\%}{12} = 1\%
$$

**EAR计算：**

$$
EAR = (1 + 0.01)^{12} - 1 = 1.1268 - 1 = 0.1268 = 12.68\%
$$

**12% APR**对应**12.68% EAR**。


-  APR：**名义利率**，不计复利。 not discount rate
- EAR：**有效利率**，复利全算上。  
-  **比较不同贷款/投资时，必须看EAR。**


Term Structure 利率期限结构
Term Structure of Interest Rates
- 如果你借钱1年，利率是3%。
- 借5年，利率是4%。
- 借10年，利率是5%。

Yield Curve 收益率曲线
- 横轴 = **到期时间（maturity）**  
- 纵轴 = **收益率（yield）**

正斜率（正常）
- 时间越长，利率越高
- 代表经济预期增长、通胀上升
倒挂（Inverted）
- 时间越长，利率反而越低
- 代表经济衰退预期
平坦（Flat）
- 长短期利率差不多
- 经济不确定

Term Structure / Yield Curve用于：
- 债券定价
- 利率互换
- 经济预测（衰退信号）
- 风险管理

#### 投资决策
Lesson: The NPV Decision Rule says accept all projects with a positive NPV and reject all projects with a negative NPV

NPV = PV(Benefits) - PV(Costs)
NPV > 0, accept; NPV < 0, reject.

从高到低
- net present value
- internal rate of return
- payback
- discounted payback
- Accounting rate of return
- profitability index






## Present Value 现值

单笔现金流现值公式：
设：
- \(FV\) = 未来价值
- \(r\) = 折现率（利率）
- \(n\) = 期数

$$
PV = \frac{FV}{(1 + r)^n}
$$


单笔现金流未来价值公式：

$$
FV = PV \times (1 + r)^n
$$


## Annuity 年金
#### Present Value of Annuity
已经借了一笔钱，现在开始还，每期还多少。


$$
PV_{\text{annuity}} = C \times \frac{1 - \frac{1}{(1 + r)^n}}{r}
$$
你借了400000，你每个月还多少。PV = 400000
求C

#### Future Value of an Annuity
每期存款，最终有多少钱

$$
FV_{\text{annuity}} = C \times \frac{(1 + r)^n - 1}{r}
$$
最终有FV， 你现在应该存C


## **Yield to Maturity (YTM) 公式：**

设：
- \(P\) = 当前价格（Present Price）
- \(C\) = 每期付息（Coupon Payment）
- \(F\) = 面值（Face Value / Par Value）
- \(N\) = 剩余期数（Number of Periods）
- \(y\) = YTM

**公式：**

$$
P = \sum_{t=1}^{N} \frac{C}{(1 + y)^t} + \frac{F}{(1 + y)^N}
$$

要求的就是y。

Net Operating Profit After Taxes (NOPAT)
NOPAT=EBIT×(1−Tax Rate)

 ## Unlevered Free Cash Flow (UFCF)

**公式：**

$$
\text{Unlevered Free Cash Flow} = EBIT \times (1 - \text{Tax Rate}) + \text{Depreciation \& Amortization} - \text{Capital Expenditures} - \Delta \text{NWC}
$$

unlevered
- 不减去利息支出
- 不加上税盾效应
- 不考虑债务本金偿还

NWC: Net Working Capital

重点：减去巨大的资本支出和营运资本增加

FCF= (Revenue - Costs-Depreciation) x (1-tc) + Depreciation - Capital Expenditures Change in Net Working Capital
- Costs = Cost Margin x Revenue
- Net Working Capital = Cash +Inventory+AR-AP
	- Account receivable
	- Account payable


##  Net Present Value (NPV) 公式

**定义：**
项目未来现金流的现值总和，减去初始投资。

$$

NPV = \sum_{t=0}^{n} \frac{FCF_t}{(1 + r)^t}
$$

**变量说明：**
- \(FCF_t\)：第 t 期的自由现金流
- \(r\)：折现率
- \(n\)：项目周期（期数）

IRRR (Internal Rate of Return)
- 使得NPV = 0的折现率


$$
0 = \sum_{t=0}^{n} \frac{FCF_t}{(1 + IRR)^t}
$$

**变量说明：**
- \(FCF_t\)：第 t 期的自由现金流
- \(IRR\)：内部报酬率
- \(n\)：期数

## WACC（加权平均资本成本）

**定义：**
公司从所有资金来源（债务和股权）筹集资金所需支付的平均回报率。

**公式：**

$$
WACC = \frac{E}{D + E} \times r_e \quad + \quad \frac{D}{D + E} \times r_d \times (1 - T)
$$

**变量说明：**
- \(E\)：股权价值（Equity）
- \(D\)：债务价值（Debt）
- \(r_e\)：股权资本成本（Cost of Equity）
- \(r_d\)：债务资本成本（Cost of Debt）
- \(T\)：税率（Tax Rate）


#  **DCF 五步法**
1.预测FCF 
2.定折现率
3.算终价值  
4.折现金流
5.求和估值

 ① 预测未来自由现金流 (FCF)
$$
\text{FCF}_t = \text{EBIT} \times (1 - \text{Tax Rate}) + \text{Depreciation} - \text{Capex} - \Delta \text{NWC}
$$
 ② 确定折现率 (WACC)

$$
\text{WACC} = \frac{E}{V} \times r_E + \frac{D}{V} \times r_D \times (1 - \text{Tax Rate})
$$

其中:
- \(E\) = Equity
- \(D\) = Debt
- \(V = E + D\)

③ 估算终值 (Terminal Value)

永续增长模型:

$$
\text{Terminal Value}_N = \frac{\text{FCF}_{N+1}}{(\text{WACC} - g)}
$$

且:

$$
\text{FCF}_{N+1} = \text{FCF}_N \times (1 + g)
$$
④ 折现所有现金流

未来现金流现值:

$$
\text{PV}_{\text{FCF}} = \sum_{t=1}^{N} \frac{\text{FCF}_t}{(1 + \text{WACC})^t}
$$

终值现值:

$$
\text{PV}_{\text{Terminal}} = \frac{\text{Terminal Value}_N}{(1 + \text{WACC})^N}
$$

 ⑤ 计算企业价值 (Enterprise Value)

$$
\text{Enterprise Value} = \text{PV}_{\text{FCF}} + \text{PV}_{\text{Terminal}}
$$

若要算股权价值 (Equity Value)

$$
\text{Equity Value} = \text{Enterprise Value} - \text{Net Debt}
$$
