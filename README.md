# super-duper-engine
NLP Project for CS5316

# Libraries to Install

- `pip install pandas scikit-learn tensorflow keras`

# Dataset Preparation

1. `raw` folder should contain raw Dataset
2. `english-only` folder should contain the output of [Filter_Non-English_Tweets](./notebooks/Filter_Non-English_Tweets.ipynb) notebook
3. Run [Dataset_Preparation.ipynb](./notebooks/Dataset_Preparation.ipynb) notebook to get final dataset, divided into train, val, test split under `dataset/processed`

# Notebooks

1. [LSTM Notebook](./notebooks/LSTMs_for_Author_Detection.ipynb)
2. [RNN Notebook](./notebooks/RNN_for_Text_Classification.ipynb)
3. [Attention Model Notebook](./notebooks/Attention.ipynb) (requires tf v1.13.1)
4. [CNN Models](./notebooks/CNN_for_Author_Detection.ipynb)
5. [Fasttext Model](./notebooks/Fasttext.ipynb)
