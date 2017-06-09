---
title: Turkey is my country
date: 2017-06-08 10:14:00
categories: works
---

<iframe src="https://player.vimeo.com/video/201065693" style="width: 100%; height:334px" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<div id="galleria">
{% for i in (1..3) %}
    <a href="{{ site.baseurl }}/images/default/turkey{{ i }}.jpg">
      <img
        src="{{ site.baseurl }}/images/thumbnail/turkey{{ i }}.jpg"
        data-big="{{ site.baseurl }}/images/raw/turkey{{ i }}.jpg"
      >
    </a>
{% endfor %}
</div>