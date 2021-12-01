---
layout: archive
title: "Works"
permalink: /works/
author_profile: true
---
## " Real Exchange Rate with Inflation Targeting in Chile an USA"
--- 
This work tries to explain the behavior of the exchange rate in Chile, making a comparison with the exchange rate in the United States.

[codes here](https://github.com/GonzaloQuiroz/Works)

---
## " Replicate paper “Ex-Post Assessment of Heterogeneous Effects of Free Trade Agreements: The Case of Turkey.” "

--- 

In this work, we replicate the “Ex-Post Assessment of Heterogeneous Effects of Free Trade Agreements: The Case of Turkey.” using South Africa as the main country.

[codes here](https://github.com/GonzaloQuiroz/Turkey-work)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
