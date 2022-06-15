# Car-Price-Prediction

### About Dataset: 

This [dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=Car+details+v3.csv) contains information about used cars.
This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning.
The columns in the given dataset are as follows:

1. name - Name of the cra.
2. year - This is the year in which the car was bought.
3. selling_price - This is the price the owner wants to sell the car at.
4. present_price - This is the current ex-showroom price of the car.
5. km_driven - This is the distance completed by the car in km.
6. fuel - Defines Fuel type of the car: Petrol/Diesel/Gas.
7. seller_type - Defines whether the seller is a dealer or an individual.
8. transmission - Defines whether the car is manual or automatic.
9. Owner - Defines the number of owners the car has previously had.


### About Model:

Random Forest Regressor with parameters:
- n_estimators: 1000
- min_samples_split: 2
- min_samples_leaf: 1
- max_features: sqrt
- max_depth: 25

### Score Achieved:
- R2: 0.88 ± 0.10
- MAE: 0.88
