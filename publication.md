---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for pub in site.data.publications %}
  <div class="pub-item">
    <p>
      <strong>{{ pub.title }}</strong><br>
      {{ pub.authors }}<br>
      <em>{{ pub.venue }}</em>, {{ pub.year }}<br>
      {% if pub.paperurl %}
        <a href="{{ pub.paperurl }}">[PDF]</a>
      {% endif %}
      {% if pub.slidesurl %}
        <a href="{{ pub.slidesurl }}">[Slides]</a>
      {% endif %}
    </p>
  </div>
{% endfor %}
