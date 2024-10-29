# Identifying Customers that are Susceptible to Churn in order to Enhance Retention Strategies and Boost Business Growth.
Identifying Customers that are Susceptible to Churn in order to Enhance Retention Strategies and Boost Business Growth
The primary objective of this project was to develop a predictive model to accurately forecast customer churn within the telecommunications industry. Utilizing historical customer data, I applied machine learning techniques to identify and analyze relevant features that influence churn behavior. The project focused on creating a robust model capable of predicting which customers are likely to discontinue services. The effectiveness of the model was measured using appropriate evaluation metrics to ensure accuracy and reliability.
## Business Overview/Problem.
Reder Telecom is facing an increasing rate of customer churn, which is the percentage of customers who switch to competitors' services or terminate their subscriptions. The telecommunications industry is highly competitive, with multiple players offering similar services, and retaining existing customers is becoming increasingly difficult. 
The specific obstacles the company faces include: 
- Intense competition from the many competitors in the market.
- Changing customer Preferences usually because of their need for personalized and high-quality services.
- Pricing pressures from competitors has affected profitability making competitive pricing very difficult to sustain.
- Network quality and performance issues that influence customer satisfaction, which leads to dissatisfaction and churning.
- Difficulty in building  and maintaining customer loyalty.
## Rationale for the Project.
Churn prediction is a strategy that uses customer data to identify clients who are least likely to renew their contracts. The significance of initiating this project lies in its potential to address the aforementioned challenges and enhance Reder Telecom's operations. Here are the top reasons that underline the importance of this project:

- **Cost Reduction:** Acquiring new customers is more expensive than retaining existing ones. Reducing churn can lead to substantial cost savings.
- **Revenue Growth:** A reduction in churn can result in increased revenue as existing customers stay longer and potentially buy additional services.
- **Customer Satisfaction:** Understanding customer behavior and preferences enables Reder Telecom to improve its services, leading to higher customer satisfaction and loyalty.
- **Competitive Advantage:** By leveraging data analytics to predict churn, Reder Telecom can proactively retain customers and gain a competitive advantage over rivals.
- **Data-Driven Decision-Making:** In an industry where data is abundant, using analytics to drive decisions can lead to more informed and effective strategies.
## Aim of the Project.
The objectives of this project are as follows:

1. Develop a predictive model to identify customers at risk of churning.
2. Analyze the key factors contributing to customer churn.
## Project Scope.
- **Data Collection:** Gather historical customer data from various sources.
- **Data Exploration:** Explore the dataset to understand the structure, statistics and get insights.
- **Data Preprocessing:** Scale variables, encode features.
- **Evaluation:** Evaluate the model on different metrics like accuracy and precision.
- **Model Development:** Build ML models to predict churn from the dataset.
- **Feature Engineering:** Create new features, segment dataset, remove irrelevant features.
## Tech Stack Used.
Python will used for this project using some of its libraries. 
## Key Skills Used.
- Python Proficiency.
- Data Preprocessing.
- Exploratory Data Analysis.
- Model Development.
- Churn Prediction.
# Steps Taken to Complete the Project.
## .1 Import packages.
All the libraries to e used were imported here.
### .2 Data Collection

Loading the dataset into Python with Pandas.
### 3. Data Exploration

In Data Exploration, I aim to understand the data, and what it contains, this include:
- understanding the data structure, statistics, and quality of the dataset,
- visualize the data to get insights,
- check for missing values


Next, we see how the target variable `ChurnLabel`, and some of the other variables are distributed.


A few things to note from these visuals:
- the dataset is almost evenly distributed between the `ChurnLabel=1` (churned) and `ChurnLabel=0` (not churned).
- the number of `Male` and `Female` gendered customers are almost equal.
- the distribution of `Segment` variable is almost even across the three Segments (`Segment A`, `Segment B` and `Segment C`).
- the number of customers of any particular `Age` in the dataset, seems to flunctuate between `200` and `500`.
