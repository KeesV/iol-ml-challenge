# Machine Learning

Welcome to the Machine Learning challenge of the Xpirit Epic Event 2018. In this challenge, you will learn how to use Azure Machine Learning to predict who will be the next victim.

## About the data

Over the past years, we have compiled a data set about cardinals in the Roman Catholic Church. 
The file to import can be found in [GitHub](https://raw.githubusercontent.com/XpiritBV/GABC2018_HandsOnLabs/master/ML/TheFamily.csv).

### The Cardinals

There are hundreds of cardinals in the Roman Catholic Church. There is a strict hierarchy, a rank determines how much power an individual member has.
Over the past years, many cardinals have been murdered all over the world. There seems to be a relation between the order of which a cardinal is a member, and the chances of him being murdered. Also decorated cardinals seem to be a target.

### Summary

For every cardinal, we compiled the following information:

- CardinalId: Unique identifier
- Alive: Murdered or not
- Order:    
  1. CB - Cardinal Bishop
  2. CP - Cardinal Priest
  3. CD - Cardinal Deacon
- Name: Name
- Decorated: Cardinal has received official decoration from the Catholic Church
- YearsInOffice: How long the cardinal has been serving as an official in the Catholic Church
- ParentChild: The number of parents and children the cardinal has within the Catholic Church
- SiblingSpouse: The number of siblings and spouses the cardinal has within the Catholic Church
- PassportNr: Passport number
- PersonalWealth: Personal money hidden away on Swiss bank account x € 1000
- Continent: Continent where cardinal is from 
  - America 
  - Eurasia  
  - Africa

## Walkthrough

Either try it yourself using the file in [GitHub](https://raw.githubusercontent.com/XpiritBV/GABC2018_HandsOnLabs/master/ML/TheFamily.csv) or use the below steps to complete the workshop. In [step 3](step3.md) you will find the hints needed to complete the exercise.

1. [Step 1](step1.md); build the ML model
2. [Step 2](step2.md); deploy web service
3. [Step 3](step3.md); find the victim!
