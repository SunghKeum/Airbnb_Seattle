<h1>Statistical Analysis of Airbnb Listings in Seattle</h1>

<h2>🏡 Overview </h2> 

This is a project where I perform a statistical analysis into Airbnb listings, specifically in the Seattle area.  

<h2>📔 About dataset</h2>

The data for this project was gathered from [insideairbnb](http://insideairbnb.com/). Insideairbnb is a company that provides data on Airbnb listings in various cities around the world. The data is comprised of listings in June of 2023 with 6636 records (listings) and 18 attributes, describing price per night, host name, number of reviews, minimum nights required, neighborhood of the listings, to name a few. You can download the data <a href='/airbnb_seattle.csv' target="_blank">here</a>. Below is a full description of the dataset.

![image](https://github.com/SunghKeum/Airbnb_Seattle/assets/117948003/9610ac73-2de8-4355-a817-9a57ac48e8ef)

<h2>🏃 Actions Taken</h2>

- Examined and prepared the dataset for analysis by renaming columns and values, changing datatype, and identifying and addressing outliers.
- Performed Exploratory Data Analysis
   - Number of listings by neighborhood
   - Number of listings by region
   - Number of listings by room type
   - Number of listings by minimum night requirement
- Conveyed summary statistics table of listing price with histogram and boxplot showing distribution.
- Crafted visuals showing average price by region, neighborhood, room type, and minimum night.
- Performed ANOVA and two-sample t-test to test for statistical significance in price difference by various attributes. 

<h2>🌟 Insights</h2>

- Identified Central as the region with highest average price per night.
- Among predominant listings by minimum night requirements, which were 1, 2, 3, 30, and 31, there was a positive relationship between average price and minimum night requirement: this revealed that there's no price "discount" for booking a listing that requires more nights of stay.
- Price distribution by neighborhood indicated that good deals exist in neighborhoods where average prices are highest.
- Price difference by minimum night requirement and region were statistically significant.
- Price difference between types of host (individual vs company) was statistically insignificant. However, there was a noticeable difference in price by host type in the West region.
- Downtown, Capitol Hill, and Central Area had the most number of listings. 
- High number of listings did not exactly translate to higher average price per night.

<h2>📁 Files</h2>

- <a href='/airbnb_seattle.csv' target="_blank">Data</a> is a csv file containing raw data about airbnb listings in Seattle.
- <a href='/MSBA320_FinalProject_AirbnbSeattle.ipynb' target="_blank">Python codes</a> executed for the analysis of this project.  
- <a href='/MSBA320_FinalProject_SungKeum.pdf' target="_blankl">Paper</a> describing data, analysis, hypothesis testing, and conclusion in greater detail.
