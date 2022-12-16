# American Express - Default Prediction
CIS 4130 Semester Project for predictions of the probability that a customer does not pay back their credit card balance amount in the future based on their monthly customer profile. I intend for each customer_ID, the probability of a future payment default. The dataset is 50GB from Kaggle and it contains aggregated profile features for each customer at each statement date. Features are anonymized and normalized, and fall into the following general categories:

●	D_* = Delinquency variables

●	S_* = Date variables

●	P_* = Payment variables

●	B_* = Balance variables

●	R_* = Risk variables

I’ll choose pyspark because it runs operations using multiple machine while pandas only use single machine. Pyspark can perform lazy operation so that we have no to wait every operations to be finished. I look forward to using machine learning algorithms like the pipeline. To help combine multiple algorithms into a single pipeline, in order to help run crossvalidator in retrieving the best logistical model for predictions.
