---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on the statistical and computational foundations of **learning and decision-making under finite data and approximation**. I study both reinforcement learning, where policies are learned through interactions with an environment, and generative models, where probability distributions are learned from observations. I draw on nonconvex optimization, statistical learning theory, and empirical-process methods.

## Reinforcement learning with neural function approximation

I study convergence and sample complexity of reinforcement-learning algorithms using neural network representations for policies and value functions. My work includes finite-sample results for [fitted Q-iteration](https://proceedings.mlr.press/v202/gaur23a.html), last-iterate guarantees for [actor–critic learning under Markovian sampling](https://proceedings.mlr.press/v235/gaur24a.html), and first-order methods for [bilevel reinforcement learning](https://papers.neurips.cc/paper_files/paper/2025/hash/617ffb01ea5b57769b0d63d5e9fefd3f-Abstract-Conference.html).

## Bilevel decision problems and statistical inference

In statistical bilevel decision problems, an outer decision depends on a response estimated or optimized at a lower level. This creates challenges for both computation and inference, especially when responses are approximate or not uniquely identified. My current work studies **orthogonal estimation, response sensitivity, confidence sets, and identification-dependent rates** for such problems, with applications to repeated-measure intervention data. [Current manuscript (in preparation)](https://muditgaur.github.io/research-preprints/Bilevel_Stat_JASA_github.pdf).

## Reliable decision-making under uncertainty and change

I am interested in robust reinforcement learning with learned transition models and finite computational effort. My planned work examines approximate robust value estimation, uncertainty-model updates, and neural policy optimization in continuous state spaces. I also study continual RL, seeking ways to improve policies on recurring or changing environments without forgetting earlier tasks. Related manuscripts are listed on the [publications page]({{ '/publications/' | relative_url }}).

## Generative models and their convergence

My research on diffusion and flow matching studies how approximation, finite-sample learning, and optimization errors affect distributional accuracy. This includes [training diffusion models without empirical risk minimizer access](https://openreview.net/forum?id=CFdNqqlqOv), [discrete-state diffusion models](https://proceedings.mlr.press/v300/srikanth26a.html), and [rectified-flow sample complexity](https://muditgaur.github.io/research-preprints/SC_of_Flow_Matching_github.pdf). Future directions include finite-time analysis for multilayer neural training and generative models for reliable decision-making.

[View publications and preprints]({{ '/publications/' | relative_url }}) · [Download CV (PDF)]({{ '/files/Mudit_Gaur_CV.pdf' | relative_url }})
