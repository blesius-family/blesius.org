---
layout: default
images:
  - image_path: /ckb/00.jpg
    title: Das Geburt
  - image_path: /ckb/01.jpg
    title: Das Kind
---
<ul class="gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
