This repository showcases my implementations of core deep learning concepts built from first principles, inspired by Andrej Karpathy’s Neural Networks: Zero to Hero series.

I begin by implementing neural network fundamentals from scratch (including backpropagation), then explore language modeling with bigram probabilities and neural networks, bridging theory with real-world machine learning workflows.

🚀 Key Highlights
Built an automatic differentiation engine from scratch (Micrograd-style)
Implemented bigram and trigram language models
Developed a multi-layer perceptron (MLP) using PyTorch
Demonstrated strong understanding of neural network internals and training dynamics
🧠 Technical Skills Demonstrated
Python
PyTorch (tensors, model training, optimization)
Backpropagation & computational graphs
Neural networks (MLP, embeddings)
Probability & statistics (log-likelihood, sampling)
Language modeling (bigram & trigram)
📚 Projects
1. Autograd Engine (Micrograd-style)

A minimal automatic differentiation engine that constructs a computational graph and performs backpropagation.

Features:

Scalar-based computation graph
Automatic gradient computation via chain rule
Topological sorting for backward pass

Concepts: Backpropagation, chain rule, computational graphs

2. Bigram Language Model (MakeMore Part 1)

A probabilistic model that predicts the next character based on the previous one.

Features:

Frequency-based probability matrix
Log-likelihood loss computation
Sampling-based text generation

Concepts: Probability distributions, generative modeling, neural networks for sequence prediction

📈 What I Learned
How backpropagation works under the hood (beyond framework abstractions)
How neural networks transform data layer by layer
The relationship between probability theory and machine learning
How modern frameworks like PyTorch implement these concepts efficiently
Practical sequence modeling using bigram/trigram approaches
🔧 Future Improvements
Extend to trigram and transformer-based models
Add training visualizations (loss curves, gradients)
Optimize performance using vectorized operations
Deploy a simple demo app for text generation
🙏 Acknowledgment

Inspired by Andrej Karpathy’s Neural Networks: Zero to Hero series.
All implementations in this repository are my own.
