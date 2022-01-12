Linear Regression Assignment
                                                          By Ramraj Vasudevan (Oct'21 AI & ML Batch 1992)
This assignment is a programming assignment to build a multiple linear regression model for the prediction of demand for shared bikes.

Steps in Model building
Exploratory Data Analysis
After cleaning the data, variables were checked for their interaction with target variable, the total demand for bikes given different conditions of weather and business factors. The EDA revealed that the variable, 'season' and 'year' need to be taken as continuous variables instead of categorical. Some metrics for feel of weather condition and ratios of casual and registered users to year value were derived based on business and data driven motivations.

Data Preparation
Dummy variables were created based on categorical variables. Data was split into train and test sets. Features were normalised using MinMaxScaler. A check was done for multicollinearity.

Model Building and Selection
Variables with least Variance Inflation Factor (less than 2) were selected first to run model based on Ordinary Least Squares. Other features were added/ removed progressively. A total of 21 models were built and the last model provided the maximum R-Squared and Adjusted R-Squared numbers within acceptable p-val of less than 0.05.

Residual Analysis
Based on selected model, a Linear Regression model was run and coefficients were received. Training model was evaluated and predictions were made. Model was then evluated for distribution of error terms and homoscedasticity and found to be satisfactory.

R2 Score of Test Data
The learning from train data was used to predict the test data. The R2 Score of test data is around 0.91

Conclusion
The features having significant effect on demand for the bikes are divided into positive and negative influencers. These are listed in decreasing order of priority.

Positive Influencers
The ratio of registered users to year value was found to have maximum influence. Higher the ratio, higher is the demand. Therefore, with coming years, there should be a corresponding increase in registered users to maintain earlier demand.
Temperature plays the next best key role. With increasing temperature, the demand for bikes is seen to increase.
The year value itself is an influencer. With increasing year value, the demand can also be expected to increase.
The season is seen as an influencer. With advancing season from the beginning of a year, the demand shows an increase.
Negative Influencers
The most crucial negative influencer is Misty Weather condition. Such a condition can reduce demand for bikes.
An increase of windspeed directly reduces demand for bikes.
An increase of humidity also has the same effect of reducing demand; although to a lesser extent.
The next influencer is light snow weather condition.
An increase in heat index reduces demand of bike.
Acknowledgements
Firstly, I should thank Upgrad for their in-depth videos and content in the main and optional resources provided along with the course. The learning material in the portal and suggested additional references were very handy in gaining first hand knowledge on Linear Regression. The preparation courses and the path took by Upgrad is very helpful in providing insights into the different steps required in the model building and learning process.

Secondly, I would like to thank the mentors, both academic and non academic who took great efforts in patiently explaining even the most simple aspects and enlightening my path to knowledge and better understanding. I would like to mention Mr Vishvesh for his clear and concise explanation in providing an overall picture of the course, importance of every step in the learning process and the need for proper planning to have a smooth sailing in the course.

Thirdly, I would like to acknowledge the student support of Upgrad in enabling prompt and pointed advice to the issues and observations put up through email.

Lastly, I would like to acknowledge the help from the community of students of this batch who were forthcoming and helpful in advising and putting across their views and ideas towards the topics. A lively discussion ensues to provide guidance, support and at the same time have some light moments.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->