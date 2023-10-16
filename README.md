# rental-pricing-explore

Credit to the [Data Science Working Group](http://datascience.codeforsanfrancisco.org) for this template. To complete this project, delete all template text (save for the headers) and fill in your own information.

Begin reading `instructions.md` to get started.

## Project Intro/Objective
The purpose of this project is to predict the price of rentals. Part of what this included was going through the process of creating a repository, exploring the raw data, cleaning our data, and creating a linear regression. This put into practice the use of material from class, documentation, and asking questions to navigate the lab. The impact of this work in the context of the rental market is being able to fairly price properties base on factors of the respective location. This is relevant as rental properties become the predominant way of people affording housing.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* Linear Regression Model

### Technologies
* Python
* Pandas, jupyter
* Sklearn
* Seaborn

## Project Description
* The data used for this analysis comes from the data analytics consulting firm called **NotGPT**, from an in house dataset.
* The question that was being explored, was how much should the company charge for their rental properties by doing an analysis of the housing market.
* To analyze the dataset we cleaned, we performed a linear regression. From this analysis we derived two key metrics, the R-squared and Mean Squared Error (MSE). The R-squared told us that there is some variance in the unit price (r^2 = 0.447). Meaning that 44.7% of the unit price could be predicted with the linear regression model performed. However, our MSE was 90.262, indicating that the predications are not the most accurate. 
* The challenge at hand is that the data does not allow for the most accurate predictions of prices for the rental properties that the company acquired. This might require looking at collecting a different set of data to improve the accuracy of these predictions. 
