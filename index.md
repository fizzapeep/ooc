---
title: Home
layout: default
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-MGR2S8P4HV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-MGR2S8P4HV');
</script>

# Welcome to OOC Translations

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
