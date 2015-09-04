---
layout: page
title: Lyrics
permalink: /lyrics/
---

  <ul class="post-list">
    {% for song in site.posts %}
      <li>
        <span class="post-meta"></span>

        <h2>
          <a class="post-link" href="{{ song.url | prepend: site.baseurl }}">{{ song.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
