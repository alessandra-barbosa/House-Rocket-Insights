![house_rocket](https://user-images.githubusercontent.com/70095554/134504743-5c4db802-f270-4c53-b19c-e9a84b6b7885.png)

## <i>A market share project </i>
https://house-rocket-ds.herokuapp.com/



### 1. Description
House Rocket is a fictional company that works with the purchase and sale. I want find the best business opportunities and my strategy is to buy houses in great condition at low prices and sell those properties with higher price. 
The attributes of houses make them more or less attractive, influencing the attractiveness of the properties and, consequently, their price. 
The questions to be answered are:

1. What are the properties that the company should buy and for what price?
2. What is the best time to sell the property and the best sales price?

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

### 3. Tools
- [x] Jupyter notebook
- [x] Python
- [x] Pycharm

### 4. Steps to solve the business problem:

- Data collection via Kaggle
- Business understanding
- Data processing
- Transformation of variables
- Data cleaning
- Data exploration
- Link to app on Heroku

### 6. Business Hypotheses 
|     | hypotheses                                                                     | Result | Business                                                             |
|-----|--------------------------------------------------------------------------------|--------|----------------------------------------------------------------------|
| h1  | Properties with a view of the water are on average 30% more expensive          | True   | Investing in properties with a view of the water                     |
| h2  | Properties with a construction date less than 1955 are on average 50% cheaper  | False  | Investing in real estate regardless of the construction date         |
| h3  | Properties without a basement with a larger total area are 40% more expensive  | True   | Investing in properties without a basement                           |
| h4  | Properties that have never been renovated are on average 20% cheaper           | True   | Investing in unrenovated properties and renovating them for sale     |
| h5  | Real estate in bad condition, but with good view, is 10% more expensive        | False  | Do not invest in bad condition                                       |
| h6  | Old and unrenovated properties are 40% cheaper                                 | True   | Investing in old and unrenovated properties and renovations for sale |
| h7  | Properties with more bathrooms are on average 5% more expensive                | False  | Investing in properties with 3-5 bathrooms                           |
| h8  | Newly renovated properties are 35% more expensive                              | False  | Investing in properties regardless of renovation                     |
| h9  | The growth in property prices month after month in 2014 is 10%                 | False  | Investing in properties in the lower cost months                     |
| h10 | Properties with 3 bathrooms grow 15% month after month                         | False  | Investing in properties in the lower cost months                     |

### 5. Conclusion
- Properties below the median price and with better conditions were suggested for purchase (total of 151 properties). 
- Properties suitable for purchase were grouped by location and season of the year. 
- The median was calculated and properties with a price below the median had an increase of 10% in their value, while properties with a price above the median had an increase of 30% above their value. 
- The best time to sell properties is in the spring, as the price is higher at that time.

### 6. Next steps
Model apartment sales prices
