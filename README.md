# Data-Visualization
This is a Case on Real Estate House Project 
# Problem Statement

In the dynamic landscape of the residential real estate market, determining an optimal and competitive price for a house is a multifaceted challenge. Here task is to conduct a comprehensive analysis to identify and understand the myriad variables that significantly influence house prices. By leveraging advanced data analytics techniques and visualization tools,  goal is to uncover patterns, correlations, and trends within the dataset, enabling the company to make informed decisions and strategically position properties for better business opportunities.
Situation Overview

# The real estate industry is inherently complex, influenced by numerous factors that collectively impact the pricing of residential properties. The task at hand is to navigate through this complexity and extract meaningful insights from the available data. Here the objective is to not only identify the key variables affecting house prices but also to provide actionable recommendations based on your findings.

# The dataset comprises diverse parameters such as location, size, amenities, market trends, economic indicators, and historical transaction data. These variables contribute to the intricate web of pricing dynamics, and goal is  to unravel their interdependencies through meticulous analysis.

The ultimate objective is to empower the real estate company with a deeper understanding of the market forces at play. Idea is these insights will guide the pricing strategy, facilitating better decision-making for property acquisition, sales, and negotiation. 

Moreover, the case  findings may uncover opportunities for optimizing property values, enhancing customer satisfaction, and gaining a competitive edge in a dynamic and ever-evolving real estate landscape.
# Data Description 

Data set has 1460 Rows and 80 columns
4 columns have got Null Values
Unnecessary column ”Unnamed “ has been dropped
45 Object, 35 Integer and 1 Float data Type in the data Set  

# Approach To Analysis 
1. Columns are separated between Categorical and Numerical                                                                                                                                                                          
2.Columns with more than 5 unique value are categorized as Numerical

3.Sale Price has been included in the  Numerical Column category

4.Correlation was found among the numerical features with Sale Price and for the categorical Features post encoding

5.High degree Positive correlation attributes were observed , feature engineering was done

6. Different Plots like count plot, Bar Plot, scatter plot, Histogram, violin plot, Time Series Plot, Box Plot, Join Plots were used in analyzing the features and visualizing them
   
7.Market Trend and Customer preferences were observed and sale Price fluctuations with those features were captured for future considerations 


  4 columns with null values identified
 
 Alley feature with more than 90% null value, not healthy for analysis
 
 Rest null values have been replaced during analysis 


# Feature Engineering Has been done on the data Set

Columns along with its Features have been renamed as per the Data Dictionary 

‘Rename’ and ‘replace’ have been used to do the updation with column name and its features 

 Based on Similar attributes for two columns(condition1 , condition2), user defined  Column_addition  function has been created and features have been kept on a single column condition1 , condition2 column has been dropped 
# Count Plot has been used to show the features post feature engineering

 # The OverallCond (Rates the overall condition of the house-highest no as average), style of Dwelling(Maximum as 1 story), Neighborhood(Maximum as Names-North Ames) 

 ‘Original Construction Date’ and ‘ReModel Date’ column values have been checked and feature engineering used for filling null value in either of the columns

 # Market Trend and Historical Pricing

 1.Histogram indicates Cinder Block Foundation followed by Poured Contrete , with highest and 2nd highest number, few Poured contrete  have price beyond 7Lakh
 
 2.Scatter Plot (Red one) indicates mostly above ground Living area ranges between 1000 to 2500 square feet 
 
 3.Second Floor Sqft has got a linear relation with the Sale Price
 
 4.LotFrontage is missing in most case , followed by size between 30 to 150 sqft
 
 5. Most of the Houses are built in the year 2000 and Beyond
    
 6.Spike in House Price for years 2006 and 2009 


# Customer Preference and Amenities!


# Interpretation of Electrical System and House Price

Standard Circuit Breakers with Highest Price and count ,along with the spread for the Houses

Houses with Fuse Box over 60 AMP and all Romex wiring are having the second hghest price

# Interpretation between Overall Quality and SalePrice

1.Very Excellent -Overall Quality has got the highest Price, followed by excellent and very good

2.Garage Attached to Home has got the highest Pric, followed by Built-In Garage and Detached From Home

3.Basement Garage Price is placed in between No Garage and More than one Type of Garage 

4.Car Port garage is having the least price

# Interpretation of Box Plot with Fireplace Quality and No of FirePlaces

1.SalePrice of Excellent condition Fireplace quality homes with 2 no of fireplaces are the costliest

2.Maximum houses with Good condition Fire Quality are having 2 no of fire places and very few with 3 no of fire places

# Univariate and Bivariate Analysis

# Based on the Plots Interpretation is 
1.Typical garage Quality with maximum Sale Price

2.Slightly Irregular Shape of Property with highest Sale Price

3.Houses with Air Conditioning with more price

4.Customers Prefer “Good Exposure” garden level walks 

5.Good Living Quarters and unfinished are the ones with highest and 2nd highest prices 

# MultiVariate Analysis

# Based on the Box  Plots between Garage Quality and House Price

Interpretation Garage Quality VS House Price

1.Excellent Heating Quality and conditions have got the highest price

2."Gas Forced warm air Furnace " kind of heating with excellent Heating quality and Conditions have got the highest price

3.Fair condition Heating condition and Poor conditions are the 2nd least and least Sale Price house holds



# Interpreattion between Heating Quality and Condition VS House Price from Box plot

1.Excellent Heating Quality and conditions have got the highest price

2."Gas Forced warm air Furnace " kind of heating with excellent Heating quality and Conditions have got the highest price

3.Fair condition Heating condition and Poor conditions are the 2nd least and least Sale Price house holds



# Interpretation Based on Kitchen Quality and House Price

1.Houses with Excellent Quality Kitchen are the ones with highest price

2.Good Quality Kitchens are the ones with 2nd highest price




# Important Finding and Conclusion For the Case Study

1.LotFrontage (Linear feet of street connected to the property), Ovear all Qual,Year Bulit, Masonry veneer area,Type2 Finished sqft,Second Floor Sqft, Above Ground Living area are having positive correlation with Sale Price

2.  BsmtFullBath,CentralAir,FirePlaces,FullBath,GarageCars,HalfBath,PaveDrive are few key features with high positive correlation with SalePrice
3.  Customer prefer houses with maximum 2 no of Fireplaces, air conditioning
4.  There exists a strong positive trend between second Floor sqft and the price , so second floor planning need to be implemented accordingly.
5. Good Exposure garden area is a demand from the customers
6. Full Bath spaces are having high degree of preference by the customers and its impacting sales Price, they are preferred over Half Bath spaces
7. PavedDrive way is the  choice that customers are looing for , it should be incorporated on the design and implementation part
8.  2006-2007 and 2008-2009 years homes have shown an upward swing on the sale Price , mostly
9.  Houses built on the year 1991 and 2005 have got the highest and 2nd highest overall quality feed back from the customers , the houses features, properties  can be replicated for subsequent years for construction
10.  Fair height of basement that is (70-79) inches are the most preferred among the customers




# THANK YOU




 



 









