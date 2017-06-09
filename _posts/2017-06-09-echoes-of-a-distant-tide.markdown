---
title: "Echoes of a distant tide"
date: 2017-06-09 10:14:00
categories: works
---

<iframe src="https://player.vimeo.com/video/211004571" style="width: 100%; height:360px" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<div id="galleria">
{% for i in (1..3) %}
    <a href="{{ site.baseurl }}/images/default/echo{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/echo{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/echo{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>
