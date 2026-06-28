# Amazon Alexa Sentiment Analysis

## Project Overview
This project applies Natural Language Processing (NLP) and machine learning techniques to classify Amazon Alexa customer reviews as positive or negative. The project uses customer review text, product variations, and sentiment feedback to build and evaluate a Random Forest classification model.

## Dataset
The dataset used in this project is the Amazon Alexa Reviews dataset. It contains approximately 3,150 customer reviews with the following columns:

- rating
- date
- variation
- verified_reviews
- feedback

The target variable is `feedback`, where:
- `1` represents a positive review
- `0` represents a negative review

## Objectives
- Load and explore the Amazon Alexa review dataset
- Clean and preprocess the data
- Visualize feedback distribution and product variation ratings
- Apply one-hot encoding to categorical variables
- Convert review text into numerical features using CountVectorizer
- Train a Random Forest classification model
- Evaluate the model using confusion matrix and classification report
- Analyze feature importance
- Predict sentiment for new customer reviews

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Workflow
1. Import libraries and load the dataset
2. Explore the dataset structure
3. Check missing values and duplicates
4. Visualize feedback distribution and product variation ratings
5. Drop irrelevant columns
6. Apply one-hot encoding to the product variation column
7. Convert review text using CountVectorizer
8. Combine all numerical features
9. Split the dataset into training and testing sets
10. Train a Random Forest classifier
11. Evaluate the model
12. Analyze model performance and feature importance
13. Predict sentiment on new review text

## Model Results
The Random Forest model achieved strong performance on the test dataset.

- Training Accuracy: 99.64%
- Testing Accuracy: 93.17%

The model performed very well in classifying positive reviews, while negative reviews were more difficult due to class imbalance in the dataset.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset file `amazon_alexa.tsv`.
3. Run the notebook cells from top to bottom.
4. Review the visualizations, model evaluation results, and prediction output.

## Conclusion
This project demonstrates how NLP techniques can be used to convert customer review text into numerical features and train a machine learning model for sentiment classification. The Random Forest model showed strong overall performance and can be used as a basic sentiment analysis system for customer feedback.