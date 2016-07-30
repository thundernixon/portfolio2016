---
layout: about
---
<div class="blog-index">
  {% for post in site.posts offset:1 limit:1 %}
  {% endfor %}
  {% include post_detail.html %}
</div>
