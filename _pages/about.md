---
layout: about
title: about
permalink: /
subtitle: Undergraduate student in Computer Science, Fudan University

profile:
  align: right
  image: me.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>stevencaiyiyang at gmail dot com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am an undergraduate student in Computer Science and Technology at Fudan University, expected to graduate in June 2027. I am currently looking for research collaborations and PhD opportunities.

My research interests include **robot learning**, **embodied AI**, **physical agents**, and **world models**. I am broadly interested in building embodied agents that can learn from visual observations, scalable data, and interactive environments.

Research experience:

- Jun 2026 - Present: Research Assistant, Code-as-Policy for LLM-Driven Mobile Manipulation from a Human Demonstration Video, New York University. Advisor: [Prof. Sherry Yang](https://sherryy.github.io/).
- Dec 2025 - May 2026: Research Assistant, Benchmarking Robot Imitative Ability Beyond Action Prediction, TranscEngram. Advisor: [Prof. Yanchao Yang](https://yanchaoyang.github.io/).
- Mar 2025 - Sep 2025: Research Assistant, From VLM to VLA: Scaling Data for Robust Action Learning, The University of Hong Kong. Advisor: [Prof. Tao Yu](https://taoyds.github.io/).
- Jul 2024 - Feb 2025: Research Assistant, Multi-omics Prediction of PD Based on Deep Learning, Fudan University. Advisor: Prof. Shanfeng Zhu.

## Publications

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>
