# Machine learning projects

1. Fashion Image Recognition
2. Predictive Modeling for Voluntary Attrition

## 1. Fashion Image Recognition
**Project Overview**

The Clueless Closet project is a comprehensive machine learning initiative that originated during my Data Science Bootcamp at BrainStation in 2019. The project draws inspiration from Cher's closet in the movie Clueless (1995). For those unfamiliar with the film, you can watch a [YouTube trailer here](https://www.youtube.com/watch?v=XNDubWJU0aU).

**Project Phases**

1. Image Classification: Categorizing fashion product images (e.g., "pants," "tops," "shoes," "bags") *(Completed)*
During my program at BrainStation, I concentrated on the first phase. I employed a Convolutional Neural Network (CNN) architecture, specifically MobileNet, to classify images from the Fashion MNIST dataset publicly available on Kaggle.
2. Outfit Scoring: Rating how well different pieces of clothing complement each other on a scale from 0 to 10.
3. Recommendation System: Providing suggestions for improvement if the outfit score is below 5.

**Technical Details**
- Model Used: MobileNet (CNN)
- Dataset: Fashion Product Images (Small) from Kaggle
- Frameworks: TensorFlow, Keras
- Tools: Python, Jupyter Notebook

**Future Work**
- performance enhancement, including an update to a more recent model
- developing a recommendation system solution

## 2. Attrition modelling

**Project Overview**

This project focuses on building predictive models to forecast voluntary employee attrition based on various characteristics such as department, age, hire source, and location. The objective is to identify key factors contributing to employee turnover and to predict which employees are at risk of leaving the organization.

**Project Phases**

1. Exploratory Data Analysis (EDA): Conducting a thorough analysis to understand data distributions, correlations, and potential outliers.
  - correlation matrix
  - data visualization
2. Data Splitting: Dividing the dataset into training and testing sets to validate model performance.
  - training 70%
  - testing 30%
3. Model Initialization: Setting up various machine learning models for training.
4. Model Training and Evaluation: Training the models and evaluating their performance using accuracy scores and other relevant metrics.

**Models Used**

- Regular models
  - Logistic Regression
  - Decision Tree
  - Naive Bayes
- Ensemble models
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)

**Technical Details**

- Libraries Used: NumPy, Pandas, Scikit-learn
- Frameworks: Scikit-learn for model implementation
- Tools: Python, Jupyter Notebook
