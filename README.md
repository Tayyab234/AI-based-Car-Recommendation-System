🚗 AI-based Car Recommendation System

This project implements an end-to-end AI-based Car Recommendation System to predict car names and their selling prices based on user-defined features. It combines machine learning, deep learning, and similarity search techniques to provide intelligent recommendations.

📌 Features
✅ Predicts car selling prices using Random Forest and XGBoost
✅ Predicts car names using an Artificial Neural Network (ANN)
✅ Cosine similarity for recommending similar cars
✅ Interactive command-line interface to collect user preferences
✅ Clean and robust data preprocessing
✅ Exploratory Data Analysis with visualizations
✅ Web scraping pipeline with BeautifulSoup for automotive listings (optional, for EDA)

🧩 Technologies Used
Python

pandas

scikit-learn

XGBoost

TensorFlow/Keras

Matplotlib & Seaborn

BeautifulSoup (for scraping)

🗂️ Project Workflow
1️⃣ Data Preprocessing

Cleaned nulls, missing, and duplicate entries

Encoded categorical features

Scaled numeric features

2️⃣ EDA

Pie plots of seat distributions

Bar plots for brand/model counts

Heatmaps of feature correlations

Residuals and predicted vs actual graphs for model evaluation

3️⃣ Machine Learning

Random Forest Regressor

XGBoost Regressor

Explained variance and R2 score evaluation

4️⃣ Deep Learning

ANN trained on car name classification

RNN explored (but identified as sub-optimal for tabular data)

Early stopping and dropout applied

5️⃣ Recommendation

Cosine similarity to suggest the most similar car to user preferences

6️⃣ User Interaction

Command line interface asks user preferences (brand, fuel type, mileage, price range, etc.)

Returns predicted car names and prices

📊 Visualizations
Feature importance plots

Pie charts

Heatmaps

Predicted vs. actual scatter plots

ANN/RNN accuracy and loss curves

📝 Learnings
✅ Tree-based models outperform other approaches for tabular data
✅ ANN can classify car names with reasonable performance
✅ RNN does not suit static tabular data
✅ Visualizations help communicate results
✅ User-friendly CLI can boost adoption of ML models                                                                                                                                        
🤝 Let’s Connect!
If you are interested in machine learning, recommender systems, or automotive data, feel free to connect and collaborate!

