---
layout: about
---
<div class="blog-index">
  {% for post in site.work offset:1 limit:1 %}
  {% endfor %}
  {% include post_detail.html %}
</div>
