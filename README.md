<p align="center">
  <h3 align="center">Fasion MNIST Classification</h3>
</p>


## Model overview

### MLP
Number of hidden layers : 2 <br />
Loss function (objective function) : cross-entropy <br />
Optimization technique : Adam <br />
Learning rate : 0.001 <br />
Batch size for optimization step : 100 <br />
Activation function : ReLU <br />
Input layer width : 784 <br />
Input feature : pixel value <br />
Epochs : 50 <br />
Accuracy on test_data : 88.32% <br />

### CNN
Number of CNN layers : 2 <br />
Number of FFN layers: 3 <br />
Avg pooling layers: 2 <br />
Stride length: 2 <br />
Kernel filter size: 5 <br />
Loss function (objective function) : cross-entropy <br />
Optimization technique : Adam <br />
Learning rate : 0.001 <br />
Batch size for optimization step : 1024 <br />
Activation function : ReLU <br />
Input layer width : 784 <br />
Input feature : pixel value <br />
Epochs : 200 <br />
Accuracy on test_data : 89.66% <br />
