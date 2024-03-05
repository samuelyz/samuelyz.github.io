---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find more code and projects at my <a href="https://github.com/{{site.author.github}}">Github</a>.</div>
{% endif %}

<a href="https://github.com/{{site.author.github}}">DynamicHedgeAIXI</a>
- An implementation of the Reinforcement Learning agent described in _Dynamic Knowledge Injection for AIXI Agents_ (see [publications](/publications/)).
- Written in Python with multi-threaded Monte-Carlo Tree Search offloaded to C++ via Cython. 

<a href="https://github.com/{{site.author.github}}">$$\Phi$$-Context Tree Weighting</a>
- An implementation of the modification of Context Tree Weighting (CTW) as described in _A Direct Approximation of AIXI Using Logical State Abstractions_ (see [publications](/publications/)).
- $$\Phi$$-CTW increases CTW's modelling capacity beyond variable-order Markov models and allows easy incorporation of domain knowledge.


