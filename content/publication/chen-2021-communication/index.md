---
title: "Communication Efficient Primal-Dual Algorithm for Nonconvex Nonsmooth Distributed Optimization"
date: 2021-01-01
publishDate: 2023-06-12T09:48:22.163003Z
authors: ["Congliang Chen", "Jiawei Zhang", "Li Shen", "Peilin Zhao", "Zhiquan Luo"]
publication_types: ["1"]
abstract: "Decentralized optimization problems frequently appear in the large scale machine learning problems. However, few works work on the difficult nonconvex nonsmooth case. In this paper, we propose a decentralized primal-dual algorithm to solve this type of problem in a decentralized manner and the proposed algorithm can achieve an $O(1/epsilon^2)$ iteration complexity to attain an $epsilon$-solution, which is the well-known lower iteration complexity bound for nonconvex optimization. To our knowledge, it is the first algorithm achieving this rate under a nonconvex, nonsmooth decentralized setting. Furthermore, to reduce communication overhead, we also modifying our algorithm by compressing the vectors exchanged between agents. The iteration complexity of the algorithm with compression is still $O(1/epsilon^2)$. Besides, we apply the proposed algorithm to solve nonconvex linear regression problem and train deep learning model, both of which demonstrate the efficiency and efficacy of the proposed algorithm."
featured: false
publication: "*International Conference on Artificial Intelligence and Statistics (AISTATS 2021)*"
---

