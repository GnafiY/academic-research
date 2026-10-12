---
layout: page
title: ""
permalink: /
lang: en
---

<div style="text-align: right; margin-bottom: 20px;">
  <strong>English</strong> | <a style="text-decoration: none;" href="/academic-research/zh/">中文</a>
</div>

I'm Haoyu Li (李浩宇), a Ph.D. student at Nanjing University, where I am supervised by <a style="text-decoration: none;" href="https://is.nju.edu.cn/ws_en/main.htm">Shuai Wang, Tenure-Track Associate Professor</a>. I received my M.S. in Computer Science and Technology from Shanghai Jiao Tong University under the supervision of <a style="text-decoration: none;" href="https://x-lance.github.io/kaiyu/" target="_blank" rel="noopener">Prof. Kai Yu</a>.

My research focuses on **Target Speaker Extraction (TSE)**, **Automatic Speech Recognition (ASR)**, and **Speech Large Language Models (Speech LLMs)**. I aim to develop robust speech interaction systems capable of operating in noisy, multi-talker real-world environments.

---

## Research Interests

Generally, I am focusing on **TSE** front-end and **Multi-talker ASR** for front-end signal processing and speech understanding:

- **Speech Separation**, including TSE and Blind Source Separation (BSS)
- **Speaker-Attributed ASR (SA-ASR)**
- **Keyword Spotting (KWS)** for resource-constrained edge devices

---

## Research Experience

My recent work spans both academic labs and industry research:

- **Text-Guided Speech Separation and Robust Keyword Spotting (AISpeech, Suzhou)**  
  I developed a text-guided speech separation system that reduced the false rejection rate to 4.3% and lowered the false wake-up rate to 20% of the baseline in real-world multi-talker scenarios. Concurrently, I engineered an end-to-end keyword spotting algorithm for low-SNR environments, integrating robust streaming decoding with WFST optimization, yielding two papers accepted at ICASSP 2025.

- **Speaker-Adaptive Alignment for Flow-Matching TTS (Alibaba, Beijing)**  
  I proposed a dual temporal and hierarchical adaptive scheme that dynamically modulates supervision strength during denoising and assigns layer-specific alignment objectives, significantly enhancing timbre consistency in zero-shot voice cloning. This work was accepted to NCMMSC 2026 in the long paper track for an oral presentation.

- **A Novel Paradigm for Keyword-Guided Target Speaker Extraction (Nanjing University / Collaborative Research)**  
  I proposed a three-stage Detect-Attend-Extract framework that achieves extraction performance superior to conventional speech-enrollment baselines using only partial text cues. This work was published at IJCAI-ECAI 2026.

---

## Publications (Selected)
You may refer to the full list on **[Google Scholar](https://scholar.google.com/citations?user=ox4ykukAAAAJ)**.
> \* indicates equal contribution.

<div class="publications" markdown="1">

- **Detect, Attend and Extract: Keyword Guided Target Speaker Extraction**  
  *<u>Haoyu&nbsp;Li</u>\**, Yu&nbsp;Xi\*, Yidi&nbsp;Jiang, Shuai&nbsp;Wang, Kate&nbsp;Knill, Mark&nbsp;Gales, Haizhou&nbsp;Li, Kai&nbsp;Yu  
  *IJCAI-ECAI&nbsp;2026.*  
  [Paper](https://www.ijcai.org/proceedings/2026/644) /
  [Code](https://github.com/GnafiY/DAE-TSE) /
  [WeSep Training Recipe](https://github.com/wenet-e2e/wesep/tree/master/examples/textual/librimix_keywords) /
  [Demo Page](https://gnafiy.github.io/DAE-TSE_demo/)

- **Text-aware Speech Separation for Multi-talker Keyword Spotting**  
  *<u>Haoyu&nbsp;Li</u>*, Baochen&nbsp;Yang, Yu&nbsp;Xi, Linfeng&nbsp;Yu, Tian&nbsp;Tan, Hao&nbsp;Li, Kai&nbsp;Yu  
  *Interspeech&nbsp;2024.*  
  [Paper](https://www.isca-archive.org/interspeech_2024/li24r_interspeech.html) /
  [Code](https://github.com/GnafiY/TPDT-SS-KWS)

- **Time-Layer Adaptive Alignment for Speaker Similarity in Flow-Matching Based Zero-Shot TTS**  
  *<u>Haoyu&nbsp;Li</u>\**, Mingyang&nbsp;Han\*, Yu&nbsp;Xi, Dongxiao&nbsp;Wang, Hankun&nbsp;Wang, Haoxiang&nbsp;Shi, Boyu&nbsp;Li, Jun&nbsp;Song, Bo&nbsp;Zheng, Shuai&nbsp;Wang, Kai&nbsp;Yu  
  **arXiv:2511.09995**. *Accepted to NCMMSC&nbsp;2026 (Long&nbsp;Paper&nbsp;Track, Oral).*  
  [Paper](https://arxiv.org/abs/2511.09995)

- **Streaming Keyword Spotting Boosted by Cross-layer Discrimination Consistency**  
  Yu&nbsp;Xi\*, *<u>Haoyu&nbsp;Li</u>\**, Xiaoyu&nbsp;Gu, Hao&nbsp;Li, Yidi&nbsp;Jiang, Kai&nbsp;Yu  
  *ICASSP&nbsp;2025.*  
  [Paper](https://ieeexplore.ieee.org/abstract/document/10890010/) /
  [Code](https://github.com/x-lance/kwstreamingsearch)

- **NTC-KWS: Noise-aware CTC for Robust Keyword Spotting**  
  Yu&nbsp;Xi, *<u>Haoyu&nbsp;Li</u>*, Hao&nbsp;Li, Jiaqi&nbsp;Guo, Xu&nbsp;Li, Wen&nbsp;Ding, Kai&nbsp;Yu  
  *ICASSP&nbsp;2025.*  
  [Paper](https://ieeexplore.ieee.org/abstract/document/10889332)

- **MFA-KWS: Effective Keyword Spotting with Multi-head Frame-asynchronous Decoding**  
  Yu&nbsp;Xi, *<u>Haoyu&nbsp;Li</u>*, Xiaoyu&nbsp;Gu, Yidi&nbsp;Jiang, Kai&nbsp;Yu  
  *TASLP.*  
  [Paper](https://ieeexplore.ieee.org/abstract/document/11074751) /
  [Code](https://github.com/x-lance/kwstreamingsearch)

- **WeSep: A Modular and Cue-Composable Framework for Target Speaker Extraction**  
  Ke&nbsp;Zhang, Xiaoyang&nbsp;Yu, *<u>Haoyu&nbsp;Li</u>*, Shuai&nbsp;Wang, Shuhan&nbsp;Zhang, Haizhou&nbsp;Li  
  *Interspeech&nbsp;2026.*  
  [Paper](https://www.isca-archive.org/interspeech_2026/zhang26k_interspeech.html) /
  [Code](https://github.com/wenet-e2e/wesep)

- **G-STAR: End-to-End Global Speaker-Tracking Attributed Recognition**  
  Jing&nbsp;Peng\*, Ziyi&nbsp;Chen\*, *<u>Haoyu&nbsp;Li</u>\**, Yucheng&nbsp;Wang, Duo&nbsp;Ma, Mengtian&nbsp;Li, Yunfan&nbsp;Du, Dezhu&nbsp;Xu, Kai&nbsp;Yu, Shuai&nbsp;Wang  
  **arXiv:2603.10468**. *Submitted to Interspeech&nbsp;2026.*  
  [Paper](https://arxiv.org/abs/2603.10468)

</div>


## Education

- **Nanjing University - School of Intelligence Science and Technology** <span class="education-period">(2026-present)</span>  
  Ph.D. student | Advisor: Shuai&nbsp;Wang (Tenure-Track Associate Professor)

- **Shanghai Jiao Tong University - School of Computer Science** <span class="education-period">(2023-2026)</span>  
  M.S. in Computer Science and Technology | Advisor: Kai&nbsp;Yu (Professor)

- **Beijing Jiaotong University - School of Computer Science and Technology** <span class="education-period">(2019-2023)</span>  
  B.S. in Computer Science and Technology

## Honors & Awards
- National Scholarship for Undergraduates (2019-2020)
- National Scholarship for Undergraduates (2020-2021)
- Outstanding Graduate, Beijing Jiaotong University

---

## Contact Information

I am willing to chat and collaborate on the topics above and you can contact me by:

- **Email:** [haoyu.li.cs@smail.nju.edu.cn](mailto:haoyu.li.cs@smail.nju.edu.cn)
- **GitHub:** [https://github.com/GnafiY](https://github.com/GnafiY)
- **Google Scholar:** [https://scholar.google.com/citations?user=ox4ykukAAAAJ&hl](https://scholar.google.com/citations?user=ox4ykukAAAAJ&hl)
