# Madrid house price predictor
![alt text](https://github.com/KevsDe/madrid_house_price/blob/main/static/madrid.jpg?raw=true)
## About the project:
Are you trying to figure out your dream house price in Madrid Spain?  
With this model, you can provide the features such as neighborhood, bedroom number, etc, and get an approximate price of a house with that characteristics.  
**This project was made for learning and fun purposes and is not a production service**

## About the data:
I scraped the data from a real estate website in October 2022,  the data has not been updated since then, and the last update is relevant because the house  price fluctuation. 

## About the model:
 - Model trained with 11404 observations
 - Last Update 2022/11/05
 - The model used is Random Forest
 - Available parameters (all mandatory):  House type, House type 2, Rooms, m2, Elevator, Garage, District & Neighborhood.
 
## How to run the model
**Option 1**
 - Download the files
 - Build Docker container: `docker build -t madrid_house_price .`
 - Run Docker container: `docker run -it -p 9696:9696 madrid_house_price:latest`
 
**Option 2**
The model is deployed in pythonanywhere: https://kevmp.pythonanywhere.com/

**From Madrid (L)**