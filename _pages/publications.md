---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
<font size=5 color=DarkRed><b>Publications</b></font>

<font size=4 color=Gray></font>
{% if site.author.googlescholar %}
<!--  <div class="wordwrap"><font size=4 color=Gray>You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.--> 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
