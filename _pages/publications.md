---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

# Conference Papers

{% include base_path %}

{% for post in site.publications reversed %}
  {% unless post.venue contains "Workshop" or post.venue == "Preprint" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

(<i>*</i>: Indicates equal contribution)<br/>

# Workshop Papers

{% for post in site.publications reversed %}
  {% if post.venue contains "Workshop" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

# Preprints

{% for post in site.publications reversed %}
  {% if post.venue == "Preprint" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
