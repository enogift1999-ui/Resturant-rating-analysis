# Restaurant Ratings & Market Analysis
![](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/restaurant-rating-infographics-vector.jpg)

## Introduction:
This project explores the Restaurant Rating Dataset, which contains survey-based data collected in Mexico (2012), focusing on restaurant types, cuisines offered, customer demographics, and consumer preferences. Acting as a Data Analyst, contracted to analyze this dataset and extract actionable insights to guide entrepreneurs and investors in making informed decisions regarding new restaurant ventures. The analysis focuses on identifying demand-supply gaps, satisfaction levels by cuisine, and the alignment between consumer preferences and available offerings.

## Data Sourcing:
Find the the link to the restaurant rating dataset here. [Here](https://drive.google.com/file/d/1c1HKM8UTqwWOgexRLOtEJuxjBiA2N6xf/view?usp=drive_link)

## Data Modelling
This data was modelled using one to many relationship because of the presence of foreign keys. 

![](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/data%20model.png)

## Key Metrics: 
- Average rating per cuisine.
- Number of restaurants per cuisine.
- Consumer preferences per cuisine.
- Demand–supply gap (preference vs. availability).
- Demographic segmentation (age, marital status, income tier).

## Skills & Concepts Demonstrated:
This project showcased a complete data analytics workflow:

#### Data Cleaning & Preparation
- Removed duplicates and handled missing values in Excel.
- Standardized inconsistent values (e.g., budget, marital status, age groups).
- Ensured relational integrity across the 5 tables.

#### Data Analysis (SQL – pgAdmin)
- Wrote complex SQL queries to answer business questions.
- Used JOIN, GROUP BY, COUNT, AVG, and calculated fields for insights.
- Designed demand–supply gap analysis by comparing consumer preferences vs. actual restaurant availability.

#### Data Visualization (Power BI)
- Created a single-page interactive dashboard with:
    - KPIs (No. of cuisines, restaurants, consumers, reviews, avg. rating).
    - Age group and spending visualizations.
    - Top-rated cuisines and restaurants.
    - Demand vs. supply matrix.
    - Investment Score ranking.
- Implemented filters/slicers for city, age, budget, and cuisine.

#### Business Insights 
- Answered 4 business questions with actionable recommendations. you can see it here [Here](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/capstone%20Project%203.docx)
- Designed an Investment Score model to guide investors.
- Identified demographic bias in data (skew toward young, single consumers).
- Suggested targeted strategies for restaurant growth in Mexico.

This project demonstrates end-to-end data analysis skills: from cleaning and SQL querying to visualization and business decision-making.

## Visualization and Analysis:
![](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/Screenshot%20(109).png)


## Analysis:
This project explored the Restaurant Ratings & Market Analysis (Mexico, 2012) dataset, which contained five interrelated tables:
- Restaurants – details of restaurants in Mexico.
- Restaurant_Cuisine – links restaurants to one or more cuisines.
- Ratings – consumer ratings for overall experience, food, and service.
- Consumers – demographic details (age, marital status, occupation, etc.).
- Consumer_Preference – consumer budget and cuisine preferences.

The analysis was performed in SQL (pgAdmin), Excel, and Power BI. The workflow included data cleaning, SQL querying, and building interactive dashboards to answer four key business questions.

### 1. Highest-rated Restaurants & Cuisines: 
Identified the top-performing restaurants by average overall rating.
Highlighted cuisines such as Mediterranean, Japanese, and Seafood as consumer favorites.
Linked consumer preferences to restaurant success, showing how taste alignment impacts ratings.

### 2. Consumer Demographics & Biases:
Found that the 18–25 age group dominates reviews (≈80%), creating potential age-driven bias in results.
Majority of reviewers were single, influencing restaurant demand and spending patterns.
Budget analysis showed young consumers leaned toward medium and low spending categories.

### 3. Demand & Supply Gaps in Cuisines:
Strong demand but limited supply was uncovered for cuisines like American, Armenian, Bakery, and Bar.
These cuisines show high potential for new restaurant investment.
Over-supplied or saturated cuisines were flagged to avoid over-investment.

### 4. Investment-worthy Restaurant Characteristics:
Developed an Investment Score by combining demand, supply gaps, and average ratings.
Restaurants like Vips and Tacos de … emerged as strong candidates for scaling.
This scoring model provides a data-driven way to prioritize investments.

##### The insights were visualized in a single Power BI dashboard featuring:
- KPIs (cuisines, restaurants, consumers, reviews, average ratings)
- Age group distribution and spending habits
- Top-rated cuisines and restaurants
- Demand vs. supply matrix for cuisines
- Investment score rankings

## Key Insights:
- 23 cuisines and 125 restaurants were analyzed, reviewed by 138 consumers with 1,161 reviews.
- Average overall restaurant rating = 1.2, showing a tough competitive market.
- Mediterranean, Japanese, and Seafood cuisines achieved the highest average ratings.
- 18–25 age group = 80% of consumers, dominating the feedback landscape.
- Single consumers made up the majority of reviewers, influencing demand patterns.
- Most consumers preferred medium and low budget restaurants, limiting high-budget demand.
- Large demand–supply gaps exist for American, Bakery, Bar, and Armenian cuisines.
- Cuisines with oversupply (e.g., Mexican, Cafeteria) showed lower growth opportunities.
- The Investment Score model helped identify top restaurants for expansion, such as Vips.

Overall, the data revealed strong opportunities for targeted investment in under-supplied but high-demand cuisines.

You can view live visualization here [Here](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/resturant%20rating.pbix) And some Questions answered here [Here](https://github.com/enogift1999-ui/Resturant-rating-analysis/blob/main/capstone%20Project%203.docx)

## Conclusion:
This analysis reveals clear opportunities for restaurant investment in Mexico's urban dining market. Mainstream cuisines such as Mexican, Fast Food, and American are in high demand but currently underdeliver on quality and supply. Meanwhile, niche cuisines offer untapped market entry points with low competition but limited reach. Importantly, the dominant consumer demographic of young, single, medium-budget individuals should inform the style and pricing of new ventures. Overall, strategic investments can either focus on scaling high-demand concepts with improved quality or differentiating through niche offerings in unmet segments.

## Recommendation:
- Invest in high-demand, low-satisfaction cuisines like Mexican and Fast Food, focusing on raising quality standards to stand out from competitors.
- Target the dominant demographic with affordable, fast-casual formats tailored to young, urban, price-sensitive consumers.
- Explore niche cuisines (e.g., Turkish, Ethiopian, Sushi) in under-served areas to capture loyal niche audiences with minimal competition.
- Avoid oversaturated cuisines (e.g., Brewery, Mediterranean) for now, as they show balanced supply-demand and limited immediate growth potential.
- Focus on scalability, especially for mainstream categories with repeatable models that can expand across multiple locations.

Conect with me on socials:
[LinkedIn](https://www.linkedin.com/in/nnamani-gift-303a7b1ba/)
[Github](https://github.com/enogift1999-ui)
