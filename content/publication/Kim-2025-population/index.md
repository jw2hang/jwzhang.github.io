---
title: "Beyond RLHF and NLHF: Population-Proportional Alignment under an Axiomatic Framework"
date: 2026-04-01
publishDate: 2026-04-01
authors: ["Kihyun Kim", "Jiawei Zhang", "Asuman E. Ozdaglar", "Pablo A. Parrilo (Kihyun Kim and Jiawei Zhang are the first authors)"]
publication_types: ["1"]
abstract: "Conventional preference learning methods often prioritize opinions held more widely when aggregating preferences from multiple evaluators. This may result in policies that are biased in favor of some types of opinions or groups and susceptible to strategic manipulation. To address this issue, we develop a novel preference learning framework capable of aligning aggregate opinions and policies proportionally with the true population distribution of evaluator preferences. Grounded in social choice theory, our approach infers the feasible set of evaluator population distributions directly from pairwise comparison data. Using these estimates, the algorithm constructs a policy that satisfies foundational axioms from social choice theory, namely monotonicity and Pareto efficiency, as well as our newly-introduced axioms of population-proportional alignment and population-bounded manipulability. Moreover, we propose a soft-max relaxation method that smoothly trades off population-proportional alignment with the selection of the Condorcet winner (which beats all other options in pairwise comparisons). Finally, we validate the effectiveness and scalability of our approach through experiments on both tabular recommendation tasks and large language model alignment."
featured: false
publication: "*International Conference on Learning Representations (ICLR 2026)*"
---
