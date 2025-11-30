---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* --- General Text Styling --- */
  .profile-text {
    font-size: 0.95em; /* Slightly smaller font as requested */
    line-height: 1.6;
    color: #333;
  }

  .profile-text a {
    text-decoration: none;
    color: #007bff;
  }

  .profile-text a:hover {
    text-decoration: underline;
  }

  /* --- Intro Section --- */
  .hero-block {
    margin-bottom: 2em;
  }

  /* --- Research Focus Box --- */
  .focus-box {
    background-color: #f8f9fa;
    border-left: 4px solid #007bff; /* Blue accent for Networks */
    padding: 1em 1.2em;
    margin: 2em 0;
    color: #444;
    font-size: 0.9em; /* Compact font for the box */
    border-radius: 4px;
  }

  /* --- News Section --- */
  .news-container {
    margin-top: 3em;
    margin-bottom: 3em;
  }
  
  .news-header {
    border-bottom: 2px solid #eee;
    padding-bottom: 8px;
    margin-bottom: 15px;
    font-size: 1.2em;
    color: #222;
  }

  .news-item {
    display: flex;
    gap: 15px;
    margin-bottom: 10px;
    font-size: 0.9em; /* Smaller font for news */
    line-height: 1.5;
  }

  .news-date {
    font-weight: bold;
    color: #555;
    min-width: 80px;
  }

  /* --- Dark Mode Adjustments --- */
  @media (prefers-color-scheme: dark) {
    .profile-text, .focus-box, .news-item { color: #ccc; }
    .focus-box { background-color: #252a34; border-color: #007bff; }
    .news-date { color: #aaa; }
    .news-header { color: #f0f0f0; border-color: #444; }
  }
</style>

<div class="profile-text">
  
  <div class="hero-block">
    I am a Tenure-Track Assistant Professor for <strong>Embedded Sensing Systems and Industrial Networks</strong> at the Institute of Computer Science in Vorarlberg <a href="https://icv.unisg.ch/" target="_blank">(ICV)</a>, School of Computer Science <a href="https://www.unisg.ch/de/universitaet/schools/computer-science/" target="_blank">(SCS)</a>, University of St. Gallen <a href="https://www.unisg.ch/en/" target="_blank">(HSG)</a>.
    <br><br>
    My work bridges the gap between <strong>Network Security</strong>, <strong>Distributed Systems</strong>, and the <strong>Physical World</strong>. I investigate how to build resilient digital infrastructures that can securely sense, interpret, and interact with their environments.
  </div>

  <div class="focus-box">
    <strong>Primary Research Focus:</strong><br>
    Designing <strong>secure and distributed network architectures</strong> for Cyber-Physical Systems (CPS).
    Key areas include passive wireless intelligence, collaborative DDoS defense, and privacy-preserving data fusion in industrial and smart environments.
  </div>

  <h3>Short Bio</h3>
  <p>
    Before joining HSG, I received my doctoral degree from the <strong>University of Zurich (UZH)</strong> in 2020, where I also served as a postdoctoral researcher until 2024. My PhD thesis focused on <strong>collaborative signaling systems</strong> and cross-domain architectures to mitigate <strong>Distributed Denial-of-Service (DDoS)</strong> attacks. During my postdoc, I expanded this expertise into the physical layer, exploring <strong>passive wireless sensing</strong> (Wi-Fi/BLE) and the privacy implications of RF-based tracking.
  </p>
  <p>
    Prior to my PhD, I was a researcher at the <strong>University of São Paulo (USP)</strong>, Brazil, collaborating with <strong>Ericsson Research</strong> (2013–2016). My work there centered on <strong>Software-Defined Networking (SDN)</strong> and resource orchestration in cloud environments. I hold an MSc in Computer Science from USP, where I optimized energy efficiency in virtualized networks, and a BSc from UDESC, focusing on cloud security and large-scale distributed systems analysis.
  </p>

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

</div>