## Problem Statement 

Birth control medication is taken to treat issues ranging from acne prevention, anxiety/depression, pregnancy prevention and more. While birth control can be effective in certain ways, there are a lot of potential issues and negative side effects, which influence its user satisfaction.

The goal of this project is to focus on the medication YAZ, a specific form of birth control, and analyze its user satisfaction. The end product is a text classification model to predict if reviews on YAZ as a birth control are positive, negative, or neutral.

## Data Extraction

723 YAZ reviews were scraped from the following WebMD drug review page: https://reviews.webmd.com/drugs/drugreview-95358-yaz-28-oral. 
All Condition Reviews were used (reasons for taking YAZ) which include the following: Birth Control, Acne, Premenstural Disorder with a State of Unhappiness.

The data was scraped using BeautifulSoup shown in YAZ_web_crawler.ipynb. 

## Manual Labeling of the Data

The scraped data was manually labeled 1, 0, and -1 for positive, neutral, and negative respectively. The records were labeled three times each by different individuals, and the most common rating was chosen for that respective record. 

## Data Preprocessing

The data was checked for imbalance and cleaned as shown by Data_Pre_processing.ipynb. 
Feature extraction was performed and then the data was split into testing and training sets. 

## Modeling 











