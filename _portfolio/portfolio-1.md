---
title: "Rainfall Data Visualization"
excerpt: "Interactive Plotly visualizations analyzing rainfall patterns and trends"
collection: portfolio
permalink: /portfolio/rainfall-visualization/
date: 2025-06-09
---

# India Rainfall Descriptive Analytics Report (1901-2015)

## Interactive Dashboard
<div style="text-align: center; margin: 20px 0;">
    <a href="/files/visualizations/Rainfall_EDA.html" target="_blank" 
       style="background-color: #007cba; color: white; padding: 10px 20px; 
              text-decoration: none; border-radius: 5px;">
        View Interactive Visualization
    </a>
</div>

## Executive Summary

This comprehensive analysis examines 115 years of rainfall data across India from 1901 to 2015, revealing critical patterns in precipitation distribution, seasonal variations, extreme weather events, and long-term trends. The dataset encompasses monthly rainfall measurements aggregated at the national level, providing insights into India's monsoon-dependent climate system.

## 1. Dataset Overview

### Basic Statistics
- **Analysis Period**: 1901-2015 (115 years)
- **Geographic Coverage**: India (National Level)
- **Data Granularity**: Monthly measurements
- **Total Data Points**: 1,380 monthly observations

### Key Metrics
- **Mean Annual Rainfall**: 1,182.0 mm
- **Median Annual Rainfall**: 1,190.5 mm
- **Standard Deviation**: 110.7 mm
- **Coefficient of Variation**: 9.4% (relatively stable)

## 2. Temporal Distribution Analysis

### 2.1 Monthly Rainfall Patterns

| Month | Average Rainfall (mm) | Percentage of Annual | Seasonal Classification |
|-------|----------------------|---------------------|------------------------|
| January | 20 mm | 1.7% | Winter (Dry) |
| February | 23 mm | 1.9% | Winter (Dry) |
| March | 28 mm | 2.4% | Pre-Monsoon |
| April | 38 mm | 3.2% | Pre-Monsoon |
| May | 62 mm | 5.2% | Pre-Monsoon |
| June | 168 mm | 14.2% | Monsoon |
| July | **291 mm** | **24.6%** | **Monsoon (Peak)** |
| August | 258 mm | 21.8% | Monsoon |
| September | 172 mm | 14.5% | Monsoon |
| October | 76 mm | 6.4% | Post-Monsoon |
| November | 29 mm | 2.5% | Post-Monsoon |
| December | **15 mm** | **1.3%** | **Winter (Lowest)** |

### 2.2 Seasonal Distribution

| Season | Rainfall (mm) | Percentage | Duration |
|--------|---------------|------------|----------|
| **Monsoon** (Jun-Sep) | **889 mm** | **75.3%** | 4 months |
| Pre-Monsoon (Mar-May) | 129 mm | 10.9% | 3 months |
| Post-Monsoon (Oct-Nov) | 120 mm | 10.1% | 2 months |
| Winter (Dec-Feb) | 43 mm | 3.7% | 3 months |

## 3. Extreme Weather Events Analysis

### 3.1 Drought Years (≤ 1,016.0 mm)

| Rank | Year | Rainfall (mm) | Drought Category | Anomaly Score | Percentile |
|------|------|---------------|------------------|---------------|------------|
| 1 | **2002** | **920.8** | Extreme Drought | -2.36σ | 0.9% |
| 2 | 1965 | 938.4 | Extreme Drought | -2.20σ | 1.7% |
| 3 | 1972 | 948.5 | Extreme Drought | -2.11σ | 2.6% |
| 4 | 2009 | 959.3 | Extreme Drought | -2.01σ | 3.5% |
| 5 | 1905 | 975.3 | Severe Drought | -1.87σ | 4.3% |

**Drought Frequency**: 4.3% (5 years out of 115)

### 3.2 Excess Rainfall Years (≥ 1,348.1 mm)

| Rank | Year | Rainfall (mm) | Excess Category | Anomaly Score | Percentile |
|------|------|---------------|-----------------|---------------|------------|
| 1 | **1917** | **1,480.3** | Extreme Excess | +2.69σ | 100.0% |
| 2 | 1961 | 1,403.0 | Severe Excess | +2.00σ | 99.1% |
| 3 | 1990 | 1,400.6 | Severe Excess | +1.97σ | 98.3% |
| 4 | 1933 | 1,393.5 | Severe Excess | +1.91σ | 97.4% |
| 5 | 1956 | 1,386.2 | Severe Excess | +1.84σ | 96.5% |
| 6 | 1959 | 1,382.1 | Severe Excess | +1.81σ | 95.7% |
| 7 | 1988 | 1,351.0 | Severe Excess | +1.53σ | 94.8% |

**Excess Frequency**: 6.1% (7 years out of 115)

### 3.3 Extreme Event Summary
- **Total Extreme Years**: 12 (10.4% of all years)
- **Wettest Year**: 1917 with 1,480.3 mm (+298.3 mm above average)
- **Driest Year**: 2002 with 920.8 mm (-261.2 mm below average)
- **Range**: 559.5 mm between wettest and driest years

## 4. Monthly Anomaly Analysis

### 4.1 Anomaly Frequency by Month

| Month | Anomalous Years | Most Extreme Event | Extreme Value | Anomaly Score |
|-------|-----------------|-------------------|---------------|---------------|
| January | 10 | 1943 | 58.5 mm | +3.88σ |
| **February** | **17** | 1937 | 53.8 mm | +2.64σ |
| March | 12 | 1967 | 63.3 mm | +2.85σ |
| April | 14 | 2015 | 69.4 mm | +3.01σ |
| May | 13 | 1990 | 114.5 mm | +3.34σ |
| June | 14 | 1938 | 275.5 mm | +3.01σ |
| July | 11 | 2002 | 138.9 mm | -3.70σ |
| August | 17 | 1926 | 335.5 mm | +2.20σ |
| September | 13 | 1917 | 281.0 mm | +2.96σ |
| October | 14 | 1917 | 158.8 mm | +2.94σ |
| November | 14 | 1979 | 74.2 mm | +2.79σ |
| December | 9 | 1967 | 54.4 mm | +4.49σ |

- **Total Anomalous Months**: 158 (across all years)
- **Anomaly Threshold**: ±1.5 standard deviations
- **Most Variable Month**: February (17 anomalous years)
- **Least Variable Month**: December (9 anomalous years)

### 4.2 Decadal Anomaly Distribution

| Decade | Anomalous Months | Anomaly Rate |
|--------|------------------|--------------|
| 1900s | 21 | High |
| 1910s | 20 | High |
| 1920s | 17 | Moderate |
| 1930s | 13 | Low |
| 1940s | 13 | Low |
| 1950s | 17 | Moderate |
| 1960s | 9 | Very Low |
| 1970s | 13 | Low |
| 1980s | 7 | Very Low |
| 1990s | 10 | Low |
| 2000s | 10 | Low |
| 2010s | 8 | Very Low |

**Observation**: Earlier decades (1900s-1910s) show higher anomaly frequencies, while recent decades show more stability.

## 5. Seasonal Correlation Analysis

### 5.1 Correlation with Annual Rainfall

| Season | Pearson Correlation | P-Value | Spearman Correlation | P-Value | Significance |
|--------|-------------------|---------|---------------------|---------|--------------|
| **Monsoon** | **0.9300** | **<0.0001** | **0.9124** | **<0.0001** | **Highly Significant** |
| Post-Monsoon | 0.5316 | <0.0001 | 0.4755 | <0.0001 | Significant |
| Pre-Monsoon | 0.3131 | 0.0007 | 0.2897 | 0.0017 | Significant |
| Winter | 0.2289 | 0.0139 | 0.2301 | 0.0134 | Significant |

**Key Finding**: Monsoon season shows the strongest correlation with annual rainfall (r = 0.93), confirming its dominant role in India's annual precipitation.

## 6. Long-term Trends and Patterns

### 6.1 Historical Trends (1901-2015)
- **Overall Trend**: Relatively stable with cyclical variations
- **10-Year Moving Average**: Shows periodic fluctuations around the long-term mean
- **Trend Analysis**: No significant linear trend detected over the 115-year period

### 6.2 Clustering Analysis
- **Optimal Clusters**: 3 distinct rainfall patterns identified
- **Pattern Classification**: Low, Normal, and High rainfall years
- **Cluster Distribution**: Balanced distribution across the three patterns

## 7. Forecasting Insights (2016-2035)

### 7.1 Prophet Model Projections
- **Historical Average (1901-2015)**: 1,182.0 mm
- **Forecast Average (2016-2035)**: 1,104.7 mm
- **Projected Change**: -77.3 mm (-6.5% decrease)

### 7.2 Seasonal Components
- **Trend Component**: Slight declining trend identified
- **Seasonal Component**: Strong annual seasonality preserved
- **Confidence Intervals**: Wide range indicating natural variability

## 8. Key Insights and Conclusions

### 8.1 Critical Findings

1. **Monsoon Dominance**: 75.3% of annual rainfall occurs during the 4-month monsoon season (June-September)

2. **Peak Variability**: July represents the peak rainfall month (291 mm average) with significant year-to-year variation

3. **Extreme Events**: Historical occurrence of severe droughts (4.3% frequency) and excess rainfall years (6.1% frequency)

4. **Seasonal Predictability**: Strong correlation between monsoon performance and annual rainfall totals

5. **Temporal Stability**: Recent decades show reduced anomaly frequency compared to early 20th century

### 8.2 Risk Assessment

**High Risk Factors**:
- Monsoon failure can lead to severe annual deficits
- Extreme events (both drought and excess) occur regularly
- Winter and pre-monsoon seasons contribute minimally to annual totals

**Moderate Risk Factors**:
- Post-monsoon rainfall shows moderate correlation with annual totals
- Decadal variations in anomaly patterns

### 8.3 Implications for Water Resource Management

1. **Monsoon Dependency**: Critical need for monsoon-season water conservation and storage
2. **Extreme Event Preparedness**: Planning for both drought and flood scenarios
3. **Seasonal Distribution**: Limited rainfall outside monsoon requires efficient water management
4. **Long-term Planning**: Stable long-term patterns support consistent water resource planning

## 9. Data Quality and Limitations

### 9.1 Data Strengths
- **Comprehensive Coverage**: 115 years of consistent data
- **National Scope**: Represents India-wide patterns
- **High Temporal Resolution**: Monthly granularity
- **Statistical Robustness**: Large sample size for reliable analysis

### 9.2 Limitations
- **Spatial Aggregation**: National averages may mask regional variations
- **Climate Change Context**: Future projections may not capture non-linear climate changes
- **Extreme Event Rarity**: Limited sample of extreme events for robust modeling

---

*This analysis provides a comprehensive overview of India's rainfall patterns from 1901-2015, highlighting the critical role of monsoon seasons, the occurrence of extreme events, and long-term trends that inform water resource management and climate adaptation strategies.*