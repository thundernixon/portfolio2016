---
layout: about
---
<div class="blog-index">

<!-- copy paste from stack overflow -->
  <ul class="post-list">
    {% for post in site.work %}
      <li>
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}
                <img src="{{ site.baseurl }}/imagens/{{ post.image }}">
                </a>
        </h2>
      </li>
    {% endfor %}
  </ul>
</div>
