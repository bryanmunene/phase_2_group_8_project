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

The analysis and summary of the model indicate that the proposed multiple linear regression model is adept at analyzing and forecasting housing prices. It suggests that enhancing the overall house will likely have a more significant effect on the property's value compared to renovating only specific parts of the house

RECOMMENDATIONS:

Expanding the living room area (sqfit_living) tends to result in higher property prices, as larger living spaces are more appealing to buyers.

Investing in bedroom upgrades can enhance the value of the property, as improved bedrooms contribute positively to overall property value.

Effective house maintenance is essential for increasing home value. Homeowners should aim for at least an average maintenance rating or above to enhance their property's worth.

Bathrooms are a crucial factor in determining home value, with the assumption being that having advanced or multiple bathrooms leads to higher property prices.

NECESSARY STEPS TO TAKE

Feedback Collection: The Hepta team will collect feedback from the Finsco team to gather additional requirements and input.

Market Analysis: We will conduct research to uncover trends in the real estate market, including demands for renovations and property features.

Data Enhancement: We aim to gather more data on various factors influencing property values, such as user preferences and additional sales and renovation information.

Model Enhancement: Our data scientists will explore alternative regression algorithms to enhance the model's performance through comparisons and improvements.

LINKS:

DATASET - [https://github.com/bryanmunene/phase_2_project/blob/master/kc_house_data.csv](https://github.com/bryanmunene/phase_2_group_8_project/blob/master/kc_house_data.csv)

Presentation - https://github.com/bryanmunene/phase_2_group_8_project/blob/master/Final%20Group%208%20Phase%202%20Project_POWERPOINT_DSF%20PT6.pptx

Notebook - https://github.com/bryanmunene/phase_2_group_8_project/blob/master/Final%20Group%208%20Phase%202%20Project_DSF%20PT6.ipynb

Column Description - https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3/blob/main/data/column_names.md

TABLEAU - https://public.tableau.com/views/KingCountySalesDashboard-Group8/KingCountySalesdashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

REPO STRUCTURE:

![image](https://github.com/bryanmunene/phase_2_group_8_project/assets/38291708/397d8de7-7512-41ab-bafe-18ee0fac31c9)



















