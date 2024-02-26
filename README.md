# MNESEDA
MNESEDA: a prior-guided subgraph representation learning framework for predicting disease-related enhancers.

# Requirements:
- python 3.7.15
- pytorch 1.12.1
- torch-geometric 2.2.0
- scikit-learn 1.0.2
- networkx 2.5.0
- numpy 1.21.6
- pandas 1.2.0

## Datasets

Please Contact us (jsxu@webmail.hzau.edu.cn) to obtain the Data and Splits.

### Statistic of EDA Dataset
|Dataset|#Enhncer|#Disease|#Associations|
|:-:|:-:|:-:|:-:|
|Disease|792|167|1059|
|EnDisease|413|127|478|
|CancerEnD|8525|18|8541|

## Usages
```
python main.py --data-name ${data_name} --pos-neg-ratio '1_1' --save-results --epochs 200 --lr 0.0001 --embedDim ${embed_size}
```


### Note: The code will be public once the paper is accepted.

