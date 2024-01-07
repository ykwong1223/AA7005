#Basic Flow-
churn_1.csv and churn_2.csv are my raw files. They are integrated uisng OngYiKwong_S2181260_talend_integration_0.1.properties.

churn_final_yk.csv is produced and changed to xlsx.

OngYiKwong_S2181260_sas.xml is used to sample and output em_save_TRAIN.xlsx

Then OngYiKwong_S2181260_talend_prep.json is used to produce em_save_TRAIN PREPARATION(1)(1).xlsx

Then OngYiKwong_S2181260_sas.xml is used again.

#Project overview-
Objective: Predict customer churn in e-commerce platform
Talend_Integration: Integrate Datasets
Talend_preparation: Clean dataset
SAS Miner: Perform SMMA

#SAS-
Models are built usingg right clcik->add nodes -> Models

#Talend Integration-
Use Inputdelimited to input csv, use tmap to combine and outputdelimited to output

#Talend_Prep-
Use fill missing values to handle missing values. Use search and replace to replace data inconsistency

#Results & Discussion-
Gradient Boosting is better. Business must focus on cashback amount, services and delivery time.

#Refelction-
Learn how to apply 3 tools and ML to slove pratical issues
