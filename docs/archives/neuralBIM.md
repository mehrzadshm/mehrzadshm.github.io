---
layout: default
title: Home
nav_order: 1
description: "About me"
nav_exclude: true

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
    window.location.href = "/";

  
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '☀️';

  }
});
</script>

<br>
<br>



# Hello, I'm Mehrzad

Welcome to my personal page! <br>
Here, you'll find a collection of my latest projects, pulications, and coding journeys.
{: .fs-6 .fw-300 }

---
# Short bio
From hard hats to algorithms, I've transitioned from being a construction site supervisor to crafting code and prototyping AI-enabled solutions. Fueled by a passion for innovation and a commitment to efficiency, I'm on a mission to disrupt traditional workflows with scientifically robust and impactful inventions.

[Projects](/docs/projects/){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[About me](#what-we-do){: .btn .fs-5 .mb-4 .mb-md-0 }

## About me 
NeuralBIM-Labs is on a mission to explore the untapped potential of state-of-the-art AI techniques within the Building Information Modeling (BIM) landscape. At the same time, equal emphasis is laid on crafting solutions that are not only innovative but also highly functional. 

At NeuralBIM-Labs, a high priority is placed on openness and the sharing of knowledge. We believe that collective wisdom fosters greater innovation and impact, enriching both the academic and industrial communities.

Major focus areas include:

- **Intuitive Interactions:** Utilizing advanced NLP techniques to enhance user experiences, whether it's for searching within a model or seeking recommendations based on building codes and regulations.

- **Multi-Modal Integration:** Pioneering the use of multi-modal data to enrich BIM models, including text, images, and sensor data for more comprehensive insights and applications.

- **Data Optimization:** Leveraging advanced algorithms to elevate BIM data quality and usability beyond conventional limits. 

- **Automated Workflows:** Harnessing the predictive and reasoning capabilities of AI techniques to automate intricate tasks such as BIM coordination and compliance checking.


----
