# Finding Blood Donors



## Project Motivation
Blood donation is an extremely important contribution that a person can make towards the society because donating blood does not only save lives of people who need blood, it also has beneficial for donors themselves. Every day, people lose blood in accidents, injuries and surgeries, and then urgently need fresh blood to compensate for the loss so, there is a high demand for donors who are ready to donate their blood. 

Predicting if a donor will donate blood in the future can help in finding blood donation easily. Therefore, in this project, I will apply machine learning techniques on data collected from Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The goal of this project is to construct a model that predict whether or not a blood donor will give blood in future.




## File Descriptions 
- One notebook file `Finding_Blood_Donors.ipynb` which contains the code. 
- One data file `transfusion.data` The file contains a dataset from donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The center passes their blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. The dataset contains 748 donors data, each donor has:
	- Recency (months) - months since last donation.
	- Frequency (Times) - total number of donation.
	- Monetary (c.c. blood) - total blood donated in cubic centimeter
	- Time (months) - months since first donation.
	- whether he/she donated blood in March 2007 - a binary variable representing whether he/she donated blood in March 2007 (1 stand for donating blood; 0 stands for not donating blood).

## Results

Blood donation is significant for saving lives of people who lost large amounts of blood. An accurate prediction of the future supply of blood help to take the right action to save people lives. In this project, I created different classification models to predict whether or not a blood donor will give blood in future. Then, I used parameter tuning to improve the models. Random forest classification algorithm gave the best accuracy (78%). 

## Data 
The dataset is avilable in [UCI Machine Learning Repository](archive.ics.uci.edu/ml/datasets/Blood+Transfusion+Service+Center) website. 
