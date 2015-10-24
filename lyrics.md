---
layout: page
title: Lyrics
permalink: /lyrics/
---

  <ul class="post-list">
    {% for song in site.posts %}
    {% if post.categories contains 'blog1' %}
      <li>
        <span class="post-meta"></span>

        <h2>
          <a class="post-link" href="{{ song.url | prepend: site.baseurl }}">{{ song.title }}</a>
        </h2>
      </li>
    {% endif %}
    {% endfor %}
  </ul>
