# Geopolitical-Market-Analysis
An analysis of the impact of geopolitical events on global stock markets
# Project 3: Analyzing the Impact of Geopolitical Events on Global Stock Markets

**Author:** Wil Watkins

## 1. Project Objective
To conduct an event study analyzing the impact of 15 major geopolitical and political events of the 21st century on the performance and volatility of six key global stock market indices, including those in emerging markets.

## 2. Methodology & Skills
This project utilized Python with the Pandas and Matplotlib/Seaborn libraries. Daily market data was sourced programmatically from Yahoo Finance using the yfinance library. Key analytical techniques included:

**Event Study Analysis:** Isolating 21-day windows around each event to measure market reaction.

**Time-Series Analysis:** Calculating daily returns and cumulative returns.

**Volatility Analysis:** Calculating and visualizing 30-day rolling volatility to measure market uncertainty.

**Data Visualization:** Creating normalized timeline charts to compare performance across disparate indices.

## 3. Key Findings
The analysis revealed several key patterns in how global markets react to shocks:

**Systemic vs. Regional Risk:** The visualizations clearly distinguish between systemic shocks (e.g., 2008 Financial Crisis, COVID-19 Pandemic) that cause synchronized spikes in volatility across all global markets, and regional political events (e.g., elections in Brazil, protests in India) whose impact is much more localized.
Market Anticipation: For predictable events like the Iraq War, market volatility often rises before the event, with a muted reaction on the day itself. For surprising events like Brexit, the reaction is immediate and severe.`
Divergent Economies: The master timeline chart visualizes the "two-speed" global economy post-2008, with US and Indian markets showing much stronger growth trajectories than those in the UK and Japan.`

**Market Anticipation**: For predictable events like the Iraq War, market volatility often rises before the event, with a muted reaction on the day itself. For surprising events like Brexit, the reaction is immediate and severe.`

**Divergent Economies:** The master timeline chart visualizes the "two-speed" global economy post-2008, with US and Indian markets showing much stronger growth trajectories than those in the UK and Japan.`

https://github.com/user-attachments/assets/d854b621-9708-41cc-bafd-49f20be030fb

--- Event Legend for the Chart Above ---
  1: 2001-09-17 - 9/11 Attacks (Market Re-opens)
  2: 2003-03-20 - Start of Iraq War
  3: 2008-09-15 - Collapse of Lehman Brothers
  4: 2014-05-16 - Narendra Modi Elected in India
  5: 2016-06-24 - Brexit Referendum Result
  6: 2016-11-09 - Donald Trump 2016 Election Victory
  7: 2018-03-22 - Start of US-China Trade War
  8: 2018-10-29 - Jair Bolsonaro Elected in Brazil (Market Reaction)
  9: 2020-11-09 - Joe Biden 2020 Election Victory
  10: 2020-11-26 - Start of Major Farmer Protests in India
  11: 2022-02-24 - Full-scale Invasion of Ukraine
  12: 2023-01-09 - Attack on Brazilian Congress (Market Reaction)
  13: 2023-10-09 - Start of Israel-Hamas War
  14: 2024-11-06 - Donald Trump 2024 Election Victory
  15: 2025-04-02 - Trump Tariff Announcement

## 4. How to Use This Repository

The complete analysis is in the Jupyter Notebook: **[Geopolitics_Market_Analysis.ipynb]**
The cleaned data is available in the CSV files.
An interactive version of this analysis can be viewed on my **[Tableau Public Dashboard](https://public.tableau.com/app/profile/william.watkins5080/vizzes)**.
A narrative summary is available on my **[LinkedIn Profile](link-to-your-linkedin-article)**.
