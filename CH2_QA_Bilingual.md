# Chapter 2: Asset Classes and Financial Instruments
# 第二章：資產類別與金融工具

> 精選題目與解答 | Selected Problems & Answers

---

## Problem 2 / 第 2 題

### 題目（英文）
Why are money market securities often called "cash equivalents"?

### 題目（中文）
為什麼貨幣市場證券常被稱為「現金等價物」？

### Answer / 答案（英文）
Money market securities are called cash equivalents because of their high level of liquidity. The prices of money market securities are very stable, and they can be converted to cash (i.e., sold) on very short notice and with very low transaction costs. Examples of money market securities include Treasury bills, commercial paper, and banker's acceptances, each of which is highly marketable and traded in the secondary market.

### 答案（中文）
貨幣市場證券之所以被稱為現金等價物，是因為其流動性極高。貨幣市場證券的價格非常穩定，能夠在極短時間內以極低的交易成本轉換為現金（即出售）。例子包括國庫券、商業票據及銀行承兌匯票，這些證券均具高度市場性，且在次級市場上交易。

---

## Problem 11 / 第 11 題

### 題目（英文）
Consider the three stocks in the following table. $P_t$ represents price at time $t$, and $Q_t$ represents shares outstanding at time $t$. Stock C splits two for one in the last period.

|   | $P_0$ | $Q_0$ | $P_1$ | $Q_1$ | $P_2$ | $Q_2$ |
|---|------:|------:|------:|------:|------:|------:|
| A |    90 |   100 |    95 |   100 |    95 |   100 |
| B |    50 |   200 |    45 |   200 |    45 |   200 |
| C |   100 |   200 |   110 |   200 |    55 |   400 |

**(a)** Calculate the rate of return on a price-weighted index of the three stocks for the first period ($t = 0$ to $t = 1$).

**(b)** What must happen to the divisor for the price-weighted index in year 2?

**(c)** Calculate the rate of return for the second period ($t = 1$ to $t = 2$).

### 題目（中文）
考慮下表中三支股票。$P_t$ 代表時間 $t$ 的股價，$Q_t$ 代表時間 $t$ 的流通在外股數。股票 C 在最後一期進行 2 股換 1 股的股票分割。

|   | $P_0$ | $Q_0$ | $P_1$ | $Q_1$ | $P_2$ | $Q_2$ |
|---|------:|------:|------:|------:|------:|------:|
| A |    90 |   100 |    95 |   100 |    95 |   100 |
| B |    50 |   200 |    45 |   200 |    45 |   200 |
| C |   100 |   200 |   110 |   200 |    55 |   400 |

**(a)** 計算第一期（$t=0$ 至 $t=1$）三支股票價格加權指數的報酬率。

**(b)** 在第二年，價格加權指數的除數必須如何調整？

**(c)** 計算第二期（$t=1$ 至 $t=2$）的報酬率。

### Answer / 答案（英文）

**(a)**

$$\text{Index}_{t=0} = \frac{90 + 50 + 100}{3} = 80$$

$$\text{Index}_{t=1} = \frac{95 + 45 + 110}{3} = 83.33$$

$$\text{Rate of Return} = \frac{83.33}{80} - 1 = 4.17\%$$

**(b)**

Without the split, Stock C would sell for 110, giving:

$$\frac{95 + 45 + 110}{3} = 83.33$$

After the split, Stock C sells for 55. We solve for the new divisor $d$:

$$83.33 = \frac{95 + 45 + 55}{d} \implies d = \frac{195}{83.33} = 2.340$$

The divisor **fell** from 3 to 2.340 — this always happens when a component stock splits.

**(c)**

$$\text{Index}_{t=1} = \frac{95 + 45 + 110}{3} = 83.33$$

$$\text{Index}_{t=2} = \frac{95 + 45 + 55}{2.340} = 83.33$$

$$\text{Rate of Return} = \frac{83.33}{83.33} - 1 = \mathbf{0\%}$$

The return is zero because each stock's individual return equals zero in this period.

### 答案（中文）

**(a)**

$$\text{指數}_{t=0} = \frac{90 + 50 + 100}{3} = 80$$

$$\text{指數}_{t=1} = \frac{95 + 45 + 110}{3} = 83.33$$

$$\text{報酬率} = \frac{83.33}{80} - 1 = 4.17\%$$

**(b)**

若沒有股票分割，股票 C 股價應為 110，指數值維持 83.33，除數為 3。

分割後股票 C 股價為 55，需找出新除數 $d$：

$$83.33 = \frac{95 + 45 + 55}{d} \implies d = \frac{195}{83.33} = 2.340$$

除數從 3 **下降**至 2.340，這是成分股進行股票分割後的必然結果。

**(c)**

$$\text{指數}_{t=1} = \frac{95 + 45 + 110}{3} = 83.33$$

$$\text{指數}_{t=2} = \frac{95 + 45 + 55}{2.340} = 83.33$$

$$\text{報酬率} = \frac{83.33}{83.33} - 1 = \mathbf{0\%}$$

報酬率為零，因為第二期每支股票的個別報酬率均為零。

---

## Problem 12 / 第 12 題

### 題目（英文）
Using the data in the previous problem, calculate the first-period rates of return on the following indexes of the three stocks:

**(a)** A market-value-weighted index.

**(b)** An equally weighted index.

### 題目（中文）
利用前一題的數據，計算三支股票以下指數在第一期的報酬率：

**(a)** 市值加權指數。

**(b)** 等權重指數。

### Answer / 答案（英文）

**(a)** Market-value-weighted index:

| Stock | $P_0$ | $Q_0$ | Market Value $t=0$ | $P_1$ | $Q_1$ | Market Value $t=1$ |
|-------|------:|------:|-------------------:|------:|------:|-------------------:|
| A     |    90 |   100 |             $9,000 |    95 |   100 |             $9,500 |
| B     |    50 |   200 |            $10,000 |    45 |   200 |             $9,000 |
| C     |   100 |   200 |            $20,000 |   110 |   200 |            $22,000 |
| **Total** |  |       |        **$39,000** |       |       |        **$40,500** |

$$\text{Rate of Return} = \frac{40{,}500}{39{,}000} - 1 = 3.85\%$$

**(b)** Equally weighted index:

$$r_A = \frac{95}{90} - 1 = +5.56\%$$

$$r_B = \frac{45}{50} - 1 = -10.00\%$$

$$r_C = \frac{110}{100} - 1 = +10.00\%$$

$$\bar{r} = \frac{5.56\% + (-10.00\%) + 10.00\%}{3} = \frac{5.56\%}{3} = 1.85\%$$

### 答案（中文）

**(a)** 市值加權指數：

| 股票 | $P_0$ | $Q_0$ | 市值（$t=0$） | $P_1$ | $Q_1$ | 市值（$t=1$） |
|------|------:|------:|-------------:|------:|------:|-------------:|
| A    |    90 |   100 |       $9,000 |    95 |   100 |       $9,500 |
| B    |    50 |   200 |      $10,000 |    45 |   200 |       $9,000 |
| C    |   100 |   200 |      $20,000 |   110 |   200 |      $22,000 |
| **合計** |  |   |   **$39,000** |      |       |   **$40,500** |

$$\text{報酬率} = \frac{40{,}500}{39{,}000} - 1 = 3.85\%$$

**(b)** 等權重指數：

$$r_A = \frac{95}{90} - 1 = +5.56\%$$

$$r_B = \frac{45}{50} - 1 = -10.00\%$$

$$r_C = \frac{110}{100} - 1 = +10.00\%$$

$$\bar{r} = \frac{5.56\% + (-10.00\%) + 10.00\%}{3} = 1.85\%$$

---

*文件結束 | End of Document*
