## Kaggle Competition Summary
### **Title:** Cosmic Mystery Challenge  
**Description:** Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. The Spaceship Titanic, carrying 13,000 passengers, collided with a spacetime anomaly, transporting almost half of them to an alternate dimension. Your task is to predict which passengers were transported by the anomaly using recovered records.

**Evaluation Metric:** Classification accuracy - the percentage of predicted labels that are correct.  
**Dataset**: https://www.kaggle.com/competitions/spaceship-titanic/data

### Data Cleaning & EDA Steps
1. Data loading and basic exploration.
2. Feature preprocessing:
   - Scaling using MinMax Scaler for log-transformed features.
   - Encoding boolean features (CryoSleep and VIP).
   - Dummy encoding for Cabin information ('Deck' and 'Side').
   - One-hot encoding for categorical features (HomePlanet, Destination, top_amenities).

### Model Building
#### Decision Tree Classifier
1. Build a basic decision tree for a base score.
2. Extract feature importance.
3. Fine-tune hyperparameters using GridSearchCV.
4. Evaluate and print results.

#### MLP Classifier (Multi-layer Perceptron)
1. Build a basic MLP model.
2. Tune hyperparameters using GridSearchCV for solver, hidden layer sizes, learning rate, and regularization.
3. Evaluate and print results.

#### XGBoost Model (EXtreme Gradient Boosted)
1. Train and evaluate XGBoost models on uncleaned data.
2. Train and evaluate XGBoost models on cleaned data.
3. Extract feature importance on both to view impact of our cleaning & preprocessing
4. Evaluate results and compare on other models 
5. Submit predictions to Kaggle.

### Model Comparison
Compare the performance of basic and tuned  models to have an idea of which model performs best on the data that we have and which one to use going forward.

This summary provides an overview of the tasks performed in your notebook. If you have specific questions or need assistance with any part of the code, feel free to ask!
Email: makalamabotjasfp@gmail.com
LinkedIn: Makala Mabotja
