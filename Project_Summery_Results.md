# Customer Personality Analysis
## Scenario
You are a junior data analyst working in the marketing analyst team for a ecommerce company. 

You're assigned to the 2 questions to answer: 1/ which customer segment is most likely to buy a particular product and 2/ Which product should we recommend to whom?  
# Business task
## Problem Statement
Analyze customers personality for for marketing programs.

*Tools:* Python for data cleaning and data modeling, Tableau for data visualization.

*Dataset:* [Here](https://github.com/plnh/Customer_Personality_Analysis/tree/main/Data)

*Python code:* [Here](https://github.com/plnh/Customer_Personality_Analysis/blob/main/Customer%20Personality%20Analysis.ipynb)

*Tableau:* Here

# Data exploration
To be able to answer the business question, I'll perform exploration data analysis. Most of this task will be explained in this [notebook](https://github.com/plnh/Customer_Personality_Analysis/blob/main/Customer%20Personality%20Analysis.ipynb) in which I will classify the customers of into different segments with the purpose of understanding their needs. The steps of the analysis are below 
## 1. Analysis preparation
  - Understand data: The dataset is used to analyze customer personality. The dataset's feature can be found [Here](https://github.com/plnh/Customer_Personality_Analysis/blob/main/Data/Detail.md)
  - Importing libraries: I used mainly numpy, pandas, and plotly
  - Data Preparation: I create new features for the dataset in order to define the customer personalities
  - Data cleaning: I identify missing values and outliners. Then I'll make decision on how to handle them
## 2. Data Exploratory: this is the main step of the analysis
**- Modeling clusters:**
In this step I'll organize the customers into clusters. I'll classify the customers by demographics using 4 segments:
- Stars: Old customers with high income and high spending nature.
- High Potential: New customers with high income and high spending nature.
- Need Attention: New customers with below-average income and low spending nature. 
- Leaky Bucket: Old customers with below-average income and a low spending nature.

Then I'll analyzise by products to answer which customer segment tend to buy what. Again I define 4 new segments according to the spending of customers on each product:
- Non Buyer
- Low Buyer
- Frequent Buyer
- Biggest Buyer

**- Clusters interpretation:** in this step I'll export the dataset and visualize them using tableau. The visualization can be found Here
# Results
## Findings:
**What I found from the general demoraphics segment:**

- Majority of the customers who visit the site are  in their 35-65s and have atleast one univeristy degree. They also tend to be in relationship and have atleast one child. 
- Although clients without children do not contribute to the majority, they mostly have high income and high spending nature.
- Customers with 1 child seems to have more income and spend more than the one with more than 1 child. 
- Educations and Material status seem have no affect to income and spending nature as vast majority of customers are in relationship & post-graduated as mentioned above.

**What i found from product segment:**

- 
## Recommendations
