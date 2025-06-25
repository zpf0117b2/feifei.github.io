---
layout: page
permalink: /main/
title: Bio
# toc:  true
sitemap: true
map: false
---

Pengfei Zhang is a PHD student in UC Irvine, with a strong research focus on intelligent systems at the intersection of large language models (LLMs), speech, and vision. Most of his work centers around building multimodal agent frameworks that unify language, audio, and visual modalities to enhance decision-making in human-centric tasks. His projects span LLM-enhanced automatic speech recognition, multimodal alignment of LLMs for speech and visual understanding and generation, and agent-based personalized healthcare recommendation systems. His resume is presented in [Pengfei’s CV](files/PengfeiZhang_resume2.pdf).

---

#### NEWS 

06/2025：:fireworks: One paper, [\[KinMo\]](https://andypinxinliu.github.io/KinMo/), is accepted by ICCV 2025!

06/2025: :fist: Start an Applied Scientist Intern position at Amazon Web Service AI Lab!

06/2025: One paper is accepted by AMIA 2025!

12/2024: :fireworks: One paper, [\[DEMENTIA-PLAN\]](https://openreview.net/pdf?id=m7KkNKMDVp), is accepted by AAAI W 2025!

06/2024: :fist: Start a research scientist intern position at Flawless. Inc!

10/2023: One paper is accepted by WACV 2024!


<!-- ##### Website Introduction

My scientific experiences are recorded in [research](https://zpf0117b.github.io/PengfeiZhang.github.io/research/) and [publications](https://zpf0117b.github.io/PengfeiZhang.github.io/publications/).  -->


<!-- <embed src="http://files2.17173.com/__flash/2011/10/21/honehone_clock_tr.swf"> -->

<style scoped>
table {
  font-size: 10px;
}
</style>

<style>
table th:first-of-type {
    width: 45%;
}
table th:nth-of-type(2) {
    width: 55%;
}
/* table th:nth-of-type(3) {
    width: 50%;
}
table th:nth-of-type(4) {
    width: 30%;
} */
</style>

# Research

### Multimodal Alignment of LLMs for Speech and Visual Understanding and Generation

| Jan 2023 - Present       | &nbsp;         |
| ---- |:---------------:|
| Multimodal alignment of LLMs for speech and visual understanding and generation aims to bridge language, audio, and vision into a unified semantic space. By synchronizing temporal and contextual cues across modalities—such as aligning speech with co-speech gestures or visual actions—LLMs can generate coherent, context-aware outputs that reflect human-like perception and behavior. This enables applications like gesture generation, motion synthesis, and audiovisual narration grounded in natural language. | ![Multimodal](pubimages/R_multimodal.jpg) | 
| **Publications:**        | &nbsp;         |
| ![C2.3](pubimages/C_kinmo.jpg) | KinMo: Kinematic-aware Human Motion Understanding and Generation.<br> **Pengfei Zhang**, Pinxin Liu, Pablo Garrido, Hyeongwoo Kim, Bindita Chaudhuri.<br> ICCV 2025 <br> [\[project\]](https://andypinxinliu.github.io/KinMo/) [\[preprint\]](https://arxiv.org/abs/2411.15472) [\[demo\]](https://andypinxinliu.github.io/KinMo/static/videos/KinMo-Demo.mp4) |
| ![C2.2](pubimages/C_cospeech.png) |  Contextual Gesture: Co-Speech Gesture Video Generation through Semantic-aware Gesture Representation.<br> Pinxin Liu, **Pengfei Zhang**, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski.<br> ACM MM 2025 <br> [\[project\]](https://andypinxinliu.github.io/Contextual-Gesture/) [\[preprint\]](https://arxiv.org/abs/2502.07239)  |
| ![C2.1](pubimages/C_handformer2t.jpg) |  Handformer2T: A Lightweight Regression-based model for Interacting Hands Pose Estimation from a single RGB Image.<br> **Pengfei Zhang**, Deying Kong. <br> WACV 2024 <br> [\[paper\]](https://openaccess.thecvf.com/content/WACV2024/html/Zhang_Handformer2T_A_Lightweight_Regression-Based_Model_for_Interacting_Hands_Pose_Estimation_WACV_2024_paper.html) |


### LLM-enhanced Automatic Speech Recognition

| Jan 2023 - Present       | &nbsp;         |
| ---- |:---------------:|
| LLM-enhanced automatic speech recognition (ASR) integrates large language models with traditional ASR pipelines to improve transcription accuracy, particularly in domain-specific and noisy scenarios. By leveraging external knowledge sources—such as medical knowledge graphs—and contextual understanding, LLMs can correct recognition errors, disambiguate terms, and enhance spoken question answering. This hybrid approach enables more robust and semantically informed speech understanding in complex applications like healthcare. | ![ASR](pubimages/R_ASR.png) | 
| **Publications:**        | &nbsp;         |
| ![C1.2](pubimages/C_medspeak.jpg) | MedSpeak: Knowledge Enhanced ASR Error Correction framework for Spoken Medical Question Answering |
| ![C1.1](pubimages/C_cospeech.png) |  Contextual Gesture: Co-Speech Gesture Video Generation through Semantic-aware Gesture Representation.<br> Pinxin Liu, **Pengfei Zhang**, Hyeongwoo Kim, Pablo Garrido, Ari Shapiro, Kyle Olszewski.<br> ACM MM 2025 <br> [\[project\]](https://andypinxinliu.github.io/Contextual-Gesture/) [\[preprint\]](https://arxiv.org/abs/2502.07239)  |

### Agent-based Personalized Healthcare Recommendation Systems

| Sep 2021 - Present       | &nbsp;         |
| ---- |:---------------:|
| Agent-based personalized healthcare recommendation systems leverage autonomous software agents to analyze individual patient data—such as medical history, lifestyle, and preferences—to deliver tailored health advice and treatment options. These systems can interact dynamically with users and other agents (e.g., diagnostic or monitoring tools), adapting recommendations in real time to improve decision-making and patient outcomes. | ![Agent](pubimages/R_personalized.jpg) |
| **Publications:**        | &nbsp; |
| ![C3.4](pubimages/C_adaptiveRetrieval.jpg) | Adaptive Constraint Relaxation in Personalized Nutrition Recommendations: An LLM-Driven Knowledge Graph Retrieval Approach<br> Pengfei Zhang, Mohbat Fnu, Yutong Song, Oshani Seneviratne, Zhongqi Yang, Iman Azimi, Amir M. Rahmani<br> AMIA - American Medical Informatics Association <br>[\[preprint\]](http://dx.doi.org/10.13140/RG.2.2.29331.80163) |
| ![C3.3](pubimages/C_dementialPlan2.png) | DEMENTIA-PLAN: An Agent-Based Framework for Multi-Knowledge Graph Retrieval-Augmented Generation in Dementia Care.<br> Yutong Song, Chenhan Lyu, **Pengfei Zhang**, Sabine Brunswicker, Nikil Dutt, Amir M. Rahmani.<br> AAAI 2025 Workshop: Knowledge Graphs for Health Equity, Justice, and Social Services <br>[\[preprint\]](https://openreview.net/pdf?id=m7KkNKMDVp) |
| ![C3.2](pubimages/C_mahyarEMBC.png) | Knowledge-Infused LLM-Powered Conversational Health Agent: A Case Study for Diabetes Patients.<br> Mahyar Abbasian, Zhongqi Yang, Elahe Khatibi, **Pengfei Zhang**, Nitish Nagesh, Iman Azimi, Ramesh Jain, Amir M. Rahmani.<br> EMBC 2024 <br> [\[paper\]](https://arxiv.org/abs/2402.10153) [\[code\]](https://github.com/Institute4FutureHealth/CHA) [\[website\]](https://www.opencha.com/) |
| ![C3.1](pubimages/C_clmb.jpg) | CLMB: deep contrastive learning for robust metagenomic binning<br>**Pengfei Zhang**, Zhengyuan Jiang, Yixuan Wang, Yu Li.<br>RECOMB 2022 (oral)<br>[\[paper\]](https://doi.org/10.1101/2021.11.15.468566) [\[code\]](https://github.com/zpf0117b/CLMB/) [\[blog\]](https://zpf0117b2.github.io/feifei.github.io/2022/01/20/contrastive-learning-for-robust-metagenome-binning/)     |

# Internships

2025 Applied Scientist Intern at Amazon Web Service AI Lab. Location: Santa Clara

2024 Research Science Intern at Flawless. AI. Inc. Location: Los Angeles

2022 Research Intern in the Chinese University of Hong Kong. Location: Hong Kong

# Projects

| Personal Software Programming Projects  | &nbsp;         |
| ---- |:---------------:|
| [\[Distributed Chatroom with LLaMa-Powered Summarization\]](https://github.com/zpf0117b/Distributed-Chatroom-with-LLaMa-Powered-Summarization)  |  A Multi-topic Web Chatroom which can provide backup on previous conversations and LLaMa Powered summarizations after each refresh |

# Awards

Dean's award from UCI

National Encouragement Scholarship (top 20%) from USTC

National Encouragement Scholarship (top 20%) from USTC
