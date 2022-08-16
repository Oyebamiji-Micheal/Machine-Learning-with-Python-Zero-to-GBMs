# Assignment One: House Price Prediction with Linear Regression
<img src= https://github.com/Oyebamiji-Micheal/Machine-Learning-with-Python-Zero-to-GBMs/blob/master/images/House.jpg height="200" width="900" >


## Objective
In this assignment, my instructions are the following

* Download and prepare a housing dataset for training 
* Train a linear regression model using sklearn
* Make predictions and evaluate the model

## Datasets
The datasets used in this assignment can be found as a zip file in [Jovian's Github repository](https://github.com/JovianML/opendatasets/raw/master/data/house-prices-advanced-regression-techniques.zip). The zip file contains three CSV files and one txt file. One of these CSV files, ```train.csv``` is used to train the model while another ```test.csv``` is used to test the model. Lastly, the description of the training dataset can be found in the txt file.

## Notebook workflow
* Download: I downloaded the zip file using the urlretrieve function from the urllib module and extracted the contents using the zipfile module
* Explore: Pandas and NumPy are used for data exploration while matplotlib and seaborn are used for visualization. All insights generated in the dataset can be found in the assignment notebook. 
* Prepare: In the preparation phase, we   
>- Identify the input and target column(s) for training the model.
>- Identify numeric and categorical input columns.
>- Impute (fill) missing values in numeric columns
>- Scale values in numeric columns to a (0,1) range.
>- Encode categorical data into one-hot vectors.
>- Split the dataset into training and validation sets.
* Train: Create and train a linear regression model using the Ridge class from sklearn.linear_model.

## Model 
Finally, we build a linear regression model using the Ridge class.   
</b>
Details about the predictions generated and evaluation can be found in the project notebook.
