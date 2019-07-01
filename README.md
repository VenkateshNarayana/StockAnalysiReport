# StockAnalysiReport
<p align="center">
  <img width="460" height="300" src="Images/images.jpg">
</p>

## INTRODUCTION
Nitin Bhatia and enpert in the Real Estate and Personal Finance who also covers areas like Investment, Insurance, Stocks, Mutual Funds, Credit Score, Taxation, and Business Start-ups. He ofers a blog https://www.nitinbhatia.in which provides an insight on current stocks trending based on which investors can select the stocks which the expert believes to go bullish in the market in the near future.

o	Problem statement: Stock Analysis report for the Future Options was a tedious and cumbersome process of consolidation of the data 
from various sources like price changes, trade values, total trades, delivery position, no of contracts & change in open interests.
	The time spent on these report and manual errors introduced lot of confusion and not so reliable report so that the experts 
could make use of it for their day to day decision making.


| Column Name         | Description  |
| ------------------- |:-------------|
| SYMBOL              | Stock Name                        |
| Nifty 50            | Is a Nifty50 Stock? |
| FO                  | Is Future Stoock Option?                                          |
| P1                  | Price change yesterday                                        |
| P1                  | Price change today|
| NT1                 | No of trades 2 days ago                                          |
| NT2                 | No of trades yesterday            |
| NT3                 | No of trades today|
| C1                  | change in No of trades between 2 days ago and yesterday |
| C2                  | change in No of trades between yesterday and today|
| %C1                 | percentage increase in No of trades 2 days ago and yesterday|
| %C2                 | percentage increase in No of trades between yesterday and today|
| TV 1                | Traded Value in crs 2 days ago |
| TV 2                | Traded Value in crs yesterday                                         |
| TV3                 | Traded Value in crs today |
| C1                  | change in Traded Value between 2 days ago and yesterday |
| C2                  | change in Traded Value between yesterday and today|
| %C1                 | percentage increase in Traded Value 2 days ago and yesterday|
| %C2                 | percentage increase in Traded Value between yesterday and today|
| DQ1                 | Delivery Qty value 2 days ago|
| DQ2                 | Delivery Qty value yesterday |
| DQ3                 | Delivery Qty value today |
| C1                  | change in Delivery Qty between 2 days ago and yesterday|
| C2                  | change in Delivery Qty between yesterday and today|
| %C1                 | percentage increase in Delivery Qty 2 days ago and yesterday|
| %C2                 | percentage increase in Delivery Qty yesterday and today|
| COI1                | Open Interest value yesterday|
| COI2                | Open Interest value today|
| OIC1                | No of Contracts -2 days ago|
| OIC2                | No of Contracts  yesterday|
| OIC3                | No of Contracts today|
| C1                  | change in Contracts between 2 days ago and yesterday|
| C2                  | change in Contracts  between yesterday and today|
| %C1                 | percentage increase in Contracts 2 days ago and yesterday|
| %C2                 | percentage increase in Delivery Qty yesterday and today           |


### CONCLUSION

Created a python script which would pull up the data into a central place and then use this raw information to provide a 
complete reliable report from which decision on stock trading can be done.

### FUTURE CONSIDERATIONS
Below are few things that can be implemented in near future.

  - Automaticlly run the script file to pull the raw data from the different sources and put it in destination and kickoff the generation of the report only when all the data files have been collated.

  
[Jupyter Notebook](.StockAnalysiReport/Stock-Analysis_Report.ipynb)
