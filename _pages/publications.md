---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% if site.author.googlescholar %}
  You can find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% if author.linkedin %}
  You can also find my articles on <u><a href="{{author.linkedin}}">my LinkedIn profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}