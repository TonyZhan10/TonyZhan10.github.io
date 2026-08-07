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

I am **Jiabo Zhan (詹佳博)**, affiliated with Tsinghua University. My research interests include **computer vision**, **multimodal large language models (MLLMs)**, **AI-generated content (AIGC)**, and generative models for transparent and layered RGBA images.

My publications have received <a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><strong><span id='total_cit'>13</span> Google Scholar citations</strong></a>. Citation counts are updated automatically every day. <a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations"></a>

Contact: **WeChat: `_Marsquakes`**


# 🔥 News
- *2026.04*: &nbsp;OmniAlpha was substantially revised with multi-task reinforcement learning for transparency-aware generation.
- *2025.11*: &nbsp;OmniAlpha was released with open-source code and model weights.
- *2025.07*: &nbsp;AlphaVAE was released with open-source code, data, and models.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/omnialpha.jpg' alt="OmniAlpha examples" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniAlpha: Aligning Transparency-Aware Generation via Multi-Task Unified Reinforcement Learning](https://arxiv.org/abs/2511.20211)

Hao Yu<sup>*</sup>, Jinglin Wang<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Rui Chen, Zile Wang, Huaisong Zhang, Hongyu Li, Xinrui Chen, Yongxian Wei, Chun Yuan

<sup>*</sup> Equal contribution.

[**Paper**](https://arxiv.org/abs/2511.20211) / [**PDF**](https://arxiv.org/pdf/2511.20211) / [**Code**](https://github.com/Longin-Yu/OmniAlpha) / [**Model**](https://huggingface.co/Longin-Yu/OmniAlpha) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u-x6o8ySG0sC) <strong><span class='show_paper_citations' data='jGxsEcoAAAAJ:u-x6o8ySG0sC'>| Citations: 5</span></strong>

- A unified framework for transparency-aware generation and manipulation across image matting, object removal, layer decomposition, and RGBA generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/alphavae.jpg' alt="AlphaVAE transparent image generation examples" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AlphaVAE: Unified End-to-End RGBA Image Reconstruction and Generation with Alpha-Aware Representation Learning](https://arxiv.org/abs/2507.09308)

Zile Wang, Hao Yu, **Jiabo Zhan**, Chun Yuan

[**Paper**](https://arxiv.org/abs/2507.09308) / [**PDF**](https://arxiv.org/pdf/2507.09308) / [**Code**](https://github.com/o0o0o00o0/AlphaVAE) / [**Model**](https://huggingface.co/AlphaVAE/AlphaVAE) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='jGxsEcoAAAAJ:u5HHmVD_uO8C'>| Citations: 8</span></strong>

- An alpha-aware VAE for end-to-end RGBA reconstruction and transparent image generation, accompanied by the ALPHA evaluation benchmark.
</div>
</div>
