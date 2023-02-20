# Final_Ad_Program
Final_Machine learning
INTRODUCTION FROM IDEA Proposal to remind the topic idea
Project Arrangements
Project Proposal

a.	Problem: student should create any project and main goal of project is to enable the students to develop their skills in machine learning 
b.	Background information:
I have an interest in starting coffee shop business in future, because I am good at baking desserts, however it is not easy to start business because, the success depends not only on the desserts of coffee shop , but in other different factors as service, cleanliness, the compatibility, diversity of products, and so on. Even if we will imagine that because of the great desserts , I collected enough customers to have high amount of revenue , the next issue is to hold these customers and make them constant in my coffee shop, so all the factors that I listed before affect to the churn rate that is important to know to make stable and successful business. However , only counting of how much people leaved as a customer not enough , because it is significant to know why in order to prevent it in the future. 
Nevertheless, there is another problem, the prediction is hard for person , because a lot of factors affect on the churn rate and then prediction is also hard , because we don’t know what will happen in future. 
Idea description: As a result, based on the lectures and assignment 1, I decided to create a machine learning customer churn prediction model on python. 
Brief description of your solution
o	Cleaning the dataset from unnecessary information as N.D.
o	Data analysis and their relations
o	Encoding categorical variables
o	Training the machine based on the dataset we get
o	Churn prediction model
o	Analyze which is best and predict the customers churn rate.
CONTINUATION 
I had been following the plan from the idea proposal , so 
1.	Firstly I took the dataset from this website https://raw.githubusercontent.com/carlosfab/dsnp2/master/datasets/WA_Fn-UseC_-Telco-Customer-Churn.csv
2.	As I understood there is no other datasets for churn rate , or it is hard to find them , because everywhere only this dataset.
3.	The source which had been helping me was this one: https://github.com/nitinkaushik01/Deep_and_Machine_Learning_Projects/blob/master/Churn_Prediction_of_Customers/Customer_Churn_Prediction.ipynb
4.	But almost all code there was not loading and causing errors , therefore I had been writing differently in the form which will be easy for beginner as me
5.	After importing the dataset , I started with reading and analyzing the columns of the dataset
 
 
6.	The code itself has all the explanation in it due to the fact that while writing code I had been googling every function name and its purpose to straitly know how it is working.
I started analyzing the information about people who use these services and how they vary.
 
I have plotted such kind of graphs for deep understanding , there were also another various version of graphs as circles, tables, dots. However most understandable is bar graph for me.
Then there is analyze of effect of charges per month to the churn rate
 
 
Here I took only five factors , due to the reason of ineffective columns who had not as clear effects as these 5 one. Because some of them didn’t really have an effect on churn rate as phoneservice and so on. 
7.	Then there was a stage of data cleaning 
 
By converting them to numeric values , I was able then to train my machine 
 
8.	In the beginning when I saw the churn rate, I noticed the imbalance .could fail to do as well as expected, because it will predict that customers will not churn due to high level (3/4) unchurned customer.
To solve this issue , I decided to do oversampling. It is helpful due to the choosing the samples for training set rendomly from minor class. we will continue overampling before the number of minor class will be equal for major class.
 
9.	Analyzing which model is better 
 
Result was Random Forest
 
 
In this part I had been sitting 5 hours until I realized that I messed up with the names of newer df several times in code which caused such errors.
At the end I was able to predict the churn rate for the clients
 
And as you see the results are accurate , I checked according to the id )))
That is all, Thank you for attention 

