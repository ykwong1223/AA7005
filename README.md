# Project overview-
Objective: Predict customer churn in e-commerce platform using folloeing 3 tools and Machine Learning.

Dataset: Obtained from Kaggle.

Talend_Integration: Integrate Datasets

Talend_preparation: Clean dataset

SAS Miner: Perform Sample, Modify, Model and Assessment

# Basic Flow-
1) churn_1.csv and churn_2.csv are my raw files. They are integrated uisng OngYiKwong_S2181260_talend_integration_0.1.properties.

2) churn_final_yk.csv is produced and changed to xlsx.

3) OngYiKwong_S2181260_sas.xml is used to sample and output em_save_TRAIN.xlsx

4) OngYiKwong_S2181260_talend_prep.json is used to produce em_save_TRAIN PREPARATION(1)(1).xlsx

5) OngYiKwong_S2181260_sas.xml is used again.

# SAS-
Sample right click-> add nodes -> Sample

Explore right click-> add nodes -> StatExplore/GraphExplore

Models right clcik-> add nodes -> Models

Assessment right click -> add nodes -> Models Comparison

# Talend Integration-
Use "FileInputDelimited" to input csv, use "tMap" to combine and "tFileOutputDelimited" to output

# Talend_Prep-
Use "fill missing values with..." to handle missing values. Use "Search and Replace" to replace inconsistent data

# Results & Discussion-
Gradient Boosting is the best prediction model comapred to Decision Tree and Random Forest. E-commerce business must focus on their cashback amount, services and delivery time.

# Refelction-
Learn how to apply 3 tools and Machien Learning to slove pratical issues. Challenges are the dataset is unbalanced. Methods like SMOTE can applied to further improve performance.
