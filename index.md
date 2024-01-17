---
layout: default
images:
  - image_path: /images/meep.jpg
    title: Meep
---
# hi.
<ul class="gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
