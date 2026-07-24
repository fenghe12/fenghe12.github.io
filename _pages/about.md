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
- My research interests mainly focus on **digital human video generation**, **talking-head / portrait animation**, **DiT / diffusion models for video generation**, and **large-scale face video dataset construction**.
- I am actively **seeking research discussion and collaboration opportunities**, so feel free to contact me!

<a href='https://scholar.google.com/citations?user=_Xik6HkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Our paper "CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning" has been accepted by [ACM MM 2026]().
- *2026.05*: &nbsp;🎉🎉 Our paper "DiTalker: A Unified DiT-based Framework for High-Quality and Speaking Styles Controllable Portrait Animation" has been accepted by [CVIU 2026]().
- *2025.07*: &nbsp;🎉🎉 Our paper "DH-FaceVid-1K: A Large-Scale High-Quality Dataset for Face Video Generation" has been accepted by [ICCV 2025]().
- *2025.05*: &nbsp;🎉🎉 Our paper "DH-OmniFace: A Large-Scale and Multi-Attribute Dataset Suite for Controllable Face Video Generation" is under major revision at [IEEE TMM]().

# 📝 Publications

#### 2026
- ``ACM MM'26`` [CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning](), **He Feng**, et al. (<span style="color:red">CCF-A</span>, **First Author**)
- ``CVIU'26`` [DiTalker: A Unified DiT-based Framework for High-Quality and Speaking Styles Controllable Portrait Animation](), **He Feng**, et al. (<span style="color:red">CCF-B</span>, **First Author**)

#### 2025
- ``ICCV'25`` [DH-FaceVid-1K: A Large-Scale High-Quality Dataset for Face Video Generation](), et al. (<span style="color:red">CCF-A</span>, **Second Author**)

#### Under Review
- ``TMM`` [DH-OmniFace: A Large-Scale and Multi-Attribute Dataset Suite for Controllable Face Video Generation](), **He Feng**, et al. (<span style="color:red">CCF-A / JCR Q1</span>, **First Author**, Major Revision)
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

# 💼 Internships

### Algorithm Intern · Digital Human Group, Li Auto
**Jul. 2024 – Jan. 2025**

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
- **Organizer**, ACM Multimedia Asia 2025 Grand Challenge: Multimodal Multiethnic Talking-Head Video Generation.

<span class='anchor' id='academic-services'></span>

# 📚 Academic Services
- **Reviewer** for TMM, Neurocomputing, Pattern Recognition, Knowledge-Based Systems, Neural Networks, ACM MM, AAAI, NeurIPS, CVPR, ICLR, ICML.

# 🛠️ Skills
- **Programming:** Python, PyTorch, Linux, Git, Docker, LaTeX
- **Deep Learning:** training, inference, hyperparameter tuning, experiment management
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
