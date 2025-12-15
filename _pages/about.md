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

I am currently a second-year doctoral candidate at the Multi-domain Intelligent Perception and Cognition Laboratory, School of Electronic and Information, Northwestern Polytechnical University. I am supervised by Professor [Wen Jiang](https://teacher.nwpu.edu.cn/jiangwen.html), Professor [Xinyang Deng](https://teacher.nwpu.edu.cn/2017010003.html), and Professor [Qianli Zhou](https://noah199711.github.io/). 
My research interests include：
 - **LLM Safety**
 - **Mechanism Interpretability**
 - **Computer Vsion**


# 📖 Educations
- *2024 – Fall 2028 (Expected)*, Institute of Electronic and Information, Northwestern Polytechnical University, Xian, ShanXi.
- *2021 – 2024*, School of Information Engineering, Sichuan Agricultural University, Ya'an, Sichuan.
- *2017 – 2021*, School of Information Engineering, Sichuan Agricultural University, Ya'an, Sichuan.

# 🎖 Honors and Awards
- *2023*: Third-Class Academic Scholarship for Master's Students. 
- *2023*: Excellence Award in Academic Presentation, Postgraduate Innovation and Design Competition on "Digital Agriculture and Intelligent Decision-Making".
- *2023*: Champion of Men's Singles and Doubles, Postgraduate Table Tennis Competition.
- *2023*: 5th Place, "The Ultimate Team" Table Tennis Competition, Sichuan Agricultural University. 
- *2023*: 5th Place (Team), Inter-Campus Table Tennis League, Sichuan Agricultural University.
- *2022*: First-Class Academic Scholarship for Master's Students. 
- *2021*: 4th Place, Men's Singles, "Freshmen Cup" Table Tennis Competition, Sichuan Agricultural University.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/method.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Understanding and Mitigating Over-refusal for Large Language Models via Safety Representation**](https://arxiv.org/pdf/2511.19009)

**Junbo Zhang**, Ran Chen, Qianli Zhou, Xinyang Deng, Wen Jiang

We analyze over-refusal in LLMs from a representation perspective, finding such samples lie at the boundary of benign and malicious ones. We propose MOSR with Overlap-Aware Loss Weighting and Context-Aware Augmentation to intervene safety representation. Experiments show we mitigate over-refusal while maintaining safety, offering insights for balancing model safety and over-refusal.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJRS 2025</div><img src='images/domain gap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unsupervised global-local domain adaptation with self-training for remote sensing image semantic segmentation**](https://www.tandfonline.com/doi/full/10.1080/01431161.2025.2450564)

**Junbo Zhang**, Zhiyong Li, Mantao Wang, Kunhong Li

We propose a hybrid framework integrating global-local adversarial training and self-training. We achieve feature alignment via multi-level discriminators, acquire domain-specific knowledge through self-training, and correct pseudo-labels with a self-labeling mechanism, effectively alleviating global-local domain shift for remote sensing image semantic segmentation.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RS 2022</div><img src='images/UDA-ag.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unsupervised adversarial domain adaptation for agricultural land extraction of remote sensing images**](https://www.mdpi.com/2072-4292/14/24/6298)

**Junbo Zhang**, Shifeng Xu, Jun Sun, Dinghua Ou, Xiaobo Wu, Mantao Wang

We adopt unsupervised adversarial domain adaptation for agricultural land extraction. We use Transformer as the generator backbone with a multi-scale feature fusion module, reduce source-target domain gap via GAN, and minimize intra-domain differences by dividing the target domain with an entropy-based method, enabling accurate unsupervised extraction.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RS 2022</div><img src='images/HSI.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Fusing spatial attention with spectral-channel attention mechanism for hyperspectral image classification via encoder–decoder networks**](https://www.mdpi.com/2072-4292/14/9/1968)

**Jun Sun**\*, **Junbo Zhang**\*, Xuesong Gao, Mantao Wang, Dinghua Ou, Xiaobo Wu, Dejun Zhang

We propose an encoder-decoder network fusing spatial and spectral-channel attention, with three fusion strategies to utilize dual attention. We use a hierarchical Transformer in the encoder to extract long-range context, and fuse multi-scale features via upsampling and skip connections in the decoder, improving hyperspectral image classification performance.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Plants 2023</div><img src='images/PLANTS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**YOLOv7-Plum: advancing plum fruit detection in natural environments with deep learning**](https://www.mdpi.com/2223-7747/12/15/2883)

Rong Tang, Yujie Lei, Beisiqi Luo, **Junbo Zhang**, Jiong Mu

We propose YOLOv7-Plum, an improved YOLOv7-based model for plum fruit detection. We construct a dataset of plums in natural environments, introduce CBAM attention, replace CSPSPP with CSPSPPF, and use bilinear interpolation for upsampling, enhancing detection efficiency and accuracy.

</div></div>

