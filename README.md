# Yahoo-Finance-Scraper
This scraper scraped for all the mentioned companies for their stock open, close, daily high, and low values along with the Adj close and volume traded that day
This scraper is capable of scraping the below-mentioned stocks
1. Apple- AAPL
2. Tesla- TSLA
3. Meta- META
4. Microsoft- MSFT
5. Netflix- NFLX
6. Amazon- AMZN
7. Google- GOOG
8. IBM- IBM
9. Adobe- ADBE
10. Dell- DELL
11. Uber- UBER

There are many other alternative approaches to get the finance data from Yahoo which include using the direct Python yfinance module and retrieving the finance data for a certain mentioned time frame. using Yfinance retrieves the data automatically into a Pandas DataFrame whereas this scraper constantly inserts the data to the Database directly without needing to use a data frame.  

I have also mentioned the code for the data extraction using the yfinance module in python. In the notebook there are two approaches to saving the data, first method saved the csv files to a google drive folder, (folder name Stocks Data to be created before running or might cause errors) other method is Google Colab saves the CSV files in its workspace and user can use Pandas library to use those CSV files by converting them into a DataFrame and do Analysis and predictions. 
