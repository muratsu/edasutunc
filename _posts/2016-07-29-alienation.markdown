---
title: Alienation
date: 2016-07-29 13:21:00
categories: installation
---

<div id="galleria">
{% for i in (1..7) %}
    <a href="{{ site.baseurl }}/images/default/alienation{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/alienation{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/alienation{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>
