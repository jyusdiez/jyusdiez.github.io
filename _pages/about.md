---
layout: page
title: "About"
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---

<!-- Hero section -->
<div style="text-align: center; margin-bottom: 2rem;">

  <!-- Avatar (responsive) -->
  {% if site.author.avatar %}
    <img src="{{ site.baseurl }}/images/{{ site.author.avatar }}" 
         alt="{{ site.author.name }}" 
         style="width:25vw; max-width:150px; height:auto; border-radius:50%; margin-bottom:1rem;">
  {% endif %}

  <!-- Name -->
  <h1 style="font-size:4vw; max-font-size:2.5rem; font-weight:bold; margin-bottom:0.5rem;">
    {{ site.author.name }}
  </h1>

  <!-- Social links (icons only, horizontal) -->
  <div style="margin-top:0.5rem; display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap;">
    {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}" target="_blank"><i class="ai ai-github ai-fw"></i></a>
    {% endif %}
    {% if site.author.linkedin %}
      <a href="{{ site.author.linkedin }}" target="_blank"><i class="ai ai-linkedin ai-fw"></i></a>
    {% endif %}
    {% if site.author.twitter %}
      <a href="{{ site.author.twitter }}" target="_blank"><i class="ai ai-twitter ai-fw"></i></a>
    {% endif %}
    {% if site.author.orcid %}
      <a href="{{ site.author.orcid }}" target="_blank"><i class="ai ai-orcid ai-fw"></i></a>
    {% endif %}
  </div>

</div>
