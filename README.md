# JSON ML Veg Non-Veg Prediction

A Machine Learning classification project that predicts whether a recipe is **Vegetarian or Non-Vegetarian** using structured recipe data stored in JSON format.

## Overview

This project demonstrates an end-to-end Machine Learning workflow for classifying recipes based on their ingredient information.

The JSON dataset contains recipe-related information, which is processed and transformed into features suitable for Machine Learning. The trained classification model then predicts whether a recipe belongs to the **Vegetarian** or **Non-Vegetarian** category.

## Problem Statement

Identifying whether a recipe is vegetarian or non-vegetarian can be automated using the ingredients present in the recipe.

The goal of this project is to build a Machine Learning model that learns patterns from recipe ingredients and predicts the food category.

## Project Workflow

```text
JSON Recipe Data
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Ingredient Processing
       ↓
Feature Extraction
       ↓
Train-Test Split
       ↓
ML Classification Model
       ↓
Model Evaluation
       ↓
Veg / Non-Veg Prediction
```

## Key Features

* Reads structured recipe data from JSON
* Performs data cleaning and preprocessing
* Extracts useful information from recipe ingredients
* Converts recipe information into Machine Learning features
* Trains a classification model
* Evaluates model performance
* Predicts whether a recipe is Vegetarian or Non-Vegetarian

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **JSON**
* **Jupyter Notebook / Google Colab**
* **Matplotlib / Seaborn** for visualization

## Machine Learning Approach

This project follows a supervised classification approach.

### Input

Recipe information, particularly the **ingredients** associated with the recipe.

### Target

```text
Vegetarian
Non-Vegetarian
```

### Classification

The model learns the relationship between recipe ingredients and the target category and uses this learned pattern to classify new recipes.

## Data Processing

The dataset is processed through several steps:

1. Load the JSON recipe data.
2. Convert the nested JSON structure into a usable tabular format.
3. Handle missing values.
4. Remove duplicate records where required.
5. Process ingredient information.
6. Create features from the recipe data.
7. Separate input features and target labels.
8. Split the data into training and testing sets.

## Model Evaluation

The trained model can be evaluated using standard classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help measure how well the model distinguishes between Vegetarian and Non-Vegetarian recipes.

## Project Structure

```text
json_ml_veg_nonveg_prediction/
│
├── data/
│   └── recipe_images.json
│
├── notebook/
│   └── veg_nonveg_prediction.ipynb
│
├── README.md
├── requirements.txt
```

> Update the file names above if your repository uses different names.

## Installation

Clone the repository:

```bash
git clone https://github.com/sejalrathod2001/json_ml_veg_nonveg_prediction.git
```

Navigate to the project:

```bash
cd json_ml_veg_nonveg_prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the notebook in **Jupyter Notebook** or **Google Colab** and execute the cells sequentially.

The notebook performs:

```text
Data Loading
→ Data Cleaning
→ Feature Engineering
→ Model Training
→ Model Evaluation
→ Prediction
```

## Example

For a recipe containing ingredients such as:

```text
Paneer
Tomato
Onion
Capsicum
Spices
```

the model can classify the recipe as:

```text
Prediction: Vegetarian
```

For a recipe containing ingredients such as:

```text
Chicken
Onion
Garlic
Spices
```

the model can classify it as:

```text
Prediction: Non-Vegetarian
```

## Future Improvements

* Build a Flask or FastAPI prediction API
* Add a web interface for recipe classification
* Save the trained model using Joblib
* Add support for real-time ingredient input
* Improve feature engineering for ingredient text
* Compare multiple classification algorithms
* Deploy the model as a web application

## Learning Outcomes

This project demonstrates practical experience with:

* JSON data handling
* Data preprocessing
* Feature engineering
* Text/ingredient-based feature extraction
* Supervised Machine Learning
* Classification
* Model evaluation
* End-to-end ML workflow

## Author

**Sejal Rathod**

GitHub: [@sejalrathod2001](https://github.com/sejalrathod2001)
