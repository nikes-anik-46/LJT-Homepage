---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Junteng Liu**, a first-year Ph.D. candidate at the **HKUST NLP Group**, where I am supervised by **Prof. Junxian He**. My research focuses on **natural language processing** and **machine learning**. I completed my **B.Eng.** at **Shanghai Jiao Tong University** (2020 -- 2024) and graduated in June 2024. Prof. Junxian He also advised me during my undergraduate studies at SJTU.

Research interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM truthfulness and Interpretability

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024 -- Present
  * First-year Ph.D. candidate in the HKUST NLP Group, which is led by Prof. Junxian He
* **B.Eng.**, Shanghai Jiao Tong University, 2020 -- 2024
  * Graduated in June 2024

Research experience
======
* **Research Intern, MINIMAX** -- February 2025 to Present
* **Research Intern, Tencent WXG** -- June 2024 to September 2024
  * Advised by Zifei Shan
* **Research Intern, Shanghai AI Lab** -- June 2023 to December 2023
  * Advised by Prof. Yu Cheng

Skills
======
* Natural Language Processing -- primary research area
* Machine Learning -- primary research area
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Honors and awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Publications
======
The full list of my publications is given below. The same list is also available on the [Publications]({{ site.baseurl }}/publications/) page and on my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

<!-- Rendered from the _publications collection, so both this page and the /publications/ page always show the same records -->
{% for category in site.publication_category %}
  {% assign title_shown = false %}
  {% for post in site.publications reversed %}
    {% if post.category != category[0] %}
      {% continue %}
    {% endif %}
    {% unless title_shown %}
      <h2>{{ category[1].title }}</h2><hr />
      {% assign title_shown = true %}
    {% endunless %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
