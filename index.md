---
layout: default
title: Hello.
images:
  - image_path: /images/meep.jpg
    title: Meep
---
{% for image in page.images %}
  <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
{% endfor %}
