---
layout: splash
title: "Pablo César"
permalink: /
header:
  overlay_color: none
  overlay_filter: "0"
  actions:
    - label: "See My Work"
      url: "/projects/"
    - label: "About Me"
      url: "/about/"
excerpt: "Gamedev · Film · Transmedia"
read_time: false
---

<!-- Video de fondo ubicado antes que el resto del contenido -->
<video autoplay loop muted playsinline id="background-video">
  <source src="{{ '/assets/videos/background.mp4' | relative_url }}" type="video/mp4">
  Tu navegador no soporta el video.
</video>

{% include feature_row id="intro" %}
{% include feature_row id="projects" %}
