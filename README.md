# Trivago Booking
 
## Abstract
The purpose of this report will be to use the Trivago Booking Data to classify hotel bookings into a possible canceled booking, or retained booking.

This can be used to gain insight into how and why bookings are canceled. This can also be used as a model to gain a marketing advantage, by advertisement targeting those who are more likely to retain their bookings, or saving money by not targeting the bookings that are most likely to cancel their bookings.

## Results
We can gather that while booking cancelations are seemingly random, they can be classified into potential cancelations or retention.
At the end of the project, we have a model witch can predict whether a booking will be canceled or not with an **accuracy of 87 %** in a dataset with a distribution of 37.04 % canceled bookings and 62.96 % retained bookings. These are significant results witch can be useful for marketing towards customers, to increase booking retention, or to help a company focus on areas of improvement.

## Model
ROC_AUC: 0.85
Accuracy: 0.87

## Analysis
In general, we found that customers are more likely to cancel a booking when they have the following features:

+ Reserved a booking with a full-board meal.
+ Reserved a booking from the groups market segment.
+ Have no special requests.
+ However, customers are more likely to retain a booking when they:

+ Have a low amount of lead time.
+ Are a repeat guest.
+ Come from the following market segment:
    + Direct
    + Corporate
    + Complementary
    + Aviation
+ Are classified as a group customer type.

These statistics can be useful for marketing towards customers, to increase booking retention, or they can be used to help a company focus on areas of improvement.
