# 🌸 Iris Flower Classification – Internship Project (Week 1)

This project is part of the AI & ML Internship Program – Week 1. The goal is to build a simple machine learning model to classify iris flowers into one of three species based on their sepal and petal measurements.

## 📌 Project Objective

To apply fundamental machine learning concepts using a classic classification problem. The task is to accurately predict the species of iris flowers using the **Decision Tree Classifier**.

## 🗂️ Dataset

- Source: `sklearn.datasets.load_iris()`  
- Number of Samples: 150  
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width  
- Target Labels:
  - Setosa
  - Versicolor
  - Virginica

## 🛠️ Technologies & Libraries Used

- Python
- pandas – Data manipulation
- numpy – Numerical operations
- matplotlib & seaborn – Data visualization
- scikit-learn – Machine learning (modeling & evaluation)
- Google Colab – Development environment

## 🔁 Workflow Overview

1. **Load the Dataset**  
   Load the Iris dataset from scikit-learn and convert it into a pandas DataFrame.

2. **Data Exploration**  
   Perform basic statistical analysis and visualizations to understand feature relationships.

3. **Preprocessing**  
   - Split the data into features (`X`) and target (`y`)  
   - Divide the dataset into training and testing sets

4. **Model Training**  
   Train a **Decision Tree Classifier** using the training data.

5. **Model Evaluation**  
   - Predict using the test set  
   - Evaluate using accuracy score, classification report, and confusion matrix

6. **Visualization**  
   Visualize the confusion matrix to analyze model performance.

## 📊 Results

- The model achieved **high accuracy** in predicting the species.
- The features show strong separation between classes, especially for *Setosa*.
- Confusion matrix and classification report confirm model reliability.

## 📁 Project Structure

```bash
📦 iris-flower-classification/
├── Iris_Classification_Project.ipynb
├── README.md
