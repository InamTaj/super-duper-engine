# super-duper-engine
NLP Project for CS5316

# Libraries to Install
- `pip install pandas scikit-learn`

# Dataset Preparation
1. `raw` folder should contain raw Dataset
2. `english-only` folder should contain the output of [Filter_Non-English_Tweets](./notebooks/Filter_Non-English_Tweets.ipynb) notebook
3. Run [Dataset_Preparation.ipynb](./notebooks/Dataset_Preparation.ipynb) notebook to get final dataset, divided into train, val, test split under `dataset/processed`
