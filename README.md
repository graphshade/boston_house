# Predicting House Prices in Boston

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


<h2>Reproducing the Analysis:</h2>

<p align="left">
 
1. Clone the project: Run this from the command line
 
 ```commandline
 git clone https://github.com/graphshade/boston_house.git
 ```
 
2. Set up a virtual environment and install the required packages.

3. Run the boston_house_project.ipynb file using Jupyter notebook
 
