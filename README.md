# light-diagnostic-function
Painless step size adaptation for SGD

We address two crucial aspects of performance in neural networks: convergence and generalization: faster training does not guarantee better generalization. To balance them out, recent studies suggest using a moderately large step size for optimizers, but the added value on the performance remains unclear.

We built a simple diagnostic function by simulating different types of non-monotonocity with a growth rate and decline rate. The function allows to 1) improve both convergence and generalization of neural networks with no need to guarantee their stability; 2) build more reliable and explainable network architectures with no need for overparameterization. We refer to it as "painless" step size adaptation and call the function LIGHT (**L**og**I**stic **G**rowth with **H**arves**T**ing) as its behavior inherits the principles of population dynamics.
