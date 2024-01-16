# Neural Net
In this project I have written a feed forward neural net framework which allows to build neural networks with arbitrary depth and arbitrary number of neurons in each layer.<br>

- Supports the following activation functions -
1. relu
2. leaky relu
3. tanh
4. sigmoid
5. linear
6. softmax

- Supports the following tasks - 
1. Regression
2. Binary Classification
3. Multiclass Classification
4. Multilabel Classification <br>
Cost function suitable to the task is used.

- Trains the parameters in a vectorized manner using Adaptive Moment Estimation (ADAM). The batch size can be determined. Supports learning rate decay as well.
  
- Supports regularization.

For the mathematics used in this project, refer to - 
- https://explained.ai/matrix-calculus/index.html
- https://jonaslalin.com/2021/12/10/feedforward-neural-networks-part-1/
- https://jonaslalin.com/2021/12/21/feedforward-neural-networks-part-2/
- https://jonaslalin.com/2021/12/22/feedforward-neural-networks-part-3/

Content - 
- NN_framework.py
