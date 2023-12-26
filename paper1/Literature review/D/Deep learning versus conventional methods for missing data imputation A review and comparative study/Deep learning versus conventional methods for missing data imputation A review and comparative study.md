## abstract
 + reveiw the popular statistical,machine learning,and deep learning approaches,and discuss the adcantges and disadvantages
 + As for deep learning
	1. [[GAIN]] (generative adversarial imputation networks)
		+ onehot encoding
		+ embeding
	2. [[VAE]](variational aoto encoder)
		+ onehot encoding
		+ embedding
+ conventional methods:
	1. multiple imputation by chained equations[[MICE]]
	2. [[missForest]] 
+ missing ratios
	1. missing completely at random[[MCAR]]
	2. missing at random[[MAR]]
	3. missing not at random[[MNAR]]
## Conclusion
+ for small or moderate sample sizes, the GAINs only perform well in the case of MCAR and ofen fail in the cases of MAR and MNAR
+ VAEs are easy to fall into mode collapse in all missing mechanisms.
+ the conventional methods, MICE and missForest,are preferable for practitioners to deal with missing data imputation for tabular data with a limited sample size(<30000),in real case analyses