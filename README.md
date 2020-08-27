# Project2
## Group 3
### Summary by Jonathan Park

Project 2 explored utilizing various different machine learning models to predict the price of Bitcoin. Though larger in scope initially, the project concluded with the use of Linear Regression, Gradient Boosting Regression, K-Fold Cross Validation Regression, Deep Neural Network, and finally Long Short Term Memory Recurrent Neural Network.

Supporting the project was a wide variety of stock, commodity, and macroeconomic data ranging from 1/1/2016 - 6/30/2020:
- Dow Jones Industrial Average
- NASDAQ Composite
- S&P500
- CBOE Volatility Index
- Gold
- Silver
- US Dollar Index
- WTI Crude Oil
- 10 YR Treasury Bond Yield
- Gross Domestic Product
- Consumer Price Index
- Industrial Production Index
- Unemployment Rate
- Non-Farm Payrolls
- Initial Unemployment Claims
- Federal Reserve Total Assets

As part of my contribution to the group effort, I researched and found all of the data at www.investing.com and downloaded each dataset. I subsequently cleaned the data and created a new .csv file containing all of the different datasets joined together. This was quite an extensive process as it included changing the date to date/time format, setting the date as the dataframe index, removing number shorthand ("K" for thousands, for example), and converting string datatypes to floats, among other data cleaning operations. Additionally, I carried out correlation and heatmap analysis of the data to better understand the relationship of our datasets to Bitcoin and eachother. Finally, I shared the data correlation analysis and cleaned data with my group so we could begin working on the machine learning models.

I deployed the Deep Neural Network and LSTM RNN models and had surprisingly good results with both. The Deep Neural Network, using 4 hidden layers, had an evaluation accuracy of 0.214 and the LSTM RNN had a very solid prediction of Bitcoin prices. Though the results were positive, there was also a large gap between training and testing loss curves in the Deep Neural Network, suggesting either unprepresentative data or overfitting. In hindsight, I should have used a more rigorous scientific method for trying different hyperparameters in both of the models, instead of relying on just trial and error. Also, I should have experimented more with the dropout rate as it may have aided in potential overfitting of the Deep Neural Network.

Conclusions to the project were that the models would have benefited greatly from more data input. Because Bitcoin is a relatively new asset, and lengthly historical data is not available, additional features data may be the only option to solve the need for more data. Bitcoin FnG, additional stock indices, commodities and macroeconomic data would all be welcome in a second iteration of the project. 

Rounding out my contributions to the project were the deliverables and slide presentation. Throughout the course of the project, I created the deliverables that were turned in during the class periods and also created the slide presentation. I worked to develop and refine it every couple days with the final result turning out to be satisfactory. Finally, I enjoyed the presentation and believe our group did a satisfactory job in conveying our efforts and lessons learned.

Please find my personal project submission in two parts. One is a link to the origin github repository, hosted by Richard Henderson. The other is a link to my own github repository where this personal project summary and slide presentation can be found. I had to split the submission into these 2 github repositories because my group is not currently present to approve a pull request into my branch of the origin repository.
