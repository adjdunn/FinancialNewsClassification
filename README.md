# Financial News Classification
This is a natural language processing, multi-class, text classification project on financial news data. The project will test 3 machine learning algorithms (AdaBoost, Logistic Regression and Support Vector Machines) to classify financial news release titles into 5 different categories (financial release, earnings announcement, acquisition, dividend, dividend increase and misc). 

The goal of this project is to improve the ease and efficiency of reading through financial news releases. Financial analysts and investors use news releases to stay informed and make assessments regarding a company's future financial performance and investment return potential. In any given day, thousands of news releases can be distributed with only a small portion containing useful information. Classifying news releases saves time and improves outcomes by filtering noise and focusing attention on important information. Classification can also be the first step before additional ML and NLP technique are applied, including text summarization, sentiment analysis and information extraction. 

The dataset was personally created by me for the purpose of researching NLP techniques on financial news and related data. I created this dataset by web scraping new release headlines from various public RSS feeds of news release providers. I then personally annotated each sample as belonging to 1 of 6 different classes. 

The categories Financials, Increased Dividend and Acquisition contain information which can be relevant to the future financial and investment performance of a company. The categories Dividend, Earnings Announcement and Misc, generally contain information which is already known or not relevant to future performance.


| Category             | Description                                                       | Important Information |   
|----------------------|-------------------------------------------------------------------|-----------------------|
|Financials            | Quarter and annual financial reporting and outlook.               |         Yes           |
|Increased Dividend    | Dividend or distribution increase annoucement.                    |         Yes           |
|Acquisition           | Acquisition or major asset purchase annoucement.                  |         Yes           |
|Dividend              | Declaration of existing, regular dividend.                        |          No           |
|Earnings Announcement | Announcement of financial results to be released at future date.  |          No           |
|Misc                  | Lawsuits, conferences, management changes, regulatory, etc.       |          No           |
