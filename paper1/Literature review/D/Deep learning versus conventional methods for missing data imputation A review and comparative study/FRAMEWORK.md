# technical summary
1. conventional statistical methods
	+ mean/median imputation
	+ regression imputation
	+ expectation-maximization
	+ [[Multiple imputation]]
	+ [[MICE]]
2. machine learning methods
	+ [[K-nearest neighbors]]
	+ [[traditional feed-forward neural network]]
	+ [[MissForest]]
3. deep learning methods
	+ Generative adversarial imputation nets [[GAIN]]
	+ [[MIDA]]
	+ [[VAE]]
	+ [[DLIN]]
## STRUCTURE
1. Problem definition
2. expriments
	1. RMSE
	2. Accuracy
	3. Conducted each experiment 100 times. We report mean RMSE and/or Accuracy along with their standard deviations (SD) as the performance metrics.
3. settings
	1. database
		1. ![[Pasted image 20231225094005.png]]
		2. It has seven real datasets and three syntheric datasets
		3. these datasets include cases with small, moderate, and large sample sizes and cases with continuous variables, categorical variables and mixe -typed variables.
	3. Generation of missing values
	4. Datapreprocessing for deep generatie models
		1. apply onehot encoding and dense embedding to transform categorical values to numerical vectors.
	5. Model training configurations
4. results
	1. Comparisons using real data
		1. Pure continuous data
		2. Pure categorical data
		3. Mixed data
	2. Comparisons using simulated data
5. discuss
	1. Advantages and disadvantages of popular missing data imputation methods.![[Pasted image 20231225095327.png]]
6. conclusion and submission