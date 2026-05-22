PROBLEM STATEMENT: This project understands how the students's performnce(test scores)(in both regression and catefories wise) is affected by other variables such as Gender , Ethnicity,Parental level of education,Lunch and Test preparation course.

The steps to build the end to end Ml project(Which personally i used):

step 1 : Set up the github (Repository)
         -- New Environmnet
         -- setup.py (To get the application as to packages)
         -- requirements.txt 

step 2 : Created the Components Floder (These are the modules use for the project)
         -- Data Ingestion (Reading the data from some specific source like Data base)
         -- Data Transformation
         -- Model Trainer

step 3 : Created the Pipeline folder 
         -- test pipeline
         -- train pipeline
        also created the logger , exception and utils(Any functionalities which we use in a common way like Mogo , Cloud , you can run the components folder in utils) in the source folder.

step 4 : Written  the Code for my custom Exception handling and the logger.

step 5 : Start the EDA of the dataset and get the insights my case i got the:

- More students achieved full marks in Reading and Writing compared to Mathematics.
- Mathematics has comparatively higher low-score occurrences.
- Reading appears to be the strongest subject overall among students.
- The dataset indicates students struggle more with quantitative subjects than language-based subjects.

step 6: Created the Model training 

Regression models
 Algorithm         
 -----------------  
 Linear Regression 
 Ridge              
 Random Forest     
 Gradient Boosting  
 XGBoost            
 CatBoost          (Modern boosting for categorical data)

 Classification Models
 Algorithm         
 -----------------  
Logistic Regression
Random Forest
XGBoost
CatBoost






