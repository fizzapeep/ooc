---
title: Home
layout: default
---

# Welcome to OOC Translations

soz for the janky site, will code improvements as i go:

<ul>
<li>fix last updated column</li>
<li>dark mode</li>
<li>hover over footnotes on desktop</li>
</ul>

## Novels List

<ul>
  {% for chapter in site.chapters %}
    {% if chapter.path contains "toc.md" %}
    <li>
      <a href="{{ site.baseurl }}{{ chapter.url }}">{{ chapter.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
