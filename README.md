# Exploratory Analysis and Feature Selection for the Prediction of Nitrogen Dioxide

Nitrogen dioxide is one of the most hazardous pollutants identified by the World Health Organisation. Predicting and reducing pollutants is becoming a very urgent task and many methods have been used to predict their concentration, such as physical or machine learning models. In addition to choosing the right model, it is also critical to choose the appropriate features. This work focuses on the spatiotemporal prediction of nitrogen dioxide concentration using Bidirectional Convolutional LSTM integrated with the exploration of nitrogen dioxide and associated features, as well as the implementation of feature selection methods. The Root Mean Square Error and the Mean Absolute Error were used to evaluate the proposed approach.

The purpose of each file included in this repository is briefly described below:

- _MadridExploration.zip_ contains the result of an exploratory analysis that identifies the relationship between nitrogen dioxide and additional features (meteorological and traffic data).
- _Traffic_Average_Speed_Calculation.ipynb_ calculates the average traffic speed for the period 1-7 January 2019 in the city of Madrid.
- _mRMR.ipynb_ calculates Maximum Relevance - Minimum Redundancy. 
- _Mutual_Information.ipynb_ calculates mutual information. 
- _BiConvLSTM.ipynb_ includes the steps for predicting nitrogen dioxide implementing BiConvLSTM on various selected subsets.

The final version of the preprocessed dataset can be found at the following link: https://doi.org/10.5281/zenodo.6497108. The code for grid cell generation, data preprocessing and the model construction can be found at the following link: https://bit.ly/3vfwrjJ


