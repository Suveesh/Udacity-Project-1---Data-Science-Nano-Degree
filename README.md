# Udacity-Project-1---Data-Science-Nano-Degree
Airbnb is an online marketplace which lets people to rent their properties, rooms in their house, or share their rooms to the guests. This blog is an effort to interpret the Airbnb, Boston dataset retrieved from Kaggle and answer few business questions, mentioned below.

## Data Scource: [Kaggle](https://www.kaggle.com/airbnb/boston)

[My Kaggle Notebook](https://www.kaggle.com/suveesh/airbnb-boston-data-anaysis-and-price-prediction)

## Medium Blog
[Boston Airbnb Data Analysis and price prediction](https://suveesh-m92.medium.com/boston-airbnb-data-analysis-and-price-prediction-5473f9726dbe)

## Business Questions:
1.) What are the features that influence the property pricing?

2.) What time of year has the highest rental prices?

3.) Do Superhosts perform better than other hosts?

4.) How are the listings distributed on Boston city?

## Task:
1.) Create a model to predict property price

## Libraries and Installation

Most of the code in this project will run with Python version 3.*. 


The following libraries are used in the notebook: 

1.) numpy, 

2.) pandas, 

3.) matplotlib, 

4.) sklearn, and 

5.) seaborn. 

To install any library exectue 'pip install library_name' in terminal.

## Directory structure

├── Udacity-Project-1---Data-Science-Nano-Degree

├── Airbnb_Dataset.zip

│   ├── calendar                                                 <- Property availability and pricings based on the calendar dates

│   ├── listings                                                 <- Airbnb Property lisitngs with all th supporting features such as roo_types, no. of bedrooms, review ratings etc.

│   ├── reviews                                                  <- Reviews dataset with respect to calendar dates

│   

├── airbnb-boston-data-anaysis-and-price-prediction.ipynb        <- Python coding on data analysis and visualzation to answer the business questions.

│

├── README.md                                                    <- Brief description of the project and a guide to walk through the repository


## The Conclusion

1.) We have found that property pricing is dependent on many number of features and strongly correlated with the property size, and room type. Thus provided, pricing is a sensitive feature and we cannot be relied only on the available features in our observations and consider many other factors to determine the price.
   
2.) Superhost are the recognition provided by Airbnb for performing well in hospitality. We have analysed the data to verify that they are really performing better than other host in the listings.
   
3.) September and October are the expensive months to travel and stay in Airbnb rooms. Properties are highly distributed along the Boston north station, Cambridge port, Brighton, and East Boston.
   
4.) We have created a model with Random Forest Regressor algorithm to predict the property pricing with few features selected from the listings dataset.

## Acknowledgments

Thanks to Kaggle and AirBnb for the dataset and Udacity for the course.
