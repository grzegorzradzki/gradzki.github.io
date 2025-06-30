---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<ol class="pub-list" reversed>
  {% assign sorted_pubs = site.data.publications | sort: "date" | reverse %}
  {% for pub in sorted_pubs %}
    <li class="pub-item">
      {{ pub.html | markdownify }}
    </li>
  {% endfor %}
</ol>

