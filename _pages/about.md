---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm an EDEE PhD student in [EPFL](https://www.epfl.ch/en/) and a research assistant at [VITA](https://www.epfl.ch/labs/vita/) under supervision of [Alexandre Alahi](https://people.epfl.ch/alexandre.alahi?lang=en). I recieved my master's degree in Electrical engineering from [Sharif university of technology](https://en.sharif.edu/). 


My research interest revolves around generalizable neural networks where we tackle the problem through causal learning, knowledge-driven networks, and adversarial attack. I pursue these topics in the application of vehicle behavior prediction for self-driving cars. 


I am open for any types of collaborations. Fell free to drop me a massage :)

# News

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts  limit:3  %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}

### [See more...]({{ site.url }}/updates)
