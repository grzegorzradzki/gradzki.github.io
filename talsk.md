---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

{% include base_path %}

<ol class="talks-list" reversed>
  {% assign sorted_talks = site.data.talks | sort: "date" | reverse %}
  {% for talk in sorted_talks %}
    <li class="talks-item">
      {{ talk.html | markdownify }}
    </li>
  {% endfor %}
</ol>
