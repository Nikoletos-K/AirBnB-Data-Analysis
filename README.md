# Data exploration
---
__Language:__ python > 3.0

__Data:__ The data of this project come from AirBnB.Specifically, there's a directory named data,which contains directories Aril,March and February.These directories have information from AirBnB platform such as id,zipcode,transit,Bedrooms,Beds,Review_scores_rating,Number_of_reviews,Neighbourhood,etc.

This project consists of __2 main queries.__ 

## 1st Query | Data exploration

Using simple and common functions such as groupby,sum,count,etc and plotting the results into multiple and various plots in order to make assuptions and get some results .
Also,query 2 consist of 11 subqueries that are written as comments in the notebook.

## 2nd Query | Recommendation System
Experimenting with vectorazation (TF-IDF,BoW) and cosine similarity
Isolation of columns id,name,description from given airbnb files and text processing.More specifically Q.2 consists of:

__Subqueries:__
1. __TF-IDF,BoW Vectorazation :__ Vectorazation of the three isolated columns
2. __Cosine Similarity :__ Calculating the similarity between every element of tf-idf with all the others
3. Function that finds and returns the __most similar entries__ given an id
