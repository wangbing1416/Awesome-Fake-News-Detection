

## Fake News Detection

An awesome paper list of **fake news detection (FND)** and **rumor detection** with ![](https://img.shields.io/badge/162-red) papers. FND methods are divided into context-based and social media-based methods.  
Moreover, this is a personal list, if you have some additional literature, which need to be supplemented, you can feel free to drop an email (wangbing1416@gmail.com) to me!

- [Fake News Detection](#fake-news-detection)
  - [Context-based FND](#context-based-fnd)
    - [Text-only Methods](#text-only-methods)
      - [Supervised Learning](#supervised-learning)
      - [Domain Adaptation](#domain-adaptation)
      - [Knowledge base-based](#knowledge-base-based)
      - [Machine-generated News Detection](#machine-generated-news-detection)
    - [Evidence-aware Methods](#evidence-aware-methods)
    - [Multi-modal Methods](#large-language-model-based-methods)
    - [Large Language Model-based Methods](#multi-modal-methods)
  - [Social Media-based FND](#social-media-based-fnd)
- [Fact-check & Fact Verification](#fact-check--fact-verification)
  - [Supervised Methods](#supervised-methods)
  - [LLM Based Methods](#llm-based-methods)
  - [Multi-hop Fact Verification](#multi-hop-fact-verification)
  - [Previously Fact-check](#previously-fact-check)
  - [New Datasets](#new-datasets)
- [Rumor Detection](#rumor-detection)
  - [Supervised Methods](#supervised-methods-1)
    - [with Unreliable Propagations](#with-unreliable-propagations)
    - [with Temporal Features](#with-temporal-features)
    - [with User Profile](#with-user-profile)
    - [with Data Augmentation](#with-data-augmentation)
  - [Multi-modal Methods](#multi-modal-methods-1)
  - [Joint Stance & Rumor Detection](#joint-stance--rumor-detection)
- [Summarizations of FND](#summarizations-of-fnd)
    - [Social Media-based Fake News Detection and Rumor Detection](#social-media-based-fake-news-detection-and-rumor-detection)
    - [Context-based Fake News Detection](#context-based-fake-news-detection)
- [Famous Chinese Researchers in FND](#famous-chinese-researchers-in-fnd)


## Context-based FND

### Text-only Methods

#### Supervised Learning
**[CIKM 2024]** <i>Why Misinformation is Created? Detecting them by Integrating Intent Features</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3627673.3679799)]  
**[CIKM 2024]** <i>Evolving to the Future: Unseen Event Adaptive Fake News Detection on Social Media</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3627673.3679919)]  
**[WWW 2024]** <i>MSynFD: Multi-hop Syntax Aware Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3589334.3645468)]  
**[ACL 2023]** <i>Learn over Past, Evolve for Future: Forecasting Temporal Trends for Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2306.14728)]  
**[ACL 2023]** <i>Faking Fake News for Real Fake News Detection: Propaganda-loaded Training Data Generation</i> [[Paper](https://arxiv.org/pdf/2203.05386)]  
**[ACL 2022]** <i>Zoom Out and Observe: News Environment Perception for Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2203.10885.pdf)]  
**[COLING 2022]** <i>A Coarse-to-fine Cascaded Evidence-Distillation Neural Network for Explainable Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2209.14642.pdf)]  
**[COLING 2022]** <i>Demystifying Neural Fake News via Linguistic Feature-Based Interpretation</i> [[Paper](https://aclanthology.org/2022.coling-1.573.pdf)]  
**[SIGIR 2022]** <i>Generalizing to the Future: Mitigating Entity Bias in Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3477495.3531816)]  
**[ECML 2021]** <i>Early Detection of Fake News with Multi-source Weak Social Supervision</i> [[Paper](http://www.cs.iit.edu/~kshu/files/ecml_pkdd_mwss.pdf)]  
**[WWW 2021]** <i>Mining Dual Emotion for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3450004)]  
**[ICCART 2019]** <i>Fake News Detection via NLP is Vulnerable to Adversarial Attacks</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/1901/1901.09657.pdf)]  

#### Domain Adaptation

**[COLING 2022]** <i>Improving Fake News Detection of Influential Domain via Domain-and Instance-Level Transfer</i> [[Paper](https://arxiv.org/pdf/2209.08902.pdf)]  
**[WWW 2022]** <i>Domain Adaptive Fake News Detection via Reinforcement Learning</i> [[Paper](https://arxiv.org/pdf/2202.08159.pdf)]  
**[TKDE 2022]** <i>Memory-Guided Multi-View Multi-Domain Fake News Detection</i> [[Paper](https://ieeexplore.ieee.org/document/9802916)]  
**[IPM 2022]** <i>Characterizing Multi-Domain False News and Underlying User Effects on Chinese Weibo</i> [[Paper](https://www.sciencedirect.com/science/article/pii/S0306457322000784?via%3Dihub)]  
**[ArXiv 2022]** <i>FuDFEND: Fuzzy-domain for Multi-domain Fake News Detection</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/2205/2205.03778.pdf)]  
**[CIKM 2021]** <i>MDFEND: Multi-domain Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2201.00987.pdf)]  
**[ICONIP 2021]** <i>DAFD: Domain Adaptation Framework for Fake News Detection</i> [[Paper](http://www.cs.iit.edu/~kshu/files/DAFD_ICONIP.pdf)]  

#### Knowledge base-based

**[IPM 2022]** <i>Fake News Detection via Knowledgeable Prompt Learning</i> [[Paper](https://www.sciencedirect.com/science/article/pii/S030645732200139X)]  
**[AAAI 2021]** <i>KAN: Knowledge-aware Attention Network for Fake News Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16080)]  
**[ACL 2021]** <i>Compare to The Knowledge: Graph Neural Fake News Detection with External Knowledge</i> [[Paper](https://aclanthology.org/2021.acl-long.62.pdf)]  

#### Machine-generated News Detection
**[ICLR 2024]** <i>Can LLM-Generated Misinformation Be Detected?</i> [[Paper](https://openreview.net/pdf?id=ccxD4mtkTU)]  
**[ACL 2022]** <i>Automatic Detection of Entity-Manipulated Text Using Factual Knowledge</i> [[Paper](https://aclanthology.org/2022.acl-short.10.pdf)]  
**[COLING 2022]** <i>Threat Scenarios and Best Practices for Neural Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.106.pdf)]  
**[CL 2020]** <i>The Limitations of Stylometry for Detecting Machine-Generated Fake News</i> [[Paper](https://aclanthology.org/2020.cl-2.8.pdf)]  

### Evidence-aware Methods

**[KDD 2023]** <i>MUSER: A MUlti-Step Evidence Retrieval Enhancement Framework for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3580305.3599873)]  
**[SIGIR 2022]** <i>Bias Mitigation for Evidence-aware Fake News Detection by Causal Intervention</i> [[Paper](https://web.archive.org/web/20220712063219id_/https://dl.acm.org/doi/pdf/10.1145/3477495.3531850)]  
**[WWW 2022]** <i>Evidence-aware Fake News Detection with Graph Neural Networks</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3485447.3512122)]  
**[ACL 2021]** <i>Automatic Fake News Detection: Are Models Learning to Reason?</i> [[Paper](https://arxiv.org/pdf/2105.07698.pdf)]  
**[CIKM 2021]** <i>Integrating Pattern-and Fact-based Fake News Detection via Model Preference Learning</i> [[Paper](https://arxiv.org/pdf/2109.11333.pdf)]  

### Multi-modal Methods
**[MM 2024]** <i>FKA-Owl: Advancing Multimodal Fake News Detection through Knowledge-Augmented LVLMs</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3681089)]  
**[MM 2024]** <i>Mitigating Social Hazards: Early Detection of Fake News via Diffusion-Guided Propagation Path Generation</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3681087)]  
**[MM 2024]** <i>Harmfully Manipulated Images Matter in Multimodal Misinformation Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3681322)]  
**[MM 2024]** <i>MMDFND: Multi-modal Multi-Domain Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3681317)]  
**[CIKM 2024]** <i>Multimodal Misinformation Detection using Large Vision-Language Models</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3627673.3679826)]  
**[SIGIR 2024]** <i>Fake News Detection via Multi-scale Semantic Alignment and Cross-modal Attention</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3626772.3657905)]  
**[WWW 2024]** <i>MCFEND: A Multi-source Benchmark Dataset for Chinese Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3589334.3645385)]  
**[ACL 2024]** <i>Event-Radar: Event-driven Multi-View Learning for Multimodal Fake News Detection</i> [[Paper](https://aclanthology.org/2024.acl-long.316.pdf)]  
**[AAAI 2024]** <i>Unveiling Implicit Deceptive Patterns in Multi-Modal Fake News via Neuro-Symbolic Reasoning</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28677/29315)]  
**[CVPR 2024]** <i>SNIFFER: Multimodal Large Language Model for Explainable Out-of-Context Misinformation Detection</i> [[Paper](https://arxiv.org/pdf/2403.03170.pdf)]  
**[Arxiv 2024]** <i>FakeNewsGPT4: Advancing Multimodal Fake News Detection through Knowledge-Augmented LVLMs</i> [[Paper](https://arxiv.org/pdf/2403.01988.pdf)]  
**[Arxiv 2024]** <i>LEMMA: Towards LVLM-Enhanced Multimodal Misinformation Detection with External Knowledge Augmentation</i> [[Paper](https://arxiv.org/pdf/2402.11943.pdf)]  
**[ACL 2023]** <i>Two Heads Are Better Than One: Improving Fake News Video Detection by Correlating with Neighbors</i> [[Paper](https://arxiv.org/pdf/2306.05241)]  
**[AAAI 2023]** <i>FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/download/26689/26461)]  
**[MM 2023]** <i>Cross-modal Contrastive Learning for Multimodal Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3613850)]  
**[MM 2023]** <i>Combating Online Misinformation Videos: Characterization, Detection, and Future Directions</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3612426)]  
**[ACL 2023]** <i>Causal Intervention and Counterfactual Reasoning for Multi-modal Fake News Detection</i> [[Paper](https://aclanthology.org/2023.acl-long.37.pdf)]  
**[AAAI 2023]** <i>Bootstrapping Multi-view Representations for Fake News Detection</i> [[Paper](https://openreview.net/pdf?id=tS2AkSDLYZ)]  
**[AAAI 2023]** <i>See How You Read? Multi-Reading Habits Fusion Reasoning for Multi-Modal Fake News Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/download/26609/26381)]  
**[AAAI 2023]** <i>FakeSV: A Multimodal Benchmark with Rich Social Context for Fake News Detection on Short Video Platforms</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/download/26689/26461)]  
**[AAAI 2023]** <i>COSMOS: Catching Out-of-Context Misinformation with Self-Supervised Learning</i> [[Paper](https://arxiv.org/pdf/2101.06278)]  
**[TKDE 2023]** <i>Causal Inference for Leveraging Image-text Matching Bias in Multi-modal Fake News Detection</i> [[Paper](https://ieeexplore.ieee.org/abstract/document/9996587/)]  
**[WWW 2022]** <i>Cross-modal Ambiguity Learning for Multimodal Fake News Detection</i> [[Paper](https://web.archive.org/web/20220428130656id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3511968)]  
**[WWW 2022]** <i>A Duo-generative Approach to Explainable Multimodal COVID-19 Misinformation Detection</i> [[Paper](https://web.archive.org/web/20220503034453id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3512257)]  
**[ACL 2021]** <i>InfoSurgeon: Cross-Media Fine-grained Information Consistency Checking for Fake News Detection</i> [[Paper](https://aclanthology.org/2021.acl-long.133.pdf)]  
**[ACL 2021]** <i>Multimodal Fusion with Co-Attention Networks for Fake News Detection</i> [[Paper](https://aclanthology.org/2021.findings-acl.226.pdf)]  
**[ACL 2021]** <i>Edited Media Understanding Frames: Reasoning About the Intents and Implications of Visual Disinformation</i> [[Paper](https://aclanthology.org/2021.acl-long.158.pdf)]  
**[CIKM 2021]** <i>Using Topic Modeling and Adversarial Neural Networks for Fake News Video Detection</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3459637.3482212)]  
**[CIKM 2021]** <i>Supervised Contrastive Learning for Multimodal Unreliable News Detection in COVID-19 Pandemic</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/2109/2109.01850.pdf)]  
**[KDD 2021]** <i>Multimodal Emergent Fake News Detection via Meta Neural Process Networks</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3447548.3467153)]  
**[IPM 2021]** <i>Detecting Fake News by Exploring the Consistency of Multimodal Data</i> [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0306457321001060)]  
**[MM 2021]** <i>Improving Fake News Detection by Using an Entity-enhanced Framework to Fuse Diverse Multimodal Clues</i> [[Paper](https://arxiv.org/pdf/2108.10509.pdf)]  
**[SIGIR 2021]** <i>Hierarchical Multi-modal Contextual Attention Network for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3462871)]  
**[EMNLP 2020]** <i>Detecting Cross-Modal Inconsistency to Defend Against Neural Fake News</i> [[Paper](https://arxiv.org/pdf/2009.07698.pdf)]  
**[PAKDD 2020]** <i>SAFE: Similarity-Aware Multi-Modal Fake News Detection</i> [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-47436-2_27)]  
**[WWW 2019]** <i>MVAE: Multimodal Variational Autoencoder for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3308558.3313552)]  
**[KDD 2018]** <i>EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3219903)]  

### Large Language Model-based Methods
**[ACL Findings 2024]** <i>DELL: Generating Reactions and Explanations for LLM-Based Misinformation Detection</i> [[Paper](https://aclanthology.org/2024.findings-acl.155.pdf)]  
**[WWW 2024]** <i>Explainable Fake News Detection With Large Language Model via Defense Among Competing Wisdom</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3589334.3645471)]  
**[Arxiv 2024]** <i>Re-Search for The Truth: Multi-round Retrieval-augmented Large Language Models are Strong Fake News Detectors</i> [[Paper](https://arxiv.org/pdf/2403.09747)]  
**[NAACL 2024]** <i>Evidence-Driven Retrieval Augmented Response Generation for Online Misinformation</i> [[Paper](https://arxiv.org/pdf/2403.14952)]  
**[CIKM 2024]** <i>Let Silence Speak: Enhancing Fake News Detection with Generated Comments from Large Language Models</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3627673.3679519)]  
**[AAAI 2024]** <i>Bad Actor, Good Advisor: Exploring the Role of Large Language Models in Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2309.12247)]  

---

## Social Media-based FND

**[AAAI 2023]** <i>HG-SL: Jointly Learning of Global and Local User Spreading Behavior for Fake News Early Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25655/25427)]  
**[KDD 2023]** <i>DECOR: Degree-Corrected Social Graph Refinement for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3580305.3599298)]  
**[WWW 2023]** <i>Attacking Fake News Detectors via Manipulating News Social Engagement</i> [[Paper](https://arxiv.org/pdf/2302.07363)]  
**[AAAI 2022]** <i>Towards Fine-Grained Reasoning for Fake News Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20517)]  
**[ACL 2022]** <i>Tackling Fake News Detection by Continually Improving Social Context Representations using Graph Neural Networks</i> [[Paper](https://aclanthology.org/2022.acl-long.97.pdf)]  
**[COLING 2022]** <i>Uncertainty-aware Propagation Structure Reconstruction for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.243.pdf)]  
**[COLING 2022]** <i>A Unified Propagation Forest-based Framework for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.244.pdf)]  
**[COLING 2022]** <i>Topology imbalance and Relation inauthenticity aware Hierarchical Graph Attention Networks for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.415.pdf)]  
**[KDD 2022]** <i>Reinforcement Subgraph Reasoning for Fake News Detection</i> [[Paper](https://www.microsoft.com/en-us/research/uploads/prod/2022/05/KDD2022_FakeNewsDetection_camera_ready.pdf)]  
**[WWW 2022]** <i>Divide-and-Conquer: Post-User Interaction Network for Fake News Detection on Social Media</i> [[Paper](https://www.atailab.cn/seminar2022fall/pdf/2022_WWW_Divide-and-Conquer_Post-User%20Interaction%20Network%20for%20Fake%20News%20Detection%20on%20Social%20Media.pdf)]  
**[KDD 2021]** <i>Causal Understanding of Fake News Dissemination on Social Media</i> [[Paper](https://arxiv.org/pdf/2010.10580.pdf)]  
**[SIGIR 2021]** <i>User Preference-aware Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3462990)]  

---

## Fact-check & Fact Verification

### Supervised Methods
**[NAACL 2024]** <i>Fact Checking Beyond Training Set</i> [[Paper](https://arxiv.org/pdf/2403.18671)]  
**[ICLR 2024]** <i>Unsupervised Pretraining for Fact Verification by Language Model Distillation</i> [[Paper](https://openreview.net/pdf?id=1mjsP8RYAw)]  
**[SIGIR 2023]** <i>Read it Twice: Towards Faithfully Interpretable Fact Verification by Revisiting Evidence</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3539618.3592049)]  
**[ACL 2023]** <i>DECKER: Double Check with Heterogeneous Knowledge for Commonsense Fact Verification</i> [[Paper](https://aclanthology.org/2023.findings-acl.752)]  
**[ACL 2023]** <i>Counterfactual Debiasing for Fact Verification</i> [[Paper](https://aclanthology.org/2023.acl-long.374.pdf)]  
**[ACL 2023]** <i>Fact-Checking Complex Claims with Program-Guided Reasoning</i> [[Paper](https://arxiv.org/pdf/2305.12744)]  
**[AAAI 2022]** <i>Synthetic Disinformation Attacks on Automated Fact Verification Systems</i> [[Paper](https://www.aaai.org/AAAI22Papers/AAAI-11986.DuY.pdf)]  
**[AAAI 2022]** <i>LOREN: Logic-Regularized Reasoning for Interpretable Fact Verification</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/21291)]  
**[SIGIR 2022]** <i>GERE: Generative Evidence Retrieval for Fact Verification</i> [[Paper](https://arxiv.org/pdf/2204.05511.pdf)]  
**[WWW 2022]** <i>EvidenceNet: Evidence Fusion Network for Fact Verification</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3485447.3512135)]  
**[ACL 2021]** <i>Zero-shot Fact Verification by Claim Generation</i> [[Paper](https://arxiv.org/pdf/2105.14682.pdf)]  
**[ACL 2021]** <i>Unified Dual-view Cognitive Model for Interpretable Claim Verification</i> [[Paper](https://arxiv.org/pdf/2105.09567.pdf)]  
**[ACL 2021]** <i>Topic-Aware Evidence Reasoning and Stance-Aware Aggregation for Fact Verification</i> [[Paper](https://arxiv.org/pdf/2106.01191.pdf)]  
**[ACL 2021]** <i>Structurizing Misinformation Stories via Rationalizing Fact-Checks</i> [[Paper](https://aclanthology.org/2021.acl-long.51.pdf)]  
**[ACL 2021]** <i>Exploring Listwise Evidence Reasoning with T5 for Fact Verification</i> [[Paper](https://aclanthology.org/2021.acl-short.51.pdf)]  
**[ACL 2021]** <i>Evidence-based Factual Error Correction</i> [[Paper](https://aclanthology.org/2021.acl-long.256.pdf)]  
**[ACL Findings 2021]** <i>Strong and Light Baseline Models for Fact-Checking Joint Inference</i> [[Paper](https://aclanthology.org/2021.findings-acl.426.pdf)]  
**[ACL Findings 2021]** <i>A Multi-Level Attention Model for Evidence-Based Fact Checking</i> [[Paper](https://arxiv.org/pdf/2106.00950.pdf)]  
**[CIKM 2021]** <i>CrossAug: A Contrastive Data Augmentation Method for Debiasing Fact Verification Models</i> [[Paper](https://arxiv.org/pdf/2109.15107.pdf)]  
**[EMNLP 2021]** <i>Students Who Study Together Learn Better: On the Importance of Collective Knowledge Distillation for Domain Transfer in Fact Verification</i> [[Paper](https://aclanthology.org/2021.emnlp-main.558.pdf?ref=https://githubhelp.com)]  
**[NAACL 2021]** <i>Towards Few-Shot Fact-Checking via Perplexity</i> [[Paper](https://arxiv.org/pdf/2103.09535.pdf)]  
**[NAACL 2021]** <i>How Robust are Fact Checking Systems on Colloquial Claims?</i> [[Paper](https://aclanthology.org/2021.naacl-main.121.pdf)]  

### LLM-based Methods
**[ACL 2024]** <i>Retrieval Augmented Fact Verification by Synthesizing Contrastive Arguments</i> [[Paper](https://arxiv.org/pdf/2406.09815)]  
**[NAACL 2024]** <i>Complex Claim Verification with Evidence Retrieved in the Wild</i> [[Paper](https://arxiv.org/pdf/2305.11859)]  
**[NAACL 2024]** <i>Language Models Hallucinate, but May Excel at Fact Verification</i> [[Paper](https://arxiv.org/pdf/2310.14564)]  
**[TACL 2024]** <i>JustiLM: Few-shot Justification Generation for Explainable Fact-Checking of Real-world Claims</i> [[Paper](https://arxiv.org/pdf/2401.08026.pdf)]  
**[Arxiv 2024]** <i>Can LLMs Produce Faithful Explanations For Fact-checking? Towards Faithful Explainable Fact-Checking via Multi-Agent Debate</i> [[Paper](https://arxiv.org/pdf/2402.07401)]  
**[EMNLP Findings 2023]** <i>Explainable Claim Verification via Knowledge-Grounded Reasoning with Large Language Models</i> [[Paper](https://aclanthology.org/2023.findings-emnlp.416.pdf)]  
**[AACL 2023]** <i>Towards LLM-based Fact Verification on News Claims with a Hierarchical Step-by-Step Prompting Method</i> [[Paper](https://arxiv.org/pdf/2310.00305)]  
**[Arxiv 2023]** <i>Are Large Language Models Good Fact Checkers: A Preliminary Study</i> [[Paper](https://arxiv.org/pdf/2311.17355)]  

### Multimodal Methods
**[Arxiv 2024]** <i>Multimodal Large Language Models to Support Real-World Fact-Checking</i> [[Paper](https://arxiv.org/pdf/2403.03627)]  
**[MM 2023]** <i>ECENet: Explainable and Context-Enhanced Network for Multi-modal Fact Verification</i> [[Paper](https://doi.org/10.1145/3581783.3612183)]  

### Multi-hop Fact Verification
**[AAAI 2023]** <i>Exploring Faithful Rationale for Multi-Hop Fact Verification via Salience-Aware Graph Learning</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26591/26363)]  
**[EMNLP 2023]** <i>EXPLAIN, EDIT, GENERATE: Rationale-Sensitive Counterfactual Data Augmentation for Multi-hop Fact Verification</i> [[Paper](https://aclanthology.org/2023.emnlp-main.826.pdf)]  
**[Arxiv 2023]** <i>Consistent Multi-Granular Rationale Extraction for Explainable Multi-hop Fact Verification</i> [[Paper](https://arxiv.org/pdf/2305.09400)]  
  
### Previously Fact-check

**[NAACL 2022]** <i>The Role of Context in Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2104.07423.pdf)]  
**[ACL 2021]** <i>Article Reranking by Memory-Enhanced Key Sentence Matching for Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2112.10322.pdf)]  
**[ACL 2021]** <i>Claim Matching Beyond English to Scale Global Fact-Checking</i> [[Paper](https://arxiv.org/pdf/2106.00853.pdf)]  
**[ACL 2020]** <i>That is a Known Lie: Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2005.06058.pdf)]  
**[EMNLP 2020]** <i>Where Are the Facts? Searching for Fact-checked Information to Alleviate the Spread of Fake News</i> [[Paper](https://arxiv.org/pdf/2010.03159.pdf)]  

### New Datasets

**[ACL 2022]** <i>FAVIQ: FAct Verification from Information-seeking Questions</i> [[Paper](https://arxiv.org/pdf/2107.02153.pdf)]  
**[ACL 2022]** <i>Misinfo Reaction Frames: Reasoning about Readers’ Reactions to News Headlines</i> [[Paper](https://arxiv.org/pdf/2104.08790.pdf)]  
**[ACL 2021]** <i>COVID-Fact: Fact Extraction and Verification of Real-World Claims on COVID-19 Pandemic</i> [[Paper](https://arxiv.org/pdf/2106.03794.pdf)]  

---

## Rumor Detection

### Supervised Methods
**[WWW 2024]** <i>Message Injection Attack on Rumor Detection under the Black-Box Evasion Setting Using Large Language Model</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3589334.3648139)]  
**[KDD 2023]** <i>Rumor Detection with Diverse Counterfactual Evidence</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3580305.3599494)]  
**[AAAI 2023]** <i>Zero-Shot Rumor Detection with Propagation Structure via Prompt Learning</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25651/25423)]  
**[AAAI 2022]** <i>DDGCN: Dual Dynamic Graph Convolutional Networks for Rumor Detection on Social Media</i> [[Paper](https://www.aaai.org/AAAI22Papers/AAAI-6370.SunM.pdf)]  
**[COLING 2022]** <i>A Progressive Framework for Role-Aware Rumor Resolution</i> [[Paper](https://aclanthology.org/2022.coling-1.242.pdf)]  
**[COLING 2022]** <i>Social Bot-Aware Graph Neural Network for Early Rumor Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.580.pdf)]  
**[NAACL 2022]** <i>Detect Rumors in Microblog Posts for Low-Resource Domains via Adversarial Contrastive Learning</i> [[Paper](https://arxiv.org/pdf/2204.08143.pdf)]  
**[WWW 2022]** <i>Rumor Detection on Social Media with Graph Adversarial Contrastive Learning</i> [[Paper](https://web.archive.org/web/20220505023214id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3511999)]  
**[WWW 2022]** <i>Detecting False Rumors from Retweet Dynamics on Social Media</i> [[Paper](https://arxiv.org/pdf/2201.13103.pdf)]  
**[ACL Findings 2021]** <i>Adversary-Aware Rumor Detection</i> [[Paper](https://aclanthology.org/2021.findings-acl.118.pdf)]  
**[ACL Findings 2021]** <i>Meet The Truth: Leverage Objective Facts and Subjective Views for Interpretable Rumor Detection</i> [[Paper](https://aclanthology.org/2021.findings-acl.63.pdf)]  
**[EMNLP 2021]** <i>Rumor Detection on Twitter with Claim-Guided Hierarchical Graph Attention Networks</i> [[Paper](https://aclanthology.org/2021.emnlp-main.786.pdf?ref=https://githubhelp.com)]  
**[EMNLP 2021]** <i>STANKER: Stacking Network based on Level-grained Attention-masked BERT for Rumor Detection on Social Media</i> [[Paper](https://aclanthology.org/2021.emnlp-main.269.pdf)]  
**[AAAI 2020]** <i>Rumor Detection on Social Media with Bi-Directional Graph Convolutional Networks</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5393)]  
**[COLING 2020]** <i>Debunking Rumors on Twitter with Tree Transformer</i> [[Paper](https://aclanthology.org/2020.coling-main.476.pdf?ref=https://githubhelp.com)]  
**[ACL 2018]** <i>Rumor Detection on Twitter with Tree-structured Recursive Neural Networks</i> [[Paper](https://aclanthology.org/P18-1184.pdf)]  

#### with Unreliable Propagations

**[ACL 2021]** <i>Towards Propagation Uncertainty: Edge-enhanced Bayesian Graph Convolutional Networks for Rumor Detection</i> [[Paper](https://aclanthology.org/2021.acl-long.297.pdf)]  
**[AAAI 2020]** <i>Interpretable Rumor Detection in Microblogs by Attending to User Interactions</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/6405)]  

#### with Temporal Features

**[COLING 2022]** <i>Continually Detection, Rapidly React: Unseen Rumors Detection based on Continual Prompt-Tuning</i> [[Paper](https://aclanthology.org/2022.coling-1.268.pdf)]  
**[NAACL 2022]** <i>Early Rumor Detection Using Neural Hawkes Process with a New Benchmark Dataset</i> [[Paper](https://aclanthology.org/2022.naacl-main.302.pdf)]  
**[WWW 2021]** <i>Rumor Detection with Field of Linear and Non-Linear Propagation</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3442381.3450016)]  
**[EMNLP 2020]** <i>A State-independent and Time-evolving Network for Early Rumor Detection in Social Media</i> [[Paper](https://aclanthology.org/2020.emnlp-main.727.pdf)]  

#### with User Profile

**[NAACL 2022]** <i>DUCK: Rumour Detection on Social Media by Modelling User and Comment Propagation Networks</i> [[Paper](https://aclanthology.org/2022.naacl-main.364.pdf)]  

#### with Data Augmentation

**[SIGIR ShortPaper 2021]** <i>Rumor Detection on Social Media with Event Augmentations</i> [[Paper](https://www.researchgate.net/profile/Zhenyu-He-5/publication/353188656_Rumor_Detection_on_Social_Media_with_Event_Augmentations/links/62e8f9a83c0ea87887765e3d/Rumor-Detection-on-Social-Media-with-Event-Augmentations.pdf)]  
**[ICLR 2019]** <i>Data Augmentation for Rumor Detection using Context-sensitive Neural Language Model with Large-scale Credibility</i> [[Paper](https://openreview.net/pdf?id=SyxCysRNdV)]  

### Multi-modal Methods

**[IJCAI 2022]** <i>MFAN: Multi-modal Feature-enhanced Attention Networks for Rumor Detection</i> [[Paper](https://www.ijcai.org/proceedings/2022/0335.pdf)]  
**[EMNLP 2021]** <i>Inconsistency Matters: A Knowledge-guided Dual-inconsistency Network for Multi-modal Rumor Detection</i> [[Paper](https://aclanthology.org/2021.findings-emnlp.122.pdf)]  
**[MM 2019]** <i>Multi-modal Knowledge-aware Event Memory Network for Social Media Rumor Detection</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3350850)]  
**[MM 2017]** <i>Multimodal Fusion with Recurrent Neural Networks for Rumor Detection on Microblogs</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3123266.3123454)]  

### Joint Stance & Rumor Detection

**[SIGIR 2022]** <i>A Weakly Supervised Propagation Model for Rumor Verification and Stance Detection with Multiple Instance Learning</i> [[Paper](https://arxiv.org/pdf/2204.02626.pdf)]  
**[ACL ShortPaper 2019]** <i>Rumor Detection By Exploiting User Credibility Information,  Attention and Multi-task Learning</i> [[Paper](https://aclanthology.org/P19-1113.pdf)]  
**[COLING 2018]** <i>All-in-one: Multi-task Learning for Rumour Verification</i> [[Paper](https://arxiv.org/pdf/1806.03713.pdf)]  
**[WWW 2018]** <i>Detect Rumor and Stance Jointly by Neural Multi-task Learning</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3184558.3188729)]  

---

## Summarizations of FND

#### Social Media-based Fake News Detection and Rumor Detection
1 **Interpretability**  
2 **Emergency** -> low-resource setting, event-invariant features, temporal information  
3 **Select bias / social homophily** -> edge augmentation  
4 **User profile** -> user embeddings, historical posts  
5 **Unreliable connections** -> graph reconstraction, edge reweighting  
6 **Temporal information**  
7 **Robustness** -> augmentation, adversarial learning  
8 **Stance detection**

#### Context-based Fake News Detection
1 **Interpretability**  
2 **Emergency**  
3 **Dynamicity (entity bias)**  
4 **Domain adaptation** -> pre-training, new datasets, adversarial learning, mixture of experts  
5 **Feature engineering** -> emotion, writing style  
6 **Semi-supervised Learning**  
7 **Robustness** -> adversarial attack  
8 **Evidence-based FND**  
9 **Multi-modal FND (ambiguity, alignment, emergency)**

---

## Famous Chinese Researchers in FND
- [Juan Cao](https://people.ucas.ac.cn/~caojuan), Institute of Computing Technology, Chinese Academy of Sciences
- [Jing Ma](https://majingcuhk.github.io/), Department of Computer Science, Hong Kong Baptist University
- [Huan Liu](https://www.public.asu.edu/~huanliu/), Ira A. Fulton Schools of Engineering, Arizona State University
- [Kai Shu](http://www.cs.iit.edu/~kshu/index.html), Department of Computer Science, Illinois Institute of Technology
- [Songlin Hu](https://people.ucas.edu.cn/~husonglin), Institute of Information Engineering, Chinese Academy of Sciences
- [Linmei Hu](https://scholar.google.com/citations?user=OphdKw8AAAAJ&hl=zh-CN&oi=ao), Beijing Institute of Technology
