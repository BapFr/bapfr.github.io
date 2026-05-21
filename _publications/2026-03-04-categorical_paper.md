---
title: "Exact Functional ANOVA Decomposition for Categorical Inputs Models"
collection: publications
category: manuscripts
permalink: /publication/2026-03-04-categorical_paper
excerpt: 'We introduce a closed-form formulation for the Generalized Functional ANOVA on categorical domains.'
date: 2026-03-04
venue: 'ICML 2026 (Spotlight)'
paperurl: 'https://arxiv.org/pdf/2603.02673'
---

## Abstract

Functional ANOVA offers a principled framework for interpretability by decomposing a model’s prediction into main effects and higher-order interactions. For independent features, this decomposition is well-defined, strongly linked with SHAP values, and serves as a cornerstone of additive explainability. However, the lack of an explicit closed-form expression for general dependent distributions has forced practitioners to rely on costly sampling-based approximations. We completely resolve this limitation for categorical inputs. By bridging functional analysis with the extension of discrete Fourier analysis, we derive a closed-form decomposition without any assumption. Our formulation is computationally very efficient. It seamlessly recovers the classical independent case and extends to arbitrary dependence structures, including distributions with non-rectangular support. Furthermore, leveraging the intrinsic link between SHAP and ANOVA under independence, our framework yields a natural generalization of SHAP values for the general categorical setting. 
