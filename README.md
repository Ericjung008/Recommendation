# Recommender System
This is a project assigned to me during [theDevMasters](https://www.thedevmasters.com) bootcamp.<br> 

## Introduction
E-commerce companies are looking to generate incremental sales by implementing a recommender system. With item-item filtering, similar products can be recommended to users. This results in more purchases by customers and increase in the company's revenue. 

## Objective
The objective of this project is to recommend similar products to customers.

## Metric 
Cosine similarity was the metric used for this project. The metric measures how similar text data are irrespective of their size. The formula is shown below:
<img width="215" alt="Screen Shot 2020-10-22 at 9 07 29 PM" src="https://user-images.githubusercontent.com/51253177/96955661-f86fbb80-14aa-11eb-8b61-b4a3dbff17dd.png">

## Approach
The following steps were taken to complete the project:
1. Import libraries and dataset.
2. Export dataset into SQL database.
3. Import dataset from SQL database.
4. Analyze which columns to use.
5. Fill in missing values.
6. Find most popular products.
7. Find companies with highest purchase.
8. Find highest selling products.
9. Preprocess text data.
10. Create a TF-IDF Dataframe.
11. Apply cosine similarity to find similar products based on product ID.

## Technologies
Applications: Jupyter Notebook, MySQL<br>
Programming Language: Python 3.7.4<br>
Libraries: Numpy, Pandas, Sqlite3, Pickle, Re, Autocorrect, NLTK, Scikit-learn <br>

## Project Files
[README](https://github.com/Ericjung008/Customer-Segmentation/blob/master/README.md)<br>
[Project - SQL](https://github.com/Ericjung008/Recommendation/blob/main/Recommendation%20-%20SQL.ipynb)<br>
[Project - Cleaning & Analysis](https://github.com/Ericjung008/Recommendation/blob/main/Recommendation%20-%20Cleaning%20%26%20Analysis.ipynb)<br>
[Project - Cosine Similarity](https://github.com/Ericjung008/Recommendation/blob/main/Recommendation%20-%20Cosine%20Similarity.ipynb)<br>
[Dataset](https://github.com/Ericjung008/Recommendation/blob/main/data.csv)<br>
