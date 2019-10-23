---
title: About
nav: true
---

# About

The amount of computation required for deep learning research in NLP has increased dramatically in the past few years. This has led to a surprisingly large carbon footprint for NLP experiments [(Strubell et al., 2019)](https://arxiv.org/abs/1906.02243), and to the financial cost of running experiments being increasingly burdensome for academics, students, and researchers, particularly those in emerging economies. These trends are the direct result of the NLP community primarily valuing state-of-the-art results, as opposed to comparing methods with varying amounts of data, model parameters, and hyperparameter trials ([Rogers et al., 2019](https://hackingsemantics.xyz/2019/leaderboards/); [Schwartz et al., 2019](https://arxiv.org/abs/1907.10597)).

The Green NLP workshop aims to promote efficiency as a core evaluation criterion for NLP models alongside accuracy and related measures, to improve community norms around reporting experimental results (e.g. reporting training curves for large, pretrained models), and to facilitate more robust comparisons between approaches with varying amounts of resources.
Specifically, our goal is to encourage submissions relating to:
- Improved reporting of experimental results as we vary the amount of available computation, such as the size of the model, the amount of training data, or the number of hyperparameter optimization trials ([Reimers  and  Gurevych, 2017](https://arxiv.org/abs/1707.09861); [Dodge et al., 2019a](https://arxiv.org/abs/1909.03004)).
- Methods which present efficient solutions to NLP problems. These include, among others, models that are efficient in:
    - Training data ([e.g., Schwartz et al., 2018](https://aclweb.org/anthology/P18-1028))
    - Training time (e.g., [Dettmers and Zettlemoyer, 2019](https://arxiv.org/abs/1907.04840); [Gururangan et al., 2019](https://arxiv.org/abs/1909.03004))
    - Inference time (e.g., [Dodge et al., 2019b](https://arxiv.org/abs/1909.03011))
    - Number of hyperparameter trails (e.g., [Li et al., 2017](https://openreview.net/pdf?id=ry18Ww5ee)) 
- Evaluation criteria which promote efficiency and improve comparisons between models with varying computational budgets. Many different criteria for efficiency exist, such as runtime, number of parameters, floating point operations, and dollar cost. It’s often unclear, however, which criteria to use, and some criteria are difficult to measure [(Schwartz et al, 2019)](https://arxiv.org/abs/1907.10597). We hope to make progress by encouraging the development of easy-to-use solutions for measuring efficiency.