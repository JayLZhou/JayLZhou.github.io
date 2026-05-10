---
permalink: /
title: Yingli ZHOU
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received my Ph.D. in March 2026 from the School of Data Science at [The Chinese University of Hong Kong, Shenzhen](https://sds.cuhk.edu.cn/), advised by Prof. [Yixiang Fang](https://fangyixiang.github.io/).
I am a postdoctoral researcher at [LIRIS, CNRS](https://liris.cnrs.fr/) / Université Claude Bernard Lyon 1 (Lyon, France) supported by ERC-Advanced Go-Y Project, working with Prof. [Angela Bonifati](https://perso.liris.cnrs.fr/angela.bonifati/) (ACM Fellow, SIGMOD Chair) on graph data management and reliable data infrastructure for AI.


I received my M.Eng. and B.Eng. from Harbin Institute of Technology in 2022 and 2020 respectively, under the supervision of Prof. [Yunming Ye](https://scholar.google.com/citations?user=n30nnskAAAAJ&hl=zh-CN). I was a visiting student at the [National University of Singapore](https://www.comp.nus.edu.sg/) in 2025, where I worked with Prof. [Xiaokui Xiao](https://www.comp.nus.edu.sg/~xiaoxk/index.html).




## Research Interests

My research agenda is to build **causality-aware graph data management** and **reliable graph data infrastructure for AI**. I study how graph structure, causal signals, and scalable data systems can make AI applications more trustworthy, explainable, and efficient.

Current directions include:

- **Causality-aware graph data management:** causal property graphs, causal provenance query, and scalable intervention analysis over graph data.
- **Reliable graph data infrastructure for AI:** graph-based RAG, structured retrieval, graph memory, and evaluation pipelines for knowledge-intensive AI systems.
- **Scalable graph analytics:** efficient algorithms for densest subgraph discovery, community search, clique counting/listing, and graph similarity.
- **Large models for data systems:** LLM-powered and pretrained methods for data analysis, database optimization, and DBMS testing.

I am open to collaborations, invited talks, and visiting opportunities in data management, database systems, and graph-based AI infrastructure. Please reach out via [email](mailto:yinglizhou@link.cuhk.edu.cn).


## Selected Publications

<div class="home-pub-list">
  <div class="home-pub-year">2026</div>

  <div class="home-pub-card">
    <h3>HAMMER: An Automatic RAG Tuning System via Hierarchical Memory-Guided Monte Carlo Tree Search</h3>
    <p class="home-pub-authors"><strong>Yingli Zhou</strong>, Zixuan Wang, Yixiang Fang</p>
    <p class="home-pub-venue">SIGMOD'26, Proceedings of the ACM on Management of Data</p>
    <p>HAMMER studies how to automatically tune retrieval-augmented generation systems through hierarchical memory and search, connecting graph-based retrieval, system optimization, and reliable AI pipelines.</p>
    <p class="home-pub-links">
      <a href="/publications/">Paper</a>
      <a href="/publications/">BibTex</a>
    </p>
  </div>

  <div class="home-pub-card">
    <h3>A Semantics-aware Approach for Graph Edit Distance Estimation over Knowledge Graphs</h3>
    <p class="home-pub-authors"><strong>Yingli Zhou</strong>, HuiZhong Wang, Chenhao Ma, Yixiang Fang</p>
    <p class="home-pub-venue">VLDB'26, Proceedings of the VLDB Endowment</p>
    <p>This work develops semantics-aware graph similarity estimation for knowledge graphs, supporting robust graph data management when structure alone is insufficient.</p>
    <p class="home-pub-links">
      <a href="/publications/">Paper</a>
      <a href="/publications/">BibTex</a>
    </p>
  </div>

  <div class="home-pub-card">
    <h3>Efficient Anchored Densest Subgraph Discovery: Improved Time Complexity and Practical Performance</h3>
    <p class="home-pub-authors"><strong>Yingli Zhou</strong>, Youran Sun, Yixiang Fang</p>
    <p class="home-pub-venue">SIGMOD'26, Proceedings of the ACM on Management of Data</p>
    <p>This paper advances scalable graph analytics by improving the theory and practice of anchored densest subgraph discovery, a core primitive for graph data exploration.</p>
    <p class="home-pub-links">
      <a href="/publications/">Paper</a>
      <a href="/publications/">BibTex</a>
    </p>
  </div>

  <div class="home-pub-year">2025</div>

  <div class="home-pub-card">
    <h3>In-depth Analysis of Graph-based RAG in a Unified Framework</h3>
    <p class="home-pub-authors"><strong>Yingli Zhou</strong>, Yaodong Su, Youran Sun, Shu Wang, Taotao Wang, Runyuan He, Yongwei Zhang, Sicong Liang, Xilin Liu, Yuchi Ma, Yixiang Fang</p>
    <p class="home-pub-venue">VLDB'25, Proceedings of the VLDB Endowment</p>
    <p>This work provides a unified framework for benchmarking and analyzing graph-based RAG, clarifying when graph structure improves retrieval and generation over noisy, evolving data.</p>
    <p class="home-pub-links">
      <a href="https://arxiv.org/abs/2503.04338">Arxiv</a>
      <a href="https://github.com/EverM0re/EraRAG-Official">Project</a>
      <a href="/publications/">BibTex</a>
    </p>
  </div>
</div>


## Recent News

- **March 2026:** I received my Ph.D. from CUHK-Shenzhen and will continue my research as an ERC postdoctoral researcher at LIRIS, CNRS / Université Lyon 1.
- **February 2026:** Two papers were accepted to SIGMOD 2026.
- **January 2026:** One paper was accepted to VLDB 2026.
- **September 2025:** One paper was accepted to VLDB 2026.
- **March 2025:** Our paper on the systematic benchmark and analysis of graph-based RAG became available on arXiv. [[arXiv]](https://arxiv.org/abs/2503.04338)


## Selected Open-source Projects

<div class="home-project-list">
  <div class="home-project-item">
    <strong><a href="https://github.com/JayLZhou/GraphRAG">DIGIMON / GraphRAG</a>:</strong>
    the first unified graph-based RAG prototype system for structured retrieval and reasoning over complex data.
    <a href="https://github.com/JayLZhou/GraphRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/JayLZhou/GraphRAG?label=GitHub%20stars&style=social"></a>
    <a href="/publications/">[papers]</a>
  </div>

  <div class="home-project-item">
    <strong><a href="https://github.com/EverM0re/EraRAG-Official">EraRAG</a>:</strong>
    the first graph-based RAG system to handle evolving documents.
    <a href="https://github.com/EverM0re/EraRAG-Official"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EverM0re/EraRAG-Official?label=GitHub%20stars&style=social"></a>
    <a href="https://arxiv.org/abs/2503.04338">[arXiv]</a>
  </div>

  <div class="home-project-item">
    <strong><a href="https://github.com/sam234990/BookRAG">BookRAG</a>:</strong>
    a hierarchical structure-aware index-based approach for retrieval-augmented generation on complex documents.
    <a href="https://github.com/sam234990/BookRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/sam234990/BookRAG?label=GitHub%20stars&style=social"></a>
    <a href="https://arxiv.org/abs/2512.03413">[arXiv]</a>
  </div>

  <div class="home-project-item">
    <strong><a href="https://github.com/D2I-CUHKSZ/MicroWorld">MicroWorld</a>:</strong>
    a lightweight system for turning multi-modal event materials into structured graphs, agent populations, and inspectable social simulations.
    <a href="https://github.com/D2I-CUHKSZ/MicroWorld"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D2I-CUHKSZ/MicroWorld?label=GitHub%20stars&style=social"></a>
    <a href="https://d2i-cuhksz.github.io/MicroWorld/">[site]</a>
  </div>
</div>


## Personal Information
- I have been a big fan of Jay Chou for around 18 years. I also grew up listening to Avril Lavigne and Coldplay, and their music has been a big part of my life.
- I love watching football, Dota2 and LOL. My favorite national teams are Portugal and France. As for clubs, I support Manchester City and used to support Real Madrid when Cristiano Ronaldo played there.
- I enjoy running in my free time, and my current goal is to complete a marathon.
