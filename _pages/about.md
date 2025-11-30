---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* --- Intro Section --- */
  .hero-text {
    font-size: 1.1em;
    line-height: 1.6;
    color: #333;
    margin-bottom: 1.5em;
  }

  /* --- Research Focus Box --- */
  .focus-box {
    background-color: #f8f9fa;
    border-left: 5px solid #007bff; /* Blue accent for Networks/Systems */
    padding: 1.2em 1.5em;
    margin: 2em 0;
    color: #444;
    border-radius: 4px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }

  /* --- Impact Grid (Scholar Data) --- */
  .impact-grid {
    display: flex;
    gap: 15px;
    margin-bottom: 2.5em;
    flex-wrap: wrap;
  }

  .impact-card {
    flex: 1;
    min-width: 140px;
    background: linear-gradient(145deg, #ffffff, #f4f4f4);
    border: 1px solid #e0e0e0;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    transition: transform 0.2s, border-color 0.2s;
  }

  .impact-card:hover {
    transform: translateY(-2px);
    border-color: #007bff;
  }

  .impact-number {
    font-size: 1.8em;
    font-weight: 800;
    color: #007bff;
    display: block;
    margin-bottom: 4px;
  }

  .impact-label {
    font-size: 0.8em;
    text-transform: uppercase;
    color: #666;
    letter-spacing: 0.5px;
    font-weight: 600;
  }

  /* --- News Section --- */
  .news-container {
    margin-top: 3em;
    margin-bottom: 3em;
  }
  
  .news-header {
    border-bottom: 2px solid #eee;
    padding-bottom: 10px;
    margin-bottom: 15px;
    font-size: 1.3em;
    color: #222;
  }

  .news-item {
    display: flex;
    gap: 15px;
    margin-bottom: 12px;
    font-size: 0.95em;
    line-height: 1.5;
  }

  .news-date {
    font-weight: bold;
    color: #555;
    min-width: 85px;
    font-size: 0.9em;
  }

  /* --- Dark Mode Adjustments --- */
  @media (prefers-color-scheme: dark) {
    .hero-text, .focus-box { color: #ccc; }
    .focus-box { background-color: #252a34; border-color: #007bff; }
    .impact-card { background: #252a34; border-color: #444; }
    .impact-label, .news-date { color: #aaa; }
    .news-header { color: #f0f0f0; border-color: #444; }
  }
</style>

<div class="hero-text">
  I am a Tenure-Track Assistant Professor for <strong>Embedded Sensing Systems and Industrial Networks</strong> at the Institute of Computer Science in Vorarlberg [(ICV)](https://icv.unisg.ch/), School of Computer Science [(SCS)](https://www.unisg.ch/de/universitaet/schools/computer-science/), University of St. Gallen [(HSG)](https://www.unisg.ch/en/).
  <br><br>
  My work bridges the gap between <strong>Network Security</strong>, <strong>Distributed Systems</strong>, and the <strong>Physical World</strong>. I investigate how to build resilient digital infrastructures that can securely sense, interpret, and interact with their environments.
</div>

<div class="impact-grid">
  <a href="https://scholar.google.com/citations?user=V55fIyEAAAAJ" target="_blank" style="text-decoration:none; flex:1;">
    <div class="impact-card">
      <span class="impact-number">1,600+</span>
      <span class="impact-label">Citations</span>
    </div>
  </a>
  <a href="https://scholar.google.com/citations?user=V55fIyEAAAAJ" target="_blank" style="text-decoration:none; flex:1;">
    <div class="impact-card">
      <span class="impact-number">21</span>
      <span class="impact-label">h-index</span>
    </div>
  </a>
  <a href="/publications/" style="text-decoration:none; flex:1;">
    <div class="impact-card">
      <span class="impact-number">60+</span>
      <span class="impact-label">Publications</span>
    </div>
  </a>
</div>

<div class="focus-box">
  <strong>Primary Research Focus:</strong><br>
  Designing <strong>secure and distributed network architectures</strong> for Cyber-Physical Systems (CPS).
  Key areas include passive wireless intelligence, collaborative DDoS defense, and privacy-preserving data fusion in industrial and smart environments.
</div>

### Short Bio
Before joining HSG, I received my doctoral degree from the **University of Zurich (UZH)** in 2020, where I also served as a postdoctoral researcher until 2024. My PhD thesis focused on **collaborative signaling systems** and cross-domain architectures to mitigate **Distributed Denial-of-Service (DDoS)** attacks. During my postdoc, I expanded this expertise into the physical layer, exploring **passive wireless sensing** (Wi-Fi/BLE) and the privacy implications of RF-based tracking.

Prior to my PhD, I was a researcher at the **University of São Paulo (USP)**, Brazil, collaborating with **Ericsson Research** (2013–2016). My work there centered on **Software-Defined Networking (SDN)** and resource orchestration in cloud environments. I hold an MSc in Computer Science from USP, where I optimized energy efficiency in virtualized networks, and a BSc from UDESC, focusing on cloud security and large-scale distributed systems analysis.

<div class="news-container">
  <h3 class="news-header">📢 Latest Updates</h3>
  
  <div class="news-item">
    <div class="news-date">Oct 2024</div>
    <div>
      Paper accepted at <strong>IFIP/IEEE CNSM 2024</strong>: <em>"Big Brother is Watching You: Non-Intrusive ZigBee User Profiling."</em> <a href="/publications/">[Read more]</a>
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">Sep 2024</div>
    <div>
      Joined the <strong>University of St. Gallen (HSG)</strong> as Assistant Professor.
    </div>
  </div>
  
   <div class="news-item">
    <div class="news-date">May 2024</div>
    <div>
      Invited talk at <strong>University of Zürich (CSG)</strong> on privacy risks in passive RF sensing systems.
    </div>
  </div>

</div>