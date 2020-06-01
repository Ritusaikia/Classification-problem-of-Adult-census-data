# Classification-problem-of-Adult-census-data
This project is only for the purpose of learning and I've used the publicely available data on the Kaggle website and used some of the key methods from different kernels to learn the approaches.

# Problem Statement:
To classify the recorded individuals in the Census whether their income is greater than $50,000 or less than equal to $50,000 based on the other recorded attributes.

# Algorithms used
Tried to implement different algorithms and check how they performe on the dataset. Impemented the following algorithms:
  •	Logistic regression
  •	Random Forest
  •	Decision Trees
  •	Naïve Bayes
  •	Support Vector Machine
  •	Kernel SVM
  •	XGBoost

# Data Description
  •	Dataset was taken from Kaggle.
  •	The data was extracted from 1994 Census bureau database.
  •	The prediction to be made is to determine whether a person earns more than $50K per year or not.
  •	For this prediction many attributes are considered and a final prediction is made for the income of the targeted category.
  •	The dataset has 48842 entries extracted from the US Census Database.

# Attributes of the data
  •	age: Gives the age of the individual
  •	workclass: Gives the working class of people whether it is private or government
  •	Fnlwgt: Final weight. The number of people the census believes the entry represents.
  •	Education: Gives the education of the person whether he is high school or college graduate
  •	education-num: The highest level of education achieved by an individual in the numerical format.
  •	marital-status: Gives the details about the marital status of the person.
  •	Occupation: The occupation of the person.
  •	Relationship: Represents what an individual is relative to others.
  •	Race: Gives the race of the person i.e. White or black. 
  •	sex: Gives the gender of the person.
  •	capital-gain: Gives the capital gain of the person (income from other sources)
  •	capital-loss: Gives the capital loss of the person.
  •	hours-per-week: Gives the hours worked by the person.
  •	native-country: Give the native country of the person

# Approach of classification
  •	Finding out the problem statement i.e. to classify the income of an individual.
  •	Data Understanding: The data has missing values which are not as none or null. There are? in the data.
  •	Data Preparation: Removed the null, missing values and unappropriated values. Label encoding, OneHotEncoding and PCA.
  •	Modelling: Various models are created to classify an individual to fit into the slab of less than or greater than $50k.
  •	Evaluation: Based on the accuracy of the model the best model is recommended.
