---
permalink: /
title: "He Feng"
excerpt: "Ph.D. Student at Harbin Institute of Technology"
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

# 👋 About me

- I am a direct Ph.D. student in Electronic Information at [Harbin Institute of Technology (HIT)](https://www.hit.edu.cn/), advised by Prof. [Tonghua Su](http://www.hit.edu.cn/). I expect to graduate in Jun. 2029.
- I received my Bachelor's Degree in Software Engineering at [Central South University](https://en.csu.edu.cn/) in Jun. 2024.
- My [research](#current-research) focuses on **agent memory** and **recursive self-improvement (RSI)** in **multi-agent systems (MAS)**. I also work on generating **digital human videos with physiologically plausible motion**.
- I am actively **seeking research discussion and collaboration opportunities**, so feel free to contact me!

<a href='https://scholar.google.com/citations?user=_Xik6HkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2026.10*: &nbsp;🏅 Selected for the **National Scholarship for Doctoral Students** at Harbin Institute of Technology.
- *2026.09*: &nbsp;🎉🎉 Our paper "DH-OmniFace" has been accepted with mandatory minor revisions by [IEEE Transactions on Multimedia](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6046). (<span style="color:red">CCF-A, First Author</span>)
- *2026.07*: &nbsp;🎉🎉 Our paper "CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning" has been accepted by [ACM MM 2026](https://acmmm2026.org/). (<span style="color:red">CCF-A, First Author</span>)
- *2026.05*: &nbsp;🎉🎉 Our paper "DiTalker: A unified DiT-based framework for high-quality and style-controllable portrait animation" was accepted by [Computer Vision and Image Understanding](https://doi.org/10.1016/j.cviu.2026.104819). (<span style="color:red">CCF-B, First Author</span>)
- *2025.12*: &nbsp;🎉🎉 Served as an **organizer** for the ACM Multimedia Asia 2025 Grand Challenge on [Multimodal Multiethnic Talking-Head Video Generation](https://mmasia2025.org/multimodal_multiethnic).
- *2025.06*: &nbsp;🎉🎉 Our paper "DH-FaceVid-1K: A Large-Scale High-Quality Dataset for Face Video Generation" has been accepted by [ICCV 2025](https://iccv2025.thecvf.com/). (<span style="color:red">CCF-A, Second Author</span>)
- *2024.07*: &nbsp;💼 Started Algorithm Internship at **Digital Human Group, Li Auto**.

<span class='anchor' id='publications'></span>

# 📝 Publications

#### 2026

<div class="publication-list" markdown="0">
  <article class="publication-entry" id="cogportrait">
    <a class="publication-figure" href="{{ '/images/publications/cogportrait-framework.webp' | relative_url }}">
      <img src="{{ '/images/publications/cogportrait-framework.webp' | relative_url }}" width="2100" height="870" alt="CogPortrait framework for facial keypoint planning and keypoint-guided video generation" loading="lazy" decoding="async">
    </a>
    <div>
      <h3>CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning</h3>
      <p><strong>He Feng</strong>, Yongjia Ma, Donglin Di, Lei Fan, Tonghua Su</p>
      <p class="publication-venue">ACM Multimedia 2026 · CCF-A</p>
      <p class="publication-links"><a href="https://arxiv.org/abs/2605.28056">arXiv</a><a href="https://fenghe12.github.io/cogportrait-io/">Project</a></p>
    </div>
  </article>
  <article class="publication-entry" id="ditalker">
    <a class="publication-figure" href="{{ '/images/publications/ditalker-framework.webp' | relative_url }}">
      <img src="{{ '/images/publications/ditalker-framework.webp' | relative_url }}" width="2001" height="790" alt="DiTalker training and inference framework with style-expression encoding and audio-style fusion" loading="lazy" decoding="async">
    </a>
    <div>
      <h3>DiTalker: A unified DiT-based framework for high-quality and style-controllable portrait animation</h3>
      <p><strong>He Feng</strong>, Yongjia Ma, Lei Fan, Donglin Di, Tonghua Su</p>
      <p class="publication-venue">Computer Vision and Image Understanding, 2026 · CCF-B</p>
      <p class="publication-links"><a href="https://doi.org/10.1016/j.cviu.2026.104819">Paper</a><a href="https://arxiv.org/abs/2508.06511">arXiv</a><a href="https://github.com/fenghe12/DiTalker-CVIU">Code</a></p>
    </div>
  </article>
  <article class="publication-entry" id="dh-omniface">
    <a class="publication-figure" href="{{ '/images/publications/dh-omniface.webp' | relative_url }}">
      <img src="{{ '/images/publications/dh-omniface.webp' | relative_url }}" width="2000" height="1015" alt="DH-OmniFace dataset overview with face and full-body subsets and the FACET benchmark" loading="lazy" decoding="async">
    </a>
    <div>
      <h3>DH-OmniFace: A Large-Scale and Multi-Attribute Dataset Suite for Controllable Face Video Generation</h3>
      <p><strong>He Feng</strong> et al.</p>
      <p class="publication-venue">IEEE Transactions on Multimedia · CCF-A</p>
      <p>Accepted with mandatory minor revisions (AQ)</p>
      <p class="publication-links"><a href="https://fenghe12.github.io/DH-OmniFace/">Project</a></p>
    </div>
  </article>
</div>

#### 2025

<div class="publication-list" markdown="0">
  <article class="publication-entry" id="dh-facevid-1k">
    <a class="publication-figure" href="{{ '/images/publications/dh-facevid-1k.webp' | relative_url }}">
      <img src="{{ '/images/publications/dh-facevid-1k.webp' | relative_url }}" width="1039" height="287" alt="DH-FaceVid-1K samples with accompanying audio and text annotations" loading="lazy" decoding="async">
    </a>
    <div>
      <h3>DH-FaceVid-1K: A Large-Scale High-Quality Dataset for Face Video Generation</h3>
      <p>Donglin Di, <strong>He Feng</strong>, Wenzhang Sun, Yongjia Ma, Hao Li, Wei Chen, Lei Fan, Tonghua Su, Xun Yang</p>
      <p class="publication-venue">ICCV 2025 · CCF-A</p>
      <p class="publication-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/html/Di_DH-FaceVid-1K_A_Large-Scale_High-Quality_Dataset_for_Face_Video_Generation_ICCV_2025_paper.html">Paper</a><a href="https://luna-ai-lab.github.io/DH-FaceVid-1K/">Project</a><a href="https://github.com/luna-ai-lab/DH-FaceVid-1K">Code</a><a href="https://huggingface.co/datasets/jjuik2014/DH-FaceVid-1K">Data</a></p>
    </div>
  </article>
</div>

#### Current Research

<div class="publication-list" markdown="0">
  <article class="publication-entry publication-entry--overview" id="tooneval">
    <div>
      <h3>ToonEval: A Diagnostic Benchmark for Cartoon Talking Portraits</h3>
      <p><strong>He Feng</strong><sup>*</sup>, Xiangyang Shi<sup>*</sup>, Yongjia Ma, Kun Wang, Haoxuan Ge, Ran Li, Tonghua Su <small>(* Equal contribution)</small></p>
      <p>ToonEval evaluates character design, rendering style, part depiction, temporal stability, and motion fidelity in generated cartoon talking portraits.</p>
    </div>
    <a class="publication-figure" href="{{ '/images/publications/tooneval-overview.webp' | relative_url }}">
      <img src="{{ '/images/publications/tooneval-overview.webp' | relative_url }}" width="2400" height="788" alt="ToonEval benchmark overview with cartoon styles and structured ground-truth annotations" loading="lazy" decoding="async">
    </a>
  </article>
  <article class="publication-entry publication-entry--overview" id="phyhoi-bench">
    <div>
      <h3>PhyHOI-Bench: Diagnosing Physical Plausibility in Third-Person Human-Object Interaction Video Generation</h3>
      <p><strong>He Feng</strong> (First Author)</p>
      <p>PhyHOI-Bench uses causal annotations to identify where generated human-object interactions depart from physically plausible behavior.</p>
    </div>
    <a class="publication-figure" href="{{ '/images/publications/phyhoi-bench.webp' | relative_url }}">
      <img src="{{ '/images/publications/phyhoi-bench.webp' | relative_url }}" width="2400" height="717" alt="PhyHOI-Bench overview of causal annotations and physical plausibility evaluation" loading="lazy" decoding="async">
    </a>
  </article>
</div>

#### Under Review
- ``TPAMI`` [Talking Face Video Generation Survey](), et al. (Contributor)

### 📜 Patents
- Two accepted internal invention patents on talking-face generation and digital human foundation models.
- *Method and System for Automatic Generation of Multilingual Educational Videos Based on Multi-Agent Collaboration* — Accepted.
- *Multi-language MOOC Teaching Video Automatic Generation System Based on Multi-Agent Collaboration* — Software Copyright.

<span class='anchor' id='educations'></span>

# 🎓 Educations
- *Sep. 2024 – Jun. 2029*, **Harbin Institute of Technology**, Direct Ph.D. in Electronic Information, Advisor: Prof. Tonghua Su
- *Sep. 2020 – Jun. 2024*, **Central South University**, B.Eng. in Software Engineering

<span class='anchor' id='internships'></span>
<span class='anchor' id='experience'></span>

# 💼 Internships

### Algorithm Intern · Advanced Computing Research Group
**[Spring Research Institute, China Electronics Corporation](https://www.cec.com.cn/2106.html) · Sep. 2026 – Present · Shenzhen, China**

### Algorithm Intern · Digital Human Group, Li Auto
**Jul. 2024 – Jan. 2025 · Beijing, China**

- Reproduced and evaluated 20+ talking-face generation models (SadTalker, AniPortrait, EMO, MuseV, VASA-1, MODA).
- Developed and evaluated OpenSora-Plan-based talking-face foundation models at 1B/3B/5B scales.
- Built a 1,000+ hour talking-face video database with MLLM-generated captions and multimodal annotations.
- Supported DH-FaceVid-1K and DH-OmniFace dataset construction.

<span class='anchor' id='projects'></span>

# 🛠️ Projects

### Digital Human Generation Foundation Model R&D
**Li Auto – University Joint Program · Jun. 2024 – Jan. 2025**

Technical route design, dataset investigation, model reproduction, and experimental validation for a 2D digital human video generation foundation model.

### Agent-Based Multilingual MOOC Teaching Video Generation System
**Jan. 2026 – Mar. 2026**

Multi-agent course video generation pipeline supporting PPT upload or course-topic input, with automatic course structuring, translation verification, voice cloning, digital human generation, video composition, and subtitle export.

<span class='anchor' id='honors-and-awards'></span>

# 🏆 Honors and Awards
- **National Scholarship for Doctoral Students**, Harbin Institute of Technology, 2026.
- **Organizer**, ACM Multimedia Asia 2025 Grand Challenge: Multimodal Multiethnic Talking-Head Video Generation.

<span class='anchor' id='academic-services'></span>

# 📚 Academic Services
- **Journal reviewer:** IEEE Transactions on Multimedia (TMM), Neurocomputing, Pattern Recognition, Knowledge-Based Systems, Neural Networks, and Chinese Journal of Computers (计算机学报).
- **Conference reviewer:** ACM Multimedia (ACM MM), AAAI, NeurIPS, CVPR, ICLR, ICML, ICASSP, ICME, and the International Conference on Multimedia Modeling (MMM).

# 🛠️ Skills
- **Programming:** Python, PyTorch, Linux, Git, Docker, LaTeX
- **Research methods:** diffusion transformers, vision-language models, and benchmark design for video generation
- **Languages:** Chinese, English

# 🌍 Visitor Map

<div style="display:flex; flex-direction:column; align-items:center; gap:12px; margin:24px 0;">
<div style="font-size:200px; line-height:1;">🌍</div>
<div style="font-size:15px; color:#555;">
Thanks to <b><span id="busuanzi_value_site_uv">-</span></b> visitors from <b><span id="busuanzi_value_site_pv">-</span></b>+ views worldwide.
</div>
</div>
<script>
(function(){
  fetch('https://events.vercount.one/api/v2/log?url=' + encodeURIComponent(location.origin + '/'), {method:'GET'})
    .then(function(r){return r.json();})
    .then(function(d){
      if(d && d.data){
        var uv=document.getElementById('busuanzi_value_site_uv');
        var pv=document.getElementById('busuanzi_value_site_pv');
        if(uv) uv.textContent=d.data.site_uv;
        if(pv) pv.textContent=d.data.site_pv;
      }
    }).catch(function(){});
})();
</script>
