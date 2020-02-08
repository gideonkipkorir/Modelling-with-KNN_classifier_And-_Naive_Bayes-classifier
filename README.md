# Modelling-with-KNN_classifier_And-_Naive_Bayes-classifier
## problem statement:
**create a model that can predict survival rate in a ship taking into consideration factors sorrounding passengers aboard the Titanic.**
## Data Understanding
			**Variable **	**Definition**	**Key**
*	1	survival		Survival	0 = No, 1 = Yes
*	2	pclass		Ticket class     	1 = 1st, 2 = 2nd, 3 = 3rd
*	3	sex		Male or Female
*	4	Age		Age in years	
*	5	sibsp		# of siblings / spouses aboard the Titanic	
*	6	parch		# of parents / children aboard the Titanic	
*	7	ticket		Ticket number	
*	8	fare		Passenger fare	
*	9	cabin		Cabin number	
*	10	embarked	Port of Embarkation,	C = Cherbourg, Q = Queenstown, S = Southampton


## Experimental design
* Loading and previewing the dataset
* Data cleaning,removing and replacing null values, checking for outliers
* Undertook exploratory data analysis, both bivariate, univariate and multivariate analysis to gain insights about the data
* Modelling with KNearest Neigbhbors and Multilinear Naice Bayes , including hyper parameter tunning 
## Challenging the solution
We do not have know the true picture of the location of the passengers when the tradgy occured.Furthermore, our analysis does not incorporate the safety measures available in the a ship, e.g safety jackets or rescue boats, availability oxygen masks. 

## Did we have the right data? ## 
no,We need additional data of those survived that can help to explain the deaths
 we need to know the causes of death of the non-survivors,could be due to extreme cold, drowning etc... we also lack data on afety measures available in the a ship, e.g safety jackets or rescue boats, availability oxygen masks. 
## Follow up questions?## what unique feature did the females have that made them have better chance of survival than men?
