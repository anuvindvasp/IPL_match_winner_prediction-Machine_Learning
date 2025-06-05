# IPL Match Winner Prediction

![image](https://github.com/user-attachments/assets/94e6b5a2-c229-4893-bbff-be4a6f41dd93)

## INTRODUCTION

The Indian Premier League (IPL) is one of the world’s most popular and competitive professional T20 cricket leagues. The franchise-based teams representing Indian cities/states with top International and Domestics players

The aim of this project is to predict the winner of an IPL match based on various features such as the teams playing, toss winner, toss decision, and other match    related factors.
using different machine learning models like Logistic Regression, SVM, KNN, Decision Trees, Random Forest, and XGBoost.
The best model must be selected after evaluating the performance and hyperparameters must be tuned for further improvements.


## WORK FLOW

### 📥 DATA COLLECTION
   * Data was sourced from publicly available IPL datasets on Kaggle
   * The dataset includes IPL match details such as team lineups, match venues, toss outcomes, past performance, and other key features
     
### 🧹 DATA PREPROCESSING
   * Cleaned the data by handling missing values and ensuring consistency for accurate analysis and modeling.

### 📊 EXPLORATORY DATA ANALYSIS (EDA)
   * Performed EDA to identify important trends, patterns, and insights within the IPL match data.

### ⚙️ MODEL BUILDING

   :white_small_square: Used classification algorithms:

   
      ○ Logistic Regression

      ○ Support Vector Machine (SVM)
   
      ○ K-Nearest Neighbors (KNN)
   
      ○ Decision Trees
   
      ○ Random Forest
   
      ○ XGBoost
   

### 🔧 HYPERPARAMETER TUNING
   *  Tuned using Grid Search
   *  Randomized Searchcv

### 🏁 MODEL EVALUATION & SELECTION
   * Accuracy, Precision, Recall, F1-Score
   * Confusion Matrix

### 💾 MODEL SAVING
   * Saved Final Model as .pkl

## Results and Conclusion

   ○ Trained and compared multiple models; XGBoost delivered the   best performance after hyperparameter tuning
   ○ Achieved high scores in accuracy, precision, recall, and F1-score, indicating strong predictive capabilities.

### Potential Future Work

* Implement deep learning models like RNNs or LSTMs to consider time-based performance patterns.

* Create a real-time prediction tool using web scraping and a live dashboard (e.g., Streamlit or Flask).

* Use ensemble techniques (blending XGBoost, Random Forest, etc.) to boost predictive power.

* Explore feature importance to better understand the key drivers of match outcomes.


