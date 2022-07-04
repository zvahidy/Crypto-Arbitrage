# Crypto-Arbitrage# Loan_Qualifier

I currently work as an analyst at a high-tech investment firm and the vice president is considering arbitrage opportunities in Bitcoin and other cryptocurrencies. Simultaneous price dislocations across Bitcoin trades can create oppotunities to buy and sell and make profits. So by using pandas to analyze data, will reveal the potential profits in those markets.

I will be sorting through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase to locate arbitrage opportunities that may exist for Bitcoin. .

---

## Technologies
###### Resource 
- Data Availabe for download:
    -Bitstamp http://localhost:8888/lab/tree/Resources/bitstamp.csv
    -Coinbase http://localhost:8888/lab/tree/Resources/coinbase.csv
###### Tools
Jupyter Lab
- Jupyter Notebook
- Pythons and Pandas Libraries

    

---

## Installation Guide

Installation requirements for this project included Pyton and Panda Libraries and JupyterLab (See Appendix)

Activate conda dev environment:
![Activate conda dev environment](http://localhost:8888/lab/tree/Screenshots/conda_activate_dev.png) 
![JupyterLab is built into Anaconda therefore, run the following command to laund JupyterLab](http://localhost:8888/lab/tree/Screenshots/jupyter_lab_command.png)
![JupyterLab user interface does NOT automatically open in a browser window, manually copy the URL provided in the terminal and paste into your browser](http://localhost:8888/lab/tree/Screenshots/access_link_to_browser.png)
![Once pasted into your broswer, you will be able to see and use Jupyter Notebook](http://localhost:8888/lab/tree/Screenshots/jupyter_notebook.png)
![Begin data analysis by importing Panda](http://localhost:8888/lab/tree/Screenshots/Import_pandas.png)


---

## Results

![After cleaning the data files for missing date and duplicates. The data was anlyzed to test the arbitrage opportunies and their potential for profit amoung the two trading platforms; Bitstamp and Coinbase](http://localhost:8888/lab/tree/Screenshots/Summary_stats_bitstamp_and_coinbase.png)
![Used Visulaizations to determine areas of potential arbitrage](http://localhost:8888/lab/tree/Screenshots/bitstamp_plot.png)
![](http://localhost:8888/lab/tree/Screenshots/Coinbase_plot.png)
![Data was overlayed to determine discrepancies in prices in these exchanges where arbitrage opportunities lay](http://localhost:8888/lab/tree/Screenshots/bitstamp_vs_coinbase_plot.png)
![Data was seperated into three segments: Early, Middle and Late to show the effect of time over arbitrage opportunities and their profitability](http://localhost:8888/lab/tree/Screenshots/overlay_plot_early.png)
![](http://localhost:8888/lab/tree/Screenshots/overlay_plot_middle.png)
![](http://localhost:8888/lab/tree/Screenshots/overlay_plot_late.png)
![Only the early segment indicate profitable trades](http://localhost:8888/lab/tree/Screenshots/profitable_trades.png)


Final Analysis: indicated that in the early dataset there were several arbitrage opportunities a count of 1379, in the middle it was reduced to 1039 and in the late 937 which shows a pattern of decreased opportunities as time progresses. Also indicated is the profitabilty as time progressed was reduced as well. In January there were 742 profitable trades however the datasets for middle and late show there were no profitable trades. Once again as time progressed the profitable arbitrage opportunities declined and infact, ceased. There are very little opportunities for arbitrage in Bitcoin now that the exchanges tend to price the same. Further research could be performed amoungst other exchanges, however it is more likely that arbitrage opportunities are more prevelant in newer cryptocurrencies that are and will emerge. New traders will seek arbritrage opportunities which over time will shrink profits as new traders will over saturate the market decreasing its potential to profit. 

---

## Contributors

#### Contact
zehra.vahidy@gmail.com
LinkedIn https://www.linkedin.com/in/zehra-vahidy-6025b820

---

## License

Unlicesened

## Appendix
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings
https://jupyterlab.readthedocs.io/en/stable/
