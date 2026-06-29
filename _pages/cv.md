---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024&ndash;Present
* B.Eng., Shanghai Jiao Tong University, 2020&ndash;2024

Work experience
======
* Research Intern, MiniMax, February 2025&ndash;Present
* Research Intern, Tencent WXG, June 2024&ndash;September 2024
* Research Intern, Shanghai AI Lab, June 2023&ndash;December 2023

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models
* LLM Truthfulness and Interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
