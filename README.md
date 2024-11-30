# Akka-Cluster-Fundamentals
Akka Cluster Fundamentals from akkademy


In the exercises we will be interacting with a sample microservice built for the Reactive BBQ restaurant. 
The restaurant includes a loyalty program that allows users to accumulate points each time they order. 
Once they have accumulated enough points they can deduct those points and cash them in for discounts.

This course presents a skeleton of the Loyalty Service with a minimal feature set. 
It allows us to award points to an account and deduct points from the account. 
It also ensures that an account balance never goes below zero (You can't deduct points that you don't have).