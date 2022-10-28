Flight_delay Prediction Project
Step1: 
	▪	Referred to requirement to get the procedure 

Step2:
	▪	Workflow for this project 
![WechatIMG6797](https://user-images.githubusercontent.com/105768533/198748606-d6ec2a66-fa9d-4578-afb3-7efa9ba1ae14.jpeg)
Original Data 
	•	 Get data from SQLite Database with random selected
	•	 11000 random rows of data
	•	 Flights with in United States from 2018-2019
Clean 
	•	 Clean Data
	•	 Choose the useful variables
	•	 Merge data from different three tables

EDA
	•	Work through EDA to understand Data 
	•	Useful Data information 
   
Feature Selection
	•	Weather conditions
	•	Day of week 
	•	Average passenger per carrier(monthly)
	•	Average scheduled departures per airports(monthly)
	•	Average passengers per airport (monthly)
	•	Average payload per carrier (monthly)
Model Selection 
![WechatIMG6798](https://user-images.githubusercontent.com/105768533/198748993-655eb1be-ee90-4800-966b-e3926a9f0759.jpeg)

Hyperparameter Tuning 

	•	Grid Search 
	•	increasing  a little bit accuracy of the models

Prediction: 
	•	We choose the Naive Bayes Classification 
  
Results:
	Arr delay distribution 
	![WechatIMG6809](https://user-images.githubusercontent.com/105768533/198748815-bf297aac-631b-4fd0-8695-f0cb75490249.jpeg)	Month vs delaydistribution  
		  
	Weather VS delay distribution 
  ![WechatIMG6813](https://user-images.githubusercontent.com/105768533/198748873-3f4cc776-8cff-4364-8c7f-71f5fcc3d05f.jpeg)
  
  Month VS delay distribution 
  ![WechatIMG6811](https://user-images.githubusercontent.com/105768533/198748924-19ff0acc-1eda-4bdd-b511-e28a3b732a23.jpeg)	•	For our regression model, the R2 is very. And, some are negative
  
  
  •	For our regression model, the R2 is very. And, some are negative
	•	For classification, the accuracy is higher. Around 0.5

Challenges:
 
	•	Finding the suitable model with higher R2
	•	Figuring out which features hold more importance
	•	Understanding the document of tables
	•	Running the grid search to get the hyper_parameters

Future Goal:
	•	More time to do the evaluation 
	•	Figure out why the regression  R2 is very low 
	•	More time to check and modify the data 
