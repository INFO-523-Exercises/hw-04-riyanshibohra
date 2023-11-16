## Data Source

Big Tech Stock Prices: 
https://github.com/rfordatascience/tidytuesday/tree/master/data/2023/2023-02-07

### Data Dictionary

|variable     |class     |description  |
|:------------|:---------|:------------|
|stock_symbol |character |stock_symbol |
|date         |double    |date         |
|open         |double    |The price at market open.|
|high         |double    |The highest price for that day.|
|low          |double    |The lowest price for that day.|
|close        |double    |The price at market close, adjusted for splits.|
|adj_close    |double    |The closing price after adjustments for all applicable splits and dividend distributions. Data is adjusted using appropriate split and dividend multipliers, adhering to Center for Research in Security Prices (CRSP) standards.|
|volume       |double    |The number of shares traded on that day.|
