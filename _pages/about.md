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

# 👋 About Me

<!-- Yu Pan -->
Hello! I am PAN Yu (潘宇). I obtained my Ph.D. (early completion) from the School of Information Science and Electrical Engineering at Kyushu University, where I was truly fortunate to be advised by Prof. [Jianjun Zhao](https://stap.ait.kyushu-u.ac.jp/~zhao/index.html) and Prof. [Lei Ma](https://www.malei.org/). Prior to that, I received my Master's degree from Beijing Institute of Technology and my Bachelor's degree from Northeastern University, China.

My research journey began in computer vision: during my undergraduate and Master's studies, I worked on feature matching-based object tracking, and later on deep learning-based object detection and fine-grained recognition. During my Ph.D., my research shifted to **speech and language processing**, with a particular focus on expressive and controllable speech generation, spanning automatic speech recognition, speech emotion recognition, speech tokenization, voice conversion, text-to-speech synthesis, turn-taking detection, voice activity detection, and SpeechLLM-based speech-to-speech translation. Building on this cross-modal background, I am now particularly excited about **multimodal and audio-visual learning**. In addition, I am also interested in Software Engineering (SE) support for complex AI-based systems (quality assurance for AI).

I am always open to research discussions and collaborations — feel free to reach out! 😃


# 🔥 News

- *2026.05*: &nbsp;🎉 S2ST-Omni is accepted by **Findings of ACL 2026**!
- *2026.03*: &nbsp;🎓 I successfully defended my Ph.D. thesis at Kyushu University (early completion)!
- *2025.10*: &nbsp;🎉 CTEFM-VC is accepted by **IEEE Signal Processing Letters**!
- *2025.05*: &nbsp;🎉 ClapFM-EVC is accepted by **INTERSPEECH 2025** as an **Oral** presentation!
- *2025.05*: &nbsp;🎉 Takin-VC is accepted by **ACL 2025 (Main)** as an **Oral** presentation!


# 🎓 Experience

- **Kyushu University**, Fukuoka, Japan <span style="float:right; color:#888; font-size:14px;">2023.10 – 2026.03</span>  
Ph.D. in Information Science and Electrical Engineering
  - Early completion of the doctoral program in recognition of outstanding research achievements
  - Thesis: *A Study on High-Fidelity, Expressive, and Emotion-Controllable Voice Conversion*

- **University of Alberta**, Edmonton, Canada <span style="float:right; color:#888; font-size:14px;">2022.09 – 2023.09</span>  
Ph.D. in Electrical and Computer Engineering 

- **Beijing Institute of Technology**, Beijing, China <span style="float:right; color:#888; font-size:14px;">2018.09 – 2021.06</span>  
M.Sc. in Information and Signal Processing
  - Thesis: *Research on Object Detection and Fine-Grained Recognition*
  - GPA: 91.9/100 (Top 1%)

- **Northeastern University**, Shenyang, China <span style="float:right; color:#888; font-size:14px;">2014.09 – 2018.06</span>  
B.Eng. in Electronic and Information Engineering
  - Thesis: *Research on Object Tracking Algorithms Based on Feature Matching*
  - GPA: 89.4/100 (Top 5%)


# 🔍 Research Area

**🎙️ Generative**

- **Speech-to-Speech Translation (SpeechLLM)**: [arXiv'26](https://arxiv.org/pdf/2605.16026), S2ST-Omni ([ACL Findings'26](https://arxiv.org/abs/2506.11160))
- **Voice Conversion**:
  - *Zero-Shot Voice Conversion*: CTEFM-VC ([IEEE SPL'25](https://ieeexplore.ieee.org/document/11194707))
  - *Expressive Zero-Shot Voice Conversion*: Takin-VC ([ACL'25, Oral](https://aclanthology.org/2025.acl-long.87.pdf)), StableVC ([AAAI'25](https://arxiv.org/abs/2412.04724))
  - *Flexible and Interpretable Emotional Voice Conversion*: ClapFM-EVC ([INTERSPEECH'25, Oral](https://arxiv.org/pdf/2505.13805))
  - *Flexible and Interpretable Stylistic Voice Conversion*: PromptVC ([ICASSP'24](https://arxiv.org/pdf/2309.09262))
- **Speech Tokenization**: PSCodec/PromptCodec ([arXiv'24](https://arxiv.org/pdf/2404.02702))
- **Text-to-Speech Synthesis**: FPO ([IEEE TASLP'25](https://ieeexplore.ieee.org/abstract/document/11316389)), Takin ([arXiv'24, technical report](https://arxiv.org/pdf/2409.12139))
- **Speaker Anonymization**: MUSA ([IEEE TASLP'24](https://arxiv.org/pdf/2407.11629))

**🧠 Discriminative**

- **Automatic Speech Recognition**: HybridFormer ([ICASSP'23](https://ieeexplore.ieee.org/abstract/document/10096467)) — also serves as the content encoder for Takin-VC, CTEFM-VC, and ClapFM-EVC
- **Speech Emotion Recognition**: GEmo-CLAP ([ICASSP'24](https://arxiv.org/pdf/2306.07848), which also provides the emotional natural-language prompt control interface for ClapFM-EVC); GMP-TL ([SLT'24](https://arxiv.org/abs/2405.02151)); MSAC ([arXiv'23](https://arxiv.org/pdf/2308.04025)); MuSe'23 winning solution ([ACM MM Workshop'23](https://dl.acm.org/doi/10.1145/3606039.3613109)) — 🏆 1st place in the MuSe 2023 Mimic Sub-challenge @ ACM MM

**🔧 Others**

- **Neural Network Quantization**: [DCC'24](https://ieeexplore.ieee.org/abstract/document/10533810)
- **Audio-Driven Animation**: Takin-ADA ([arXiv'24](https://arxiv.org/pdf/2410.14283))
- **Graph Learning**: DPGAN ([arXiv'24](https://arxiv.org/pdf/2404.17164))


# 📝 Publications 

<span style="color:#888; font-size:14px;">(⭐ denotes equal contribution)</span>

2026:

- <span style="display:inline-block; background-color:#6c757d; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">arXiv</span> 
From Flat Language Labels to Typological Priors: Structured Language Conditioning for Multilingual Speech-to-Speech Translation. **Y Pan**, Y Hou, X Wu, L Zhang, Y Traon, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2605.16026)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">Findings of ACL 2026</span> 
S2ST-Omni: Hierarchical Language-Aware SpeechLLM Adaptation for Multilingual Speech-to-Speech Translation. **Y Pan**, X Wu, Y Yang, J Yao, M Cordy, L Ma, J Zhao. [[PDF]](https://arxiv.org/abs/2506.11160)

2025:

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">IEEE SPL 2025</span>
Zero-Shot Voice Conversion via Content-Aware Timbre Ensemble and Conditional Flow Matching. **Y Pan**, Y Yang, J Yao, L Ma, J Zhao. [[PDF]](https://ieeexplore.ieee.org/document/11194707)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">INTERSPEECH 2025 (Oral)</span> ClapFM-EVC: High-Fidelity and Flexible Emotional Voice Conversion with Dual Control from Natural Language and Speech. **Y Pan**, Y Hu, Y Yang, J Yao, J Ye, H Zhou, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2505.13805)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">ACL 2025 (Oral)</span> 
Takin-VC: Expressive Zero-Shot Voice Conversion via Adaptive Hybrid Content Encoding and Enhanced Timbre Modeling. Y Yang<sup>⭐</sup>, **Y Pan<sup>⭐</sup>**, J Yao<sup>⭐</sup>, X Zhang<sup>⭐</sup>, J Ye, H Zhou, L Xie, L Ma, J Zhao. [[PDF]](https://aclanthology.org/2025.acl-long.87.pdf)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">AAAI 2025</span> StableVC: Style Controllable Zero-Shot Voice Conversion with Conditional Flow Matching. J Yao, Y Yang, **Y Pan**, Z Ning, J Ye, H Zhou, L Xie. [[PDF]](https://arxiv.org/abs/2412.04724)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">IEEE TASLP 2025</span> 
Fine-grained Preference Optimization Improves Zero-shot Text-to-Speech. J Yao, Y Yang, Y Feng, **Y Pan**, Z Ning, J Ye, H Zhou, L Xie. [[PDF]](https://arxiv.org/pdf/2502.02950)


2024:

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">ICASSP 2024</span> GEmo-CLAP: Gender-Attribute-Enhanced Contrastive Language-Audio Pretraining for Accurate Speech Emotion Recognition. **Y Pan**, Y Hu, Y Yang, W Fei, J Yao, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2306.07848)
  
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">IEEE SLT 2024</span> GMP-TL: Gender-augmented Multi-scale Pseudo-label Enhanced Transfer Learning for Speech Emotion Recognition. **Y Pan<sup>⭐</sup>**, Y Yang<sup>⭐</sup>, Y Huang, T Jin, J Yin, Y Hu, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/abs/2405.02151) 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">ICASSP 2024</span> PromptVC: Flexible Stylistic Voice Conversion in Latent Space Driven by Natural Language Prompts. J Yao, Y Yang, Y Lei, Z Ning, Y Hu, **Y Pan**, J Yin, H Zhou, H Lu, L Xie. [[PDF]](https://arxiv.org/pdf/2309.09262)  [[DemoPage]](https://yaoxunji.github.io/prompt_vc/)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">DCC 2024</span> Initialization Seeds Facilitating Neural Network Quantization. W Fei, L Ding, **Y Pan**, W Dai, C Li, J Zou, H Xiong. [[PDF]](https://ieeexplore.ieee.org/abstract/document/10533810)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">IEEE TASLP 2024</span> 
MUSA: Multi-lingual Speaker Anonymization via Serial Disentanglement. J Yao, Q Wang, P Guo, Z Ning, Y Yang, **Y Pan**, L Xie. [[PDF]](https://arxiv.org/pdf/2407.11629)

- <span style="display:inline-block; background-color:#6c757d; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">arXiv 2024 (Technical Report)</span> 
Takin: A Cohort of Superior Quality Zero-shot Speech Generation Models. [[PDF]](https://arxiv.org/pdf/2409.12139)

- <span style="display:inline-block; background-color:#6c757d; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">arXiv 2024</span> 
PromptCodec: High-Fidelity Neural Speech Codec using Disentangled Representation Learning based Adaptive Feature-aware Prompt Encoders. **Y Pan**, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2404.02702)

- <span style="display:inline-block; background-color:#6c757d; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">arXiv 2024</span> 
DPGAN: A Dual-Path Generative Adversarial Network for Missing Data Imputation in Graphs. X Zheng, Y Wu, **Y Pan**, W Lin, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2404.17164)


2023:

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">ICASSP 2023</span> HybridFormer: Improving Squeezeformer with Hybrid Attention and NSR Mechanism. Y Yang<sup>⭐</sup>, **Y Pan**<sup>⭐</sup>, J Yin, J Han, L Ma, H Lu. [[PDF]](https://ieeexplore.ieee.org/abstract/document/10096467)
  
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">ACM MM Workshop 2023</span> Exploring the Power of Cross-Contextual Large Language Model in Mimic Emotion Prediction. G Yi, Y Yang, **Y Pan**, Y Cao, J Yao, X Lv, C Fan, Z Lv, J Tao, S Liang, H Lu. [[PDF]](https://dl.acm.org/doi/10.1145/3606039.3613109) 

- <span style="display:inline-block; background-color:#6c757d; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px; border-radius:3px;">arXiv 2023</span> 
MSAC: Multiple Speech Attribute Control Method for Reliable Speech Emotion Recognition. **Y Pan**, Y Yang, Y Huang, J Yin, Y Hu, H Lu, L Ma, J Zhao. [[PDF]](https://arxiv.org/pdf/2308.04025)



# 💻 Internships
- *2022.12 - 2023.10, Everest Team - Ximalaya, China.
- *2025.03 - 2026.03, Research Team - Recho, Japan.

# 🏆 Honors & Awards

- *2023.10*: 🥇 **1st Place Winner**, Mimic Sub-challenge of the 4th Multimodal Sentiment Analysis Challenge and Workshop (MuSe 2023) @ ACM MM.


# 💬 Academic Services

**Conference Reviewer**

- *Speech & Audio*: ICASSP (2024–2026), INTERSPEECH (2026), IEEE SLT (2026)
- *Natural Language Processing*: ACL (2025–2026), EMNLP (2025–2026)
- *Artificial Intelligence*: AAAI (2025–2027), NeurIPS (2026)
- *Multimedia*: ACM MM (2025)
- *Software Engineering*: ICSE (2025–2026), ISSTA (2025), ASE (2025), FSE (2025)


Thanks for the template of [acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io)

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=m3bxB5AtfyzWsAE07t3xgXcTY-tytE-8I-82gax8q4Y&cl=ffffff&w=a"></script>
