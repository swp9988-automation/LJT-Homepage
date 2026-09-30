---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## About

I am **Junteng Liu**, a first-year Ph.D. candidate in Computer Science at the **Hong Kong University of Science and Technology (HKUST)**, where I am a member of the **HKUST NLP Group** supervised by **Professor Junxian He**. I received my **B.Eng.** from **Shanghai Jiao Tong University (SJTU)** in June 2024.

My research focuses on **natural language processing** and **machine learning**. My research interests include:

- LLM reasoning and reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness and interpretability

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024 – Present
- **B.Eng.**, Shanghai Jiao Tong University, 2020 – 2024

## Research Experience

- **Research Intern, MINIMAX**, February 2025 – Present
- **Research Intern, Tencent WXG**, June 2024 – September 2024 (advised by Zifei Shan)
- **Research Intern, Shanghai AI Lab**, June 2023 – December 2023 (advised by Prof. Yu Cheng)

## Honors and Awards

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://x.com/junteng88716710)
