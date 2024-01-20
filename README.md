## Kaggle Competition Summary
### **Title:** Cosmic Mystery Challenge  
**Description:** Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. The Spaceship Titanic, carrying 13,000 passengers, collided with a spacetime anomaly, transporting almost half of them to an alternate dimension. Your task is to predict which passengers were transported by the anomaly using recovered records.

**Evaluation Metric:** Classification accuracy - the percentage of predicted labels that are correct.  

1. **Data Cleaning & EDA:**
   - Loaded and explored the dataset from [Kaggle](https://www.kaggle.com/competitions/spaceship-titanic/data).
   - Performed feature preprocessing, including scaling, encoding, and one-hot encoding.

2. **Model Building:**
   - **Decision Tree Classifier:**
     - Built a basic decision tree for a base score.
     - Extracted feature importance.
     - Fine-tuned hyperparameters using GridSearchCV.
     - Evaluated and printed results.

   - **MLP Classifier (Multi-layer Perceptron):**
     - Built a basic MLP model.
     - Tuned hyperparameters using GridSearchCV for solver, hidden layer sizes, learning rate, and regularization.
     - Evaluated and printed results.

   - **XGBoost Model (EXtreme Gradient Boosted):**
     - Trained and evaluated XGBoost models on both uncleaned and cleaned data.
     - Extracted feature importance for insights into cleaning & preprocessing impact.
     - Compared results with other models.
     - Submitted predictions to Kaggle.

### Evaluation Metric:

Classification accuracy - the percentage of predicted labels that are correct.

### Libraries:

- **Data Cleaning & EDA:**
  - pandas, numpy, scikit-learn, scipy

- **Model Building:**
  - scikit-learn, XGBoost

### Model Comparison
Compare the performance of basic and tuned  models to have an idea of which model performs best on the data that we have and which one to use going forward.

This summary provides an overview of the tasks performed in your notebook. If you have specific questions or need assistance with any part of the code, feel free to ask!  
Email: makalamabotjasfp@gmail.com  
LinkedIn: Makala Mabotja
