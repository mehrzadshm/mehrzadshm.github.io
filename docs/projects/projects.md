---
layout: default
title: Projects
nav_order: 2
has_children: true
permalink: /docs/projects
has_toc: false
---

<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>

<button class="btn js-toggle-dark-mode" style="float: right;"> <i class="fas fa-moon"></i> </button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = ' ';
    window.location.href = "/docs/projects";

  
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '☀️';

  }
});
</script>

<br>
## IFC-NeuralSearch

<div style="display: flex; justify-content: space-between;">
  <div style="flex: 1;">
    <p class="fs-5 fw-300">Streamlining intuitive and quick interactions with openBIM models by harnessing the power of custom-trained language models.</p>
    <a href="/docs/projects/ifc-neural-search" class="btn fs-5 mb-4 mb-md-0">Learn more</a>
  </div>
  <div style="flex: 0.1;"></div> <!-- Empty column for spacing -->
  <div style="flex: 1;">
    <img src="/assets/images/ifc-neural.gif" width="800">
  </div>
</div>
---


## textInspect.AEC
<br>
<div style="display: flex; justify-content: space-between;">
  <div style="flex: 1;">
     <img src="/assets/images/entities.png" width="300">
  </div>
  <div style="flex: 0.1;"></div> <!-- Empty column for spacing -->
  <div style="flex: 1;">
    <p class="fs-5 fw-300">Adapting Large Language Models for specialized entity extraction in the Architecture, Engineering, and Construction (AEC) sector. </p>
    <a href="/docs/projects/text-inspect" class="btn fs-5 mb-4 mb-md-0">Learn more</a>
  </div>
</div>

