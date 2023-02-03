# Sales Prediction 
## Sales prediction for food items sold at various stores

**Author**: Jerico Viloria 

### Business problem:

Retailer wants to know which stores and products play a big role in increasing sales

### Data Sources:
Main Data source: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

There are 8523 rows and 12 columns within the dataset 

### Data Dictionary 

![Capture8](https://user-images.githubusercontent.com/118643932/216562060-da5e61c2-d3a0-462a-92df-9d99897f9197.PNG)

## Methods
#### Exploratory Data Analysis 
![Capture14](https://user-images.githubusercontent.com/118643932/216569090-ec040f4a-1401-4131-98d9-e9a4f18d29cb.PNG)
> This histogram explores how many various products items there are in the outlets.

#### Explanatory Visual 1
![Capture15](https://user-images.githubusercontent.com/118643932/216569276-7265ee0e-d95e-4c21-b3e2-e7d057296e06.PNG)
> This visual shows the total average item sales between the different Outlet Area Type.

#### Explanatory Visual 2
![Capture16](https://user-images.githubusercontent.com/118643932/216574948-cb01463d-dc11-4f27-a16f-147b154a1e6e.PNG)
> This visual shows the Total Items Sales and the Item's Visbility. There difference between the two is very similar and Item Visibility looks like it plays a big part on Item Sales.

## Machine Learning Models Used
- Linear Regression Model
- Decision Tree Regressor Model

Linear Regression Model Testing:
- Test R2 Score: -1.6575880497968222e+19
- Test RMSE Score: 6762579228318.999

Decision Tree Regressor Model Testing:
- Test R2 Score: 0.5960564372160062
- Test RMSE: 1055.685

## Recommendations:

- Looking at the two models, I would have to recommend the Regression Tree model and it has the lowest variance in the y 

- Choosing the Tuned Regression Tree model because it overall has performed better of the two models. 
