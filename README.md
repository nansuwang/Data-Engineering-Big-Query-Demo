# Data-Engineering-Big-Query-Demo
IDS706 Project #5: Cloud SQL
Nansu Wang

## Summary
In this assignment, I use Big Query Planform in GCP to build some useful insights.

The response variable is trip miles for each taxi order, the predictors I need to explore are the total cost of the trip, taxi company, and payment method.

An interaction may exist between payment methods and taxi companies. However, there is not enough data in some splitting categories, so this interaction term will not be included in the final model.

Multicollinearity issue exists between total cost and total tips. Thus, only one of them will be added to my final model.

Big Query Platform could be fast in SQL queries. Also, it is efficient to make plots using internal UI. Finding insights using the Big Query Platform is efficient and enjoyable.
