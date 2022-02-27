---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Page WIP.

You can also find my past articles on <u><a href="{{site.author.googlescholar}}">Google Scholar</a>.</u>


{% comment %}
{% include base_path %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
{% endcomment %}
