Federal Funds Rates Impact on Market Indexes

Group Members:
Cameron Wilson
Jose Santos
Sierra Morgan
Carlos Adrian Stahl Alvarez de la Cuadra

Description:
What impact does the Federal Funds rate have on the stock market? We are going to pull the federal funds rate data from the FED website and compare it to the value of market indexes over time to determine if the federal funds rate is correlated with the value of the market indexes.

Null Hypothesis:
The Federal Funds rate does not impact the growth rate of the market indexes.

Datasets to be used:
    - Federal Funds Rate Dataset: https://fred.stlouisfed.org/series/FEDFUNDS
    - Market Indexes API: https://fred.stlouisfed.org/docs/api/fred/

Data Analysis Jupyter Notebook:
    - Import federal funds CSV
    - Connect to the FRED API for:
        - Federal funds percent change
        - S&P 500 value, percent change, value change
        - NASDAQ value, percent change, value change
        - DowJones value, percent change, value change
    - Create combined DataFrame with above variables
    - View data, look for errors and necessary drops
    - Write CSV from combined DataFrame

Data Visualization Jupyter Notebook:
    - Line graphs: 
        - Fed Funds vs time
        - S&P500 Valuation vs time
        - NASDAQ Valuation vs time
        - DowJones  Valuation vs time
        - All Valuations vs time
        - All Percent Change Valuations vs time
        - S&P500 Percent Change vs time
        - NASDAQ Percent Change vs time
        - DowJones Percent Change vs time
    - Box Plots:
        - S&P500 Percent Change
        - NASDAQ Percent Change
        - DowJones Percent Change
    - Regression Lines:
        - Regression Line: Fed Funds Rate vs S&P500 Value, Fed Funds Rate % Change vs S&P500 Value, Fed Funds Rate vs S&P500 % Change, Fed Funds Rate % Change vs S&P500 % Change
        - Regression Line: Fed Funds Rate vs NASDAQ Value, Fed Funds Rate % Change vs NASDAQ Value, Fed Funds Rate vs NASDAQ % Change, Fed Funds Rate % Change vs NASDAQ % Change
        - Regression Line: Fed Funds Rate vs DowJones Value, Fed Funds Rate % Change vs DowJones Value, Fed Funds Rate vs DowJones % Change, Fed Funds Rate % Change vs DowJones % Change
    - Independent T-Tests & Correlation Coefficent
        - Fed Funds Rate % Change vs S&P500 % Change
        - Fed Funds Rate % Change vs NASDAQ % Change 
        - Fed Funds Rate % Change vs DowJones % Change

Limitations: 
    - Limited to ten years of data for S&P 500 and DowJones Indexes, influencing our abililty to test for correlation.
    -Long periods of little change in the federal funds rate over the past 10 years may be an outlier when looking at longer periods of time.
    
    
Conclusions:
    - We were unable to reject our null hypothesis: The Federal Funds rate does not impact the growth rate of the market indexes.
