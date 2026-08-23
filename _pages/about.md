---
permalink: /
title: ""
excerpt: "Jiabo Zhan - computer vision, multimodal large language models, reinforcement learning, generative AI, and document intelligence."
lang: en
sidebar_description: "Computer vision, multimodal large language models, reinforcement learning, generative AI, and document intelligence."
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

I am **Jiabo Zhan (詹佳博)**, an incoming M.Eng. student in Computer Technology at **Tsinghua University, Shenzhen International Graduate School**, advised by Prof. Chun Yuan. I received my B.E. in Software Engineering from **Beihang University** in 2026, graduating **2nd out of 172 students (top 1.2%)** with a GPA of **3.873/4.0**.

My research interests include **computer vision**, **multimodal large language models (MLLMs)**, **reinforcement learning**, **AI-generated content (AIGC)**, and **document intelligence**. My recent work focuses on transparent and layered RGBA generation, efficient document parsing, multimodal data construction, and evaluation.

My publications have received <a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><strong><span id='total_cit'>14</span> Google Scholar citations</strong></a>. Citation counts are updated automatically every day. <a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations"></a>

<div class="contact-block">
  <div class="contact-block__title">Contact</div>
  <div><strong>Email:</strong> <a href="mailto:jiabozhan0618@gmail.com">jiabozhan0618@gmail.com</a></div>
  <div><strong>WeChat:</strong> <code>_Marsquakes</code></div>
</div>

<span class='anchor' id='news'></span>

# 🔥 News

- *2026.08*: &nbsp;PaDoc was released with open-source code and model weights.
- *2026.08*: &nbsp;🎉 **OmniAlpha was accepted to ACM Multimedia 2026 (ACM MM 2026)!**
- *2026.04*: &nbsp;OmniAlpha was substantially revised with multi-task reinforcement learning for transparency-aware generation.
- *2025.11*: &nbsp;OmniAlpha was released with open-source code and model weights.
- *2025.07*: &nbsp;AlphaVAE was released with open-source code, data, and models.

<span class='anchor' id='publications'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='{{ "/images/padoc.png" | relative_url }}' alt="PaDoc layout-grounded parallel document parsing" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PaDoc: Layout-Grounded Parallel Decoding for Document Parsing](https://arxiv.org/abs/2608.06146)

Hao Yu, **Jiabo Zhan**, Kang Liu, Linnan Zhao, Dongxu Yue, Rui Chen, Jinglin Wang, Chong Sun, Chen Li, Jing Lyu, Chun Yuan

[**Paper**](https://arxiv.org/abs/2608.06146) / [**PDF**](https://arxiv.org/pdf/2608.06146) / [**Code**](https://github.com/Longin-Yu/Padoc) / [**Model**](https://huggingface.co/Longin-Yu/PaDoc) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:2osOgNQ5qMEC)

- A layout-grounded parser that branches regional content from shared full-page prefixes, improving throughput by 67.4–118% over same-backbone sequential decoding while retaining top-tier parsing quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2026</div><img src='{{ "/images/omnialpha.jpg" | relative_url }}' alt="OmniAlpha examples" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniAlpha: Aligning Transparency-Aware Generation via Multi-Task Unified Reinforcement Learning](https://arxiv.org/abs/2511.20211)

Hao Yu<sup>*</sup>, Jinglin Wang<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Rui Chen, Zile Wang, Huaisong Zhang, Hongyu Li, Xinrui Chen, Yongxian Wei, Chun Yuan

<sup>*</sup> Equal contribution. **ACM Multimedia 2026.**

[**Paper**](https://arxiv.org/abs/2511.20211) / [**PDF**](https://arxiv.org/pdf/2511.20211) / [**Code**](https://github.com/Longin-Yu/OmniAlpha) / [**Model**](https://huggingface.co/Longin-Yu/OmniAlpha) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u-x6o8ySG0sC)

- A unified framework for transparency-aware generation and manipulation across image matting, object removal, layer decomposition, and RGBA generation.
- **Contribution:** Co-designed the multi-task data schema and evaluation pipeline, curated training data, and contributed to multi-task SFT and GRPO-style RL post-training; achieved a 9.07% relative reduction in RGB L1 on layer decomposition.
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

[AlphaVAE: Unified End-to-End RGBA Image Reconstruction and Generation with Alpha-Aware Representation Learning](https://arxiv.org/abs/2507.09308)

Zile Wang, Hao Yu, **Jiabo Zhan**, Chun Yuan

[**Paper**](https://arxiv.org/abs/2507.09308) / [**PDF**](https://arxiv.org/pdf/2507.09308) / [**Code**](https://github.com/o0o0o00o0/AlphaVAE) / [**Model**](https://huggingface.co/AlphaVAE/AlphaVAE) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u5HHmVD_uO8C)

- An alpha-aware VAE for end-to-end RGBA reconstruction and transparent image generation, accompanied by the ALPHA evaluation benchmark.
- **Contribution:** Curated and governed 8,124 high-quality RGBA training samples and helped design the benchmark, evaluation code, and LoRA data iteration workflow.
</div>
</div>

<span class='anchor' id='education'></span>

# 🎓 Education

<div class="cv-item">
  <div class="cv-item__header">
    <div class="cv-item__title">Tsinghua University, Shenzhen International Graduate School</div>
    <div class="cv-item__date">Sep. 2026 – Jun. 2028 (expected)</div>
  </div>
  <div class="cv-item__meta">M.Eng. in Computer Technology · Advisor: Prof. Chun Yuan</div>
  <p>Research focus: computer vision, multimodal large language models, and reinforcement learning.</p>
</div>

<div class="cv-item">
  <div class="cv-item__header">
    <div class="cv-item__title">Beihang University, School of Software</div>
    <div class="cv-item__date">Sep. 2022 – Jun. 2026</div>
  </div>
  <div class="cv-item__meta">B.E. in Software Engineering · GPA: 3.873/4.0 · Weighted average: 93.005/100</div>
  <p>Ranked 2/172 (top 1.2%) and admitted to Tsinghua University for graduate study through recommendation, exempt from the national entrance examination.</p>
</div>

<span class='anchor' id='experience'></span>

# 💼 Research & Industry Experience

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">VFlow AI Video Generation · Tsinghua University, Shenzhen International Graduate School</div>
  <div class="cv-item__date">Dec. 2025 – Jun. 2026</div>
</div>
<div class="cv-item__meta">Algorithm Intern · Industry project led by Prof. Chun Yuan</div>

- Helped build a page-level multimodal pipeline that turns product pages, images, and marketing copy into structured attributes, scripts, and generated videos.
- Built and cleaned image-text and instruction data, iterated prompt templates, and conducted offline evaluation for visual grounding, structured extraction, and multi-turn generation.

</div>

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">Momenta</div>
  <div class="cv-item__date">Sep. 2025 – Nov. 2025</div>
</div>
<div class="cv-item__meta">Algorithm Intern · Autonomous-driving road-condition classification</div>

- Developed a Qwen3-VL classification approach that combined camera images with structured rosbag signals such as speed and position; built the evaluation set, prompts, and offline evaluation pipeline.
- Migrated a high-cost Gemini-2.5 Pro workflow to a deployable open-source VLM solution, reducing classification cost by approximately 80% while accepting an accuracy change from 80% to 70%.

</div>

<span class='anchor' id='honors'></span>

# 🏆 Honors & Awards

- **National Scholarship**, 2022–2023 and 2023–2024 academic years.
- **Outstanding Student** at Beihang University for three consecutive academic years; **Outstanding Communist Youth League Member**.
- **Samsung Scholarship**, 2024–2025; **First Prize in Beijing**, Chinese Mathematics Competitions for College Students.

<span class='anchor' id='skills'></span>

# 🛠 Skills

<div class="skills-grid">
  <p><strong>Models & Training</strong><br>VLM, VAE, DiT, multi-task SFT, GRPO-style RL; familiar with DPO and PPO.</p>
  <p><strong>Data & Evaluation</strong><br>Dataset construction and governance, benchmark design, evaluation pipelines, offline evaluation, and error analysis.</p>
  <p><strong>Multimodal Understanding</strong><br>Visual grounding, OCR, layout analysis, key information extraction, and image-text-structured signal modeling.</p>
  <p><strong>Engineering</strong><br>Python, PyTorch, C/C++, and Java; multimodal pipeline engineering and product deployment.</p>
  <p><strong>Languages</strong><br>Chinese (native); English (CET-4: 662, CET-6: 633).</p>
  <p><strong>Service</strong><br>Teaching assistant for College English and Compiler Technology; 250 hours of volunteering in Beijing.</p>
</div>
