---
layout: blog
title: Tags
---
{% capture tags %}
  {% for tag in site.tags %}
    {{ tag[0] }}
  {% endfor %}
{% endcapture %}
{% assign sortedtags = tags | split:' ' | sort %}

{% for tag in sortedtags %}
### {{ tag }}
  {% for post in site.tags[tag] %}
  - **{{ post.date | date: "%Y-%d-%m" }}** [{{ post.title }}]({{ post.url }})
  {% endfor %}
{% endfor %}

{% include footer.html %}