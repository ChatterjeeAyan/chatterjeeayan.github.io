---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

I develop research and engineering projects in computational biology, machine learning, and network science. My work is centered at **BioClarity AI**, where I lead development of AI tools for gene therapy and drug discovery.

{% for post in site.portfolio %}
  {% include archive-single.html type="grid" %}
{% endfor %}

## Featured research & applications

**Drug discovery & protein engineering:**
- **AI-Bind** — Interpretable machine learning for protein-ligand binding prediction
- **DeepPurpose** — Deep learning toolkit for drug-target interaction and drug properties

**Graph neural networks & link prediction:**
- **fm4tlp** — Transfer learning for temporal link prediction in dynamic graphs
- **ILP** — Inductive link prediction methods for isolated and temporal nodes
- **observational-bias** — Exploring observational biases and shortcuts in link prediction  
- **inductive_biases** — Studying GNN inductive biases through structural entropy

**Network visualization & analysis:**
- **MultiViz** — Gephi plugin for visualizing multilayer and complex networks
- **Spotify collaboration network** — Network analysis of artist collaboration patterns

For a complete list of repositories, visit my [GitHub profile](https://github.com/ChatterjeeAyan).

**BioClarity AI** — Learn more at [bioclarity.ai](https://www.bioclarity.ai/)
