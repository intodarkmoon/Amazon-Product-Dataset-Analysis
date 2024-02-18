# Amazon-Product-Dataset-Analysis
Analysis of Amazon Product Dataset 2023. This dataset contains several columns which is :
* Product ID : Product ID from Amazon. (type:str)
* Product Title : Title of the product. (type:str)
* ImgURL : Url of the product image. (type:str)
* ProductURL : Url of the product. (type:str)
* Stars : Product rating. If 0, no ratings were found. (type:float)
* Reviews : Number of reviews. If 0, no reviews were found. (type:int)
* Price : Buy now price of the product. If 0, price was unavailable. (type:float, currency: USD)
* listPrice or Original Price : Original price of the product before discount. If 0, no list price was found AKA, no discounts. (type:float, currency: USD
* Category_ID : Use the amazon_categories.csv to find the actual category name. (type:int)
* isBestSeller : Whether the product had the Amazon BestSeller status or not. (type:bool)

## Table of Contents
* [Introduction](#introduction)
* [Technologies](#technologies)

## Introduction
This project is one of my portfolio projects which aims to analyze bundesliga 2023 player data from [Kaggle](https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products?select=amazon_products.csv). In this project I carried out several stages in conducting data analysis. These stages are
* Perform data cleaning and data transformation with PostgreSQL
* Perform data analysis with PostgreSQL
* Perform data visualization with Power BI

## Technologies
This project is created with :
* PostgreSQL
* Power BI
