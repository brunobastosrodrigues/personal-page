---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  /* --- Intro & Visuals --- */
  .research-intro {
    font-size: 1.1em;
    line-height: 1.6;
    margin-bottom: 2em;
    color: #444;
  }

  .lab-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-bottom: 3em;
  }

  .lab-figure {
    margin: 0;
    border: 1px solid #eee;
    padding: 10px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
  }

  .lab-figure img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    display: block;
  }

  .lab-caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #666;
    text-align: center;
    font-style: italic;
  }

  /* --- Themes Grid --- */
  .section-title {
    font-size: 1.5em;
    border-bottom: 2px solid #f2f3f3;
    padding-bottom: 10px;
    margin-bottom: 20px;
    margin-top: 40px;
  }

  .theme-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }

  .theme-card {
    background: #fdfdfd;
    border: 1px solid #e0e0e0;
    border-top: 3px solid #007bff; /* Blue accent top */
    padding: 20px;
    border-radius: 4px;
  }

  .theme-header {
    font-weight: bold;
    font-size: 1.1em;
    margin-bottom: 10px;
    color: #333;
  }

  .theme-text {
    font-size: 0.95em;
    color: #555;
    line-height: 1.5;
  }

  /* --- Project Timeline --- */
  .timeline {
    position: relative;
    padding-left: 20px;
    margin-top: 20px;
    border-left: 2px solid #e0e0e0;
  }

  .project-item {
    position: relative;
    margin-bottom: 30px;
    padding-left: 20px;
  }

  /* The Dot on the timeline */
  .project-item::before {
    content: '';
    position: absolute;
    left: -26px; /* Adjust based on border width and padding */
    top: 5px;
    width: 12px;
    height: 12px;
    background: #fff;
    border: 2px solid #007bff;
    border-radius: 50%;
  }

  .project-title {
    font-size: 1.1em;
    font-weight: bold;
    color: #222;
  }

  .project-meta {
    font-size: 0.85em;
    color: #888;
    margin-bottom: 8px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  .project-desc {
    font-size: 0.95em;
    color: #444;
  }

  /* Dark Mode adjustments */
  @media (prefers-color-scheme: dark) {
    .research-intro, .theme-text, .project-desc { color: #ccc; }
    .lab-figure, .theme-card { background: #252a34; border-color: #333; }
    .theme-header, .project-title { color: #f0f0f0; }
    .timeline { border-left-color: #444; }
    .project-item::before { background: #252a34; border-color: #007bff; }
  }
</style>

<div class="research-intro">
  My research investigates secure and privacy-aware sensing systems in the Internet of Things (IoT). 
  I focus on how we perceive, interpret, and act on physical world information through digital systems, 
  with a particular interest in <strong>passive sensing</strong>, <strong>multi-modal data fusion</strong>, 
  and <strong>cyber-physical security</strong>.
</div>

<div class="lab-gallery">
  <figure class="lab-figure">
    <img src="/images/img-setup.jpg" alt="Passive wireless sensor setup">
    <figcaption class="lab-caption">
      Passive wireless sensor setup for real-world data collection.
    </figcaption>
  </figure>
  <figure class="lab-figure">
    <img src="/images/img-heatmap.png" alt="Heatmap of occupancy">
    <figcaption class="lab-caption">
      Heatmap visualizing occupancy patterns from fused sensor data.
    </figcaption>
  </figure>
</div>

<h2 class="section-title">Research Themes</h2>
<div class="theme-grid">
  
  <div class="theme-card">
    <div class="theme-header">Passive Sensing & Tracking</div>
    <div class="theme-text">
      Leveraging BLE, Wi-Fi, ZigBee, and LiDAR signals to unobtrusively track people and assets without active cooperation. Used for occupancy analytics and crowd flow.
    </div>
  </div>

  <div class="theme-card">
    <div class="theme-header">Privacy-Preserving Perception</div>
    <div class="theme-text">
      Designing systems that ensure privacy through selective sensing (e.g., depth-only LiDAR), anonymized signal processing, and differential handling of personal data.
    </div>
  </div>

  <div class="theme-card">
    <div class="theme-header">Secure IoT Systems</div>
    <div class="theme-text">
      Mitigating cyber threats like DDoS attacks and unauthorized profiling by securing the communication and behavioral footprint of IoT devices.
    </div>
  </div>

  <div class="theme-card">
    <div class="theme-header">Multi-Modal Fusion</div>
    <div class="theme-text">
      Combining heterogeneous sensor data (RF, LiDAR, thermal) to enhance robustness, reduce noise, and support contextual awareness in real-world deployments.
    </div>
  </div>

</div>

<h2 class="section-title">Project Experience</h2>
<div class="timeline">

  <div class="project-item">
    <div class="project-title">PasWITS – Passive Wireless Tracking Intelligence</div>
    <div class="project-meta">2020–2022 | Funded by Innosuisse</div>
    <div class="project-desc">
      Developed a privacy-preserving localization system using BLE and Wi-Fi signals. I led the architectural design, coordinated student development, and oversaw prototype testing with industry partners.
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">H2020 CONCORDIA – Cybersecurity Network</div>
    <div class="project-meta">2019–2022 | European Commission</div>
    <div class="project-desc">
      Contributed to distributed network defense (Task 1.2), the economics of cybersecurity, and piloted the DDoS Clearing House for Europe (Task 3.2).
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">BC4CC – Blockchain Cold Chain Monitoring</div>
    <div class="project-meta">2018–2019 | Swiss KTI</div>
    <div class="project-desc">
      Designed an interoperability framework matching policy constraints to optimal blockchain platforms for pharmaceutical logistics.
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">E2C – Energy Efficiency to Clouds</div>
    <div class="project-meta">2015–2016 | Laboratory of Sustainability (USP)</div>
    <div class="project-desc">
      Developed resource allocation strategies tailored to energy-aware user profiles and coordinated technical activities.
    </div>
  </div>

  <div class="project-item">
    <div class="project-title">SOS – Sustainability-Oriented SDN Policies</div>
    <div class="project-meta">2014–2015</div>
    <div class="project-desc">
      Developed an SDN-based control system for energy-efficient networking, including dynamic policy refinement for data center infrastructure.
    </div>
  </div>

</div>

<div style="margin-top:3em; text-align: center; padding: 20px; background: #f9f9f9; border-radius: 8px;">
  <strong>Interested in the results?</strong> <br>
  Explore the <a href="/publications/" style="text-decoration:none; color: #007bff; font-weight:bold;">Publications Page &rarr;</a>
</div>