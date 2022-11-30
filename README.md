## Fake News Detection

An awesome paper list of **fake news detection (FND)** and **rumor detection** with ![](https://img.shields.io/badge/101-red) papers. FND methods are divided into context-based and social media-based methods.  
Moreover, this is a personal list, if you have some additional literature, which need be supplemented, you can feel free to drop an email (wangbing1416@gmail.com) to me!


- [Fake News Detection](#fake-news-detection)
  - [Context-based FND](#context-based-fnd)
    - [Text-only Methods](#text-only-methods)
      - [Supervised Learning](#supervised-learning)
      - [Domain Adaptation](#domain-adaptation)
      - [Knowledge base-based](#knowledge-base-based)
      - [Machine-generated News Detection](#machine-generated-news-detection)
    - [Evidence-aware Methods](#evidence-aware-methods)
    - [Multi-modal Methods](#multi-modal-methods)
  - [Social Media-based FND](#social-media-based-fnd)
  - [Fact-check & Fact Verification](#fact-check--fact-verification)
    - [Supervised Methods](#supervised-methods)
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


### Context-based FND

#### Text-only Methods

##### Supervised Learning

- ACL 2022, <i>Zoom Out and Observe: News Environment Perception for Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2203.10885.pdf)]
- COLING 2022, <i>A Coarse-to-fine Cascaded Evidence-Distillation Neural Network for Explainable Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2209.14642.pdf)]
- COLING 2022, <i>Demystifying Neural Fake News via Linguistic Feature-Based Interpretation</i> [[Paper](https://aclanthology.org/2022.coling-1.573.pdf)]
- SIGIR 2022, <i>Generalizing to the Future: Mitigating Entity Bias in Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3477495.3531816)]
- ECML 2021, <i>Early Detection of Fake News with Multi-source Weak Social Supervision</i> [[Paper](http://www.cs.iit.edu/~kshu/files/ecml_pkdd_mwss.pdf)]
- WWW 2021, <i>Mining Dual Emotion for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3450004)]
- ICCART 2019, <i>Fake News Detection via NLP is Vulnerable to Adversarial Attacks</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/1901/1901.09657.pdf)]

##### Domain Adaptation

- COLING 2022, <i>Improving Fake News Detection of Influential Domain via Domain- and Instance-Level Transfer</i> [[Paper](https://arxiv.org/pdf/2209.08902.pdf)]
- WWW 2022, <i>Domain Adaptive Fake News Detection via Reinforcement Learning</i> [[Paper](https://arxiv.org/pdf/2202.08159.pdf)]
- TKDE 2022, <i>Memory-Guided Multi-View Multi-Domain Fake News Detection</i> [[Paper](https://ieeexplore.ieee.org/document/9802916)]
- IPM 2022, <i>Characterizing Multi-Domain False News and Underlying User Effects on Chinese Weibo</i> [[Paper](https://www.sciencedirect.com/science/article/pii/S0306457322000784?via%3Dihub)]
- ArXiv 2022, <i>FuDFEND: Fuzzy-domain for Multi-domain Fake News Detection</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/2205/2205.03778.pdf)]
- CIKM 2021, <i>MDFEND: Multi-domain Fake News Detection</i> [[Paper](https://arxiv.org/pdf/2201.00987.pdf)]
- ICONIP 2021, <i>DAFD: Domain Adaptation Framework for Fake News Detection</i> [[Paper](http://www.cs.iit.edu/~kshu/files/DAFD_ICONIP.pdf)]

##### Knowledge base-based

- IPM 2022, <i>Fake News Detection via Knowledgeable Prompt Learning</i> [[Paper](https://www.sciencedirect.com/science/article/pii/S030645732200139X)]
- AAAI 2021, <i>KAN: Knowledge-aware Attention Network for Fake News Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16080)]
- ACL 2021, <i>Compare to The Knowledge: Graph Neural Fake News Detection with External Knowledge</i> [[Paper](https://aclanthology.org/2021.acl-long.62.pdf)]

##### Machine-generated News Detection

- ACL 2022, <i>Automatic Detection of Entity-Manipulated Text Using Factual Knowledge</i> [[Paper](https://aclanthology.org/2022.acl-short.10.pdf)]
- COLING 2022, <i>Threat Scenarios and Best Practices for Neural Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.106.pdf)]
- CL 2020, <i>The Limitations of Stylometry for Detecting Machine-Generated Fake News</i> [[Paper](https://watermark.silverchair.com/coli_a_00380.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAq4wggKqBgkqhkiG9w0BBwagggKbMIIClwIBADCCApAGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMxz9Xg1SndcEbQDYRAgEQgIICYezKOBSVkeblU0UiMgQBFTxwWxvVxyHMsoZNjebxXy_s7hVI8uyU1oxQJ0CFP1zIZd65qql15yVtv5CEq3RHl7TKSCYtFPWhMF4t-1jQaugAnyONxxeNuzPqHSrswxpjDG8HveRLQUiwoftHtfwjc0xUKG7pgHOpjXTWslc2XcQLv4HZ_krec_fLwygsTymj7jkzhn2v2aZdrpNXXzInEajuZA6bNeVhOfUmH2RaKMeRtrvVgXz6hiGn-zvZq2bcBWdHRueLpJY2vakrzJnQf42CghuRVvzxP2Hj-qfBfb08YnQI3lwmbERyn4GiKxAfQzyEoX_tkY8nqwpOm8t5wA-tTHW_AYKXQsoQMp1j2Q8wShdDRVQMnGyWLgxNR5WOJTgTvmcnr6D1tQTJhd_ilxUPCvNd8RnD4fU_7jWXeeEDtb5hQi45zKVUp9SropLnacTuOiQN4xY1saSH8EQCdNHJ79X9QZ2Ii7NGZrVm4ZCVcpN4DqHgR3WFeHPKZrTyT_6fluW-Mc69SpuIhu7nRLgavhAbyC8UAHS_Krk6vhch1GWIMPXeWyfo66jNJ_jZUUY8lEnoNfsfuyARpqb9x0IEseo_5WeHpR2SrQpWGlWxWBO8Twwi0nJgp9nlv4Ig7a4LAG66UXxRbzQs0kXENqOJM_qRVCIAKF_JDgKhXnk8Xoq15o-3fTdUeYlv-7mS_4XpA0f8l9nVRmq2GMwiNe41JuA1yV5nggN91T6bEC7mq9Vnc9x9B6uXji2tOT6TD7cmh-2XQl7CIbBvRfyLJpieHR0vFBydp9mnHXVuTT8v1Q)]

#### Evidence-aware Methods

- SIGIR 2022, <i>Bias Mitigation for Evidence-aware Fake News Detection by Causal Intervention</i> [[Paper](https://web.archive.org/web/20220712063219id_/https://dl.acm.org/doi/pdf/10.1145/3477495.3531850)]
- WWW 2022, <i>Evidence-aware Fake News Detection with Graph Neural Networks</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3485447.3512122)]
- ACL 2021, <i>Automatic Fake News Detection: Are Models Learning to Reason?</i> [[Paper](https://arxiv.org/pdf/2105.07698.pdf)]
- CIKM 2021, <i>Integrating Pattern- and Fact-based Fake News Detection via Model Preference Learning</i> [[Paper](https://arxiv.org/pdf/2109.11333.pdf)]

#### Multi-modal Methods

- WWW 2022, <i>Cross-modal Ambiguity Learning for Multimodal Fake News Detection</i> [[Paper](https://web.archive.org/web/20220428130656id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3511968)]
- WWW 2022, <i>A Duo-generative Approach to Explainable Multimodal COVID-19 Misinformation Detection</i> [[Paper](https://web.archive.org/web/20220503034453id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3512257)]
- ACL 2021, <i>InfoSurgeon: Cross-Media Fine-grained Information Consistency Checking for Fake News Detection</i> [[Paper](https://aclanthology.org/2021.acl-long.133.pdf)]
- ACL 2021, <i>Multimodal Fusion with Co-Attention Networks for Fake News Detection</i> [[Paper](https://aclanthology.org/2021.findings-acl.226.pdf)]
- ACL 2021, <i>Edited Media Understanding Frames: Reasoning About the Intents and Implications of Visual Disinformation</i> [[Paper](https://aclanthology.org/2021.acl-long.158.pdf)]
- CIKM 2021, <i>Supervised Contrastive Learning for Multimodal Unreliable News Detection in COVID-19 Pandemic</i> [[Paper](https://arxiv.org/ftp/arxiv/papers/2109/2109.01850.pdf)]
- KDD 2021, <i>Multimodal Emergent Fake News Detection via Meta Neural Process Networks</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3447548.3467153)]
- IPM 2021, <i>Detecting Fake News by Exploring the Consistency of Multimodal Data</i> [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0306457321001060)]
- MM 2021,  <i>Improving Fake News Detection by Using an Entity-enhanced Framework to Fuse Diverse Multimodal Clues</i> [[Paper](https://arxiv.org/pdf/2108.10509.pdf)]
- SIGIR 2021, <i>Hierarchical Multi-modal Contextual Attention Network for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3462871)]
- EMNLP 2020, <i>Detecting Cross-Modal Inconsistency to Defend Against Neural Fake News</i> [[Paper](https://arxiv.org/pdf/2009.07698.pdf)]
- PAKDD 2020, <i>SAFE: Similarity-Aware Multi-Modal Fake News Detection</i> [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-47436-2_27)]
- WWW 2019, <i>MVAE: Multimodal Variational Autoencoder for Fake News Detection</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3308558.3313552)]
- KDD 2018, <i>EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3219903)]



---

### Social Media-based FND

- AAAI 2022, <i>Towards Fine-Grained Reasoning for Fake News Detection</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20517)]
- ACL 2022, <i>Tackling Fake News Detection by Continually Improving Social Context Representations using Graph Neural Networks</i> [[Paper](https://aclanthology.org/2022.acl-long.97.pdf)]
- COLING 2022, <i>Uncertainty-aware Propagation Structure Reconstruction for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.243.pdf)]
- COLING 2022, <i>A Unified Propagation Forest-based Framework for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.244.pdf)]
- COLING 2022, <i>Topology imbalance and Relation inauthenticity aware Hierarchical Graph Attention Networks for Fake News Detection</i> [[Paper](https://aclanthology.org/2022.coling-1.415.pdf)]
- KDD 2022, <i>Reinforcement Subgraph Reasoning for Fake News Detection</i> [[Paper](https://www.microsoft.com/en-us/research/uploads/prod/2022/05/KDD2022_FakeNewsDetection_camera_ready.pdf)]
- WWW 2022, <i>Divide-and-Conquer: Post-User Interaction Network for Fake News Detection on Social Media</i> [[Paper](https://www.atailab.cn/seminar2022fall/pdf/2022_WWW_Divide-and-Conquer_Post-User%20Interaction%20Network%20for%20Fake%20News%20Detection%20on%20Social%20Media.pdf)]
- KDD 2021, <i>Causal Understanding of Fake News Dissemination on Social Media</i> [[Paper](https://arxiv.org/pdf/2010.10580.pdf)]
- SIGIR 2021, <i>User Preference-aware Fake News Detection</i> [[Paper](https://dl.acm.org/doi/pdf/10.1145/3404835.3462990)]

---

### Fact-check & Fact Verification

#### Supervised Methods

- AAAI 2022, <i>Synthetic Disinformation Attacks on Automated Fact Verification Systems</i> [[Paper](https://www.aaai.org/AAAI22Papers/AAAI-11986.DuY.pdf)]
- AAAI 2022, <i>LOREN: Logic-Regularized Reasoning for Interpretable Fact Verification</i> [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/21291)]
- SIGIR 2022, <i>GERE: Generative Evidence Retrieval for Fact Verification</i> [[Paper](https://arxiv.org/pdf/2204.05511.pdf)]
- WWW 2022, <i>EvidenceNet: Evidence Fusion Network for Fact Verification</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3485447.3512135)]
- ACL 2021, <i>Zero-shot Fact Verification by Claim Generation</i> [[Paper](https://arxiv.org/pdf/2105.14682.pdf)]
- ACL 2021, <i>Unified Dual-view Cognitive Model for Interpretable Claim Verification</i> [[Paper](https://arxiv.org/pdf/2105.09567.pdf)]
- ACL 2021, <i>Topic-Aware Evidence Reasoning and Stance-Aware Aggregation for Fact Verification</i> [[Paper](https://arxiv.org/pdf/2106.01191.pdf)]
- ACL 2021, <i>Structurizing Misinformation Stories via Rationalizing Fact-Checks</i> [[Paper](https://aclanthology.org/2021.acl-long.51.pdf)]
- ACL 2021, <i>Exploring Listwise Evidence Reasoning with T5 for Fact Verification</i> [[Paper](https://aclanthology.org/2021.acl-short.51.pdf)]
- ACL 2021, <i>Evidence-based Factual Error Correction</i> [[Paper](https://aclanthology.org/2021.acl-long.256.pdf)]
- ACL Findings 2021, <i>Strong and Light Baseline Models for Fact-Checking Joint Inference</i> [[Paper](https://aclanthology.org/2021.findings-acl.426.pdf)]
- ACL Findings 2021, <i>A Multi-Level Attention Model for Evidence-Based Fact Checking</i> [[Paper](https://arxiv.org/pdf/2106.00950.pdf)]
- CIKM 2021, <i>CrossAug: A Contrastive Data Augmentation Method for Debiasing Fact Verification Models</i> [[Paper](https://arxiv.org/pdf/2109.15107.pdf)]
- EMNLP 2021, <i>Students Who Study Together Learn Better: On the Importance of Collective Knowledge Distillation for Domain Transfer in Fact Verification</i> [[Paper](https://aclanthology.org/2021.emnlp-main.558.pdf?ref=https://githubhelp.com)]
- NAACL 2021, <i>Towards Few-Shot Fact-Checking via Perplexity</i> [[Paper](https://arxiv.org/pdf/2103.09535.pdf)]
- NAACL 2021, <i>How Robust are Fact Checking Systems on Colloquial Claims?</i> [[Paper](https://aclanthology.org/2021.naacl-main.121.pdf)]

#### Previously Fact-check

- NAACL 2022, <i>The Role of Context in Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2104.07423.pdf)]
- ACL 2021, <i>Article Reranking by Memory-Enhanced Key Sentence Matching for Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2112.10322.pdf)]
- ACL 2021, <i>Claim Matching Beyond English to Scale Global Fact-Checking</i> [[Paper](https://arxiv.org/pdf/2106.00853.pdf)]
- ACL 2020, <i>That is a Known Lie: Detecting Previously Fact-Checked Claims</i> [[Paper](https://arxiv.org/pdf/2005.06058.pdf)]
- EMNLP 2020, <i>Where Are the Facts? Searching for Fact-checked Information to Alleviate the Spread of Fake News</i> [[Paper](https://arxiv.org/pdf/2010.03159.pdf)]

#### New Datasets

- ACL 2022, <i>FAVIQ: FAct Verification from Information-seeking Questions</i> [[Paper](https://arxiv.org/pdf/2107.02153.pdf)]
- ACL 2022, <i>Misinfo Reaction Frames: Reasoning about Readers’ Reactions to News Headlines</i> [[Paper](https://arxiv.org/pdf/2104.08790.pdf)]
- ACL 2021, <i>COVID-Fact: Fact Extraction and Verification of Real-World Claims on COVID-19 Pandemic</i> [[Paper](https://arxiv.org/pdf/2106.03794.pdf)]

---

### Rumor Detection

#### Supervised Methods

- AAAI 2022, *DDGCN: Dual Dynamic Graph Convolutional Networks for Rumor Detection on Social Media* [[Paper](https://www.aaai.org/AAAI22Papers/AAAI-6370.SunM.pdf)]
- COLING 2022, *A Progressive Framework for Role-Aware Rumor Resolution* [[Paper](https://aclanthology.org/2022.coling-1.242.pdf)]
- COLING 2022, *Social Bot-Aware Graph Neural Network for Early Rumor Detection* [[Paper](https://aclanthology.org/2022.coling-1.580.pdf)]
- NAACL 2022, *Detect Rumors in Microblog Posts for Low-Resource Domains via Adversarial Contrastive Learning* [[Paper](https://arxiv.org/pdf/2204.08143.pdf)]
- WWW 2022, Rumor Detection on Social Media with Graph Adversarial Contrastive Learning [[Paper](https://web.archive.org/web/20220505023214id_/https://dl.acm.org/doi/pdf/10.1145/3485447.3511999)]
- WWW 2022, Detecting False Rumors from Retweet Dynamics on Social Media [[Paper](https://arxiv.org/pdf/2201.13103.pdf)]
- ACL Findings 2021, *Adversary-Aware Rumor Detection* [[Paper](https://aclanthology.org/2021.findings-acl.118.pdf)]
- ACL Findings 2021, *Meet The Truth: Leverage Objective Facts and Subjective Views for Interpretable Rumor Detection* [[Paper](https://aclanthology.org/2021.findings-acl.63.pdf)]
- EMNLP 2021, *Rumor Detection on Twitter with Claim-Guided Hierarchical Graph Attention Networks* [[Paper](https://aclanthology.org/2021.emnlp-main.786.pdf?ref=https://githubhelp.com)]
- EMNLP 2021, *STANKER: Stacking Network based on Level-grained Attention-masked BERT for Rumor Detection on Social Media* [[Paper](https://aclanthology.org/2021.emnlp-main.269.pdf)]
- AAAI 2020, *Rumor Detection on Social Media with Bi-Directional Graph Convolutional Networks* [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5393)]
- COLING 2020, *Debunking Rumors on Twitter with Tree Transformer* [[Paper](https://aclanthology.org/2020.coling-main.476.pdf?ref=https://githubhelp.com)]
- ACL 2018, *Rumor Detection on Twitter with Tree-structured Recursive Neural Networks* [[Paper](https://aclanthology.org/P18-1184.pdf)]

##### with Unreliable Propagations

- ACL 2021, *Towards Propagation Uncertainty: Edge-enhanced Bayesian Graph Convolutional Networks for Rumor Detection* [[Paper](https://aclanthology.org/2021.acl-long.297.pdf)]
- AAAI 2020, *Interpretable Rumor Detection in Microblogs by Attending to User Interactions* [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/6405)]

##### with Temporal Features

- COLING 2022, *Continually Detection, Rapidly React: Unseen Rumors Detection based on Continual Prompt-Tuning* [[Paper](https://aclanthology.org/2022.coling-1.268.pdf)]
- NAACL 2022, *Early Rumor Detection Using Neural Hawkes Process with a New Benchmark Dataset* [[Paper](https://aclanthology.org/2022.naacl-main.302.pdf)]
- WWW 2021, *Rumor Detection with Field of Linear and Non-Linear Propagation* [[Paper](https://dl.acm.org/doi/abs/10.1145/3442381.3450016)]
- EMNLP 2020, *A State-independent and Time-evolving Network for Early Rumor Detection in Social Media* [[Paper](https://aclanthology.org/2020.emnlp-main.727.pdf)]

##### with User Profile

- NAACL 2022, *DUCK: Rumour Detection on Social Media by Modelling User and Comment Propagation Networks* [[Paper](https://aclanthology.org/2022.naacl-main.364.pdf)]

##### with Data Augmentation

- SIGIR ShortPaper 2021, *Rumor Detection on Social Media with Event Augmentations* [[Paper](https://www.researchgate.net/profile/Zhenyu-He-5/publication/353188656_Rumor_Detection_on_Social_Media_with_Event_Augmentations/links/62e8f9a83c0ea87887765e3d/Rumor-Detection-on-Social-Media-with-Event-Augmentations.pdf)]
- ICLR 2019, *Data Augmentation for Rumor Detection using Context-sensitive Neural Language Model with Large-scale Credibility* [[Paper](https://openreview.net/pdf?id=SyxCysRNdV)]

#### Multi-modal Methods

- IJCAI 2022, *MFAN: Multi-modal Feature-enhanced Attention Networks for Rumor Detection* [[Paper](https://www.ijcai.org/proceedings/2022/0335.pdf)]
- EMNLP 2021, <i>Inconsistency Matters: A Knowledge-guided Dual-inconsistency Network for Multi-modal Rumor Detection</i> [[Paper](https://aclanthology.org/2021.findings-emnlp.122.pdf)]
- MM 2019, <i>Multi-modal Knowledge-aware Event Memory Network for Social Media Rumor Detection</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3350850)]
- MM 2017, <i>Multimodal Fusion with Recurrent Neural Networks for Rumor Detection on Microblogs</i> [[Paper](https://dl.acm.org/doi/abs/10.1145/3123266.3123454)]

#### Joint Stance & Rumor Detection

- SIGIR 2022, *A Weakly Supervised Propagation Model for Rumor Verification and Stance Detection with Multiple Instance Learning* [[Paper](https://arxiv.org/pdf/2204.02626.pdf)]
- ACL ShortPaper 2019, *Rumor Detection By Exploiting User Credibility Information,  Attention and Multi-task Learning* [[Paper](https://aclanthology.org/P19-1113.pdf)]
- COLING 2018, *All-in-one: Multi-task Learning for Rumour Verification* [[Paper](https://arxiv.org/pdf/1806.03713.pdf)]
- WWW 2018, *Detect Rumor and Stance Jointly by Neural Multi-task Learning* [[Paper](https://dl.acm.org/doi/pdf/10.1145/3184558.3188729)]
