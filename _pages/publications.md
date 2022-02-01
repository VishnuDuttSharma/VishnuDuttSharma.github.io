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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Preprints
## **[Risk-Aware Path Planning for Ground Vehicles using Occluded Aerial Images](https://arxiv.org/pdf/2104.11709.pdf)**<br/>
<b>Vishnu Dutt Sharma</b>, Pratap Tokekar (2021)<br/><br/>
Download [here](https://arxiv.org/pdf/2104.11709.pdf)

## **[Graph Neural Networks for Decentralized Multi-Robot Submodular Action Selection](https://arxiv.org/pdf/2105.08601.pdf)**<br/>
Lifeng Zhou, <b>Vishnu Dutt Sharma</b>, Qingbiao Li, Amanda Prorok, Alejandro Ribeiro, Vijay Kumar (2021)<br/><br/>
Download [here](https://arxiv.org/pdf/2105.08601.pdf)
