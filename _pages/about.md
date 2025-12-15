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

I am currently a second-year doctoral candidate at the Multi-domain Intelligent Perception and Cognition Laboratory, School of Electronic and Information Engineering, Northwestern Polytechnical University. I am supervised by Professor Jiang Wen, Professor Deng Xinyang, and Professor Zhou Qianli. My research interests include **LLM Safety**, **Mechanism Interpretability**, and **Computer Vsion**.

# 📖 Educations
- *2024 – Fall 2028 (Expected)*, **Institute of Electronic and Information Engineering, Northwestern Polytechnical University**, Xian, ShanXi.
- *2021 – 2024*, **School of Information Engineering, Sichuan Agricultural University**, Ya'an, Sichuan.
- *2017 – 2021*, **School of Information Engineering, Sichuan Agricultural University**, Ya'an, Sichuan.

# 🎖 Honors and Awards
- *2023* Third-Class Academic Scholarship for Master's Students. 
- *2023* Excellence Award in Academic Presentation, Postgraduate Innovation and Design Competition on "Digital Agriculture and Intelligent Decision-Making".
- *2023* Champion of Men's Singles and Doubles, Postgraduate Table Tennis Competition.
- *2023* 5th Place, "The Ultimate Team" Table Tennis Competition, Sichuan Agricultural University. 
- *2023* 5th Place (Team), Inter-Campus Table Tennis League, Sichuan Agricultural University.
- *2022* First-Class Academic Scholarship for Master's Students. 
- *2021* 4th Place, Men's Singles, "Freshmen Cup" Table Tennis Competition, Sichuan Agricultural University.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Understanding and Mitigating Over-refusal for Large Language Models via Safety Representation**](https://arxiv.org/pdf/2511.19009)

**Junbo Zhang**, Ran Chen, Qianli Zhou, Xinyang Deng, Wen Jiang

we first analyze the causes of over-refusal from a representation perspective, revealing that over-refusal samples reside at the boundary between benign and malicious samples. Based on this, we propose MOSR, designed to mitigate over-refusal by intervening the safety representation of LLMs. MOSR incorporates two novel components: (1) Overlap-Aware Loss Weighting, which determines the erasure weight for malicious samples by quantifying their similarity to pseudo-malicious samples in the representation space, and (2) Context-Aware Augmentation, which supplements the necessary context for rejection decisions by adding harmful prefixes before rejection responses. Experiments demonstrate that our method outperforms existing approaches in mitigating overrefusal while largely maintaining safety. Overall, we advocate that future defense methods should strike a better balance between safety and over-refusal.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJRS 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unsupervised global-local domain adaptation with self-training for remote sensing image semantic segmentation**](https://www.tandfonline.com/doi/full/10.1080/01431161.2025.2450564)

**Junbo Zhang**, Zhiyong Li, Mantao Wang, Kunhong Li

We propose a hybrid training framework that integrates global-local adversarial training and self-training strategies to effectively tackle global-local domain shift. First, the adversarial approach measures the discrepancies between domains from domain and category-level perspectives. The adversarial network incorporates discriminators at the local-category and global-domain levels, thereby facilitating global-local feature alignment through multi-level adversarial training. Second, the self-training strategy is integrated to acquire domain-specific knowledge, effectively mitigating negative migration. By combining these two domain adaptation strategies, we present a more efficient approach for mitigating the domain gap. Finally, a self-labelling mechanism is introduced to directly explore the inherent distribution of pixels, allowing for the rectification of pseudo labels generated during the self-training stage. 

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RS 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unsupervised adversarial domain adaptation for agricultural land extraction of remote sensing images**](https://www.mdpi.com/2072-4292/14/24/6298)

**Junbo Zhang**, Shifeng Xu, Jun Sun, Dinghua Ou, Xiaobo Wu, Mantao Wang

we use an unsupervised adversarial domain adaptation method to train a neural network to close the gap between the source and target domains for unsupervised agricultural land extraction. The overall approach consists of two phases: inter-domain and intra-domain adaptation. In the inter-domain adaptation, we use a generative adversarial network (GAN) to reduce the inter-domain gap between the source domain (labeled dataset) and the target domain (unlabeled dataset). The transformer with robust long-range dependency modeling acts as the backbone of the generator. In addition, the multi-scale feature fusion (MSFF) module is designed in the generator to accommodate remote sensing datasets with different spatial resolutions. Further, we use an entropy-based approach to divide the target domain. The target domain is divided into two subdomains, easy split images and hard split images. By training against each other between the two subdomains, we reduce the intra-domain gap.

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RS 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Fusing spatial attention with spectral-channel attention mechanism for hyperspectral image classification via encoder–decoder networks**](https://www.mdpi.com/2072-4292/14/9/1968)

**Jun Sun**, **Junbo Zhang**, Xuesong Gao, Mantao Wang, Dinghua Ou, Xiaobo Wu, Dejun Zhang

We propose an encoder–decoder network that fuses spatial attention and spectral-channel attention for HSI classification from three public HSI datasets to tackle these issues. In terms of feature information fusion, a multi-source attention mechanism including spatial and spectral-channel attention is proposed to encode the spatial and spectral multi-channels contextual information. Moreover, three fusion strategies are proposed to effectively utilize spatial and spectral-channel attention. They are direct aggregation, aggregation on feature space, and Hadamard product. In terms of network development, an encoder–decoder framework is employed for hyperspectral image classification. The encoder is a hierarchical transformer pipeline that can extract long-range context information. Both shallow local features and rich global semantic information are encoded through hierarchical feature expressions. The decoder consists of suitable upsampling, skip connection, and convolution blocks, which fuse multi-scale features efficiently. 

</div></div>





