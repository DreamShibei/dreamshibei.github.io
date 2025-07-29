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

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

Hi there!

Welcome to Shibei Meng(孟诗蓓)'s website! I am a second-year M.S. student in Computer Science and Technology at Beijing Normal University, supervised by [Prof. Saihui Hou](https://housaihui.cn/) and [Prof. Yongzhen Huang](https://ai.bnu.edu.cn/xygk/szdw/zgj/bfed57e2f8fc4de2a6b370063517f801.htm). 

My research lies at the intersection of Computer Vision, Multimodal Large Language Models (MLLMs), and Video Understanding. 

Cooperation and discussion are welcomed. Feel free to drop me an email :)

# 🔥 News
# 🔥 News
- *2025.07*: &nbsp;🎉 [StreamGait \& MirrorGait]() is accepted by ACM MM'25!
- *2025.06*: &nbsp;🎉 [OmniDiff \& M<sup>3</sup>Diff](https://arxiv.org/abs/2503.11093) is accepted by ICCV'25! 
- *2025.06*: &nbsp;🎉 [FastPoseGait \& GPGait++](https://ieeexplore.ieee.org/abstract/document/11029177) is accepted by TPAMI'25! 
- *2024.07*: &nbsp;🎉 [GaitHeat](https://fq.pkwyx.com/default/https/www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04501.pdf) is accepted by ECCV'24! 
- *2023.07*: &nbsp;🎉 [GPGait](https://openaccess.thecvf.com/content/ICCV2023/papers/Fu_GPGait_Generalized_Pose-based_Gait_Recognition_ICCV_2023_paper.pdf) is accepted by ICCV'23! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/mirrorgait.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Seeing from Magic Mirror: Contrastive Learning from Reconstruction for Pose-based Gait Recognition]()

**Shibei Meng**, Saihui Hou, Yang Fu, Xuecai Hu, Junzhou Huang, and Yongzhen Huang

[[**Paper**]]() 
[[**Dataset**]](https://github.com/BNU-IVC/StreamGait) 
[[**Code**]](https://github.com/BNU-IVC/StreamGait) 
- **StreamGait**: A large-scale, unlabelled gait dataset collected from 353 YouTube live-stream channels across 30 countries / 81 cities.
- **MirrorGait**: A self-supervised 3D-aware pre-training framework that lifts 2D poses to 3D for contrastive learning, achieving SOTA on Gait3D, GREW and OUMVLP-Pose with minimal fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/gpgait++.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From FastPoseGait to GPGait++: Bridging the Past and Future for Pose-based Gait Recognition](https://ieeexplore.ieee.org/document/11029177)

**Shibei Meng**<sup>*</sup>, Yang Fu<sup>*</sup>, Saihui Hou, Xuecai Hu, Chunshui Cao, Xu Liu, and Yongzhen Huang

[[**Paper**]](https://ieeexplore.ieee.org/document/11029177) 
[[**Code**]](https://github.com/BNU-IVC/FastPoseGait) 
- **FastPoseGait**: We developed the FastPoseGait open-source toolbox and used it to establish a fairer, more consistent benchmark for gait recognition algorithms.
- **GPGait++**: We proposed GPGait++, a new method that significantly outperforms all prior pose-based work in challenging cross-domain scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/gpgait.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GPGait: Generalized Pose-based Gait Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Fu_GPGait_Generalized_Pose-based_Gait_Recognition_ICCV_2023_paper.pdf)

Yang Fu<sup>*</sup>, **Shibei Meng**<sup>*</sup>, Saihui Hou, Xuecai Hu, and Yongzhen Huang

[[**Paper**]](https://openaccess.thecvf.com/content/ICCV2023/papers/Fu_GPGait_Generalized_Pose-based_Gait_Recognition_ICCV_2023_paper.pdf) 
[[**Code**]](https://github.com/BNU-IVC/FastPoseGait) 

We introduce GPGait, a framework designed to improve the generalization of pose-based gait recognition across different datasets. To achieve this, it first uses a Human-Oriented Transformation (HOT) to create a unified and feature-rich pose representation. Then, it employs a Part-Aware Graph Convolutional Network (PAGCN) to effectively extract local and global spatial features from the keypoints, making the model more robust and effective in diverse scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/omnidiff.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniDiff: A Comprehensive Benchmark for Fine-grained Image Difference Captioning](https://arxiv.org/abs/2503.11093)

Yuan Liu, Saihui Hou, Saijie Hou, Jiabao Du, **Shibei Meng**, and Yongzhen Huang

[[**Paper**]](https://arxiv.org/abs/2503.11093) 

- **OmniDiff**: We construct OmniDiff, a high-quality dataset comprising 324 diverse scenarios, encompassing both real-world complex environments and 3D synthetic settings. 
- **M<sup>3</sup>Diff**: We integrate a plug-and-play Multi-scale Differential Perception (MDP) Module into the MLLM architecture, establishing a strong base model specifically tailored for IDC.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/gaitheat.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cut out the Middleman: Revisiting Pose-based Gait Recognition](https://fq.pkwyx.com/default/https/www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04501.pdf)

Yang Fu, Saihui Hou, **Shibei Meng**, Xuecai Hu, Chunshui Cao, Xu Liu, and Yongzhen Huang

[[**Paper**]](https://fq.pkwyx.com/default/https/www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04501.pdf) 
[[**Code**]](https://github.com/BNU-IVC/FastPoseGait) 

We introduce a new method for gait recognition using heatmaps directly from upstream methods as the primary representation, instead of the more traditional skeletons. It also identifies the key challenges associated with using heatmaps and provides a simple yet non-trivial solution to overcome them.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->



# 📖 Educations
- *2023.09 - (now)*, M.Eng. in Computer Science and Technology, School of Artificial Intelligence, Beijing Normal University. 
- *2019.09 - 2023.07*, B.Eng. in Computer Science and Technology, School of Artificial Intelligence, Beijing Normal University. 

# 🎖 Honors and Awards
- First Prize in ACM MM'24 Multimodal Gait Recognition Challenge (Pose Track), 2024.
- Outstanding Undergraduate of Beijing Normal University, 2023.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->