---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a EDEE PhD student in [EPFL](https://www.epfl.ch/en/) and a research assistant at [VITA](https://www.epfl.ch/labs/vita/).


My research interest revolves around ...


I am open for any types of collaborations :)

# News

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts  limit:3  %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}

### [See more...]({{ site.url }}/updates)
