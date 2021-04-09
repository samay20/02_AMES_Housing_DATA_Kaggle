# Project 2 - Ames Housing Data and Kaggle Challenge




## Problem Statement

**Create a regression model based on the Ames Housing Dataset to predict the price of a house at sale.**
+ Use test dataset to submit predictions for select houses



## Executive Summary

### Contents:

- [Data Dictionary](#Data-Dictionary)
- [Import Libraries](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#Import-Libraries)
- [EDA Step1: Check for datatypes and missing values](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#EDA-Step1:-Check-for-datatypes-and-missing-values)
- [EDA Step 2: Plot and Clean dataset](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#EDA-Step-2:-Plot-and-Clean-dataset)
- [EDA Step 3: Multivariate Analysis](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#EDA-Step-3:-Multivariate-Analysis)
- [EDA Step 4: Feature Engineering - Create Dummy Variables](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#EDA-Step-4:-Feature-Engineering---Create-Dummy-Variables)
- [EDA Step 5: Export Datasets to create models](SamayShah_Project2(Main_TRAIN)_DataCleaning_Train_Dataset.ipynb#EDA-Step-5:-Export-Datasets-to-create-models)
- [FINAL MODEL Dataset Export - Model#4](SamayShah_MODEL%234__FINAL_MODEL__.ipynb)
- [TRAIN using FINAL MODEL](SamayShah_MODEL%234__FINAL_MODEL__.ipynb)



## Project Flow

**1 TRAIN DATASET FILE**

+ Main File contains train dataset and other EDA. Should not be modified.

**1 TEST DATASET FILE**

+ File to try test datasets. Copy .csv file containg housing information to predict in the 'datasets' folder. Name your file as 'test.csv' or else you can change the file path in cell#3 of test file. Run call cells and close the file.

**4 MODELS**

+ Use Model#4 as main file to predict prices. Run this file after running your test file and it will generate a .csv in the main folder. (default file name: 'Model4_Predicted_SalePrices_Test_Dataset.csv'

**1Dataset Folder**

+ Main Folder contains all the datasets for train.csv. (##do not alter)
+ 'Test' folder contains all the datasets for test.csv

**Readme File**

+ Brief information about the project and workaround.


## Data Dictionary

<center><strong><span style="color:maroon"> Ames Housing Data and Kaggle Challenge | DATASET: Train.csv </span></strong></center>
 
<center>Note: All Ratings are converted to fit 0 to 5 or 1 to 5 scale, with 5 being highest and 0 / 1 being the lowest</center>


|Feature|Type|Description|
|---|---|---|
|Id|int64| Id - Unique Column to match with Test.csv |
|PID|int64|PID - Purchase ID unique values | 
|MS Subclass|int64|Building Class | 
|MS Zoning|object|Zoning Classification | 
|Lot Frontage|int64| Linear feet of street connected to property |
|Lot Area|int64| Total Area on Sq.Ft. |
|Neighbourhood|object|Physical locations within Ames city limits| 
|Overall Qual|int64| Overall material and finish quality | 
|Overall Cond|int64| Overall condition rating| 
|Roof Style|object|Type of roof|
|Exterior 1st|object| Exterior covering on house |
|Exterior 2nd|object|Exterior covering on house (if more than one material) | 
|Exterior Qual|int64|Exterior material quality | 
|Exter Cond|int64| Present condition of the material on the exterior | 
|Bsmt Exposure|int64|Walkout or garden level basement walls|
|BsmtFin Type 1|int64|Quality of basement finished area |
|BsmtFin Type 2|int64|Quality of second finished area | 
|Total Bsmt SF|int64|Total square feet of basement area| 
|Heating QC|int64|Heating quality and condition| 
|Bedroom AbvGr|int64|Number of bedrooms above basement level|
|Fireplaces|int64|Number of fireplaces | 
|Garage Cars|int64|Size of garage in car capacity | 
|Garage Qual|int64|Garage material and finish quality|
|Garage Cond|int64| GARAGE condition rating |
|Mo Sold|int64|Month Sold | 
|Yr Sold|int64|Year Sold | 
|Sale Type|object|Type of sale: Warranty Deed, Contract or other | 
|Street_isPaved|int64|Boolean|
|Lotshape_isRegular|int64|Boolean |
|isLandLevel|int64|Boolean | 
|Exterior Qual|int64|Exterior quality of the house | 
|isLotInside|int64|Boolean | 
|isLotCorner|int64|Boolean|
|isLotCulDSac|int64| Boolean |
|isSlopeNormal|int64|Boolean | 
|proximity_to|object|Proximity to Main road or Rail road | 
|Density|object|Residential Density | 
|House_style|object|Style of dwelling|
|Bldg_type|object|Type of Dwelling 1Family, 2Family, Townhouse or Duplex | 
|isgood_overall|int64|Boolean | 
|is_remodeled|int64|Boolean|
|is_roofGable|int64| Boolean |
|has_masonryveneer|int64|Boolean | 
|hasgood_Exterior|int64|Boolean | 
|hasgood_Basement|int64|Boolean | 
|has_Basement|int64|Boolean|
|is_fullfurnished|int64| Boolean |
|has_gasFurnace|int64|Boolean | 
|has_centralAir|int64|Boolean | 
|total_full_baths|int64| Number of full bathrooms | 
|total_half_baths|int64|Number of half bathrooms|
|has_1pluskitchen|int64| Boolean |
|has_goodkitchen|int64|Boolean | 
|is_fullyfunctional|int64|Boolean | 
|has_fireplace|int64|Boolean | 
|has_detachedGarage|int64|Boolean|
|has_Garage|int64|Boolean | 
|has_goodGarage|int64|Boolean | 
|has_paveddriveway|int64|Boolean|
|has_pool|int64| Boolean |
|has_woodDeck|int64|Boolean | 
|has_Porch|int64|Boolean | 
|has_miscFeatures|int64|Boolean | 
|has_goodFence|int64|Boolean|
|Foundation|object|Foundation categories for a house | 
|isNeigh_collgcr_oldtown|int64| Boolean |
|is_densityHigh|int64|Boolean | 


## Future Scope:

Model could futher be trained using several polynomial features.





Thankyou
@@@@@@@@@@@@ Samay Shah @@@@@@@ General Assembly @@@@@@@@@ Project-2 @@@@@@@@@ Samay Shah @@@@@@@@