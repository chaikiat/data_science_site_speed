# Data Science Portfolio

About Me
    - I am Chai Kiat Kho (CK), currently in the May 2022 cohort of the Optus University/Macquarie Univeristy Data Science 1 micro-credential course
    - I am also a Senior Digital Analyst at Optus, working with the Digital Personalisation team
    - My work email is: chaikiat.kho@optus.com.au
    - My GIT ID is: ck-kho-1

### Portfolio Status

1. Portfolio 1 
    - __Status: Completed and Committed (commit message: Commit | Portfolio 1 | 25Jul)__
    - _Git organisation name: MQ-Data-Science-OptusU-2022-May_
    - _Repository name: portfolio-ck-kho-1_
    - _File name: Portfolio 1.ipynb_

2. Portfolio 2
    - __Status: Completed and Committed (commit message: Commit | Portfolio 2 | 25Jul)__
    - _Git organisation name: MQ-Data-Science-OptusU-2022-May_
    - _Repository name: portfolio-ck-kho-1_
    - _File name: Portfolio 2.ipynb_

3. Portfolio 3
    - __Status: Completed and Committed (commit message: Commit | Portfolio 3 | 25Jul)__
    - _Git organisation name: MQ-Data-Science-OptusU-2022-May_
    - _Repository name: portfolio-ck-kho-1_
    - _File name: Portfolio 3.ipynb_

### Portfolio Findings Summary

1. Portfolio 1 
    - 2) Analysis of Property Sales
        - 2A) Average price of houses were higher than units and townhouses.
        - 2B) As I would expect - The larger the building area, the larger the price of the property.
        - 2C) For 2 bedrooms, the average price of houses were also higher than units and townhouses.
        - 2D) The average price of a house has gone down over the period 2016 to 2018. However, the trend was not the same for units - where it went up in 2017 and                   then down in 2018 to a level even lower than the 2016 average.
    - 3) Challenge
        - The top 5 suburbs with highest proportion of unit sales were all located in the Melbourne CBD area, where land is scarce and majority of homes are units.
        - The top 5 suburbs with lowest proportion unit sales were all located outside of the Melbourne CBD area, where land is more abundant and hence more houses are             available.

2. Portfolio 2
    - Analysis of Game Sales
        - 1D) The extreme outlier for NA_Sales and EU_Sales was Wii Sports, which was also the extreme outlier for Global_Sales. This indicates that the cause of the                   outlier was due to the fact that Wii Sports had extreme sales in both North America and Europe, hence totaling up to an extreme Global sales.
        - 2B) North America market is more closely correlated to Europe market, hence a game's sales in the North American market is a better predictor of success in                   Europe.
        - 2C)
            - In North America, popularity of role-playing games is rather low. Whereas the popularity of the other genres are rather balanced.
            - This is quite similar to Europe where role-playing and fighting games are less popular, while the other genres are rather balanced.
            - However in Japan, there are bigger differences in popularity across different genres. While role-playing and strategy games are very popular, shooter and                 racing games are actually very poor in popularity.
            - While Role-Playing games are the least popular of all genres in North America, it is actually the most popular genre in Japan.
            - On the other hand - while Shooter games are the most popular genre in North America, it is actually the least popular in Japan
        - 2D)
            - There is a positive relationship between critic and user score - in that the higher the critic score for that year, the higher the user score as well
            - The average critic score went up in 2012 and maintained at high levels, however the average user score did not have the same trend. In fact average user                  scores dropped in 2007, and has stayed lower than average until 2016
            - This indicates that the improvement in critic scores especially in the recent years are not consistent with general users, hence making the critic                        scoring not representative of the general population
            - Due to this, the data here does indicate some evidence to support the claim that critics are indeed pressured to give more positive reviews. At least                     from 2012 onwards.
    - Challenge
        - Game 1 - in a popular, established section of the market.
            -  Recommendation
                -   In order to have a strong chance of success in a popular and established section of the gaming marketing in Japan, it is recommended to release a product on: 3DS platform, role-playing genre with a 'M' rating.
            - Summary
                -   The platform with the largest sales since 2011 to 2015 is 3DS (Darkest Red) - indicating that this is the most popular platform in the recent years                     till 2015
                - The genre with the largest sales since 2011 to 2015 is Role-Playing (orange) - indicating that this is the most popular genre in the recent years                         till 2015
                - The rating with the largest number of users since 2011 to 2015 is M (Pink) - indicating that this is the most popular game rating in the recent years                     till 2015
        - Game 2 - in an emerging space that has been historically underserved.
            -   Recommendation
                -   In order to have a strong chance of success in an emerging space that has been historically underserved in Japan, it is recommended to release a                        product that has been hugely popular across the other markets (NA, EU, Others) but not as close in popularity in Japan. The recommmendation will                        be to release a product that is: X360 platform, Shooting genre with a 'M' rating.
            -   Summary
                -   X360 was top 2 best selling platform in Non-JP markets, but only number 9 in JP market - indicating a very popular platform that has not yet hit                        its potential in JP market.
                -   Shooter was top 3 best selling genre in Non-JP markets, but only number 9 in JP market - indicating a very popular genre that has not yet hit its                        potential in JP market.
                -   M was top 2 best selling genre in Non-JP markets, but only number 3 in JP market - indicating a very popular rating that has not yet hit its                            potential in JP market.

3. Portfolio 3
    - Clustering
        - 6.6) Number of clusters for cluster analysis
            - Both dendrograms for Total Customers and Churned Customer are rather identical, indicating that cluster charisteristics is most likely to be similar                      across both types.
            - When a line is drawn on 220 of the Total Customers dendrogram, it shows 5 clusters. Since this is consistent with the 5 clusters observed in the "Elbow"                  method we will proceed to create a model based on 5 clusters.
        - 6.10) Cluster Characteristics
            -   Cluster 1 (Orange): They tend to have certain attributes that are highest or longest compared to the other clusters - like plan access fee, months of                   contract remaining, last fx contract duration and monthly spend. Indicating that these are the highest customer lifetime value consumer customers, who                  are generally on higher value and longer term plans.
            -   Cluster 2 (Green): They tend to have rather high attributes for plan access fee, months of contract remaining, last fx contract duration, previous                      contract duration. And are generally have handset with their service plan. Indicating that this cluster are medium-high customer lifetime valye                        consumer customers, who generally get on longer-term plan with a device and tend to stick with the telecommunications company.
            -   Cluster 4 (Purple): They have the highest attributes for service tenure and CFU level. Indicating that this cluster are generally small business                        customers, who tend to be on longer term services with the telecommunications company. They generally stick to the same telecommunications provider                    for their business operations.
            -   Cluster 3 (Red): They tend to have certain attributes that are the lowest compared to the other clusters - like service tenure, plan access fee, plan                    tenure, months of contract remaining, last fx contract duration, previous contract duration and monthly spend. They are also mainly on no-contract BYO                  plans that do no include handsets and the plan is not contract based. Indicating that this cluster are generally more short-term and value-for-money                    consumers, who are most probably on prepaid mobile plans that are lower cost and short-termed, and using their own handsets that is not necessary                      purchased from this telecommuncations company. And has a higher chance of switching to another provider to access more value-for-money prepaid plans.
            -   Cluster 0 (Blue): They are generally in the middle level in terms of most attributes, however many of them are off contract. Indicating that these are                  the most general consumer customer types, in the middle in terms of plan value and service term with the telecommunications company and are ought to                    be targeted for a new contract to keep them as active customers.
    - Predictive Modeling
            - Model C uses 9 input variables to predict the value of 'CHURN_IND'
            - Model C has highest R Squared and lowest MSE across all models, this indicates that Model C is the most accurate model

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------



