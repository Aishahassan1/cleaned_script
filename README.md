1) I need to upload the raw data files from desktop to dropbox. In readme include that user needs to download the files into the cleaning script main folder 


# Consumer Behaviour - Sales Analyis Dashboard

Data analysis and clean up done using Jupyter notebook

## Table of Contents

- Introduction
- Technologies used
- Wireframes and user stories
- Images
- Development process and data cleaning and transformation
- Unsolved problems
- Favourite functions

## Introduction

I was presented with 10 years of sales data that I had to clean and concatenate into one big data frame. This cleaned data then needed to be turned into a dashboard where the end user could vizualise the data.

## Technologies used


## Wireframes and user stories

## Images

## Development process and data cleaning and transformation

1st I cleaned up the date using Jupyter notebook. 
I installed numpy, pandas and petl then imported them as np, pd and etl respectively (SAY WHY I INSTALLED EACH OF THEM)

I then imported one file at a time to work on and started the clean up operation.

I decided to use the petl library to perform the analysis on my data so as to prevent me having to change the data back and forth between pandas and pets as this was time consuming.

I didn’t check for Nan’s because the data was collected by non-technical people and therefore we can assume that they wouldn’t have inputed this in any field.

I used the isnumeric() method to check the numeric columns for input that is not a number so they can be removed. The two columns that didn’t have data were quantity_purchased and amount_in_gap. With each operation I ran the function etl.nrows() to count the number of rows to see if there were rows removed due to the selected column having fields that were invalid.


## Unsolved problems

## Favourite functions
