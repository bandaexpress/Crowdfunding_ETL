# Crowdfunding_ETL
Project 2 from Columbia University Data Analytics Bootcamp

# Authors
- Daniel Kenet - Category and Subcategory DataFrames
- Jarret Baum - Campaign DataFrame
- Emily Sims - Contacts DataFrame
- Anthony Banda - Crowdfunding Database


# Requirements

## A Category DataFrame is Created (15 points)
- The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories (5 points)
- The DataFrame has a "category" column that contains only the category titles (5 points)
- The category DataFrame is exported as category.csv (5 points) See category.csv file in Resources folder: https://github.com/bandaexpress/Crowdfunding_ETL/blob/9f9f992a88d2fefe0a3493c7f538ea0c81515ff5/Resources/category.csv

## A Subcategory DataFrame is Created (15 points)
- The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories (5 points)
- The DataFrame contains a "subcategory" column that contains only the subcategory titles (5 points)
- The subcategory DataFrame is exported as subcategory.csv (5 points) See subcategory.csv file in Resources folder: https://github.com/bandaexpress/Crowdfunding_ETL/blob/095da255766a639718cb9f7e20dfd5c089fa4d72/Resources/subcategory.csv

## A Campaign DataFrame is Created (30 points)
- The DataFrame has the following columns: (25 points)
  - A "cf_id" column
  - A "contact_id" column
  - A "company_name" column
  - A "description" column
  - A "goal" column that is a float data type
  - A "pledged" column that is a float data type
  - An "outcome" column
  - A "backers_count" column
  - A "country" column
  - A "currency" column
  - A "launch_date" with the time formatted as "YYYY-MM-DD"
  - An "end_date" with the time formatted as "YYYY-MM-DD"
  - A "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
  - A "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
  - The campaign DataFrame is exported as campaign.csv (5 points) See campaign.csv in Resources folder: https://github.com/bandaexpress/Crowdfunding_ETL/blob/490de93a472b1860d2fc70666bbc834c0a779803/Resources/campaign.csv

## A Contacts DataFrame is Created (15 points)
- The DataFrame has the following columns: (10 points)
  - A "contact_id" column
  - A "first_name" column
  - A "last_name" column
  - An "email" column
  - The contacts DataFrame is exported as contacts.csv (5 points) See contacts.csv file in Resources folder: https://github.com/bandaexpress/Crowdfunding_ETL/blob/0417a660795c6b3cbff3dc7314dbbe7b8f51b979/Resources/contacts.csv

## A Crowdfunding Database is Created (25 points)
- A database schema labeled, crowdfunding_db_schema.sql is created (5 points)
- A crowdfunding_db is created using the crowdfunding_db_schema.sql file (5 points)
- The database has the appropriate primary and foreign keys and relationships (5 points)
- Each CSV file is imported into the appropriate table without errors (5 points)
- The data from each table is displayed using a SELECT * statement (5 points)

# References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
