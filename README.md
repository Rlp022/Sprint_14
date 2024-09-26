# Sprint_14

# Automated Sentiment Analysis for Movie Reviews

## Introduction 
The Film Junky Union, a vibrant community of classic movie enthusiasts, initiated a project to develop a system for filtering and categorizing movie reviews. Their goal was to create a model capable of automatically detecting negative reviews. Using an IMDb movie reviews dataset labeled by sentiment polarity, the objective was to build a model that could classify reviews as positive or negative with an F1 score of at least 0.85.

## Table of Contents

### Data Loading and Preprocessing
### Exploratory Data Analysis (EDA) and Modeling Preprocessing
### Model Training and Evaluation
### Model Testing and Conclusion

## 1. Data Loading and Preprocessing 
The first step involved loading the dataset from the 'imdb_reviews.tsv' file and preparing it for analysis. Preprocessing tasks included removing unwanted characters, converting text to lowercase, tokenization, and lemmatization to ensure the data was clean and ready for modeling.

## 2. Exploratory Data Analysis (EDA) and Modeling Preprocessing
Exploratory Data Analysis (EDA) was performed to understand the class distribution within the dataset, revealing a noticeable class imbalance. This insight informed the choice of evaluation metrics and strategies to address the imbalance during model training.

Further preprocessing involved converting the text data into numerical formats suitable for machine learning algorithms, employing techniques such as Bag-of-Words or TF-IDF.

## 3. Model Training and Evaluation
Multiple models were trained on the dataset, with Logistic Regression and Gradient Boosting being among the recommended approaches. However, flexibility was allowed to experiment with various methods. The models were evaluated using the F1 score to ensure they met the project's performance target.

## 4. Model Testing and Conclusion  
 The trained models were tested on a new set of reviews, and the results were compared and analyzed. A performance summary revealed that the Logistic Regression model, when trained on data lemmatized with Spacy and DistilBERT, underperformed relative to others. In contrast, models trained on data lemmatized with NLTK showed better results.

Despite the strong performance of the models, there remains potential for further improvement, particularly through more refined hyperparameter tuning.

Overall, the project was successful, achieving the goal of building models that accurately classify movie reviews as positive or negative, thereby meeting the Film Junky Union's requirements.
