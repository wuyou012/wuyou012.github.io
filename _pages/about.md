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

Hi, I'm Zongqi He, currently a final year undergraduate student from [Department of Electrical and Electronic Engineering](https://www.polyu.edu.hk/en/eee/), [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/). 
I am very fortunate to be advised by [Prof. Kenneth K. M. Lam](https://www.eie.polyu.edu.hk/~enkmlam/). 

My research interest includes computer vision, deep learning , low-level vision and 3D reconstruction.

Here is my [CV](../assets/CV_Zongqi_He.pdf) and [transcripts](../assets/Transcript_Zongqi_He.pdf).


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 Our team has submitted two papers to **ACM MM 2025**, where I contributed as first author on one and co-first author on the other.
- *2025.03*: &nbsp;🎉🎉 Our team ranked among the top in three NTIRE 2025 Challenges.
- *2025.01*: &nbsp;🎉🎉 Our paper on enhancing Sparse input 3D Gaussian splatting for novel view synthesis is submitted to IEEE Transactions on Visualization and Computer Graphics **(TVCG)**.
- *2025.01*: &nbsp;🎉🎉 Our paper See In Detail: Enhancing Sparse-view 3D Gaussian Splatting with Local Depth and Semantic Regularization has been accepted by [International Conference on Acoustics, Speech, and Signal Processin **(ICASSP)**](https://2025.ieeeicassp.org/) 2025.
- *2024.10*: &nbsp;🎉🎉 Our paper MFGan: OCT Image Super-resolution and Enhancement with Blind Degradation and Multi-frame Fusing is accpeted by [International Workshop on Advanced Image Technology (IWAIT)](https://iwait.online/) 2025.
- *2024.10*: &nbsp;🎉🎉 Our paper A Multi-Perceptual Learning Network for Retina OCT Image Denoising and Classification is accpeted by [Asia-Pacific Signal and Information Processing Association (APSIPA)](https://www.apsipa.org/) 2024.

# 🚧 Ongoing Projects
* Gaussian Avatar: Developing a dynamic avatar system using 3D Gaussian Splatting to enable expressive and real-time human rendering.
* Novel View Synthesis: Enhancing Sparse-view Gaussian Splatting with Multi-view Consistent Diffusion for 360° Novel View Synthesis from Unposed Viewpoints.
* Test Time Scaling: Exploring test-time scaling strategies within cutting-edge text-to-image generation frameworks.

# 📝 Publications 
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

# 💻 Project Experience
* **UV prediction using GNN**
  * I am working as a student assistant under Prof. Mengying Li, focusing on UV index prediction around Hong Kong using Graph Neural Networks (GNNs).
* **Enhancing Sparse-view 3D Gaussian Splatting**
  * We proposed a novel 3D Gaussian Splatting method, SIDGaussian, for novel view synthesis under extremely sparse input conditions. We designed a semantic regularization and local depth regularization.
    * 📝 This work has been accepted by ICASSP 2025.
  * After that, we explored the potential of leveraging diffusion models to enhance sparse-view 3DGS.
    * Our paper has been submitted to ACM MM 2025.
* **Medical Image Analysis**
  * Built a novel visual odometry pipeline for colonoscopic navigation, achieving robust depth and pose estimation under illumination shifts.
    * Our paper has been submitted to ACM MM 2025.
* **Retina OCT Image Denoising and Classification**
  * Proposed the FD Loss into the GAN architecture, which helps preserve the structural integrity of OCT images
    during denoising. 
    * 📝 This work has been accepted by APSIPA 2024.

# 📖 Educations
- *2021.09 - 2025.06 (now)*, The Hong Kong Polytechnic University. 

<!-- # ✈️ Travel around
I love exploring different cultures, landscapes, and lifestyles through travel. So far, I have been to
<span>&#127469;&#127472;</span> <span>&#127474;&#127476;</span> <span>&#127472;&#127475;</span> <span>&#127462;&#127482;</span> <span>&#127471;&#127477;</span> -->

# 💻 Internships
- *2022.06 - 2022.08*, [Plaper (HK) Limited](https://plaper.hk/), Hong Kong.


<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=Sssn3K3IJ1S4fFkzB4icCb_L9ZJLePypFcOc6h1i6MA&cl=ffffff&w=a"></script> -->
