---
permalink: /pubs/beyond_expo/
title: ""
---

## Beyond Exponentially Fast Mixing in Average-Reward RL via Multi-Level Monte Carlo Actor-Critic

<font size = "3"> Suttle, Wesley A., et al. "Beyond Exponentially Fast Mixing in Average-Reward Reinforcement Learning via Multi-Level Monte Carlo Actor-Critic." arXiv preprint arXiv:2301.12083 (2023). </font>

<a href="https://arxiv.org/abs/2301.12083"><font size="3">Link to paper</font></a>

## Abstract

<font size = "3"> Many existing reinforcement learning (RL) methods employ stochastic gradient iteration on the back end, whose stability hinges upon a hypothesis that the data-generating process mixes exponentially fast with a rate parameter that appears in the step-size selection. Unfortunately, this assumption is violated for large state spaces or settings with sparse rewards, and the mixing time is unknown, making the step size inoperable. In this work, we propose an RL methodology attuned to the mixing time by employing a multi-level Monte Carlo estimator for the critic, the actor, and the average reward embedded within an actor-critic (AC) algorithm. This method, which we call Multi-level Actor-Critic (MAC), is developed especially for infinite-horizon average-reward settings and neither relies on oracle knowledge of the mixing time in its parameter selection nor assumes its exponential decay; it, therefore, is readily applicable to applications with slower mixing times. Nonetheless, it achieves a convergence rate comparable to the state-of-the-art AC algorithms. We experimentally show that these alleviated restrictions on the technical conditions required for stability translate to superior performance in practice for RL problems with sparse rewards. </font>