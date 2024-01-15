# Python_Grocery_Basket_Analysis
This repository showcases Python syntax for data analytics (using `pandas`, `numpy`, and `os`) and visualization libraries (`matplotlib.pyplot`, `seaborn`, `scipy`) in Jupyter Notebook within Anaconda. Focused on enhancing their already successful sales, Instacart aims to delve deeper into sales patterns, particularly exploring customer variety and purchasing behaviors. Recognizing the need for a targeted approach, Instacart seeks to tailor marketing campaigns to specific customer profiles, aiming to optimize product sales. This analysis will guide the formulation of an effective strategy to ensure Instacart targets the right customers with the most relevant products. 
## Project Overview
### Motivation
Instacart, thriving in sales, aims to enhance business by understanding customer diversity and behaviors. Recognizing the need for targeted marketing, the project seeks insights to optimize strategies, ensuring precise targeting of customer segments for increased sales impact.
### Objective
Address business questions posed by Instacart Management Board, regarding customer profiling and sales patterns. 
#### Customer profile questions 
* What is the distribution of customer profiles?
* Is there a difference in ordering habits of different customer profiles?
* Is there a link between customer profiles and regions or departments?
#### Stakeholder key questions 
* The sales team needs to know what the busiest days of the week and hours of the day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders.
* They also want to know whether there are particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times.
* Instacart has a lot of products with different price tags. Marketing and sales want to use simple price range groupings to help direct their efforts.
* Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
* The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviors differ in terms of loyalty, and ordering habits per region, family status, age and spending power.  
### Scope
The project focuses on conducting an initial data and exploratory analysis for Instacart, aiming to uncover sales insights and propose strategies to enhance customer segmentation based on specified criteria proposed by the Management board.
## Dataframes overview
* The Instacart datasets 2017: Orders, Orders Products Prior, Products were accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle on 19.12.2023. 
* The Customer dataset was provided by CareerFoundry.
NOTE: The Customer dataset as well as the “prices” column in the Products dataset from Instacart, were both fabricated for the purpose of the Data Analytics course by CareerFoundry.
## Python scripts
This data analysis project is organized into 9 scripts outlined below:
* [Step1](12_2023_Instacart_Basket_Analysis/03_Scripts/Step1_IC_Project Brief_data_wrangling_and_consistency_checks.ipynb): IC Project Brief, Data Wrangling, and Consistency Checks
  * Comprehensive project description, research questions, data sources, and initial data cleaning steps such as missing data, duplicates, data inconsistency, etc.
* [Step 2 to 5](12_2023_Instacart_Basket_Analysis/03_Scripts): IC Final Dataframe after Exclusion Flag
  * Merging all dataframes and applying an exclusion flag, while handling RAM memory issues.
* [Step 6](12_2023_Instacart_Basket_Analysis/03_Scripts/Step6_IC_Derivations_and_Aggregations.ipynb): IC Derivations and Aggregations
  * Explanation of aggregate and derived variables based on stakeholders' requests.
* [Step 7](12_2023_Instacart_Basket_Analysis/03_Scripts/Step7_IC_Customer_profiling.ipynb): IC Customer Profiling
  * Development of customer profiles derived from the customer dataframe.
* [Step 8](12_2023_Instacart_Basket_Analysis/03_Scripts/Step8_IC_Customer_profiling_questions.ipynb): IC Customer Profiling Questions
  * Responses to questions related to customer profiling, using visuals.
* [Step 9](12_2023_Instacart_Basket_Analysis/03_Scripts/Step9_IC_Stakeholders_key_questions.ipynb): IC Stakeholder Key Questions
  * Responses to key questions posed by stakeholders, using visuals.

ChatGPT 3.5 was used to facilitate and speed the data analysis process. 
## Instacart customer profile and sales recommendations 
Stakekholders are informed about our main Python findings in the [Excel report](Rockbuster_ppt_NadiaOrdonez.pdf). The below recommendations are supported by our data analysis process.
* _Optimized Ad Scheduling:_ To enhance the effectiveness of our targeted marketing campaign, consider scheduling ads during periods with lower order volumes. The analysis indicates that Wednesdays and Thursdays between 23:00 and 06:00 experience the fewest orders on our app.
* _Strategic Advertising Timing:_ Capitalize on peak user activity and spending by focusing product advertising between 09:00 and 16:00. During these hours, our users spend each hour over 17 million dollars. Aligning marketing efforts with this active period can maximize engagement and sales.
* _Product Pricing:_ Emphasize mid-range products priced between 5 and 15 dollars, as these have proven to be the most popular among our users.
* _Targeted Grocery Department Promotion:_ Acknowledge the popularity of certain grocery departments, such as produce, dairy eggs, snacks, beverages, and frozen items, where over 2 million products are ordered in each category. Consider intensifying promotions in these areas or strategizing to boost the visibility of other departments.
* _Demographic and Regional Insights_:
  * Launch a loyalty program targeting customers who currently contribute to 33.8% of all app sales. On average, these loyal customers place orders once a week, presenting an opportunity to foster continued engagement and loyalty.
  * Recognize that customers across all US regions and family statuses exhibit similar app usage frequencies, placing orders every 10 to 11 days on average. However, note that married customers, particularly those older than 40, exhibit higher spending power, contributing to sales exceeding 160 million dollars in our current database. Consider refining marketing approaches to capitalize on these trends.
  * Our top 3 customer profiles are from a middle-income, encompassing adults with and without kids, and retirees with kids. Here in particular, the customer profile "Adult with kids and middle income" standouts, by surpassing 10 million counts and contributing over $90 million to our total sales of $163 millions. Despite a slightly less frequent ordering pattern, our top 3 profiles exhibit prevalence nationwide, with the Southern states leading in customer counts. To amplify engagement with our key customer base, a targeted marketing campaign focusing on the "Adult with kids and middle income" group is crucial. Tailoring messages and promotions to meet their preferences can further enhance our market share.                                                                                                     
## Project timeline
This data analysis project was completed within 7 days, using Python for data analysis and visualization and Excel for stakeholder reporting. 
