# Kaggle-2020

Submission to the 3rd annual Women in Data Science (WiDS 2020) datathon. 

Using MIT's GOSSIS dataset to predict in-hospital mortality rates, my teammates Kat, Irina, Jialin and I set out to do several things:
1. Clean the dataset, dropping NaN values
2. Hot-encode categorical variables and normalize their distribution with Scaler
3. Balance the dataset using a combination of SMOTE and downsampling 
4. Explore automatic feature engineering with FeatureTools
3. Experiment with RandomForest, XGBoost and CatBoost (gradient boosting on decision trees) classifier to determine which regression model best predicts ICU deaths around the world. 

For more information on the Kaggle challenge we entered: https://widsconference.medium.com/the-wids-datathon-2020-is-now-live-encouraging-women-worldwide-to-hone-their-data-science-skills-936712870b09
