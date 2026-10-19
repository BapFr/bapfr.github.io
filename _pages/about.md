---
layout: academic
permalink: /
title: "Baptiste Ferrere"
home: true
description: "PhD student in Applied Mathematics at Université de Toulouse and EDF R&D. Statistical learning theory and nonparametric interaction models for XAI, uncertainty quantification and interpretability."
redirect_from:
  - /about/
  - /about.html
---

<header class="home-heading">
  <p class="eyebrow">Mathematics for Interpretability</p>
  <h1>Baptiste Ferrere<span class="name-dot" aria-hidden="true" style="color: var(--blue)">.</span></h1>
  <p class="home-subtitle">Statistical Learning Theory, Nonparametric Interaction Models, Interpretability, XAI, UQ</p>
</header>

<div class="introduction">
  <p>I am a Ph.D. student in Applied Mathematics at <a href="https://www.univ-tlse3.fr/">Université de Toulouse</a>, in collaboration with <a href="https://www.edf.fr/en/the-edf-group/who-we-are/activities/research-and-development">EDF R&amp;D</a> through a CIFRE partnership.</p>
  <p>My research lies at the intersection of <strong>statistical learning theory</strong> and <strong>nonparametric interaction models</strong>, motivated by questions in explainable AI, uncertainty quantification and model interpretability.</p>
  <p>I am deeply interested in the theoretical and mathematical foundations of machine learning. I particularly enjoy developing methods grounded in statistical learning theory, functional decompositions and functional analysis, and using them to address concrete problems in explainable AI.</p>
  <p>I study how to represent and estimate individual effects and interactions between variables, particularly when the inputs are dependent and their distribution is unknown.</p>
  <p>My recent contributions include explicit representations for generalized functional ANOVA and minimax guarantees for additive regression under unknown dependent designs.</p>
</div>

<dl class="advisors">
  <div><dt>Academic supervisors</dt><dd><a href="https://www.math.univ-toulouse.fr/~gamboa/">Fabrice Gamboa</a><br><a href="https://jmltoulouse.github.io/jmloubes/">Jean-Michel Loubes</a></dd></div>
  <div><dt>Industrial supervisors · EDF</dt><dd><a href="https://bousquet-n.github.io/research/">Nicolas Bousquet</a><br><a href="https://josephmure.wordpress.com/">Joseph Muré</a></dd></div>
</dl>

<section class="content-section" aria-labelledby="news-heading">
  <div class="section-heading"><h2 id="news-heading"><span class="section-number" aria-hidden="true">01</span>News</h2></div>
  <ul class="news-list">
    <li><time datetime="2026-10">Oct 2026</time><p>I am visiting <a href="https://uqam.ca/">Université du Québec à Montréal (UQAM)</a> throughout October 2026, working with <a href="https://freakonometrics.github.io/">Arthur Charpentier</a> and <a href="https://marouaneilidrissi.com/fr/index.html">Marouane Il Idrissi</a> on interpretability and fairness.</p></li>
    <li><time datetime="2026-10-03">Oct 2026</time><p>Our new preprint <a href="https://arxiv.org/abs/2609.39212">Minimax Additive Regression under Unknown Dependent Designs</a> is available on arXiv!</p></li>
    <li><time datetime="2026-04">Apr 2026</time><p>Our paper on functional ANOVA for categorical inputs was accepted at <strong>ICML 2026</strong> for an <span style="color: var(--blue)">oral presentation</span>.</p></li>
  </ul>
  <details class="news-archive"><summary>Earlier news</summary><ul class="news-list">
    <li><time datetime="2026-05">May 2026</time><p>Our new preprint <a href="https://arxiv.org/abs/2605.18422">Generalized Functional ANOVA: A Complete Theoretical Framework</a> is available on arXiv!</p></li>
    <li><time datetime="2026-03">Mar 2026</time><p>Our new preprint <a href="https://arxiv.org/abs/2603.02673">Exact Functional ANOVA Decomposition for Categorical Inputs Models</a> is available on arXiv!</p></li>
    <li><time datetime="2025-10">Oct 2025</time><p>Our new preprint <a href="https://arxiv.org/abs/2510.07088">Fourier Analysis on the Boolean Hypercube via Hoeffding Functional Decomposition</a> is available on arXiv!</p></li>
  </ul></details>
</section>

<section class="content-section" aria-labelledby="papers-heading">
  <div class="section-heading"><h2 id="papers-heading"><span class="section-number" aria-hidden="true">02</span>Selected publications</h2><a class="section-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">↗</span></a></div>
  {% assign selected_papers = site.publications | where: 'selected', true | sort: 'selected_order' %}
  {% for paper in selected_papers %}{% include research-paper.html paper=paper compact=true %}{% endfor %}
</section>

<section class="content-section" aria-labelledby="research-heading">
  <div class="section-heading"><h2 id="research-heading"><span class="section-number" aria-hidden="true">03</span>Research directions</h2></div>
  <div class="research-topics">
    <article><span class="topic-symbol" aria-hidden="true">ℒ</span><h3>Statistical learning theory</h3><p>Statistical guarantees for nonparametric models, including minimax rates for additive regression under unknown dependent designs.</p></article>
    <article><span class="topic-symbol" aria-hidden="true">ƒ</span><h3>Nonparametric interaction models</h3><p>Representation and estimation of main effects and higher-order interactions using functional decompositions and generalized ANOVA.</p></article>
    <article><span class="topic-symbol" aria-hidden="true">φ</span><h3>Interpretability &amp; UQ</h3><p>Functional decompositions for model interpretability and uncertainty quantification; ongoing work on interactions in transformer architectures.</p></article>
  </div>
</section>

<section class="content-section" aria-labelledby="background-heading">
  <div class="section-heading"><h2 id="background-heading"><span class="section-number" aria-hidden="true">04</span>Background</h2><a class="section-link" href="{{ '/cv/' | relative_url }}">Full CV <span aria-hidden="true">↗</span></a></div>
  <p class="background-note">Before my Ph.D., I worked on functional ANOVA for correlated inputs during a research internship at EDF R&amp;D. I hold an M.Sc. in Statistical Learning from <a href="https://www.ip-paris.fr/">Institut Polytechnique de Paris</a> and an engineering degree from <a href="https://www.ensae.fr/">ENSAE Paris</a>.</p>
</section>
<div class="contact-note"><p>For research discussions and collaborations, <a href="mailto:{{ site.author.email }}">get in touch <span aria-hidden="true">↗</span></a>.</p></div>
