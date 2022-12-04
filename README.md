# Debugging Deep Models

The goal of this git repository is to propose a systematic approach to detect problems in deep models and how to fix
them. Each problem will be discussed in one standalone document. This document will contain the following sections:

- Description
- Experiment setup that will detect if this problem exists
- Possible ways to remedies this problem
- Resources

You can either select a problem and separately read it or if you have a model and don't know where to start to debug,
you
can follow these steps:

1. Reduce training error to the desire level
   1. Define desire level
      1. Define the baseline, and the target metric value
   2. Reduce training error
      1. Reduce training error to zero when there is one example
      2. Keep the training error below the target value as you increase the training data set size.
2. Close the gap between testing and training error.
   1. Make sure there is correlation between train error and test error
   2. Identify the value of increasing the data set size

## How to contribute

- If you have a new approach to debug a model, please create a pull request. Please format your as
  described [here](#debugging-deep-models).
- If you have a network and you don't know how to fix it, please create a stackoverflow question and an issue here and
  tag your question. We will brainstorm in stackoverflow and then document conclusions here.
- If you find an error, disagree or typo, please create an issue or send a pull request with full description.
- If you find this repository useful, please share it.

## Resources

- [Deep Learning Rules of Thumb](https://jeffmacaluso.github.io/post/DeepLearningRulesOfThumb/)
- [MLSS 2020](https://youtu.be/c_U4THknoHE?t=4171)

