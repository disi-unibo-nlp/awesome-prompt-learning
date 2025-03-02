<div id="user-content-toc">
  <ul align="center" style="list-style: none;">
    <summary>
      <h1>🌟 Awesome Prompt Learning 🌟</h1><br>
      A curated repository of <i>automated prompt</i> techniques
    </summary>
  </ul>
</div>

[![Awesome](https://awesome.re/badge.svg)](https://github.com/disi-unibo-nlp/awesome-prompt-learning?tab=readme-ov-file) 
<!--[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT) -->

This curated repository is your gateway to automated prompt engineering, where models learn to craft their own prompts, replacing the tedious, trial-and-error process of manual prompt design!

The following work provides a collection of the most recent papers about automated prompt learning techniques with corresponding, approach-specific, tags to help users navigate this new paradigm. 
<br>
<br>
<p align="right"><br><i>"<br>Consider a future where the arduous art of manually crafting prompts,<br>once mired in endless cycles of trial and error, becomes but a relic of our past.<br>In that future, these intelligent machines shall, by their own inherent capacities,<br>discern the optimal prompt to address any challenge.<br>"</i>

## 🔔 News

- **[2025-02-15]** Creation of the repository to maintain a list of papers about *Automated prompt techniques*.

## 🔍 Contents

- [🌟 Prompt Learning](#intro)
- [📜 Papers](#papers)
    - [🏷️ Tagset](#tagset)
    - [🎯 The List](#list)
- [💾 Datasets](#datasets)
- [🔍 Query](#query)<!--- [🚩 Citation](#citation)-->
- [🎉 Contribution](#contribution)
- [🤝 Acknowledgement](#acknowledgement)

<a id="intro"></a>
## 🌟 What's Prompt Learning?

Prompt Learning refers to the group of techniques that use task-specific input sequences--prompts--to steer the Pre-Trained Large Language Model into producing a desired output.
This paradigm shift from "_pre-train, fine-tune_" to "_pre-train, prompt, predict_" aims at better navigating a model's knowledge.
Automated prompt learning techniques overcome manual engineering challenges, automatically crafting and/or optimizing prompts, unlocking superior task performance.

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

1. **AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts** (EMNLP, 2020) [[paper](https://aclanthology.org/2020.emnlp-main.346.pdf)] [[code](https://ucinlp.github.io/autoprompt/)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Token%0ASearch-6d738d)

2. **BERTese: Learning to Speak to BERT** (EACL, 2021) [[paper](https://aclanthology.org/2021.eacl-main.316.pdf)] [[code](https://github.com/adihaviv/bertese)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) 

1. **Prefix-Tuning: Optimizing Continuous Prompts for Generation** (ACL, 2021) [[paper](https://aclanthology.org/2021.acl-long.353.pdf)] [[code](https://github.com/XiangLi1999/PrefixTuning)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

1. **Discrete and Soft Prompting for Multilingual Models** (EMNLP, 2021) [[paper](https://aclanthology.org/2021.emnlp-main.672.pdf)] [[code](https://github.com/mprompting/xlmrprompt)]<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

2.  **The Power of Scale for Parameter-Efficient Prompt Tuning** (EMNLP, 2021) [[paper](https://aclanthology.org/2021.emnlp-main.243.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

3. **PADA: Example-based Prompt Learning for on-the-fly Adaptation to Unseen Domains** (ACL, 2022) [[paper](https://arxiv.org/pdf/2102.12206)] [[code](https://github.com/eyalbd2/PADA)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

4. **Ontology-enhanced Prompt-tuning for Few-shot Learning** (ACM, 2022) [[paper](https://arxiv.org/pdf/2201.11332)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

5. **KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction** (ACM, 2022) [[paper](https://arxiv.org/pdf/2104.07650)] [[code](https://github.com/zjunlp/KnowPrompthttps://github.com/zjunlp/KnowPrompt)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

6. **Continual Prompt Tuning for Dialog State Tracking** (ACL 2022) [[paper](https://arxiv.org/pdf/2203.06654)] [[code](https://github.com/thu-coai/CPT4DST)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

7. **P-Tuning: Prompt Tuning Can Be Comparable to Fine-tuning Across Scales and Tasks** (ACL 2022) [[paper](https://aclanthology.org/2022.acl-short.8.pdf)] [[code](https://github.com/THUDM/P-tuning-v2)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

8. **Dual Context-Guided Continuous Prompt Tuning for Few-Shot Learning** (Findings, 2022) [[paper](https://aclanthology.org/2022.findings-acl.8.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

9. **PPT: Pre-trained Prompt Tuning for Few-shot Learning** (ACL, 2022) [[paper](https://arxiv.org/pdf/2109.04332)] [[code](https://github.com/thu-coai/PPT)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

10. **The Power of Prompt Tuning for Low-Resource Semantic Parsing** (ACL, 2022) [[paper](https://aclanthology.org/2022.acl-short.17.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

12. **Novelty Controlled Paraphrase Generation with Retrieval Augmented Conditional Prompt Tuning** (AAAI, 2022) [[paper](https://arxiv.org/pdf/2202.00535)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

13. **AESPrompt: Self-supervised Constraints for Automated Essay Scoring with Prompt Tuning** (The 34th International Conference on Software Engineering and Knowledge Engineering, 2022) [[paper](https://ksiresearch.org/seke/seke22paper/paper095.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

15. **Enhancing Entity Representations with Prompt Learning for Biomedical Entity Linking** (IJCAI) [[paper](https://www.ijcai.org/proceedings/2022/0560.pdf)] [[code](https://github.com/TiantianZhu110/BioPRO)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

16. **Relation Extraction as Open-book Examination: Retrieval-enhanced Prompt Tuning** (ACM SIGIR) [[paper](https://dl.acm.org/doi/10.1145/3477495.3531746)] [[code](https://github.com/zjunlp/PromptKG/tree/main/research/RetrievalRE)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

17. **Towards Unified Conversational Recommender Systems via Knowledge-Enhanced Prompt Learning** (ACM SIGKDD) [[paper](https://dl.acm.org/doi/10.1145/3534678.3539382)] [[code](https://github.com/RUCAIBox/UniCRS)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 
 
21. **Investigating Prompt Learning for Chinese Few-Shot Text Classification with Pre-Trained Language Models** (Applied Sciences (Switzerland)) [[paper](https://doi.org/10.3390/app122111117)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

22. **RLPrompt: Optimizing Discrete Text Prompts with Reinforcement Learning** (EMNLP 2022) [[paper](https://aclanthology.org/2022.emnlp-main.222.pdf)] [[code](https://github.com/mingkaid/rl-prompt)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55) ![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Token%0ASearch-6d738d)

23. **Continuous Prompt Tuning Based Textual Entailment Model for E-commerce Entity Typing** (IEEE 2022) [[paper](https://doi.org/10.1109/BigData55660.2022.10020766)] [[code](https://github.com/YiboWANG214/CTM)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

24. **PTR: Prompt Tuning with Rules for Text Classification** (AI Open) [[paper](https://pdf.sciencedirectassets.com/777606/1-s2.0-S2666651022X00028/1-s2.0-S2666651022000183/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLWVhc3QtMSJIMEYCIQDQCjVW987ktT3ZtFB9K%2B3wh%2BrqYQVfQYzT5OU3lKbUBgIhAJSHAIq8evjTbd2k8AqHNOHZfnykvQvje9hofrhDEZ1LKrwFCKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1IgzdnGVin5bXYUW9LGUqkAUazKC5KFTsrUOzdDZaMpnVRtt9NrmDb3sPZ%2BaVsw22Qa%2FnGRgoy3sVYw7vaDHwpzTE8h0FrQ%2FqVmImdCX4eSh5ZCVGITJmf%2FVUYBZgaKnaB5z1MCgwRVtAmQxZBeulSgQrQWH7v7ljzL9zlWkO%2FYRlm8rQASekRTann5h7%2FYZQQ%2F7WPD54STCPPIn1mvzPrnG4xPglTFzR9aSsWgQI1eitBrdV7J4a%2BpgNITjtrRbXvFiRxBjJCkMdR22OpEvt9nEJWYHGECbw1nao5Q7w%2F02oL8yOEd4xX5%2BC%2B4R%2Blrp5v%2FNbIjZNvJi89GPnh9qNzc7CNxuozczO51HOgcYfuJpMLO3QAARfV7TOAM1xUvzPKJWZqR6aBnxvr3GoqlV1C5jQit3vtEyYtROTEoJM2YlZAUKk1ALzRGWPbyohrw0HuSnh2NgNjXVqSOfPebXNLtrK%2FVU%2BvbLGDHbCiOMlTSaDFRcn8Ny3H4wz%2FIgwJdXCNITOJokZJ8kCap%2FRmbf3XiS6S0tGrtbzYiXpQJgqRRWv75Isad5hLhSs%2BYorbVTjbwhvudqgJkRBWdgwnHYNQ2MH6rFuX3Qj15rfwaFwO%2BncZcVrFh9VS4BB%2FdLcWyDifPY1k6WoTqXRWTU42hAgQDOL2row1Q95yKCAhQdQLzUfA%2BcSXiSm577dR1Ekwvs5k6DSwJjfMB%2FhP66gHV95rEWxWNsarBNbxF4Ow3Z7r3vV11of71E7r0fbCCMZjUHpZ8pjAYpUaTYtaibjl2OHiwTH31ycsFybGlAxXQxXqXxta1EV8naK5eTt4VoaosHJoYKZcEMKfU5UbMVlKkwdt1K0Y%2Fgp8WzqClefr3sFuUUR%2F1N54cIb3l8XVzao3FkN6DDKtte9BjqwAUOE%2FF6cdfxX1XvvVJjyv7YhPMM96wa0qWxnqMv0UVhKzP3kp0RULrCXQIHwrJn%2BBr%2BOeJXzKQSCl9EIO4l7ZGQT0MmzVFrL%2FQM6biBEZuYZQIHSPEhov6UrTfF6s50kq0l4rwVZFX33LfyV%2BgOKQjwAgL99SAazk6%2FiP5TyDbK5y%2BGCi7SjJHL3YqFcREfks7LVNsxR97Whf%2Bh5%2Bmk%2BI1f9Urx11AOsy89r5xGFP94O&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250219T140131Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYRLJGUV2I%2F20250219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3c8575cdce5290ad54346e8ca225975cd17d87355d343d58b9e1cf27638a2ccb&hash=9172e4ce9c1fa8a81a83d340b1ddadd09968d39d98424ce1987fc86e8c5022d8&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2666651022000183&tid=spdf-73da5cc9-e93e-4113-b6a3-a1713a5bcab3&sid=9961a1301e7c08471399f0f8358a0ececd28gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131558575158000f5257&rr=9146ca12c90eea6a&cc=it)] [[code](https://github.com/thunlp/PTR)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

25. **Coherent Long Text Generation by Contrastive Soft Prompt** (GEM 2022) [[paper](https://aclanthology.org/2022.gem-1.42.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

26. **ATTEMPT: Parameter-Efficient Multi-task Tuning via Attentional Mixtures of Soft Prompts** (EMNLP 2022) [[paper](https://aclanthology.org/2022.emnlp-main.446.pdf)] [[code](https://github.com/AkariAsai/ATTEMPT)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

27. **DisCup: Discriminator Cooperative Unlikelihood Prompt-tuning for Controllable Text Generation** (EMNLP 2022) [[paper](https://aclanthology.org/2022.emnlp-main.223.pdf)] [[code](https://github.com/littlehacker26/Discriminator-Cooperative-Unlikelihood-Prompt-Tuning)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

28. **Making Pre-trained Language Models End-to-end Few-shot Learners with Contrastive Prompt Tuning** (WSDM 2023) [[paper](https://doi.org/10.1145/3539597.3570398)] [[code](https://github.com/alibaba/EasyNLP?tab=readme-ov-file)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

29. **A Chinese Few-Shot Text Classification Method Utilizing Improved Prompt Learning and Unlabeled Data** (Applied Sciences (Switzerland)) [[paper](https://doi.org/10.3390/app13053334)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

30. **Knowledge-Guided Prompt Learning for Few-Shot Text Classification** (Electronics (Switzerland)) [[paper](https://doi.org/10.3390/electronics12061486)<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

31. **Personalized Prompt Learning for Explainable Recommendation** (ACM Transactions on Information Systems) [[paper](https://dl.acm.org/doi/pdf/10.1145/3580488)]<br>![](https://img.shields.io/badge/Discrete-84648a) ![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

32. **Adaptive Prompt Learning-Based Few-Shot Sentiment Analysis** (Neural Processing Letters) [[paper](https://link.springer.com/article/10.1007/s11063-023-11259-4)] [[code](https://github.com/simonZPF/AP)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

33. **Decomposed Two-Stage Prompt Learning for Few-Shot Named Entity Recognition** (Information (Switzerland)) [[paper](https://doi.org/10.3390/info14050262)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

34. **GrIPS: Gradient-free, Edit-based Instruction Search for Prompting Large Language Models** (EACL 2023) [[paper](https://aclanthology.org/2023.eacl-main.277.pdf)] [[code](https://github.com/archiki/GrIPS)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

35. **Automating Method Naming with Context-Aware Prompt-Tuning** (IEEE/ACM) [[paper](https://doi.org/10.1109/ICPC58990.2023.00035)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3) 

37. **Multi-Stage Prompt Tuning for Political Perspective Detection in Low-Resource Settings** (Applied Sciences (Switzerland)) [[paper](https://doi.org/10.3390/app13106252)] (code available upon request)<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

39. **FedPrompt: Communication-Efficient and Privacy-Preserving Prompt Tuning in Federated Learning** (ICASSP) [[paper](https://doi.org/10.1109/ICASSP49357.2023.10095356)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

40. **Knowledge-Augmented Frame Semantic Parsing with Hybrid Prompt-Tuning** (ICASSP) [[paper](https://doi.org/10.1109/ICASSP49357.2023.10095476)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

41. **MedKPL: A heterogeneous knowledge enhanced prompt learning framework for transferable diagnosis** (Journal of Biomedical Informatics) [[paper](https://pdf.sciencedirectassets.com/272371/1-s2.0-S1532046423X00069/1-s2.0-S1532046423001387/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLWVhc3QtMSJIMEYCIQDLb1vq9cG%2F%2FtA4tyfcWcm%2BBc6gVtTiMewBD1BdyBOUAQIhAMxfT30gw6WV6FyaflIOgOwS%2FL60tQNCweS%2FtcCyKbncKrsFCKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1Igz0qrcxIWDuqXsMAHUqjwVzOXHHHbAovy%2Fs3VPqE8%2F7VCPrXAp%2Flobct2CX4vhdoiSreXxQCs4ELpm5rgyy2OT9RBqGKhdgDGxZgD91deF1ts0ymlITT1nEAHye6jNAgZkPrMWvHKMlJxPW7La66hUWxhYNG%2Fj3Pco4JrXkdoV7RSL%2FFQF7c32jUO02n7j%2BNwGzeLYfq7rlEvUpk7X9t6rPQkbowwjKQ0fYLA%2BtMLedbyuUaz3fVCMm2EzHWUqWvcLKu9gOOArsM4VPaJwBTdz1RR1JnT65SZkaxs7yN7xD1O90hqQ7BRMW8Sh9LxMM%2FPNJ70f3pAFR2fKcQacYwtTxrVynviB8%2FFus%2BX%2Fln3r2DYie%2Bc4%2FQ6BbHjAlH4UYj98J8Br1v5d8xcd1E%2F7bB1FM2prWFnpNvktONv4%2BT68uLwAmv4C8aZLZva7%2BjtvDLzZ9zOdC0rlbgSEbr9IEuL1Su3LtTGfYHOryuG%2Fygt2d2kTfLvyK81Ul60KcmFbZ3rddGpfKIw0qd0srmIp6cQ1C10ATn1Wmvb79XFHyku79Q1VJID2ZvsaN%2BJ2pohcZJv62qeADClTyPM1HEDkezVy88grN2mcbSruJi4EPRJixQa6m4J23wzWpOccm64W%2FW53nQlKM0OuYkSVYS2ER9dE%2BWP4UCFcbiiJRlUUqmMzdMnj0Jw77r2g%2BPbpaHIuGKPr9azJJuSHoC8QM45OQznGhgX42yHdPzmCh1Fs3WCsU6VV9kHyK8RnJW8pZJU468%2BrmZ5idQHS4%2BwzVyhQBfk7CI5TX5tvZCZSyOdZRUlIAAtMmu4Sz0lE2o2GcfT2WCJY3jATYfjmI%2BMRgf%2BnJsVSwMi%2FdmehfE9jod%2Ffbzo%2BcxrLpp1%2F7aGiyE7kn%2BIPXMI64170GOrAB3%2Bot67ncqrue1AIADAahiHAsDjDi2YHZStO0v6a4vvoq6OHpt6DxQmb%2BcA6OxTdi8JWjqXaaI4HVJr%2B6QGO1CNzqnd7arxCl8SP4xOrPKJw1JmP2o8Dcb5HG1r9cFWZgRu0xjGlwV41SIKZbEO5SV6NhrfYSly%2FTmHBidCGtzWyZWXrZQiMNqOmKJRobSKwmDqzBmyi9HhWcB0FosSMWlXz7qLXJUAvvPJmkcPMg2qM%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250219T140843Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY46MHC3OL%2F20250219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=42a47d33eed86215264465f8809d0410a639b3713a6e8df0815edfb112995611&hash=435919ad7654b0aa818dd4172c7d0f5c9c8a0d2b37f7b9113a1e6f8fe8eb91ed&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1532046423001387&tid=spdf-19548386-65a1-4a4e-8e23-7c2b640de0a8&sid=9961a1301e7c08471399f0f8358a0ececd28gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131558575158075a0255&rr=9146d4a0c929a259&cc=it)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

43. **Zero-Shot Cross-Lingual Event Argument Extraction with Language-Oriented Prefix-Tuning** (AAAI) [[paper](https://doi.org/10.1609/aaai.v37i11.26482)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

46. **KLAPrompt: Infusing Semantic Knowledge into Pre-trained Language Models by Long-answer Prompt Learning** (SEKE) [[paper](https://doi.org/10.18293/SEKE2023-200)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

47. **ETHICIST: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation** (ACL) [[paper](https://aclanthology.org/2023.acl-long.709.pdf)] [[code](https://github.com/thu-coai/Targeted-Data-Extraction)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

48. **Emotion classification on code-mixed text messages via soft prompt tuning** (WASSA) [[paper](https://aclanthology.org/2023.wassa-1.57.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

49. **A Unified Generative Retriever for Knowledge-Intensive Language Tasks via Prompt Learning** (SIGIR 2023) [[paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3591631)] [[code](https://github.com/ict-bigdatalab/UGR)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

50. **Adversarial Meta Prompt Tuning for Open Compound Domain Adaptive Intent Detection** (SIGIR 2023) [[paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3591945)] [[code](https://github.com/calubkk/AMPT)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

51. **Prompt Learning for News Recommendation** (SIGIR 2023) [[paper](https://doi.org/10.1145/3539618.3591752)] [[code](https://github.com/resistzzz/Prompt4NR)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

53. **Soft Prompt Decoding for Multilingual Dense Retrieval** (SIGIR 2023) [[paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3591769)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

54. **VPN: Variation on Prompt Tuning for Named-Entity Recognition** (Applied Sciences (Switzerland)) [[paper](https://doi.org/10.3390/app13148359)] [[code](https://github.com/huniu20/vpn)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

55. **Few-shot Sentiment Analysis Based on Adaptive Prompt Learning and Contrastive Learning** (Information Technology and Control) [[paper](https://doi.org/10.5755/j01.itc.52.4.34021)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) ![](https://img.shields.io/badge/Non%0APEFT-e8b85c)   

56. **Instance-Aware Prompt Learning for Language Understanding and Generation** (ACM Transactions on Asian and Low-Resource Language Information Processing) [[paper](https://doi.org/10.1145/3604613)] [[code](https://github.com/jinfeihu-stan/IPL)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c) 

58. **Prompt Learning with Structured Semantic Knowledge Makes Pre-Trained Language Models Better** (Electronics (Switzerland)) [[paper](https://doi.org/10.3390/electronics12153281)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

59. **GPT Understands, Too** (AI Open) [[paper](https://pdf.sciencedirectassets.com/777606/1-s2.0-S2666651023X00023/1-s2.0-S2666651023000141/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLWVhc3QtMSJIMEYCIQCkHVAYj3eaD1V8vk3cwnwby9zg0ZgdM3pCaWoj8aEhuAIhAINBM6OilIKtjq9aBxOoEvIcVmDDb3a7StX4pDScdCEDKrsFCKf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1IgzgL28XqSOUfg5kirUqjwVuO37HYeNBC5Ig9VLUh%2FwIIigyjFeISyb7nPEAoqg4PEtkAZgH827lyV8ZpFC317cwUwYPAho2z0DSLUh8UuiADW4uyZ03ha5rJeBZ1FCpd9TT9AmJZsaMYe4WMWNE%2BkopA9ut3h0KOzCWVunoQyPvGgoqwsbbveiokuQtv78Iv5wM%2FFwD%2Fri9rfrrCP2JuMrQN0ogxYE3dE49VVDgKSYKKUNZivPdCqfpvgrZ3%2FxBqDyIFL8gvgda5XVklpCprK97EzM%2B251tGtSRbz%2FgQqYT6gXRGLkCsC8LedkYvO8pA9l36EnPV%2BlkxMCzvDjj98AWUc7cOUetU9dvQGIzDXCV%2B0azicPNabOYIBK8EVF8QHrHmSKNENRwrXJgJI4FDtrvvizOLGo%2FgViZC%2FMuTwkJkfdny7H5nha1y5%2B3WhHccYxQlvTP6AeCdEhEUYen2zGEG9ndJno0kE9WjF5SOyezT9gSa4NY9fv3ic%2B4smsqdd3SpZKXcf%2BKyq1gB1%2BkheegZ1WhmKppQ6SvLb%2BsVAVF%2FK6IEmOe8bc%2FKB2zqtZlFno6IYDcSWcaWYoOGEAwUskssihJWFWAmuMwaMU19Wyk5MZ4saImwRxmbk1wz06gOhE6D48XIy9IrbLjIwNggqQCr8N1%2BGXmoNzgZYr8qB4%2Fz76Jg2F3svwdLAUyVyhZZVXYlev0eVJzm7Eql2dQdZm7FfLf1q%2F43fHK8xvI8hJRBPO4HogVnvVqR3hn%2BiXYDfmTZS2997aaa8jLQWzqza0BeVCHPBOzupo5rx8vpBELmiIypw9K0nRq5iYVX%2BkijYkkq0vm7vs4ccy7qy%2FXx0ZClZygf3M%2BrxJjEYb%2B2RLUEECpIbsys90Vu%2FxBKInUMNy3170GOrABrYsAOC%2BFYbGlzW%2Fq0SpXz5c6dxim8aTkE1LLRqOxJqUOSwRRekjWfwZFnnk2WESv1Ra7llRmcjysF7QijHzZdXZ%2BZKe2sOLLNYbAfuw7%2BsLSIxa07nJPK3sUVYCZ%2FZK%2FxvNqLEvw5pv9DX3QCZXja01nt8oWHPLyWwCe5z%2FqGP%2BvpK2%2B%2FEcTexTasDgxRHjpZ6kNw01e3bNpBj%2BilKLvAWlPSpKbinrChcE9Y0idGS8%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250219T141315Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYVZLG6PU4%2F20250219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a2bdb4cc654329079c98bc9c8910c9e4d4dbe2f9449df86ead5af69353d344af&hash=e48e139525f89a27e2f52c837915c758f6813066d33f63c12fecfe94e7396c4e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2666651023000141&tid=spdf-011689dc-ef2e-4bae-a378-a3d1dec49683&sid=9961a1301e7c08471399f0f8358a0ececd28gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131558575158070c5756&rr=9146db43cc63a259&cc=it)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

60. **APICom: Automatic API Completion via Prompt Learning and Adversarial Training-based Data Augmentation** (ACM International Conference Proceeding Series) [[paper](https://doi.org/10.1145/3609437.3609450)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

61. **Research on the Application of Prompt Learning Pretrained Language Model in Machine Translation Task with Reinforcement Learning** (Electronics (Switzerland)) [[paper](https://doi.org/10.3390/electronics12163391)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098) 

62. **Simple Knowledge Graph Completion Model Based on Differential Negative Sampling and Prompt Learning** (Information (Switzerland)) [[paper](https://doi.org/10.3390/info14080450)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

64. **One Model for All Domains: Collaborative Domain-Prefix Tuning for Cross-Domain NER** (IJCAI) [[paper](https://www.ijcai.org/proceedings/2023/0559.pdf)] [[code](https://github.com/zjunlp/DeepKE/tree/main/example/ner/cross)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

65. **Generating Chinese Event Extraction Method Based on ChatGPT and Prompt Learning** (Applied Sciences (Switzerland)) [[paper](https://doi.org/10.3390/app13179500)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

67. **ContrastNER: Contrastive-based Prompt Tuning for Few-shot NER** (IEEE/COMPSAC) [[paper](https://doi.org/10.1109/COMPSAC57700.2023.00038)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

68. **Prompt-Learning for Cross-Lingual Relation Extraction** (IJCNN) [[paper](https://doi.org/10.1109/IJCNN54540.2023.10192002)]<br>![](https://img.shields.io/badge/Soft-e16d50) ![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

69. **Parameter-Efficient Low-Resource Dialogue State Tracking by Prompt Tuning** (INTERSPEECH) [[paper](https://www.isca-archive.org/interspeech_2023/ma23g_interspeech.pdf)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

72. **MsPrompt: Multi-step prompt learning for debiasing few-shot event detection** (Information Processing and Management) [[paper](https://doi.org/10.1016/j.ipm.2023.103509)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

74. **Soft prompt enhanced joint learning for cross-domain aspect-based sentiment analysis** (Intelligent Systems with Applications) [[paper](https://pdf.sciencedirectassets.com/779210/1-s2.0-S2667305323X00040/1-s2.0-S2667305323001175/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLWVhc3QtMSJHMEUCIClKx4nxvBoBVz6awfUU1bWbyc1NSm%2B5fOB%2FKsLpYazuAiEAvIgHlpIXbKisUR8ZnjHFceEie2Vrm182Pvznr0LPyr0quwUIpv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDDeQCdKEpTLs5CJOhyqPBahXepUKaSHtMWf%2F9LIem%2Bek%2FLzwR9ZWpZcQwOtxf4cDF1WDP8Uf5J947v6VbbD5NdVy%2B6IXzDePRbRk3CuyFHz95kLTBULDImg%2Bf1evErnNIbXVUBs%2BpACSDnqvtyJaqGZHmAkID%2FZg36ClIPu5E31jbX%2B2m6EI9kHrSBIU9lwkearLlU29GV0TvPtwuebB01%2FF6dq3YOfeJjsieEb6OqG2bVJ0ouE4pLH%2Bkzz8SBMXG%2BEsCeGrKpQFza9qRTBeEC0LEQHzuibThxCqnsnNqzJEoeMXKo8cZfO0GzKfrq%2BCBQBizgzOw7wIiweu11v%2B%2Brd93b%2FcGouMSYtlmzuGbOaUicDuMM%2BorWp9txbrHxR2HeUME7wt5lAjns%2B%2BMKamErFCP04yD5mnG1mEp1x6zyV2vjxUb24kahPMcjP7PZlAjXgwc67uimLk2EKB1jh%2FxU0ai3PVQneo9nQ%2Bv9SYunJUgZxRXIIYgCEW3gl6I4DhJHLC48er4xNQg2fsemBAiKFk7No3kX3ELKCXITuI9s3EXbNQdMftW82itzNEp4BD0t5DN2dC%2F0c3W7ZcgEI%2BMvfLl8lIvodSKQdUTmOu8Lf8c2bQGkFWjW0uzWGixaFKM7M93iNNsDXDBTOnyNZfN7X7KSDCzWz4vJZPC%2FBvkdjR9Q%2BrwzHKGQNd%2BPJXZTd2GrmwAhNYq%2BW7ARVq%2B9eOuFbvGiUVe6ziy8oQrMunf0nbSE3kM3FgXF6fC6yH0AXH%2BijzuYdTLKF3e4%2FZZYlB934g2KxYtvWznUkCIyWwq429aNPPMLr6LzRKjxX0FDlZS1wcyEmh73fzIL5G2Umqt1tS3L9e2QXg4VBfIqUaqUCbaC78zKCytvElTvTOMRYw37DXvQY6sQEHKpGPw2k2p9AVTfUrbBWYzER%2BCQFFdFkAMO1pH8i7xYKpqJJX%2FTiHlmS8Kxfel657%2BjeG8m4rbz7pI%2Bby%2F%2FOOA3dEUAD0QUpY%2Fze93jDQtiP%2FTE1NEygZu41AJGP9BFWBGMPxcH0ajSBUje9neq7%2BPBjHuqJfpKjH43EnLreBe0fvIHjvwY1ljRtmP%2BYMsOb8apLypSosqGYF5wlFLb0ePqoarCeXFmVHCvD%2FmvnSZu8%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250219T141740Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYT42QHZ7I%2F20250219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=ce14033d7740c7ccea2360cc9319300c94d0044aadd20d2145308137aa8de049&hash=b66bc802aa73a3d22e41621395b5b21f889c274c2c8f917c85bdc186478e4d1b&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2667305323001175&tid=spdf-665d6128-e6e1-452e-8f61-a47a4c807a1d&sid=9961a1301e7c08471399f0f8358a0ececd28gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131558575158065f0104&rr=9146e1ba08dca259&cc=it)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

75. **Knowledge Prompt-tuning for Sequential Recommendation** (MM 2023) [[paper](https://doi.org/10.1145/3581783.3612252)] [[code](https://github.com/zhaijianyang/KP4SR)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)  

78. **Domain-Enhanced Prompt Learning for Chinese Implicit Hate Speech Detection** (IEEE) [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10385216)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

79. **SPeC: A Soft Prompt-Based Calibration on Performance Variability of Large Language Model in Clinical Notes Summarization** (Journal of Biomedical Informatics) [[paper](https://doi.org/10.1016/j.jbi.2024.104606)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

81. **Prompt to Transfer: Sim-to-Real Transfer for Traffic Signal Control with Prompt Learning** (AAAI) [[paper](https://www.scopus.com/record/display.uri?eid=2-s2.0-85189348156&origin=resultslist&sort=tp-f&src=s&sid=c1a88076e2d4998dd920b032a31fb49f&sot=a&sdt=a&cluster=scofreetoread%2C%22all%22%2Ct%2C%22publisherfullgold%22%2Ct%2Bscopubstage%2C%22final%22%2Ct%2Bscosubjabbr%2C%22COMP%22%2Ct%2Bscosubtype%2C%22cp%22%2Ct%2C%22ar%22%2Ct%2Bscolang%2C%22English%22%2Ct%2Bscoexactkeywords%2C%22Image+Features%22%2Cf%2C%22Image+Recognition+And+Understanding%22%2Cf%2C%22Images+Classification%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modalities%22%2Cf%2C%22Vision+%2B+Language+And%2For+Other+Modality%22%2Cf%2C%22Vision-language+Models%22%2Cf%2C%22Learning+For+Vision%22%2Cf%2C%22Vision-language+Model%22%2Cf%2C%22Image+Classification%22%2Cf%2C%22Image+Recognition%22%2Cf%2C%22Visual+Prompts%22%2Cf%2C%22Image+Enhancement%22%2Cf%2C%22Computer+Vision%22%2Cf%2C%22Visual+Languages%22%2Cf%2C%22Multi-modal%22%2Cf%2C%22Multi-modal+Learning%22%2Cf&s=%28TITLE%28%28+%22prompt+tuning%22+%29+OR+%28+%22prefix+tuning%22+%29+OR+%28+%22prompt+learning%22+%29+OR+%28+%22soft+prompt*%22+%29+OR+%28+%22prompt*+optimization%22+%29%29+AND+PUBYEAR+%26gt%3B+2020+AND+PUBYEAR+%26lt%3B+2025+%29&sessionSearchId=c1a88076e2d4998dd920b032a31fb49f&relpos=62)] [[code](https://github.com/DaRL-LibSignal/PromptGAT)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

82. **Prompt Optimization in Large Language Models** (Mathematics) [[paper](https://doi.org/10.3390/math12060929)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)  

83. **On Unsupervised Domain Adaptation: Pseudo Label Guided Mixup for Adversarial Prompt Tuning** (Proceedings of the AAAI Conference on Artificial Intelligence) [[paper](https://doi.org/10.1609/aaai.v38i16.29800)] [[code](https://github.com/fskong/PL-Mix)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

86. **ProRLearn: boosting prompt tuning-based vulnerability detection by reinforcement learning** (ASE) [[paper](https://doi.org/10.1007/s10515-024-00438-9)] [[code](https://github.com/ProRLearn/ProRLearn001)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

87. **Affective Prompt-Tuning-Based Language Model for Semantic-Based Emotional Text Generation** (International Journal on Semantic Web and Information Systems) [[paper](https://doi.org/10.4018/ijswis.339187)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49) 

88. **Enhancing Zero-Shot Stance Detection with Contrastive and Prompt Learning** (Entropy) [[paper](https://doi.org/10.3390/e26040325)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

90. **Knowledge-Enhanced Prompt Learning for Few-Shot Text Classification** (Big Data and Cognitive Computing) [[paper](https://doi.org/10.3390/bdcc8040043)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Context%0Definition-94b5a3)

91. **ConsPrompt: Exploiting Contrastive Samples for Fewshot Prompt Learning** (ICASSP) [[paper](https://doi.org/10.1109/ICASSP48485.2024.10448403)] [[code](https://github.com/Nagin-Kim/cosprompt)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)  

93. **Adapting LLMs for Efficient Context Processing through Soft Prompt Compression** (ACM) [[paper](https://arxiv.org/pdf/2404.04997)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

94. **Can we Soft Prompt LLMs for Graph Learning Tasks?** (ACM) [[paper](https://doi.org/10.1145/3589335.3651476)] [[code](https://github.com/franciscoliu/graphprompter)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

96. **KBPT: knowledge-based prompt tuning for zero-shot relation triplet extraction** (PeerJ Computer Science) [[paper](https://doi.org/10.7717/peerj-cs.2014/fig-1)] [[code](https://github.com/Phevos75/KBPT)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

98. **A Rumors Detection Method Using T5-Based Prompt Learning** (International Journal of Data Warehousing and Mining) [[paper](https://www.igi-global.com/gateway/article/344415)]<br>![](https://img.shields.io/badge/Discrete-84648a)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Template%0ADefinition-799098)

99. **Meta Soft Prompting and Learning** (APSIPA) [[paper](http://dx.doi.org/10.1561/116.20240010)] [[code](https://github.com/NYCU-MLLab/Domain-Agnostic-Soft-Prompt)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)  

102. **Prompt Tuning on Graph-Augmented Low-Resource Text Classification** (IEEE) [[paper](https://doi.org/10.1109/TKDE.2024.3440068)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)   

103. **Prompt learning for metonymy resolution: Enhancing performance with internal prior knowledge of pre-trained language models** (Knowledge-Based Systems) [[paper](https://pdf.sciencedirectassets.com/271505/1-s2.0-S0950705123X00185/1-s2.0-S0950705123006780/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEH4aCXVzLWVhc3QtMSJGMEQCIAJfcMbA5dtpeCMhZJN6VvWEamvHCPDE57uyzNAt9IhEAiAGTuKRkby8UKsybwT%2Brp6WQlq6ngKmnALALxOit3oD0Sq7BQin%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMbDkpg9IniNRE1%2BejKo8F2y7SwdCUswl1spRJmGFeX%2FDcCY8vDeey3YmcQhZ%2FTJhvuPdvKOwk%2F67W3uZJ28Dzvlu1i2iwxKM2IofAy4FVNjG8hRVnthXXOCa4pVm3SugC1nujNV9Anj08bTePOKT%2BVvb5%2F5O%2FAvgtAwo74syv634zmFpCGJ8sspL%2FB5JyZQpYVjmunt%2FsxMAO6fLsLj2im6VsQqIBVDFLt9zJ7bFscPhxt8BpdwQH%2FTNgAR59ybp%2B%2BOe4K0KTs5JLfvSmFzImXOx6njIYKFWdR34g0ZBlhiNGBMq57mDN7LUwrN4%2F8fO3EptPi3tvLe%2BcGXfmm3MQv19YuIyelq0%2Bvzx6XO3GqqVnYzyUu9TM3C5w2cqdiJ5f6a%2FWOEmC5YJQX7raviKnZSpYhMCc9xAGUq%2FJKCxrA6NM2MKARFHzcGo9gQV1t3Rc8p2CJpvlGNKBZdp9jpTo%2Fxtg85mR5aDAoPurvEGDEnCDGwqbtEw4bviqtBVhIv3aQ7BsytMfI5ASez6zSkVjo2ZMUE01aC0KWnzwkthdzWTbIWNq8cv%2FuQJNpL7QRI3kpeOUpwGBZsAaPjrKxebubCbWeHgOjSR4LImo4HGsSRmhaLO2KHG6Qrwya0%2FaQyKrxQcqiPH4K1XLkXafsiyPy%2FFesrtEwnC893%2FcB0jkdyCrOw%2BMBes%2FflQ3cUOVT%2F3STJ6yFz43cHqzBfJn3WAZ%2BMyPknnSh8bXezeJIdRARTUwZXHFcaxymESHKokMesp5%2B5ZmhJK3NhqKoOD9ZOTTrYmpMYwZ2Y2e3SPaaiZxHn%2BLrIbfxRjUnRAQPADmhpio4zOOBvLKltZl%2BfJ4Q2itLeuSOBPO2QojRVO69mbD%2BwcTOWLk%2F3eHSlNB19YjaDDLxde9BjqyASVIWhaReM1M%2FNmxZ5gV%2F0eKTj3J3OfWFAJMBlW6ZvJ62NPkKWfdqtSUzKcTeRInTSs%2BWpqFDALOIYPFTX1rhpIroGyp33yrUDdfkLEkfUsC0UeURPNAu4Jh1am7tR7tIm5DpFnsQ9npmvY%2B2JTeGmE2UI0xBeBOhTbHmhc5WNIzOfilajJgMf6oMUccev9jeTxui1Z0fA8tSzwvx1nD2jkrHRBhLmGX5rUtnYzucdTxw4Y%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250219T142634Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYX4YUHOQY%2F20250219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=10fd3dd43f2ce1238cc3a3be001c8ebc6ffb7fd0d82b888a9fba3e197f131697&hash=d60ba3c21d3dbaa79c1a7f69f743141ac83765fe3638817b5721173ee5f822ea&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0950705123006780&tid=spdf-abb10865-8c01-4891-9989-cca66cef8433&sid=9961a1301e7c08471399f0f8358a0ececd28gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=131558575158060b0050&rr=9146eec5ea7eea52&cc=it)] [[code](https://github.com/albert-jin/PromptTuning2MetonymyResolution)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

105. **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with LLMs** (CCS) [[paper](https://dl.acm.org/doi/pdf/10.1145/3658644.3690298)] [[code](https://github.com/mahmoudkanazzal/PromSec)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

106. **RPEPL: Tibetan Sentiment Analysis Based on Relative Position Encoding and Prompt Learning** (ACM) [[paper](https://doi.org/10.1145/3698575)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

108. **Prompt Tuning for Item Cold-start Recommendation** (ACM) [[paper](https://doi.org/10.1145/3640457.3688126)] [[code](https://github.com/PROMOREC/PROMO)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/PEFT-d98d49)

109. **G-SAP: Graph-based Structure-Aware Prompt Learning over Heterogeneous Knowledge for Commonsense Question Answering** (ICMR) [[paper](https://doi.org/10.1145/3652583.3658040)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/PEFT-d98d49)

110. **Graph‑Enhanced Prompt Learning for Personalized Review Generation** (Data Science and Engineering) [[paper](https://doi.org/10.1007/s41019-024-00252-z)]<br>![](https://img.shields.io/badge/Soft-e16d50)<br>![](https://img.shields.io/badge/Prefix-d98d49)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

111. **Multi-Relation Extraction for Cybersecurity Based on Ontology Rule-Enhanced Prompt Learning** (Electronics) [[paper](https://doi.org/10.3390/electronics13122379)]<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

113. **Knowledge-injected Prompt Learning for Chinese Biomedical Entity Normalization** (ACM) [[paper](https://doi.org/10.1145/3689629)]<br>![](https://img.shields.io/badge/Hybrid-c381a7)<br>![](https://img.shields.io/badge/Cloze-7c7f55)<br>![](https://img.shields.io/badge/Non%0APEFT-e8b85c)

<a id="datasets"></a>
## 💾 Datasets

This repository maintains two datasets tracking the aforementioned research papers in prompt learning:

- **Automated Prompt Learning Papers** (```automated_prompt_learning_papers.csv```)
  - Includes only papers that employ automated prompt learning techniques (i.e., the one listed above)
- **All Prompt Learning Papers** (```all_prompt_learning_papers.csv```)
  - Contains all retrieved papers from the Scopus search, including non-automated approaches and those excluded from the study. 
    Papers were not included in our analysis if:
    <br>❌ Did not focused on textual downstream tasks
    <br>❌ Utilized multi-modal approaches
    <br>❌ They were theoretical analyses without novel methods
   
### Datasets Guide

Each dataset contains the following columns:

| Column | Explanation |
|--------|-------------|
| Publication Date | Paper publication date |
| Title | Full title of the paper |
| Acronym | Paper's method acronym |
| Venue | Conference or journal where the paper was published |
| Pre-training Objective | The pre-training objective employed during training and aimed at elliciting via prompts (i.e. Cloze, Prefix) |
| Automation Object/Training Strategy | The category of the paper based on our taxonomy |
| Prompt Length<br>(soft prompts) | # of soft prompt tokens |
| Prompt Initialization Strategy<br>(soft prompts) | Soft prompt initialization strategy |
| PLMs | Pre-trained language models used |
| Datasets | Datasets utilized in the study |
| Tasks | Target NLP tasks |
| Code | Link to the implementation, if available |
| Additional Notes<br>(only in ```all_prompt_learning_papers.csv```) | Indicates whether the paper was categorized as a study or discarded based on the criteria mentioned above |


<a id="query"></a>
## 🔍 Query

To ensure reproducibility, we provide the exact query used to retrieve the papers analyzed in this survey. The search was conducted on Scopus, with the full list of filters provided below. The final execution of the query took place on November 29, 2024. Since Scopus' database contents are continuously updated, re-executing the same query will produce additional results beyond those considered in this study.

```plaintext
(TITLE(( "prompt tuning" ) OR ( "prefix tuning" ) OR ( "prompt learning" ) OR ( "soft prompt*" ) OR ( "prompt* optimization" )) AND PUBYEAR > 2020 AND PUBYEAR < 2025 AND ( LIMIT-TO ( SUBJAREA,"COMP" ) )  AND ( LIMIT-TO ( PUBSTAGE,"final" ) )  AND ( LIMIT-TO ( DOCTYPE,"cp" ) OR LIMIT-TO ( DOCTYPE,"ar" ) )  AND ( LIMIT-TO ( LANGUAGE,"English" ) )  AND ( LIMIT-TO ( OA,"all" ) OR LIMIT-TO ( OA,"publisherfullgold" ) )  AND ( EXCLUDE ( EXACTKEYWORD,"Image Features" ) OR EXCLUDE ( EXACTKEYWORD,"Image Recognition And Understanding" ) OR EXCLUDE ( EXACTKEYWORD,"Images Classification" ) OR EXCLUDE ( EXACTKEYWORD,"Vision + Language And/or Other Modalities" ) OR EXCLUDE ( EXACTKEYWORD,"Vision + Language And/or Other Modality" ) OR EXCLUDE ( EXACTKEYWORD,"Vision-language Models" ) OR EXCLUDE ( EXACTKEYWORD,"Learning For Vision" ) OR EXCLUDE ( EXACTKEYWORD,"Vision-language Model" ) OR EXCLUDE ( EXACTKEYWORD,"Image Classification" ) OR EXCLUDE ( EXACTKEYWORD,"Image Recognition" ) OR EXCLUDE ( EXACTKEYWORD,"Visual Prompts" ) OR EXCLUDE ( EXACTKEYWORD,"Image Enhancement" ) OR EXCLUDE ( EXACTKEYWORD,"Computer Vision" ) OR EXCLUDE ( EXACTKEYWORD,"Visual Languages" ) OR EXCLUDE ( EXACTKEYWORD,"Multi-modal" ) OR EXCLUDE ( EXACTKEYWORD,"Multi-modal Learning" ) ) )
```

<!--
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
-->

<a id="contribution"></a>
## 🎉 Contribution

Despite our best efforts, we acknowledge that some works may not be included in this repository. To help improve this list, we welcome contributions! Feel free to open a PR or issue in our repository to suggest missing papers. 😊

We thank all contributors to this repo!
<!-- our names and email here -->

<a id="acknowledgement"></a>
## 🤝 Acknowledgement

We referred to the template of [Awesome Data Contamination](https://github.com/lyy1994/awesome-data-contamination). Thank for the helpful contribution!

<p align="right"><a href="#top">🔝Back to top</a></p>

