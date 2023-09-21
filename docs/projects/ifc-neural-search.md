---
layout: default
title: IFC-NeuralSearch
parent: Projects
nav_order: 1
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
    window.location.href = "/docs/projects/ifc-neural-search";

  
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '☀️';

  }
});
</script>

<br>
<br>


# IFC-NeuralSearch

Neural Language Models Meet BIM: Watch How It Works
{: .fs-5 .fw-300 }



<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/YR8k_OZs-CA" frameborder="0" allowfullscreen></iframe>
</div>

<br>

[Try live demo](#live-demo){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[Learn more](#project-insights){: .btn .fs-5 .mb-4 .mb-md-0 }


## Overview

Originally born as a research initiative during my PhD studies at [École de technologie supérieure](https://www.etsmtl.ca/), IFC-NeuralSearch has found its niche at the intersection of advanced Natural Language Processing (NLP) techniques and Building Information Modeling (BIM). While its roots lie in academic research, the project's vision extends beyond theory; **It serves as tangible proof of what's possible not in some distant future, but right here, right now!**

---

## Project insights

### Motivation
Minding the gap
{: .fs-5 .fw-300 }

The driving force behind IFC-NeuralSearch is to bridge the **technical knowledge gap** that often impedes the wider adoption of Building Information Modeling (BIM), and Industry Foundation Classes (IFC) standard in particular. Most practitioners lack the expertise to formulate formal queries and understanding complex data schemas can be an overwhelming task. 

This *ungoing* project aims to eliminate the mentioned **Information Retreival Bottleneck** by enhancing the intuitiveness and effectiveness of the search experience, thus making BIM more accessible and user-friendly for stakeholders across diverse backgrounds.


### Scope & objectives
IFC-NeuralSearch is engineered to revolutionize the search experience in Building Information Modeling (BIM). Leveraging **deep neural language models**, it enables intuitive, text-based queries. At the heart of IFC-NeuralSearch is the Industry Foundation Classes (IFC) standard, which serves as the foundational layer of our design.

Unlike conventional search mechanisms that rely on keywords and lexical characteristics, pre-defined templates, or object trees, IFC-NeuralSearch delivers a contextual and semantically-aware understanding of natural language queries related to building entities and their descriptions. 

The project's ultimate goal is to faciliate a more streamlined and democratized BIM experience, empowering a diverse range of professionals to **focus on meaningful data**.

---

## Live demo
IFC-NeuralSearch in Action
{: .fs-5 .fw-300 }

Curious about how it works? After all, seeing is believing! Witness firsthand how the search experience in BIM can be redefined. **Before igniting the search engine:**


{: .warning-title }
> Important
>
> * The demo app is NOT optimized for phone/tablet screens. 
> * This is a work in progress; future updates will cover more search capabilities. 
> * MEP (Mechanical, Electrical Plumbing) demo currently NOT functional. 

<br>

[Go to demo page  <i class="fas fa-external-link-alt fa-sm"></i>](https://demo.text2ifc.com/){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Publications; Sharing is caring
We are deeply committed to contributing to the greater body of knowledge in this evolving field. To ensure maximum dissemination and accessibility, all findings garnered through this research initiative will be published in **open-access scientific journals**. Stay tuned!

---
