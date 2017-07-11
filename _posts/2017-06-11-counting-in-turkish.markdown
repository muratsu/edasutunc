---
title: Counting in Turkish
date: 2017-06-11 10:14:00
categories: works
---

<div id="galleria">
{% for i in (1..3) %}
    <a href="{{ site.baseurl }}/images/default/counting{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/counting{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/counting{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>