---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

<style>
  .pub-legend { margin: -6px 0 26px; font-size: 14px; color: #666; }
  .vb {
    display: inline-block; padding: 2px 10px; border-radius: 999px;
    font-size: 14px; font-weight: 600; color: #fff; white-space: nowrap;
  }
  .vb-a { background: #c00000; }
  .vb-w { background: #f4bc42; }
  .pub-note {
    padding: 12px 16px; margin-bottom: 20px; border-radius: 0 6px 6px 0;
    box-shadow: 1px 2px 6px rgba(0, 0, 0, 0.05);
    font-style: italic; color: #555; font-size: 0.95em;
  }
  .pub-list { list-style: none; padding-left: 0; margin: 0; }
  .pub-list > li {
    padding: 14px 0 14px 46px; position: relative;
    border-bottom: 1px solid #f2f3f3;
  }
  .pub-list > li:last-child { border-bottom: none; }
  .pub-list > li::before {
    content: counter(pub); counter-increment: pub;
    position: absolute; left: 0; top: 16px;
    font-size: 13px; font-variant-numeric: tabular-nums; color: #9aa3ad;
  }
  .pub-list { counter-reset: pub; }
  .pub-t { display: block; font-size: 16px; font-weight: 600; line-height: 1.45; }
  .pub-a { display: block; font-size: 14px; color: #555; margin-top: 3px; }
  .pub-a .me { color: #d32f2f; font-weight: 700; }
  .pub-v { display: block; font-size: 14px; margin-top: 5px; }
  .pub-v em { color: #666; }
  .pub-x { font-weight: 700; white-space: nowrap; }
  .pub-links { font-size: 14px; margin-top: 4px; display: block; }
  @media (max-width: 600px) {
    .pub-list > li { padding-left: 32px; }
  }
</style>

<p class="pub-legend">
  <span class="vb vb-a">CCF A</span> &nbsp;<span class="vb vb-w">Workshop</span>
  &nbsp;&nbsp;·&nbsp;&nbsp; <sup>#</sup> equal contribution &nbsp;·&nbsp; <sup>*</sup> corresponding author
</p>

<h1 id="-graph-based-llm-systems"><span class="anchor" id="graph-based-llm-systems"></span>🧭 Graph-based LLM Systems</h1>

<div class="pub-note" style="background-color:#eef6fb; border-left:4px solid #2f6f97;">
  Designing cost-efficient, high-performance graph-based LLM systems spanning Retrieval-Augmented Generation (RAG), structured agent memory, and large-scale social simulation.
</div>

<ul class="pub-list">
  <li>
    <span class="pub-t">HAMMER: An Automatic RAG Tuning System via Hierarchical Memory-Guided Monte Carlo Tree Search</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Zixuan Wang, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">SIGMOD'26</span> <em>Proceedings of the ACM on Management of Data.</em></span>
  </li>
  <li>
    <span class="pub-t">ArchRAG: Attributed Community-based Hierarchical Retrieval-Augmented Generation</span>
    <span class="pub-a">Shu Wang, Yixiang Fang, <span class="me">Yingli Zhou</span>, Xilin Liu, Yuchi Ma.</span>
    <span class="pub-v"><span class="vb vb-a">AAAI'26</span> <em>AAAI Conference on Artificial Intelligence.</em> <span class="pub-x" style="color:#ea6eaf;">🎤 Oral</span></span>
  </li>
  <li>
    <span class="pub-t">Clue-RAG: Towards Accurate and Cost-Efficient Graph-based RAG via Multi-Partite Graph-based Index</span>
    <span class="pub-a">Yaodong Su, Yixiang Fang, <span class="me">Yingli Zhou</span>, Chuanhui Yang.</span>
    <span class="pub-v"><span class="vb vb-a">ICDE'26</span> <em>IEEE International Conference on Data Engineering.</em></span>
  </li>
  <li>
    <span class="pub-t">In-depth Analysis of Graph-based RAG in a Unified Framework</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Yaodong Su, Youran Sun, Shu Wang, Taotao Wang, Runyuan He, Yongwei Zhang, Sicong Liang, Xilin Liu, Yuchi Ma, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment, 18(13): 5623–5637.</em> <span class="pub-x" style="color:#4f9ac7;">⭐ High-Star Project</span></span>
    <span class="pub-links">[<a href="https://arxiv.org/abs/2503.04338">arXiv</a>] [<a href="https://github.com/JayLZhou/GraphRAG">Code</a>]</span>
  </li>
  <li>
    <span class="pub-t">Towards the Next Generation of Agent Systems: From RAG to Agentic AI</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Shu Wang.</span>
    <span class="pub-v"><span class="vb vb-w">VLDB-W'25</span> <em>Proceedings of the VLDB Endowment, Graph+LLM Workshop.</em></span>
  </li>
  <li>
    <span class="pub-t">Scalable Graph-based Retrieval-Augmented Generation via Locality-Sensitive Hashing</span>
    <span class="pub-a">Fangyuan Zhang, Zhengjun Huang, <span class="me">Yingli Zhou</span><sup>*</sup>, Qingtian Guo, Wensheng Luo, Xiaofang Zhou.</span>
    <span class="pub-v"><span class="vb vb-w">VLDB-W'25</span> <em>Proceedings of the VLDB Endowment, Graph+LLM Workshop.</em></span>
  </li>
</ul>

<h1 id="-large-language-models-for-data"><span class="anchor" id="large-language-models-for-data"></span>🔨 Large (Language) Models for Data</h1>

<div class="pub-note" style="background-color:#fff7ec; border-left:4px solid #9a5a12;">
  Advancing database system optimizations and data management through the application of pre-trained models and LLMs, covering pivotal tasks such as dataset search, cardinality estimation, latency prediction, and automated testing.
</div>

<ul class="pub-list">
  <li>
    <span class="pub-t">Lamba: A Pretrained Model for Latency Prediction over Distributed Databases</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span><sup>#</sup>, Tianjing Zeng<sup>#</sup>, Rong Zhu, Yingze Li, Junwei Lan, Zhewei Wei, Yixiang Fang, Bolin Ding, Jingren Zhou.</span>
    <span class="pub-v"><span class="vb vb-a">VLDBJ'26</span> <em>The VLDB Journal.</em></span>
  </li>
  <li>
    <span class="pub-t">LLM-Based Test Case Generation in DBMS through Monte Carlo Tree Search</span>
    <span class="pub-a">Yujia Chen, <span class="me">Yingli Zhou</span>, Fangyuan Zhang, Cuiyun Gao.</span>
    <span class="pub-v"><span class="vb vb-a">ICSE'26</span> <em>International Conference on Software Engineering, Industry Challenge Track.</em> <span class="pub-x" style="color:#b30000;">🏆 Best Paper Award</span></span>
  </li>
  <li>
    <span class="pub-t">PRICE: A Pretrained Model for Cross-Database Cardinality Estimation</span>
    <span class="pub-a">Tianjing Zeng, Junwei Lan, Jiahong Ma, Wenqing Wei, Rong Zhu, <span class="me">Yingli Zhou</span>, Pengfei Li, Bolin Ding, Defu Lian, Zhewei Wei, Jingren Zhou.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment, 18(3): 637–650.</em></span>
  </li>
</ul>

<h1 id="-graph-mining--algorithms"><span class="anchor" id="graph-mining-algorithms"></span>⚡️ Graph Mining &amp; Algorithms</h1>

<div class="pub-note" style="background-color:#eef8f2; border-left:4px solid #2f7a5b;">
  Developing highly efficient and scalable algorithms for graph mining and graph data management, including densest subgraph discovery, community search, and clique counting/listing.
</div>

<ul class="pub-list">
  <li>
    <span class="pub-t">Efficient Anchored Densest Subgraph Discovery: Improved Time Complexity and Practical Performance</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Youran Sun, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">SIGMOD'26</span> <em>Proceedings of the ACM on Management of Data.</em></span>
  </li>
  <li>
    <span class="pub-t">A Semantics-aware Approach for Graph Edit Distance Estimation over Knowledge Graphs</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, HuiZhong Wang, Chenhao Ma, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'26</span> <em>Proceedings of the VLDB Endowment, 19(6): 1226–1239.</em></span>
  </li>
  <li>
    <span class="pub-t">Scalable Approximate Biclique Counting over Large Bipartite Graphs</span>
    <span class="pub-a">Jingbang Chen<sup>#</sup>, Weinuo Li<sup>#</sup>, <span class="me">Yingli Zhou</span><sup>#</sup>, Hangrui Zhou, Qiuyang Mang, Can Wang, Yixiang Fang, Chenhao Ma.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'26</span> <em>Proceedings of the VLDB Endowment.</em></span>
  </li>
  <li>
    <span class="pub-t">Accelerated Coordinate Descent for Directed Densest Subgraph Discovery</span>
    <span class="pub-a">Luocheng Liang, <span class="me">Yingli Zhou</span>, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">KDD'26</span> <em>ACM SIGKDD International Conference on Knowledge Discovery and Data Mining.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient Influential Community Search over Dynamic Graphs</span>
    <span class="pub-a">Youran Sun, <span class="me">Yingli Zhou</span>, Yixiang Fang, Cheng Chen, Yongmin Hu, Yingqian Hu.</span>
    <span class="pub-v"><span class="vb vb-a">SIGMOD'26</span> <em>Proceedings of the ACM on Management of Data.</em></span>
  </li>
  <li>
    <span class="pub-t">Effective Durable Community Search in Large Temporal Graph</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span><sup>#</sup>, Yige Jiang<sup>#</sup>, Yixiang Fang, Wensheng Luo, Yongmin Hu, Yingqian Hu, Cheng Chen.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'26</span> <em>Proceedings of the VLDB Endowment.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient and Scalable Directed Densest Subgraph Discovery</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Luocheng Liang, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">SIGMOD'26</span> <em>Proceedings of the ACM on Management of Data.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient 𝑘-Clique Densest Subgraph Discovery: Towards Bridging Practice and Theory</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span><sup>#</sup>, Qingshuo Guo<sup>#</sup>, Yixiang Fang.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment, 18(10): 3490–3503.</em></span>
  </li>
  <li>
    <span class="pub-t">UTCS: Effective Unsupervised Temporal Community Search with Pre-training of Temporal Dynamics and Subgraph Knowledge</span>
    <span class="pub-a">Yue Zhang, Yankai Chen, <span class="me">Yingli Zhou</span>, Yucan Guo, Xiaolin Han, Chenhao Ma.</span>
    <span class="pub-v"><span class="vb vb-a">SIGIR'25</span> <em>International ACM SIGIR Conference on Research and Development in Information Retrieval.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient Historical Butterfly Counting in Large Temporal Bipartite Networks via Graph Structure-aware Index</span>
    <span class="pub-a">Qiuyang Mang, Jingbang Chen, Hangrui Zhou, Yu Gao, <span class="me">Yingli Zhou</span>, Qingyu Shi, Richard Peng, Yixiang Fang, Chenhao Ma.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment, 18(6): 1607–1620.</em></span>
  </li>
  <li>
    <span class="pub-t">In-depth Analysis of Densest Subgraph Discovery in a Unified Framework</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Qingshuo Guo, Yi Yang, Yixiang Fang, Chenhao Ma, Laks V.S. Lakshmanan.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment, 18(4): 1131–1144.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient Maximal Motif-Clique Enumeration over Large Heterogeneous Information Networks</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Yixiang Fang, Chenhao Ma, Tianci Hou, Xin Huang.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'24</span> <em>Proceedings of the VLDB Endowment, 17(11): 2946–2959.</em></span>
  </li>
  <li>
    <span class="pub-t">Efficient Parallel D-core Decomposition at Scale</span>
    <span class="pub-a">Wensheng Luo, Yixiang Fang, Chunxu Lin, <span class="me">Yingli Zhou</span>.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'24</span> <em>Proceedings of the VLDB Endowment, 17(10): 2654–2667.</em></span>
  </li>
  <li>
    <span class="pub-t">A Counting-based Approach for Efficient 𝑘-Clique Densest Subgraph Discovery</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Qingshuo Guo, Yixiang Fang, Chenhao Ma.</span>
    <span class="pub-v"><span class="vb vb-a">SIGMOD'24</span> <em>Proceedings of the ACM on Management of Data, 2(3): 156:2–156:27.</em></span>
  </li>
  <li>
    <span class="pub-t">Influential Community Search over Large Heterogeneous Information Networks</span>
    <span class="pub-a"><span class="me">Yingli Zhou</span>, Yixiang Fang, Wensheng Luo, Yunming Ye.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'23</span> <em>Proceedings of the VLDB Endowment, 16(8): 2047–2059.</em></span>
    <span class="pub-links">[<a href="https://www.vldb.org/pvldb/vol16/p2047-zhou.pdf">Paper</a>] [<a href="https://github.com/JayLZhou/ICSH">Code</a>]</span>
  </li>
</ul>

<h1 id="-database-systems--industry-applications"><span class="anchor" id="database-systems-industry-applications"></span>⚙️ Database Systems &amp; Industry Applications</h1>

<div class="pub-note" style="background-color:#f4f5f7; border-left:4px solid #6b7280;">
  Bridging theoretical research with industrial practice by building scalable, real-time data processing engines and robust database architectures for modern data warehouses.
</div>

<ul class="pub-list">
  <li>
    <span class="pub-t">Streaming View: An Efficient Data Processing Engine for Modern Real-time Data Warehouse of Alibaba Cloud</span>
    <span class="pub-a">Fangyuan Zhang, Mengqi Wu, Chunlei Xu, Yunong Bao, Jiyu Qiao, <span class="me">Yingli Zhou</span>, Hua Fan, Caihua Yin, Wenchao Zhou, Feifei Li.</span>
    <span class="pub-v"><span class="vb vb-a">VLDB'25</span> <em>Proceedings of the VLDB Endowment.</em></span>
  </li>
</ul>
