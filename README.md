# Python_Grocery_Basket_Analysis
This repository showcases Python syntax for data analytics (using `pandas`, `numpy`, and `os`) and visualization libraries (`matplotlib.pyplot`, `seaborn`, `scipy`) in Jupyter Notebook within the Anaconda environment. Focused on enhancing their already successful sales, Instacart aims to delve deeper into sales patterns, particularly exploring customer variety and purchasing behaviors. Recognizing the need for a targeted approach, Instacart seeks to tailor marketing campaigns to specific customer profiles, aiming to optimize product sales. This analysis will guide the formulation of an effective strategy to ensure Instacart targets the right customers with the most relevant products. 
## Project Overview
### Motivation
Instacart, thriving in sales, aims to enhance business by understanding customer diversity and behaviors. Recognizing the need for targeted marketing, the project seeks insights to optimize strategies, ensuring precise targeting of customer segments and aligning products with preferences for increased sales impact.
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
* Step 1: IC Project Brief, Data Wrangling, and Consistency Checks
  * Comprehensive project description, research questions, data sources, and initial data cleaning steps.
* Step 2 to 5: IC Final Dataframe after Exclusion Flag
  * Merging all dataframes and applying an exclusion flag.
* Step 6: IC Derivations and Aggregations
  * Explanation of aggregate and derived variables based on stakeholders' requests.
* Step 7: IC Customer Profiling
  * Development of customer profiles derived from the customer dataframe.
* Step 8: IC Customer Profiling Questions
  * Responses to questions related to customer profiling.
* Step 9: IC Stakeholder Key Questions
  * Responses to key questions posed by stakeholders.

ChatGPT 3.5 was used to facilitate and speed the data analysis process. 
## Instacart customer profile and sales recommendations 
Stakekholders are informed about our main Python findings in the [Excel report](Rockbuster_ppt_NadiaOrdonez.pdf). The below recommendations are supported by our data analysis process.
* _Optimized Ad Scheduling:_ To enhance the effectiveness of our targeted marketing campaign, consider scheduling ads during periods with lower order volumes. The analysis indicates that Wednesdays and Thursdays between 23:00 and 06:00 experience the fewest orders on our app.
* _Strategic Advertising Timing:_ Capitalize on peak user activity and spending by focusing product advertising between 09:00 and 16:00. During these hours, our users spend each hour over 17 million dollars. Aligning marketing efforts with this active period can maximize engagement and sales.
* _Product Pricing:_ Simplify the product pricing scheme for the marketing and sales teams. Emphasize mid-range products priced between 5 and 15 dollars, as these have proven to be the most popular among our users.
* _Targeted Grocery Department Promotion:_ Acknowledge the popularity of certain grocery departments, such as produce, dairy eggs, snacks, beverages, and frozen items, where over 2 million products are ordered in each category. Consider intensifying promotions in these areas or strategizing to boost the visibility of other departments.
* _Demographic and Regional Insights_:
  * Launch a loyalty program targeting customers who currently contribute to 33.8% of all app sales. On average, these loyal customers place orders once a week, presenting an opportunity to foster continued engagement and loyalty.
  *  Leverage demographic insights to tailor marketing strategies. Recognize that customers across all US regions and family statuses exhibit similar app usage frequencies, placing orders every 10 to 11 days on average. However, note that married customers, particularly those older than 40, exhibit higher spending power, contributing to sales exceeding 160 million dollars in our current database. Consider refining marketing approaches to capitalize on these trends.
  *  Our top three middle-income customer profiles, encompassing adults with and without kids, and retirees with kids, reveal the standout influence of the "Adult with kids and middle income" category, surpassing 10 million occurrences and contributing substantially to our $163 million in sales. Despite a slightly less frequent ordering pattern, these profiles exhibit prevalence nationwide, with the Southern states leading in customer counts. In a targeted marketing campaign aimed at amplifying engagement with our key customer base, prioritizing the "Adult with kids and middle income" group is essential. Tailoring messages and promotions specifically to meet their preferences could further enhance our market share.                                                                                                               
## Project timeline
This data analysis project was completed within 7 days, using tools such as Python and Excel. 
