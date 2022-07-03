# Credit_Risk_Analysis

## Purpose:

Lending Club, a peer-to-peer service, requested analysis be completed on credit card risk. Using a dataset provided by the company, several techniques are used to train and evaluate each model to determine the best to use in determing. This report will provide an overview of each and recommendations on model used and which will provide the highest accuracy results to determine high-risk loans. 

## Results: 

Six machine learning models were used to calculate precision and recall scores for the data provided by Lending Club. The balance of the loan status for the dataset indicates there are 64,784 low risk and 322 high risk loans. This information is derived by comparing loan status to all other features asked on a credit application. 

Using this information, the data was separated into test and train groups, including using a random state to ensure other tests could be  replicated. Tests were then run on ensemble groups, over sampled, under sampled and combined groups to determine the model that produces the highest accuracy. 

Ensemble models include:  

	- Balanced Random Forest Classifier model 
	- AdaBoost Classifier model 

Over sampled groups include:

	_ Random oversampling model
	_ Smote model

Under sampled groups include: 

	- ClusterCentroids model

Combination model include:  

	_ Smoteenn Combination model 

Results of each test are displayed below. 


A comparison of the accuracy results on the six models is highlighted in the table below. 


	Bal Random Forest Cls | AdaBoost Cls | Random Over Samp | Smote | ClusterCentroid | Smoteen
	______________________|______________|__________________|_______|_________________|________
	                      |              |                  |       |                 |
		.78  		    	|	 .99     	|  		.65		    |  .66  |       .66       |  .54
	______________________|______________|__________________|_______|_________________|________


Precision and recall results indicate the prediction and sensitivity percentages by model. The higher the precision the more likely the predition of loan status is correct. Recall, or sensitivity, scores indicate the ratio of time that the prediction scores are correctly predicted. Below are the results for all six models tested. 


	# Balanced Random Forest Classifier 

	![Balanced_Random_Forest_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning	\Credit_Risk_Analysis\Resources\Balanced_Random_Forest_Classifier.png") 

	# AdaBoost Classifier

	![AdaBoost_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning\Credit_Risk_Analysis\Resources	\AdaBoost_Classifier.png") 

	# Random Over Sampling 

	![Random_Sampler_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning\Credit_Risk_Analysis	\Resources\Random_Sampler_Classifier.png") 

	# Smote 

	![Smote_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning\Credit_Risk_Analysis\Resources	\Smote_Classifier.png") 

	# ClusterCentroid
	
	![Cluster_Centroid_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning\Credit_Risk_Analysis	\Resources\Cluster_Centroid_Classifier.png") 

	# Smoteenn

	![Smoteenn_Classifier]("C:\Users\kathl\OneDrive\Desktop\Bootcamp_Classwork\Projects\Module_17_Machine_Learning\Credit_Risk_Analysis\Resources	\Smoteen_Classifier.png") 


## Results: 

Based on accuracy, precision and recall it is recommended that Lender Club use the AdaBoost model to determine high and low risk loan statuses for their credit applicants. This model has a .99% accuracy rate with a precision percentage of .88% and recall of .38% for high risk loans. This indicates that the model is accurate almost all of the time. With a high precision rate of almost 90% percent that is accurate about 40% of the time, Lender Club analysts can rely on the results of loan status testing as a means of determining prospective customers that are high and low risk for lending. 

	




	
	


