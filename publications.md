---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for pub in site.data.publications %}
  <div class="pub-item">
    <p>{{ pub.html | markdownify }}</p>
  </div>
{% endfor %}

