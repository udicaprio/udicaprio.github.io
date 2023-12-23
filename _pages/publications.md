---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


{% include base_path %}

<h2><i>Journal papers</i></h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == "journal" %}
    {% include archive-single-publications.html %}
  {% endif %}
{% endfor %}

<h2><i>Conference proceedings</i></h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == "proceeding" %}
    {% include archive-single-publications.html %}
  {% endif %}
{% endfor %}