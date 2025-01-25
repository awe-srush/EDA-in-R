# EDA in R

## Overview
This document provides a summary of the work completed across eight distinct projects for the IMT 573 course. Each project focused on specific datasets and analytical techniques, utilizing R and RStudio for exploration, statistical analysis, and regression modeling. Below is a detailed breakdown of the tasks and objectives completed in each project.

---

## **1: EDA on `nycflights13` Dataset**
- **Dataset**: `nycflights13` (flight data from New York airports).
- **Key Tasks**:
  - Performed exploratory data analysis (EDA) on flight delay patterns.
  - Analyzed flight departure delays and their relationship to weather conditions.
  - Created visualizations for trends such as delays by carrier and month.
- **Techniques**:
  - Data cleaning, aggregation, and visualization using ggplot2 and dplyr.
  - Summary statistics for delay distributions.

---

## **2: COVID-19 Data Analysis (Part 1)**
- **Dataset**: COVID-19 data from Johns Hopkins University.
- **Key Tasks**:
  - Investigated global COVID-19 trends by country and time.
  - Explored new cases, recovery rates, and mortality rates.
  - Created visualizations like line charts and bar plots to compare countries.
- **Techniques**:
  - Data wrangling with dplyr.
  - Used visualization tools for comparative analysis of pandemic trends.

---

## **3: COVID-19 Data Analysis (Part 2)**
- **Dataset**: COVID-19 data (continuation from Part 1).
- **Key Tasks**:
  - Performed time-series analysis to study trends over specific periods.
  - Examined vaccination rates and their correlation with case counts.
  - Extended the previous analysis by focusing on demographic factors.
- **Techniques**:
  - Time-series decomposition.
  - Advanced data manipulation and plotting techniques.

---

## **4: Web Scraping with R**
- **Dataset**: Scraped data on mountain elevations from Wikipedia.
- **Key Tasks**:
  - Used the `rvest` package to scrape and parse data on mountains above 6800m.
  - Extracted geographic coordinates for each mountain and plotted them on a world map.
  - Cleaned and structured scraped data for analysis.
- **Techniques**:
  - Web scraping with `rvest`.
  - Data visualization with maps using `ggplot2`.

---

## **5: Statistical Analysis of Overbooking**
- **Dataset**: Hypothetical data for a small airline’s overbooking strategy.
- **Key Tasks**:
  - Determined optimal overbooking rates for a 100-seat plane.
  - Used binomial distributions to calculate probabilities of passenger show-ups.
  - Performed expected profit calculations for different overbooking scenarios.
- **Techniques**:
  - Statistical modeling using the binomial distribution.
  - Decision-making based on expected value calculations.

---

## **6: Heights of Fathers and Sons**
- **Dataset**: Father-son height data from 19th-century Britain (fatherson.csv).
- **Key Tasks**:
  - Explored "regression to the mean" concept using height data.
  - Computed descriptive statistics (mean, median, standard deviation) for fathers and sons.
  - Conducted simulations to test hypotheses about height differences.
- **Techniques**:
  - Descriptive and inferential statistics.
  - Simulations and hypothesis testing using random normal distributions.

---

## **7: Boston Housing Data**
- **Dataset**: Boston housing dataset (MASS package).
- **Key Tasks**:
  - Performed regression analysis to study relationships between median home value (`medv`) and predictors (`rm`, `lstat`, `tax`).
  - Conducted both simple and multiple regression modeling.
  - Compared and interpreted regression results for predictors.
- **Techniques**:
  - Simple and multiple linear regression.
  - Visualization of relationships using scatterplots with regression lines.

---

## **8: Mario Kart Auctions and Titanic Data**
- **Dataset 1**: Mario Kart auction data (openintro package).
- **Dataset 2**: Titanic survival data.
- **Key Tasks**:
  - **Mario Kart**:
    - Investigated factors affecting auction prices, including duration, condition, and shipping price.
    - Explored interaction effects between auction duration and item condition.
  - **Titanic**:
    - Preprocessed Titanic data to inspect survival rates by class, sex, and age.
    - Conducted regression analysis to determine predictors of survival.
- **Techniques**:
  - Multiple linear regression and interaction modeling.
  - Logistic regression for survival prediction.

---

## Tools and Libraries
- **Programming Language**: R
- **Key Libraries**:
  - `tidyverse` (data manipulation and visualization).
  - `rvest` (web scraping).
  - `MASS` (regression analysis).
  - `openintro` (datasets for analysis).
  - `ggplot2` (data visualization).

---

## Summary
These projects provided a comprehensive learning experience in data analysis, visualization, statistical modeling, and regression techniques. Each task built on foundational skills, culminating in more advanced analysis and predictive modeling.

---


