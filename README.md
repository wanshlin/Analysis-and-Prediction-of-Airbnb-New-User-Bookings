# Analysis and Prediction of Airbnb New User Bookings

This capstone project aims to solve whether a newly registered Airbnb user will book his/her travel or not with analysis on a variety of data including user information and browsing session records. By coming up with a model that could accurately predict new users' booking behaviour, Airbnb can better forecast users' demand, carry out individually targeted promotional campaigns, and find the effective optimization of their network/app.


Data:
-------------------------------
Source: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data

The data contain a list of users along with their demographics, web session records, and some summary statistics. There are 12 possible outcomes of the users' booking destination country: 'US', 'FR', 'CA', 'GB', 'ES', 'IT', 'PT', 'NL','DE', 'AU', 'NDF' (no destination found), and 'other'. 'NDF' is different from 'other' because 'other' means there was a booking, but is to a country not included in the list, while 'NDF' means there wasn't a booking.


Approach:
-------------------------------
The project was divided into several steps:

1. **Data Exploration:** Extensive data visualisation and summary statistics were used to find trends and insights from the train_users and sessions datasets.
2. **Feature Engineering:** From the insights discovered in the previous step, raw data were transformed into features that better represent the underlying problem of the predictive model.
3. **Machine Learning:** Various classifiers were tested and the best classifier was hyperparamter tuned by using Grid Search Cross Validation. 


Results:
-------------------------------

1. **The number of newly registered Airbnb users with booking increased at the roughly same rate as the users who did not book before July, 2021, however, the booking users had been experiencing a smaller increasing since then.** Under the deepening of market segmentation and the stimulation of increasing homogeneous competition, Airbnb are facing with greater challenges. Airbnb may need to analysis and redesign their competitive strategy.

2. Women who aged betwen 28 and 37 years old are the more likely to book on Airbnbs. **More marketing resources should be targeted to these people  to increase their rate of conversion.**

3. The majority of booking users are on Mac Desktop and they come without any affiliate marketing channels. Also, the average browing time of booking users are 40% higher compared with non-booking users. Thus, **some resources should be transfer from affiliate marketing to the improvement of the user experience of desktop, especially Mac Desktop.**







