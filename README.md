# MC-VaR-Deposit-Outflow-
The project part eliminated the shortcomings of the current methodology for calculating the risks of VaR of the outflow of the deposit portfolio of Center Credit Bank.

The Value-at-Risk model evaluates market risk by determining how much the value of a portfolio is likely to decline over a given period of time with a given probability as a result of changes in market prices or rates.

Two main parameters are used in the calculation:
- N (time horizon) is the time period over which VaR is measured.
Traditionally, it is measured in trading days rather than calendar days. From a 11
pragmatic point of view, financial analysts most often set N = 1 due to a lack of data to assess the behavior of market variables over a longer period of time;
- 𝛼 (trust level) - frequently used trust levels - 99% and 95%.
According to the 1996 BIS Amendmend document, the capital recorded in the
trading book must be calculated using two parameters:
- N = 10: This parameter means that regulators are focusing on the potential
losses that the bank may incur within 10 days;
- X = 99: This parameter indicates that regulators expect the bank's losses
to exceed VaR only 1% of the time.
Based on these parameters, the bank is obliged to maintain the amount of capital,
which will be k times greater than the VaR indicator (taking into account specific risks). Coefficient k It is set by regulators individually for each bank and should not be less than 3.0. For banks that have carefully established procedures for assessing VaR, the k coefficient is set at a minimum level of 3.0. For other banks, this ratio may be
higher, depending on the assessment of their riskiness.

Risk is calculated taking into account changes in value in three ways:
- Absolute price change;
- Logarithmic price change (used in the normal yield distribution hypothesis);
- A relative change in price, but if the change occurs relative to the original price, then it is called the yield or rate of profit. 1-day period.
The confidence level in the VaR estimation process is determined by the number of standard variance deviations applied to the probability distribution.

Another way to quantify risk is Conditional Value-at-Risk (CVaR). If we are talking about random variables with continuous distribution functions, it is a conditional expectation 𝐶𝑉𝑎𝑅)(𝑋)X Taking into account the fact that . This definition is the basis of the term "Conditional Value-at-Risk". The concept of notional value at risk was proposed by Rokafellar and Uryasev [𝑋 ≥ 𝑉𝑎𝑅)(𝑋)15].

VaR may be preferable for portfolio optimization in situations where reliable models for extreme events are lacking, as it overlooks the most hard-to-measure events. Conversely, CVaR may not produce satisfactory results when applied to out-of-sample scenarios if portfolio optimization is based on a poorly composed set of potential scenarios. The medium-reversing nature of assets can make historical data inadequate for predicting future tail events, as periods of high returns are usually followed by periods of low returns. Therefore, CVaR derived from historical data can lead to erroneous risk estimates.

Based on the results of the analysis, several recommendations can be made for the development of an updated methodology for calculating the risk of outflow of deposits for Home Credit Bank.

It is recommended to use the Value-at-Risk calculation methodology using modeling and use the parametric model only in the specific cases described in the first part.

Net 10-day risk of outflow of the deposit portfolio as of the date calculated by Monte Carlo simulation - 8.36 billion tenge. But if the risks go beyond the 99th percentile – 9.92 billion tenge – there is a risk of outflow. This is the minimum level of liquidity maintained for Home Credit Bank.
If we take into account the calculations of VaR and CVaR using the most accurate method – Monte Carlo, on the date of calculation, Home Credit Bank must have at least 25 billion tenge in net liquidity in order to meet the standards of the Basel Committee and cover the risks of outflow of the agreed deposit portfolio.
