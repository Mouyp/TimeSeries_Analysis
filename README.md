# TimeSeries_Analysis

## Project Overview

This project presents a comprehensive analysis of a hypothetical brand's sales performance operated in the FMCG in relation to its marketing strategies and the corresponding competitive landscape. 

Purpose of the Analysis:

The primary objective of this analysis is to evaluate the effectiveness of the brand's marketing initiatives and their interplay with competitor strategies. By scrutinizing sales, advertising, and pricing data, this report aims to empower the brand's management with actionable insights for data-driven decision-making. The analysis can be broken into:

1) Analysis on the brand's marketing effectiveness
2) Analysis on the brand's marketing interaction with competitors
3) Analysis on the relative impact of the brand own and competitors' marketing action on sales.

## Outline

Part 1: Import dataset and necessary libraries

Part 2: Data preprocessing - data wrangling & cleaning

Part 3: Exploratory data analysis (EDA)

- Descriptive Analysis
- Temporal Causality Analysis
- Stationarity Analysis
- Dynamic System Analysis
- Variance Decomposition Analysis

Part 4: Conclusion: manegerial insights & recommendations


## Data Descriptions

The dataset contains 207 weekly observations of the brand's performance metrics including log-transformed sales, advertising expenditure, and pricing data, and competitors' actions including competitors' price and advertising. 

1) Week - Identifier for the week of observation; 1-207 (linear trend)

2) LnSales - Log-transformed volume sales of the brand (expressed in the relevant unit)

3) LnAdvertising - Log-transformed advertising spending by the brand (in dollars) 

4) LnPrice - Log-transformed unit price of the brand (expressed in dollars per unit)

5) LnTotalCompAdvertising - Log-transformed total advertising spending by competitors of the brand (expressed in dollars)

6) LnAvgCompPrice - Log-transformed average unit price of competitors of the brand (expressed in dollars per unit)

7) Qrtr 1 - Indicator variable = 1 for the first quarter, 0 otherwise

8) Qrtr 2 - Indicator variable = 1 for the second quarter, 0 otherwise

9) Qrtr 3 - Indicator variable = 1 for the third quarter, 0 otherwise

10) Qrtr 4 - Indicator variable = 1 for the fourth quarter, 0 otherwise
