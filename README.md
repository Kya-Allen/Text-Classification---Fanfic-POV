# Text Classification - Fanfic POV
Classifying Fanfiction from Archive of Our Own (Ao3) as either First, Second, or Third Person using Statistical/Machine Learning Algorithms
## Current Content:
  * Notebook on Data Extraction
     * Used Archivist.py to scrape Work Id's and first chapter tests from Ao3
  * Notebook on Cleaning & Feature Engineering
     * Removed html artifacts from text. 
     * Tokenized by words and by sentences. 
     * Created features based on frequency ratios for key words that 1. appear anywhere 2. begin a sentence 
  * Notebook on training ML models
      * Logistic Regression: 86% Accuracy
      * K Nearest Neighbors: 93% Accuracy
       *  <img src="https://github.com/Kya-Allen/Text-Classification---Fanfic-POV/blob/main/Data/LogReg.PNG" width="350" height="350"> <img src="https://github.com/Kya-Allen/Text-Classification---Fanfic-POV/blob/main/Data/KNN.PNG" width="350" height="350">
## Planned Directions:
  * Implement more models:
    * Random Forest
    * Boosting
  * Productionize model for a browser extention for Ao3 users
  * Investigate Features that might allow the model to differentiate between Third Person Subtypes (i.e. Limited, Omniscient) 
