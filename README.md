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