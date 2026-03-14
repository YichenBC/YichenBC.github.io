---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently working at [LiblibAI](https://www.liblib.art/) on AI agents.
Previously, I worked at Ant Group on GUI agents.
I received my Ph.D. from the Department of Computer Science and Technology, Tsinghua University (THU) in June 2025.

My research interests lie in LLM-based agents, post-training of Large Language Models (LLMs), and content security of (Multimodal)LLMs.
During my Ph.D., I conducted extensive research on the vulnerabilities of the safety alignment, and intellectual property protection in LLMs. Currently, I focus on building practical AI agent systems.

Email: [gongyc18@gmail.com](mailto:gongyc18@gmail.com)

 <a href='https://scholar.google.com/citations?user=bdw6PVkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/6uivenus1d5.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UI-Venus-1.5 Technical Report](https://arxiv.org/abs/2602.09082)

Changlong Gao, Zhangxuan Gu, Yulin Liu, ..., **Yichen Gong**, ..., Weiqiang Wang

[**GitHub**](https://github.com/inclusionAI/UI-Venus/tree/UI-Venus-1.5) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:UeHWp8X0CEIC'></span></strong>
- UI-Venus-1.5 is the next-generation GUI agent built at Ant Group, advancing the UI-Venus series with improved multi-turn interaction and cross-platform generalization capabilities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/5uivenus.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UI-Venus Technical Report: Building High-Performance UI Agents with RFT](https://arxiv.org/abs/2508.10833)

Zhangxuan Gu, Zhengwen Zeng, ..., **Yichen Gong**, ..., Weiqiang Wang

[**GitHub**](https://github.com/inclusionAI/UI-Venus/tree/UI-Venus-1.5) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:qjMakFHDy7sC'></span></strong>
- UI-Venus is a screenshot-based UI agent built on Qwen2.5-VL and fine-tuned via reinforcement fine-tuning (RFT), achieving state-of-the-art performance on UI grounding and navigation benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 (Oral)</div><img src='images/1figstep.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Figstep: Jailbreaking large vision-language models via typographic visual prompts](https://arxiv.org/pdf/2311.05608)

**Yichen Gong**, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:u5HHmVD_uO8C'></span></strong>
- This work exposes safety vulnerabilities in Large Vision-Language Models (LVLMs) and proposes FigStep, a black-box jailbreak algorithm that converts harmful text into visual modality to bypass safe guardrail, achieving an 82.50\% attack success rate. Our analysis highlights deficiencies in visual embedding safety alignment and underscores the need for robust cross-modality safety solutions. Our findings underscore the urgent need for robust cross-modality safety alignment techniques to secure LVLMs against such attacks.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2025</div><img src='images/2msialignment.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Safety Misalignment against Large Language Models]()

**Yichen Gong**, Delong Ran, Xinlei He, Tianshuo Cong, Anyu Wang, and Xiaoyun Wang

- This work introduces a framework to evaluate various safety misalignment attacks against LLMs, revealing vulnerabilities to attacks like supervised fine-tuning and our novel SSRA. We propose SSRD to effectively re-align models, preserving safety after fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/3jailbreakeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JailbreakEval: An Integrated Toolkit for Evaluating Jailbreak Attempts Against Large Language Models](https://arxiv.org/pdf/2406.09321)

Delong Ran, Jinyuan Liu, **Yichen Gong**, Jingyi Zheng, Xinlei He, Tianshuo Cong, Anyu Wang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:d1gkVwhDpl0C'></span></strong>

- This work analyzes jailbreak evaluation methods for LLMs. We propose a taxonomy of jailbreak evaluators and introduce JailbreakEval, a toolkit to streamline and standardize jailbreak evaluation, advancing the efficiency and fairness of evaluation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2024 LAMPS Workshop (Best Paper)</div><img src='images/4merge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Have You Merged My Model? On The Robustness of Large Language Model IP Protection Methods Against Model Merging]([https://arxiv.org/pdf/2406.09321](https://dl.acm.org/doi/pdf/10.1145/3689217.3690614))

Tianshuo Cong, Delong Ran, Zesen Liu, Xinlei He, Jinyuan Liu, **Yichen Gong**, Qi Li, Anyu Wang, Xiaoyun Wang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:u-x6o8ySG0sC'></span></strong>

- This work studies the robustness of IP protection techniques for Large Language Models (LLMs) under model merging.
While watermark fails in merged models, fingerprint remains effective, highlighting the need to address IP protection in model merging scenarios.
</div>
</div>

# 🎖 Honors and Awards
- NDSS Fellowship, awarded by Internet Society, Spring 2025
- China Software Cup, Grand Prize, awarded by Ministry of Industry and Information Technology (China), Fall 2017
- Science and Technology Competition Scholarship (First-Class), awarded by Beihang University, Winter 2017
- Beihang Star of Innovation: Annual Student Innovator of the Year, awarded by Beihang University, Winter 2017
- MIIT Innovation Scholarship (Third-Class), awarded by Ministry of Industry and Information Technology (China), Spring 2018

# 💼 Work Experience
- *2026.03 - Present*, AI Agent Engineer, [LiblibAI](https://www.liblib.art/)
- *2025.07 - 2026.03*, GUI Agent Engineer, Ant Group

# 📖 Educations
- *2018.09 - 2025.06*, Ph.D. in Computer Science and Technology, Tsinghua University (THU)
- *2014.09 - 2018.06*, B.E. in Software Engineering, Beihang University
