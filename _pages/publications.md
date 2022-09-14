---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Below is a set of selected preprints and publications. Please see [my Google Scholar page](https://scholar.google.com/citations?user=GVHMq88AAAAJ&hl=en) for a full list.

\* denotes co-first authorship, and <u>underlines</u> denote corresponding authors.

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

