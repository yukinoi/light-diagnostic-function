# light-diagnostic-function
[2021:]Painless step size adaptation for SGD

We address two crucial aspects of performance in neural networks: convergence and generalization: faster training does not guarantee better generalization. To balance them out, recent studies suggest using a moderately large step size for optimizers, but the added value on the performance remains unclear.

Rather than suggesting another activation function, we put forward a simple diagnostic function which allows to 1) improve both convergence and generalization of neural networks with no need to guarantee their stability; 2) build more reliable and explainable network architectures with no need for overparameterization. We refer to it as "painless" step size adaptation. The function relies on the laws of population dynamics as an original s-shaped monotonic function but exhibits more complex behavior, leading to more reliable and explainable neural network architectures.
