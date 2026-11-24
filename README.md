# Parkinson-s-disease-progression-prediction
Parkinson's Disease Progression Prediction with TensorFlow Decision Forests
# Dataset
data for this code is taken from kaggle
# Models
following modes are applied on code\
tensorflow_decision_forests.keras.RandomForestMode\
 tensorflow_decision_forests.keras.GradientBoostedTreesModel\
 tensorflow_decision_forests.keras.CartModel\
 tensorflow_decision_forests.keras.DistributedGradientBoostedTreesModel\
 # Scoreing Metrics
 MAPE(Mean Absolute Percentage Error) we calculate the sum of absolute value of the forecast errors, divided by the actual values for each period(source).Difference between MAPE and sMAPE is that sMAPE has both a lower bound and an upper bound.Since TensorFlow Datasets doesn't have a bultin function to calculate sMAPE metric yet, a custom function to calculate sMAPE.
