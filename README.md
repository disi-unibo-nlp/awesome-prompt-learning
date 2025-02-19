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
| ![](https://img.shields.io/badge/Cloze-7c7f55) | This paper use prompts in a Cloze notation |
| ![](https://img.shields.io/badge/Prefix-d98d49) | This paper use prompts in a Prefix notation |
| ![](https://img.shields.io/badge/Soft-e16d50) | This paper use Soft prompts |
| ![](https://img.shields.io/badge/PEFT-d98d49) | This paper trains solely the soft prompts in a PEFT methodology |
| ![](https://img.shields.io/badge/Non%0APEFT-e8b85c) | This paper trains the model and the soft prompts in a non PEFT methodology |
| ![](https://img.shields.io/badge/Discrete-84648a) | This paper use Dicrete prompts |
| ![](https://img.shields.io/badge/Token%0ASearch-6d738d) | This paper performs Token Search to discover discrete tokens |
| ![](https://img.shields.io/badge/Template%0ADefinition-799098)| This paper performs Template Definition to discover the discrete prompt template |
| ![](https://img.shields.io/badge/Context%0Definition-94b5a3) | This paper performs Context Definition to discover discrete tokens |
| ![](https://img.shields.io/badge/Hybrid-c381a7) | This paper use Hybrid prompts (Discrete + Soft) |

<a id="list"></a>
### 🎯 The List

> [!Note]
> The list is ordered based on the publication date of the paper, from oldest to newest.

1. **AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts** (EMNLP, 2020) [[paper]()] [[code](https://ucinlp.github.io/autoprompt/)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Token%0ASearch-6d738d)

2. **BERTese: Learning to Speak to BERT** (EACL, 2021) [[paper]()] [[code](https://github.com/adihaviv/bertese)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) 

1. **Prefix-Tuning: Optimizing Continuous Promts for Generation** (ACL, 2021) [[paper]()] [[code](https://github.com/XiangLi1999/PrefixTuning)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

1. **Discrete and Soft Prompting for Multilingual Models** (EMNLP, 2021) [[paper](https://aclanthology.org/2021.emnlp-main.672.pdf)] [[code](https://github.com/mprompting/xlmrprompt)]<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

2.  **The Power of Scale for Parameter-Efficient Prompt Tuning** (EMNLP, 2021) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

3. **PADA: Example-based Prompt Learning for on-the-fly Adaptation to Unseen Domains** (ACL, 2022) [[paper](https://arxiv.org/pdf/2102.12206)] [[code](https://github.com/eyalbd2/PADA)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

4. **Ontology-enhanced Prompt-tuning for Few-shot Learning** (ACM, 2022) [[paper](https://arxiv.org/pdf/2201.11332)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

5. **KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction** (ACM, 2022) [[paper](https://arxiv.org/pdf/2104.07650)] [[code](https://github.com/zjunlp/KnowPrompthttps://github.com/zjunlp/KnowPrompt)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

6. **Continual Prompt Tuning for Dialog State Tracking** (ACL 2022) [[paper](https://arxiv.org/pdf/2203.06654)] [[code](https://github.com/thu-coai/CPT4DST)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

7. **P-Tuning: Prompt Tuning Can Be Comparable to Fine-tuning Across Scales and Tasks** (ACL 2022) [[paper]()] [[code](https://github.com/THUDM/P-tuning-v2)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

8. **Dual Context-Guided Continuous Prompt Tuning for Few-Shot Learning** (Findings, 2022) [[paper](https://aclanthology.org/2022.findings-acl.8.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

9. **PPT: Pre-trained Prompt Tuning for Few-shot Learning** (ACL, 2022) [[paper](https://arxiv.org/pdf/2109.04332)] [[code](https://github.com/thu-coai/PPT)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

10. **The Power of Prompt Tuning for Low-Resource Semantic Parsing** (ACL, 2022) [[paper](https://aclanthology.org/2022.acl-short.17.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

12. **Novelty Controlled Paraphrase Generation with Retrieval Augmented Conditional Prompt Tuning** (AAAI, 2022) [[paper](https://arxiv.org/pdf/2202.00535)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

13. **AESPrompt: Self-supervised Constraints for Automated Essay Scoring with Prompt Tuning** (The 34th International Conference on Software Engineering and Knowledge Engineering, 2022) [[paper](https://ksiresearch.org/seke/seke22paper/paper095.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

15. **Enhancing Entity Representations with Prompt Learning for Biomedical Entity Linking** (IJCAI) [[paper]( )] [[code](https://github.com/TiantianZhu110/BioPRO)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

16. **Relation Extraction as Open-book Examination: Retrieval-enhanced Prompt Tuning** (ACM SIGIR) [[paper]( )]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

17. **Towards Unified Conversational Recommender Systems via Knowledge-Enhanced Prompt Learning** (ACM SIGKDD) [[paper]( )]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 
 
21. **Investigating Prompt Learning for Chinese Few-Shot Text Classification with Pre-Trained Language Models** (Applied Sciences (Switzerland)) [[paper]( )]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

22. **RLPrompt: Optimizing Discrete Text Prompts with Reinforcement Learning** (EMNLP 2022) [[paper]( )] [[code](https://github.com/mingkaid/rl-prompt)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55) ![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Token%0ASearch-6d738d)

23. **Continuous Prompt Tuning Based Textual Entailment Model for E-commerce Entity Typing** (IEEE 2022) [[paper]( )]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

24. **PTR: Prompt Tuning with Rules for Text Classification** (AI Open) [[paper]( )] [[code](https://github.com/thunlp/PTR)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

25. **Coherent Long Text Generation by Contrastive Soft Prompt** (GEM 2022) [[paper]( )]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

26. **ATTEMPT: Parameter-Efficient Multi-task Tuning via Attentional Mixtures of Soft Prompts** (EMNLP 2022) [[paper]()] [[code](https://github.com/AkariAsai/ATTEMPT)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

27. **DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation** (EMNLP 2022) [[paper]()] [[code](https://github.com/littlehacker26/Discriminator-Cooperative-Unlikelihood-Prompt-Tuning)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

28. **Making Pre-trained Language Models End-to-end Few-shot Learners with Contrastive Prompt Tuning** (WSDM 2023) [[paper]()] [[code](https://github.com/alibaba/EasyNLP?tab=readme-ov-file)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

29. **A Chinese Few-Shot Text Classification Method Utilizing Improved Prompt Learning and Unlabeled Data** (Applied Sciences (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

30. **Knowledge-Guided Prompt Learning for Few-Shot Text Classification** (Electronics (Switzerland)) [[paper]()<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

31. **Personalized Prompt Learning for Explainable Recommendation** (ACM Transactions on Information Systems) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

32. **Adaptive Prompt Learning-Based Few-Shot Sentiment Analysis** (Neural Processing Letters) [[paper](https://link.springer.com/article/10.1007/s11063-023-11259-4)] [[code](https://github.com/simonZPF/AP)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

33. **Decomposed Two-Stage Prompt Learning for Few-Shot Named Entity Recognition** (Information (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

35. **Automating Method Naming with Context-Aware Prompt-Tuning** (IEEE/ACM) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

37. **Multi-Stage Prompt Tuning for Political Perspective Detection in Low-Resource Settings** (Applied Sciences (Switzerland)) [[paper]()] (code available upon request)<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

39. **FedPrompt: Communication-Efficient and Privacy-Preserving Prompt Tuning in Federated Learning** (ICASSP) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

40. **Knowledge-Augmented Frame Semantic Parsing with Hybrid Prompt-Tuning** (ICASSP) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

41. **MedKPL: A heterogeneous knowledge enhanced prompt learning framework for transferable diagnosis** (Journal of Biomedical Informatics) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

43. **Zero-Shot Cross-Lingual Event Argument Extraction with Language-Oriented Prefix-Tuning** (AAAI) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

46. **KLAPrompt: Infusing Semantic Knowledge into Pre-trained Language Models by Long-answer Prompt Learning** (SEKE) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

47. **ETHICIST: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation** (ACL) [[paper]()] [[code](https://github.com/thu-coai/Targeted-Data-Extraction)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

48. **Emotion classification on code-mixed text messages via soft prompt tuning** (WASSA) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

49. **A Unified Generative Retriever for Knowledge-Intensive Language Tasks via Prompt Learning** (SIGIR 2023) [[paper]()] [[code](https://github.com/ict-bigdatalab/UGR)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

50. **Adversarial Meta Prompt Tuning for Open Compound Domain Adaptive Intent Detection** (SIGIR 2023) [[paper]()] [[code](https://github.com/calubkk/AMPT)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

51. **Prompt Learning for News Recommendation** (SIGIR 2023) [[paper]()] [[code](https://github.com/resistzzz/Prompt4NR)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

53. **Soft Prompt Decoding for Multilingual Dense Retrieval** (SIGIR 2023) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

54. **VPN: Variation on Prompt Tuning for Named-Entity Recognition** (Applied Sciences (Switzerland)) [[paper]()] [[code](https://github.com/huniu20/vpn)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

55. **Few-shot Sentiment Analysis Based on Adaptive Prompt Learning and Contrastive Learning** (Information Technology and Control) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)   

56. **Instance-Aware Prompt Learning for Language Understanding and Generation** (ACM Transactions on Asian and Low-Resource Language Information Processing) [[paper]()] [[code](https://github.com/jinfeihu-stan/IPL)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

58. **Prompt Learning with Structured Semantic Knowledge Makes Pre-Trained Language Models Better** (Electronics (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

59. **GPT Understands, Too** (AI Open) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

60. **APICom: Automatic API Completion via Prompt Learning and Adversarial Training-based Data Augmentation** (ACM International Conference Proceeding Series) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

61. **Research on the Application of Prompt Learning Pretrained Language Model in Machine Translation Task with Reinforcement Learning** (Electronics (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) 

62. **Simple Knowledge Graph Completion Model Based on Differential Negative Sampling and Prompt Learning** (Information (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

64. **One Model for All Domains: Collaborative Domain-Prefix Tuning for Cross-Domain NER** (IJCAI) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

65. **Generating Chinese Event Extraction Method Based on ChatGPT and Prompt Learning** (Applied Sciences (Switzerland)) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

67. **ContrastNER: Contrastive-based Prompt Tuning for Few-shot NER** (IEEE/COMPSAC) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

68. **Prompt-Learning for Cross-Lingual Relation Extraction** (IJCNN) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

69. **Parameter-Efficient Low-Resource Dialogue State Tracking by Prompt Tuning** (INTERSPEECH) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

72. **MsPrompt: Multi-step prompt learning for debiasing few-shot event detection** (Information Processing and Management) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

74. **Soft prompt enhanced joint learning for cross-domain aspect-based sentiment analysis** (Intelligent Systems with Applications) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

75. **Knowledge Prompt-tuning for Sequential Recommendation** (MM 2023) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)  

78. **Domain-Enhanced Prompt Learning for Chinese Implicit Hate Speech Detection** (IEEE) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

79. **SPeC: A Soft Prompt-Based Calibration on Performance Variability of Large Language Model in Clinical Notes Summarization** (Journal of Biomedical Informatics) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

81. **Prompt to Transfer: Sim-to-Real Transfer for Traffic Signal Control with Prompt Learning** (AAAI) [[paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85189348156&origin=resultslist&sort=tp-f&src=s&sid=c1a88076e2d4998dd920b032a31fb49f&sot=a&sdt=a&cluster=scofreetoread%2C%22all%22%2Ct%2C%22publisherfullgold%22%2Ct%2Bscopubstage%2C%22final%22%2Ct%2Bscosubjabbr%2C%22COMP%22%2Ct%2Bscosubtype%2C%22cp%22%2Ct%2C%22ar%22%2Ct%2Bscolang%2C%22English%22%2Ct%2Bscoexactkeywords%2C%22Image+Features%22%2Cf%2C%22Image+Recognition+And+Understanding%22%2Cf%2C%22Images+Classification%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modalities%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modality%22%2Cf%2C%22Vision-language+Models%22%2Cf%2C%22Learning+For+Vision%22%2Cf%2C%22Vision-language+Model%22%2Cf%2C%22Image+Classification%22%2Cf%2C%22Image+Recognition%22%2Cf%2C%22Visual+Prompts%22%2Cf%2C%22Image+Enhancement%22%2Cf%2C%22Computer+Vision%22%2Cf%2C%22Visual+Languages%22%2Cf%2C%22Multi-modal%22%2Cf%2C%22Multi-modal+Learning%22%2Cf&s=%28TITLE%28%28+%22prompt+tuning%22+%29+OR+%28+%22prefix+tuning%22+%29+OR+%28+%22prompt+learning%22+%29+OR+%28+%22soft+prompt*%22+%29+OR+%28+%22prompt*+optimization%22+%29%29+AND+PUBYEAR+%26gt%3B+2020+AND+PUBYEAR+%26lt%3B+2025+%29&sessionSearchId=c1a88076e2d4998dd920b032a31fb49f&relpos=62)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

82. **Prompt Optimization in Large Language Models** (Mathematics) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)  

83. **On Unsupervised Domain Adaptation: Pseudo Label Guided Mixup for Adversarial Prompt Tuning** (Proceedings of the AAAI Conference on Artificial Intelligence) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

86. **ProRLearn: boosting prompt tuning-based vulnerability detection by reinforcement learning** (ASE) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

87. **Affective Prompt-Tuning-Based Language Model for Semantic-Based Emotional Text Generation** (International Journal on Semantic Web and Information Systems) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

88. **Enhancing Zero-Shot Stance Detection with Contrastive and Prompt Learning** (Entropy) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

90. **Knowledge-Enhanced Prompt Learning for Few-Shot Text Classification** (Big Data and Cognitive Computing) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

91. **ConsPrompt: Exploiting Contrastive Samples for Fewshot Prompt Learning** (ICASSP) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

93. **Adapting LLMs for Efficient Context Processing through Soft Prompt Compression** (ACM) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

94. **Can we Soft Prompt LLMs for Graph Learning Tasks?** (ACM) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

96. **KBPT: knowledge-based prompt tuning for zero-shot relation triplet extraction** (PeerJ Computer Science) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

98. **A Rumors Detection Method Using T5-Based Prompt Learning** (International Journal of Data Warehousing and Mining) [[paper]()]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

99. **Meta Soft Prompting and Learning** (APSIPA) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

102. **Prompt Tuning on Graph-Augmented Low-Resource Text Classification** (IEEE) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)   

103. **Prompt learning for metonymy resolution: Enhancing performance with internal prior knowledge of pre-trained language models** (Knowledge-Based Systems) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

105. **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with LLMs** (CCS) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

106. **RPEPL: Tibetan Sentiment Analysis Based on Relative Position Encoding and Prompt Learning** (ACM) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

108. **Prompt Tuning for Item Cold-start Recommendation** (ACM) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

109. **G-SAP: Graph-based Structure-Aware Prompt Learning over Heterogeneous Knowledge for Commonsense Question Answering** (ICMR) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

110. **Graph‑Enhanced Prompt Learning for Personalized Review Generation** (Data Science and Engineering) [[paper]()]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

111. **Multi-Relation Extraction for Cybersecurity Based on Ontology Rule-Enhanced Prompt Learning** (Electronics) [[paper]()]<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

113. **Knowledge-injected Prompt Learning for Chinese Biomedical Entity Normalization** (ACM) [[paper]()]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

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

