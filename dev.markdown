---
layout: page
title: Dev
permalink: /dev/
---

## Development Posts

<div class="dev-posts">
  {% if site.posts.size > 0 %}
    <ul class="post-list">
      {% for post in site.posts %}
        {% if post.categories contains "dev" %}
          <li>
            {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
            <span class="post-meta">{{ post.date | date: date_format }}</span>
            <h3>
              <a class="post-link" href="{{ post.url | relative_url }}">
                {{ post.title | escape }}
              </a>
            </h3>
            {% if post.description %}
              <p>{{ post.description }}</p>
            {% else %}
              <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
            {% endif %}
          </li>
        {% endif %}
      {% endfor %}
    </ul>
  {% endif %}
</div>

