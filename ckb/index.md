---
layout: default
images:
  - image_path: /ckb/00.jpg
    title: Das Geburt
  - image_path: /ckb/01.jpg
    title: Kindheit 1
  - image_path: /ckb/02.jpg
    title: Kindheit 2
---
<ul class="ckb-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
