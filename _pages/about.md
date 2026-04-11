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

Hi! I am a Ph.D. student in Computer Science at Texas A&M University, advised by [Dr. Shuiwang Ji](https://people.tamu.edu/~sji/); actively collaborate with [Dr. Dileep Kalathil](https://people.it.tamu.edu/~dileep.kalathil/) and [Dr. James Caverlee](https://caverlee.github.io/). My research focuses on **post-training of Large Language Models (LLMs) and Diffusion Language Models (DLMs)**. 

More specifically, I develop curriculum-based reinforcement learning approaches that train models at the frontier of their learnability, continuously expanding what they can reason about and yielding progressively stronger models. I have published multiple papers as (co-)first author in top-tier venues including **ICLR**, **CVPR**, and **EMNLP**.

During my **M.S.** at Texas A&M, advised by [Dr. Shu Kong](https://aimerykong.github.io/) and [Dr. James Caverlee](https://caverlee.github.io/), I focused on identifying and mitigating biases in **Vision-Language Models (VLMs)** to improve their robustness and fairness, especially for use in multimodal chatbots and diffusion models. Prior to that, I completed my undergraduate degree in Computer Science and Engineering at the **Vellore Institute of Technology, Chennai**.
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.03*: I have been awarded the ICLR 2026 Financial Assistance grant to attend the conference in Rio!
- *2026.01*: Our paper, "Curriculum Reinforcement Learning from Easy to Hard Tasks Improves LLM Reasoning" was accepted at ICLR 2026!
- *2025.05*: I will be interning as an Applied Scientist at Amazon (Santa Clara, CA) this summer.
- *2025.02*: Our paper, "Few-Shot Recognition via Stage-Wise Retrieval-Augmented Finetuning" was accepted at CVPR 2025!
- *2024.06*: Our paper, "The Neglected Tails of Vision-Language Models" was accepted to DMLR as <span style="color:green">**ORAL**</span>. 
- *2024.06*: I have begun my Ph.D. at Texas A&M under the supervision of Dr. Shuiwang Ji. 
- *2024.02*: Our paper, "The Neglected Tails of Vision-Language Models" has been accepted at CVPR 2024! 
- *2023.12*: I will be presenting our paper, "Prompting Scientific Names for Zero-Shot Species Recognition" at EMNLP 2023. 
- *2022.02*: I was awarded the Texas A&M Computer Science departmental scholarship. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/teaser-e2h.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Curriculum Reinforcement Learning from Easy to Hard Tasks Improves LLM Reasoning](https://openreview.net/pdf?id=KJvHnl3kUv)

**Shubham Parashar**, Shurui Gui, Xiner Li, Hongyi Ling, Sushil Vemuri, Blake Olson, Eric Li, Yu Zhang, James Caverlee, Dileep Kalathil, Shuiwang Ji

[**Paper**](https://openreview.net/forum?id=KJvHnl3kUv) [**Code**](https://github.com/divelab/E2H-Reasoning) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose E2H Reasoner, a curriculum-based RL approach that schedules tasks from easy to hard using a probabilistic scheduler, enabling small LLMs (1.5B–3B) to solve tasks they initially failed at zero-shot.
- We provide theoretical convergence guarantees showing curriculum stages require fewer samples than direct learning on hard tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/swat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Few-Shot Recognition via Stage-Wise Retrieval-Augmented Finetuning](https://arxiv.org/abs/2406.11148)

__Tian Liu__, Huixin Zhang, **Shubham Parashar**, Shu Kong

[**Paper**](https://arxiv.org/abs/2406.11148) [**Website**](https://tian1327.github.io/SWAT/) [**Poster**](https://tian1327.github.io/data/SWAT_CVPR'25_poster.pdf) [**Code**](https://github.com/tian1327/SWAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We retrieve open-world data for solving few-shot recognition, and propose stage-wise training to mitigate the imbalanced distribution and domain gap issues.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 (DMLR 2024 ORAL)</div><img src='images/teaser-tails.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Neglected Tails in Vision-Language Models.](https://openaccess.thecvf.com/content/CVPR2024/papers/Parashar_The_Neglected_Tails_in_Vision-Language_Models_CVPR_2024_paper.pdf)

**Shubham Parashar**, Zhiqiu Lin, Tian Liu, Xianjue Dong, Yanan Li, Deva Ramanan, James Caverlee, Shu Kong

[**Project**](https://shubhamprshr27.github.io/neglected-tails-of-vlms/)
[**Paper**](https://arxiv.org/abs/2401.12425) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Our study is the first to reveal bias in popular VLMs like CLIP due to long-tailed training data.
- To mitigate the bias, we propose a novel prompting method and retrieval augmented strategy. 
- Both our methods achieve a new SOTA and our retrieval augmented method is 100x cheaper on compute resources compared to the previous retrieval augmented strategies. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/teaser-emnlp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prompting Scientific Names for Zero-Shot Species Recognition](https://aclanthology.org/2023.emnlp-main.610/)

**Shubham Parashar**, Zhiqiu Lin, Yanan Li, Shu Kong

[**Paper**](https://arxiv.org/abs/2310.09929) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose an embarassingly simple prompting method that boosts the zero-shot accuracy of VLMs on 4 fine-grained species recognition benchmarks by **2-5x**.
</div>
</div>

- [Facial identification using Haar Cascading with BRISK](https://ieeexplore.ieee.org/abstract/document/9077901/), Dhruv Dixit, Shubham Parashar, Aashay Gondalia, Animesh Sengupta, M Sivagami, **ic-ETITE 2020**
- [IoT-based healthcare monitoring system for war soldiers using machine learning](https://www.sciencedirect.com/science/article/pii/S1877050918310202), Aashay Gondalia, Dhruv Dixit, Shubham Parashar, Vijayanand Raghava, Animesh Sengupta, Vergin Raja Sarobin, **IcROSMA 2018**

# 📝 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/teaser-sys2bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inference-Time Computations for LLM Reasoning and Planning: A Benchmark and Insights](https://arxiv.org/abs/2502.12521)

**Shubham Parashar**, Blake Olson, Sambhav Khurana, Eric Li, Hongyi Ling, James Caverlee, Shuiwang Ji

[**Paper**](https://arxiv.org/abs/2502.12521) [**Code**](https://github.com/divelab/Sys2Bench) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We construct Sys2Bench, a comprehensive benchmark evaluating inference-time techniques across 11 diverse tasks spanning arithmetic, logical, common sense, algorithmic reasoning, and planning.
- We reveal that simply scaling inference-time compute does not consistently improve performance, highlighting fundamental limitations of existing methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/teaser-autohd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Complex LLM Planning via Automated Heuristics Discovery](https://arxiv.org/abs/2502.19295)

**Shubham Parashar**, Hongyi Ling, Sambhav Khurana, Blake Olson, Anwesha Basu, Gaurangi Sinha, Zhengzhong Tu, James Caverlee, Shuiwang Ji

[**Paper**](https://arxiv.org/abs/2502.19295) [**Code**](https://github.com/divelab/Sys2Bench) [**OpenReview**](https://openreview.net/forum?id=yX1gmPYHOL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose AutoHD, which prompts LLMs to generate explicit heuristic functions as Python code to guide inference-time search, removing reliance on unreliable self-verification.
- AutoHD refines heuristics functions through an evolutionary process, which are then used for inference time search.
</div>
</div>


# 🎖 Honors and Awards
- *2026*: **Financial Assistance Award** — International Conference on Learning Representations (**ICLR**) *(awarded to ~325 of ~15,000 authors, ~2.2%)*
- *2024*: **Best Reviewer Award** — Annual Conference on Neural Information Processing Systems (**NeurIPS**)
- *2024*: **Travel Award** — Conference on Computer Vision and Pattern Recognition (**CVPR**)
- *2023*: **Travel Grant** — CSE@TAMU
- *2023*: **Department Scholarship** — CSE@TAMU

# 📚 Teaching & Service

## Teaching
- *2024*: Teaching Assistant — CSCE 421: Machine Learning (Texas A&M)
- *Spring 2024*: Grader — CSCE 636: Deep Learning (Texas A&M)
- *Spring 2023*: Grader — CSCE 642: Deep Reinforcement Learning (Texas A&M)

## Professional Service
- *2026*: Reviewer — ACM Computing Surveys (**CSUR**)
- *2026*: Reviewer — Transactions on Pattern Analysis and Machine Intelligence (**PAMI**)
- *2025*: Reviewer — Transactions on Machine Learning Research (**TMLR**)
- *2025, 2026*: Reviewer — International Conference on Machine Learning (**ICML**)
- *2025, 2026*: Reviewer — International Conference on Learning Representations (**ICLR**)
- *2024, 2025*: Reviewer — Annual Conference on Neural Information Processing Systems (**NeurIPS**)
- *2024*: Reviewer — Data-centric Machine Learning Research Workshop @ **ICML**
- *2024*: Organizer — Visual Perception via Learning in an Open World Workshop @ **CVPR**
- *2024*: Reviewer — What is Next in Multimodal Foundation Models Workshop @ **CVPR**

## Mentoring

- *2025–Present*: [Lakshmi Jotsna Madhavarapu](https://www.linkedin.com/in/lakshmi-jotsna-madhavarapu-116863253/) — Incoming Data Scientist Intern @ Capital One
- *2025–Present*: [Atharv Chagi](https://www.linkedin.com/in/atharv-chagi-b04575234/) — Incoming Software Engineer Intern @ Texas Instruments
- *2024–2025*: [Blake Olson](https://www.linkedin.com/in/blakeaolson/) — MS CS @ UT Austin
- *2024–2025*: [Eric Li](https://www.linkedin.com/in/ericli18/) — Junior @ Texas A&M University


# 📖 Education
<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2024.06 - Present*, Ph.D. in Computer Science, Texas A&M University, College Station, Texas 
- *2022.08 - 2024.05*, M.S. in Computer Science, Texas A&M University, College Station, Texas 
- *2015.07 - 2019.05*, Undergraduate, Vellore Institute of Technology University, Chennai, India

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *2025.05 - 2025.08*, [AWS](https://aws.amazon.com/), Santa Clara, Ca.
- *2023.05 - 2023.08*, [HPE](https://www.hpe.com/us/en/home.html), Houston, Tx.
- *2019.07 - 2022.09*, [PayPal](https://www.paypal.com/), Bangalore, India