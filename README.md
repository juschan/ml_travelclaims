# Travel Insurance Claims Prediction

### Goals

The goal of this project is to determine if we can predict the claim status (Yes or No) from the various travel insurance-related attributes.

### Dataset

- The "Travel Insurance" data is provided by a third-party travel insurance servicing company based in Singapore.

- The data is downloadable from Kaggle, [https://www.kaggle.com/mhdzahier/travel-insurance](https://www.kaggle.com/mhdzahier/travel-insurance)

- The dataset has 63326 records. There are 11 fields/attributes where "Claim" is the target variable.

### Results

The dataset is very imbalanced with a majority of having 'no claims'. As such, we produced 3 notebooks to explore various possibilities:

1. [A multi-layer perceptron Neural Network without address data imbalance](Justin_Chan_Travel_insurance_NoSMOTE.ipynb)

2. [A multi-layer perceptron Neural Network (as per 1. ) but applying SMOTE](Justin_Chan_Travel_insurance_MLP.ipynb)

3. [A multi-layer perceptron Neural Network with SMOTE (as per 2. ) and also Adaboost](Justin_Chan_Travel_insurance_Adaboost.ipynb)

Addressing data imbalances (ie. small number if claims) is a common problem in insurance and actuarial science. Other possibilities include the use of under-sampling and over-sampling. 