# Olist PBI Dashboard
A PBI dashboard project analysing a Brazilian E-Commerce Company

## Project Overview

Olist is a Brazilian company founded in 2015 and operates as an online e-commerce site that connects shops to wider marketplaces.  
The company is a pioneer in the business model called “marketplace of marketplaces”. It does not hold any inventory or sell products of its own, products are sent directly from merchant stores to clients around the country.

This report will be implemented in Power BI Desktop to analyse the e-commerce performance for the Financial Year 2016 , 2017 and 2018  starting from 15/09/2016 to 03/09/2018. It will generate business insights and investigate improvements to the company’s processes. 
The report will be based on the dataset provided on Kaggle. 
The dataset can be found via this link Brazilian [E-Commerce Public Dataset by Olist | Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

### Main Tables:

● Orders  
● Customers  


### Reference Tables:

● Order Items  
● Products  
● Sellers  
● Payments  
● Reviews  


### Supporting Tables:

● Geolocations  
● Product Category Translations  

A detailed project report and presentation slides can be found in the [Report and Slide folder](https://github.com/stephy416/Olist/tree/main/Reports%20and%20Slides). As the original reviews dataset is in Portuguese, I used google sheets to translate all reviews into English. For a more accurate sentiment analysis. The translated dataset can be found [here](https://github.com/stephy416/Olist/blob/main/olist_order_reviews_with_comment_translated.csv).
A sentiment analysis is performed on the customer reviews. The source code of Jupyter Notebook could be found [here](https://github.com/stephy416/Olist/blob/main/review_cleaning_sentimental_test.ipynb)
