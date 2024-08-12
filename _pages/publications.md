---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <p style="font-size: smaller">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar</a>.<br  /><br /></p>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
