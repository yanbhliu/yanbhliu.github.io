---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Guest Lecture
------
{% for post in site.teaching reversed %}
  {% if post.status == "guestlecture" %}
    {% include teaching-single.html %}
  {% endif %}
{% endfor %}

Teaching Assistant
------
{% for post in site.teaching reversed %}
  {% if post.status == "teachingassistant" %}
    {% include teaching-single.html %}
  {% endif %}
{% endfor %}