# Starbucks Customer Behaviour and Promotional Offer Analysis

## Student Information :-

### 1. Student Name :- Sahil Pathania
### 2. Student ID :- GH10411137
### 3. Module :- B141  Data Mining

## Project Overview :-
In this project, we have applied the techniques of Data Mining for analysing Starbucks Customer Behaviour and promotional offer interactions. A complete workflow is followed in this project, including data understanding, preprocessing, integration, analysis, customer segmentation, and recommendation.

The main focus is to understand customer characteristics, analyse the promotional campaign performance, segmenting customers into meaningful groups and then finally developing a recommendation system using collaborative filtering and cosine similarity as discussed in this module.

## Dataset Description :-
So mainly three datasets from Starbucks are used in this project.
### 1. Profile.csv
 It contains demographic information of customers like Customers ID, Gender, Age, Income and Membership Date
### 2. Porfolio.csv
It contains the promotional offer information like Offer ID, Reward, Difficulty, Duration, Channels and then Offer Type
### 3. Transcript.csv
It contains customer activity Records like Offer received, offer viewed, offer completed and then transactions
The original transcript.csv dataset was not uploaded because it exceeds GitHub's web upload size limit. The dataset can be downloaded from the original Kaggle source:

https://www.kaggle.com/datasets/ihormuliar/starbucks-customer-data

## Project Workflow

### Data Understanding :- 
In this file the datasets were used to explore things like dataset dimensions, data types, column structures, missing values and then dataset relationships.
### Data Preprocessing :-
The activites in Data includes and preprocessing includes removing unnecessary columns, handling missing values, handling age outliers, replacing missing gender and income values and finally creating cleaned datasets.
And the output files are :- profile_cleaned.csv,  portfolio_cleaned.csv,  transcript_cleaned.csv
### Data Integration :-
The datasets which were cleaned were combined using common identifiers. 
The tasks that were included are Extracting Offer IDs, Integrating transcript and portfolio datasets, merging customer profile information and then creating a unified master dataset. At last, we finally created an output file named master_data.csv
### Customer Behaviour Analysis :-
Many analytical techniques were used that included event distribution analysis, offer type analysis, distribution based on gender, age and income and then finally correlation analysis between age and income.

This analysis provided the information about customer demographics and promotional campaign performance.
### Customer Segmentation :-
The customers were grouped using rule-based conditions. 

Age Segments
1. Young Customers
2. Middle-aged customers
3. Senior Customers


Income Segments 
1. Low income
2. Medium income
3. High Income

The file was saved as customer_segmented.csv
## Recommendation System :- 
Collaborative filtering technique was used by me for creating this recommendation system 

Recommendation Process :-

1. Creation of Customer - Offer Matrix
2. Application of Cosine Similarity
3. Generation of an Offer Similarity Matrix
4. Identification of Top Similar Offers
5. Recommendation of similar promotional offers

The recommendation system identifies the promotional offers which are more frequently completed by similar groups of customers. 

And we also the exported the final file named as offer_similarity_matrix.csv

## Technologies Used 

1. Python
2. Pandas
3. Numpy
4. Scikit - Learn
5. Jupyter Notebook

## Output files

The project generated the files which are stated below :-
1. profile_cleaned.csv
2. portfolio_cleaned.csv
3. transcript_cleaned.csv
4. master_data.csv
5. customer_segments.csv
6. offer_similarity_matrix.csv

## Large File Notice

The following files are not included in this repository because they exceed GitHub's web upload size limit:

1. master_data.csv
2. transcript.csv
3. transcript_cleaned.csv

These files can be recreated by running the Jupyter notebooks included in this repository in the following order:

understanding.ipynb
preprocessing.ipynb
integration.ipynb
analysis.ipynb
segmentation.ipynb
recommendation.ipynb

## Conclusion 
This project reflects how the techniques of data mining are used for analysing behaviour of custoemer and promotional campaign data. Through preprocessing, integration, analysis, segmentation, and collaborative filtering, the project gives meaningful customer insights and generates recommendations that are based on customer's interaction with promotional offers. Cosine similarity enables the identification of related offers and support marketing decision having some good data.