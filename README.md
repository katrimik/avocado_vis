# Avocado Market Analysis: Trends, Prices & Sales

## Project Overview

This project analyzes California avocado production data to explore agricultural trends, yields, and market values across different counties over multiple years. This is **farm production data**, not retail market data. The goal is to apply curriculum concepts in data visualization and statistical analysis to extract meaningful insights from agricultural production and economic data.

**Target Audience:** Educational presentation for curriculum demonstration

---

## Dataset Information

### Source & Contents
The dataset (`cali_avocados.csv`) contains **annual agricultural production data** for California avocados, sourced from agricultural census records. This is **farming and production data**, not retail market data, including:

- **Year**: Annual data spanning multiple years
- **County**: California county where avocados are grown
- **Harvested Acres**: Total acres of avocado farmland in that county
- **Yield**: Production efficiency (tons per acre)
- **Production**: Total tons harvested annually
- **Price P/U**: Price per unit received by farmers (per ton)
- **Value**: Total market value of the harvest (Production × Price)

### Dataset Scope & Size
- **Total Records**: 420 rows × 11 columns
- **Time Period**: 1980 to 2020 (41 years of data)
- **Geographic Coverage**: 27 California counties (from major producers like San Diego and Ventura to smaller producers in Fresno, Kern, Santa Cruz, and others)
- **Granularity**: Annual county-level agricultural data
- **Data Type**: Production data directly from farms (not retail/consumer market data)
- **Key Metrics**: Acres harvested, yield, production volume, farm prices, and total value
- **Data Source**: Agricultural census records

---

## Analysis Objectives

1. **Production Trends**: Understand how California avocado production volumes change over time by county
2. **Yield Analysis**: Compare agricultural efficiency (yield per acre) across different regions
3. **Economic Value**: Analyze total farm value and price trends for avocado crops
4. **Regional Comparison**: Identify which counties are major producers and how they differ
5. **Price-Production Relationships**: Explore whether production volumes correlate with prices
6. **Agricultural Volatility**: Identify periods of significant yield or price variations

---

## Visualization Techniques & Curriculum Concepts

### Information Visualization Principles

This analysis demonstrates key principles from **Shneiderman's Information Visualization Mantra**:
- **Overview first**: National trends across all California
- **Zoom and filter**: Detailed regional comparisons
- **Details on demand**: Individual county/type analysis

### Encoding Methods Used

We apply **best practices for visual encoding**:

- **Spatial Position**: Used for **quantitative data** (most accurate for precise value comparison)
  - Example: Prices and volumes on X/Y axes in line charts and scatter plots
  - Why: The human eye is most accurate at judging position, ideal for continuous numerical data

- **Color Hue**: Used for **categorical data** (distinguishing between categories)
  - Example: Blue for Conventional, Orange for Organic avocados
  - Why: Color distinctness helps separate discrete categories without affecting quantitative accuracy

- **Shape/Line Style**: Used to enhance category differentiation
  - Example: Solid lines for one type, dashed for another

### Statistical Techniques Explained

1. **Moving Average**
   - Smooths out weekly "noise" to reveal underlying trends
   - Shows the true market direction without short-term fluctuations
   - Particularly useful for agricultural data with seasonal variations

2. **Residuals**
   - Represents the deviation from the moving average
   - Highlights periods of exceptional market behavior
   - Useful for identifying supply shocks, trade events, or harvest anomalies

3. **Scatter Plots**
   - Reveals relationships between price and volume
   - Shows if higher prices correlate with higher/lower sales

---

## Notebook Structure

### Level 1: Overview First
- **State-wide trend analysis**: California-wide price and volume trends
- **Long-term patterns**: Multi-year perspective on market evolution

### Level 2: Zoom and Filter
- **Regional comparisons**: Selected counties/regions side-by-side
- **Conventional vs. Organic**: Direct market comparison
- **County-level detail**: Individual market dynamics

### Level 3: Details on Demand
- **Scatter plots**: Price-volume relationships
- **Volatility analysis**: Historical price variability
- **Moving averages & residuals**: Trend identification and anomaly detection
- **Distribution analysis**: Histograms of price/volume patterns
- **Grouped comparisons**: Avocado type performance by region

---

## Key Insights to Look For

As you explore the visualizations, consider these questions:

1. **Seasonality**: Do prices follow a seasonal pattern? When are avocados most expensive?
2. **Type Comparison**: Are organic avocados consistently more expensive? How do they behave differently?
3. **Regional Variation**: Do all California regions show the same trends, or are there local differences?
4. **Market Volatility**: When were the largest price swings? What might have caused them?
5. **Volume-Price Relationship**: When demand is high, do prices increase or decrease?

---

## How to Use This Notebook

1. **Start at the top** and work through sections sequentially
2. **Follow the analysis flow**: Overview → Regional Zoom → Details
3. **Read the markdown cells** for context and method explanations
4. **Examine the visualizations** and look for patterns
5. **Review the summary** for key findings and implications

---

## Technical Details

- **Language**: Python 3.x
- **Libraries**: pandas, matplotlib, numpy
- **Data Format**: CSV (comma-separated values)
- **Notebook Format**: Jupyter Notebook (.ipynb)

---

## Educational Value

This project demonstrates:
- ✓ Data analysis workflows
- ✓ Effective data visualization design
- ✓ Statistical analysis techniques (moving averages, residuals)
- ✓ Information visualization principles (Shneiderman's mantra)
- ✓ Visual encoding best practices (position vs. color)
- ✓ Exploratory data analysis methodology
- ✓ Real-world data interpretation

---

**Last Updated**: May 2026
