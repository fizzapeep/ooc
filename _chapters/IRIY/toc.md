---
title: IRIY
layout: toc
permalink: /novels/IRIY/toc/
---

# I Returned to the Immortal's Youth

[Novel Updates Page](https://www.novelupdates.com/series/i-returned-to-the-immortals-youth/)

# TOC:

<ul>
    <li>
      <a href="https://banoffeetranslations.blogspot.com/2023/10/i-returned-to-immortals-youth-table-of.html">Chapters 1-25</a> by cela's translation
    </li>
{% for chapter in site.chapters %}
    {% if chapter.path contains "IRIY/" %}
    {% unless chapter.path contains "toc" %}
    <li>
      <a href="{{ site.baseurl }}{{ chapter.url }}">{{ chapter.title }}</a>
    </li>
    {% endunless %}
    {% endif %}
{% endfor %}
</ul>
