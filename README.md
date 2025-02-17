# Web Scraping

Data collection using Web Scraping and preparing the raw data into a clean, structured, and usable format for analysis skincare sales from female daily.

This is a repository to showcase my data analytics skills and projects that i get during my studies using Jupyter Notebook 

# Objectives
- Able to retrieve data from internet sources with Web Scraping.
- Able to perform data preparation before further analysis with Pandas.

---

## Cases

You want to increase your income by selling. However, you do not have enough capital to produce goods and only enough for promotion, so you decide to run a dropship scheme on the Tokopedia platform. 

You are still confused about what to sell and remember that seblak is currently viral. However, you are not sure whether it is true that people have great enthusiasm for seblak. With your skills and knowledge, you want to analyze how seblak products are sold on Tokopedia. Do people like it, do many buy it, etc. 

The challenge is, you have no data at all other than what is displayed on the Tokopedia e-commerce website. Therefore, your journey begins with data collection using Web Scraping!

#### A. Web Scraping
1. Take data from the product keyword search page "seblak".

2. Take data `Product Name`, `Product Price`, `Seller`, `Store City`, `Number Sold`, and `Product Rating`.

3. Tokopedia has a promotion scheme so that the top panel is the product info of a merchant who pays for advertising. We will take the product in a regular box with the element `<div class="css-974ipl">`.

5. Take product information from at least 10 search pages

#### B. Data Preparation
1. Do a simple data exploration:
    - Display several rows of data
    - Display summary information of the data - write the condition of the data structure based on this
2. Make changes to the data in the column containing the product price:
    Take the numbers only, for example `Rp29,000` becomes `29000`. Make sure the data type of this column after the format is changed to integer or float
3. Make changes to the data in the column containing the number of products that have been sold:
    The number of products sold is written as `Sold 750+`, `Sold 1 thousand`. Take the numbers only. For example `Sold 750+` -> `750` and `Sold 1 thousand` -> `1000`. Make sure after the data format is changed, this column is an integer or float data type.
