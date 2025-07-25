# Stroke Prediction using Machine Learning

This project was developed as part of a **Machine Learning course group assignment**. The goal is to build and compare different machine learning models to **predict the risk of stroke** based on patient data. The implementation was done in **Python**, and after comparing the models, the best-performing one was selected for further use.

## 📌 Objective

- To develop machine learning models that predict the risk of stroke.
- To compare the performance of multiple models to determine the most accurate one.
- To select and finalize the best model based on performance metrics.

## 🛠 Technologies Used

- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy` – Data processing
  - `scikit-learn` – Machine learning models and evaluation
  - `matplotlib`, `seaborn` – Data visualization

## 📊 Models and Accuracy

The following models were implemented and evaluated:

| Model                      | Accuracy (%) |
|---------------------------|--------------|
| Logistic Regression        | 93.9         |
| Naive Bayes                | 93.9         |
| Artificial Neural Network (ANN) | 93.9   |
| Decision Tree              | **94.0**     |

> **Decision Tree** achieved the highest accuracy and was selected as the final model for prediction.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/stroke-prediction.git
   cd stroke-prediction
