# Understanding the Double Descent

This work explores the Double Descent phenomenon, where test error paradoxically decays in the overparameterization regime, challenging the traditional bias-variance dilemma. By conducting experiments with Extreme Learning Machines (ELMs) and Deep Neural Networks on datasets such as Breast Cancer Wisconsin and MNIST, the study demonstrates that Stochastic Gradient Descent (SGD) acts as an implicit regularizer, favoring solutions with smaller norms even when parameters far exceed the number of training samples. Ultimately, the research concludes that high model capacity does not inherently lead to overfitting, as optimization methods like SGD prevent the capture of excessive data complexity, thereby stabilizing generalization error beyond the interpolation threshold.

---
[**View Project on GitHub**](https://github.com/oliveiraarturm/Understanding-Double-Descent/blob/main/Paper2.pdf)
