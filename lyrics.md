---
layout: page
title: Lyrics
permalink: /lyrics/
---

  <ul class="post-list">
    {% for song in site.lyrics %}
      <li>
        <span class="post-meta"></span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
