## CS336 Assignment 1: Basic, Building a Transformer LM

Github Link From: https://github.com/stanford-cs336/assignment1-basics/tree/main

### 1 Assignment Overview

In this assignment, you will build all the components needed to train a standard Transformer language model (LM) from scratch and train some models.

What you will implement:

1. Byte-pair encoding(BPE) tokenizer
2. Transformer language model(LM)
3. The cross-entropy loss function and the AdamW optimizer
4. The training loop, with support for serializing and loading model and optimizer state

What you will run

1. Train a BPE tokenizer on the TinyStories dataset
2. Run your trained tokenizer on the dataset to convert it into a sequence of integer IDs.
3. Train a Transformer LM on the TinyStories dataset.
4. Generate samples and evaluate perplexity using the trained Transformer LM.
5. Train models on OpenWebText and submit your attained perplexities to a leaderboard.
   
What you can use

We expect you to build these components from scratch. In particular, you may not use any definitions from torch.nn, torch.nn.functional, or torch.optim except for the following:

- torch.nn.Parameter
- Container classes in torch.nn (Module, ModuleList, Sequential, etc.)
- The torch.optim.Optimizer base class

You may use any other PyTorch definitions. When in doubt, consider if using it compromises the "from-scratch" ethos of the assignment.

### BPE Tokenizer



### 2.1 The unicode Stadard






