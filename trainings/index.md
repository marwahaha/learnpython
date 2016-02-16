---
layout: page
---
{% for post in site.categories.trainings %}
  {{ DIVIDER }}
  *{{ post.date | date_to_long_string}}*

## [{{ post.title }}]({{ site.url }}/learnpython{{ post.url }})

  {{ post.content }}

  {% assign DIVIDER = "---" %}
{% endfor %}

