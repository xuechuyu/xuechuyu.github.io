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

# About me
I am a first-year PhD student from Center for Research in Computer Vision, University of Central Florida (UCF), supervised by [Dr. Chen Chen](https://www.crcv.ucf.edu/chenchen/index.html). 

My current research focuses on generative model (mainly on diffusion model now), such as, text to image generation, image restoration. Before joining UCF, I have spent three years working with 
[Dr. Ziming Zhang](https://zhang-vislab.github.io/) at Worcester Polytechnic Institute, and obtained the Master degree of Electrical and Computer Engineering.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/HyperCD.png' alt="HyperCD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hyperbolic Chamfer Distance for Point Cloud Completion.](https://openaccess.thecvf.com/content/ICCV2023/papers/Lin_Hyperbolic_Chamfer_Distance_for_Point_Cloud_Completion_ICCV_2023_paper.pdf) ICCV 2023

Fangzhou Lin, Yun Yue, Songlin Hou, **Xuechu Yu**, Yajun Xu, Kazunori D Yamada, Ziming Zhang

- Apply Chamfer distance in Hyperbolic space to deal with outlier sensibility for Point Cloud Completion.
- Experimental results show this new method can get the state-of-the-art performance on the benchmark datasets, i.e.
PCN, ShapeNet-55, and ShapeNet-34.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/SuperInfo.png' alt="SuperInfo" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Leveraging Superfluous Information in Contrastive Representation Learning.](https://arxiv.org/abs/2408.10292) arXiv 2024

**Xuechu Yu**, Fangzhou Lin, Yun Yue, Ziming Zhang

- Conjecture that the learned representations by contrastive learning not only maintain task-relevant information but also carry task-irrelevant information and design a new robust contrastive loss to eliminate this superfluous information.
- The new loss can often outperform the traditional contrastive learning approaches on image classification, object detection and instance segmentation tasks.
</div>
</div>


# 🎖 Honors and Awards
- UCF Graduate Artificial Intelligence Initiative Fellowship. 2024.
- China National Scholarship. 2015.
- China National Inspirational Scholarship. 2014.

# 📖 Educations
- *2024.09 - Now*, Ph.D., Computer Science, University of Central Florida.
- *2021.09 - 2024.05*, Master, Electrical and Computer Engineering, Worcester Polytechnic Institute.
- *2017.09 - 2020.06*, Master, Electrical Engineering , Huazhong University of Science and Technology.
- *2013.09 - 2017.06*, Bachelar, Electrical Engineering , Southwest Jiaotong University.
