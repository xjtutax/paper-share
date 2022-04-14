# EMNLP2021 信息抽取

[toc]

地址：https://2021.emnlp.org/papers#main-long

> 本文首发于我的公号《**[高能AI](https://mp.weixin.qq.com/s?__biz=MzI5NjA4MDIyMw==&mid=2656168794&idx=1&sn=2d42765e4f71c7ab4630ecb96c40ef1c&chksm=f7ec8d6ac09b047c77713f5d8248517a10cc43eff00fdb2801af6d86e3395b49b562930c4b16&token=899571521&lang=zh_CN#rd)**》，大家一定要关注哦～

## **一、实体抽取（共19篇）**

> 实体抽取主要涉及小样本NER、降噪NER、跨领域NER、细粒度实体分类、实体集拓展、NER鲁棒性、实体链接和消歧等

**小样本&低资源&降噪&跨领域NER**

1. Few-Shot Named Entity Recognition: An Empirical Baseline Study
2. Learning from Noisy Labels for Entity-Centric Information Extraction
3. Data Augmentation for Cross-Domain Named Entity Recognition
4. Unsupervised Paraphrasing Consistency Training for Low Resource Named Entity Recognition

**细粒度实体分类&实体集拓展**

1. Fine-grained Entity Typing without Knowledge
2. An Empirical Study on Multiple Information Sources for Zero-Shot Fine-Grained Entity Typing
3. Fine-grained Entity Typing via Label Reasoning
4. Progressive Adversarial Learning for Bootstrapping: A Case Study on Entity Set Expansion

**NER鲁棒性**

1. RockNER: A Simple Method to Create Adversarial Examples for Evaluating the Robustness of Named Entity Recognition Models
2. SeqAttack: On Adversarial Attacks for Named Entity Recognition

**实体链接&消歧**

1. Low-Rank Subspaces for Unsupervised Entity Linking
2. ActiveEA: Active Learning for Neural Entity Alignment
3. Highly Parallel Autoregressive Entity Linking with Discriminative Correction
4. End-to-End Entity Resolution and Question Answering Using Differentiable Knowledge
5. From Alignment to Assignment: Frustratingly Simple Unsupervised Entity Alignment
6. Robustness Evaluation of Entity Disambiguation Using Prior Probes: the Case of Entity Overshadowing

**其他**

1. TEBNER: Domain Specific Named Entity Recognition with Type Expanded Boundary-aware Network
2. Document-level Entity-based Extraction as Template Generation
3. Injecting Entity Types into Entity-Guided Text Generation
4. Enhanced Language Representation with Label Knowledge for Span Extraction
5. ChemNER: Fine-Grained Chemistry Named Entity Recognition with Ontology-Guided Distant Supervision

## **二、关系抽取（共19篇）**

> 关系抽取主要涉及等远程监督抽取、联合抽取、文档级别抽取、小样本抽取等。

**远程监督关系抽取**

1. Distantly Supervised Relation Extraction using Multi-Layer Revision Network and Confidence-based Multi-Instance Learning
2. Knowing False Negatives: An Adversarial Training Method for Distantly Supervised Relation Extraction

**实体关系联合抽取**

1. TDEER: An Efficient Translating Decoding Schema for Joint Extraction of Entities and Relations
2. A Partition Filter Network for Joint Entity and Relation Extraction
3. A Novel Global Feature-Oriented Relational Triple Extraction Model based on Table Filling
4. Synchronous Dual Network with Cross-Type Attention for Joint Entity and Relation Extraction

**文档级别关系抽取**

1. Modular Self-Supervision for Document-Level Relation Extraction
2. CodRED: A Cross-Document Relation Extraction Dataset for Acquiring Knowledge in the Wild
3. Learning Logic Rules for Document-Level Relation Extraction

**小样本&低资源关系抽取**

1. Exploring Task Difficulty for Few-Shot Relation Extraction
2. MapRE: An Effective Semantic Mapping Approach for Low-resource Relation Extraction
3. Label Verbalization and Entailment for Effective Zero and Few-Shot Relation Extraction
4. Unsupervised Relation Extraction: A Variational Autoencoder Approach
5. Gradient Imitation Reinforcement Learning for Low Resource Relation Extraction
6. Towards Realistic Few-Shot Relation Extraction

**对话关系抽取**

1. Speaker-Oriented Latent Structures for Dialogue-Based Relation Extraction

**其他**

1. Relation Extraction with Word Graphs from N-grams
2. Separating Retention from Extraction in the Evaluation of End-to-end Relation Extraction
3. Incorporating medical knowledge in BERT for clinical relation extraction

## **三、事件抽取（共7篇）**

1. Machine Reading Comprehension as Data Augmentation: A Case Study on Implicit Event Argument Extraction
2. Modeling Document-Level Context for Event Detection via Important Context Selection
3. Extracting Event Temporal Relations via Hyperbolic Geometry
4. Utilizing Relative Event Time to Enhance Event-Event Temporal Relation Extraction
5. Corpus-based Open-Domain Event Type Induction
6. Honey or Poison? Solving the Trigger Curse in Few-shot Event Detection via Causal Intervention
7. Learning Prototype Representations Across Few-Shot Tasks for Event Detection

## **四、信息抽取（综合，共9篇）**

> 综合类的信息抽取主要涉及开放抽取、多模抽取、跨语言抽取、长尾抽取。

**开放信息抽取**

1. Maximal Clique Based Non-Autoregressive Open Information Extraction
2. A Relation-Oriented Clustering Method for Open Relation Extraction
3. Zero-Shot Information Extraction as a Unified Text-to-Triple Translation

**多模信息抽取**

1. Entity Relation Extraction as Dependency Parsing in Visually Rich Documents
2. Cost-effective End-to-end Information Extraction for Semi-structured Document Images

**跨语言信息抽取**

1. Everything Is All It Takes: A Multipronged Strategy for Zero-Shot Cross-Lingual Information Extraction
2. Crosslingual Transfer Learning for Relation and Event Extraction via Word Category and Class Alignments
3. XLEnt: Mining a Large Cross-lingual Entity Dataset with Lexical-Semantic-Phonetic Word Alignment

**长尾信息抽取**

1. Uncovering Main Causalities for Long-tailed Information Extraction

## **五、关键词&短语抽取（共4篇）**

1. Unsupervised Keyphrase Extraction by Jointly Modeling Local and Global Context
2. Back to the Basics: A Quantitative Analysis of Statistical and Graph-Based Term Weighting Schemes for Keyword Extraction
3. AttentionRank: Unsupervised Keyphrase Extraction using Self and Cross Attentions
4. Importance Estimation from Multiple Perspectives for Keyphrase Extraction

## **六、属性抽取&观点抽取（共4篇）**

1. DILBERT: Customized Pre-Training for Domain Adaptation with Category Shift, with an Application to Aspect Extraction
2. Progressive Self-Training with Discriminator for Aspect Term Extraction
3. PASTE: A Tagging-Free Decoding Framework Using Pointer Networks for Aspect Sentiment Triplet Extraction
4. An Empirical Study on Leveraging Position Embeddings for Target-oriented Opinion Words Extraction