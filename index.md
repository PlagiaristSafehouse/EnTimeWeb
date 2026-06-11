---
layout: page
title: EnTimeCode for iOS
---

EnTimeCode converts video with embedded LTC audio into video files with timecode metadata.

## Latest updates

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No posts yet.</p>
{% endif %}
