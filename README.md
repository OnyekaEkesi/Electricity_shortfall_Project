# Predicting Load Shortfall Of Electricity Generated In Spain 

## Project Description

In this undertaking, we developed a regression model tailored to forecast the deficit in electricity load every three hours in Spain accurately. The term "load shortfall" pertains to the variation between renewable and non-renewable energy generation. The Spanish government is contemplating additional investments in renewable energy and requires detailed insights into the prevailing trends and patterns of both renewable and non-renewable energy generation in the country. More specifically, they aim to predict the daily load shortfall under specific conditions such as wind speed, pressure, humidity, and other relevant factors.

## Feature

We used a regression model to make predictions on the dataset, the model was deployed using flask on an EC2 instance for easy access to non technical stakeholders.

## Tools used

* Python
* AWS EC2
* GitHub
* Sklearn
* Flask


## Installation

1. pip install ipython (preferably Python 3.10.11)
2. Install the project dependencies including pandas, numpy, matplotlib, and scikit-learn using the following command: <br> 
pip install -U matplotlib numpy pandas scikit-learn <br> 

## Result 

We were able to visualize the three hourly shortfall by days of the week from the dataset as seen in the graph below: 

<p align = 'center'>
<img width="700" height="400" src = 'https://github.com/OnyekaEkesi/Pics_for_github_project_readme/blob/main/load-shortfall/insight.jpg?raw=true'>
</p>
We used a regression model to make predictions using different models and RSME score and the R-squared score as an evaluation metrics, the random forest model performmed better and was used to make the final prediction of the given dataset. The model was deployed using flask on an EC2 instance. <br> 


## Conclusion

Through continuous assessment and testing iterations of our model, we successfully identified an improved version capable of predicting the three-hourly load deficits in renewable power generation in Spain. Subsequently, we provided recommendations regarding the optimal renewable energy resources for the Spanish government to consider investing in.
## Acknowledgement
I would like to also acknowledge the contribution made by my teammates who embarked on this project with me:

* Emmanuel Osayande
* Al-Moaruf Ajasa
* Mmatlou Matlakala
* Ibrahim Olasupo
* Olaniyi Samuel <br> 

### Note:
* Code cannot be shared publicly due to the nature of this project
