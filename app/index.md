---
title: Home
layout: page
---

{% assign header = "header/_index.html" %}
{% assign banner = "banner/_index.html" %}
{% assign features = "features/_index.html" %}
{% assign posts = "posts/_index.html" %}

{% include {{ header }} %}
{% include {{ banner }} %}
{% include {{ features }} %}
{% include {{ posts }} %}