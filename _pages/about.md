---
permalink: /
title: "Minbo Gao"
layout: academic
author_profile: false
home: true
redirect_from: 
  - /about/
  - /about.html
---

<header class="academic-intro">
  <div>
    <h1 class="page__title">Minbo Gao</h1>
    <p class="academic-intro__position">Ph.D. Candidate in Computer Science<br>
    <span>Institute of Software, Chinese Academy of Sciences</span></p>
    <nav class="academic-links" aria-label="Profile links">
      <a href="mailto:{{ site.author.email }}">Email</a>
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      <a href="{{ '/files/minbogao_cv.pdf' | relative_url }}">CV</a>
      <a href="{{ '/publications/' | relative_url }}">Publications</a>
    </nav>
  </div>
  <img class="academic-intro__photo" src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="Minbo Gao" width="154" height="180">
</header>

I am a Ph.D. candidate in Computer Science at the Institute of Software, Chinese Academy of Sciences, advised by Prof. Mingsheng Ying and Prof. Zhengfeng Ji. I received my B.Sc. in Computer Science and Technology from the Yao Class at Tsinghua University in 2021.

My research lies in the theoretical foundations of quantum computing, spanning quantum algorithms and complexity, and quantum programming languages and semantics. I am also interested in quantum optimal transport, both as a mathematical subject and as a tool for reasoning about quantum programs.

<ul class="research-labels" aria-label="Research themes">
  <li><a href="{{ '/research/#algorithms' | relative_url }}">Algorithms &amp; Complexity</a></li>
  <li><a href="{{ '/research/#semantics' | relative_url }}">Program Equivalence &amp; Semantics</a></li>
  <li><a href="{{ '/research/#transport' | relative_url }}">Quantum Optimal Transport</a></li>
</ul>

## Research

<div class="research-directions" markdown="1">
<section markdown="1">
### Quantum Algorithms & Complexity

I study the design and analysis of quantum algorithms and their computational limits. My work covers quantum simulation, linear systems, state preparation, optimization, sampling, learning, and complexity lower bounds. I am particularly interested in general algorithmic frameworks, polynomial methods, and the mathematical structure underlying quantum computational advantages.

[Explore algorithms and complexity]({{ '/research/#algorithms' | relative_url }})
</section>
<section markdown="1">
### Quantum Programming Languages & Semantics

I am interested in program equivalence, relational reasoning, and the mathematical foundations of quantum program semantics. My work investigates relational quantum program logics, particularly their soundness and completeness. Quantum optimal transport duality has been an important tool in establishing completeness results, including for infinite-dimensional quantum and classical–quantum programs.

[Explore programming languages and semantics]({{ '/research/#semantics' | relative_url }})
</section>
</div>

<section class="research-theme" markdown="1">
### Quantum Optimal Transport

I also study quantum optimal transport as a mathematical subject in its own right, particularly duality, quantum couplings, and transport costs and metrics. This research connects to my work on quantum relational logics, while also raising independent mathematical questions about transport-based formulations of quantum state distances.

[Explore quantum optimal transport]({{ '/research/#transport' | relative_url }})
</section>

## Selected Publications

{% assign featured_publications = site.publications | where_exp: "paper", "paper.featured != nil" | sort: "featured" %}
<ul class="publication-list publication-list--selected">
  {% for paper in featured_publications %}
    <li>{% include publication-entry.html publication=paper hide_order=true %}</li>
  {% endfor %}
</ul>

[View all publications]({{ '/publications/' | relative_url }})

## Academic Activities & Contact

My [CV]({{ '/cv/' | relative_url }}) includes education, honors, and professional service, including conference and journal reviewing and recognition as a Notable Reviewer at ICLR 2025. See [academic activities]({{ '/academic-activities/' | relative_url }}) for talks, workshops, and research visits.

For research discussions, please contact me at [{{ site.author.email }}](mailto:{{ site.author.email }}). You can also find me on [Google Scholar]({{ site.author.googlescholar }}) and [ORCID]({{ site.author.orcid }}).
