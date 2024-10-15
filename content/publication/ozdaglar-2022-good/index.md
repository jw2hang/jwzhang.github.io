---
title: "What is a Good Metric to Study Generalization of Minimax Learners?"
date: 2022-06-01
publishDate: 2023-06-12T09:48:22.161686Z
authors: ["Asuman Ozdaglar", "Sarath Pattathil", "Jiawei Zhang", "Kaiqing Zhang (Authors are listed in alphabetical order and Jiawei Zhang is the corresponding author)"]
publication_types: ["1"]
abstract: "Minimax optimization has served as the backbone of many machine learning problems. Although the convergence behavior of optimization algorithms has been extensively studied in minimax settings, their generalization guarantees, i.e., how the model trained on empirical data performs on the unseen testing data, have been relatively under-explored. A fundamental question remains elusive: What is a good metric to study generalization of minimax learners? In this paper, we aim to answer this question by first showing that primal risk, a universal metric to study generalization in minimization problems, fails in simple examples of minimax problems. Furthermore, another popular metric, the primal-dual risk, also fails to characterize the generalization behavior for minimax problems with nonconvexity, due to non-existence of saddle points. We thus propose a new metric to study generalization of minimax learners: the primal gap, to circumvent these issues. Next, we derive generalization bounds for the primal gap in nonconvex-concave settings. As byproducts of our analysis, we also solve two open questions: establishing generalization bounds for primal risk and primal-dual risk in this setting, and in the strong sense, i.e., without assuming that the maximization and expectation can be interchanged. Finally, we leverage this new metric to compare the generalization behavior of two popular algorithms - gradient descent-ascent (GDA) and gradient descent-max (GDMax) in minimax optimization."
featured: false
publication: "*Advances in Neural Information Processing Systems 35 (NeurIPS 2022)*"
---

