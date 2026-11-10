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

{% assign pubs = site.publications | sort: "date" | reverse %}

# Conference Papers

{% for post in pubs %}{% if post.pubtype == "conference" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

# Journal Papers

{% for post in pubs %}{% if post.pubtype == "journal" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

# Workshop Papers

{% for post in pubs %}{% if post.pubtype == "workshop" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

# Preprints

{% for post in pubs %}{% if post.pubtype == "preprint" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

# Thesis & Patents

{% for post in pubs %}{% if post.pubtype == "thesis" or post.pubtype == "patent" %}
  {% include archive-single.html %}
{% endif %}{% endfor %}

(<i>*</i>: Indicates equal contribution)<br/>
