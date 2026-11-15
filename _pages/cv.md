---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Junteng Liu

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
  - HKUST NLP Group
  - Supervisor: Professor Junxian He
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024; graduated June 2024
  - Previously advised by Professor Junxian He during undergraduate studies at SJTU

## Research Experience

- **Research Intern**, MINIMAX, February 2025–Present
- **Research Intern**, Tencent WXG, June 2024–September 2024
  - Advisor: Zifei Shan
- **Research Intern**, Shanghai AI Lab, June 2023–December 2023
  - Advisor: Prof. Yu Cheng
- **Ph.D. Research**, HKUST NLP Group, 2024–Present
  - Supervisor: Professor Junxian He

## Skills & Research Interests

- Natural language processing
- Machine learning
- LLM reasoning and reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness and interpretability

## Honors and Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Publications

{% assign publication_ids = "synlogic|chart-understanding|truthfulness-hyperplane|in-context-sharpness|c-eval|composing-parameter-efficient-modules" | split: "|" %}
<ul>
  {% for publication_id in publication_ids %}
    {% assign post = site.publications | where: "pub_id", publication_id | first %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
