 ![](/home/alessandra/Repos/Python_DS_Meigarom/house rocket.png)

# [<b>House Rocket Insights</b>](https://house-rocket-ds.herokuapp.com/)
## <i>A market share project </i>
https://house-rocket-ds.herokuapp.com/

### 1. Description
House Rocket is a fictional company that works with the purchase and sale. I want find the best business opportunities and my strategy is to buy houses in great condition at low prices and sell those properties at a higher price. 
The attributes of houses make them more or less attractive, influencing the attractiveness of the properties and, consequently, their price. 
The questions to be answered are:

1. Which houses should the CEO of House Rocket buy and at what purchase price?
2. Once the house is owned by the company, what is the best time to sell it and what would be the sale price?


### 2. Dataset
- Data for this project can be found at: https://www.kaggle.com/harlfoxem/housesalesprediction/discussion/207885 
- This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

| Attributes     | Meaning                                                                                                                                                                                              |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| id             | Unique ID for each home sold                                                                                                                                                                         |
| date           | Date of the home sale                                                                                                                                                                                |
| price          | Price of each home sold                                                                                                                                                                              |
| bedrooms       | Number of bedrooms                                                                                                                                                                                   |
| bathrooms      | Number of bathrooms, where .5 accounts for a room with a toilet but no shower                                                                                                                        |
| sqft_living    | Square footage of the apartments interior living space                                                                                                                                               |
| sqft_lot       | Square footage of the land space                                                                                                                                                                     |
| floors         | Number of floors                                                                                                                                                                                     |
| waterfront     | A dummy variable for whether the apartment was overlooking the waterfront or not                                                                                                                     |
| view           | An index from 0 to 4 of how good the view of the property was                                                                                                                                        |
| condition      | An index from 1 to 5 on the condition of the apartment                                                                                                                                               |
| grade          | An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design. |
| sqft_above     | The square footage of the interior housing space that is above ground level                                                                                                                          |
| sqft_basement  | The square footage of the interior housing space that is below ground level                                                                                                                          |
| yr_built       | The year the house was initially built                                                                                                                                                               |
| yr_renovated   | The year of the house’s last renovation                                                                                                                                                              |
| zipcode        | What zipcode area the house is in                                                                                                                                                                    |
| lat            | Lattitude                                                                                                                                                                                            |
| long           | Longitude                                                                                                                                                                                            |
| sqft_living15  | The square footage of interior housing living space for the nearest 15 neighbors                                                                                                                     |
| sqft_lot15     | The square footage of the land lots of the nearest 15 neighbors                                                                                                                                      |

### 2. Tools
- [x] Jupyter notebook
- [x] Python
