##  [[GACN]]
+ proposes to model spatial-temporal dependencies in time series data by interleaving GAT and temporal convolution layers in its encoder. It then imputes the missing data by combining GAT and temporal deconvolution layers that map latent states back to original feature spaces. 
## [[SPIN]]
+ first embeds historical observations and sensor-level covariates to obtain initial time series representations. These are then processed by multi-layered sparse spatial-temporal attention blocks be-fore the final imputations are obtained with a nonlinear transformation
## [[GRIN]]
+ introduces the graph recurrent imputation network, where each unidirectional module con-sists of one spatial-temporal encoder and two different im-putation executors. The spatial-temporal encoder adopted in this work combines MPNN and GRU . After generating the latent time series representations, the first-stage imputation fills missing values with one-step-ahead predicted values, which are then refined by a final one-layer MPNN before passing to the second-stage imputation for further processing.
## [[AGRN , DGCRIN , GARNN , and MDGCN]]
+ AGRN and DGCRIN propose different graph recurrent cells that integrate graph convolution and GRU to capture spatial-temporal relations
+  GARNN involves the use of GAT and different LSTM cells to compose a graph at-tention recurrent cell in its model architecture.
+ models time series as dynamic graphs and captures spatial-temporal dependencies by stacking bidirectional LSTM and graph convolution.
## [[PriSTI]]
+ a similar architecture of denoising diffusion probabilistic models has been adopted to effectively sample the missing data with a spatial-temporal denoising network composed of attentive MPNN and tem-poral attention.
## [[IGNNK]]
+ proposes an inductive GNN kriging model to recover signals for unobserved time series
+ the training process involves masked subgraph sampling and signal reconstruction with the diffusion graph convolution network presented in .
## [[SATCN]]
+ proposes a spatial aggregation network combined with temporal convolutions to model the under-lying spatial-temporal dependencies.