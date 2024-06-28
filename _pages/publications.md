---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
<font face="微软雅黑" size=5 color=DarkRed><b>Publications<b></font>
{% if site.author.googlescholar %}
  <div class="wordwrap"><font face="calibri" size=4 color=DarkRed>You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</font></a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
