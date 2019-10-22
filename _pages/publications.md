---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.ca/citations?hl=en&view_op=list_works&authuser=1&gmla=AJsN-F7k7mZDjCkhCHLSwB3DKAICq2b4IzVsP4WJ7ApndhtmCsNwIyKUtRfDfcDItGaXl9j7jgHYCGeXzMpH36224bkgZgA5TBsk5rbebmPVJ24MpNhUE0A&user=mQZqPVAAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
