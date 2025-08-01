---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all main sections on this site. For robots, an [XML version]({{ base_path }}/sitemap.xml) is available.

{% assign nav = site.data.navigation %}

<ul>
{% for item in nav %}
  {% if item.url %}
    <li>
      <a href="{{ item.url | relative_url }}">{{ item.title }}</a>
      {% if item.children %}
        <ul>
        {% for child in item.children %}
          <li>
            <a href="{{ child.url | relative_url }}">{{ child.title }}</a>
          </li>
        {% endfor %}
        </ul>
      {% endif %}
    </li>
  {% endif %}
{% endfor %}
</ul>
