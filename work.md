---
layout: about
---
<div class="blog-index">
  {% for work in site.work offset:1 limit:1 %}
  {% endfor %}
  <!-- {% include post_detail.html %} -->
  {% include work_index.html %}
  <!-- /Users/stephennixon/code/portfolio2016/_includes/work_index.html -->
</div>
