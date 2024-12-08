# History-of-Asset-Pricing
I explore the history of market pricing, starting with the Efficient Market Hypothesis and the CAPM, moving through anomalies, and culminating with Fama-French 3- and 5-factor models. I also provide links and a brief summary of their effectiveness.

## Description
This repository provides tools and tutorials for analyzing financial markets, focusing on asset pricing models and their application to real-world data. Using APIs such as Yahoo Finance and WRDS, it demonstrates data importation, correlation analysis, and step-by-step implementation of asset pricing theories like CAPM, Fama-French 3-factor, and 5-factor models.

This is strongly base on https://www.tidy-finance.org/python/
Please use it for further references. 

## Files Overview

### 1. Yahoo Finance API
This notebook demonstrates:
- How to import financial data using the Yahoo Finance API.
- How to analyze correlations between ETFs and market indices.
- Actual application on "How to edge reneable stocks to inflation." 

### 2. Factor_5
This is the main notebook, showcasing:
- A historical walkthrough of asset pricing models:
  - **CAPM (Capital Asset Pricing Model)**: Foundational model linking risk and return.
  - **Fama-French 3-Factor Model**: Expands CAPM to include size and value factors.
  - **Fama-French 5-Factor Model**: Adds profitability and investment factors.
- Implementation using real-world data. (WRDS)
- Commentary on model implications and practical applications in modern finance.

### 3. Loading Financial Data
This notebook:
- Requires access to **WRDS (Wharton Research Data Services)** for private financial datasets.
- Uses WRDS API to download data to a local SQLite database.
- Prepares data for analysis in `Factor_5`.

### 4. Creating Environment
- A utility notebook for setting up your environment.
- Creates a `.env` file to securely store the WRDS API credentials.
- Ensures that APIs for WRDS and other services are configured correctly for seamless use.

### 5. WRDS Dummy Data
- For those without WRDS Dummy Data, it simualte the datas. 
