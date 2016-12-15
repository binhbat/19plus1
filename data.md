---
layout: null
title: read data
permalink: /data.html
---
<div class="text-center">
{"0k":[
{% for d in site.data.0k %}
  {% include data %}
{% endfor %}
]}
</div>
