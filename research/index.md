---
title: Research
nav:
  order: 1
  tooltip: List of active research projects
---

# {% include icon.html icon="fa-solid fa-droplet" %}Research Projects

Below are a list of currently active and past reseach projects led by the Shah lab group. These research projects are an exciting way for us to bring new scientific discoveries to the forfront of our field that we hope impact people's lives and the natural world around us.

{% include tags.html tags="publication, funded, collaboration" %}

{% include search-info.html %}

{% include section.html %}

## Current Projects

<div style="display: block; width: 100%; max-width: 800px; margin: 0 auto;">
  {% include list.html component="card" data="projects" filter="group == 'Current Projects'" %}
</div>

{% comment %}
{% include list.html component="card" data="projects" filter="group == 'Current Projects'" %}

{% include section.html %}
{% endcomment %}

## Past Projects

{% include list.html component="card" data="projects" filter="!group" style="small" %}
