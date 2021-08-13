# awesome-graph-structural-learning
A curated list of amazingly awesome things regarding Graph Structural Learning.





## Table of Contents

[TOC]

## Taxonomy

The learning of graph structure is a fundamental problem of a wide range of applications. Here, we collect and summarize the toolboxes, datasets, surveys, related works and other useful open-source resources which can be modelled as a graph structural learning problem. To our best knowledge, we will cover different types of graphs, and their further applications.

-   Directed acyclic graph (e.g., Causal graph or Bayesian network, Neural network)
    -   Bayesian Network Learning
-   Undirected graph
    -   Knowledge Graph Complement
    -   Graph Neural Network Architecture Search

## Toolboxes

| Name                   | Description                                                  | Code                                                       |
| ---------------------- | ------------------------------------------------------------ | ---------------------------------------------------------- |
| CausalDiscoveryToolbox | Causal Discovery could be modelled as a dynamic learning problem of Directed acyclic graph(DAG). This is a pytorch-based toolbox, including  constraint-based methods (e..g, PC), score-based methods(e.g., GES, GS, Pairwise) as well as useful implementation of  performance measurement such as PR,SHD,SID | https://github.com/FenTechSolutions/CausalDiscoveryToolbox |
|                        |                                                              |                                                            |
|                        |                                                              |                                                            |

## Data-sets / Env

| Dataset Name | Nodes | Arcs | Average Degree | Max In-degree | Free parameters | description |                                   |
| ------------ | ----- | ---- | -------------- | ------------- | --------------- | ----------- | --------------------------------- |
| Asia         | 8     | 8    | 2              | 2             | 18              | 2.25        | prior knowledge                   |
| Alarm        | 37    | 46   | 2.49           | 4             | 509             | 13.75676    | prior knowledge                   |
| Formed       | 88    | 138  | 3.14           | 6             | 912             | 10.36364    | realdata                          |
| Sports       | 9     | 15   | 3.33           | 2             | 1059            | 117.6667    | realdata                          |
| Property     | 27    | 31   | 2.3            | 3             | 3056            | 113.1852    | defined rule + regulatig protocol |
| Pathfinder   | 109   | 195  | 3.58           | 5             | 71890           | 659.5413    | prior knowledge                   |

## Paper List

### 01 Survey

1.   M. J. Vowels, N. C. Camgoz, and R. Bowden, ‘D’ya like DAGs? A Survey on Structure Learning and Causal Discovery’, [*arXiv:2103.02582 [cs, stat]*](http://arxiv.org/abs/2103.02582), Mar. 2021.
2.   M. Scanagatta, A. Salmerón, and F. Stella, ‘A survey on Bayesian network structure learning from data’, *Prog Artif Intell*, vol. 8, no. 4, pp. 425–439, Dec. 2019, doi: [10.1007/s13748-019-00194-y](https://doi.org/10.1007/s13748-019-00194-y).
3.   C. Glymour, K. Zhang, and P. Spirtes, ‘Review of Causal Discovery Methods Based on Graphical Models’, *Front. Genet.*, vol. 10, p. 524, Jun. 2019, doi: [10.3389/fgene.2019.00524](https://doi.org/10.3389/fgene.2019.00524).
4.   B. Schölkopf *et al*., "Toward Causal Representation Learning," in *Proceedings of the IEEE*, vol. 109, no. 5, pp. 612-634, May 2021, doi: [10.1109/JPROC.2021.3058954](https://ieeexplore.ieee.org/abstract/document/9363924).

### 02 DAG-Learning

[1] X. Zheng, B. Aragam, P. Ravikumar, and E. P. Xing, [‘DAGs with NO TEARS: Continuous Optimization for Structure Learning’](https://proceedings.neurips.cc/paper/2018/hash/e347c51419ffb23ca3fd5050202f9c3d-Abstract.html), in *Advances in Neural Information Processing Systems 31: Annual Conference on Neural Information Processing Systems 2018, NeurIPS 2018, December 3-8, 2018, Montréal, Canada*, 2018, pp. 9492–9503. 

[2] Lachapelle, S., Brouillard, P., Deleu, T. & Lacoste-Julien, S. Gradient-Based Neural DAG Learning. *ICLR*, 2020, Addis Ababa, Ethiopia, April 26-30, 2020.

[3] Cussens *et al*. Polyhedral aspects of score equivalence in Bayesian network structure learning. Mathematical Programming, 164(1-2), 285–324, 2017.

[4] Y. W. Park and D. Klabjan, ‘Bayesian Network Learning via Topological Order’, *J. Mach. Learn. Res.*, vol. 18, p. 99:1-99:32, 2017.

[5] Chickering *et al*. Optimal structure identification with greedy search. *JMLR*, 3, pp. 507–554, 2003.

[6] Ramsey *et al*. A million variables and more: the Fast Greedy Equivalence Search algorithm for learning high-dimensional graphical causal models, with an application to functional magnetic resonance images. International Journal of Data Science and Analytics, pp. 1–9. 2016

[7] J. Xiang and S. Kim, [‘A* Lasso for Learning a Sparse Bayesian Network Structure for Continuous Variables’](https://proceedings.neurips.cc/paper/2013/hash/8ce6790cc6a94e65f17f908f462fae85-Abstract.html), in *Advances in Neural Information Processing Systems 26: 27th Annual Conference on Neural Information Processing Systems 2013. Proceedings of a meeting held December 5-8, 2013, Lake Tahoe, Nevada, United States*, 2013, pp. 2418–2426.

[8] Y. Yu, J. Chen, T. Gao, and M. Yu, [‘DAG-GNN: DAG Structure Learning with Graph Neural Networks]( http://proceedings.mlr.press/v97/yu19a.html), in *Proceedings of the 36th International Conference on Machine Learning, ICML 2019, 9-15 June 2019, Long Beach, California, USA*, 2019, vol. 97, pp. 7154–7163. 

[9]S. Lachapelle, P. Brouillard, T. Deleu, and S. Lacoste-Julien, [‘Gradient-Based Neural DAG Learning’](https://arxiv.org/pdf/1906.02226.pdf), 2020.

[10] H. Liu, K. Simonyan, and Y. Yang, [‘DARTS: Differentiable Architecture Search’](https://openreview.net/forum?id=S1eYHoC5FX), 2019.

[11] R. Zhu *et al.*, [‘Efficient and Scalable Structure Learning for Bayesian Networks: Algorithms and Applications’](http://arxiv.org/abs/2012.03540), *arXiv:2012.03540 [cs]*, Dec. 2020. 

### 03 UAG-Learning

[1] J. You *et al*, “Graph Structure of Neural Networks,” *ICML*, Jul. 2020

[2] lskene, Thomas, *et al*. Neural architecture search: A survey, pp. 1-21. *JMLR*, 2019. 

[3] Hanxiao Liu, *et al*. Hierarchical Representations for Efficient Architecture Search, *ICLR*, 2018.

[4] Sirui Xie, Stochastic Neural Architecture Search, *ICLR*, 2019

[5] Hanxiao Liu, *et al.* DARTS: Differentiable architecture search, *ICLR*, 2019.

[6] Senior, A.W., Evans, R., Jumper, J. *et al.* Improved protein structure prediction using potentials from deep learning. *Nature* 577, pp. 706–710, 2020.

[7] Translating embeddings for modeling multi-relational data NIPS2013

[8] Knowledge Transfer for Out-of-Knowledge-Base Entities: A Graph Neural Network Approach, *IJCAI*, 2017

