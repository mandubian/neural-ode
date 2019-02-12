# Tensorflow Experiments on Neural Ordinary Differential Equations

> You can contact me on twitter as @mandubian

The notebook [tf-neural-ode-v1.0.ipynb] is a sandbox to test concepts exposed in this amazing paper:

> Neural Ordinary Differential Equations http://arxiv.org/abs/1806.07366
> Authors: Chen, Ricky T. Q. Rubanova, Yulia Bettencourt, Jesse Duvenaud, David

My idea here is to reproduce the concepts exposed in the paper fully in Tensorflow using Eager-Mode and GradientTape (I didn't want to depend on Autograd and to be able to use classic Keras models). For ODE Solver, I wanted to compare implementations in TF with Scipy very robust ones (the only one I found is Runge-Kutta Dopri5).
