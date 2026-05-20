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

I am a direct Ph.D. student in Electronic Information at **Harbin Institute of Technology (HIT)**, advised by Prof. Tonghua Su. My research focuses on multimodal generation, digital human video generation, talking-head generation, and portrait animation. I work on DiT / diffusion-based video generation, controllable face video generation, large-scale digital human datasets, and agent-based AIGC systems.
<a href='https://scholar.google.com/citations?user=_Xik6HkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

My research interests include:
- Digital human video generation
- Talking-head generation and audio-driven portrait animation
- DiT / diffusion models for video generation
- Multimodal generation and controllable AIGC
- Large-scale face video dataset construction
- Fine-grained facial motion, gaze, expression, and speaking-style control
- Agent-based video generation systems

<span class='anchor' id='education'></span>

# Education

- *Sep. 2024 – Jun. 2029*, **Harbin Institute of Technology**, Ph.D. Student in Electronic Information, Advisor: Prof. Tonghua Su. Research: Multimodal Generation, Digital Human Video Generation.
- *Sep. 2020 – Jun. 2024*, **Central South University**, B.Eng. in Software Engineering. University-level Third-Class Scholarship (twice).

<span class='anchor' id='publications'></span>

# Selected Publications

---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVIU 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **DiTalker: A Unified DiT-based Framework for High-Quality and Speaking Styles Controllable Portrait Animation**
  **He Feng**, et al. *Computer Vision and Image Understanding (CVIU)*, 2026. **CCF-B · First Author**
  DiTalker proposes a unified DiT-based framework for controllable portrait animation. It decouples personalized facial dynamics and global expression semantics, and fuses audio and speaking-style conditions to generate high-quality, lip-synchronized, and style-controllable portrait videos.
  [[Project Page](#)] [[Paper](#)] [[Code](#)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **DH-FaceVid-1K: A Large-Scale High-Quality Dataset for Face Video Generation**
  *ICCV*, 2025. **CCF-A · Second Author**
  A large-scale, high-quality face video generation dataset for talking-head and face video generation. It covers diverse identities, scenarios, and high-quality speaking-face samples, supporting model training and evaluation.
  [[Project Page](#)] [[Paper](#)] [[Dataset](#)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **DH-OmniFace: A Large-Scale and Multi-Attribute Dataset Suite for Controllable Face Video Generation**
  **He Feng**, et al. *IEEE Trans. Multimedia (TMM)*. **CCF-A / JCR Q1 · First Author · Major Revision**
  A multi-attribute dataset suite for controllable face video generation, covering identity, emotion, lighting, multi-view head pose, large head motion, laughter, and complex body motion. 340K+ video clips, ~1,879 hours. Introduces FACET as a fine-grained controllable generation benchmark.
  [[Project Page](#)] [[Paper](#)] [[Dataset](#)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- **CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning**
  **He Feng**, et al. *ACM Multimedia (MM)*. **CCF-A · First Author · Under Review**
  Explores fine-grained eye-region control for portrait animation. Uses hierarchical MLLM-agent planning to convert high-level semantic control into executable facial landmarks, and a DiT-based video generation backbone to synthesize digital human videos with controllable gaze, blinking, eyebrow motion, and head pose.
  [[Project Page](#)] [[Paper](#)] [[Code](#)]

</div>
</div>

- **Talking Face Video Generation Survey**, *TPAMI*. **Contributor · Under Review**
  A survey on talking face video generation, covering audio-driven portrait animation, talking-head generation, digital avatar generation, datasets, model paradigms, evaluation metrics, and future directions.

### Patents and Software Copyrights

- **Two accepted internal invention patents** related to talking-face video generation, digital human foundation model training, and dataset construction.
- **Invention Patent**: *Method and System for Automatic Generation of Multilingual Educational Videos Based on Multi-Agent Collaboration* — Accepted.
- **Software Copyright**: *Multi-language MOOC Teaching Video Automatic Generation System Based on Multi-Agent Collaboration* — Accepted.

<span class='anchor' id='experience'></span>

# Industry Experience

### Algorithm Intern · Digital Human Group, Spatial AI Department, Li Auto
**Jul. 2024 – Jan. 2025**

- Reproduced and evaluated 20+ talking-face and digital human video generation models, including SadTalker, AniPortrait, EMO, MuseV, VASA-1, and MODA.
- Developed and evaluated OpenSora-Plan-based talking-face foundation models at 1B / 3B / 5B scales.
- Participated in training, inference, and evaluation of DiT / diffusion architectures for talking-head generation.
- Built a 1,000+ hour talking-face video database with MLLM-generated captions and multimodal annotations.
- Supported DH-FaceVid-1K and DH-OmniFace dataset construction.
- Contributed to two accepted internal invention patents.
- Participated in writing a TPAMI survey submission.

# Projects

### Digital Human Generation Foundation Model R&D
**Li Auto-University Joint Program · Jun. 2024 – Jan. 2025**
Worked on technical route design, dataset investigation, model reproduction, and experimental validation for a 2D digital human video generation foundation model, targeting talking-face, upper-body digital human, and stylized avatar generation.

### Agent-Based Multilingual MOOC Teaching Video Generation System
**Jan. 2026 – Mar. 2026**
Designed and implemented a multi-agent course video generation pipeline for smart education. The system supports PPT upload or course-topic input and automatically performs course structuring, translation verification, voice cloning, digital human generation, video composition, and subtitle export. Personal responsibilities include multilingual translation consistency checking, page-level timeline alignment, digital human layout avoidance, and WeChat mini-program features including task management, stage preview, and video/subtitle download.

<span class='anchor' id='service'></span>

# Academic Service

- **Organizer**, ACM Multimedia Asia 2025 Grand Challenge: Multimodal Multiethnic Talking-Head Video Generation. Contributed to task design, evaluation protocols, and submission rules based on DH-FaceVid-1K, covering lip synchronization, identity consistency, speaking-style controllability, and inference speed.
- **Reviewer** for TMM, Neurocomputing, Pattern Recognition, Knowledge-Based Systems, Neural Networks, ACM MM, AAAI, NeurIPS, CVPR, ICLR, and ICML.

# Skills

**Programming & Engineering:** Python, PyTorch, Linux, Git, Docker, LaTeX
**Research Workflow:** literature review, problem formulation, algorithm design, experiment validation, metric analysis, academic writing
**Deep Learning:** training, inference, debugging, hyperparameter tuning, experiment management
**AIGC Tools:** Claude Code, Codex, rapid prototyping, code refactoring, engineering implementation
**Languages:** Chinese, English

# Visitor Map

<p align="center">
  <a href="https://clustrmaps.com/site/1bxv5" title="Visitor Map">
    <img src="https://clustrmaps.com/map_v2.png?d=YOUR_KEY&cl=ffffff&w=900&t=tt" alt="Visitor map" />
  </a>
</p>
