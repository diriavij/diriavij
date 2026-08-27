<h1 align="center">Foma Popov</h1>

<p align="center">
  <strong>Software Engineering undergraduate · Research-oriented ML and data practitioner</strong><br>
  HSE University · Data Analyst at Yandex
</p>

<p align="center">
  <a href="mailto:popovfoma06@gmail.com">Email</a> ·
  <a href="https://github.com/diriavij">GitHub</a>
</p>

I work at the intersection of **machine learning, data analysis, and software
engineering**. My main interests are probabilistic language modeling,
information-theoretic methods for NLP, evidence-grounded LLM systems, and
reproducible experimentation.

At Yandex, I work on product analytics, controlled experiments, ML scoring,
and data pipelines. In research and coursework, I am particularly drawn to
questions where careful evaluation matters as much as model implementation.

## Featured research

### [Finite-Memory Language Modeling with Context Trees](https://github.com/diriavij/ctw-language-modeling)

Research completed at the **CUHK-Shenzhen Elite Undergraduate Summer Camp
2026** under the supervision of Associate Professor Shenghao Yang.

- Implemented Context-Tree Weighting and practical text context-tree models
  from scratch.
- Compared finite-memory models with GPT-2 on WikiText-2 and investigated
  whether the performance gap comes from limited context or sparse statistics.
- Reached **2.162 bits per character** with the context-tree model, versus
  **1.154 BPC** for GPT-2 small; the depth-7 conditional-entropy estimate was
  **1.205 BPC**, pointing to data sparsity as the central limitation.
- Packaged the work as reproducible research code with tests, experiment
  artifacts, a full report, slides, and citation metadata.

**[Research report](https://github.com/diriavij/ctw-language-modeling/blob/main/report.pdf)** ·
**[Presentation](https://github.com/diriavij/ctw-language-modeling/blob/main/slides.pdf)** ·
**[Reproduction guide](https://github.com/diriavij/ctw-language-modeling#quick-start)**

<p align="center">
  <img src="https://raw.githubusercontent.com/diriavij/ctw-language-modeling/main/experiments/figures/bpc_plot_2panel.png" width="780" alt="Comparison of context-tree and neural language models">
</p>

### [LLM for ESG](https://github.com/diriavij/LLM-for-ESG)

An evidence-grounded pipeline for assessing corporate sustainability reports
and public documents across **15 ESG indicators**.

- Built hybrid retrieval with BM25, vector search, and reciprocal rank fusion.
- Explored direct prompting, RAG variants, Writer-Critic workflows, ensemble
  methods, multi-agent orchestration, and LoRA fine-tuning.
- Evaluated scores and supporting evidence with bootstrap resampling, MAE,
  citation similarity, evidence-type accuracy, and McNemar's test.
- Research-course project at HSE University; manuscript in preparation.

## Selected engineering project

### [King of the Beat](https://github.com/diriavij/King-of-the-Beat)

A full-stack collaborative playlist application with competitive voting and
real-time room synchronization.

- **iOS:** Swift, UIKit, Spotify API, SVIP architecture
- **Backend:** Go, REST API, WebSockets
- **Data and infrastructure:** PostgreSQL, Docker Compose

## Background

- Bachelor's student in **Software Engineering at HSE University**
- **Data Analyst at Yandex**, working across experimentation, predictive
  modeling, analytics engineering, and AI-assisted analytical workflows
- Former **Python programming instructor** for a class of 25 students
- Finalist, **HSE AI Assistant Hack**; winner, **Rosatom Mathematics Olympiad**

## Technical focus

**Research and ML:** Python · PyTorch · scikit-learn · NLP · RAG · LLM
evaluation · statistical testing · experiment design

**Data and systems:** SQL · ETL · PostgreSQL · Docker · Go · Swift/UIKit · REST
APIs · WebSockets
