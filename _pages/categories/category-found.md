---
title: "Post about Found"
layout: archive
permalink: /categories/found
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.found | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
