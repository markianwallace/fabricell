---
layout: default
---
{% for post in site.tags.meetings limit: 20 %}
<h1><a href="{{ post.url }}">{{post.meetingdate}} {{ post.title }}</a></h1>
  <p>{{ post.excerpt }}</p>
{% endfor %}