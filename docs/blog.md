---
layout: default
title: Blog
nav_order: 4
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
    window.location.href = "/docs/blog";

  
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = '☀️';

  }
});
</script>

<br>
<br>

# September, 2023


{: .fs-6 .fw-300 }
