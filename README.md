# Car-price-prediction

#### Dataset for the model can be found at https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho
# Work Done:

On basis of features such as : 'Selling_Price', 'Present_Price', 'Kms_Driven', 'Owner', 'Fuel_Type_Diesel', 'Fuel_Type_Petrol', 'Seller_Type_Individual','Transmission_Manual', 'No_of_Year' the selling price of the vehicle is predicted

    1.Dataset was analyzed using graphs  heatmap, barplots and histograms for data insights.  
    2.No_of_year feature was derived from Year column of the orignal Dataset.  
    3.Preprocessing of categorical features was done using OneHotEncoding.  
    4.Feature importance was calculated using ExtraTreesRegressor and correlation matrix was used for feature selection.  
    5.HyperParameter tuning was done for selection of best parameters for RandomForestRegressor.  
    6.Model was fit to the RandomforestRegressor and tested on Test Dataset.  

# To Run the model:

Use requirements.txt for installing dependencies.  
Make a folder named as 'Data' in the working directory and put all the csv files in that folder  
Run the caprediction.py
