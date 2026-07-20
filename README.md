# Geoffrey Hinton Paper Replications

Educational PyTorch implementations of the most influential papers by **Geoffrey Hinton and collaborators**.

The repository follows the historical development of deep learning, from backpropagation and Boltzmann machines to dropout, knowledge distillation, capsule networks, and the Forward-Forward algorithm.

## Goals

- Read foundational papers.
- Reproduce their core ideas in PyTorch.
- Keep implementations simple and educational.
- Visualize training, evaluation, and learned representations.
- Clearly document all simplifications.

## Paper Roadmap

| # | Paper | Year | Status |
|---:|---|---:|:---:|
| 01 | A Learning Algorithm for Boltzmann Machines | 1985 | [ ] |
| 02 | Learning Representations by Back-Propagating Errors | 1986 | [ ] |
| 03 | Distributed Representations | 1986 | [ ] |
| 04 | Learning Internal Representations by Error Propagation | 1986 | [ ] |
| 05 | Adaptive Mixtures of Local Experts | 1991 | [ ] |
| 06 | Autoencoders, MDL and Helmholtz Free Energy | 1994 | [ ] |
| 07 | The Helmholtz Machine | 1995 | [ ] |
| 08 | The Wake-Sleep Algorithm | 1995 | [ ] |
| 09 | Products of Experts | 1999 | [ ] |
| 10 | Contrastive Divergence | 2002 | [ ] |
| 11 | A Fast Learning Algorithm for Deep Belief Nets | 2006 | [ ] |
| 12 | Reducing Dimensionality with Neural Networks | 2006 | [ ] |
| 13 | Deep Boltzmann Machines | 2009 | [ ] |
| 14 | Rectified Linear Units Improve RBMs | 2010 | [ ] |
| 15 | Deep Neural Networks for Acoustic Modeling | 2012 | [ ] |
| 16 | AlexNet | 2012 | [ ] |
| 17 | Initialization and Momentum | 2013 | [ ] |
| 18 | Dropout | 2014 | [ ] |
| 19 | Knowledge Distillation | 2015 | [ ] |
| 20 | Layer Normalization | 2016 | [ ] |
| 21 | Fast Weights | 2016 | [ ] |
| 22 | Dynamic Routing Between Capsules | 2017 | [ ] |
| 23 | Matrix Capsules with EM Routing | 2018 | [ ] |
| 24 | Part-Whole Hierarchies | 2021 | [ ] |
| 25 | Forward-Forward Algorithm | 2022 | [ ] |

## Recommended Starting Path

1. Backpropagation  
2. Boltzmann Machines  
3. Contrastive Divergence  
4. Deep Belief Networks  
5. Deep Autoencoders  
6. AlexNet  
7. Dropout  
8. Knowledge Distillation  
9. Capsule Networks  
10. Forward-Forward  

## Repository Structure

```text
paper-replications/
├── README.md
├── requirements.txt
├── shared/
└── papers/
    ├── 01_boltzmann_machine/
    ├── 02_backpropagation/
    ├── 03_distributed_representations/
    └── ...
```
Important Note

These implementations may use smaller datasets, fewer epochs, and reduced architectures. They should not be presented as exact reproductions unless the original experimental setup is closely matched.

Author

Mohammed Fahd Abrah
AI Engineer and Technical Writer

License

MIT License
