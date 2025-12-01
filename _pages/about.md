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
<div class="about-hero" style="margin-bottom: 2rem;">

  <!-- Avatar -->
  {% if site.author.avatar %}
    <img src="{{ site.baseurl }}/images/{{ site.author.avatar }}" alt="{{ site.author.name }}" class="avatar">
  {% endif %}

  <!-- Name -->
  <h1 style="font-size: 3rem; font-weight: bold; margin-top: 1rem;">
    {{ site.author.name }}
  </h1>

  <!-- Bio -->
  {% if site.author.bio %}
    <p style="font-size: 1.2rem; margin-top: 0.5rem; max-width: 600px; margin-left: auto; margin-right: auto;">
      {{ site.author.bio }}
    </p>
  {% endif %}

  <!-- Social links -->
  <div class="author-social" style="margin-top: 1rem;">
    {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}" target="_blank"><i class="ai ai-github ai-fw icon-pad-right"></i></a>
    {% endif %}
    {% if site.author.linkedin %}
      <a href="{{ site.author.linkedin }}" target="_blank"><i class="ai ai-linkedin ai-fw icon-pad-right"></i></a>
    {% endif %}
    {% if site.author.twitter %}
      <a href="{{ site.author.twitter }}" target="_blank"><i class="ai ai-twitter ai-fw icon-pad-right"></i></a>
    {% endif %}
    {% if site.author.orcid %}
      <a href="{{ site.author.orcid }}" target="_blank"><i class="ai ai-orcid ai-fw icon-pad-right"></i></a>
    {% endif %}
  </div>

</div>

<!-- Rest of the page content -->
# About

I am an aerosol scientist and 
