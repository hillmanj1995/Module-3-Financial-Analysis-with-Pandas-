# Cryptocurrency Arbitrage

The Analyst was tasked with creating an analysis of calculating arbitrage profits for Bitcoin across (2) exchanges: Bitstamp and Coinbase.

---

## Technology

This analysis was based in Python 3.7, and used the following libraries:
- pathlib - Object-oriented filesystem paths
- csv - File Reading and Writing
- pandas - dataframe calculations and ETL
- matplotlib - visualizations

---

## Installation Guide

Prior to running the application, the following libraries must be installed:

![libraries.png](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/libraries.png)

---

## Results
The analysis was broken into (3) distinct sections: data collection, preparation, and analysis.  The data collections phase was achieved through the pd.read_csv and turning that raw data into a dataframe.

The second phase of the analysis, the preparation, was achieved by reviewing the data and applying transformations to the datatypes to change them into data that can be analyzed.  The Analyst did this by using the commands:

    .dtypes(), .isnull(), .dropna(), .astype()

These functions allowed the analyst to see the data types, determine and drop null values, and change the datatypes to usable types.

The last phase was the analysis portion.  The Analyst set out to determine arbitrage profits for bitcoin across the bitstamp and coinbase exchanges.  To do this, the Analyst first created visualizations of the closing prices of bitcoin across the (2) exchanges.  Those visualizations can be seen below:

Early Stage Closing Prices:

![early_close](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/early_close.png)

Middle Stage Closing Prices:

![middle_close](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/middle_close.png)

Late Stage Closing Prices:

![End_close](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/End_close.png)

From those visualizations and values, The Analyst was able to calculate the arbitrage spread and profitable trades over the allotted timeframe.  The Analyst then summed the profitable trades to show the total amount of profits for the various timeframes at early, middle, and late stages of the dataset.  Those values and code are shown below:

Early Stage Profits:

![early_profits](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/early_profits.png)

Middle Stage Closing Prices:

![middle_profits](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/middle_profits.png)

Late Stage Closing Prices:

![late_profits](https://github.com/hillmanj1995/Module-3-Financial-Analysis-with-Pandas-/blob/main/Challenge_Code/images/late_profits.png)

## Summary
By looking at the profits, it is apparent that the opportunity for arbitrage profit was highest in the beginning of the year ($14,148 at the early date) and progressively decreased as time went on.
