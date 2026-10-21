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

I am **Jiabo Zhan (詹佳博)**, an M.Eng. student in Computer Technology at **Tsinghua University, Shenzhen International Graduate School**, advised by Prof. Chun Yuan. I received my B.E. in Software Engineering from **Beihang University** in 2026, graduating **2nd out of 172 students (top 1.2%)** with a GPA of **3.873/4.0**.

My research focuses on **computer vision**, **multimodal large language models (MLLMs)**, and **reinforcement learning**, with recent work on transparency-aware RGBA generation and editing, robust document parsing, and tool-augmented visual question answering. I am currently an algorithm intern in **Tencent's Weixin Group (WXG), Technology Architecture Department**, working on multimodal training data, supervised fine-tuning, and evaluation.

<a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations"></a>

<div class="contact-block">
  <div class="contact-block__title">Contact</div>
  <div><strong>Email:</strong> <a href="mailto:jiabozhan0618@gmail.com">jiabozhan0618@gmail.com</a></div>
  <div><strong>WeChat:</strong> <code>_Marsquakes</code></div>
</div>

<span class='anchor' id='news'></span>

# 🔥 News

- *2026.09*: &nbsp;Started my M.Eng. studies in Computer Technology at Tsinghua University, Shenzhen International Graduate School, advised by Prof. Chun Yuan.
- *2026.09*: &nbsp;[WeVisDoc](https://tencent.github.io/WeVisDoc/) was released as a technical report on robust end-to-end document parsing, with open-source code and 2B/4B model weights.
- *2026.08*: &nbsp;PaDoc was released with open-source code and model weights.
- *2026.08*: &nbsp;🎉 **OmniAlpha was accepted to ACM Multimedia 2026 (ACM MM 2026) as an Oral Presentation!**
- *2026.07*: &nbsp;Joined Tencent WXG's Technology Architecture Department as an algorithm intern.
- *2026.04*: &nbsp;OmniAlpha was substantially revised with multi-task reinforcement learning for transparency-aware generation.
- *2025.11*: &nbsp;OmniAlpha was released with open-source code and model weights.
- *2025.07*: &nbsp;AlphaVAE was released with open-source code, data, and models.

<span class='anchor' id='technical-reports'></span>

# 📄 Technical Reports {#technical-reports-heading}

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<a class="github-stars" href="https://github.com/Tencent/WeVisDoc" aria-label="WeVisDoc GitHub stars">
  <img src="https://img.shields.io/github/stars/Tencent/WeVisDoc?style=flat&amp;logo=github&amp;label=GitHub%20stars&amp;labelColor=24292f&amp;color=ffc928" alt="WeVisDoc GitHub stars" height="20">
</a>
<a href="https://tencent.github.io/WeVisDoc/"><img src='{{ "/images/wevisdoc.png" | relative_url }}' alt="WeVisDoc-4B benchmark results on OmniDocBench and PureDocBench" width="1224" height="626" style="width: 100%;" loading="lazy"></a></div></div>
<div class='paper-box-text' markdown="1">

[WeVisDoc: From Coverage to Capability for Robust End-to-End Document Parsing](https://arxiv.org/abs/2609.20423)

Hao Yu<sup>*</sup>, Kang Liu<sup>*</sup>, Linnan Zhao<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Chong Sun, Chen Li, Jing Lyu

<sup>*</sup> Equal contribution (co-first authors). **Technical Report, 2026.**

Research period: Jun. 2026 – Sep. 2026.

[**Report**](https://arxiv.org/abs/2609.20423) / [**PDF**](https://arxiv.org/pdf/2609.20423) / [**Project**](https://tencent.github.io/WeVisDoc/) / [**Code**](https://github.com/Tencent/WeVisDoc) / [**Model (2B)**](https://huggingface.co/Tencent/WeVisDoc-2B) / [**Model (4B)**](https://huggingface.co/Tencent/WeVisDoc-4B)

- A two-stage data-centric framework that expands document coverage, then uses residual-error diagnostics to guide targeted data construction and training-budget allocation for robust end-to-end parsing.
- WeVisDoc-4B achieves an Overall score of **95.38** on OmniDocBench v1.6 and a mean Overall score of **75.54** across the three PureDocBench tracks, ranking first among the compared end-to-end parsers in all four settings.
- **Contribution:** Collected and annotated handwriting, exam-paper, and textbook data; deduplicated samples by hash and filtered corrupt or unreadable documents. Combined candidate annotations from MinerU2.5-Pro and PaddleOCR-VL with MLLM review and manual region-level reannotation to produce consistent training ground truth.
- Built document degradation and augmentation pipelines covering wrinkles, bending, rotation, real-scene synthesis, and blur, while preserving image–annotation consistency and content readability.
</div>
</div>

<span class='anchor' id='publications'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"><span>ACM MM 2026</span><span class="badge__oral">ORAL</span></div><img src='{{ "/images/omnialpha.jpg" | relative_url }}' alt="OmniAlpha examples" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniAlpha: Aligning Transparency-Aware Generation via Multi-Task Unified Reinforcement Learning](https://arxiv.org/abs/2511.20211)

Hao Yu<sup>*</sup>, Jinglin Wang<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Rui Chen, Zile Wang, Huaisong Zhang, Hongyu Li, Xinrui Chen, Yongxian Wei, Chun Yuan

<sup>*</sup> Equal contribution. **ACM Multimedia 2026.** <span class="oral-highlight">ORAL PRESENTATION</span>

Research period: Jan. 2026 – Apr. 2026.

[**Paper**](https://arxiv.org/abs/2511.20211) / [**PDF**](https://arxiv.org/pdf/2511.20211) / [**Code**](https://github.com/Longin-Yu/OmniAlpha) / [**Model**](https://huggingface.co/Longin-Yu/OmniAlpha) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u-x6o8ySG0sC)

- A unified RGBA generation and editing framework for five transparency-aware tasks: text-to-RGBA generation, object removal, automatic matting, referring matting, and layer decomposition. The model achieves state-of-the-art or near-state-of-the-art results across all five tasks.
- **Contribution:** As a co-first author, was primarily responsible for multi-task training-data schema design, sample construction, data cleaning, and evaluation-code development. Participated in multi-task SFT cold-start training and GRPO-style RL post-training, with a focus on reward design, cross-task evaluation, and training stability.
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

[PaDoc: Layout-Grounded Parallel Decoding for Document Parsing](https://arxiv.org/abs/2608.06146)

Hao Yu<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Kang Liu, Linnan Zhao, Dongxu Yue, Rui Chen, Jinglin Wang, Chong Sun, Chen Li, Jing Lyu, Chun Yuan

<sup>*</sup> Equal contribution.

[**Paper**](https://arxiv.org/abs/2608.06146) / [**PDF**](https://arxiv.org/pdf/2608.06146) / [**Code**](https://github.com/Longin-Yu/Padoc) / [**Model**](https://huggingface.co/Longin-Yu/PaDoc) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:2osOgNQ5qMEC)

- A layout-grounded parser that branches regional content from shared full-page prefixes, improving throughput by 67.4–118% over same-backbone sequential decoding while retaining top-tier parsing quality.
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

# 💼 Internships

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">Tencent · Weixin Group (WXG)</div>
  <div class="cv-item__date">Jul. 2026 – Present</div>
</div>
<div class="cv-item__meta">Algorithm Intern · Technology Architecture Department · Expected end: Mar. 2027</div>

- Built and governed Parsing/VQA data for WeVisDoc document understanding: maintained approximately **9 million VQA examples**, added approximately **1.5 million examples**, and curated around **30,000 pages** of long-tail documents such as handwritten notes and exam papers through deduplication, reannotation, and training-data delivery.
- Constructed mixed Direct/CoT supervision, ran two-stage SFT and cross-task evaluation, analyzed shifts in model capabilities, and optimized sampling ratios across data sources.
- Built **57,132 Direct/tool-assisted QA examples** involving Zoom/Crop and Python through teacher-model generation, real tool execution, and automated review. Completed tool-augmented SFT of **Qwen3-VL-4B-Instruct**, improving accuracy from **40.6% to 45.9% (+5.3 percentage points)** on the 1,000-question CharXiv-RQ validation set under the same Direct protocol.

</div>

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">Momenta</div>
  <div class="cv-item__date">Sep. 2025 – Dec. 2025</div>
</div>
<div class="cv-item__meta">Algorithm Intern · Driving-behavior classification and multimodal model fine-tuning</div>

- Developed a locally deployable open-source VLM solution for driving behaviors such as crossing solid lane markings and overtaking. Uniformly sampled **16 frames** from rosbag videos as 2D multi-frame inputs and fine-tuned **Qwen3-VL-8B-Instruct** with manually reviewed ground truth, covering input modeling, supervision-data construction, and SFT.
- Improved model accuracy from **59% to 70% (+11 percentage points)**; the Gemini 2.5 Pro baseline achieved 80%. Replaced the original API workflow, priced at approximately **US$10 per million tokens**, with local GPU deployment and inference.

</div>

<span class='anchor' id='honors'></span>

# 🏆 Honors & Awards

- **National Scholarship**, 2022–2023 and 2023–2024 academic years.
- **Outstanding Student** and **Outstanding Communist Youth League Member** at Beihang University, 2022–2023, 2023–2024, and 2024–2025 academic years.
- **Samsung Scholarship**, 2024–2025; **First Prize in Beijing**, Chinese Mathematics Competitions for College Students.
- More than ten additional university-level scholarships at Beihang University.

<span class='anchor' id='skills'></span>

# 🛠 Skills

<div class="skills-grid">
  <p><strong>Models & Training</strong><br>VLM, VAE, and DiT training and evaluation; SFT and GRPO; knowledge of DPO and PPO.</p>
  <p><strong>Data & Evaluation</strong><br>Training-data construction, cleaning and governance, benchmark and evaluation-code development, offline evaluation, and error analysis.</p>
  <p><strong>Multimodal Understanding</strong><br>Visual grounding, OCR, layout analysis, key information extraction, and image-text-structured signal modeling.</p>
  <p><strong>Engineering</strong><br>Python, PyTorch, C/C++, and Java; multimodal pipeline engineering and product deployment.</p>
  <p><strong>Languages</strong><br>Chinese (native); English (CET-4: 662, CET-6: 633), including academic reading and spoken communication.</p>
  <p><strong>Service</strong><br>Staff member of the School of Software Student Union's Academic Center; teaching assistant for College English and Compiler Technology; 250 hours of volunteering in Beijing.</p>
</div>
