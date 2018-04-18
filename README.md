# Image Processing Analysis

# Neural Network Decision Boundary:
I will explain the question through a simpler representation called a Threshold Logic Unit.
1. A set of connection between neurons gives an activations from other neurons.
2. In the circle of above shape, the unit sums the inputs, and then applies a non-linear activation function.
3. The output line transfer the result to other neurons. The McCulloch-Pitts model was an extremely simple artificial neuron. The inputs could be either a zero or a one. And the output was a zero or a one. And each input could be either excitatory or inhibitory. Now the whole point was to sum the inputs. If an input is one, and is excitatory in nature, it added one. If it was one, and was inhibitory, it subtracted one from the sum. This is done for all inputs, and a final sum is calculated. An arrangement of one input layer of McCulloch-Pitts neurons feeding forward to one output layer of McCulloch-Pitts neurons is known as a Perceptron.

# Gradient Descent
The biggest advantages of the linear activation function over the unit step function is that it is differentiable.
This property allows us to define a cost function J(w)J(w) that we can minimize in order to update our weights.
In the case of the linear activation function, we can define the cost function J(w)J(w) as the sum of squared errors , which is similar to the cost function that is minimized in ordinary least squares linear regression.
