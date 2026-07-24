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

Hi, I'm Zongqi He. I received my Bachelor's degree from the [Department of Electrical and Electronic Engineering](https://www.polyu.edu.hk/en/eee/) at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/). I was very fortunate to be advised by [Prof. Kenneth K. M. Lam](https://www.eie.polyu.edu.hk/~enkmlam/) during my undergraduate studies.
I am now a Ph.D. student at [The University of Hong Kong](https://www.hku.hk/), advised by [Yifan (Evan) Peng](https://www.eee.hku.hk/~evanpeng/).

My research interests include computer vision, deep learning, low-level vision, and 3D/4D reconstruction.


# 🔥 News
- *2026.07*: &nbsp;🎉🎉 Our paper [Augmented Reality Integration Improves Ergonomics in Dynamic Navigation for Dental Implant Surgery](https://doi.org/10.1002/jsid.70061) received the **Distinguished Student Paper Award** at **SID 2026**.
- *2026.07*: &nbsp;🎉🎉 Our paper [SfM-free 3D Gaussian Splatting from Extremely Sparse View](https://doi.org/10.1016/j.cag.2026.104684) is now available online in **Computers & Graphics**.
- *2026.06*: &nbsp;🎉🎉 Our paper [PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://kelvar00.github.io/PhyGaP/) was selected as a **CVPR 2026 Oral** presentation.
- *2025.12*: &nbsp;🎉🎉 I joined **The University of Hong Kong (HKU)** as a Ph.D. student.
- 

# 🚧 Ongoing Projects
* **RestoreAvatars:** Developing a high-fidelity head-avatar reconstruction method that is robust to degraded facial sequences from old films.
* **ConsistNav:** Improving action consistency in zero-shot object navigation through semantic executive control.
* **Continuous-Time Gaussian Motion Adapters:** Adapting frozen dynamic-scene reconstruction models with continuous-time Gaussian motion representations.
* **Illumination-Aware Colonoscopic Visual Odometry:** Exploring self-supervised visual odometry for colonoscopy using illumination-aware 3D Gaussian splatting.
* **Generative Sparse-View Synthesis:** Investigating collaborative learning for sparse-view synthesis based on generative 3D Gaussian splatting.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Oral</div><img src='images/PhyGaP_pipeline.png' alt="PhyGaP pipeline" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://arxiv.org/abs/2603.14001) [[Project Page](https://kelvar00.github.io/PhyGaP/)]

Jiale Wu, Xiaoyang Bai, **Zongqi He**, Weiwei Xu, Yifan (Evan) Peng.
</div>

</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/PhysInOne_teaser.jpg' alt="PhysInOne teaser" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[PhysInOne: Visual Physics Learning and Reasoning in One Suite](https://arxiv.org/abs/2604.09415) [[Project Page](https://vlar-group.github.io/PhysInOne.html)]

Siyuan Zhou\*, Hejun Wang\*, Hu Cheng\*, Jinxi Li\*, DataTeam (including **Zongqi He**), et al.

</div>
</div>
<div class='paper-box paper-box-text-only'><div class='paper-box-text' markdown="1">

[Augmented Reality Integration Improves Ergonomics in Dynamic Navigation for Dental Implant Surgery](https://doi.org/10.1002/jsid.70061)

**🏆 Distinguished Student Paper Award**

Pui Hang Leung, Feng Wang, Zhenyang Li, **Zongqi He**, Yifan Peng, Wei-fa Yang.

*Journal of the Society for Information Display*, 34(5): 428-435, 2026.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computers &amp; Graphics 2026</div><img src='images/SfMfreeGS_pipeline.jpg' alt="SfM-free 3D Gaussian Splatting pipeline" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[SfM-free 3D Gaussian Splatting from Extremely Sparse View](https://doi.org/10.1016/j.cag.2026.104684)

**Zongqi He**, Hanmin Li, Kin-Chung Chan, Yushen Zuo, Hao Xie, Zhe Xiao, Jun Xiao, Xiaoyang Bai, Yifan Peng, Kin-Man Lam.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/SIDGS_pipe.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[See In Detail: Enhancing Sparse-view 3D Gaussian Splatting with Local Depth and Semantic Regularization](https://arxiv.org/abs/2501.11508)

**Zongqi He***, Zhe Xiao*, Kin-Chung Chan, Yushen Zuo, Jun Xiao, Kin-Man Lam.

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIM@ECCV 2024</div><img src='images/AIM2024.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[AIM 2024 Challenge on Efficient Video Super-Resolution for AV1 Compressed Content](https://arxiv.org/pdf/2409.17256)

Marcos V. Conde, Zhijun Lei, Wen Li, Christos Bampis, Ioannis Katsavounidis, Radu Timofte, **Zongqi He** et al.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIM@ECCV 2024</div><img src='images/AIM2024_ESNeRF.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[AIM 2024 Sparse Neural Rendering Challenge: Methods and Results](https://arxiv.org/abs/2409.15045)

Michal Nazarczuk, Sibi Catley-Chandar, Thomas Tanay, Richard Shaw, Eduardo Pérez-Pellitero, Radu Timofte, **Zongqi He** et al.

</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AI4VA@ECCV 2024</div><img src='images/MuvieCastONeSDiff_pipe.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [Towards Multi-View Consistent Style Transfer with One-Step Diffusion via Vision Conditioning](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->
Towards Multi-View Consistent Style Transfer with One-Step Diffusion via Vision Conditioning

Yushen Zuo, Jun Xiao, Kin-Chung Chan, Rongkang Dong, Cuixin Yang, **Zongqi He**, Hao Xie, Kin-Man Lam

</div>
</div>

# 🎖 Honors and Awards
- *2025.03* NTIRE 2025 Challenge on Night Photography Rendering - 5th place.
- *2025.03* NTIRE 2025 Challenge on Ambient Light Normalization - 6th place.
- *2025.03* NTIRE 2025 Challenge on Restore Any Image Model (RAIM) in the Wild - Track 1 - 3rd place.
- *2024.08* AIM 2024 Challenge on Sparse Neural Rendering - Track 1 - 3 views - 3rd place.
- *2024.08* AIM 2024 Challenge on Sparse Neural Rendering - Track 2 - 9 views - 3rd place.  
- *2024.08* AIM 2024 Challenge on Efficient Video Super-Resolution for AV1 Compressed Content - 2nd place. 
- *2022-2024* Dean’s Honours List (two years)
- *2023* HKSAR Government Talent Development Scholarship

# 📖 Educations
- *2021.09 - 2025.10*, The Hong Kong Polytechnic University. 
- *2025.12 - now*, The University of Hong Kong.

<!-- # ✈️ Travel around
I love exploring different cultures, landscapes, and lifestyles through travel. So far, I have been to
<span>&#127469;&#127472;</span> <span>&#127474;&#127476;</span> <span>&#127472;&#127475;</span> <span>&#127462;&#127482;</span> <span>&#127471;&#127477;</span> -->

# 💻 Internships
- *2022.06 - 2022.08*, [Plaper (HK) Limited](https://plaper.hk/), Hong Kong.


<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=Sssn3K3IJ1S4fFkzB4icCb_L9ZJLePypFcOc6h1i6MA&cl=ffffff&w=a"></script> -->
