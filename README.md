# Get dataset from KAGGLE : https://www.kaggle.com/competitions/home-credit-default-risk 
# Bank-loan-defaulter-prediction

* An important fraction of the population finds it difficult to get their home loans approved due to insufficient or absent credit history. This prevents them to buy their own dream homes and at times even forces them to rely on other sources of money which may be unreliable and have exorbitant interest rates.
* Conversely, it is a major challenge for banks and other finance lending agencies to decide for which candidates to approve housing loans. The credit history is not always a sufficient tool for decisions, since it is possible that those borrowers with a long credit history can still default on the loan and some people with a good chance of loan repayment may simply not have a sufficiently long credit history
* This is important since a machine learning-based classification tool to predict the loan default risk which uses more features than just the traditional credit history can be of great help for both, potential borrowers, and the lending institutionlT this project will helusme gain an insight into which factors are the most important indicators for a bank when making a loan decision in cassomeone I decide to apply for a housing loan in the future.

# NOTE
* **Due to the size constraint of csv and ipynb files, Uploading web application with dataset is not feasible. Please unzip the folder to get all 7 csv files of various banking data and the code.**

# Key points
 1. The most crucial task in this problem statement is to merge and process all the 7 datasets in a way no data is loss, the relationship and relevancy between each column and table is preserved and a SQL like      
    structure is preserved while model training. Another important factor is feature engineering, as we have more than 120 columns with categorical, float and integer data type all providing information about the 
    data
2. EDA to discover crucial insights on what the data is saying and past cases which tells us a general pattern of people who default their loand or not
   The data is uncleaned, requires computing outliers and null values which may tip the training of model in the worse direction.  
   Normalization is required to improve model accuracy and prevent overfitting
3. Class imbalance is a huge issue in this dataset as the loan defaulters are relatively much lesser , this causes an imbalance and the less complex models usually just predict patterns of the majority class (non      defaulters) which is wrong for our problem statement.
4. Further hyperparameter tuning, gridsearch, bayesian optimization, tweaking more outliers using z-score method etc can be done to improve the model but more epochs and iterations require higher computational power


