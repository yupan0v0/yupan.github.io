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

<!-- Yu Pan -->
I am currently a Ph.D. student in the School of Information Science and Electrical Engineering at Kyushu University, working under the supervision of Prof. [Jianjun Zhao](https://stap.ait.kyushu-u.ac.jp/~zhao/index.html) and Prof. [Lei Ma](https://www.malei.org/). Prior to this, I received my Master's degree from Beijing Institute of Technology and Bachelor's degree from Northeastern University in China.


My research interests primarily focus on the modeling of speech processing systems, including speech synthesis, voice conversion, speech recognition, speech emotion recognition. Besides, I am also interested in the Software Engineering (SE) support for complex AI-based systems (quality assurance for AI).


# 🔍 Research Area
**Speech Processing**: Speech Recognition, Speech Emotion Generation, Voice Conversion, Speech Generation

**Large Language Models**: Speech Tokenizer, Speech LLMs, Diffusion Models

**Software Engineering**: Software Testing, Analysis, and Repair



# 📝 Publications (⭐ denotes equal contribution.)

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->



2025:
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ACL 2025</span> 
Takin-VC: Zero-shot Voice Conversion via Jointly Hybrid Content and Memory-Augmented Context-Aware Timbre Modeling. Y Yang<sup>⭐</sup>, **Y Pan<sup>⭐</sup>**, J Yao<sup>⭐</sup>, X Zhang<sup>⭐</sup>, J Ye, H Zhou, L Xie, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2410.01350)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">AAAI 2025</span> StableVC: Style Controllable Zero-Shot Voice Conversion with Conditional Flow Matching. J Yao, Y Yang, **Y Pan**, Z Ning, J Ye, H Zhou, L Xie. [[PDF]](https://arxiv.org/abs/2412.04724)



2024:
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> GEmo-CLAP: Gender-Attribute-Enhanced Contrastive Language-Audio Pretraining for Accurate Speech Emotion Recognition. **Y Pan**, Y Hu, Y Yang, W Fei, J Yao, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2306.07848)
  
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE SLT 2024</span> GMP-TL: Gender-augmented Multi-scale Pseudo-label Enhanced Transfer Learning for Speech Emotion Recognition. **Y Pan<sup>⭐</sup>**, Y Yang<sup>⭐</sup>, Y Huang, T Jin, J Yin, Y Hu, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/abs/2405.02151) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> PromptVC: Flexible stylistic voice conversion in latent space driven by natural language prompts. J Yao, Y Yang, Y Lei, Z Ning, Y Hu, **Y Pan**, J Yin, H Zhou, H Lu, L Xie. [[PDF]](https://arxiv.org/pdf/2309.09262)  [[DemoPage]](https://yaoxunji.github.io/prompt_vc/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">DCC 2024</span> Initialization Seeds Facilitating Neural Network Quantization. W Fei, L Ding, **Y Pan**, W Dai, C Li, J Zou, H Xiong. [[PDF]](https://ieeexplore.ieee.org/abstract/document/10533810)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP</span> 
Musa: Multi-lingual speaker anonymization via serial disentanglement. J Yao, Q Wang, P Guo, Z Ning, Y Yang, **Y Pan**, L Xie. [[PDF]](https://arxiv.org/pdf/2407.11629)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Arixv 2024 (Technical report)</span> 
Takin: A Cohort of Superior Quality Zero-shot Speech Generation Models. [[PDF]](https://arxiv.org/pdf/2409.12139)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Arixv 2024</span> CTEFM-VC: Zero-Shot Voice Conversion Based on Content-Aware Timbre Ensemble Modeling and Flow Matching. **Y Pan**, Y Yang, J Yao, J Ye, H Zhou, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2411.02026)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Arixv 2024</span> 
PromptCodec: High-Fidelity Neural Speech Codec using Disentangled Representation Learning based Adaptive Feature-aware Prompt Encoders. **Y Pan**, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2404.02702)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Arixv 2024</span> 
DPGAN: A Dual-Path Generative Adversarial Network for Missing Data Imputation in Graphs. X Zheng, Y Wu, **Y Pan**, W Lin, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2404.17164)



2023:
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span> Hybridformer: Improving Squeezeformer with Hybrid Attention and NSR Mechanism. Y Yang<sup>⭐</sup>, **Y Pan**<sup>⭐</sup>, J Yin, J Han, L Ma, H Lu. [[PDF]](https://ieeexplore.ieee.org/abstract/document/10096467)
  
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">SMAC 2023</span> Exploring the power of cross-contextual large language model in mimic emotion prediction. G Yi, Y Yang, **Y Pan**, Y Cao, J Yao, X Lv, C Fan, Z Lv, J Tao, S Liang, H Lu. [[PDF]](https://dl.acm.org/doi/10.1145/3606039.3613109) 


- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Arixv 2023</span> 
MSAC: Multiple Speech Attribute Control Method for Reliable Speech Emotion Recognition. **Y Pan**, Y Yang, Y Huang, J Yin, Y Hu, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2308.04025)




<!--
# 💻 Internships
- *2022.12 - *, Everest Team - Ximalaya, China.
-->

# 💻 Competitions
*2023.10* The 1st place winner in the 4th Multimodal Sentiment Analysis Challenge and Workshop (MuSe) Mimic Sub-challenge 2023 @ ACM MM. 



Thanks for the template of [acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io)

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=m3bxB5AtfyzWsAE07t3xgXcTY-tytE-8I-82gax8q4Y&cl=ffffff&w=a"></script>
