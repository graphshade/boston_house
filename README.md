# Predicting House Prices in Boston

<img src="https://i.imgur.com/pWBEwXX.png" />

<h2>Problem statement</h2>
The current model used by the City of Boston to predict the assessed value of properties has a high root mean squared error. In other words, there is high uncertainty associated with the predicted house prices. This hinders the City's ability to forecast revenue from property taxes precisely within a specified margin of error for effective budgeting and planning. Also, the assessed value of some properties is underestimated such that the City of Boston is losing tax revenue. The situation is critical and warrants immediate action.

<h2>Languages and Libraries Used</h2>

- Python
- [List of libraries](https://github.com/graphshade/loan_default/blob/main/renv.lock)

<h2>Environment Used </h2>

- <b>Ubuntu 22.04.1 LTS</b>


<h2>Key Findings & Recommendation:</h2>

1. Properties with extreme features like properties with more than 10 rooms or properties with living area over 2000 square footage tend to be underestimated causing the City of Boston to lose tax revenue. Based on this, it is recommended that the City of Boston should favor a differential property tax rate other than a fixed tax rate

2. Lastly, if the City of Boston wants to increase its tax revenues, it may adopt social policies to reduce population density in certain neighborhoods and increase the overall median income of citizens. The city may also give tax incentives to encourage homeowners to own properties with larger living area per square footage



<h2>Recommendations:</h2>

Based on the findings, the following recommendations were made:
1. Operate the model at the 50% predictive probability of default threshold. At this level, the selected model can identify 63% of loan default cases. Historically, this could saved $3 million in loan defaults.This saving in loan default is computed without taking into consideration the cost of associated with wrongly classifying a non-default loan as default. Specifically, operating at the 50% threshold results into wrongly classing 9 out of every 100 observations

2. The customer service department may use the predicted probability of default to segment borrowers and device an outreach campaign targeted at the various segments. For instance, for customers with high probability of default, the customer service department may constantly follow up to understand their financial situation and help them restructure their payment plan

<h2>Reproducing the Analysis:</h2>

<p align="left">

1. [Install R and RStudio](https://techvidvan.com/tutorials/install-r/)
 
2. Clone the project: Run this from the command line
 
 ```commandline
 git clone https://github.com/graphshade/loan_default.git
 ```
 
3. Install Required Libraries Using Virtual Environment: 
   
   You may install the libraries directly on your computer however, using the virtual environment library `renv`. [Follow this guide to install renv](https://www.youtube.com/watch?v=yc7ZB4F_dc0)
   1. Open the app.R file in RStudio
   2. In the RStudio console run `renv::init()` to initiate the renv virtual environment and install the required libraries from the [renv.lock](https://github.com/graphshade/loan_default/blob/main/renv.lock) file 
