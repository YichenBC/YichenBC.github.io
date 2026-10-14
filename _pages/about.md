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

I am Yichen Gong (巩毅琛). I received my Ph.D. in Computer Science and Technology from Tsinghua University in June 2025, where I studied LLM safety and alignment in Xiaoyun Wang's research group.

After my Ph.D., I explored agent safety, but found that agents still struggled to complete many tasks. This led me to agent training. I now work on **multimodal agent post-training** and **video world models**, while continuing research on model safety and alignment.

My recent work covers GUI agents, visual instruction following for image editing, capability transfer after post-training, and long video generation.

[Google Scholar](https://scholar.google.com/citations?user=bdw6PVkAAAAJ) · [GitHub](https://github.com/YichenBC) · [Email](mailto:gongyc18@gmail.com)

 <a href='https://scholar.google.com/citations?user=bdw6PVkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


<span class='anchor' id='news'></span>

# 📰 News

- **October 2026:** Released [Commit Forcing](https://github.com/Dwell-Jing/commit-forcing) for long video generation.
- **September 2026:** Our [ATD paper](https://arxiv.org/abs/2609.29233) studies how post-training capabilities can transfer through responses to unrelated prompts.
- **2026:** Released [VPEBench](https://github.com/Dwell-Jing/vpebench) for visual instruction following in image editing.
- **2026:** [VenusBench-Mobile](https://arxiv.org/abs/2604.06182) was accepted to **ICML 2026 as an Oral**.

<span class='anchor' id='publications'></span>

# 📝 Publications

<div class='paper-box'><div markdown="1">

### [Post-Training Leaves Behavioral Shadows on Unrelated Decisions](https://arxiv.org/abs/2609.29233)

Ziyang Zhang, Yubin Jing, Yuanhao Zeng, Yuyao Li, Haofan Wang, **Yichen Gong**

*arXiv 2026 · Corresponding author*

Active Taskless Distillation (ATD) transfers post-training capabilities between models with a shared ancestor using one-word teacher responses to task-unrelated prompts.

</div></div>

<div class='paper-box'><div markdown="1">

### [VPEBench: The Image Plane Is an Instruction Surface for Image Editing](https://github.com/Dwell-Jing/vpebench/blob/main/paper/VPEBench.pdf)

Yubin Jing, Ziyang Zhang, Yuyao Li, Tianyu Lao, Zhaohui Xiong, Haofan Wang, **Yichen Gong**

*2026 · Corresponding author* · [**GitHub**](https://github.com/Dwell-Jing/vpebench) · [**Dataset**](https://huggingface.co/datasets/Whalesjyb/VPEBench)

Can image-editing models follow instructions drawn as boxes, arrows, and curves? VPEBench diagnoses where edits land, whether they follow the instruction, and whether models preserve the image and remove the marks. It also includes MarkCheck, a verification and repair harness.

</div></div>

<div class='paper-box'><div markdown="1">

### [VenusBench-Mobile: A Challenging and User-Centric Benchmark for Mobile GUI Agents with Capability Diagnostics](https://arxiv.org/abs/2604.06182)

**Yichen Gong**, Zhuohan Cai, Sunhao Dai, Yuqi Zhou, Zhangxuan Gu, Changhua Meng, Shuheng Shen

***ICML 2026 (Oral)*** · *First and corresponding author*

A benchmark of challenging mobile GUI tasks, with capability diagnostics to study where agents fail and how memory, reflection, and self-evolution affect task completion.

</div></div>

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

[FigStep: Jailbreaking Large Vision-Language Models via Typographic Visual Prompts](https://arxiv.org/pdf/2311.05608)

**Yichen Gong**, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang

[**Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:u5HHmVD_uO8C'></span></strong>
- FigStep converts harmful text into typographic visual prompts to study how visual inputs can bypass the safety alignment of large vision-language models. The results expose gaps between text and visual safety alignment.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2025</div><img src='images/2msialignment.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Safety Misalignment Against Large Language Models](https://www.ndss-symposium.org/wp-content/uploads/2025-1089-paper.pdf)

**Yichen Gong**, Delong Ran, Xinlei He, Tianshuo Cong, Anyu Wang, and Xiaoyun Wang

- This work introduces a framework to evaluate various safety misalignment attacks against LLMs, revealing vulnerabilities to attacks like supervised fine-tuning and our novel SSRA. We propose SSRD to effectively re-align models, preserving safety after fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/3jailbreakeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JailbreakEval: An Integrated Toolkit for Evaluating Jailbreak Attempts Against Large Language Models](https://arxiv.org/pdf/2406.09321)

Delong Ran, Jinyuan Liu, **Yichen Gong**, Jingyi Zheng, Xinlei He, Tianshuo Cong, Anyu Wang

[**Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:d1gkVwhDpl0C'></span></strong>

- This work analyzes jailbreak evaluation methods for LLMs. We propose a taxonomy of jailbreak evaluators and introduce JailbreakEval, a toolkit to streamline and standardize jailbreak evaluation, advancing the efficiency and fairness of evaluation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2024 LAMPS Workshop (Best Paper)</div><img src='images/4merge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Have You Merged My Model? On the Robustness of Large Language Model IP Protection Methods Against Model Merging](https://arxiv.org/abs/2404.05188)

Tianshuo Cong, Delong Ran, Zesen Liu, Xinlei He, Jinyuan Liu, **Yichen Gong**, Qi Li, Anyu Wang, Xiaoyun Wang

[**Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=bdw6PVkAAAAJ&citation_for_view=bdw6PVkAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='bdw6PVkAAAAJ:u-x6o8ySG0sC'></span></strong>

- This work studies the robustness of IP protection techniques for Large Language Models (LLMs) under model merging.
While watermark fails in merged models, fingerprint remains effective, highlighting the need to address IP protection in model merging scenarios.
</div>
</div>

<span class='anchor' id='projects'></span>

# 🛠 Research Projects

### [Commit Forcing](https://github.com/Dwell-Jing/commit-forcing)

**What Helps Denoising Can Hurt Memory: Rethinking History in Long Video Generation**

A training-free method for updating the KV cache in long video generation. It separates the history used during denoising from the history used to construct clean KV, improving long-range consistency without additional model forwards. Code, evaluations, and qualitative comparisons are available in the repository.

<span class='anchor' id='honors'></span>

# 🎖 Honors and Awards
- ICML 2026 Oral, VenusBench-Mobile
- AAAI 2025 Oral, FigStep
- NDSS 2025 Best Technical Poster, JailbreakEval
- CCS LAMPS 2024 Best Paper, Have You Merged My Model?
- NDSS Fellowship, awarded by Internet Society, Spring 2025
- China Software Cup, Grand Prize, awarded by Ministry of Industry and Information Technology (China), Fall 2017
- Science and Technology Competition Scholarship (First-Class), awarded by Beihang University, Winter 2017
- Beihang Star of Innovation: Annual Student Innovator of the Year, awarded by Beihang University, Winter 2017
- MIIT Innovation Scholarship (Third-Class), awarded by Ministry of Industry and Information Technology (China), Spring 2018

<span class='anchor' id='experience'></span>

# 💼 Work Experience
- *2026.03 – Present*, Algorithm Engineer — multimodal agent post-training and video world models
- *2025.06 – 2026.03*, GUI Agent Engineer — joint research with the InclusionAI Venus Team, Ant Group; contributed to UI-Venus and UI-Venus-1.5

<span class='anchor' id='education'></span>

# 📖 Education
- *2018.09 – 2025.06*, Ph.D. in Computer Science and Technology, Tsinghua University. Research in Xiaoyun Wang's group. [Doctoral thesis](https://newetds.lib.tsinghua.edu.cn/qh/paper/summary?dbCode=ETDQH&sysId=304523): 面向大语言模型安全对齐的鲁棒性分析研究.
- *2014.09 – 2018.06*, B.E. in Software Engineering, Beihang University
