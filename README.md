# World-Bank-Data-Analysis-1991-2017
Examine the top 3 countries population-wise and analyze what are their trend and pain-points.

## Inspriration

[World Bank data](https://data.worldbank.org/country) is gold mine to support crucial management decisions that can show how countries are doing and fix issues to improve people's lives. I was curious to compare how India, China & United States compare on multiple metric of real-world importance and what are the real causes that differentiates the standard of living in all three countries.

## Objective
Comparing cross-country statistics about development and people's lives around the globe and show the progress society is making through data visualization.

## Data Description
I have chosen 27 years time-series data starting 1991 - 2017. It includes three countries namely USA, India, China and average of World as a metric of comparison. Countries are compared on around 1500 metrics broken down by gender, age, employment sector, birth rate etc.

## Link to Nbviewer Python Notebook 
[Click Here](http://nbviewer.jupyter.org/github/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Python%20Notebook/Project%202%20-World%20Bank%20Data%20Analysis%201991%20to%202017.ipynb#inspiration)

## Tech-stack

* Matplotlib
* Plotly
* Python(pandas,numpy)

## Insights
> ### 1st Visualization : Analyze top three populated countries
![figure1](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/World%20population.png)
* As shown above the top three populated nations are China, India & USA in order. With China & India together constitute 36% of world population.

![figure2](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/population%20growth%20rate.png)
* China is the most populated nation in 2017. However, India is second nation with over 1Billion. Current growth rate of 1.5% suggests that if Indian government does not put stringent methods in place it will become the most populated country beating.

![figure3](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/population%20group%20by%20age.png)
* China, India, United States all three countries have nearly 60-70% of their population in working age group. This is a positive sign of country's demographic health.

> ### 2nd Visualization : Highest CO2 emission in United States?

![figure4](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/CO2%20emission.PNG)
* United States is well above World average in CO2 emmision, world average at 5% whereas USA CO2 emission rate is 20%.
* India is constantly below world average at around 0.9%
* BUT Is it the true picture? 
    * USA emits CO2, 2.2 times as China on per capita basis.But, China has 4.3 times as many people as USA! *Thus from overall perspective China emits over 70% more CO2 compared to US annually. India even greater *
    
![figure5](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/CO2%20composition.png)
* Electricity and heat production stays the main source of CO2 emission across all three countries. 
* In United States, second contributing sector is transport unlike India & China where it is residential buildings. It makes sense because in USA buildings are constructed using wood, whereas in India it is always brick and mortar.

> ### 3rd Visualization : Indian Paradox: Rising Education, Decrease in Women's Labor Force 

![figure5](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/education%20gender%20gap.PNG)
* It is paradoxical that for India the labor force participation has been declining since 2005, However since 2005 women participation in primary and lower secondary education has been higher!

![figure6](https://github.com/dkekre21/World-Bank-Data-Analysis-1991-2017/blob/master/Visualizations/labor%20force%20gender%20gap.PNG)
* It would be interesting to see female labor force participation by income group and level of education. However, the dataset is limited in capabilities to do so.
* Theory suggests that women have a curvilinear relationship between education and employment. 
    * It would mean that women with less eduation and less income would be compelled to have a job for sustenance.
    * On the other hand women with advanced education would be ambitious enough to participate in labor force.
    * It would be the women in between who do not meet the gap between mid level education and skilled job requirements.
    

## Future Scope
* Time series forecasting
* Comparing World Population based on regions, low income-high income, and development.
