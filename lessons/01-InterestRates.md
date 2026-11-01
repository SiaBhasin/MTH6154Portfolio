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
where \(P\) is the principal, \(r\) is the annual interest rate, \(m\) is the number of compounding periods per year, and \(t\) is the time in years.

Continuous compounding takes this a step further by considering what happens when interest is added increasingly frequently. As the number of compounding periods approaches infinity, the accumulated value approaches a limit given by:
$$A = Pe^{rt}$$
where \(e\) is Euler's number (approximately 2.71828), while \(P\), \(r\) and \(t\) have the same meanings as before. For a fixed positive nominal interest rate, continuous compounding gives the highest accumulated value in the limit, compared with compounding at a finite number of intervals.

### 1.2 Nominal, effective and equivalent interest rates
The main distinction between nominal and effective interest rates is how compounding is accounted for.
The nominal rate is the interest rate a bank advertises. However, it doesn't always tell you exactly how much interest you'll earn in a year.
The effective rate takes compounding into account, so it gives a better picture of your actual annual return.


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
