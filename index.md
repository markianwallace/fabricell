---
layout: default
---
{% for post in site.posts limit:10 %}
<div class="container">
  <img src="/assets/images/{{post.image}}" alt="{{post.image}}">
  <div class="bottomright"><h1><a href="{{ post.url }}">{{ post.title }}</a></h1></div>

</div>
  <p>{{ post.excerpt }}</p>

{% endfor %}
