



**1.  Project Summary**
		This project develops a machine learning model that predicts a salary of a person based on their background information.

  

**2. The approach I will take to address this problem is:**  
    

	1- Exploratory data analysis
    
    2 - Baseline model. Have a simple model first: predicting salary of
    a person based on one feature alone, that is industry. Then
    calculate the error rate for this baseline model. The metric that I
    use here is MSE.
    
    3- Data preprocessing. Process the data so that it can be prepared
    to be put into ML models.
    
    4- Developing ML models. I choose 4 different models and pick one
    that performs the best
    
    5- Tune the one model that is selected.
    
    6- Feature importance graph.

**3.  Data sets:**  
    

1,000,000 entries.

The features of the dataset:

 - Categorical:  
	 - Nominal:
		
			    
			-   Industry  
			-   Major
			-   jobID
			-   companyID



	-   Ordinal:  
    

				-   jobType  
				    
				-   Degree  
    

-   Numerical:  
    

				-   yearsExperience  
				    
				-   milesFromMetropolis  
				    
				-   salary
