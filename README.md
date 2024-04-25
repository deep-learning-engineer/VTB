# VTB


## Formulation of the problem
It is necessary to solve the problem of predicting the outflow of bank customers. Namely, using transaction data for 6 months, you need to build an algorithm that predicts the probability of customer churn in the next 6 months. A special feature of the task is that, as part of the training data for training, participants are given not only a label corresponding to the fact that the client will “churn,” but also the time until his last transaction. More information about the structure and features of the data can be found on the “Data” page.

Predicting customer churn is an extremely common task found in many companies across a variety of industries. Despite its widespread use, churn problems have a large number of pitfalls and features that are often talked about, but almost never shown in practice. On the other hand, in churn problems there are many useful developments, analytical practices and entire scientific directions, which few people know about outside of practicing expert teams.

In this competition, participants can approach a problem in more ways than one. In particular, the presence of information such as time until the last transaction within the training data will allow participants to take advantage of Time-to-Event approaches in machine learning.


## Checking solutions

The competition metric is CI, also known as Concordance Index or (Harrel's) C-index. For those new to this metric, it is worth looking at it as a generalization of ROC-AUC for Time-to-Event tasks. The competition uses the implementation of metric calculation from the lifelines library: lifelines.utils.concordance_index.

## Startup instructions

1) Download ```VTB_CHURN.ipynb``` and run it in Google Colab (or Kaggle, local device)
2) Install all required dependencies from ```requirements.txt``` \
   ```pip3 install -r requirements.txt```

## Competition link

https://ods.ai/tracks/data-fusion-2024-competitions
   
