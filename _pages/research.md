---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div style="background: linear-gradient(135deg, #f7fbff 0%, #f4f8f3 100%); border: 1px solid #d9e7df; border-radius: 14px; padding: 20px 22px; margin-bottom: 28px;">
  <p style="margin: 0 0 10px 0; font-size: 1.05em;"><strong>Overview.</strong> My general research interests mainly focus on data management, graph mining, and large language models for big data, with an emphasis on building efficient, reliable, and scalable algorithms and systems for real-world data-intensive applications.</p>
  <p style="margin: 0;">Currently, I am working on the following research topics, which are aligned with my <a href="/publications/">publications</a> and current projects.</p>
</div>

## Research Interests: Overview

### 🧭 Graph-based LLM Systems

- Cost-efficient graph-based RAG systems, graph memory, and agentic retrieval for knowledge-intensive tasks.

### 🔨 Large (Language) Models for Data

- LLM-powered and pretrained methods for data systems, including dataset search, latency prediction, cardinality estimation, and automated DBMS testing.

### ⚡️ Graph Mining & Algorithms

- Scalable algorithms for densest subgraph discovery, community search, clique counting/listing, temporal graph analytics, and graph edit distance estimation.

## Representative Research Topics

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/research-rag.svg" alt="Graph-based LLM systems" style="width: 100%; border-radius: 12px; border: 1px solid #d8e4ea; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0;">Topic 1: Graph-based LLM Systems</h3>
    <p>I study how graph structures can improve retrieval, memory, and reasoning in large language model systems. A major line of my recent work is graph-based retrieval-augmented generation, where I investigate both system benchmarking and new indexing or tuning methods for accurate and cost-efficient retrieval.</p>
    <ul>
      <li>Graph-based RAG benchmarking and unified analysis: VLDB 2025.</li>
      <li>Automatic RAG tuning and optimization: SIGMOD 2026.</li>
      <li>Hierarchical and attributed graph-based RAG methods: ICDE 2026, AAAI 2026.</li>
    </ul>
  </div>
</div>

### Selected Open-Source Projects

#### Graph-based RAG Systems

- [DIGIMON / GraphRAG](https://github.com/JayLZhou/GraphRAG): a graph-based RAG system for structured retrieval and reasoning. <a href="https://github.com/JayLZhou/GraphRAG"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/JayLZhou/GraphRAG?label=GitHub%20Repo%20stars&style=social"></a>
- [EraRAG](https://github.com/EverM0re/EraRAG-Official): a unified benchmark and analysis framework for graph-based RAG. <a href="https://github.com/EverM0re/EraRAG-Official"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EverM0re/EraRAG-Official?label=GitHub%20Repo%20stars&style=social"></a>

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/research-ai4db.svg" alt="AI for data systems" style="width: 100%; border-radius: 12px; border: 1px solid #d8e4ea; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0;">Topic 2: AI for Data Systems</h3>
    <p>I build learning-enhanced methods for database systems, especially for tasks where traditional heuristics are expensive or brittle. My work spans dataset search, latency prediction, cardinality estimation, and test-case generation for DBMS with LLMs.</p>
    <ul>
      <li>Pretrained models for latency prediction over distributed databases: VLDB Journal 2026.</li>
      <li>Cross-database cardinality estimation with pretrained models: VLDB 2025.</li>
      <li>LLM-based test-case generation for DBMS: ICSE 2026.</li>
    </ul>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 26px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/research-graph.svg" alt="Graph mining and algorithms" style="width: 100%; border-radius: 12px; border: 1px solid #d8e4ea; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0;">Topic 3: Graph Mining and Graph Algorithms</h3>
    <p>I design scalable algorithms for graph data management and mining, with a particular focus on densest subgraph discovery, community search, clique counting, and temporal graph analytics. This line of work combines theoretical guarantees with practical performance on large graphs.</p>
    <ul>
      <li>Densest subgraph discovery on undirected and directed graphs: SIGMOD 2024, VLDB 2025, SIGMOD 2026.</li>
      <li>Community search over heterogeneous and temporal graphs: VLDB 2023, VLDB 2026, SIGMOD 2026.</li>
      <li>Graph edit distance estimation, motif-clique enumeration, and biclique counting: VLDB 2024-2026.</li>
    </ul>
  </div>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin-bottom: 18px;">
  <div style="flex: 1 1 260px; min-width: 260px;">
    <img src="/images/DDG.png" alt="Database systems and industry applications" style="width: 100%; border-radius: 12px; border: 1px solid #d8e4ea; background: #ffffff;">
  </div>
  <div style="flex: 2 1 420px; min-width: 280px;">
    <h3 style="margin-top: 0;">Topic 4: Database Systems and Industry Applications</h3>
    <p>I am also interested in bridging academic ideas with production-grade systems. My industrial experience includes database kernel optimization and modern data warehouse infrastructure, especially for high-throughput and real-time workloads.</p>
    <ul>
      <li>Streaming data processing engine for modern real-time data warehouses: VLDB 2025.</li>
      <li>TiDB kernel optimization and hotspot workload improvement.</li>
      <li>System design for practical LLM applications in industrial environments.</li>
    </ul>
  </div>
</div>

## Selected Publications by Topic

- For a complete list, please see [Publications](/publications/).
- Graph-based LLM Systems: SIGMOD 2026, AAAI 2026, ICDE 2026, VLDB 2025.
- AI for Data Systems: dataset search, VLDB Journal 2026, ICSE 2026, VLDB 2025.
- Graph Mining and Algorithms: SIGMOD 2024-2026, VLDB 2023-2026, KDD 2026, SIGIR 2025.
- Database Systems and Industry Applications: VLDB 2025.
