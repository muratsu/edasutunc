---
title: Shades of a Petite Turkish Artist
date: 2017-06-10 10:14:00
categories: works
---

<div id="galleria">
{% for i in (1..3) %}
    <a href="{{ site.baseurl }}/images/default/shades{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/shades{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/shades{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>