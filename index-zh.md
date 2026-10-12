---
layout: page
title: ""
permalink: /zh/
lang: zh
---

<div style="text-align: right; margin-bottom: 20px;">
  <a style="text-decoration: none;" href="/academic-research/">English</a> | <strong>中文</strong>
</div>

我是李浩宇（Haoyu Li），现为南京大学博士研究生，师从<a style="text-decoration: none;" href="https://is.nju.edu.cn/ws">准聘副教授王帅</a>。硕士毕业于上海交通大学计算机科学与技术专业，师从<a style="text-decoration: none;" href="https://x-lance.github.io/kaiyu/" target="_blank" rel="noopener">俞凯教授</a>。

研究方向聚焦于**目标说话人提取（Target Speaker Extraction, TSE）**、**自动语音识别（Automatic Speech Recognition, ASR）**与**语音大语言模型（Speech LLMs）**，致力于构建能够在嘈杂、多人说话的真实场景中稳定运行的鲁棒语音交互系统。

---

## 研究兴趣

总体而言，我的研究聚焦于面向前端信号处理与语音理解的**目标说话人提取（TSE）**与**多说话人自动语音识别（Multi-talker ASR）**：

- **语音分离**：涵盖目标说话人提取（TSE）与盲源分离（Blind Source Separation, BSS）
- **说话人属性化自动语音识别（Speaker-Attributed ASR, SA-ASR）**
- **面向资源受限边缘设备的关键词检测（Keyword Spotting, KWS）**
  
---

## 研究经历

我的近期工作跨越学术实验室和工业研究：

- **文本引导语音分离与鲁棒关键词检测 (思必驰，苏州)**  
  我构建基于文本线索的语音分离系统，在真实多人对话场景中将拒识率降至4.3%、误唤醒率压缩至基线20%；同时研发面向低信噪比环境的端到端关键词检测算法，结合鲁棒流式解码与 WFST 优化，相关成果形成2篇ICASSP 2025论文。

- **流匹配TTS的说话人自适应对齐 (阿里巴巴，北京)**  
  我提出时序与层级双自适应方案，动态调整去噪阶段监督强度与网络层对齐目标，有效提升零样本语音克隆中的音色一致性，相关工作已被NCMMSC 2026长文赛道接收，并安排口头报告。

- **关键词引导的目标说话人提取新范式 (南京大学/合作研究)**  
  我提出Detect-Attend-Extract三阶段框架，仅需部分文本线索即可实现优于语音注册基线的提取性能，相关工作已发表于IJCAI-ECAI 2026。

---

## 发表论文（选集）

完整列表请见 **[谷歌学术](https://scholar.google.com/citations?user=ox4ykukAAAAJ)**。
> \* 表示同等贡献。

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

## 教育经历

- **南京大学 - 智能科学与技术学院** <span class="education-period">（2026-至今）</span>  
  博士研究生 | 导师：王帅（准聘副教授）

- **上海交通大学 - 计算机学院** <span class="education-period">（2023-2026）</span>  
  工学硕士 | 导师：俞凯（教授）

- **北京交通大学 - 计算机科学与技术学院** <span class="education-period">（2019-2023）</span>  
  工学学士

## 荣誉奖项
- 2019-2020年度本科生国家奖学金
- 2020-2021年度本科生国家奖学金
- 北京交通大学优秀毕业生

---

## 联系方式

我非常乐意就上述话题进行交流和合作，您可以通过以下方式联系我：

- **邮箱:** [haoyu.li.cs@smail.nju.edu.cn](mailto:haoyu.li.cs@smail.nju.edu.cn)
- **GitHub:** [https://github.com/GnafiY](https://github.com/GnafiY)
- **Google Scholar:** [https://scholar.google.com/citations?user=ox4ykukAAAAJ&hl](https://scholar.google.com/citations?user=ox4ykukAAAAJ&hl)
