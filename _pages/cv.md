---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Formation

- Agrégation externe de physique-chimie, 1990

## Emplois

- PRAG UNC, 2021-2024
- Lycée machin

## Enseignements de physique

  <ul>{% for post in site.physique %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Enseignements de chimie

  <ul>{% for post in site.chimie %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
