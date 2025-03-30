# T-drive-Taxi
This model is a simple model for predicting the location of a taxi via Transformer. The model is implemented by predicting the next location through a small window of size 3. The model loss is MSE loss.

### Precautions
Limited by the computation time and loading speed of the model, I only used 10% of the data from the T-drive dataset for training and validation.

### Possible optimizations for the model:
1.Utilize more complex feature engineering. Currently, the model only encodes time and location.

2.Implement a more sophisticated model architecture. The current architecture consists of Transformer + ResNet.

3.Use long sequences for prediction and consider employing GNN or other RNN architectures to handle long-term dependencies.

4.Apply regularization techniques beyond dropout.

5.Incorporate more advanced time encoding methods, such as sinusoidal encoding, to capture periodicity.

6.Dynamically adjust the learning rate using techniques like annealing to prevent the model from getting stuck in local optima.
