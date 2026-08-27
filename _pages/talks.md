---
layout: page
title: talks
permalink: /talks/
description: talks, lectures, posters, and research presentations.
nav: true
nav_order: 7
---

<style>
.talk-year {
  display: flex;
  align-items: center;
  gap: 0.85rem;
  margin-top: 2rem;
  margin-bottom: 1rem;
  font-size: 1.55rem;
  font-weight: 800;
  line-height: 1.2;
  color: var(--global-theme-color);
}

.talk-year::after {
  content: "";
  flex: 1;
  height: 2px;
  background: var(--global-theme-color);
  opacity: 0.35;
}

.talk-entry {
  margin-bottom: 1.1rem;
}

.talk-tag {
  display: inline-block;
  padding: 0.18rem 0.48rem;
  margin-right: 0.25rem;
  margin-top: 0.25rem;
  font-size: 0.72rem;
  font-weight: 600;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  border-radius: 999px;
  background-color: var(--global-theme-color);
  color: white;
}

.talk-entry .btn {
  margin-top: 0.25rem;
  margin-left: 0.25rem;
}
</style>

<div class="talk-year">2026</div>

<div class="talk-entry">
  <strong>ML for Systems, Systems for ML</strong><br>
  <span class="text-muted">Lecture, ITU IoT course, Copenhagen, Denmark, April 9</span><br>
  <span class="talk-tag">lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/2026-MLxSystems-IoT.pdf' | relative_url }}" target="_blank">Slides</a>
</div>

<div class="talk-entry">
  <strong>Taming GPU Interference: Safe Co-location and Fair Resource Management</strong><br>
  <span class="text-muted">Workshop talk, SAINTS, Copenhagen, Denmark, March 6</span><br>
  <span class="talk-tag">workshop talk</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/Ehsan-SAINTS%2726.pdf' | relative_url }}" target="_blank">Slides</a>
  <a class="btn btn-sm z-depth-0" href="https://saintslab.github.io/workshop2026/" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-year">2025</div>

<div class="talk-entry">
  <strong>CARMA: Collocation-aware Resource Management System for Deep Learning Training Tasks</strong><br>
  <span class="text-muted">Talk, SUITS Symposium, Copenhagen, Denmark, September 22–25</span><br>
  <span class="talk-tag">talk</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/2025-SUIT-ehsan.pdf' | relative_url }}" target="_blank">Slides</a>
  <a class="btn btn-sm z-depth-0" href="https://suits-25.github.io/" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-entry">
  <strong>CARMA: Collocation-aware Resource Management System for Deep Learning Training Tasks</strong><br>
  <span class="text-muted">Poster, D3A 3.0, Nyborg, Denmark, August 26–27</span><br>
  <span class="talk-tag">poster</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/2025-CARMA-poster.pdf' | relative_url }}" target="_blank">Poster</a>
  <a class="btn btn-sm z-depth-0" href="https://d3aconference.dk/poster-session-d3a-3-0/" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-entry">
  <strong>GPUMemNet: Deep Learning-based Estimation of GPU Memory Requirement for Neural Network Training Tasks</strong><br>
  <span class="text-muted">Poster, D3A 3.0, Nyborg, Denmark, August 26–27</span><br>
  <span class="talk-tag">poster</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/2025-GPUMemNet-poster.pdf' | relative_url }}" target="_blank">Poster</a>
  <a class="btn btn-sm z-depth-0" href="https://d3aconference.dk/poster-session-d3a-3-0/" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-entry">
  <strong>GPU Memory Usage Estimation for Efficient Resource Management for Deep Learning Training</strong><br>
  <span class="text-muted">Workshop talk, ESwML, Rotterdam, Netherlands, March 31.</span><br>
  <span class="talk-tag">workshop talk</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/2025-GPUMemNet-ESwML.pdf' | relative_url }}" target="_blank">Slides</a>
  <a class="btn btn-sm z-depth-0" href="https://eswml.github.io/2025/2025.html" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-year">2024</div>

<div class="talk-entry">
  <strong>Introduction to CUDA Programming</strong><br>
  <span class="text-muted">Guest lecture, Operating Systems and C, IT University of Copenhagen, November 18</span><br>
  <span class="talk-tag">guest lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/CUDA_programming_lecture.pdf' | relative_url }}" target="_blank">Slides</a>
  <a class="btn btn-sm z-depth-0" href="https://github.com/ehsanyousefzadehasl/CUDA_for_ITU" target="_blank" rel="noopener noreferrer">Code</a>
  <a class="btn btn-sm z-depth-0" href="https://www.youtube.com/watch?v=J_PyywWtqXY" target="_blank" rel="noopener noreferrer">Video</a>
</div>

<div class="talk-entry">
  <strong>GPUs, FPGAs, Accelerators</strong><br>
  <span class="text-muted">Guest lecture, Operating Systems and C, IT University of Copenhagen, November 11</span><br>
  <span class="talk-tag">guest lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/Processors_lecture.pdf' | relative_url }}" target="_blank">Slides</a>
  <a class="btn btn-sm z-depth-0" href="https://www.youtube.com/watch?v=4-Bd5PxJMgw" target="_blank" rel="noopener noreferrer">Video</a>
</div>

<div class="talk-entry">
  <strong>Resource-Efficient Training via Task Collocation on GPUs</strong><br>
  <span class="text-muted">Presentation and poster, D3A 1.0, Nyborg, Denmark, February 1–2</span><br>
  <span class="talk-tag">presentation</span>
  <a class="btn btn-sm z-depth-0" href="https://d3aconference.dk/d3a-1-0/" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-year">2023</div>

<div class="talk-entry">
  <strong>Profiling and Monitoring Deep Learning Training Tasks</strong><br>
  <span class="text-muted">Paper presentation, EuroMLSys, Rome, Italy, May 8</span><br>
  <span class="talk-tag">paper presentation</span>
  <span class="talk-tag">poster</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/profiling_and_monitoring_poster.pdf' | relative_url }}">Poster</a>
  <a class="btn btn-sm z-depth-0" href="https://euromlsys.eu/" target="_blank" rel="noopener noreferrer">Venue</a>
  <a class="btn btn-sm z-depth-0" href="https://www.youtube.com/watch?v=-dZkowi_zpM" target="_blank" rel="noopener noreferrer">Video</a>
</div>

<div class="talk-entry">
  <strong>Orchestration of Deep Learning Tasks on CPU-GPU Co-Processors for Multi-Tenant Settings</strong><br>
  <span class="text-muted">Presentation and poster, EuroSys Doctoral Workshop, Rome, Italy, May 2023.</span><br>
  <span class="talk-tag">presentation</span>
  <span class="talk-tag">poster</span>
  <a class="btn btn-sm z-depth-0" href="https://2023.eurosys.org/euroDW.html" target="_blank" rel="noopener noreferrer">Venue</a>
</div>

<div class="talk-entry">
  <strong>Processors</strong><br>
  <span class="text-muted">Guest lecture, Large Scale Data Analysis / Big Data Management, IT University of Copenhagen, April; November</span><br>
  <span class="talk-tag">guest lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/Processors_lecture.pdf' | relative_url }}" target="_blank">Slides</a>
</div>

<div class="talk-year">2022</div>

<div class="talk-entry">
  <strong>Overprovisioning GPUs in the age of AI</strong><br>
  <span class="text-muted">Guest lecture, Large Scale Data Analysis, IT University of Copenhagen, November</span><br>
  <span class="talk-tag">guest lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/gpu-provisioning.pdf' | relative_url }}" target="_blank">Slides</a>
</div>

<div class="talk-entry">
  <strong>Processors</strong><br>
  <span class="text-muted">Guest lecture, Large Scale Data Analysis / Big Data Management, IT University of Copenhagen, April; November</span><br>
  <span class="talk-tag">guest lecture</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/Processors_lecture.pdf' | relative_url }}" target="_blank">Slides</a>
</div>

<div class="talk-entry">
  <strong>GPU Efficiency through Intelligent Collocation</strong><br>
  <span class="text-muted">Poster, REAML Summer School, Dortmund, Germany, September</span><br>
  <span class="talk-tag">poster</span>
  <a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/talks/GPU-efficiency-through-intelligent-collocation-Ehsan-Yousefzadeh-Asl-Miandoab.pdf' | relative_url }}" target="_blank">Poster</a>
</div>
