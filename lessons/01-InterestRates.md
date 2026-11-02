# 1. Interest rates

[Back to contents](../README.md)

## Summary

### 1.1 Interest rates and compounding
An interest rate tells us how much money is earned from saving or investing, or how much extra money someone must pay when borrowing.

Compound interest allows an investment to grow over time, as interest is calculated on both the initial amount known as the principal and interest accumulated in previous periods. The frequency of compounding affects the final value of the investment, the investment grows at an increasing rate over time, assuming a constant positive interest rate. Compounding can occur annually ($m=1$), semi-annually ($m=2$), quarterly ($m=4$) or monthly ($m=12$).

For example, suppose you invest £1,000 at 5% interest compounded annually.
- After the first year, you have £1,050.
- In the second year, interest is calculated on £1,050 rather than the original £1,000.

This means the balance grows faster over time because previously earned interest also earns interest.

The accumulated value of an investment can be calculated using:

$$A = P\left(1+\frac{r}{m}\right)^{mt}$$

where $P$ is the principal, $r$ is the annual interest rate, $m$ is the number of compounding periods per year, and $t$ is the time in years.

Continuous compounding takes this a step further by considering what happens when interest is added increasingly frequently. As the number of compounding periods approaches infinity, the accumulated value approaches a limit given by:

$$A = Pe^{rt}$$

where $e$ is Euler's number (approximately 2.71828), while $P$, $r$ and $t$ have the same meanings as before. For a fixed positive nominal interest rate, continuous compounding gives the highest accumulated value in the limit, compared with compounding at a finite number of intervals.

### 1.2 Nominal, effective and equivalent interest rates
A nominal interest rate is the annual rate advertised by a bank or lender. However, it does not fully account for how often interest is added. The effective rate takes compounding into account, giving a more accurate measure of the actual return earned over one year. This makes effective rates particularly useful when comparing investments with different compounding frequencies.

The effective annual interest rate is calculated using:

$$r_{\text{eff}} = \left(1+\frac{r}{m}\right)^m - 1

where $r$ is the nominal interest rate and $m$ is the number of compounding periods per year.

For continuous compounding:

$$r_{\text{eff}} = e^{r}-1 \ \text{(continuous)}$$

Equivalent interest rates are rates quoted using different compounding frequencies that produce the same effective annual return.
Two nominal rates r1 and r2, with compounding frequencies m1 and m2, are equivalent when:

$$\left(1+\frac{r_1}{m_1}\right)^{m_1} = \left(1+\frac{r_2}{m_2}\right)^{m_2}$$

### 1.3 Variable interest rates and the yield curve 

### 1.4 Inflation and real interest rates 

## My example

A situation you made up (your own numbers, not the ones in the lecture
notes), worked step by step.

## Solved exercises

### Exercise 1.x (from Exercise Sheet 1)

Question, then your solution.

## Spreadsheet

[01-InterestRates.xlsx](../spreadsheets/01-InterestRates.xlsx): what it
does, which cells to change and what to look at.
