---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm passionate about AI, with several years of experience in developing cutting-edge AI solutions for leading companies such as Honda and Valeo. My expertise lies in Generative AI (LLMs, VLMs), robustness, and generalization.
I earned my PhD under the supervision of [Alexandre Alahi](https://people.epfl.ch/alexandre.alahi?lang=en) at [EPFL](https://www.epfl.ch/en/) and received my master’s and bachelor’s degrees in Electrical engineering from [Sharif university of technology](https://en.sharif.ir/).

I’ve contributed to several AI projects that involved adapting large language models (LLMs) to NLP-specific tasks and Retrieval-Augmented Generation Systems (RAGs), as well as designing vision-based solutions using foundation models. During my Ph.D. at VITA, EPFL, my work focused on the robustness and explainability of machine learning models in the context of autonomous driving. I developed methodologies using adversarial attacks, synthetic data generation, and parametric perturbations to evaluate and interpret model performance. I also explored knowledge-based AI approaches and formal certification techniques to enhance model reliability. Additionally, during a six-month internship at [Five AI](https://www.five.ai/) (now acquired by Bosch) in Oxford, I worked on counterfactual-based explainable AI methods. 

# News

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts  limit:5  %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}

### [See more...]({{ site.url }}/updates)
