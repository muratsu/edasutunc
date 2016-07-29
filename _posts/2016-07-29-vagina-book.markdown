---
title: Vagina Book
date: 2016-07-29 13:21:00
categories: installation
---

<div id="galleria">
{% for i in (1..5) %}
    <a href="{{ site.baseurl }}/images/default/vag{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/vag{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/vag{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>

