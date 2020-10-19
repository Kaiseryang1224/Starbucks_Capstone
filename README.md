# Starbucks Capstone Challenge

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run fine with Python version 3.*.

## Project Motivation<a name="motivation"></a>

Sending offers such as buy 1 and get 1 free or discount are quintessential for any business. However sending offers without proper analysis of the customers could result in suboptimal results and could sometimes result in loss of revenue too. An offer has to be sent to a person who is more likely to be incentivized to use the offer. But it should also be kept in mind to not send the offer to people who would have made a purchase without any offer. This is problem this project aims to solve for Starbucks. 

The data for this project has been provided by Starbucks. This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. This simulator has only one product offering and hence is a simpler version of the real Starbucks app.

The goal for this project is to develop two models. The first model should be able to accurately categorize people in High and Low Spend categories. This model will act as a first filter for Starbucks to decide who to send the offers to. This is because sending offers to people who are already spending high would not be optimal. The second model will predict whether or not a person will utilize an offer given the person and offer characteristics. This model will act as a second filter to which kind of offers to send. For both the models, accuracy will be used as a metric. Since the costs such cost of sending offer, cost of discounts are unknown, all are assumed to be equal and hence to maximise revenue accuracy is chosen as the metric. 


## File Descriptions <a name="files"></a>

The Satabucks_Capstone_notebook.ipynb has the code for developing the above models. The markdown cells in the file will assist in navigating the code. The data for the project can be found in the data folder

## Results<a name="results"></a>

The findings from the project have been summarized [here](https://medium.com/@sushmitha_gumireddy/starbucks-capstone-project-targeted-marketing-with-data-8799425750e0).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data has been downloaded from Udacity website. Shoutout to Starbucks for providing the data. The code can be used with no restrictions.
