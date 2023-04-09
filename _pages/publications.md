---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprint
--------
* Prompt Based Few-Shot Learning for Biomedical Relation Extraction: An Initial Investigation of ChatGPT and large language models. Huixue Zhou, Xueqing Peng, Raja, Kalpana, Hua Xu, Rui Zhang
* Complementary and Integrative Health Lexicon (CIHLex) and Entity Recognition in the Literature.Huixue Zhou, Robin Austin, Greg Silverman, Yuqi Zhou, Halil Kilicoglu, Sheng-Chieh Lu, Rui Zhang

Conference/Journal Papers
--------
* H. Zhou et al., "Annotating Music Therapy, Chiropractic and Aquatic Exercise Using Electronic Health Record," 2022 IEEE 10th International Conference on Healthcare Informatics (ICHI), Rochester, MN, USA, 2022, pp. 610-611, doi: 10.1109/ICHI54592.2022.00121.
* hou H, Austin R, Kilicoglu H, Lu S, Zhang R. Complementary and Integrative Health Lexicon (CIHLex). AMIA annual symposium proceedings 2022. Z



