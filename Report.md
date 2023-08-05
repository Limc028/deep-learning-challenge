### Report 
# Overview: The goal of this analysis is to implement deeplearning to produce a model to determine the likelihood of success for funding 
	applicants

# Results:
	Data Preprocessing:
	- Our target for the model was an binary variable for the success or failure of the funded venture, with 1 being a success and 0 
	being a failure
	- Our features for the model included the type of application, the affiliation of the applicant, the 
	classification of the venture, the use case of the funds, the type of organisation the applicant falls under, the income amount 
	of the applicant, whether there are any special considerations for the applicant, and how much they are requesting
	- We removed the EIN and Name as these were unnecessary identifiers.

	Compiling, Training, and Evaluating the Model:
	- Our model used two hidden layers with 80 and 30 nodes respectively, both using Relu activation, and a one node output layer using sigmoid 
	activation. This set up was used to maximize the accuracy of the model using the fewest layers.
	- Our model achieved an accuracy of 72.54%, which did not manage to exceed the target.
	- Two more attempts to increase the performance were made, which failed to reach the target:
     - Increasing the number of layers to 3 hidden in the second optimisation
     - Increasing the epochs to 150

# Summary: 
Overall the model was not able to meet the target accuracy, however it is possible that it could have been exceeded if 
	more computing power was available or by continuing to make more optimisation attempts.