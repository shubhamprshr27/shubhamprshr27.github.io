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

Hi! I am a second year M.S. in Computer Science Student at Texas A&M University, advised by Prof. Shu Kong, Prof. James Caverlee and Prof. Deva Ramanan. I have completed my undergraduate degree in Computer Science and Engineering from Vellore Institute of Technology, Chennai. My research interests currently lie at the intersection of Computer Vision and Natural Language Processing, particularly in Vision Language Models and their application in multi-modal chatbots and diffusion models. My aim is to investigate and address the biases and limitations of these models, to develop more robust and fairer VLMs.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.02*: &nbsp;🎉🎉 Our paper, "The Neglected Tails of Vision-Language Models" has been accepted at CVPR 2024! 
- *2023.12*: &nbsp;🎉🎉 I will be presenting our paper, "Prompting Scientific Names for Zero-Shot Species Recognition" at EMNLP 2023. 
- *2022.02*: &nbsp;🎉🎉 I was awarded the Texas A&M Computer Science departmental scholarship. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/teaser-tails.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Neglected Tails of Vision-Language Models.](https://arxiv.org/abs/2401.12425)

**Shubham Parashar**^*^, Zhiqiu Lin^*^, Tian Liu^*^, Xianjue Dong, Yanan Li, Deva Ramanan, James Caverlee, Shu Kong

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

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Education
<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2022.08 - (now)*, M.S. in Computer Science, Texas A&M University, College Station, Texas 
- *2015.07 - 2019.05, Undergraduate, Vellore Institute of Technology University, Chennai, India

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experience
- *2023.05 - 2023.08*, [HPE](https://www.hpe.com/us/en/home.html), Houston, Tx.
- *2019.07 - 2022.09*, [PayPal](https://www.paypal.com/), Bangalore, India