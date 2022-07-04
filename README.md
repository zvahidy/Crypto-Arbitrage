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

Activate conda dev environment:
![Activate conda dev environment](https://user-images.githubusercontent.com/107367097/177222060-bbe16acc-95cd-496c-aafd-0641b85024fb.png) 

JupyterLab is built into Anaconda therefore, run the following command to launch JupyterLab:
![JupyterLab](https://user-images.githubusercontent.com/107367097/177222194-5217273e-2187-4dea-b640-e175d21fc3b3.png)

JupyterLab user interface does NOT automatically open in a browser window, manually copy the URL provided in the terminal and paste into your browser:
![Interface url](https://user-images.githubusercontent.com/107367097/177222411-4aec31c1-5536-480a-b1fc-3ffb847440b9.png)

Once copied and pasted into your broswer, you will be able to see and use Jupyter Notebook:
![Jupyter Notebook](https://user-images.githubusercontent.com/107367097/177222682-f3073b3c-4d2f-4725-99d2-b1e18ecad9d4.png)
Begin data analysis by importing Panda:
![importing Panda](https://user-images.githubusercontent.com/107367097/177222941-d3f1ff41-8da5-485b-a9af-21c90b1c7021.png)


---

## Results

After cleaning the data files for missing date and duplicates. The data was anlyzed to test the arbitrage opportunies and their potential for profit amoung the two trading platforms; Bitstamp and Coinbase:
![Bitstamp and Coinbase Data](https://user-images.githubusercontent.com/107367097/177223106-ec27f8af-4f49-45ed-9d0f-ca4058c0cac2.png)

Used Visulaizations to determine areas of potential arbitrage
![Bitstamp](https://user-images.githubusercontent.com/107367097/177223619-1d9ec22b-21cb-48a5-ac4b-a70d5b18b42b.png)

![Coinbase](https://user-images.githubusercontent.com/107367097/177223678-c9b02016-c58d-4871-b666-1a72621cef14.png)

Data was overlayed to determine discrepancies in prices in these exchanges where arbitrage opportunities lay:
![overlay Bitstamp vs Coinbase](https://user-images.githubusercontent.com/107367097/177223722-511106be-3f07-4253-90fa-c59a8a1923e9.png)

Data was seperated into three segments: Early, Middle and Late to show the effect of time over arbitrage opportunities and their profitability:
![Early](https://user-images.githubusercontent.com/107367097/177223810-00f7edc3-905c-4234-a2fd-05254e47164c.png)
![Middle](https://user-images.githubusercontent.com/107367097/177223841-f5961414-d629-4319-84be-600c1f194085.png)
![Late](https://user-images.githubusercontent.com/107367097/177223949-3eeb5c6d-c8f1-4f19-ad6c-72f12443fcfd.png)
Trades that showed profitability:
![profitability](https://user-images.githubusercontent.com/107367097/177224140-057fe042-06d7-4af1-80a4-f60873301165.png)


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
