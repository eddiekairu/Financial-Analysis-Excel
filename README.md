# Financial-Analysis-Excel
 Project 1: US Tech Stock Analysis (The "Magnificent 7" Risk-Reward)
# Project Objective
Evaluated 20 years of historical price data for the "Magnificent 7" (AAPL, AMZN, GOOGL, META, MSFT, NVDA, TSLA) to determine which assets provided the best risk-adjusted returns during the AI and EV revolutions.
# Data & Tools
Source: Yahoo Finance (Daily Historical Prices 2005–2024).
Tools: Microsoft Excel (Advanced).
Key Techniques: Multi-level Sorting, IF Logic, Financial Feature Engineering, Volatility Modeling (StdDev).
# The Data Engineering Process
ETL Pipeline: Consolidated 7 separate CSV files into a unified master dataset using Power Query.
Data Integrity: Performed a Multi-Level Sort (Ticker > Date) to ensure time-series calculations were mathematically sound.
Feature Engineering:
Developed a Daily Return formula: =IF(A3=A2, (Price_T - Price_Y)/Price_Y, 0).
Calculated Historical Volatility using Standard Deviation to quantify market risk.
Interactive Visualization: Built a dynamic dashboard with Slicers allowing for instant peer-to-peer stock comparisons.
# Key Insights & Storytelling
The Volatility King: TSLA yielded the highest average daily return (0.0479) but recorded the highest Standard Deviation (Risk) in the group.
The AI Alpha: NVDA showed the most significant "Risk-Adjusted" growth, with returns accelerating sharply from 2023 onwards.
Stability vs. Growth: Established that MSFT and AAPL serve as "Anchor" assets with lower volatility compared to the high-beta profiles of the EV and Semiconductor sectors.
