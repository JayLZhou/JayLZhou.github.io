---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div style="background: linear-gradient(135deg, #f7fbff 0%, #f4f8f3 100%); border: 1px solid #d9e7df; border-radius: 14px; padding: 20px 22px; margin-bottom: 28px;">
  <p style="margin: 0 0 12px 0; font-size: 1.05em;"><strong>Overview.</strong> My research focuses on data management, graph mining, and large language models for big data. My current research topics, aligned with my <a href="/publications/">publications</a> and ongoing projects, include:</p>
  <p style="margin: 0 0 8px 0; color: #2f6f97;"><strong>🧭 Graph-based LLM Systems.</strong> <span style="color: #2f2f2f;">Cost-efficient graph-based RAG systems, graph memory, and agentic retrieval for knowledge-intensive tasks.</span></p>
  <p style="margin: 0 0 8px 0; color: #9a5a12;"><strong>🔨 Large (Language) Models for Data.</strong> <span style="color: #2f2f2f;">LLM-powered and pretrained methods for data systems, including dataset search, latency prediction, cardinality estimation, and automated DBMS testing.</span></p>
  <p style="margin: 0; color: #2f7a5b;"><strong>⚡️ Graph Mining & Algorithms.</strong> <span style="color: #2f2f2f;">Scalable algorithms for densest subgraph discovery, community search, clique counting/listing, temporal graph analytics, and graph edit distance estimation.</span></p>
</div>

## Representative Research Topics

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px; background: #eef6fb; border: 1px solid #c7ddeb; border-radius: 16px; padding: 18px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/graphllm.png" alt="Graph-based LLM systems" style="width: 100%; border-radius: 12px; border: 1px solid #b7d1e4; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0; color: #2f6f97;">Topic 1: Graph-based LLM Systems</h3>
    <p>I study how graph structures can improve retrieval, memory, and reasoning in large language model systems. A major line of my recent work focuses on graph-based retrieval-augmented generation, where I investigate both prototype systems and new indexing or RAG tuning systems.</p>
    <ul>
      <li>Graph-based RAG prototype systems: VLDB 2025.</li>
      <li>Automatic RAG optimization systems: SIGMOD 2026.</li>
      <li>Graph-based RAG methods: ICDE 2026, AAAI 2026.</li>
    </ul>
  </div>
</div>



<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px; background: #fff7ec; border: 1px solid #efd2a3; border-radius: 16px; padding: 18px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/research-ai4db.svg" alt="AI for data systems" style="width: 100%; border-radius: 12px; border: 1px solid #e6c58f; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0; color: #9a5a12;">Topic 2: AI for Data Systems</h3>
    <p>I build learning-enhanced methods for database systems, especially for tasks where traditional heuristics are expensive or brittle. My work spans dataset search, latency prediction, cardinality estimation, and test-case generation for DBMS with LLMs.</p>
    <ul>
      <li>Pretrained models for latency prediction over distributed databases: VLDB Journal 2026.</li>
      <li>Cross-database cardinality estimation with pretrained models: VLDB 2025.</li>
      <li>LLM-based test-case generation for DBMS: ICSE 2026.</li>
    </ul>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px; background: #eef8f2; border: 1px solid #bddfc9; border-radius: 16px; padding: 18px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/research-graph.svg" alt="Graph mining and algorithms" style="width: 100%; border-radius: 12px; border: 1px solid #afd6be; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0; color: #2f7a5b;">Topic 3: Graph Mining and Graph Algorithms</h3>
    <p>I design scalable algorithms for graph data management and mining, with a particular focus on densest subgraph discovery, community search, clique counting, and temporal graph analytics. This line of work combines theoretical guarantees with practical performance on large graphs.</p>
    <ul>
      <li>Densest subgraph discovery on undirected and directed graphs: SIGMOD 2024, VLDB 2025, SIGMOD 2026.</li>
      <li>Community search over heterogeneous and temporal graphs: VLDB 2023, VLDB 2026, SIGMOD 2026.</li>
      <li>Graph edit distance estimation, motif-clique enumeration, and biclique counting: VLDB 2024-2026.</li>
    </ul>
  </div>
</div>



## Selected Open-Source Projects

### <span style="color: #2f6f97;">🧭 Graph-based LLM Systems</span>

- [DIGIMON / GraphRAG](https://github.com/JayLZhou/GraphRAG): a graph-based RAG system for structured retrieval and reasoning. <a href="https://github.com/JayLZhou/GraphRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/JayLZhou/GraphRAG?label=GitHub%20Repo%20stars&style=social"></a>
- [EraRAG](https://github.com/EverM0re/EraRAG-Official): a unified benchmark and analysis framework for graph-based RAG. <a href="https://github.com/EverM0re/EraRAG-Official"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EverM0re/EraRAG-Official?label=GitHub%20Repo%20stars&style=social"></a>
