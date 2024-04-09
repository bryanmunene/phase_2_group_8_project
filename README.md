Group 8 DSF Phase 2 Project

MEMBERS: 

steve.abonyo@student.moringaschool.com

brian.kariithi@student.moringaschool.com

rosaline.mungai@student.moringaschool.com

ruth.nyakio@student.moringaschool.com

lynette.mwiti@student.moringaschool.com

ivan.wawire@student.moringaschool.com

OVERVIEW:

Finsco Limited, a real estate firm specializing in USA property investments, seeks to comprehend the impact of home renovations on the estimated value of residential properties, as well as the extent of this influence. They have commissioned the Hepta Group to perform multiple linear regression analysis on home sales data from a specific county in the Northwestern region. This data spans the years 2014 to 2015.

BUSINESS PROBLEM:

Finsco Limited aims to offer guidance to homeowners, real estate investors, and clients involved in house flipping regarding the influence of renovations on home pricing. They've assigned the Hepta Group to conduct multiple linear regression analysis on house sales data from a specific northwestern county provided to them.

DATA AND METHODOLOGY

DATA:

Finsco Limited supplied the Hepta Group with their dataset of King County house sales spanning 2014 to 2015. In this dataset, the price serves as the target variable, while the remaining variables act as predictors or independents. An example of this is exploring how altering the number of bedrooms impacts house prices for homeowners.

LIMITATIONS:

Upon initial examination of the data, we've identified missing values in certain predictor variables such as waterfront and view. Before proceeding, we need to determine whether these variables with missing values significantly impact home values. Additionally, we've observed non-numeric variables, which will require conversion to numerical format if they are to be utilized in constructing our model.

METHODOLOGY:

Data cleaning involves the process of eliminating duplicate entries, handling missing or null values, and converting categorical variables into numeric format for precise plotting and analysis.

Data visualization techniques employed include rendering the correlation matrix as a heatmap, creating Tableau dashboards, generating scatter plots, and constructing linear regression models.

Simple regression is utilized to predict the price variable using a single independent variable, such as sqft_living, bathrooms, or bedrooms. On the other hand, multiple regression is employed to predict the price using two or more independent variables, such as sqft_living, bathrooms, and bedrooms.

RESULTS:

Expanding the living area correlates with a rise in property price, with each additional square foot contributing to an increase of USD 279 in home value.

![image](https://github.com/bryanmunene/phase_2_group_8_project/assets/38291708/dc5c1fd1-5977-4ac5-ab03-bd2d41fb25e3)

![image](https://github.com/bryanmunene/phase_2_group_8_project/assets/38291708/a1b59218-f721-4b04-a5de-422a035ce14b)

Homes with a greater number of bedrooms tend to command higher prices, particularly within the preferred range of 3 to 6 bedrooms. Additionally, the inclusion of an extra bathroom can lead to a substantial increase in property value, amounting to USD 121,794.

The addition of more bathrooms positively impacts house prices, with each extra bathroom potentially raising the price by USD 250,000.


Enhancing the upkeep of a house can enhance its value, potentially resulting in a USD 21,460 increase in property worth.

The dimensions of the living room, the number of bathrooms, and bedrooms exert the greatest influence on home values, whereas the construction year of the house and its overall condition have comparatively minimal impact on pricing.

![image](https://github.com/bryanmunene/phase_2_group_8_project/assets/38291708/579e6499-dd4a-45cc-a962-1c2eaec265fb)



EQUATION OF THE MODEL

In the equation form y = c + B1x1 + B2x2 + B3x3 + ... + Bnx, our model indicates that the value of a home will be $5,934,570 when no renovations are undertaken.

MODEL EVALUATION:

Based on the f_value, our model appears to lack statistical significance. However, the p_value of 0.0 indicates that the model is statistically significant.

The variation in home prices can be explained by 55.8% through factors such as renovations in bedrooms, sqft_living, sqft_lot, floors, yr_built, condition_coded, and bathroom_density, where bathroom_density represents the ratio of bedrooms to bathrooms.

CONCLUSION:

1) From the analysis and model summary, can be concluded that the proposed multiple linear regression model can effectively analyze and predict the housing price. 
2) Admittedly, the prediction accuracy is still limited at specific points, and the universality of the model still needs to be improved further based on the sample data used .
3) From the baseline model, the independent variable with the highest effect on the price was floors
4) We assume renovating floors and bathrooms might impact the value of the home
5) We proceeded and found out that the bathroom was highly correlated to other independent variables ie: bedrooms, sqft_living, floors, yr_built where the correlation was above 0.5 which is a high positive correlation and concluded bathroom is a very important factor in the value of the home.
6) Because of this high multicollinearity effect of the bathroom we dropped it
7) P_values of all our models showed that they were statistically significant while the f_values of our models showed that they were statistically insignificant
8) We combined several predictor models to see if we could improve our baseline models and we found out we can improve the value of the homes by improving all rennovations

RECOMMENDATIONS:

Finsco Limited recommends prioritizing renovations that enhance the size of the living room, as increasing the square footage of living space significantly boosts home value. 

Adding each additional square foot of living space can lead to an estimated increase in home value ranging from USD 320 to USD 322. 

Upgrading bedrooms through renovations such as improving layout, fixtures, colors, and furnishings can also elevate property value, with an estimated increase of USD 48,290 to USD 65,110 per bedroom based on our regression findings.

Investing in overall improvements to the property's condition, including structural repairs, exterior coloring, fixture updates, and landscaping, could result in an approximate value increase of USD 20,530, according to our analysis.

Additionally, bathroom renovations may contribute to an increase in home value of around USD 134,700 per bathroom.

However, it's advised to prioritize overall house improvements over partial renovations in bathrooms, bedrooms, or living room space, as comprehensive renovations tend to have a greater impact on property value.

Recommend prioritizing enhancements for properties featuring over three bedrooms and more than two bathrooms, as this corresponds with the projected price range suggested by the data.

NECESSARY STEPS TO TAKE

The Hepta team will seek feedback from the Finsco team following the initial iteration and collect any further requirements and input.

In terms of market research, the Hepta group will conduct an analysis to identify real estate market trends and preferences, including renovation trends and demands for specific property features. This research will inform our decision-making process as we refine our model.

Additionally, the Hepta team will collaborate with the Finsco team to gather additional data on various features that could potentially enhance our model. This may involve collecting data on user preferences, historical renovation data, and other relevant factors affecting property prices.

To improve our model, our data scientists will explore alternative regression algorithms to assess their effectiveness and determine if they offer improvements over the current approach.

LINKS:

DATASET - https://github.com/bryanmunene/phase_2_project/blob/master/kc_house_data.csv

Presentation - https://github.com/bryanmunene/phase_2_project/blob/master/Phase%202%20Group%208%20Project%20Powerpoint.pptx

Notebook - 
(https://github.com/bryanmunene/phase_2_project/blob/master/Final%20Group%20Project.ipynb)

Column Description -
https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3/blob/main/data/column_names.md

TABLEAU - https://public.tableau.com/views/KingCountySalesDashboard-Group8/KingCountySalesdashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

REPO STRUCTURE:

![image](https://github.com/bryanmunene/phase_2_project/assets/38291708/8dc8d137-6218-4c6f-b0dc-53564a997d2e)


















