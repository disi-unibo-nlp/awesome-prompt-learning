# Awesome Prompt Learning

[![Awesome](https://awesome.re/badge.svg)](https://github.com/disi-unibo-nlp/awesome-prompt-learning?tab=readme-ov-file) 
<!--[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT) -->

This is a curated list of papers on Prompt Learning applied to text downstream tasks in natural language processing (NLP) and natural language generation (NLG).

The list serves as a complement to the survey below.

## 🔍 Contents

- [🌟 Prompt Learning](#intro)
- [📜 Papers](#papers)
    - [🏷️ Tagset](#tagset)
    - [🎯 The List](#list)
- [🔍 Query](#query)
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
| ![](https://img.shields.io/badge/Hybrid-8A2BE2) | This paper use Hybrid prompts (Discrete + Soft) |
| ![](https://img.shields.io/badge/Code-red) | This work provide a open source code repository |

<a id="list"></a>
### 🎯 The List

> [!Note]
> The list is ordered based on the publication date of the paper, from oldest to newest.

1. **Discrete and Soft Prompting for Multilingual Models** (EMNLP, 2021) [[paper](https://aclanthology.org/2021.emnlp-main.672.pdf)] [[code](https://github.com/mprompting/xlmrprompt)] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)![](https://img.shields.io/badge/Hybrid-8A2BE2) ![](https://img.shields.io/badge/Code-red)

2. **Commonsense Knowledge-Aware Prompt Tuning for Few-Shot NOTA Relation Classification** (Applied Sciences, 2022) [[paper](https://www.mdpi.com/2076-3417/12/4/2185)] ![](https://img.shields.io/badge/Discrete-blue) 

3. **PADA: Example-based Prompt Learning for on-the-fly Adaptation to Unseen Domains** (ACL, 2022) [[paper](https://arxiv.org/pdf/2102.12206)] [[code](https://github.com/eyalbd2/PADA)] ![](https://img.shields.io/badge/Discrete-blue) ![](https://img.shields.io/badge/Code-red)

4. **Ontology-enhanced Prompt-tuning for Few-shot Learning** (ACM, 2022) [[paper](https://arxiv.org/pdf/2201.11332)] ![](https://img.shields.io/badge/Soft-yellow)   

5. **KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction** (ACM, 2022) [[paper](https://arxiv.org/pdf/2104.07650)] [[code](https://github.com/zjunlp/KnowPrompthttps://github.com/zjunlp/KnowPrompt)] ![](https://img.shields.io/badge/Hybrid-8A2BE2) ![](https://img.shields.io/badge/Code-red) 

6. **Continual Prompt Tuning for Dialog State Tracking** (ACL 2022) [[paper](https://arxiv.org/pdf/2203.06654)] [[code](https://github.com/thu-coai/CPT4DST)] ![](https://img.shields.io/badge/Soft-yellow) ![](https://img.shields.io/badge/Code-red) <br />

7. **Dual Context-Guided Continuous Prompt Tuning for Few-Shot Learning** (Findings, 2022) [[paper](https://aclanthology.org/2022.findings-acl.8.pdf)] ![](https://img.shields.io/badge/Soft-yellow) 

8. **PPT: Pre-trained Prompt Tuning for Few-shot Learning** (ACL, 2022) [[paper](https://arxiv.org/pdf/2109.04332)] [[code](https://github.com/thu-coai/PPT)] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  ![](https://img.shields.io/badge/Code-red)

9. **Prompt Tuning for Discriminative Pre-trained Language Models** (ACL, 2022) [[paper](https://arxiv.org/pdf/2205.11166)] [[code](https://github.com/thunlp/DPT)] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

10. **The Power of Prompt Tuning for Low-Resource Semantic Parsing** (ACL, 2022) [[paper](https://aclanthology.org/2022.acl-short.17.pdf)] ![](https://img.shields.io/badge/Soft-yellow)  

11. **Chinese Spam Detection Based on Prompt Tuning** (Knowledge Systems Institute Graduate School, 2022) [[paper](https://ksiresearch.org/seke/seke22paper/paper120.pdf)] ![](https://img.shields.io/badge/Discrete-blue)  

12. **Novelty Controlled Paraphrase Generation with Retrieval Augmented Conditional Prompt Tuning** (AAAI, 2022) [[paper](https://arxiv.org/pdf/2202.00535)] ![](https://img.shields.io/badge/Soft-yellow)  

13. **AESPrompt: Self-supervised Constraints for Automated Essay Scoring with Prompt Tuning** (The 34th International Conference on Software Engineering and Knowledge Engineering, 2022) [[paper](https://ksiresearch.org/seke/seke22paper/paper095.pdf)] ![](https://img.shields.io/badge/Soft-yellow)  

14. **CUP: Curriculum Learning based Prompt Tuning for Implicit Event Argument Extraction** (IJCAI) [[paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85137248953&origin=resultslist&sort=plf-t&src=s&sid=ecd1e82c238a12612c151df214b07df7&sot=a&sdt=a&cluster=scofreetoread%2C%22all%22%2Ct%2C%22publisherfullgold%22%2Ct%2Bscopubstage%2C%22final%22%2Ct%2Bscosubjabbr%2C%22COMP%22%2Ct%2Bscosubtype%2C%22cp%22%2Ct%2C%22ar%22%2Ct%2Bscolang%2C%22English%22%2Ct%2Bscoexactkeywords%2C%22Image+Features%22%2Cf%2C%22Image+Recognition+And+Understanding%22%2Cf%2C%22Images+Classification%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modalities%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modality%22%2Cf%2C%22Vision-language+Models%22%2Cf%2C%22Learning+For+Vision%22%2Cf%2C%22Vision-language+Model%22%2Cf%2C%22Image+Classification%22%2Cf%2C%22Image+Recognition%22%2Cf%2C%22Visual+Prompts%22%2Cf%2C%22Image+Enhancement%22%2Cf%2C%22Computer+Vision%22%2Cf%2C%22Visual+Languages%22%2Cf%2C%22Multi-modal%22%2Cf%2C%22Multi-modal+Learning%22%2Cf&s=%28TITLE%28%28+%22prompt+tuning%22+%29+OR+%28+%22prefix+tuning%22+%29+OR+%28+%22prompt+learning%22+%29+OR+%28+%22soft+prompt*%22+%29+OR+%28+%22prompt*+optimization%22+%29%29+AND+PUBYEAR+%26gt%3B+2020+AND+PUBYEAR+%26lt%3B+2025+%29&sessionSearchId=ecd1e82c238a12612c151df214b07df7&relpos=11
)] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Hybrid-8A2BE2)  ![](https://img.shields.io/badge/Code-red)

15. **Enhancing Entity Representations with Prompt Learning for Biomedical Entity Linking** (IJCAI) [[paper]( )] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

16. **Relation Extraction as Open-book Examination: Retrieval-enhanced Prompt Tuning** (ACM SIGIR) [[paper]( )] ![](https://img.shields.io/badge/Soft-yellow) ![](https://img.shields.io/badge/Hybrid-8A2BE2)  ![](https://img.shields.io/badge/Code-red)

17. **Towards Unified Conversational Recommender Systems via Knowledge-Enhanced Prompt Learning** (ACM SIGKDD) [[paper]( )] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

18. **Chemical-Protein Relation Extraction with Pre-trained Prompt Tuning** (IEEE 2022) [[paper]( )] ![](https://img.shields.io/badge/Discrete-blue) 

19. **PRCBERT: Prompt Learning for Requirement Classification using BERT-based Pretrained Language Models** (ACM ASE) [[paper]( )] ![](https://img.shields.io/badge/Discrete-blue)  

20. **Prompt Tuning for Multi-Label Text Classification: How to Link Exercises to Knowledge Concepts?** (Applied Sciences (Switzerland)) [[paper]( )] ![](https://img.shields.io/badge/Soft-yellow) 
 
21. **Investigating Prompt Learning for Chinese Few-Shot Text Classification with Pre-Trained Language Models** (Applied Sciences (Switzerland)) [[paper]( )] ![](https://img.shields.io/badge/Soft-yellow)  

22. **Continuous Prompt Tuning Based Textual Entailment Model for E-commerce Entity Typing** (IEEE 2022) [[paper]( )] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  ![](https://img.shields.io/badge/Code-red)

23. **No more fine-tuning? an experimental evaluation of prompt tuning in code intelligence** (ESEC/FSE) [[paper]( )] ![](https://img.shields.io/badge/Soft-yellow)  ![](https://img.shields.io/badge/Code-red)

24. **PTR: Prompt Tuning with Rules for Text Classification** (AI Open) [[paper]( )] ![](https://img.shields.io/badge/Discrete-blue) ![](https://img.shields.io/badge/Code-red) 

25. **Coherent Long Text Generation by Contrastive Soft Prompt** (GEM 2022) [[paper]( )] ![](https://img.shields.io/badge/Soft-yellow)  

26. **ATTEMPT: Parameter-Efficient Multi-task Tuning via Attentional Mixtures of Soft Prompts** (EMNLP 2022) [[paper]()] [[code](https://github.com/AkariAsai/ATTEMPT)] ![](https://img.shields.io/badge/Soft-yellow)  ![](https://img.shields.io/badge/Code-red)

27. **DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation** (EMNLP 2022) [[paper]()] [[code](https://github.com/littlehacker26/Discriminator-Cooperative-Unlikelihood-Prompt-Tuning)] ![](https://img.shields.io/badge/Soft-yellow)  ![](https://img.shields.io/badge/Code-red)

28. **Making Pre-trained Language Models End-to-end Few-shot Learners with Contrastive Prompt Tuning** (WSDM 2023) [[paper]()] [[code](https://github.com/alibaba/EasyNLP?tab=readme-ov-file)] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

29. **A Chinese Few-Shot Text Classification Method Utilizing Improved Prompt Learning and Unlabeled Data** (Applied Sciences (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)  

30. **Knowledge-Guided Prompt Learning for Few-Shot Text Classification** (Electronics (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

31. **Personalized Prompt Learning for Explainable Recommendation** (ACM Transactions on Information Systems) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

32. **Adaptive Prompt Learning-Based Few-Shot Sentiment Analysis** (Neural Processing Letters) [[paper](https://link.springer.com/article/10.1007/s11063-023-11259-4)] [[code](https://github.com/simonZPF/AP)] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

33. **Decomposed Two-Stage Prompt Learning for Few-Shot Named Entity Recognition** (Information (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

34. **A Dual Prompt Learning Framework for Few-Shot Dialogue State Tracking** (ACM 2023) [[paper]()] [[code](https://github.com/YANG-Yuting/DPL)] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

35. **Automating Method Naming with Context-Aware Prompt-Tuning** (IEEE/ACM) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

36. **Translating radiology reports into plain language using ChatGPT and GPT-4 with prompt learning: results, limitations, and potential** (Visual Computing for Industry, Biomedicine, and Art) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)

37. **Multi-Stage Prompt Tuning for Political Perspective Detection in Low-Resource Settings** (Applied Sciences (Switzerland)) [[paper]()] (code available upon request) ![](https://img.shields.io/badge/Soft-yellow) ![](https://img.shields.io/badge/Code-red)

38. **Exploiting Prompt Learning with Pre-Trained Language Models for Alzheimer's Disease Detection** (ICASSP) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)

39. **FedPrompt: Communication-Efficient and Privacy-Preserving Prompt Tuning in Federated Learning** (ICASSP) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

40. **Knowledge-Augmented Frame Semantic Parsing with Hybrid Prompt-Tuning** (ICASSP) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

41. **MedKPL: A heterogeneous knowledge enhanced prompt learning framework for transferable diagnosis** (Journal of Biomedical Informatics) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

42. **Matching Exemplar as Next Sentence Prediction (MeNSP): Zero-Shot Prompt Learning for Automatic Scoring in Science Education** (AIED) [[paper]()] [[code](https://github.com/JacksonWuxs/MeNSP)] ![](https://img.shields.io/badge/Discrete-blue)  ![](https://img.shields.io/badge/Code-red)

43. **Zero-Shot Cross-Lingual Event Argument Extraction with Language-Oriented Prefix-Tuning** (AAAI) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)

44. **A Medical Question Classification Approach Based on Prompt Tuning and Contrastive Learning** (SEKE) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

45. **HGAPT: Heterogeneous Graph Augmented Prompt Tuning for Low-Resource Fake News Detection** (SEKE) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

46. **KLAPrompt: Infusing Semantic Knowledge into Pre-trained Language Models by Long-answer Prompt Learning** (SEKE) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

47. **ETHICIST: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation** (ACL) [[paper]()] [[code](https://github.com/thu-coai/Targeted-Data-Extraction)] ![](https://img.shields.io/badge/Soft-yellow) 

48. **Emotion classification on code-mixed text messages via soft prompt tuning** (WASSA) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Discrete-blue)  

49. **A Unified Generative Retriever for Knowledge-Intensive Language Tasks via Prompt Learning** (SIGIR 2023) [[paper]()] [[code](https://github.com/ict-bigdatalab/UGR)] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow) ![](https://img.shields.io/badge/Hybrid-8A2BE2)  ![](https://img.shields.io/badge/Code-red)

50. **Adversarial Meta Prompt Tuning for Open Compound Domain Adaptive Intent Detection** (SIGIR 2023) [[paper]()] [[code](https://github.com/calubkk/AMPT)] ![](https://img.shields.io/badge/Soft-yellow)  ![](https://img.shields.io/badge/Code-red)

51. **Prompt Learning for News Recommendation** (SIGIR 2023) [[paper]()] [[code](https://github.com/resistzzz/Prompt4NR)] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow) ![](https://img.shields.io/badge/Hybrid-8A2BE2) ![](https://img.shields.io/badge/Code-red)

52. **Prompt Learning to Mitigate Catastrophic Forgetting in Cross-lingual Transfer for Open-domain Dialogue Generation** (SIGIR 2023) [[paper]()] [[code](https://github.com/JeremyLeiLiu/XLinguDial)] ![](https://img.shields.io/badge/Discrete-blue) ![](https://img.shields.io/badge/Code-red)

53. **Soft Prompt Decoding for Multilingual Dense Retrieval** (SIGIR 2023) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

54. **VPN: Variation on Prompt Tuning for Named-Entity Recognition** (Applied Sciences (Switzerland)) [[paper]()] [[code](https://github.com/huniu20/vpn)] ![](https://img.shields.io/badge/Soft-yellow)  ![](https://img.shields.io/badge/Code-red)

55. **Few-shot Sentiment Analysis Based on Adaptive Prompt Learning and Contrastive Learning** (Information Technology and Control) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

56. **Instance-Aware Prompt Learning for Language Understanding and Generation** (ACM Transactions on Asian and Low-Resource Language Information Processing) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) [[code](https://github.com/jinfeihu-stan/IPL)] ![](https://img.shields.io/badge/Code-red)

57. **A Prompt Learning Based Intent Recognition Method on a Chinese Implicit Intent Dataset CIID** (Neural Processing Letters) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

58. **Prompt Learning with Structured Semantic Knowledge Makes Pre-Trained Language Models Better** (Electronics (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)  

59. **APICom: Automatic API Completion via Prompt Learning and Adversarial Training-based Data Augmentation** (ACM International Conference Proceeding Series) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

60. **Medical text classification based on the discriminative pre-training model and prompt-tuning** (Digital Health) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

61. **Research on the Application of Prompt Learning Pretrained Language Model in Machine Translation Task with Reinforcement Learning** (Electronics (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

62. **Simple Knowledge Graph Completion Model Based on Differential Negative Sampling and Prompt Learning** (Information (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

63. **Clinical Prompt Learning With Frozen Language Models** (IEEE Transactions on Neural Networks and Learning Systems) [[paper]()]  

64. **One Model for All Domains: Collaborative Domain-Prefix Tuning for Cross-Domain NER** (IJCAI) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)

65. **Generating Chinese Event Extraction Method Based on ChatGPT and Prompt Learning** (Applied Sciences (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

66. **ConKgPrompt: Contrastive Sample Method Based on Knowledge-Guided Prompt Learning for Text Classification** (Electronics (Switzerland)) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

67. **ContrastNER: Contrastive-based Prompt Tuning for Few-shot NER** (IEEE/COMPSAC) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

68. **Prompt-Learning for Cross-Lingual Relation Extraction** (IJCNN) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)![](https://img.shields.io/badge/Soft-yellow)![](https://img.shields.io/badge/Hybrid-8A2BE2)  

69. **Parameter-Efficient Low-Resource Dialogue State Tracking by Prompt Tuning** (INTERSPEECH) [[paper]()]  ![](https://img.shields.io/badge/Soft-yellow) 

70. **Towards using Few-Shot Prompt Learning for Automating Model Completion** (ICSE-NIER) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

71. **Prompt-Learning for Short Text Classification** (IEEE) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

72. **MsPrompt: Multi-step prompt learning for debiasing few-shot event detection** (Information Processing and Management) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

73. **Robust scientific text classification using prompt tuning based on data augmentation with L2 regularization** (Information Processing and Management) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

74. **Soft prompt enhanced joint learning for cross-domain aspect-based sentiment analysis** (Intelligent Systems with Applications) [[paper]()](https://img.shields.io/badge/Soft-yellow)  

75. **Knowledge Prompt-tuning for Sequential Recommendation** (MM 2023) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

76. **REKP: Refined External Knowledge into Prompt-Tuning for Few-Shot Text Classification** (Mathematics) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

77. **Contrastive Graph Prompt-tuning for Cross-domain Recommendation** (ACM) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

78. **Domain-Enhanced Prompt Learning for Chinese Implicit Hate Speech Detection** (IEEE) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

79. **SPeC: A Soft Prompt-Based Calibration on Performance Variability of Large Language Model in Clinical Notes Summarization** (Journal of Biomedical Informatics) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

80. **Leveraging Chain-of-Thought to Enhance Stance Detection with Prompt-Tuning** (Mathematics) [[paper]()](https://img.shields.io/badge/Discrete-blue) 

81. **Prompt to Transfer: Sim-to-Real Transfer for Traffic Signal Control with Prompt Learning** (AAAI) [[paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85189348156&origin=resultslist&sort=tp-f&src=s&sid=c1a88076e2d4998dd920b032a31fb49f&sot=a&sdt=a&cluster=scofreetoread%2C%22all%22%2Ct%2C%22publisherfullgold%22%2Ct%2Bscopubstage%2C%22final%22%2Ct%2Bscosubjabbr%2C%22COMP%22%2Ct%2Bscosubtype%2C%22cp%22%2Ct%2C%22ar%22%2Ct%2Bscolang%2C%22English%22%2Ct%2Bscoexactkeywords%2C%22Image+Features%22%2Cf%2C%22Image+Recognition+And+Understanding%22%2Cf%2C%22Images+Classification%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modalities%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modality%22%2Cf%2C%22Vision-language+Models%22%2Cf%2C%22Learning+For+Vision%22%2Cf%2C%22Vision-language+Model%22%2Cf%2C%22Image+Classification%22%2Cf%2C%22Image+Recognition%22%2Cf%2C%22Visual+Prompts%22%2Cf%2C%22Image+Enhancement%22%2Cf%2C%22Computer+Vision%22%2Cf%2C%22Visual+Languages%22%2Cf%2C%22Multi-modal%22%2Cf%2C%22Multi-modal+Learning%22%2Cf&s=%28TITLE%28%28+%22prompt+tuning%22+%29+OR+%28+%22prefix+tuning%22+%29+OR+%28+%22prompt+learning%22+%29+OR+%28+%22soft+prompt*%22+%29+OR+%28+%22prompt*+optimization%22+%29%29+AND+PUBYEAR+%26gt%3B+2020+AND+PUBYEAR+%26lt%3B+2025+%29&sessionSearchId=c1a88076e2d4998dd920b032a31fb49f&relpos=62)] ![](https://img.shields.io/badge/Discrete-blue)

82. **Prompt Optimization in Large Language Models** (Mathematics) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

83. **HGPrompt: Bridging Homogeneous and Heterogeneous Graphs for Few-Shot Prompt Learning** (AAAI) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

84. **On Unsupervised Domain Adaptation: Pseudo Label Guided Mixup for Adversarial Prompt Tuning** (Proceedings of the AAAI Conference on Artificial Intelligence) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

85. **Prompt to Transfer: Sim-to-Real Transfer for Traffic Signal Control with Prompt Learning** (AAAI) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) 

86. **Model tuning or prompt Tuning? a study of large language models for clinical concept and relation extraction** (Journal of Biomedical Informatics) [[paper]()]  

87. **ProRLearn: boosting prompt tuning-based vulnerability detection by reinforcement learning** (ASE) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

88. **Affective Prompt-Tuning-Based Language Model for Semantic-Based Emotional Text Generation** (International Journal on Semantic Web and Information Systems) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

89. **Enhancing Zero-Shot Stance Detection with Contrastive and Prompt Learning** (Entropy) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

90. **Leveraging Pretrained Language Models for Enhanced Entity-Matching: A Comprehensive Study of Fine-Tuning and Prompt-Learning Paradigms** (International Journal of Intelligent Systems) [[paper]()]  

91. **Knowledge-Enhanced Prompt Learning for Few-Shot Text Classification** (Big Data and Cognitive Computing) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

92. **ConsPrompt: Exploiting Contrastive Samples for Fewshot Prompt Learning** (ICASSP) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

93. **HetGPT: Harnessing the Power of Prompt Tuning in Pre-Trained Heterogeneous Graph Neural Networks** (ACM) 
[[paper]()] ![](https://img.shields.io/badge/Soft-yellow)

94. **Adapting LLMs for Efficient Context Processing through Soft Prompt Compression** (ACM) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

95. **Can we Soft Prompt LLMs for Graph Learning Tasks?** (ACM) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow)  

96. **You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content** (IEEE) [[paper]()]  

97. **KBPT: knowledge-based prompt tuning for zero-shot relation triplet extraction** (PeerJ Computer Science) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

98. **Enhancing Cross-Lingual Sarcasm Detection by a Prompt Learning Framework with Data Augmentation and Contrastive Learning** (Electronics) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

99. **A Rumors Detection Method Using T5-Based Prompt Learning** (International Journal of Data Warehousing and Mining) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

100. **Meta Soft Prompting and Learning** (APSIPA) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

101. **Exploring Universal Intrinsic Task Subspace for Few-Shot Learning via Prompt Tuning** (IEEE/ACM) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) ![](https://img.shields.io/badge/Soft-yellow)

102. **Prompt Tuning on Graph-Augmented Low-Resource Text Classification** (IEEE) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue) ![](https://img.shields.io/badge/Soft-yellow)  

103. **Prompt learning for metonymy resolution: Enhancing performance with internal prior knowledge of pre-trained language models** (Knowledge-Based Systems) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

104. **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with LLMs** (CCS) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

105. **RPEPL: Tibetan Sentiment Analysis Based on Relative Position Encoding and Prompt Learning** (ACM) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

106. **Application of Prompt Learning Models in Identifying the Collaborative Problem Solving Skills in an Online Task** (CSCW) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

107. **Prompt Tuning for Item Cold-start Recommendation** (ACM) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2) 

108. **G-SAP: Graph-based Structure-Aware Prompt Learning over Heterogeneous Knowledge for Commonsense Question Answering** (ICMR) [[paper]()] ![](https://img.shields.io/badge/Soft-yellow) 

109. **Graph‑Enhanced Prompt Learning for Personalized Review Generation** (Data Science and Engineering) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2) 

110. **Multi-Relation Extraction for Cybersecurity Based on Ontology Rule-Enhanced Prompt Learning** (Electronics) [[paper]()] ![](https://img.shields.io/badge/Discrete-blue)  

111. **TopicTag: Automatic Annotation of NMF Topic Models Using Chain of Thought and Prompt Tuning with LLMs** (ACM) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

112. **Knowledge-injected Prompt Learning for Chinese Biomedical Entity Normalization** (ACM) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2) 

113. **Graph Intelligence with Large Language Models and Prompt Learning** (ACM SIGKDD) [[paper]()] ![](https://img.shields.io/badge/Hybrid-8A2BE2)  

<a id="query"></a>
## 🔍 Query
The query corresponding to the search for the papers listed above was executed on Scopus and is specified below to provide maximum reproducibility.

```plaintext
(TITLE(( "prompt tuning" ) OR ( "prefix tuning" ) OR ( "prompt learning" ) OR ( "soft prompt*" ) OR ( "prompt* optimization" )) AND PUBYEAR > 2020 AND PUBYEAR < 2025 AND ( LIMIT-TO ( SUBJAREA,"COMP" ) )  AND ( LIMIT-TO ( PUBSTAGE,"final" ) )  AND ( LIMIT-TO ( DOCTYPE,"cp" ) OR LIMIT-TO ( DOCTYPE,"ar" ) )  AND ( LIMIT-TO ( LANGUAGE,"English" ) )  AND ( LIMIT-TO ( OA,"all" ) OR LIMIT-TO ( OA,"publisherfullgold" ) )  AND ( EXCLUDE ( EXACTKEYWORD,"Image Features" ) OR EXCLUDE ( EXACTKEYWORD,"Image Recognition And Understanding" ) OR EXCLUDE ( EXACTKEYWORD,"Images Classification" ) OR EXCLUDE ( EXACTKEYWORD,"Vision + Language And/or Other Modalities" ) OR EXCLUDE ( EXACTKEYWORD,"Vision + Language And/or Other Modality" ) OR EXCLUDE ( EXACTKEYWORD,"Vision-language Models" ) OR EXCLUDE ( EXACTKEYWORD,"Learning For Vision" ) OR EXCLUDE ( EXACTKEYWORD,"Vision-language Model" ) OR EXCLUDE ( EXACTKEYWORD,"Image Classification" ) OR EXCLUDE ( EXACTKEYWORD,"Image Recognition" ) OR EXCLUDE ( EXACTKEYWORD,"Visual Prompts" ) OR EXCLUDE ( EXACTKEYWORD,"Image Enhancement" ) OR EXCLUDE ( EXACTKEYWORD,"Computer Vision" ) OR EXCLUDE ( EXACTKEYWORD,"Visual Languages" ) OR EXCLUDE ( EXACTKEYWORD,"Multi-modal" ) OR EXCLUDE ( EXACTKEYWORD,"Multi-modal Learning" ) ) )
```

<a id="citation"></a>
## 🚩 Citation

Please cite our repo if find our work useful.

```bibtex
@misc{,
  author = {},
  title = {},
  year = {},
  publisher = {},
  journal = {},
  howpublished = {\url{}},
}
```

You are also welcome to cite our papers.

```bibtex
@misc{,
      title={}, 
      author={},
      year={},
      eprint={},
      archivePrefix={},
      primaryClass={},
      url={}, 
}
```

<a id="contribution"></a>
## 🎉 Contribution

We thank all contributors to this repo
<!-- our names and email here -->

<a id="acknowledgement"></a>
## 🤝 Acknowledgement

We referred to the template of [Awesome Data Contamination](https://github.com/lyy1994/awesome-data-contamination). Thank for the helpful contribution!

<p align="right"><a href="#top">🔝Back to top</a></p>

