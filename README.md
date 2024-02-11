
This is a demonstration of using DoWhy and EconML to solve a causal inference problem. Problem is as follows:

A hotel group holds data for different hotels and resorts. Data ranges from room rate, amenities desired, refundable or non-refundable deposit etc. 
The group wants to offer a refundable deposit ability to a random group of customers as they could lose deposit money if everyone has a refundable deposit and cancels.
They want to see if this service could impact a customer becoming a repeated guest and the impact that this could have on the total days stayed by the average guest.

A model is fit using DoWhy and the conditinal average treatment effect (cate) is found using EconML estimators. 
A policy is then given that shows the effect of positive and negative treatment.

Data: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
