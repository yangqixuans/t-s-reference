# Introduction
 + Some instructions
	 + faulty sensors and network failures are widespread phenomena that cause disruprion in the data acquisition process
	 + At a certain time step, missing data appear only at some of the channels of the resulting multivariatetime series
	 + spation-temporal imputation methods aim at reconstructing the missing parts of the signals by possibly exploiting both temporal and spatial dependencies.
 + Methods
	 + Deep learing
		 + Often disregard available relational information or rely on rather simplistic modifications of standard neural architectures tailored for sequence processing.
		 + stronger, structural, inductive biases are needed to advance the time series imputation and allow to build effective inference engines in the context of large and complex sensor networks as those found in real-world applications.
	 + [[GRIN]]
		 + Model input multivariate time series as sequences of graphs where edges represent relationships among different channels.
		 + GNNs as the building block of a novel, bidirectional recurrent neural network for [[MTSI]]
		 + Its core a recurrent neural network cell where gates are implemented by message-passing neural networks([[MPNNs]])
		 + Contributions
			 +  introduce a methodological framework to exploit graph neural networks in the context of MTSI
			 + propose a novel, practical and effective implementation of a GNN-based architecture for MTSI
			 + achieve state-of-the-art results on several and varied MTSI benchmarks.
		 + method does not rely on any assumption on the distribution of the miss-ing values (e.g., presence and duration of transient dynamics and/or length of missing sequences)other than stationarity of the underlying process
 + The rest of the paper
	 + Related works
	 + introduce the problem settings and the task of MTSI
	 + present the approach to MTSI
	 + describing the novel feameworl to implement imputation architectures based on GNNs
	 + The presented method against state-of-the art baselines
	 + draw conclusions