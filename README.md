# A Non-Traditional Linear Regression

This repository demonstrates how to implement linear regression using Particle Swarm Optimization.

A linear regression model has the following form:

<p align="center">
  <img src="assets/generalform.png" alt="General Form" width="400px"/>
</p>

In this equation:

<p align="center">
  <img src="assets/explanation.png" alt="Explanation" width="400px"/>
</p>

Once the model is constructed, we need to measure its performance. For this purpose, we use the Mean Square Error (MSE).

MSE is defined as follows:

<p align="center">
  <img src="assets/mse.png" alt="MSE" width="400px"/>
</p>

In this equation:

<p align="center">
  <img src="assets/explanation_mse.png" alt="Explanation MSE" width="400px"/>
</p>

Finally, to implement linear regression using Particle Swarm Optimization, we aim to find the minimum of the MSE function to perform the regression. We consider each particle as a vector of weights for our model.
