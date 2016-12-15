---
layout: null
title: read data
permalink: /data.html
---
<div class="text-center">
{"test":[
{% for d in site.data.1k %}
  {% include data %}
{% endfor %}
]}
</div>
