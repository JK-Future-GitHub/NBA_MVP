# NBA_MVP
### ➭ Predicting the last 5 (2018-2022) NBA MVP's using Machine Learning. 

The Most Valuable Player Award (MVP) is an annual National Basketball Association (NBA) award given to the top-performing player of the regular season since the 1955-56 season. I use historical data surrounding an NBA player's basketball season to predict the last 5 MVPs (2018-2022).
My regression model correctly predicted all MVPs!
But what are the stats (features) that have allowed my model to perform so well?

The following picture shows all the work steps that are carried out. I usually combine these steps in a fully automated pipeline, but since this is a side project and my free time is limited, the pipeline is split into 3 files that are executed sequentially.

##### ➤ 1 'nba_html_crawler.ipynb':
- Parse selected Basketball-Reference (Website) pages and save all relevant pages in html-format. 
- [Basketball-Reference](https://www.basketball-reference.com/)

##### ➤ 2 'nba_html_to_mongodb.ipynb':
- Aggregate the data from the html pages and upload it to my MongoDB Cloud account.

##### ➤ 3 'nba_ml.ipynb':
- Predict the last 5 (2018-2022) NBA MVPs with Machine Learning.

##### ➤ Additional 'dashboard.pbix': 
- PowerBI file with a three charts, all three are featured in the 'nba_ml.ipynb' file. 

![](pngs/pipeline.png)


# Article on Medium: 
[Medium](https://medium.com/@thejk/i-will-predict-the-2023-nba-mvp-using-machine-learning-8e7ed688b0d3?source=friends_link&sk=a04c6e064a291493da6a01409449bcdd)<br/>

## 🔗 Links from the Author(Me)
[Portfolio/Website](https://thejk.de/)<br/>
[LinkedIn](https://www.linkedin.com/in/jk05/)<br/>
[Medium](https://medium.com/@thejk)<br/>
[Pinterest](https://www.pinterest.de/thejk_real/)
