# Kenya Food Price Analytics 
!(dashboard.PNG)
## Overview
This project analyzes food price trends across Kenya using WFP market price data from 2020 to 2026. It explores how commodity prices have changed over time, which counties have the highest food costs, which commodities are most volatile, and forecasts future maize flour prices using Facebook's Prophet model.

## Objectives
- Track how food prices have changed across Kenya between 2020 and 2026
- Identify which counties pay the most for basic food commodities
- Measure which commodities are most volatile in price
- Forecast maize flour prices for the next 12 months

## Key Findings

### 1. Price Trends Over Time
Maize flour prices remained stable around KES 60-65 through 2020 and early 2021, before rising sharply through 2022 driven by post-COVID supply chain disruptions and the Russia-Ukraine war. Prices peaked at KES 115-120 in early 2023 coinciding with Kenya's election period, significantly increasing the cost of living for low income households. From 2024 onwards prices began stabilizing around KES 80-85 — higher than pre-pandemic levels but showing a clear downward trend.

Vegetable oil prices surged by over 75% between 2021 and early 2022, rising from around KES 200 to a peak of KES 350. This spike aligns with Russia's invasion of Ukraine in February 2022, disrupting global sunflower oil supply chains and driving up import costs in Kenya.

Despite the broad food inflation between 2022 and 2023, maize grain remained the most stable and affordable commodity throughout the entire period, rarely exceeding KES 80. This highlights why maize is Kenya's most critical food security crop.

### 2. Price by County
- **North Eastern** has the highest average food prices (KES 142) due to remote location, poor road infrastructure, and harsh climate making food supply difficult
- **Nairobi** has the lowest average food prices (KES 104) as the main supply and distribution hub for the country

### 3. Commodity Volatility
- **Vegetable Oil** is the most volatile commodity (std dev: KES 39) — heavily influenced by global events
- **Kale** is surprisingly volatile (std dev: KES 38) — highly seasonal and weather dependent
- **Maize** is the most stable commodity (std dev: KES 13) — confirming its role as Kenya's food security anchor

### 4. Price Forecast
Using Facebook's Prophet model, maize flour prices are forecast to gradually stabilize around KES 75-85 through 2027, continuing the downward trend observed since the 2023 peak.

## Tools & Technologies
- **Python** — Pandas, NumPy, Matplotlib, Seaborn, Prophet
- **Power BI** — Interactive dashboard
- **Data Source** — WFP VAM Food Price Monitoring (Humanitarian Data Exchange)


