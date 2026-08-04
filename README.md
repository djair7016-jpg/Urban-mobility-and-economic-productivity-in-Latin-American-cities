# Urban Mobility and Economic Productivity in Latin American Cities

## Executive Summary

Urban congestion affects travel times, accessibility, and quality of life, but its relationship with economic productivity is not necessarily the same across cities.

I developed an exploratory analysis using Python, combining TomTom mobility indicators with OECD economic data for Latin American cities. The project evaluated congestion levels alongside GDP per capita and unemployment indicators to determine whether cities with greater mobility challenges also showed weaker economic performance.

The analysis identified substantial differences between cities, but it did not reveal a consistent relationship in which higher congestion always corresponded to lower GDP per capita or higher unemployment.

The results suggest that congestion should not be used as an isolated indicator of economic performance. Transport infrastructure, population density, urban structure, labor markets, and public-transit availability should also be considered before making investment or policy decisions.

## Project Context

This project was developed as a simulated analytical case for a regional development institution interested in evaluating urban mobility and economic performance in Latin America.

The analysis focused on the following questions:

- Which cities presented the highest congestion levels?
- How did GDP per capita vary across the selected cities?
- Was congestion associated with lower economic productivity?
- Was unemployment related to urban mobility conditions?
- Which cities could serve as benchmarks for future mobility studies?

The objective was to integrate mobility and economic information into a comparative analytical framework.

## Data Sources

The project combined information from:

### TomTom Mobility Data

Mobility indicators included:

- Congestion levels
- Travel-time measures
- City-level mobility performance
- Annual urban-traffic indicators

### OECD Economic Data

Economic variables included:

- GDP per capita
- Unemployment indicators
- City or regional economic measurements
- Reference year

The analysis focused primarily on the 2024 period.

## Data Preparation

I used Python and Pandas to:

- inspect dataset structures and data types;
- standardize city names;
- review missing and inconsistent values;
- convert numerical and date variables;
- aggregate mobility indicators by city;
- integrate TomTom and OECD information;
- validate that the resulting comparisons used consistent geographic units.

This integration stage was essential because the two sources used different structures and naming conventions.

## Analytical Approach

### 1. Mobility Analysis

I compared cities according to:

- Congestion levels
- Travel-time indicators
- Relative mobility performance

### 2. Economic Analysis

I evaluated:

- GDP per capita
- Unemployment
- Differences in economic performance between cities

### 3. Relationship Analysis

Mobility and economic indicators were compared using:

- Exploratory visualizations
- Descriptive statistics
- Correlation analysis
- City-level comparisons

The project was exploratory and did not attempt to establish a causal effect between congestion and economic productivity.

## Key Findings

- Congestion levels varied considerably across Latin American cities.
- Economic performance also showed significant differences between cities.
- Higher congestion was not consistently associated with lower GDP per capita.
- Cities with similar congestion levels sometimes presented very different economic outcomes.
- Unemployment and congestion did not show a sufficiently consistent relationship to support a general conclusion.
- Urban mobility is only one of several factors associated with city-level productivity.

## Business and Policy Recommendations

- Avoid evaluating urban economic performance using congestion as a standalone indicator.
- Combine mobility measures with population density, public-transit coverage, infrastructure investment, and labor-market information.
- Extend the analysis to multiple years to distinguish temporary effects from structural patterns.
- Segment cities according to size, geography, and economic structure before comparing performance.
- Use cities with relatively efficient mobility and strong economic indicators as exploratory benchmarks.
- Conduct causal or longitudinal analyses before recommending major transportation investments.

## Tools and Techniques

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data cleaning
- Dataset integration
- Exploratory data analysis
- Correlation analysis
- Urban and economic indicator comparison

## Visualizations

### Congestion by City

![Congestion by City](images/congestion_by_city.png)

### Congestion and GDP per Capita

![Congestion vs GDP](images/congestion_vs_gdp.png)

### Mobility and Economic Comparison

![Mobility and Economic Comparison](images/mobility_economic_comparison.png)

## Repository Structure

```text
notebooks/  Data preparation, integration, and exploratory analysis
data/       Mobility and economic datasets, if publication is permitted
images/     Main visualizations
README.md   Project documentation
