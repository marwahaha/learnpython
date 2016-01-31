---
layout: page
title: Past Meetings
comments: true
permalink: /past/
---

* content
{:toc}

## Past Meetings
Here is a list of topics from our previous meetings and associated learning resources.

### Spring 2016


There have been no meetings yet. 

Our first meeting is on **February 8, at 5pm: [&#34;What&#39;s the big deal about Python?&#34;](http://marwahaha.github.io/learnpython/2016-02-08-the-big-deal-about-python/)**


<div class="all-posts" post-cate="All">
  {% assign curDate = site.time | date: '%s' %}
  {% for post in site.posts %}
    {% assign postStartDate = post.date | date: '%s' %}
    {% if postStartDate <= curDate %}
      <a class="post-list-item" href="{{ post.url | prepend: site.baseurl }}">
        <h2>
        {{ post.title }}
        </h2>
        <span class="">{{ post.date | date: "%b %-d, %Y" }}</span>
      </a>
      {% endif %}
  {% endfor %}
</div>
