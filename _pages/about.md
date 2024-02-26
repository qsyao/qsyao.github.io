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
# About Me

- I am a final-year PhD student in the Institute of Computing Technology [(ICT)](http://english.ict.cas.cn/), Chinese Academic of Science (CAS), advised by [Prof. S. Kevin Zhou](https://sz.ustc.edu.cn/en/en_research_show/42.html). 
- I obtained my B.E. in School of the Gifted Young ([SCGY](https://en.scgy.ustc.edu.cn/), 少年班学院, honors college) from the University of Science and Technology of China [(USTC)](https://en.ustc.edu.cn/) in 2019. 
- I gained valuable internship experience in 2019 at Microsoft Research Asia [(MSRA)](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) under the mentorship of [Jilong Xue](https://www.microsoft.com/en-us/research/people/jxue/). This was followed by internships at [Tencent Jarvis Lab](https://jarvislab.tencent.com/index-en.html) supervised by [Dr. Yefeng Zheng](https://sites.google.com/site/yefengzheng/), and at Z2sky.ai with [Prof. S. Kevin Zhou]((https://sz.ustc.edu.cn/en/en_research_show/42.html)) as my adviser.

My research lies at developing secure and label-efficient medical image analysis algorithms with AI to achieve cost-efficient-yet-reliable medical decision-making, with the recent focus on 1) learning under severely scarce labeled data, e.g., one-shot medical landmark detection and segmentation. 2) learning without any labeled data, e.g., anomaly detection and zero-shot classification, 3) adversarial attack and defense on medical diagnosis network, 4) universal medical landmark detection & segmentation. 

# 🔥 News
- *2024.3*: &nbsp; One papers accepted to CVPR-24.
- *2024.2*: &nbsp; Two papers accepted to ISBI-24.
- *2023.11*: &nbsp; One paper accepted to TMI.
- *2023.10*: &nbsp; Glad to be awarded as a IEEE TMI Distinguished Reviewer
- *2023.9*: &nbsp; [BMPLE dataset](https://github.com/MIRACLE-Center/Oneshot_landmark_detection) is now available!
- *2023.5*: &nbsp; Two papers accepted to MICCAI-23
- *2022.6*: &nbsp; One paper accepted to MICCAI-22
- *2022.2*: &nbsp; One paper accepted to CVPR-22
- *2021.8*: &nbsp; Glad to receive MICCAI-21 Student Travel Award 
- *2021.5*: &nbsp; Three papers accepted to MICCAI-21.
- *2021.1*: &nbsp; One paper accepted to TMI.
- *2020.6*: &nbsp; One paper accepted to MICCAI-20.

# 📝 Publications 

### One-shot landmark detection

- ``MICCAI 2021``[One-shot medical landmark detection](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_17), **Qingsong Yao**, Quan Quan, Li Xiao, S. Kevin Zhou (early accepted, rank 47/1800) [[code]](https://github.com/MIRACLE-Center/Oneshot_landmark_detection)
- ``CVPR 2022`` [Which images to label for few-shot medical landmark detection?](https://openaccess.thecvf.com/content/CVPR2022/papers/Quan_Which_Images_To_Label_for_Few-Shot_Medical_Landmark_Detection_CVPR_2022_paper.pdf), Quan Quan\*,  **Qingsong Yao\***, Jun Li, S. Kevin Zhou [[code]](https://github.com/MIRACLE-Center/Oneshot_landmark_detection)
- ``MICCAI 2023`` [UOD: Universal One-Shot Detection of Anatomical Landmarks](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_3) Heqin Zhu, Quan Quan,  **Qingsong Yao**, Zaiyi Liu, S. Kevin Zhou [[code]](https://github.com/heqin-zhu/UOD_universal_oneshot_detection)
- ``TMI in major revision`` Information-guided unsupervised augmentation: Pixel-wise contrastive learning for medical image analysis, Quan Quan\*,  **Qingsong Yao\***, Heqin Zhu, S. Kevin Zhou
- ``MIA in major revision`` Which images to label for few-shot medical image analysis, Quan Quan\*,  **Qingsong Yao\***, Heqin Zhu, S. Kevin Zhou

### Anomaly Detection
- ``TMI 2021`` [Label-free segmentation of COVID-19 lesions in lung CT](https://ieeexplore.ieee.org/abstract/document/9385788/), **Qingsong Yao**, Li Xiao, Peihang Liu, S. Kevin Zhou

### Adversarial attacks and defenses
- ``ISBI 2024`` [Nowhere to hide: Toward robust reactive medical adversarial defense](https://arxiv.org/abs/2111.10969), **Qingsong Yao**, Zecheng He, Xiaodong Yu, S. Kevin Zhou
- ``TMI 2023``[Adversarial Medical Image with Hierarchical Feature Hiding](https://ieeexplore.ieee.org/abstract/document/10328635), **Qingsong Yao**, Zecheng He, Yuexiang Li, Yi Lin, Kai Ma, Yefeng Zheng, S. Kevin Zhou  [[code]](https://github.com/MIRACLE-Center/Hierarchical_Feature_Constraint)
- ``MICCAI 2021`` [A Hierarchical Feature Constraint to Camouflage Medical Adversarial Attacks](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_4), **Qingsong Yao**, Zecheng He, Yi Lin, Kai Ma, Yefeng Zheng, S. Kevin Zhou (early accepted, rank 9/1800)
- ``MICCAI 2020`` [Miss the point: Targeted adversarial attack on multiple landmark detection](https://link.springer.com/chapter/10.1007/978-3-030-59719-1_67), **Qingsong Yao**, Zecheng He, Hu Han, S. Kevin Zhou [[code]](https://github.com/qsyao/attack_landmark_detection)

### Universal learning
- ``MICCAI 2019`` [3D U^2-Net: A 3D Universal U-Net for Multi-domain Medical Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-030-32245-8_33), Chao Huang, Hu Han, **Qingsong Yao**, Shankun Zhu, S. Kevin Zhou [[code]](https://github.com/huangmozhilv/u2net_torch/)
- ``MICCAI 2021`` [You only Learn Once: Universal Anatomical Landmark Detection](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_9), Heqin Zhu, **Qingsong Yao**, Li Xiao, S. Kevin Zhou [[code]](https://github.com/ICT-MIRACLE-lab/YOLO_Universal_Anatomical_Landmark_Detection)

### Medical Vision-Language Pre-training
- ``CVPR 2024`` Haoran Lai*, **Qingsong Yao\***, Zihang Jiang, Rongsheng Wang, Zhiyang He, Xiaodong Tao, S Kevin Zhou, CARZero: Cross-Attention Alignment for Radiology Zero-Shot Classification

### Others
- ``ISBI 2024`` Long-tailed multi-label classification with noisy label of thoracic diseases from chest X-ray, Haoran Lai, **Qingsong Yao**, Zhiyang He, Xiaodong Tao, S. Kevin Zhou
- ``MICCAI 2022`` [Rib Suppression in Digital Chest Tomosynthesis](https://link.springer.com/chapter/10.1007/978-3-031-16431-6_66) Yihua Sun, **Qingsong Yao**, Yuanyuan Lyu, Jianji Wang, Yi Xiao, Hongen Liao, S. Kevin Zhou [[code]](https://github.com/sunyh1/Rib-Suppression-in-Digital-Chest-Tomosynthesis)
- ``MICCAI 2023`` [FairAdaBN: Mitigating unfairness with adaptive batch normalization and its application to dermatological disease classification](https://arxiv.org/abs/2303.08325), Zikang Xu, Shang Zhao, Quan Quan, **Qingsong Yao**, S. Kevin Zhou


# 🎖 Honors and Awards
- *2021.10* MICCAI Student travel award, 2021. 
- *2020-2022* Academic First Class Scholarship in ICT, CAS
- *2020-2022* Merit Student in ICT, CAS 

# 📖 Educations
- *2019.06 - (now)*, Ph.D, Institute of Computing Technology, Chinese Academic of Science, Beijing
- *2015.09 - 2019.06*, Undergraduate, School of the Gifted Young, University of Science and Technology of China, Hefei 

# 💬 Professional Services
*Jornel Reviewers:* 
- IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
- IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
- IEEE Transactions on Medical Imaging (TMI Distinguished Reviewer) 
- Medical Imaging Analysis (MIA)
- Pattern Recognition (PR)
- IEEE Journal of Biomedical and Health Informatics (JBHI)

*Conference Reviewers:* 
- Computer Vision and Pattern Recognition (CVPR)-22.24
- European Conference on Computer Vision (ECCV)-22,24
- International Conference on Computer Vision (ICCV)-21,23
- International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)-21-24
- Winter Conference on Applications of Computer Vision (WACV)-23

# Developed Tools
CUDA Spatial DeformCUDA toolkits for 3D/2D image spatial deformation, 45X faster than CPU. [link](https://github.com/qsyao/cuda_spatial_deform)

# 💻 Internships
- *2021.3 - 2021.12*, Z2sky.ai, Suchoow, China
- *2020.6 - 2020.12*, [Tencent Jarvis Lab](https://jarvislab.tencent.com/index-en.html), Shenzhen, China
- *2018.08 - 2019.7*, [Microsoft Research Asia (MSRA)](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia) system group, Beijing, China.
