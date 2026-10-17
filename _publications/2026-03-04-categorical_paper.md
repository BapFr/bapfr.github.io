---
title: "Exact Functional ANOVA Decomposition for Categorical Inputs Models"
layout: research-paper
authors: "Baptiste Ferrere, Nicolas Bousquet, Fabrice Gamboa, Jean-Michel Loubes, Joseph Muré"
summary: "A closed-form functional ANOVA for categorical models, including dependent features and non-rectangular supports."
selected: true
selected_order: 2
highlight: "Oral presentation"
arxivurl: 'https://arxiv.org/abs/2603.02673'
codeurl: 'https://github.com/BapFr/Exact-Functional-ANOVA-Decomposition-for-Categorical-Inputs-Models'
oralurl: 'https://icml.cc/virtual/2026/oral/71107'
slidesurl: 'https://icml.cc/media/icml-2026/Slides/71107_ffAzlBv.pdf'
posterurl: 'https://icml.cc/media/PosterPDFs/ICML%202026/61430.png?t=1782314260.3022537'
collection: publications
category: manuscripts
permalink: /publication/2026-03-04-categorical_paper
excerpt: 'We introduce a closed-form formulation for the Generalized Functional ANOVA on categorical domains.'
date: 2026-03-04
venue: 'ICML 2026'
paperurl: 'https://arxiv.org/pdf/2603.02673'
---

## Abstract

Functional ANOVA offers a principled framework for interpretability by decomposing a model’s prediction into main effects and higher-order interactions. For independent features, this decomposition is well-defined, strongly linked with SHAP values, and serves as a cornerstone of additive explainability. However, the lack of an explicit closed-form expression for general dependent distributions has forced practitioners to rely on costly sampling-based approximations. We completely resolve this limitation for categorical inputs. By bridging functional analysis with the extension of discrete Fourier analysis, we derive a closed-form decomposition without any assumption. Our formulation is computationally very efficient. It seamlessly recovers the classical independent case and extends to arbitrary dependence structures, including distributions with non-rectangular support. Furthermore, leveraging the intrinsic link between SHAP and ANOVA under independence, our framework yields a natural generalization of SHAP values for the general categorical setting. 
