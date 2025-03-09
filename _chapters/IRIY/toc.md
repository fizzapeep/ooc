---
title: IRIY
layout: toc
permalink: /novels/IRIY/toc/
last_modified_at: "2025-03-09 00:04:57 -0800"
---
# I Returned to the Immortal's Youth

[Novel Updates Page](https://www.novelupdates.com/series/i-returned-to-the-immortals-youth/)

{% assign total_word_count = 0 %}
    {% for chapter in site.chapters %}
        {% if chapter.path contains "IRIY/" %}
        {% unless chapter.path contains "toc" %}
            {% assign word_count = chapter.content | number_of_words %}
            {% assign total_word_count = total_word_count | plus: word_count %}
        {% endunless %}
    {% endif %}
{% endfor %}

Total Word Count: {{ total_word_count }}

# TOC

<table>
  <thead>
    <tr>
      <th>Chapter</th>
      <th>Word Count</th>
      <th>Last Updated</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="3">
        <a href="https://banoffeetranslations.blogspot.com/2023/10/i-returned-to-the-immortals-youth-table-of.html">Chapters 1-25</a> by cela's translations
      </td>
    </tr>
    {% for chapter in site.chapters %}
    {% if chapter.path contains "IRIY/" %}
    {% unless chapter.path contains "toc" %}
    <tr>
      <td><a href="{{ site.baseurl }}{{ chapter.url }}">{{ chapter.title }}</a></td>
      <td>{{ chapter.content | number_of_words }}</td>
      <td>{{ chapter.last_modified_at | date: "%B %d, %Y" }}</td>
    </tr>
    {% endunless %}
    {% endif %}
    {% endfor %}
  </tbody>
</table>
