---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* --- General Typography --- */
  .profile-text {
    font-size: 0.95em;
    line-height: 1.7; /* Increased slightly for better readability without bold */
    color: #333;
    font-weight: 400; /* Ensures a clean, normal weight */
  }

  .profile-text a {
    text-decoration: none;
    color: #007bff;
    font-weight: 500; /* Links get a tiny bit of weight to stand out */
  }

  .profile-text a:hover {
    text-decoration: underline;
  }

  /* --- The "Topic Cloud" (Your visual interest) --- */
  .topic-container {
    text-align: center;
    margin: 2.5em 0;
    padding: 20px;
    background: linear-gradient(to bottom, #fcfcfc, #f4f6f8);
    border: 1px solid #eee;
    border-radius: 8px;
  }

  .topic-header {
    font-size: 0.8em;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #888;
    margin-bottom: 15px;
    display: block;
  }

  .topic-cloud {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
  }

  .topic-tag {
    background-color: #fff;
    border: 1px solid #e0e0e0;
    color: #555;
    padding: 6px 14px;
    border-radius: 20px; /* Pill shape */
    font-size: 0.85em;
    transition: all 0.2s ease;
    cursor: default;
  }

  /* Interactive hover effect */
  .topic-tag:hover {
    border-color: #007bff;
    color: #007bff;
    transform: translateY(-2px);
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

  /* --- Focus Box (Simplified) --- */
  .focus-box {
    border-left: 3px solid #007bff;
    padding-left: 15px;
    margin: 2em 0;
    color: #555;
    font-style: italic;
  }

  /* --- Dark Mode Support --- */
  @media (prefers-color-scheme: dark) {
    .profile-text, .focus-box { color: #ccc; }
    .topic-container { background: #252a34; border-color: #444; }
    .topic-tag { background-color: #333; border-color: #444; color: #ccc; }
    .topic-tag:hover { border-color: #007bff; color: white; }
  }
</style>

<div class="profile-text">
  
  <div style="margin-bottom: 2em;">
    I am a Tenure-Track Assistant Professor for Embedded Sensing Systems and Industrial Networks at the Institute of Computer Science in Vorarlberg <a href="https://icv.unisg.ch/" target="_blank">(ICV)</a>, School of Computer Science <a href="https://www.unisg.ch/de/universitaet/schools/computer-science/" target="_blank">(SCS)</a>, University of St. Gallen <a href="https://www.unisg.ch/en/" target="_blank">(HSG)</a>.
    <br><br>
    My work bridges the gap between Network Security, Distributed Systems, and the Physical World. I investigate how to design systems that can securely sense, interpret, and interact with their environments.
  </div>

  <div class="topic-container">
    <span class="topic-header">Research Ecosystem</span>
    <div class="topic-cloud">
      <span class="topic-tag">Network Security</span>
      <span class="topic-tag">Distributed Systems</span>
      <span class="topic-tag">Passive Sensing</span>
      <span class="topic-tag">DDoS Defense</span>
      <span class="topic-tag">Cyber-Physical Systems</span>
      <span class="topic-tag">IoT Security</span>
      <span class="topic-tag">Privacy Preservation</span>
      <span class="topic-tag">Multi-Modal Fusion</span>
      <span class="topic-tag">Industrial Networks</span>
      <span class="topic-tag">Blockchain Architectures</span>
    </div>
  </div>

  <div class="focus-box">
    Primary focus: Designing secure and distributed network architectures for Cyber-Physical Systems, with specific applications in logistics, smart environments, and privacy-preserving data fusion.
  </div>

  <h3>Short Bio</h3>
  <p>
    Before joining HSG, I received my doctoral degree from the University of Zurich (UZH) in 2020, where I also served as a postdoctoral researcher until 2024. My PhD thesis focused on collaborative signaling systems and cross-domain architectures to mitigate Distributed Denial-of-Service (DDoS) attacks. During my postdoc, I expanded this expertise into the physical layer, exploring passive wireless sensing (Wi-Fi/BLE) and the privacy implications of RF-based tracking.
  </p>
  <p>
    Prior to my PhD, I was a researcher at the University of São Paulo (USP), Brazil, collaborating with Ericsson Research (2013–2016). My work there centered on Software-Defined Networking (SDN) and resource orchestration in cloud environments. I hold an MSc in Computer Science from USP, where I optimized energy efficiency in virtualized networks, and a BSc from UDESC, focusing on cloud security and large-scale distributed systems analysis.
  </p>

</div>