---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science** | Hong Kong University of Science and Technology | September 2024 - Present | Supervised by Professor Junxian He
- **B.Eng. in Computer Science and Engineering** | Shanghai Jiao Tong University | September 2020 - June 2024

## Work Experience

- **Research Intern, MINIMAX** | February 2025 - Present | Working on large language model (LLM) alignment and safety, including pre-training and instruction tuning.
- **Research Intern, Tencent WXG** | June 2024 - September 2024 | Large-scale pre-training and model compression.
- **Research Intern, Shanghai AI Lab** | June 2023 - December 2023 | Multi-modal understanding and large-scale model training.

## Skills

- **Python** (expert)
- **PyTorch** (expert)
- **TensorFlow** (advanced)
- **Java** (intermediate)
- **C/C++** (intermediate)

## Publications

  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>

## Talks

  <ul>
    {% for post in site.talks reversed %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}
  </ul>

## Teaching

  <ul>
    {% for post in site.teaching reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>

## Service and Leadership

