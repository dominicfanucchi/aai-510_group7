# Group 7 Final Project
This project is a part of the AAI-510 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

**-- Project Status: Active**

- ### Partner(s)/Contributor(s)
   * Dominic Fanucchi
   * Pawan Tahiliani
   * Kim Vierczhalek

## Installation
To use this project, first clone the repo on your device using the command below:
```
git init
git clone https://github.com/dominicfanucchi/aai-510_group7.git
```

## Project Objective
Use different machine learning techniques to gain insights on the AirBnb data hosted from Kaggle. The use of both supervised and unsupervised learning will be explored in this notebook.
 

## About the Dataset
This data set comes from a [Kaggle competition](https://www.kaggle.com/competitions/airbnb-recruiting-new-user-bookings/data) and contains 6 csvs. The majority of the training and modeling was done from the test_users.csv due to the presence of the country_destination column which was absent in the train_users csv. The data contains both numerical and categorical data as well as missing values that need to be handled. The age feature seems to need some data processing as well. All of this is done within the AAI-510 Final Project.ipynb jupyter notebook.

## Approach
The specific algorithms and networks used were as follows: 

### Supervised Learning
- RandomForest
- XGBoost
- CatBoost
- Ensemble Modeling of the above 3

### Unsupervised Learning
- K-Means Clustering

These algorithms and networks were implemented through Python and Jupyter Notebooks. 

 - ### Imports and Libraries
   * Numpy 
   * Pandas 
   * Matplotlib / Pyplot
   * Scipy Stats
   * Seaborn 
   * Sklearn


## Results
Overall, the predictive model performed with low accuracy, likely due to limited correlations between the features and the target feature. The k-means clustering was able to identify using 6 clusters as the best grouping of user data. Each of these clusters had different personas that helped split the users into distinct groups. Further analysis is done throughout the notebook, with the conclusion/discussion at the very bottom of the notebook.

## References



## Acknowledgments
We would like to express our sincere gratitude to Professor David Friesen, M.S. who taught the AAI-510-03 Course, and AirBnB for putting together this dataset. 


## License
This dataset is licensed under a [CC0 1.0 DEED license](https://creativecommons.org/publicdomain/zero/1.0/legalcode.en) - see the [Creative Commons](https://creativecommons.org/publicdomain/zero/1.0/legalcode.en) website for details.