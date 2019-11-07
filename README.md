# BERT-related Papers
This is a list of BERT-related papers. Any feedback is welcome.

## Table of Contents
- [Downstream task](#downstream-task)
- [Generation](#generation)
- [Modification (multi-task, masking strategy, etc.)](#modification-multi-task-masking-strategy-etc)
- [Probe](#probe)
- [Inside BERT](#inside-bert)
- [Multi-lingual](#multi-lingual)
- [Domain specific](#domain-specific)
- [Multi-modal](#multi-modal)
- [Model compression](#model-compression)
- [Misc.](#misc)

## Downstream task
### QA, MC, Dialogue
- [A BERT Baseline for the Natural Questions](https://arxiv.org/abs/1901.08634)
- [MultiQA: An Empirical Investigation of Generalization and Transfer in Reading Comprehension](https://arxiv.org/abs/1905.13453) (ACL2019)
- [A Multi-Type Multi-Span Network for Reading Comprehension that Requires Discrete Reasoning](https://arxiv.org/abs/1908.05514) (EMNLP2019)
- [SDNet: Contextualized Attention-based Deep Network for Conversational Question Answering](https://arxiv.org/abs/1812.03593)
- [Multi-hop Question Answering via Reasoning Chains](https://arxiv.org/abs/1910.02610)
- [Select, Answer and Explain: Interpretable Multi-hop Reading Comprehension over Multiple Documents](https://arxiv.org/abs/1911.00484)
- [Multi-step Entity-centric Information Retrieval for Multi-Hop Question Answering](https://arxiv.org/abs/1909.07598) (EMNLP2019 WS)
- [End-to-End Open-Domain Question Answering with BERTserini](https://arxiv.org/abs/1902.01718) (NAALC2019)
- [Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://arxiv.org/abs/1906.00300) (ACL2019)
- [Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering](https://arxiv.org/abs/1908.08167) (EMNLP2019)
- [Learning to Ask Unanswerable Questions for Machine Reading Comprehension](https://arxiv.org/abs/1906.06045) (ACL2019)
- [Unsupervised Question Answering by Cloze Translation](https://arxiv.org/abs/1906.04980) (ACL2019)
- [Reinforcement Learning Based Graph-to-Sequence Model for Natural Question Generation](https://arxiv.org/abs/1908.04942)
- [Learning to Answer by Learning to Ask: Getting the Best of GPT-2 and BERT Worlds](https://arxiv.org/abs/1911.02365)
- [Enhancing Pre-Trained Language Representations with Rich Knowledge for Machine Reading Comprehension](https://www.aclweb.org/anthology/papers/P/P19/P19-1226/) (ACL2019)
- [Incorporating Relation Knowledge into Commonsense Reading Comprehension with Multi-task Learning](https://arxiv.org/abs/1908.04530) (CIKM2019)
- [SG-Net: Syntax-Guided Machine Reading Comprehension](https://arxiv.org/abs/1908.05147)
- [MMM: Multi-stage Multi-task Learning for Multi-choice Reading Comprehension](https://arxiv.org/abs/1910.00458)
- [A Simple but Effective Method to Incorporate Multi-turn Context with BERT for Conversational Machine Comprehension](https://arxiv.org/abs/1905.12848) (ACL2019 WS)
- [FlowDelta: Modeling Flow Information Gain in Reasoning for Conversational Machine Comprehension](https://arxiv.org/abs/1908.05117) (ACL2019 WS)
- [BERT with History Answer Embedding for Conversational Question Answering](https://arxiv.org/abs/1905.05412) (SIGIR2019)
- [GraphFlow: Exploiting Conversation Flow with Graph Neural Networks for Conversational Machine Comprehension](https://arxiv.org/abs/1908.00059) (ICML2019 WS)
- [Beyond English-only Reading Comprehension: Experiments in Zero-Shot Multilingual Transfer for Bulgarian](https://arxiv.org/abs/1908.01519) (RANLP2019)
- [Cross-Lingual Machine Reading Comprehension](https://arxiv.org/abs/1909.00361) (EMNLP2019)
- [Zero-shot Reading Comprehension by Cross-lingual Transfer Learning with Multi-lingual Language Representation Model](https://arxiv.org/abs/1909.09587)
- [Multilingual Question Answering from Formatted Text applied to Conversational Agents](https://arxiv.org/abs/1910.04659)
- [BiPaR: A Bilingual Parallel Dataset for Multilingual and Cross-lingual Reading Comprehension on Novels](https://arxiv.org/abs/1910.05040) (EMNLP2019)
- [MLQA: Evaluating Cross-lingual Extractive Question Answering](https://arxiv.org/abs/1910.07475)
- [Giving BERT a Calculator: Finding Operations and Arguments with Reading Comprehension](https://arxiv.org/abs/1909.00109) (EMNLP2019)
- [BERT for Joint Intent Classification and Slot Filling](https://arxiv.org/abs/1902.10909)
- [Multi-lingual Intent Detection and Slot Filling in a Joint BERT-based Model](https://arxiv.org/abs/1907.02884)
- [BERT-DST: Scalable End-to-End Dialogue State Tracking with Bidirectional Encoder Representations from Transformer](https://arxiv.org/abs/1907.03040) (Interspeech2019)
- [Dialog State Tracking: A Neural Reading Comprehension Approach](https://arxiv.org/abs/1908.01946) 
- [A Simple but Effective BERT Model for Dialog State Tracking on Resource-Limited Systems](https://arxiv.org/abs/1910.12995)
- [Domain Adaptive Training BERT for Response Selection](https://arxiv.org/abs/1908.04812)
- [BERT Goes to Law School: Quantifying the Competitive Advantage of Access to Large Legal Corpora in Contract Understanding](https://arxiv.org/abs/1911.00473)
### Analysis
- [Fine-grained Information Status Classification Using Discourse Context-Aware Self-Attention](https://arxiv.org/abs/1908.04755)
- [GlossBERT: BERT for Word Sense Disambiguation with Gloss Knowledge](https://arxiv.org/abs/1908.07245) (EMNLP2019)
- [Improved Word Sense Disambiguation Using Pre-Trained Contextualized Word Representations](https://arxiv.org/abs/1910.00194)  (EMNLP2019)
- [Using BERT for Word Sense Disambiguation](https://arxiv.org/abs/1909.08358)
- [Utilizing BERT for Aspect-Based Sentiment Analysis via Constructing Auxiliary Sentence](https://arxiv.org/abs/1903.09588) (NAACL2019)
- [BERT Post-Training for Review Reading Comprehension and Aspect-based Sentiment Analysis](https://arxiv.org/abs/1904.02232) (NAACL2019)
- [Exploiting BERT for End-to-End Aspect-based Sentiment Analysis](https://arxiv.org/abs/1910.00883) (EMNLP2019 WS)
- [Adapt or Get Left Behind: Domain Adaptation through BERT Language Model Finetuning for Aspect-Target Sentiment Classification](https://arxiv.org/abs/1908.11860) 
- [An Investigation of Transfer Learning-Based Sentiment Analysis in Japanese](https://arxiv.org/abs/1905.09642) (ACL2019)
- ["Mask and Infill" : Applying Masked Language Model to Sentiment Transfer](https://arxiv.org/abs/1908.08039)
- [Neural Aspect and Opinion Term Extraction with Mined Rules as Weak Supervision](https://arxiv.org/abs/1907.03750) (ACL2019) 
- [Assessing BERT’s Syntactic Abilities](https://arxiv.org/abs/1901.05287)
- [Does BERT agree? Evaluating knowledge of structure dependence through agreement relations](https://arxiv.org/abs/1908.09892)
- [Simple BERT Models for Relation Extraction and Semantic Role Labeling](https://arxiv.org/abs/1904.05255)
- [LIMIT-BERT : Linguistic Informed Multi-Task BERT](https://arxiv.org/abs/1910.14296)
- [A Simple BERT-Based Approach for Lexical Simplification](https://arxiv.org/abs/1907.06226)
- [Multi-headed Architecture Based on BERT for Grammatical Errors Correction](https://www.aclweb.org/anthology/papers/W/W19/W19-4426/) (ACL2019 WS) 
- [KG-BERT: BERT for Knowledge Graph Completion](https://arxiv.org/abs/1909.03193)
- [Language Models as Knowledge Bases?](https://arxiv.org/abs/1909.01066) (EMNLP2019) [[github](https://github.com/facebookresearch/LAMA)]
- [BERT-Based Arabic Social Media Author Profiling](https://arxiv.org/abs/1909.04181)
- [Evaluating the Factual Consistency of Abstractive Text Summarization](https://arxiv.org/abs/1910.12840)
### Word segmentation / parsing / NER
- [BERT Meets Chinese Word Segmentation](https://arxiv.org/abs/1909.09292)
- [Toward Fast and Accurate Neural Chinese Word Segmentation with Multi-Criteria Learning](https://arxiv.org/abs/1903.04190)
- [Establishing Strong Baselines for the New Decade: Sequence Tagging, Syntactic and Semantic Parsing with BERT](https://arxiv.org/abs/1908.04943)
- [Evaluating Contextualized Embeddings on 54 Languages in POS Tagging, Lemmatization and Dependency Parsing](https://arxiv.org/abs/1908.07448) 
- [NEZHA: Neural Contextualized Representation for Chinese Language Understanding](https://arxiv.org/abs/1909.00204)
- [Deep Contextualized Word Embeddings in Transition-Based and Graph-Based Dependency Parsing -- A Tale of Two Parsers Revisited](https://arxiv.org/abs/1908.07397) (EMNLP2019)
- [Cross-Lingual BERT Transformation for Zero-Shot Dependency Parsing](https://arxiv.org/abs/1909.06775)
- [Named Entity Recognition -- Is there a glass ceiling?](https://arxiv.org/abs/1910.02403) (CoNLL2019)
- [A Unified MRC Framework for Named Entity Recognition](https://arxiv.org/abs/1910.11476)
- [Training Compact Models for Low Resource Entity Tagging using Pre-trained Language Models](https://arxiv.org/abs/1910.06294)
- [Portuguese Named Entity Recognition using BERT-CRF](https://arxiv.org/abs/1909.10649)
### Pronoun/coreference resolution
- [Resolving Gendered Ambiguous Pronouns with BERT](https://arxiv.org/abs/1906.01161) (ACL2019 WS)
- [Anonymized BERT: An Augmentation Approach to the Gendered Pronoun Resolution Challenge](https://arxiv.org/abs/1905.01780) (ACL2019 WS)
- [Gendered Pronoun Resolution using BERT and an extractive question answering formulation](https://arxiv.org/abs/1906.03695) (ACL2019 WS)
- [MSnet: A BERT-based Network for Gendered Pronoun Resolution](https://arxiv.org/abs/1908.00308) (ACL2019 WS)
- [Fill the GAP: Exploiting BERT for Pronoun Resolution](https://www.aclweb.org/anthology/papers/W/W19/W19-3815/) (ACL2019 WS)
- [On GAP Coreference Resolution Shared Task: Insights from the 3rd Place Solution](https://www.aclweb.org/anthology/W19-3816/) (ACL2019 WS)
- [Look Again at the Syntax: Relational Graph Convolutional Network for Gendered Ambiguous Pronoun Resolution](https://arxiv.org/abs/1905.08868) (ACL2019 WS)
- [BERT Masked Language Modeling for Co-reference Resolution](https://www.aclweb.org/anthology/papers/W/W19/W19-3811/) (ACL2019 WS)
- [BERT for Coreference Resolution: Baselines and Analysis](https://arxiv.org/abs/1908.09091) (EMNLP2019) [[github](https://github.com/mandarjoshi90/coref)]
- [WikiCREM: A Large Unsupervised Corpus for Coreference Resolution](https://arxiv.org/abs/1908.08025) (EMNLP2019)
- [Ellipsis and Coreference Resolution as Question Answering](https://arxiv.org/abs/1908.11141)
- [Coreference Resolution as Query-based Span Prediction](https://arxiv.org/abs/1911.01746)
### Relation extraction
- [Matching the Blanks: Distributional Similarity for Relation Learning](https://arxiv.org/abs/1906.03158) (ACL2019)
- [BERT-Based Multi-Head Selection for Joint Entity-Relation Extraction](https://arxiv.org/abs/1908.05908) (NLPCC2019)
- [Enriching Pre-trained Language Model with Entity Information for Relation Classification](https://arxiv.org/abs/1905.08284)
- [Span-based Joint Entity and Relation Extraction with Transformer Pre-training](https://arxiv.org/abs/1909.07755)
- [Fine-tune Bert for DocRED with Two-step Process](https://arxiv.org/abs/1909.11898)
- [Entity, Relation, and Event Extraction with Contextualized Span Representations](https://arxiv.org/abs/1909.03546) (EMNLP2019)
- [Fine-tuning BERT for Joint Entity and Relation Extraction in Chinese Medical Text](https://arxiv.org/abs/1908.07721)
### Text classification
- [How to Fine-Tune BERT for Text Classification?](https://arxiv.org/abs/1905.05583)
- [X-BERT: eXtreme Multi-label Text Classification with BERT](https://arxiv.org/abs/1905.02331)
- [DocBERT: BERT for Document Classification](https://arxiv.org/abs/1904.08398)
- [Enriching BERT with Knowledge Graph Embeddings for Document Classification](https://arxiv.org/abs/1909.08402)
- [Classification and Clustering of Arguments with Contextualized Word Embeddings](https://arxiv.org/abs/1906.09821) (ACL2019)
- [BERT for Evidence Retrieval and Claim Verification](https://arxiv.org/abs/1910.02655)
- [Conditional BERT Contextual Augmentation](https://arxiv.org/abs/1812.06705)
### WSC, WNLI, NLI
- [Exploring Unsupervised Pretraining and Sentence Structure Modelling for Winograd Schema Challenge](https://arxiv.org/abs/1904.09705)
- [A Surprisingly Robust Trick for the Winograd Schema Challenge](https://arxiv.org/abs/1905.06290)
- [Improving Natural Language Inference with a Pretrained Parser](https://arxiv.org/abs/1909.08217)
- [Adversarial NLI: A New Benchmark for Natural Language Understanding](https://arxiv.org/abs/1910.14599)
### Commonsense
- [HellaSwag: Can a Machine Really Finish Your Sentence?](https://arxiv.org/abs/1905.07830) (ACL2019) [[website](https://rowanzellers.com/hellaswag/)]
- [Story Ending Prediction by Transferable BERT](https://arxiv.org/abs/1905.07504) (IJCAI2019)
- [Explain Yourself! Leveraging Language Models for Commonsense Reasoning](https://arxiv.org/abs/1906.02361) (ACL2019)
- [Align, Mask and Select: A Simple Method for Incorporating Commonsense Knowledge into Language Representation Models](https://arxiv.org/abs/1908.06725)
- [Informing Unsupervised Pretraining with External Linguistic Knowledge](https://arxiv.org/abs/1909.02339)
- [Commonsense Knowledge + BERT for Level 2 Reading Comprehension Ability Test](https://arxiv.org/abs/1909.03415)
- [BIG MOOD: Relating Transformers to Explicit Commonsense Knowledge](https://arxiv.org/abs/1910.07713)
- [Do Massively Pretrained Language Models Make Better Storytellers?](https://arxiv.org/abs/1909.10705) (CoNLL2019)
### Extractive summarization
- [HIBERT: Document Level Pre-training of Hierarchical Bidirectional Transformers for Document Summarization](https://arxiv.org/abs/1905.06566) (ACL2019)
- [Deleter: Leveraging BERT to Perform Unsupervised Successive Text Compression](https://arxiv.org/abs/1909.03223)
- [Discourse-Aware Neural Extractive Model for Text Summarization](https://arxiv.org/abs/1910.14142)
### IR
- [Passage Re-ranking with BERT](https://arxiv.org/abs/1901.04085)
- [Investigating the Successes and Failures of BERT for Passage Re-Ranking](https://arxiv.org/abs/1905.01758)
- [Understanding the Behaviors of BERT in Ranking](https://arxiv.org/abs/1904.07531)
- [Document Expansion by Query Prediction](https://arxiv.org/abs/1904.08375)
- [CEDR: Contextualized Embeddings for Document Ranking](https://arxiv.org/abs/1904.07094) (SIGIR2019)
- [Deeper Text Understanding for IR with Contextual Neural Language Modeling](https://arxiv.org/abs/1905.09217) (SIGIR2019)
- [FAQ Retrieval using Query-Question Similarity and BERT-Based Query-Answer Relevance](https://arxiv.org/abs/1905.02851) (SIGIR2019)
            
## Generation
- [BERT has a Mouth, and It Must Speak: BERT as a Markov Random Field Language Model](https://arxiv.org/abs/1902.04094) (NAACL2019 WS)
- [Pretraining-Based Natural Language Generation for Text Summarization](https://arxiv.org/abs/1902.09243)
- [Text Summarization with Pretrained Encoders](https://arxiv.org/abs/1908.08345) (EMNLP2019)
- [Multi-stage Pretraining for Abstractive Summarization](https://arxiv.org/abs/1909.10599)
- [MASS: Masked Sequence to Sequence Pre-training for Language Generation](https://arxiv.org/abs/1905.02450) (ICML2019) [[github](https://github.com/microsoft/MASS)], [[github](https://github.com/microsoft/MASS/tree/master/MASS-fairseq)]
- [Unified Language Model Pre-training for Natural Language Understanding and Generation](https://arxiv.org/abs/1905.03197) (NeurIPS2019)
- [Towards Making the Most of BERT in Neural Machine Translation](https://arxiv.org/abs/1908.05672)
- [Improving Neural Machine Translation with Pre-trained Representation](https://arxiv.org/abs/1908.07688)
- [On the use of BERT for Neural Machine Translation](https://arxiv.org/abs/1909.12744)
- [Leveraging Pre-trained Checkpoints for Sequence Generation Tasks](https://arxiv.org/abs/1907.12461)
- [Mask-Predict: Parallel Decoding of Conditional Masked Language Models](https://arxiv.org/abs/1904.09324) (EMNLP2019)
- [BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension](https://arxiv.org/abs/1910.13461)
- [PLATO: Pre-trained Dialogue Generation Model with Discrete Latent Variable](https://arxiv.org/abs/1910.07931)
## Modification (multi-task, masking strategy, etc.)
- [Multi-Task Deep Neural Networks for Natural Language Understanding](https://arxiv.org/abs/1901.11504) (ACL2019)
- [BERT and PALs: Projected Attention Layers for Efficient Adaptation in Multi-Task Learning](https://arxiv.org/abs/1902.02671) (ICML2019)
- [Unifying Question Answering and Text Classification via Span Extraction](https://arxiv.org/abs/1904.09286)
- [ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/abs/1905.07129) (ACL2019)
- [ERNIE: Enhanced Representation through Knowledge Integration](https://arxiv.org/abs/1904.09223)
- [ERNIE 2.0: A Continual Pre-training Framework for Language Understanding](https://arxiv.org/abs/1907.12412)
- [SpanBERT: Improving Pre-training by Representing and Predicting Spans](https://arxiv.org/abs/1907.10529) [[github](https://github.com/facebookresearch/SpanBERT)]
- [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692) [[github](https://github.com/pytorch/fairseq/tree/master/examples/roberta)]
- [ALBERT: A Lite BERT for Self-supervised Learning of Language Representations](https://arxiv.org/abs/1909.11942)
- [KERMIT: Generative Insertion-Based Modeling for Sequences](https://arxiv.org/abs/1906.01604)
- [DisSent: Sentence Representation Learning from Explicit Discourse Relations](https://arxiv.org/abs/1710.04334) (ACL2019)
- [StructBERT: Incorporating Language Structures into Pre-training for Deep Language Understanding](https://arxiv.org/abs/1908.04577)
- [SenseBERT: Driving Some Sense into BERT](https://arxiv.org/abs/1908.05646)
- [Semantics-aware BERT for Language Understanding](https://arxiv.org/abs/1909.02209)
- [K-BERT: Enabling Language Representation with Knowledge Graph](https://arxiv.org/abs/1909.07606)
- [Knowledge Enhanced Contextual Word Representations](https://arxiv.org/abs/1909.04164) (EMNLP2019)
- [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084) (EMNLP2019)
- [Universal Text Representation from BERT: An Empirical Study](https://arxiv.org/abs/1910.07973)
- [Symmetric Regularization based BERT for Pair-wise Semantic Reasoning](https://arxiv.org/abs/1909.03405)
- [Transfer Fine-Tuning: A BERT Case Study](https://arxiv.org/abs/1909.00931) (EMNLP2019)
- [Improving Pre-Trained Multilingual Models with Vocabulary Expansion](https://arxiv.org/abs/1909.12440) (CoNLL2019)
- [ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators](https://openreview.net/forum?id=r1xMH1BtvB)
- [SesameBERT: Attention for Anywhere](https://arxiv.org/abs/1910.03176)
- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683) [[github](https://github.com/google-research/text-to-text-transfer-transformer)]
## Probe
- [A Structural Probe for Finding Syntax in Word Representations](https://aclweb.org/anthology/papers/N/N19/N19-1419/) (NAACL2019)
- [Linguistic Knowledge and Transferability of Contextual Representations](https://arxiv.org/abs/1903.08855) (NAACL2019) [[github](https://github.com/nelson-liu/contextual-repr-analysis)]
- [Probing What Different NLP Tasks Teach Machines about Function Word Comprehension](https://arxiv.org/abs/1904.11544) (*SEM2019)
- [BERT Rediscovers the Classical NLP Pipeline](https://arxiv.org/abs/1905.05950) (ACL2019)
- [Probing Neural Network Comprehension of Natural Language Arguments](https://arxiv.org/abs/1907.07355) (ACL2019)
- [Cracking the Contextual Commonsense Code: Understanding Commonsense Reasoning Aptitude of Deep Contextual Representations](https://arxiv.org/abs/1910.01157) (EMNLP2019 WS)        
## Inside BERT
- [What does BERT learn about the structure of language?](https://hal.inria.fr/hal-02131630/document) (ACL2019)
- [Open Sesame: Getting Inside BERT's Linguistic Knowledge](https://arxiv.org/abs/1906.01698) (ACL2019 WS)
- [Analyzing the Structure of Attention in a Transformer Language Model](https://arxiv.org/abs/1906.04284) (ACL2019 WS)
- [What Does BERT Look At? An Analysis of BERT's Attention](https://arxiv.org/abs/1906.04341) (ACL2019 WS)
- [Blackbox meets blackbox: Representational Similarity and Stability Analysis of Neural Language Models and Brains](https://arxiv.org/abs/1906.01539) (ACL2019 WS)
- [Inducing Syntactic Trees from BERT Representations](https://arxiv.org/abs/1906.11511) (ACL2019 WS)
- [A Multiscale Visualization of Attention in the Transformer Model](https://arxiv.org/abs/1906.05714) (ACL2019 Demo)
- [Visualizing and Measuring the Geometry of BERT](https://arxiv.org/abs/1906.02715)
- [How Contextual are Contextualized Word Representations? Comparing the Geometry of BERT, ELMo, and GPT-2 Embeddings](https://arxiv.org/abs/1909.00512) (EMNLP2019) 
- [Are Sixteen Heads Really Better than One?](https://arxiv.org/abs/1905.10650) (NeurIPS2019)
- [On the Validity of Self-Attention as Explanation in Transformer Models](https://arxiv.org/abs/1908.04211)
- [Visualizing and Understanding the Effectiveness of BERT](https://arxiv.org/abs/1908.05620) (EMNLP2019)
- [Attention Interpretability Across NLP Tasks](https://arxiv.org/abs/1909.11218)
- [Revealing the Dark Secrets of BERT](https://arxiv.org/abs/1908.08593) (EMNLP2019)
- [Investigating BERT's Knowledge of Language: Five Analysis Methods with NPIs](https://arxiv.org/abs/1909.02597) (EMNLP2019)
- [The Bottom-up Evolution of Representations in the Transformer: A Study with Machine Translation and Language Modeling Objectives](https://arxiv.org/abs/1909.01380) (EMNLP2019) 
- [Do NLP Models Know Numbers? Probing Numeracy in Embeddings](https://arxiv.org/abs/1909.07940) (EMNLP2019)
- [How Does BERT Answer Questions? A Layer-Wise Analysis of Transformer Representations](https://arxiv.org/abs/1909.04925) (CIKM2019)
- [Whatcha lookin' at? DeepLIFTing BERT's Attention in Question Answering](https://arxiv.org/abs/1910.06431)
- [What does BERT Learn from Multiple-Choice Reading Comprehension Datasets?](https://arxiv.org/abs/1910.12391)
- [exBERT: A Visual Analysis Tool to Explore Learned Representations in Transformers Models](https://arxiv.org/abs/1910.05276) [[github](https://github.com/bhoov/exbert)]
## Multi-lingual
- [Multilingual Constituency Parsing with Self-Attention and Pre-Training](https://arxiv.org/abs/1812.11760) (ACL2019)
- [Cross-lingual Language Model Pretraining](https://arxiv.org/abs/1901.07291) (NeurIPS2019) [[github](https://github.com/facebookresearch/XLM)]
- [75 Languages, 1 Model: Parsing Universal Dependencies Universally](https://arxiv.org/abs/1904.02099) (EMNLP2019) [[github](https://github.com/hyperparticle/udify)]
- [Zero-shot Dependency Parsing with Pre-trained Multilingual Sentence Representations](https://arxiv.org/abs/1910.05479) (EMNLP2019 WS)
- [Beto, Bentz, Becas: The Surprising Cross-Lingual Effectiveness of BERT](https://arxiv.org/abs/1904.09077) (EMNLP2019)
- [How multilingual is Multilingual BERT?](https://arxiv.org/abs/1906.01502) (ACL2019)
- [Is Multilingual BERT Fluent in Language Generation?](https://arxiv.org/abs/1910.03806)
- [Cross-Lingual Ability of Multilingual BERT: An Empirical Study](https://openreview.net/forum?id=HJeT3yrtDr)
- [On the Cross-lingual Transferability of Monolingual Representations](https://arxiv.org/abs/1910.11856)
- [Unsupervised Cross-lingual Representation Learning at Scale](https://arxiv.org/abs/1911.02116)
## Domain specific
- [BioBERT: a pre-trained biomedical language representation model for biomedical text mining](https://arxiv.org/abs/1901.08746)
- [Transfer Learning in Biomedical Natural Language Processing: An Evaluation of BERT and ELMo on Ten Benchmarking Datasets](https://arxiv.org/abs/1906.05474) (ACL2019 WS) 
- [BERT-based Ranking for Biomedical Entity Normalization](https://arxiv.org/abs/1908.03548)
- [PubMedQA: A Dataset for Biomedical Research Question Answering](https://arxiv.org/abs/1909.06146) (EMNLP2019)
- [Pre-trained Language Model for Biomedical Question Answering](https://arxiv.org/abs/1909.08229)
- [ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission](https://arxiv.org/abs/1904.05342)
- [Publicly Available Clinical BERT Embeddings](https://arxiv.org/abs/1904.03323) (NAACL2019 WS)
- [SciBERT: Pretrained Contextualized Embeddings for Scientific Text](https://arxiv.org/abs/1903.10676) [[github](https://github.com/allenai/scibert)]
- [PatentBERT: Patent Classification with Fine-Tuning a pre-trained BERT Model](https://arxiv.org/abs/1906.02124)
        
## Multi-modal
- [VideoBERT: A Joint Model for Video and Language Representation Learning](https://arxiv.org/abs/1904.01766) (ICCV2019)
- [ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks](https://arxiv.org/abs/1908.02265) (NeurIPS2019)
- [VisualBERT: A Simple and Performant Baseline for Vision and Language](https://arxiv.org/abs/1908.03557)
- [Selfie: Self-supervised Pretraining for Image Embedding](https://arxiv.org/abs/1906.02940)
- [Contrastive Bidirectional Transformer for Temporal Representation Learning](https://arxiv.org/abs/1906.05743)
- [M-BERT: Injecting Multimodal Information in the BERT Structure](https://arxiv.org/abs/1908.05787)
- [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://arxiv.org/abs/1908.07490) (EMNLP2019)
- [Fusion of Detected Objects in Text for Visual Question Answering](https://arxiv.org/abs/1908.05054) (EMNLP2019)
- [Unified Vision-Language Pre-Training for Image Captioning and VQA](https://arxiv.org/abs/1909.11059) [[github](https://github.com/LuoweiZhou/VLP)]
- [VL-BERT: Pre-training of Generic Visual-Linguistic Representations](https://arxiv.org/abs/1908.08530)
- [Unicoder-VL: A Universal Encoder for Vision and Language by Cross-modal Pre-training](https://arxiv.org/abs/1908.06066)
- [UNITER: Learning UNiversal Image-TExt Representations](https://arxiv.org/abs/1909.11740)
- [SpeechBERT: Cross-Modal Pre-trained Language Model for End-to-end Spoken Question Answering](https://arxiv.org/abs/1910.11559)
## Model compression
- [Distilling Task-Specific Knowledge from BERT into Simple Neural Networks](https://arxiv.org/abs/1903.12136)
- [Patient Knowledge Distillation for BERT Model Compression](https://arxiv.org/abs/1908.09355) (EMNLP2019)
- [Small and Practical BERT Models for Sequence Labeling](https://arxiv.org/abs/1909.00100) (EMNLP2019)
- [Pruning a BERT-based Question Answering Model](https://arxiv.org/abs/1910.06360)
- [TinyBERT: Distilling BERT for Natural Language Understanding](https://arxiv.org/abs/1909.10351)
- [DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter](https://arxiv.org/abs/1910.01108) (NeurIPS2019 WS) [[github](https://github.com/huggingface/transformers/tree/master/examples/distillation)]
- [Extreme Language Model Compression with Optimal Subwords and Shared Projections](https://arxiv.org/abs/1909.11687)
- [Q-BERT: Hessian Based Ultra Low Precision Quantization of BERT](https://arxiv.org/abs/1909.05840)
- [Q8BERT: Quantized 8Bit BERT](https://arxiv.org/abs/1910.06188) (NeurIPS2019 WS)
## Misc.
- [Cloze-driven Pretraining of Self-attention Networks](https://arxiv.org/abs/1903.07785)
- [Learning and Evaluating General Linguistic Intelligence](https://arxiv.org/abs/1901.11373)
- [To Tune or Not to Tune? Adapting Pretrained Representations to Diverse Tasks](https://arxiv.org/abs/1903.05987) (ACL2019 WS)
- [BERTScore: Evaluating Text Generation with BERT](https://arxiv.org/abs/1904.09675)
- [Machine Translation Evaluation with BERT Regressor](https://arxiv.org/abs/1907.12679)
- [Large Batch Optimization for Deep Learning: Training BERT in 76 minutes](https://arxiv.org/abs/1904.00962)
- [Is BERT Really Robust? Natural Language Attack on Text Classification and Entailment](https://arxiv.org/abs/1907.11932)
- [Thieves on Sesame Street! Model Extraction of BERT-based APIs](https://arxiv.org/abs/1910.12366)
- [Glyce: Glyph-vectors for Chinese Character Representations](https://arxiv.org/abs/1901.10125)
- [Back to the Future -- Sequential Alignment of Text Representations](https://arxiv.org/abs/1909.03464)
- [Improving Cuneiform Language Identification with BERT](https://www.aclweb.org/anthology/papers/W/W19/W19-1402/) (NAACL2019 WS)
- [SMILES-BERT: Large Scale Unsupervised Pre-Training for Molecular Property Prediction](https://dl.acm.org/citation.cfm?id=3342186) (ACM-BCB2019)
- [Transformers: State-of-the-art Natural Language Processing](https://arxiv.org/abs/1910.03771)
- [Evolution of transfer learning in natural language processing](https://arxiv.org/abs/1910.07370)
