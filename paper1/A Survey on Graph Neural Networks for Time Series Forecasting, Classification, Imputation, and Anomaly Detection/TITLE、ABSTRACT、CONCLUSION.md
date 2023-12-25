# [[A Survey on Graph Neural Networks for Time Series: Forecasting, Classification, Imputation, and Anomaly Detection]]
## abstract
+ In this survey, we provide a comprehensive review of graph neural networks for time series analysis (GNN4TS),
+ encompassing four fundamental dimensions: Forecasting, classification, anomaly detection, and imputation. 
+ Our aim is to guide designers and practitioners to understand, build applications, and advance research of GNN4TS. 
## GNNS FOR TIME SERIES IMPUTATION![[Pasted image 20231218221936.png]]
1. Current situation
	+ statistical methodologies
		+ mean imputation, spline interpolation, and regression models
		+ **<font color="#4f81bd">these methods often struggle to capture complex temporal dependencies and non-linear relationships within the data. </font>**
	+ deep neural network-based works
		+ **<font color="#4f81bd">they have not explicitly considered inter-time series dependen-cies</font>**
2.  In-Sample Imputation and Out-of-Sample Imputation
	+ involves filling in missing values within the given time series data
	+ predicts missing values in disjoint sequences 
3.  deterministic and probabilis-tic imputation.
	+ Deterministic imputation provides a single best estimate for the missing values
	+ probabilistic imputation accounts for the uncertainty in the imputation process and provides a distribution of possible values.