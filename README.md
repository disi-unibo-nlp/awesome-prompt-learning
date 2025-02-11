# Awesome Prompt Learning

[![Awesome](https://awesome.re/badge.svg)](https://github.com/lyy1994/awesome-data-contamination) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This is a curated list of papers on Prompt Learning applied to text downstream tasks in natural language processing (NLP) and natural language generation (NLG).

The list serves as a complement to the survey below.

## 🔍 Contents

- [🌟 Prompt Learning](#intro)
- [📜 Papers](#papers)
    - [🏷️ Tagset](#tagset)
    - [🎯 The List](#list)
- [🧰 Query](#resources)
- [🚩 Citation](#citation)
- [🎉 Contribution](#contribution)
- [🤝 Acknowledgement](#acknowledgement)

<a id="intro"></a>
## 🌟 What's Prompt Learning?

Prompt Learning in the context of large language models (LLMs) refers to an automatic technique where task-specific instructions are provided as part of the input prompt to guide the model's behavior without modifying its underlying parameters. This method leverages the pre-trained knowledge of LLMs and helps them generalize across various text downstream tasks such as text classification, summarization, translation, and question-answering withoud doing any form of fine-tuning.

<a id="papers"></a>
## 📜 Papers

<a id="tagset"></a>
### 🏷️ Tagset

In this paper list, we tag each paper with one or more labels defined in the table below. These tags serve the purpose of facilitating the related work searching.

| Category | Explanation |
|----------|-------------|
| ![](https://img.shields.io/badge/Soft-yellow) | This paper use Soft prompts |
| ![](https://img.shields.io/badge/Discrete-blue) | This paper use Dicrete prompts |
| ![](https://img.shields.io/badge/Hybrid-8A2BE2) | This paper use Hybrid prompt (Discrete + Soft) |
| ![](https://img.shields.io/badge/Learning-green) |  |
| ![](https://img.shields.io/badge/NLU-cyan) | The Domain of the paper |
| ![](https://img.shields.io/badge/NLG-orange) | The Domain of the paper |
| ![](https://img.shields.io/badge/Code-red) | This work have a open source code repository |

<a id="list"></a>
### 🎯 The List

> [!Note]
> The list is ordered based on the publication date of the paper, from oldest to newest.

1. **Continual Prompt Tuning for Dialog State Tracking** (ACL 2022) [[paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85136021804&origin=resultslist&sort=plf-t&src=s&sid=0a96f95112ece499c668b02a5cb55d3f&sot=a&sdt=a&cluster=scofreetoread%2C%22all%22%2Ct%2C%22publisherfullgold%22%2Ct%2Bscopubstage%2C%22final%22%2Ct%2Bscosubjabbr%2C%22COMP%22%2Ct%2Bscosubtype%2C%22cp%22%2Ct%2C%22ar%22%2Ct%2Bscolang%2C%22English%22%2Ct%2Bscoexactkeywords%2C%22Image+Features%22%2Cf%2C%22Image+Recognition+And+Understanding%22%2Cf%2C%22Images+Classification%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modalities%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modality%22%2Cf%2C%22Vision-language+Models%22%2Cf%2C%22Learning+For+Vision%22%2Cf%2C%22Vision-language+Model%22%2Cf%2C%22Image+Classification%22%2Cf%2C%22Image+Recognition%22%2Cf%2C%22Visual+Prompts%22%2Cf%2C%22Image+Enhancement%22%2Cf%2C%22Computer+Vision%22%2Cf%2C%22Visual+Languages%22%2Cf%2C%22Multi-modal%22%2Cf%2C%22Multi-modal+Learning%22%2Cf&s=%28TITLE%28%28+%22prompt+tuning%22+%29+OR+%28+%22prefix+tuning%22+%29+OR+%28+%22prompt+learning%22+%29+OR+%28+%22soft+prompt*%22+%29+OR+%28+%22prompt*+optimization%22+%29%29+AND+PUBYEAR+%26gt%3B+2020+AND+PUBYEAR+%26lt%3B+2025+%29&sessionSearchId=0a96f95112ece499c668b02a5cb55d3f&relpos=11)] ![](https://img.shields.io/badge/Soft-yellow)![](https://img.shields.io/badge/Learning-green)![](https://img.shields.io/badge/NLU-cyan)![](https://img.shields.io/badge/Code-red) <br />
    
    > **Research Direction**: Enhancing continual learning for dialog systems, efficient knowledge transfer between tasks.

    
2. **Prompt to Transfer: Sim-to-Real Transfer for Traffic Signal Control with Prompt Learning** (AAAI) ![](https://img.shields.io/badge/Discrete-blue)  
3. **Discrete and Soft Prompting for Multilingual Models** (EMNLP 2021) ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)![](https://img.shields.io/badge/Hybrid-8A2BE2)  
4. **Commonsense Knowledge-Aware Prompt Tuning for Few-Shot NOTA Relation Classification** (Applied Sciences) ![](https://img.shields.io/badge/Discrete-blue)  
5. **PADA: Example-based Prompt Learning for on-the-fly Adaptation to Unseen Domains** (ACL) ![](https://img.shields.io/badge/Discrete-blue)  
6. **Ontology-enhanced Prompt-tuning for Few-shot Learning** (ACM) ![](https://img.shields.io/badge/Soft-yellow)  
7. **KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction** (ACM) ![](https://img.shields.io/badge/Hybrid-8A2BE2)  
8. **Dual Context-Guided Continuous Prompt Tuning for Few-Shot Learning** (Findings) ![](https://img.shields.io/badge/Soft-yellow)  
9. **PPT: Pre-trained Prompt Tuning for Few-shot Learning** (ACL) ![](https://img.shields.io/badge/Hybrid-8A2BE2)  
10. **Prompt Tuning for Discriminative Pre-trained Language Models** (ACL) ![](https://img.shields.io/badge/Discrete-blue)  
11. **The Power of Prompt Tuning for Low-Resource Semantic Parsing** (ACL) ![](https://img.shields.io/badge/Soft-yellow)  
12. **Chinese Spam Detection Based on Prompt Tuning** (Knowledge Systems Institute Graduate School) ![](https://img.shields.io/badge/Discrete-blue)  
13. **Novelty Controlled Paraphrase Generation with Retrieval Augmented Conditional Prompt Tuning** (AAAI) ![](https://img.shields.io/badge/Soft-yellow)  
14. **AESPrompt: Self-supervised Constraints for Automated Essay Scoring with Prompt Tuning** (The 34th International Conference on Software Engineering and Knowledge Engineering) ![](https://img.shields.io/badge/Soft-yellow)  
15. **CUP: Curriculum Learning based Prompt Tuning for Implicit Event Argument Extraction** (IJCAI) ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Hybrid-8A2BE2)  
16. **Enhancing Entity Representations with Prompt Learning for Biomedical Entity Linking** (IJCAI) ![](https://img.shields.io/badge/Discrete-blue)  
17. **Relation Extraction as Open-book Examination: Retrieval-enhanced Prompt Tuning** (ACM SIGIR) ![](https://img.shields.io/badge/Soft-yellow)![](https://img.shields.io/badge/Hybrid-8A2BE2)  
18. **Towards Unified Conversational Recommender Systems via Knowledge-Enhanced Prompt Learning** (ACM SIGKDD) ![](https://img.shields.io/badge/Discrete-blue)  
19. **Chemical-Protein Relation Extraction with Pre-trained Prompt Tuning** (IEEE 2022) ![](https://img.shields.io/badge/Discrete-blue)  
20. **PRCBERT: Prompt Learning for Requirement Classification using BERT-based Pretrained Language Models** (ACM ASE) ![](https://img.shields.io/badge/Discrete-blue)  
21. **Prompt Tuning for Multi-Label Text Classification: How to Link Exercises to Knowledge Concepts?** (Applied Sciences (Switzerland)) ![](https://img.shields.io/badge/Soft-yellow)  
22. **Investigating Prompt Learning for Chinese Few-Shot Text Classification with Pre-Trained Language Models** (Applied Sciences (Switzerland))  
23. **Continuous Prompt Tuning Based Textual Entailment Model for E-commerce Entity Typing** (IEEE 2022) ![](https://img.shields.io/badge/Hybrid-8A2BE2)  
24. **No more fine-tuning? an experimental evaluation of prompt tuning in code intelligence** (ESEC/FSE) ![](https://img.shields.io/badge/Soft-yellow)  
25. **PTR: Prompt Tuning with Rules for Text Classification** (AI Open) ![](https://img.shields.io/badge/Discrete-blue)  
26. **Coherent Long Text Generation by Contrastive Soft Prompt** (GEM 2022) ![](https://img.shields.io/badge/Soft-yellow)  
27. **ATTEMPT: Parameter-Efficient Multi-task Tuning via Attentional Mixtures of Soft Prompts** (EMNLP 2022) ![](https://img.shields.io/badge/Soft-yellow)  
28. **DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation** (EMNLP 2022) ![](https://img.shields.io/badge/Soft-yellow)  
29. **Making Pre-trained Language Models End-to-end Few-shot Learners with Contrastive Prompt Tuning** (WSDM 2023) ![](https://img.shields.io/badge/Discrete-blue)  
30. **A Chinese Few-Shot Text Classification Method Utilizing Improved Prompt Learning and Unlabeled Data** (Applied Sciences (Switzerland)) ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)  
31. **Knowledge-Guided Prompt Learning for Few-Shot Text Classification** (Electronics (Switzerland)) ![](https://img.shields.io/badge/Soft-yellow)  
32. **Personalized Prompt Learning for Explainable Recommendation** (ACM Transactions on Information Systems) ![](https://img.shields.io/badge/Discrete-blue)  
33. **Adaptive Prompt Learning-Based Few-Shot Sentiment Analysis** (Neural Processing Letters) ![](https://img.shields.io/badge/Discrete-blue)  
34. **Decomposed Two-Stage Prompt Learning for Few-Shot Named Entity Recognition** (Information (Switzerland)) ![](https://img.shields.io/badge/Discrete-blue)  
35. **A Dual Prompt Learning Framework for Few-Shot Dialogue State Tracking** (ACM 2023) ![](https://img.shields.io/badge/Discrete-blue)  
36. **Automating Method Naming with Context-Aware Prompt-Tuning** (IEEE/ACM) ![](https://img.shields.io/badge/Discrete-blue)  



37. **Translating radiology reports into plain language using ChatGPT and GPT-4 with prompt learning: results, limitations, and potential** (Visual Computing for Industry, Biomedicine, and Art)  
38. **Multi-Stage Prompt Tuning for Political Perspective Detection in Low-Resource Settings** (Applied Sciences (Switzerland))  
39. **Exploiting Prompt Learning with Pre-Trained Language Models for Alzheimer's Disease Detection** (ICASSP)  
40. **FedPrompt: Communication-Efficient and Privacy-Preserving Prompt Tuning in Federated Learning** (ICASSP)  
41. **Knowledge-Augmented Frame Semantic Parsing with Hybrid Prompt-Tuning** (ICASSP)  
42. **MedKPL: A heterogeneous knowledge enhanced prompt learning framework for transferable diagnosis** (Journal of Biomedical Informatics)  
43. **Matching Exemplar as Next Sentence Prediction (MeNSP): Zero-Shot Prompt Learning for Automatic Scoring in Science Education** (AIED)  
44. **Zero-Shot Cross-Lingual Event Argument Extraction with Language-Oriented Prefix-Tuning** (AAAI)  
45. **A Medical Question Classification Approach Based on Prompt Tuning and Contrastive Learning** (SEKE)  
46. **HGAPT: Heterogeneous Graph Augmented Prompt Tuning for Low-Resource Fake News Detection** (SEKE)  
47. **KLAPrompt: Infusing Semantic Knowledge into Pre-trained Language Models by Long-answer Prompt Learning** (SEKE)  
48. **ETHICIST: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation** (ACL)  
49. **Emotion classification on code-mixed text messages via soft prompt tuning** (WASSA)  
50. **A Unified Generative Retriever for Knowledge-Intensive Language Tasks via Prompt Learning** (SIGIR 2023)  
51. **Adversarial Meta Prompt Tuning for Open Compound Domain Adaptive Intent Detection** (SIGIR 2023)  
52. **Prompt Learning for News Recommendation** (SIGIR 2023)  
53. **Prompt Learning to Mitigate Catastrophic Forgetting in Cross-lingual Transfer for Open-domain Dialogue Generation** (SIGIR 2023)  
54. **Soft Prompt Decoding for Multilingual Dense Retrieval** (SIGIR 2023)  
55. **VPN: Variation on Prompt Tuning for Named-Entity Recognition** (Applied Sciences (Switzerland))  
56. **Few-shot Sentiment Analysis Based on Adaptive Prompt Learning and Contrastive Learning** (Information Technology and Control)  
57. **Instance-Aware Prompt Learning for Language Understanding and Generation** (ACM Transactions on Asian and Low-Resource Language Information Processing)  
58. **A Prompt Learning Based Intent Recognition Method on a Chinese Implicit Intent Dataset CIID** (Neural Processing Letters)  
59. **Prompt Learning with Structured Semantic Knowledge Makes Pre-Trained Language Models Better** (Electronics (Switzerland))  
60. **APICom: Automatic API Completion via Prompt Learning and Adversarial Training-based Data Augmentation** (ACM International Conference Proceeding Series)  
61. **Medical text classification based on the discriminative pre-training model and prompt-tuning** (Digital Health)  
62. **Research on the Application of Prompt Learning Pretrained Language Model in Machine Translation Task with Reinforcement Learning** (Electronics (Switzerland))  
63. **Simple Knowledge Graph Completion Model Based on Differential Negative Sampling and Prompt Learning** (Information (Switzerland))  
64. **Clinical Prompt Learning With Frozen Language Models** (IEEE Transactions on Neural Networks and Learning Systems)  
65. **One Model for All Domains: Collaborative Domain-Prefix Tuning for Cross-Domain NER** (IJCAI)  
66. **Generating Chinese Event Extraction Method Based on ChatGPT and Prompt Learning** (Applied Sciences (Switzerland))  
67. **ConKgPrompt: Contrastive Sample Method Based on Knowledge-Guided Prompt Learning for Text Classification** (Electronics (Switzerland))  
68. **ContrastNER: Contrastive-based Prompt Tuning for Few-shot NER** (IEEE/COMPSAC)  
69. **Prompt-Learning for Cross-Lingual Relation Extraction** (IJCNN)  
70. **Parameter-Efficient Low-Resource Dialogue State Tracking by Prompt Tuning** (INTERSPEECH)  
71. **Towards using Few-Shot Prompt Learning for Automating Model Completion** (ICSE-NIER)  
72. **Prompt-Learning for Short Text Classification** (IEEE)  
73. **MsPrompt: Multi-step prompt learning for debiasing few-shot event detection** (Information Processing and Management)  
74. **Robust scientific text classification using prompt tuning based on data augmentation with L2 regularization** (Information Processing and Management)  
75. **Soft prompt enhanced joint learning for cross-domain aspect-based sentiment analysis** (Intelligent Systems with Applications)  
76. **Knowledge Prompt-tuning for Sequential Recommendation** (MM 2023)  
77. **REKP: Refined External Knowledge into Prompt-Tuning for Few-Shot Text Classification** (Mathematics)  
78. **Contrastive Graph Prompt-tuning for Cross-domain Recommendation** (ACM)  
79. **Domain-Enhanced Prompt Learning for Chinese Implicit Hate Speech Detection** (IEEE)  
80. **SPeC: A Soft Prompt-Based Calibration on Performance Variability of Large Language Model in Clinical Notes Summarization** (Journal of Biomedical Informatics)  
81. **Leveraging Chain-of-Thought to Enhance Stance Detection with Prompt-Tuning** (Mathematics)  
82. **Prompt Optimization in Large Language Models** (Mathematics)  
83. **HGPrompt: Bridging Homogeneous and Heterogeneous Graphs for Few-Shot Prompt Learning** (AAAI)  
84. **On Unsupervised Domain Adaptation: Pseudo Label Guided Mixup for Adversarial Prompt Tuning** (Proceedings of the AAAI Conference on Artificial Intelligence)  
85. **Prompt to Transfer: Sim-to-Real Transfer for Traffc Signal Control with Prompt Learning** (AAAI)  
86. **Model tuning or prompt Tuning? a study of large language models for clinical concept and relation extraction** (Journal of Biomedical Informatics)  
87. **ProRLearn: boosting prompt tuning-based vulnerability detection by reinforcement learning** (ASE)  
88. **Affective Prompt-Tuning-Based Language Model for Semantic-Based Emotional Text Generation** (International Journal on Semantic Web and Information Systems)  
89. **Enhancing Zero-Shot Stance Detection with Contrastive and Prompt Learning** (Entropy)  
90. **Leveraging Pretrained Language Models for Enhanced Entity-Matching: A Comprehensive Study of Fine-Tuning and Prompt-Learning Paradigms** (International Journal of Intelligent Systems)  
91. **Knowledge-Enhanced Prompt Learning for Few-Shot Text Classification** (Big Data and Cognitive Computing)  
92. **ConsPrompt: Exploiting Contrastive Samples for Fewshot Prompt Learning** (ICASSP)  
93. **HetGPT: Harnessing the Power of Prompt Tuning in Pre-Trained Heterogeneous Graph Neural Networks** (ACM)  
94. **Adapting LLMs for Efficient Context Processing through Soft Prompt Compression** (ACM)  
95. **Can we Soft Prompt LLMs for Graph Learning Tasks?** (ACM)  
96. **You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content** (IEEE)  
97. **KBPT: knowledge-based prompt tuning for zero-shot relation triplet extraction** (PeerJ Computer Science)  
98. **Enhancing Cross-Lingual Sarcasm Detection by a Prompt Learning Framework with Data Augmentation and Contrastive Learning** (Electronics)  
99. **A Rumors Detection Method Using T5-Based Prompt Learning** (International Journal of Data Warehousing and Mining)  
100. **Meta Soft Prompting and Learning** (APSIPA)  
101. **Exploring Universal Intrinsic Task Subspace for Few-Shot Learning via Prompt Tuning** (IEEE/ACM)  
102. **Prompt Tuning on Graph-Augmented Low-Resource Text Classification** (IEEE)  
103. **Prompt learning for metonymy resolution** (Knowledge-Based Systems)  
104. **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with LLMs** (CCS)  
105. **RPEPL: Tibetan Sentiment Analysis Based on Relative Position Encoding and Prompt Learning** (ACM)  
106. **Application of Prompt Learning Models in Identifying the Collaborative Problem Solving Skills in an Online Task** (CSCW)  
107. **Prompt Tuning for Item Cold-start Recommendation** (ACM)  
108. **G-SAP: Graph-based Structure-Aware Prompt Learning over Heterogeneous Knowledge for Commonsense Question Answering** (ICMR)  
109. **Graph‑Enhanced Prompt Learning for Personalized Review Generation** (Data Science and Engineering)  
110. **Multi-Relation Extraction for Cybersecurity Based on Ontology Rule-Enhanced Prompt Learning** (Electronics)  
111. **TopicTag: Automatic Annotation of NMF Topic Models Using Chain of Thought and Prompt Tuning with LLMs** (ACM)  
112. **Knowledge-injected Prompt Learning for Chinese Biomedical Entity Normalization** (ACM)  
113. **Graph Intelligence with Large Language Models and Prompt Learning** (ACM SIGKDD) 

