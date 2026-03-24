This project, titled Marketing Analytics for a Portuguese Bank, uses machine learning to predict whether a customer will subscribe to a term deposit following a direct marketing (phone call) campaign.

The core objective is to build a response model that identifies the prospects most likely to respond, allowing the bank to optimize its telemarketing efforts by targeting the top deciles of customers.

Dataset Overview

The analysis is based on a dataset from a Portuguese banking institution containing approximately 41,188 to 45,211 observations with various customer attributes.

Customer Data: Age, job type, marital status, and education.

Financial Indicators: Credit default status, average yearly balance, and existing housing or personal loans.

Campaign Data: Contact type (cellular/telephone), last contact duration, and the number of contacts performed during the campaign.

Social/Economic Context: Employment variation rate, consumer price index, and euribor 3-month rate.

Key Insights from the Analysis

Exploratory Data Analysis (EDA) reveals several factors that significantly influence a customer's likelihood to subscribe:

Economic Profile: Customers with a higher account balance (specifically above $1,490) show a much higher propensity to subscribe.

Age Groups: Subscription rates are highest among customers under 30 and over 50 years old.

Contact Frequency: Marketing efficiency drops if a customer is contacted more than 4 times during a single campaign.

Demographics: Professionals in "admin" jobs, highly educated individuals, and married customers are more likely to accept term deposit offers.

Modeling and Strategy

The analysis involves testing various classification models, including Logistic Regression, k-Nearest Neighbors (kNN), Support Vector Machines (SVM), and Random Forest.

Realistic Prediction: A specific version of the model is built without the "duration" variable, as the duration of a call is not known before the call is made, making it impractical for real-world prospect targeting.

Business Objective: The strategy aims to capture 80% of total responders while minimizing marketing costs by calling the minimum number of prospects identified by the model's probability scores.
