
# **Hybrid TLBO for Machine Learning Hyperparameter Optimization**

## **Project Overview**
This project implements **Teaching-Learning-Based Optimization (TLBO)** and its hybrid variant to optimize hyperparameters for various machine learning models. It uses **TLBO** to enhance model performance by avoiding local optima and improving computational efficiency. The dataset used in this project is the **Student Performance Data Set** from the **UCI Machine Learning Repository**.

## **Dataset**
The dataset contains academic and demographic details of students from two Portuguese schools. The attributes include:
- **Demographic Information**: Age, gender, family size, etc.
- **Academic Information**: Study time, failures, school support, grades (G1, G2, G3), etc.
- **Personal & Lifestyle Information**: Alcohol consumption, health, free time, absences, etc.


📌 **Dataset Link**: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)


## **Project Structure**

├── data/                      # Dataset Files (student-mat.csv, student-por.csv)
├── src/                       # Source Code Files
│   ├── preprocess.py          # Data Preprocessing and Encoding
│   ├── models.py              # Machine Learning Models Implemented
│   ├── tlbo.py                # TLBO Algorithm Implementation
│   ├── hybrid_tlbo.py         # Hybrid TLBO Optimization
│   ├── train.py               # Training Machine Learning Models
│   ├── evaluate.py            # Model Evaluation and Performance Metrics
│   ├── visualization.py       # Data Visualization & Exploratory Analysis
├── notebooks/                 # Jupyter Notebooks for Experimentation
├── results/                   # Model Results and Logs
├── README.md                  # Project Documentation
├── requirements.txt           # Required Dependencies
├── main.py                    # Main Script to Run the Project
└── references.bib              # Bibliography for Citations

## **Models Implemented**

The following machine learning models are optimized using TLBO and Hybrid TLBO:

- Logistic Regression
- Support Vector Classifier (SVC)
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost
- LightGBM
  
Each model's hyperparameters are optimized to improve performance on student grade prediction.




