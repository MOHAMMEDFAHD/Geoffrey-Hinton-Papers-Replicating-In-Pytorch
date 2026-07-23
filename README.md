# Geoffrey Hinton Paper Replications

Educational **PyTorch** implementations of the most influential research papers by **Geoffrey Hinton and his collaborators**.

This repository follows the evolution of deep learning, from **Boltzmann Machines** and **Backpropagation** to **Deep Belief Networks**, **Dropout**, **Knowledge Distillation**, **Capsule Networks**, the **Forward-Forward Algorithm**, and **t-SNE**.

---

## 🎯 Goals

- Read and understand Geoffrey Hinton's foundational papers.
- Reproduce the core algorithms in PyTorch.
- Build clean, educational implementations.
- Visualize learning dynamics and learned representations.
- Document implementation details, assumptions, and simplifications.

---

# Paper Roadmap

| # | Year | Paper |
|--:|----:|--------|
| 01 | 1985 | A Learning Algorithm for Boltzmann Machines |
| 02 | 1986 | Learning Representations by Back-Propagating Errors |
| 03 | 1986 | Distributed Representations |
| 04 | 1986 | Learning Internal Representations by Error Propagation |
| 05 | 1991 | Adaptive Mixtures of Local Experts |
| 06 | 1992 | Stochastic Neighbor Embedding |
| 07 | 1994 | Autoencoders, Minimum Description Length and Helmholtz Free Energy |
| 08 | 1995 | The Helmholtz Machine |
| 09 | 1995 | The Wake-Sleep Algorithm |
| 10 | 1999 | Products of Experts |
| 11 | 2002 | Training Products of Experts by Minimizing Contrastive Divergence |
| 12 | 2006 | A Fast Learning Algorithm for Deep Belief Nets |
| 13 | 2006 | Reducing the Dimensionality of Data with Neural Networks |
| 14 | 2008 | Visualizing Data using t-SNE |
| 15 | 2009 | Deep Boltzmann Machines |
| 16 | 2010 | Rectified Linear Units Improve Restricted Boltzmann Machines |
| 17 | 2012 | Deep Neural Networks for Acoustic Modeling in Speech Recognition |
| 18 | 2012 | ImageNet Classification with Deep Convolutional Neural Networks (AlexNet) |
| 19 | 2013 | On the Importance of Initialization and Momentum in Deep Learning |
| 20 | 2014 | Dropout: A Simple Way to Prevent Neural Networks from Overfitting |
| 21 | 2015 | Distilling the Knowledge in a Neural Network |
| 22 | 2016 | Layer Normalization |
| 23 | 2016 | Using Fast Weights to Attend to the Recent Past |
| 24 | 2017 | Dynamic Routing Between Capsules |
| 25 | 2018 | Matrix Capsules with EM Routing |
| 26 | 2021 | How to Represent Part-Whole Hierarchies in a Neural Network |
| 27 | 2022 | The Forward-Forward Algorithm: Some Preliminary Investigations |

---

# Recommended Learning Path

If you're new to Geoffrey Hinton's work, a good progression is:

1. Backpropagation
2. Boltzmann Machines
3. Contrastive Divergence
4. Deep Belief Networks
5. Deep Autoencoders
6. t-SNE
7. AlexNet
8. Dropout
9. Knowledge Distillation
10. Capsule Networks
11. Forward-Forward Algorithm

---

# Repository Structure

```text
paper-name/
│
├── README.md
├── paper.pdf
├── train.py
├── model.py
├── dataset.py
├── utils.py
├── configs.py
├── requirements.txt
├── checkpoints/
└── figures/
```

---

# Philosophy

The goal of this repository is **education rather than benchmark reproduction**.

Implementations prioritize:

- readability
- modular code
- mathematical clarity
- reproducibility
- visualization
- extensive comments

Whenever the original paper uses computationally expensive experiments, simplified versions are provided while preserving the core algorithmic ideas.

---

# Disclaimer

These implementations may use:

- smaller datasets
- reduced model sizes
- fewer training epochs
- simplified hyperparameters

They should be considered **educational reproductions**, not exact replications of the original experimental results.

---

# References

Each project includes:

- Original paper
- Mathematical derivations
- Implementation notes
- Additional resources when appropriate

---

# Author

**Mohammed Fahd Abrah**

AI Engineer • Technical Writer

---

# License

This project is released under the **MIT License**.
