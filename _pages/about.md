---
layout: page
title: "About"
permalink: /about/
author_profile: true
---

<div class="container text-center" style="margin-top: 3rem; margin-bottom: 3rem;">

  <!-- Profile picture -->
  <img src="{{ site.baseurl }}/assets/images/profile.png" alt="{{ site.author.name }}" class="avatar">

  <!-- Name -->
  <h1>{{ site.author.name }}</h1>

  <!-- Short bio -->
  <p>{{ site.author.bio }}</p>

  <!-- Links (only show if defined in _config.yml) -->
  <p>
    {% if site.author.github %}
      <a href="https://github.com/{{ site.author.github }}" target="_blank"><i class="fab fa-github"></i> GitHub</a>
    {% endif %}
    {% if site.author.orcid %}
      <a href="{{ site.author.orcid }}" target="_blank"><i class="fab fa-orcid"></i> ORCID</a>
    {% endif %}
    {% if site.author.googlescholar %}
      <a href="{{ site.author.googlescholar }}" target="_blank"><i class="ai ai-google-scholar"></i> Google Scholar</a>
    {% endif %}
    {% if site.author.linkedin %}
      <a href="{{ site.author.linkedin }}" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
    {% endif %}
  </p>

</div>
