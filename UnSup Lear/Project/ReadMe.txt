Dear Participant,

Please find below the Lab for Unsupervised Learning. Kindly make your submission before the deadline.

Problem Statement -

A mobile service provider wishes to reduce customer churn. You are asked to used data science skills to help the marketing team device effective strategies to reduce the churn.

The customer database shared with you includes information about both the customers who have churned and active customers. 

Study the data. Look at the data attributes, types and make sure you understand what they mean.
Assumption is, different segments of customers will have different reasons for churn. We wish to address high value churn
Generate clusters using {kmeans, dbscan, agglomerative &amp; spectral} from this dataset without
using the labels given as the last column. Now, evaluate your clusters for purity (using the last
column as ground truth) and tabulate the results. This exercise would make you understand the
applicability of different clustering technique to a dataset. Figure out why one clustering method
give more performance than the other.
Source of data : https://mitpress.mit.edu/books/fundamentals-machine-learning-predictive-data-analyticsLinks to an external site.
Data - ACMETelephoneABT.csvView in a new window

Attributes & Description

customer - cust id/age/occupation
regionType - type of region customer lives in marriageStatus children income numHandsets handsetAge
smartPhone - Yes / No currentHandsetPrice
creditRating - credit score of the customer
homeOwner - Yes / No
creditCard - Yes / No
avgBill - Avg monthly bill
avgMins - Avg monthly call minutes
avgrecurringCharge - Avg recurring charges per month paid by the customer
avgOverBundleMins - Avg number of out of bundle minutes used by the customer
avgRoamCalls - Avg number of roaming calls made by the customer
callMinutesChangePct - %age by which the call minutes used by the customer changed from previous month to current month
billAmountChangePct - %age by which the bill amount changed
avgReceivedMins - Avg number of in-call minutes recieved by the customer
avgOutCalls - avgInCalls
peakOffPeakRatio - Ratio of peak Vs off peak calls made by the customer this month peakOffPeakRatioChangePct avgDroppedCalls - Avg number of calls dropped this month
lifeTime - Engagement duration in months
lastMonthCustomerCareCalls
numRetentionCalls - Number of times customer was called by the retention team numRetentionOffersAccepted
newFrequentNumbers - How many new numbers customer is calling frequently this mont
churn - Y /N