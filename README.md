# Lol-draft-win-prediction

dataset: [league of legends master games patch 14.10](https://www.kaggle.com/datasets/jakubjagieka/league-of-legends-2024-soloq-dataset) (put the data folder)

- This project was intially for predicting win rate percentage for champions only, but there was too much noise so I have to add a 10 more columns for champions winrate. Unfortunately i could not finished this because I simply do not have enough RAM

 - I used Random Forest Classifier, logistic Regression, lgbm, naive bayes, last is the ensemble with logistic regression as the meta classifier

 - Before adding winrate, random forest was overfitting a lot and the other model just did not perform well at all, so I had to add champions winrate as well but 16 RAM was not enough for 10 millions line of data, I cant even sample a small amount since I cannot read the 10 millions line in anyway. But the test evaluation before adding winrate is 53.32 which is not great at all.
 - I may come back to this in the future, or maybe when I have more RAM.

