---
---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
    .experience-card {
        display: flex;
        align-items: center;
        background: #f9f9f9;
        border-radius: 12px;
        padding: 16px;
        margin-bottom: 0px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .experience-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    .experience-logo {
        width: 60px;
        height: 60px;
        margin-right: 20px;
        border-radius: 8px;
        object-fit: contain;
    }
    .experience-info {
        font-family: "Segoe UI", sans-serif;
    }
    .experience-info strong {
        font-size: 1.1em;
    }
    .experience-info a {
        text-decoration: none;
        color: #5b8dd9;
    }
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
    }
    .experience-card {
        box-sizing: border-box;
    }
    .publication-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        color: #5f6368;
    }
    .publication-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    .publication-card.featured {
        border-color: #a8c4f0;
        background: #f0f6ff;
        box-shadow: 0 4px 8px rgba(91, 141, 217, 0.2);
    }
    .publication-card.featured:hover {
        box-shadow: 0 8px 16px rgba(91, 141, 217, 0.4);
    }
    .pub-button-container {
        display: flex;
        gap: 10px;
        margin: 20px 0;
        flex-wrap: wrap;
    }
    .pub-button {
        background-color: #f0f0f0;
        border: 1px solid #ccc;
        border-radius: 20px;
        padding: 8px 16px;
        cursor: pointer;
        transition: all 0.3s ease;
    }
    .pub-button:hover { background-color: #e0e0e0; }
    .pub-button.active {
        background-color: #5b8dd9;
        color: white;
        border-color: #5b8dd9;
    }
    .project-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        color: #5f6368;
    }
    .project-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
</style>

<html>
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap');
        body {
            background-color: #FFFFFF;
            font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
            font-size: 15px;
        }
        .main-heading {
            font-family: 'Permanent Marker', cursive;
            text-align: center;
            color: #5b8dd9;
        }
        div.markdown-body a, a {
            text-decoration: none !important;
            color: #5b8dd9;
            transition: all 0.3s ease;
        }
        div.markdown-body a:hover, a:hover {
            color: #2255aa;
            text-decoration: underline;
        }
    </style>
</head>
<body>
<h1 class="main-heading">Hi! I'm Jiahao. Welcome to my Homepage!</h1>
</body>
</html>

I am an undergraduate (2022–2026) at [Gaoling School of Artificial Intelligence](http://ai.ruc.edu.cn/), **Renmin University of China**. My research interests span **Information Retrieval**, **LLM Post-Training**.

I work at [IIR-Lab](http://www.thuir.cn/) at Renmin University of China. Previously, I interned at [ByteDance Seed](https://seed.bytedance.com/en/) as an AI Search Algorithm Intern.

📮 Feel free to reach out: [zhaojiahao2202@ruc.edu.cn](mailto:zhaojiahao2202@ruc.edu.cn) · [Google Scholar]()

News
---------------
- *[Paragon]() is accepted at **RecSys 2025** as **Spotlight Oral Presentation** 🔥*
- *[R1-Searcher++]() is accepted at **EMNLP 2025** 🔥*
- *Won **Outstanding Winner + COMAP Scholarship** (4/18525, $10,000) at MCM 2024 🏆*
- *Awarded **National Scholarship** for 2023–2024 and 2024–2025 🏅*

Experience
--------------
<div class="experience-container">
  <div class="experience-card">
      <img src="images/bytedance.png" alt="ByteDance logo" class="experience-logo">
      <div class="experience-info">
          <strong>ByteDance Seed</strong><br>
          2024 - 2025<br>
          AI Search Algorithm Intern at <a href="https://seed.bytedance.com/en/"><em>豆包大模型</em></a>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/THU.png" alt="Tsinghua logo" class="experience-logo">
      <div class="experience-info">
          <strong>Tsinghua University</strong><br>
          2023 - Now<br>
          Research Intern at <a href="http://www.thuir.cn/"><em>THUIR Lab</em></a>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/RUC.png" alt="RUC logo" class="experience-logo">
      <div class="experience-info">
          <strong>Renmin University of China</strong><br>
          Sep 2022 - July 2026<br>
          GPA 3.94/4.0, Rank <b>2/60</b>, <b>National Scholarship × 2</b><br>
          B.E at <a href="http://ai.ruc.edu.cn/"><em>Gaoling School of AI</em></a>
      </div>
  </div>
</div>

Publications
--------------
<div class="pub-button-container">
  <button class="pub-button active" onclick="showPublications('all')">All Publications</button>
  <button class="pub-button" onclick="showPublications('featured')">Selected Only</button>
</div>

<div class="publication-card featured">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/dllm_searcher.png" alt="DLLM-Searcher" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>DLLM-Searcher: Adapting Diffusion Large Language Models for Search Agents</strong><br>
        <i style="font-size: 13px;">
            <strong>Jiahao Zhao</strong>, et al.
        </i><br>
        We propose the first dLLM-based search agent, leveraging parallel decoding to reduce multi-turn ReAct latency. We introduce Agentic SFT & Agentic VRPO for post-training, and a novel P-ReAct paradigm that parallelizes tool-call decoding with tool response waiting.<br>
        <b><i style="color:#5b8dd9;">SIGIR 2026 Under Review &nbsp;</i></b>
        <a href=""><em>[arXiv]</em></a>
        <a href=""><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="publication-card featured">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/paragon.png" alt="Paragon" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>Paragon: Parameter Generation for Controllable Multi-Task Recommendation</strong><br>
        <i style="font-size: 13px;">
            <strong>Jiahao Zhao</strong>*, et al.
        </i><br>
        A model-agnostic control method for recommendation systems. We train a conditional diffusion model to generate adapter parameters on-the-fly based on platform/user requirements, enabling fine-grained multi-dimensional control over accuracy, diversity, and fairness.<br>
        <b><i style="color:#5b8dd9;">RecSys 2025 Spotlight Oral &nbsp;</i></b>
        <a href=""><em>[paper]</em></a>
        <a href=""><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="publication-card">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/r1searcher.png" alt="R1-Searcher++" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning</strong><br>
        <i style="font-size: 13px;">
            ..., <strong>Jiahao Zhao</strong>, et al.
        </i><br>
        A two-stage training strategy (SFT cold-start + RL) to teach LLMs to reason and use search tools for dynamic knowledge acquisition.<br>
        <b><i style="color:#5b8dd9;">EMNLP 2025 &nbsp;</i></b>
        <a href=""><em>[paper]</em></a>
        <a href=""><em>[arXiv]</em></a>
    </div>
  </div>
</div>

<div class="publication-card">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/scaling_retrieval.png" alt="Scaling Laws" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>Scaling Laws For Dense Retrieval in Inference Time</strong><br>
        <i style="font-size: 13px;">
            <strong>Jiahao Zhao</strong>, et al.
        </i><br>
        We characterize how different dense retrieval methods (bi-encoder, Cross Encoder, ColBERT, UniCOIL, SPLADE) scale with model size at inference time, providing practical guidance for model/method selection in production systems.<br>
        <b><i style="color:#5b8dd9;">Preprint &nbsp;</i></b>
        <a href=""><em>[arXiv]</em></a>
    </div>
  </div>
</div>

<div class="publication-card">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/survival_game.png" alt="Survival Game" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>Evaluating Intelligence via Trial and Error</strong><br>
        <i style="font-size: 13px;">
            ..., <strong>Jiahao Zhao</strong>, et al.
        </i><br>
        We propose the Survival Game benchmark: evaluating AI intelligence through the distribution of failure attempts in trial-and-error processes. Comprehensively benchmarks search models, recommendation models, and LLMs. Advised by Academician Bo Zhang.<br>
        <b><i style="color:#5b8dd9;">Preprint &nbsp;</i></b>
        <a href=""><em>[arXiv]</em></a>
    </div>
  </div>
</div>

<script src="assets/js/show_publications.js"></script>

Projects
--------
<div class="project-card">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/search_engine.png" alt="Search Engine" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>Campus Search Engine</strong><br>
        A full-stack search engine crawling ~1M campus webpages and AI-domain content from Xiaohongshu, featuring a web frontend and an RAG-enhanced chatbot.<br>
        <a href=""><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="project-card">
  <div style="display: flex; align-items: center; padding: 10px;">
    <img src="images/openmanus.png" alt="OpenManus" width="200" height="100" style="margin-right: 20px; border-radius: 8px; object-fit: cover;">
    <div>
        <strong>OpenManus — Web Search Contributor</strong><br>
        Contributed the web search functionality to OpenManus, an open-source general-purpose agent framework. The project has garnered <strong>55k+ GitHub stars</strong>.<br>
        <a href="https://github.com/mannaandpoem/OpenManus"><em>[GitHub ⭐ 55k]</em></a>
    </div>
  </div>
</div>

Awards
--------
- **Outstanding Winner + COMAP Scholarship**, MCM 2024 (Rank 4 / 18,525 teams, $10,000)
- **National Scholarship**, Renmin University of China, 2024–2025
- **National Scholarship**, Renmin University of China, 2023–2024

---
