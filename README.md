**ABSTRACT**

In today's fast-paced business environment, keeping customers
engaged and converting them into long-term users is a major
challenge for marketers. Analyzing customer data and
Customer segmentation is important because it allows
businesses to understand their customers better, make
marketing efforts, improve customer experiences. This project
explores the customer data and show how machine learning
and data analytics can help businesses better understand their
customers by focusing on conversion rate prediction, churn
prediction, and customer lifetime value estimation.

The goal is to build a predictive model that analyzes user
behavior during purchase and determines the possibilities for
conversion. By identifying patterns the model highlights
potential high-value customers, detect those at risk of leaving,
and enable businesses to take protective steps.
The implementation of customer segmentation using machine
learning is expected to have a significant impact on business
growth, marketing efficiency, and customer retention. By
analyzing customer behavior, spending patterns, and subscription trends, this project can help businesses make data-
driven decisions to enhance customer experience and increase
profitability. The insights gained from this research pave the
way for smarter, more effective marketing campaigns tailored
to individual customer needs.

It is important to understand the behavior of customers for any
business that wants to improve its engagement, retention, and
maximize revenue. Companies can utilize new customer data
using advanced analytics and machine learning algorithms to
identify churn and segment the audience and predict CLV.
Customer segmentation enables businesses to classify various
groups of customers based on their spending behavior, purchase
frequency, age , location, subscription status and several other
important parameters which makes it possible to personalize
marketing efforts.

Through purchasing patterns, location, subscription type, and
spending patterns, businesses are able to learn customer
preferences, making it possible for them to take more strategic
actions.
A significant portion of this project revolves around churn
prediction. This helps the business to identify the customers that
may leave or unsubscribe to the paid version so the business can
tailor customized and personalized marketing strategies. Also, the
business can appreciate the customers with high value percentage.
The goal of this project is to highlight the insights retrieved from
integrating and analyzing the pattern and possibilities of the data.

**DATA COLLECTION AND PREPROCESSING**

ALGORITHMS UTILISED
To extract meaningful insights, three machine learning
algorithms have been implemented:
  --> K-Means Clustering
  --> Logistic Regression
  --> Linear Regression

K-Means Clustering is a unsupervised algorithm. It helps the
model to group customers based on similarities in their behavior,
shopping pattern, frequency of purchase making it easier to
personalize marketing strategies.
K-Means Clustering

The algorithm works by:
Choosing the number of clusters k. This defines how many
groups the data will be divided into.
It define initial cluster centers (centroids) randomly within
the dataset. Assigns each data point to the nearest centroid
based on distance.
This process is repeated until the centroids stop changing
significantly, meaning the clusters are well-formed.

Logistic Regression
Logistic Regression is used to classify the column subscription
status that has yes or no values.
The algorithm works by:
Taking input features such as purchase frequency and
subscription status.
It predicts the probability based on the condition.
Classifying the output based on a threshold. If the
probability is above the threshold, it is classified as one
category; otherwise, it belongs to the other.

Linear Regression
Linear Regression is used for predicting continuous values
based on input features. It finds relationships between variables
by fitting a straight line to the data, making it useful for
forecasting trend.
The feature used by logistic regression are :

In this model logistic regression is used to find the possibility
percentage of churn customers based on the condition if the
subscription status is yes but the frequency of purchase and
review rating is less than 3.

Identification of Customer Segments

The bar chart provides the distribution of the age group based on the
amount they spend. Middle aged are the high spenders and frequently
purchasers. And the pie chart provides a clear visualization of gender
wise classification of spending.

**KEY FINDINGS**

The predicted conversion percentage is 77.5%, this percentage is
calculated using columns such as subscription status, frequency of
purchase, review rating, and the amount they spend. If the spending is
higher than 25 dollar and the subscription status is NO and also their
frequency of purchase is more than 6 times a year.
The churn prediction is done using the logistic regression and utilizes
columns such as frequency of purchase, spending amount, review
rating and subscription status. If the review rating is less than 3 and
the frequency of purchase is less than 6 times a year there is a high
chance of churn here.

Programming Language-Python
Development Environment-Jupyter Notebook

**Libraries & Frameworks**
Pandas – For data manipulation and preprocessing.
NumPy – For numerical computations.
Scikit-learn – For implementing machine learning models (K-Means, Logistic Regression, Linear Regression).
Matplotlib & Seaborn – For data visualization and exploratory data analysis (EDA).

**Data Source**
Kaggle – The dataset was collected from Kaggle
