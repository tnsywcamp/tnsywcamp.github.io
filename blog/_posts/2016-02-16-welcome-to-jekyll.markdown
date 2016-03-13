---
layout: post
title:  "Welcome to JekyllOrg"
date:   2016-03-01
---
JekyllOrg is a free Jekyll theme for for small organizations and non-profits.

You can fork the Github repo then configure and update your site with Prose.io.

Your website includes sections for the services you offer, issues you work on, news updates, a press library and a donations feature.

{% for post in site.posts %}
  {% unless forloop.last == true %}
  {{ post.date }}
  {% else %}
  {{ post.title }}
  {% endunless %}
{% endfor %}

[How to set up your website](/setup)
