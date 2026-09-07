---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Junteng Liu**, a first-year PhD candidate in Computer Science at the Hong Kong University of Science and Technology (HKUST), where I am a member of the [HKUST NLP Group](https://nlp.ust.hk) and am supervised by Professor Junxian He. I received my B.Eng. from Shanghai Jiao Tong University (SJTU) in June 2024. My research lies at the intersection of natural language processing and machine learning. A full list of my publications is also available on my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

Research interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024 - Present
  * HKUST NLP Group, supervised by Professor Junxian He
* **B.Eng.**, Shanghai Jiao Tong University, 2020 - 2024

Research experience
======
* **Research Intern**, MINIMAX, February 2025 - Present
* **Research Intern**, Tencent WXG, June 2024 - September 2024
  * Advisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab, June 2023 - December 2023
  * Advisor: Prof. Yu Cheng

Honors
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Publications
======
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% endif %}

Skills
======
* Natural Language Processing, Machine Learning, Deep Learning
* Programming: Python, PyTorch
* Research tools: Git, Jupyter, LaTeX

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
