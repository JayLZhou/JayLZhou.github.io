---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---

<style>
  .rv { border: 1px solid #e3e7ec; border-radius: 10px; padding: 18px 20px; margin-bottom: 30px; background: #fbfcfd; }
  .rv > p { margin: 0 0 10px 0; }
  .rv > p:last-child { margin-bottom: 0; }
  .rv-dir { font-weight: 700; }

  /* topic cards - flat, hairline, same restraint as the homepage */
  .rt { display: flex; flex-wrap: wrap; gap: 20px; align-items: stretch;
        border: 1px solid #e3e7ec; border-radius: 10px; padding: 18px; margin-bottom: 18px; }
  .rt-fig { flex: 1 1 400px; min-width: 300px; display: flex; align-items: stretch; justify-content: center; }
  .rt-fig img { width: 100%; height: auto; align-self: center; border-radius: 6px; border: 1px solid #edf0f3; display: block; }
  .rt-body { flex: 1 1 340px; min-width: 280px; }
  .rt-chip { display: inline-block; padding: 3px 11px; border-radius: 999px;
             font-size: 12px; font-weight: 700; letter-spacing: .03em; margin-bottom: 9px; }
  .rt-body h3 { margin: 0 0 9px 0; font-size: 1.32em; line-height: 1.3; }
  .rt-body > p { margin: 0 0 13px 0; font-size: 0.97em; line-height: 1.65; color: #4a515b; }
  .rt-lines { list-style: none; margin: 0; padding: 0; }
  .rt-lines li { padding: 7px 0; border-bottom: 1px dotted #e3e7ec; font-size: 0.94em; }
  .rt-lines li:last-child { border-bottom: none; }
  .rt-lines b { font-weight: 600; color: #333; }
  .vc { display: inline-block; padding: 1px 8px; margin: 2px 3px 2px 0; border-radius: 12px;
        border: 1px solid #e8ecf1; background: #fff; font-size: 12.5px; color: #555; white-space: nowrap; }
  .vc .n { color: #9aa3ad; padding-left: 3px; }
  .vc-x { border-color: #f0c9c9; color: #b30000; }

  .os { list-style: none; margin: 0; padding: 0; }
  .os li { padding: 11px 0; border-bottom: 1px dotted #e3e7ec; font-size: 0.97em; }
  .os li:last-child { border-bottom: none; }
  .os img { vertical-align: -3px; }
</style>

<h1 id="-research-overview"><span class="anchor" id="research-overview"></span>🔭 Research Overview</h1>

<div class="rv">
  <p>My research agenda is to build <strong>causality-aware graph data management</strong> and <strong>reliable graph data infrastructure for AI</strong>. I study how graph structure, causal signals, and scalable data systems can make AI applications more trustworthy, explainable, and efficient. The four directions below line up with my <a href="/publications/">publications</a> and ongoing projects.</p>
  <p><span class="rt-chip" style="background:#e8f4fd; color:#2c5282;">Q1</span> <span class="rv-dir" style="color:#2c5282;">Causally Explainable Graph Data.</span> Causal property graph data models, CDAG construction, and scalable intervention analysis over large graph data.</p>
  <p><span class="rt-chip" style="background:#e0f2e9; color:#276749;">Q2</span> <span class="rv-dir" style="color:#276749;">Reliable Graph Infrastructure for AI.</span> Cost-efficient graph-based RAG, structured retrieval, graph memory, and agentic retrieval for knowledge-intensive tasks.</p>
  <p><span class="rt-chip" style="background:#fef9ef; color:#744210;">Q3</span> <span class="rv-dir" style="color:#744210;">Dense Structure at Massive Scale.</span> Scalable algorithms for densest subgraph discovery, community search, clique and biclique counting, and graph similarity.</p>
  <p><span class="rt-chip" style="background:#f3effc; color:#553c9a;">Q4</span> <span class="rv-dir" style="color:#553c9a;">Large Models for Data Systems.</span> LLM-powered and pretrained methods for data systems: latency prediction, cardinality estimation, and automated DBMS testing.</p>
</div>

<h1 id="-research-topics"><span class="anchor" id="research-topics"></span>🧩 Research Topics</h1>

<div class="rt">
  <div class="rt-fig">
    <a href="/images/fig-causal.svg"><img src="/images/fig-causal.svg" alt="A property graph on the left; on the right the same nodes as a causal DAG with a do(A) intervention and a dashed low-confidence edge"></a>
  </div>
  <div class="rt-body">
    <span class="rt-chip" style="background:#e8f4fd; color:#2c5282;">Q1 · ERC Go-Y, ongoing</span>
    <h3 style="color:#2c5282;">Causal Property Graphs and Scalable Causal Analysis</h3>
    <p>I study causal data management over property graphs, unifying graph structure priors with statistical learning for robust causal graph construction and fast inference. This is the direction I started at CNRS LIRIS and it does not have published results yet.</p>
    <ul class="rt-lines">
      <li><b>CDAG construction</b> from temporal constraints, graph topology, and domain priors.</li>
      <li><b>Hybrid structure learning</b> with conditional-independence tests and score-based optimization.</li>
      <li><b>Large-scale causal analysis</b> via subgraph pruning, parallel discovery, and incremental updates.</li>
    </ul>
  </div>
</div>

<div class="rt">
  <div class="rt-fig">
    <a href="/images/fig-graphrag.svg"><img src="/images/fig-graphrag.svg" alt="Documents feed a graph index, whose hierarchical communities are searched to retrieve a subgraph for the LLM"></a>
  </div>
  <div class="rt-body">
    <span class="rt-chip" style="background:#e0f2e9; color:#276749;">Q2</span>
    <h3 style="color:#276749;">Graph-based LLM Systems</h3>
    <p>I study graph-based retrieval, memory, and reasoning for large language model systems, with a focus on efficient RAG frameworks, indexing, and tuning.</p>
    <ul class="rt-lines">
      <li><b>Benchmark and analysis</b> of graph-based RAG in a unified framework <span class="vc">VLDB<span class="n">'25</span></span></li>
      <li><b>Automatic RAG tuning</b> via hierarchical memory-guided search <span class="vc">SIGMOD<span class="n">'26</span></span></li>
      <li><b>Index and retrieval methods</b> <span class="vc">AAAI<span class="n">'26</span></span><span class="vc">ICDE<span class="n">'26</span></span><span class="vc">VLDB-W<span class="n">'25</span></span></li>
      <li><b>Evolving and long documents</b> <span class="vc">arXiv</span> EraRAG, BookRAG</li>
    </ul>
  </div>
</div>

<div class="rt">
  <div class="rt-fig">
    <a href="/images/fig-graphmining.svg"><img src="/images/fig-graphmining.svg" alt="A graph with its densest subgraph circled, beside the three task families: densest subgraph, community search, clique and biclique counting"></a>
  </div>
  <div class="rt-body">
    <span class="rt-chip" style="background:#fef9ef; color:#744210;">Q3</span>
    <h3 style="color:#744210;">Graph Mining and Graph Algorithms</h3>
    <p>I design scalable graph mining algorithms for densest subgraph discovery, community search, clique and biclique counting, and graph similarity tasks.</p>
    <ul class="rt-lines">
      <li><b>Densest subgraph discovery</b> <span class="vc">SIGMOD<span class="n">'24</span></span><span class="vc">VLDB<span class="n">'25 ×2</span></span><span class="vc">SIGMOD<span class="n">'26 ×2</span></span><span class="vc">KDD<span class="n">'26</span></span></li>
      <li><b>Community search</b> <span class="vc">VLDB<span class="n">'23</span></span><span class="vc">SIGIR<span class="n">'25</span></span><span class="vc">VLDB<span class="n">'26</span></span><span class="vc">SIGMOD<span class="n">'26</span></span></li>
      <li><b>Counting and similarity</b> <span class="vc">VLDB<span class="n">'24 ×2</span></span><span class="vc">VLDB<span class="n">'25</span></span><span class="vc">VLDB<span class="n">'26 ×2</span></span></li>
    </ul>
  </div>
</div>

<div class="rt">
  <div class="rt-fig">
    <a href="/images/fig-llm4data.svg"><img src="/images/fig-llm4data.svg" alt="A SQL workload feeding a pretrained model that predicts latency and cardinality for the query optimizer, plus an LLM and MCTS branch generating test cases for the DBMS"></a>
  </div>
  <div class="rt-body">
    <span class="rt-chip" style="background:#f3effc; color:#553c9a;">Q4</span>
    <h3 style="color:#553c9a;">Large (Language) Models for Data</h3>
    <p>I build LLM-powered and pretrained methods for data systems, covering latency prediction, cardinality estimation, DBMS testing, and real-time data warehouse engines.</p>
    <ul class="rt-lines">
      <li><b>Pretrained models for database optimization</b> <span class="vc">VLDB<span class="n">'25</span></span><span class="vc">VLDBJ<span class="n">'26</span></span></li>
      <li><b>LLM-based test-case generation for DBMS</b> <span class="vc vc-x">ICSE<span class="n">'26 · Best Paper</span></span></li>
      <li><b>Real-time data warehouse engines</b> <span class="vc">VLDB<span class="n">'25</span></span> with Alibaba Cloud</li>
    </ul>
  </div>
</div>

<h1 id="-open-source-projects"><span class="anchor" id="open-source-projects"></span>💻 Open-source Projects</h1>

<ul class="os">
  <li>
    🔮 <strong><a href="https://github.com/JayLZhou/GraphRAG">DIGIMON / GraphRAG</a></strong> — the first unified graph-based RAG prototype system for structured retrieval and reasoning over complex data.
    <a href="https://github.com/JayLZhou/GraphRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/JayLZhou/GraphRAG?label=GitHub%20stars&style=social"></a>
  </li>
  <li>
    ⏳ <strong><a href="https://github.com/EverM0re/EraRAG-Official">EraRAG</a></strong> — the first graph-based RAG system to handle evolving documents.
    <a href="https://github.com/EverM0re/EraRAG-Official"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EverM0re/EraRAG-Official?label=GitHub%20stars&style=social"></a>
  </li>
  <li>
    📚 <strong><a href="https://github.com/sam234990/BookRAG">BookRAG</a></strong> — a hierarchical structure-aware index for retrieval-augmented generation over complex documents.
    <a href="https://github.com/sam234990/BookRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/sam234990/BookRAG?label=GitHub%20stars&style=social"></a>
  </li>
  <li>
    🌍 <strong><a href="https://github.com/D2I-CUHKSZ/MicroWorld">MicroWorld</a></strong> — turns multi-modal event material into structured graphs, agent populations, and inspectable social simulations.
    <a href="https://github.com/D2I-CUHKSZ/MicroWorld"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D2I-CUHKSZ/MicroWorld?label=GitHub%20stars&style=social"></a>
  </li>
</ul>
