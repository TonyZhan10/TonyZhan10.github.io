---
permalink: /zh/
title: ""
excerpt: "詹佳博的个人主页：计算机视觉、多模态大模型、强化学习、生成式人工智能与文档智能。"
lang: zh
sidebar_description: "计算机视觉、多模态大模型、强化学习、生成式人工智能与文档智能。"
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我是**詹佳博（Jiabo Zhan）**，即将于清华大学深圳国际研究生院攻读计算机技术硕士学位，导师为袁春教授。我于 2026 年获得北京航空航天大学软件工程学士学位，本科期间以 **GPA 3.873/4.0、专业排名 2/172（前 1.2%）**毕业。

我的研究兴趣包括**计算机视觉**、**多模态大模型（MLLM）**、**强化学习**、**生成式人工智能（AIGC）**和**文档智能**。近期工作主要围绕透明及分层 RGBA 图像生成、高效文档解析、多模态数据构建与评测展开。

我的论文目前已获得 <a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><strong><span id='total_cit'>14</span> 次 Google Scholar 引用</strong></a>，引用数据每日自动更新。<a href='https://scholar.google.com/citations?user=jGxsEcoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar 引用数"></a>

<div class="contact-block">
  <div class="contact-block__title">联系方式</div>
  <div><strong>邮箱：</strong><a href="mailto:jiabozhan0618@gmail.com">jiabozhan0618@gmail.com</a></div>
  <div><strong>微信：</strong><code>_Marsquakes</code></div>
</div>

<span class='anchor' id='news'></span>

# 🔥 最新动态

- *2026.08*: &nbsp;PaDoc 正式发布，代码与模型权重已开源。
- *2026.08*: &nbsp;🎉 **OmniAlpha 被 ACM Multimedia 2026（ACM MM 2026）录用！**
- *2026.04*: &nbsp;OmniAlpha 完成重要更新，引入面向透明感知生成的多任务强化学习。
- *2025.11*: &nbsp;OmniAlpha 正式发布，代码与模型权重已开源。
- *2025.07*: &nbsp;AlphaVAE 正式发布，代码、数据与模型已开源。

<span class='anchor' id='publications'></span>

# 📝 论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='{{ "/images/padoc.png" | relative_url }}' alt="PaDoc 布局驱动并行文档解析" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PaDoc: Layout-Grounded Parallel Decoding for Document Parsing](https://arxiv.org/abs/2608.06146)

Hao Yu, **Jiabo Zhan**, Kang Liu, Linnan Zhao, Dongxu Yue, Rui Chen, Jinglin Wang, Chong Sun, Chen Li, Jing Lyu, Chun Yuan

[**论文**](https://arxiv.org/abs/2608.06146) / [**PDF**](https://arxiv.org/pdf/2608.06146) / [**代码**](https://github.com/Longin-Yu/Padoc) / [**模型**](https://huggingface.co/Longin-Yu/PaDoc) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:2osOgNQ5qMEC)

- 提出布局驱动的文档解析器，让各区域内容从共享的整页前缀并行分支；相较同骨干串行解码方案，吞吐提升 67.4–118%，同时保持领先的解析质量。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2026</div><img src='{{ "/images/omnialpha.jpg" | relative_url }}' alt="OmniAlpha 示例" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniAlpha: Aligning Transparency-Aware Generation via Multi-Task Unified Reinforcement Learning](https://arxiv.org/abs/2511.20211)

Hao Yu<sup>*</sup>, Jinglin Wang<sup>*</sup>, **Jiabo Zhan**<sup>*</sup>, Rui Chen, Zile Wang, Huaisong Zhang, Hongyu Li, Xinrui Chen, Yongxian Wei, Chun Yuan

<sup>*</sup> 共同一作。**ACM Multimedia 2026。**

[**论文**](https://arxiv.org/abs/2511.20211) / [**PDF**](https://arxiv.org/pdf/2511.20211) / [**代码**](https://github.com/Longin-Yu/OmniAlpha) / [**模型**](https://huggingface.co/Longin-Yu/OmniAlpha) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u-x6o8ySG0sC)

- 统一处理图像抠图、目标移除、图层分解和 RGBA 生成等透明感知生成与编辑任务。
- **个人贡献：**参与多任务数据 schema 与评测流程设计、训练数据构建与治理，以及多任务 SFT 和 GRPO 风格强化学习后训练；在图层分解任务上实现 RGB L1 相对降低 9.07%。
</div>
</div>

<div class='paper-box paper-box--text-only'>
<div class='paper-box-text' markdown="1">

[AlphaVAE: Unified End-to-End RGBA Image Reconstruction and Generation with Alpha-Aware Representation Learning](https://arxiv.org/abs/2507.09308)

Zile Wang, Hao Yu, **Jiabo Zhan**, Chun Yuan

[**论文**](https://arxiv.org/abs/2507.09308) / [**PDF**](https://arxiv.org/pdf/2507.09308) / [**代码**](https://github.com/o0o0o00o0/AlphaVAE) / [**模型**](https://huggingface.co/AlphaVAE/AlphaVAE) / [**Scholar**](https://scholar.google.com/citations?view_op=view_citation&user=jGxsEcoAAAAJ&citation_for_view=jGxsEcoAAAAJ:u5HHmVD_uO8C)

- 面向端到端 RGBA 图像重建与透明图像生成的 Alpha-aware VAE，并配套提出 ALPHA 评测基准。
- **个人贡献：**完成 8,124 张高质量 RGBA 训练样本的收集、清洗与治理，并参与 benchmark、评测代码和 LoRA 数据迭代流程设计。
</div>
</div>

<span class='anchor' id='education'></span>

# 🎓 教育背景

<div class="cv-item">
  <div class="cv-item__header">
    <div class="cv-item__title">清华大学 · 深圳国际研究生院</div>
    <div class="cv-item__date">2026.09 – 2028.06（预计）</div>
  </div>
  <div class="cv-item__meta">计算机技术硕士 · 导师：袁春教授</div>
  <p>研究方向：计算机视觉、多模态大模型与强化学习。</p>
</div>

<div class="cv-item">
  <div class="cv-item__header">
    <div class="cv-item__title">北京航空航天大学 · 软件学院</div>
    <div class="cv-item__date">2022.09 – 2026.06</div>
  </div>
  <div class="cv-item__meta">软件工程学士 · GPA：3.873/4.0 · 加权平均分：93.005/100</div>
  <p>专业排名 2/172（前 1.2%），免试攻读清华大学计算机技术硕士学位。</p>
</div>

<span class='anchor' id='experience'></span>

# 💼 科研与实习经历

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">VFlow AI 视频生成 · 清华大学深圳国际研究生院</div>
  <div class="cv-item__date">2025.12 – 至今</div>
</div>
<div class="cv-item__meta">算法实习 · 袁春教授横向项目</div>

- 参与构建页面级多模态理解 pipeline，将商品详情页、商品图片与营销文案转化为结构化属性、脚本及生成视频。
- 负责图文样本和指令数据构建与清洗、prompt 模板迭代及离线评测，重点关注视觉 grounding、结构化信息抽取和多轮生成质量。

</div>

<div class="cv-item" markdown="1">

<div class="cv-item__header">
  <div class="cv-item__title">Momenta</div>
  <div class="cv-item__date">2025.09 – 2025.11</div>
</div>
<div class="cv-item__meta">算法实习 · 自动驾驶路况分类</div>

- 基于 Qwen3-VL 构建融合相机图像与车速、位置等 rosbag 结构化信号的路况分类方案，完成评测集、prompt 与离线评测流程设计。
- 将高成本 Gemini-2.5 Pro 流程迁移为可部署的开源 VLM 方案，在接受准确率由 80% 降至 70% 的情况下，将分类成本降低约 80%。

</div>

<span class='anchor' id='honors'></span>

# 🏆 奖项荣誉

- **国家奖学金**：2022–2023、2023–2024 学年。
- 连续三个学年获评北京航空航天大学**校级三好学生**，并获**校级优秀团员**。
- **三星奖学金**（2024–2025 学年）；全国大学生数学竞赛**北京市一等奖**。
- 第三十五届北航“冯如杯”主赛道制作组**三等奖**：基于 SAMUS、Electron 与 Python 的智能胰腺诊断系统。

<span class='anchor' id='skills'></span>

# 🛠 专业技能

<div class="skills-grid">
  <p><strong>模型与训练</strong><br>VLM、VAE、DiT、多任务 SFT、GRPO 风格强化学习后训练；熟悉 DPO 与 PPO。</p>
  <p><strong>数据与评测</strong><br>训练数据构建与治理、benchmark 设计、评测流水线、离线评测及误差分析。</p>
  <p><strong>多模态理解</strong><br>视觉 grounding、OCR、版面分析、关键信息抽取及图像—文本—结构化信号联合建模。</p>
  <p><strong>工程能力</strong><br>Python、PyTorch、C/C++、Java；具备多模态 pipeline 工程化与产品化落地经验。</p>
  <p><strong>外语能力</strong><br>英语 CET-4：662 分，CET-6：633 分。</p>
  <p><strong>其他经历</strong><br>《大学英语》《编译技术》课程助教；志愿北京累计 250 小时。</p>
</div>
