# Cryptocurrencies

## Overview
The purpose of the this project is to gather data about crypto currencies and run it
through an Unsupervised Learning model to glean any insights into crypto currencies.

## What we did
We first preprocessed the data to prepare it for our model
- We filtered in only cryptocurrencies that were currently being traded
- Dropped any null value data
- encoded all our text based features
- standardize and scaled our data using Standardscaler

We then reduced our feature set to three Principal Components
Then we fit our Principal Component data into a K-Means model

Finally, we classified our data and created visualizations of the data by class.