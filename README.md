# Hi :raised_hand: , My name is Ivan!
### I am a Data Anslyst from Russia. If you want to contact me, feel free to contact me: 
* via Telegram: https://t.me/ivan_aksyonov
* via email: ivan_aksyonov@inbox.ru
### This is my portfolio for data analytics projects:


1) [Cohort Analysis](https://github.com/IvanAks777/My_Portfolio/blob/main/Cohort_Analysis/cohort_analysis_project.ipynb "Cohort Notebook")
   The project involves the Cohort Analysis of Retention Rate by Day. In short you can check out  the resulted  [Cohort graph](https://github.com/IvanAks777/My_Portfolio/blob/main/Cohort_Analysis/data/Cohort.png "Cohort Heatmap")
   * 1.1
2) [RFM Analysis](https://github.com/IvanAks777/My_Portfolio/blob/main/Olist%20E-commerce%20metrics%20and%20RFM%20analysis/aksyonov_project.ipynb "E-commerce and RFM") is my project about real e-commerce data getting from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). The stages of analysis:
   * 2.1 Data Preprocessing(cleaning) and merging (denormalization).
   * 2.2 EDA - Exploritary Data Analysis
   * 2.3 Calculate and Visualize essential metrics of e-commerce(Revenue, ARPU, AOV, CLTV, top categories in terms of order and revenue). I start by time series analysis of Revenue: monthy, daily and rolling daily aggregation. Then find the percentage of growth year over year. Next, calculate ARPPU by month and daily rolling. After that, I count the number of orders per customer. Finally, I check out top categories in terms of orders and revenue.
   * 2.4 I segment the customers using RFM analysis. The [RFM Segments Treemap](https://github.com/IvanAks777/My_Portfolio/blob/main/Olist%20E-commerce%20metrics%20and%20RFM%20analysis/pictures/newplot.png 'RFM Segments Treemap Picture') and [RFM Segments Treemap by ARPPU](https://github.com/IvanAks777/My_Portfolio/blob/main/Olist%20E-commerce%20metrics%20and%20RFM%20analysis/pictures/newplot%202.png 'RFM Segments by ARPPU') are my final visualization for different customer segments. However, first I calculate: the most recent purchase(recency), the number of purchase(frequency) and the sum of money spent(monetary). Then I separate customers into groups form 1 (more than 6 month, only 1 purchase and money less 100) to 3(less than 3 month, 5+ purchase, money spent more 400). After that I refer them to one of the categories:'Lost customers','Need Attention','Newcomers', 'Potential champions', 'Champions & Loyal'. Finally, I create a treemap based on the categories.
   * 2.5 I write down my recommendations how to deal with each separate category and where to focus the efforts to boost revenue.
