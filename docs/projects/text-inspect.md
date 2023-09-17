---
layout: default
title: textInspect.AEC
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
    window.location.href = "/docs/projects/text-inspect";

  
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '☀️';

  }
});
</script>

<br>
<br>


# textInspect.AEC

Semantic search for openBIM
{: .fs-6 .fw-300 }


[Try live demo <i class="fas fa-external-link-alt"></i>](https://demo.text2ifc.com/text-inspect.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

{: .warning-title }
> Important
>
> * The demo app is NOT optimized for phone/tablet screens. 
> * This is a work in progress; future updates will cover more search capabilities. 


# Stay tuned for more information



