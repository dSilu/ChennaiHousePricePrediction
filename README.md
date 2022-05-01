# Chennai House Price Prediction

----
![](https://github.com/dSilu/ChennaiHousePricePrediction/blob/master/D86ACBC7-9408-4C49-9361-F1072BB8D463.jpeg "src: pinterest")

Chennai is India's one of largest employment hub. To find a house for everyone in an affordable budget, we at Guvi performing this analysis to find houses around Chennai with all best possible facilities available. We have collected some data and performing the best in hand machine learning and exploratory data analysis techniques to predict prices of house.

For a better experience check the notebook @ [NBViewer](https://nbviewer.org/github/dSilu/ChennaiHousePricePrediction/blob/master/houseprice.ipynb)

Findings:
1. Listed houses in the dataset were built in between 1950 and 2010, and sold in between 2004 to 2014.
2. Hose price was record breakingly decreased during the year of 2008 to 2010 because of economical crisis in global market and natural calamities.
3. Highest number of houses were sold in 2010-11. Houses are ranges in between INR 20Lakh to more than 2 Crore.
4. Maximum number of rooms are 6, including 4 bedrooms and 2 bathrooms.
5. Sale price column has some outliers, but we can't drop them as they are actual values and there contribution is unavoidable.
6. Random Forest is a better model with coefficient of determination 98% and mean aabsolute error as minimum as. Better than rest of the regression models.

#### Builders need to take care of these things:

1. Building type and available utilities effects the house price.
2. Buildings with commercial build type and with all public facilities are very expensive.
3. In Karapakkam the streets have limited or no access, which causes the house price to drop.
4. Houses near to Gravel type of street come with highest price, followed by paved roads.
5. Streets with no access gets less value.
