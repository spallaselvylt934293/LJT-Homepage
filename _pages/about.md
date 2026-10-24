---
permalink: /
title: "Junteng Liu"
description: "First-year PhD candidate at HKUST NLP Group. Research focuses on natural language processing and machine learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me

I am a first-year PhD candidate in the HKUST NLP Group at the Hong Kong University of Science and Technology, supervised by Professor Junxian He, who leads the group. My research focuses on natural language processing and machine learning.

I graduated from Shanghai Jiao Tong University (SJTU) in June 2024. Professor Junxian He also advised me during my undergraduate studies at SJTU.

## Education

- **Ph.D. in Computer Science (2024–Present)** — Hong Kong University of Science and Technology.
- **B.Eng. (2020–2024)** — Shanghai Jiao Tong University; graduated in June 2024.

## Skills and Research Interests

My research combines natural language processing and machine learning. My interests include:

- LLM reasoning and reinforcement learning.
- Hallucination in vision-language models (VLM).
- LLM truthfulness and interpretability.

## Research Experience

- **Research Intern, MINIMAX** — February 2025–Present.
- **Research Intern, Tencent WXG** — June 2024–September 2024. Advisor: Zifei Shan.
- **Research Intern, Shanghai AI Lab** — June 2023–December 2023. Advisor: Prof. Yu Cheng.

## Honors

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University.

## Publications

The same publications recorded on the [Publications page]({{ '/publications/' | relative_url }}) are listed here, with author lists and publication venues.

{% assign sorted_publications = site.publications | sort: "order" %}
{% for post in sorted_publications %}
{% include archive-single.html %}
{% endfor %}

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Publication profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
