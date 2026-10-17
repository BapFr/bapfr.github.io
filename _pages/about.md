---
layout: academic
permalink: /
title: "Baptiste Ferrere"
home: true
description: "PhD student in Applied Mathematics at Université de Toulouse and EDF R&D. I study functional decompositions and statistical learning for interpretable machine learning."
redirect_from:
  - /about/
  - /about.html
---

<header class="home-heading">
  <p class="eyebrow">Applied mathematics &amp; explainable AI</p>
  <h1>Baptiste Ferrere<span class="name-dot" aria-hidden="true" style="color: var(--blue)">.</span></h1>
  <p class="home-subtitle">Understanding models through mathematics.</p>
</header>

<div class="introduction">
  <p>I am a Ph.D. student in Applied Mathematics at <a href="https://www.univ-tlse3.fr/">Université de Toulouse</a>, in collaboration with <a href="https://www.edf.fr/en/the-edf-group/who-we-are/activities/research-and-development">EDF R&amp;D</a> through a CIFRE partnership.</p>
  <p>I develop mathematically grounded methods for <strong>interpretable machine learning</strong>. My research combines functional decompositions, Hilbert-space methods and nonparametric statistics to understand <strong>interaction effects under dependent inputs</strong>.</p>
</div>

<dl class="advisors">
  <div><dt>Academic supervisors</dt><dd><a href="https://www.math.univ-toulouse.fr/~gamboa/">Fabrice Gamboa</a><br><a href="https://perso.math.univ-toulouse.fr/loubes/">Jean-Michel Loubes</a></dd></div>
  <div><dt>Industrial supervisors · EDF</dt><dd><a href="https://perso.lpsm.paris/~bousquet/">Nicolas Bousquet</a><br><a href="https://josephmure.wordpress.com/">Joseph Muré</a></dd></div>
</dl>

<section class="content-section" aria-labelledby="news-heading">
  <div class="section-heading"><h2 id="news-heading"><span class="section-number" aria-hidden="true">01</span>News</h2></div>
  <ul class="news-list">
    <li><time datetime="2026-09">Sep 2026</time><p>Updated preprint: <a href="https://arxiv.org/abs/2605.18422">Generalized Functional ANOVA: A Complete Theoretical Framework</a>.</p></li>
    <li><time datetime="2026-05">May 2026</time><p>Our work on generalized functional ANOVA for continuous inputs is available on <a href="https://arxiv.org/abs/2605.18422v1">arXiv</a>.</p></li>
    <li><time datetime="2026-04">Apr 2026</time><p>Our paper on functional ANOVA for categorical inputs was accepted at <strong>ICML 2026</strong> for an <span style="color: var(--blue)">oral presentation</span>.</p></li>
  </ul>
  <details class="news-archive"><summary>Earlier news</summary><ul class="news-list">
    <li><time datetime="2026-03">Mar 2026</time><p>New preprint: <a href="https://arxiv.org/abs/2603.02673">Exact Functional ANOVA Decomposition for Categorical Inputs Models</a>.</p></li>
    <li><time datetime="2025-10">Oct 2025</time><p>Our work on <a href="https://arxiv.org/abs/2510.07088">Fourier analysis on the Boolean hypercube</a> is available on arXiv.</p></li>
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
    <article><span class="topic-symbol" aria-hidden="true">ƒ</span><h3>Functional decompositions</h3><p>Separating main effects and interactions through generalized ANOVA and Hilbert-space methods.</p></article>
    <article><span class="topic-symbol" aria-hidden="true">ℒ</span><h3>Statistical learning</h3><p>Nonparametric interaction models and minimax rates with learned dependence structure.</p></article>
    <article><span class="topic-symbol" aria-hidden="true">φ</span><h3>Model explanations</h3><p>Dependence-aware additive explanations and interaction effects in transformer architectures.</p></article>
  </div>
</section>

<section class="content-section" aria-labelledby="background-heading">
  <div class="section-heading"><h2 id="background-heading"><span class="section-number" aria-hidden="true">04</span>Background</h2><a class="section-link" href="{{ '/cv/' | relative_url }}">Full CV <span aria-hidden="true">↗</span></a></div>
  <p class="background-note">Before my Ph.D., I worked on functional ANOVA for correlated inputs during a research internship at EDF R&amp;D. I hold an M.Sc. in Statistical Learning from <a href="https://www.ip-paris.fr/">Institut Polytechnique de Paris</a> and an engineering degree from <a href="https://www.ensae.fr/">ENSAE Paris</a>.</p>
</section>
<div class="contact-note"><p>For research discussions and collaborations, <a href="mailto:{{ site.author.email }}">get in touch <span aria-hidden="true">↗</span></a>.</p></div>
