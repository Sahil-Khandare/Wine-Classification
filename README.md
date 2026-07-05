# Wine Classification using Machine Learning

## Project Overview

This project implements Machine Learning classification techniques to predict different categories of wine based on their chemical properties. The Wine dataset from Scikit-learn is used to train and evaluate classification models using Naive Bayes algorithms.

The project includes data exploration, preprocessing, model training, evaluation, comparison of algorithms, and model serialization using Pickle.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Pickle

---

## Dataset Information

The project uses the built-in **Wine Dataset** available in Scikit-learn.

### Dataset Statistics

* Total Samples: **178**
* Features: **13**
* Classes: **3 Wine Categories**

### Features Include

* Alcohol
* Malic Acid
* Ash
* Alcalinity of Ash
* Magnesium
* Total Phenols
* Flavanoids
* Nonflavanoid Phenols
* Proanthocyanins
* Color Intensity
* Hue
* OD280/OD315 of Diluted Wines
* Proline

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Visualization
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Algorithm Comparison
9. Model Serialization using Pickle

---

## Machine Learning Models Used

### Gaussian Naive Bayes

* Suitable for continuous numerical features
* Assumes features follow a Gaussian distribution

### Multinomial Naive Bayes

* Commonly used for count and frequency data
* Implemented for performance comparison

---

## Project Structure

```text
Wine-Classification/
│
├── wine.ipynb
├── gaussian_nb_model.pickle
├── multinomial_nb_model.pickle
├── README.md

```

## Results

The project compares the performance of:

* Gaussian Naive Bayes
* Multinomial Naive Bayes

and evaluates their effectiveness in classifying wine categories.

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Classification algorithms
* Naive Bayes classifiers
* Model evaluation
* Algorithm comparison
* Model serialization using Pickle

---

## Future Improvements

* Implement additional classification algorithms
* Perform hyperparameter tuning
* Create interactive visualizations
* Deploy the model using Flask or Streamlit

---

## Author

**Sahil Khandare**

Machine Learning Enthusiast | Python Developer | Engineering Student
