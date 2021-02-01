# light-diagnostic-function
**Painless step size adaptation for SGD**

We address two crucial aspects of performance in neural networks: convergence and generalization: faster training does not guarantee better generalization. To balance them out, recent studies suggest using a moderately large step size for optimizers, but the added value on the performance remains unclear.

We contributed to the direction of SGD based optimization with "painless" step size adaptation. This technique allows to increase a step size by some fixed growing rate $r$ which is self-stabilized with some fixed declining rate $E$ in order to ensure best balance between convergence and generalization.

<p align="center">
<img src="https://github.com/yukinoi/light-diagnostic-function/blob/main/images/config.png" width="500" align="center">
</p>

It equips the optimizer with a simple instrument for explicit control over convergence/generalization trade-off which is the key to building reliable network architectures.
