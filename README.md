# A Paper List for Recommend-system PreTrained Models

<font size=6><center><big><b> [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) </b></big></center></font>

This is a paper list for pretrained recommend System (recommendation) models. It also contains some related research areas such as large language model for recommendation.

**Keyword:** *Recommend System, pretrained models, large language model*

**Welcome to open an issue or make a pull request!**
# Paper List

## Review
- Knowledge Transfer via Pre-training for Recommendation: A Review and Prospect, arXiv, 2020, [[paper]](https://arxiv.org/abs/2009.09226)
- Self-Supervised Learning for Recommender Systems: A Survey ,arxiv 2022, [[paper]](https://arxiv.org/pdf/2203.15876.pdf)
- Pre-train, Prompt and Recommendation: A Comprehensive Survey of Language Modelling Paradigm Adaptations in Recommender Systems, arxiv 2022, [[paper]](https://arxiv.org/abs/2302.03735)
- How Can Recommender Systems Benefit from Large Language Models: A Survey, arxiv 2023, [[paper]](http://arxiv.org/abs/2306.05817v1) [[code]](https://github.com/CHIANGEL/Awesome-LLM-for-RecSys)
## Dataset
- Yelp[[link]](https://www.yelp.com/dataset)
- Petdata[[link]](https://drive.google.com/file/d/1OcvbBJN0jlPTEjE0lvcDfXRkzOjepMXH/view)
- M5Product: Self-harmonized Contrastive Learning for E-commercial Multi-modal Pretraining, CVPR 2022 [[paper]](https://arxiv.org/pdf/2109.04275.pdf)
- Tenrec: A Large-scale Multipurpose Benchmark Dataset for Recommender Systems, NeurIPS 2022  [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/4ad4fc1528374422dd7a69dea9e72948-Paper-Datasets_and_Benchmarks.pdf)
- PixelRec:  A Image Dataset for Benchmarking Recommender Systems with Raw Pixels [[link]](https://github.com/westlake-repl/PixelRec),arxiv 2023,[[paper]](https://arxiv.org/abs/2309.06789)
## Empirical Study
- Where to Go Next for Recommender Systems? ID-vs. Modality-based recommender models revisited, SIGIR 2023, [[paper]](https://arxiv.org/pdf/2303.13835.pdf)
- Generative Recommendation: Towards Next-generation Recommender Paradigm, arxiv 2023, [[paper]](https://arxiv.org/abs/2304.03879) 
- Exploring Adapter-based Transfer Learning for Recommender Systems: Empirical Studies and Practical Insights,arxiv 2023, [[paper]](https://arxiv.org/pdf/2305.15036.pdf) [[code]](https://github.com/westlake-repl/IDvs.MoRec)
## Sequential / Session-Based Recommendation
- BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer, CIKM 2019 ,  [[paper]](https://arxiv.org/abs/1904.06690)[[code]](https://github.com/FeiSun/BERT4Rec)
- S3-Rec: Self-Supervised Learning for Sequential Recommendation with Mutual Information Maximization
, CIKM-2020 , [[paper]](https://arxiv.org/abs/2008.07873)[[code]](https://github.com/RUCAIBox/CIKM2020-S3Rec)
- Transformers4Rec: Bridging the Gap between NLP and Sequential / Session-Based Recommendation, Recsys 2021
 , [[paper]](https://dl.acm.org/doi/abs/10.1145/3460231.3474255?casa_token=b4-oEoLXZycAAAAA:khQBoMBHAS5TXADNUar92RYFH4bq68KSjk3VvD5FDJzazv3jXXfcj_LHdnREjvfUgYj-4dipepKs)[[code]](https://github.com/NVIDIA-Merlin/Transformers4Rec)
 - Towards Universal Sequence Representation Learning for Recommender Systems , KDD 2022 , [[paper]](https://arxiv.org/pdf/2206.05941.pdf)[[code]](https://github.com/RUCAIBox/UniSRec)
- Learning Vector-Quantized Item Representation for Transferable Sequential Recommenders, WWW 2023, [[paper]](https://arxiv.org/abs/2210.12316) [[code]](https://github.com/RUCAIBox/VQ-Rec)
- MISSRec: Pre-training and Transferring Multi-modal Interest-aware Sequence Representation for Recommendation, ACM MM 2023,[[paper]](https://arxiv.org/abs/2308.11175) [[code]](https://github.com/gimpong/MM23-MISSRec)

## User Representation Pretraining 
- Parameter-Efficient Transfer from Sequential Behaviors for User Modeling and Recommendation, SIGIR 2020 , [[paper]](https://arxiv.org/pdf/2001.04253.pdf), [[code]](https://github.com/fajieyuan/sigir2020_peterrec)
- UPRec: User-Aware Pre-training for Recommender Systems ，submitted TKDE in 2021 , [[paper]](https://arxiv.org/abs/2102.10989)
- U-BERT: Pre-training user representations for improved recommendation, AAAI 2021, [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16557)
- UserBERT: Self-supervised User Representation Learning ,  arxiv 2021 , [[paper]](https://arxiv.org/abs/2109.01274)
- One4all User Representation for Recommender Systems in E-commerce , arxiv 2021 , [[paper]](https://arxiv.org/abs/2106.00573)
- One Person, One Model, One World: Learning Continual User Representation without Forgetting, SIGIR 2021 , [[paper]](https://arxiv.org/pdf/2001.04253.pdf)
- Scaling Law for Recommendation Models: Towards General-purpose User Representations , AAAI 2023 , [[paper]](https://arxiv.org/abs/2111.11294)

## Two Tower Pretraining
- Self-supervised Learning for Large-scale Item Recommendations , CIKM 2021 , [[paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3481952)
- TransRec: Learning Transferable Recommendation from Mixture-of-Modality Feedback , arxiv 2022 , [[paper]](https://arxiv.org/abs/2206.06190)
- IntTower: the Next Generation of Two-Tower Model for Pre-Ranking System, CIKM 2022 , [[paper]](https://arxiv.org/abs/2210.09890)[[code]](https://github.com/archersama/inttower)

## Language Models as Recommenddation Models & Prompt Learning
- LLMRec: Large Language Models with Graph Augmentation for Recommendation , WSDM 2024 , [[paper]](https://arxiv.org/pdf/2311.00423.pdf)
- Language Models as Recommender Systems: Evaluations and Limitations , NeurIPS 2021 Workshop ICBINB , [[paper]](https://openreview.net/pdf?id=hFx3fY7-m9b)
- CTR-BERT: Cost-effective knowledge distillation for billion-parameter teacher models,  [[paper]](https://neurips2021-nlp.github.io/papers/20/CameraReady/camera_ready_final.pdf)
- Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5) , Recsys 2022 , [[paper]](https://arxiv.org/abs/2203.13366))
- M6-Rec: Generative Pretrained Language Models are Open-Ended Recommender Systems ,arxiv 2022 , [[paper]](https://arxiv.org/pdf/2205.08084.pdf)
- PTab: Using the Pre-trained Language Model for Modeling Tabular Data, arxiv 2022, [[paper]](https://arxiv.org/abs/2209.08060)
- Prompt Learning for News Recommendation, SIGIR 2023, [[paper]](https://arxiv.org/abs/2304.05263)
 ### Large Language Models for Recommendation
- Is ChatGPT a Good Recommender A Preliminary Study, arxiv 2023, [[paper]](https://arxiv.org/pdf/2304.10149.pdf)
- Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent, arxiv 2023, [[paper]](https://arxiv.org/pdf/2304.09542.pdf)
- Uncovering ChatGPT’s Capabilities in Recommender Systems, arxiv 2023, [[paper]](https://arxiv.org/pdf/2305.02182.pdf)[[code]](https://github.com/rainym00d/LLM4RS)
- Sparks of Artificial General Recommender (AGR): Early Experiments with ChatGPT, arxiv 2023, [[paper]](https://arxiv.org/pdf/2305.04518.pdf)
- Is ChatGPT Fair for Recommendation? Evaluating Fairness in Large Language Model Recommendation, arxiv 2023,[[paper]](https://arxiv.org/pdf/2305.07609.pdf)
[[code]](https://github.com/jizhi-zhang/FaiRLLM)
- TALLRec: An Effective and Efficient Tuning Framework to Align Large  Language Model with Recommendation, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.00447v1)
- PALR: Personalization Aware LLMs for Recommendation, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.07622v1)
- Large Language Models are Zero-Shot Rankers for Recommender Systems, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.08845v1)
- Recommendation as Instruction Following: A Large Language Model  Empowered Recommendation Approach, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.07001v1)
- Leveraging Large Language Models in Conversational Recommender Systems, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.07961v2)
- Privacy-Preserving Recommender Systems with Synthetic Query Generation  using Differentially Private Large Language Models, arxiv 2023, [[paper]](http://arxiv.org/abs/2305.05973v1)
- Exploring the Upper Limits of Text-Based Collaborative Filtering Using Large Language Models: Discoveries and Insights, arxiv 2023, [[paper]](https://arxiv.org/pdf/2305.11700.pdf)
- A Bi-Step Grounding Paradigm for Large Language Models in Recommendation Systems,arxiv 2023, [[paper]](https://arxiv.org/abs/2308.08434)
- CTRL: Connect Tabular and Language Model for CTR Prediction, arxiv 2023,[[paper]](https://arxiv.org/abs/2306.02841)




## Graph Pretraining
- Curriculum Pre-Training Heterogeneous Subgraph Transformer for Top-N Recommendation , arxiv 2021 ,[[paper]](https://arxiv.org/abs/2106.06722)
- Contrastive Pre-Training of GNNs on Heterogeneous Graphs , CIKM 2021 , [[paper]](https://yuanfulu.github.io/publication/CIKM-CPT.pdf)
- Self-supervised Graph Learning for Recommendation , SIGIR 2021 , [[paper]](https://arxiv.org/pdf/2010.10783.pdf)
- Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation , AAAI 2021 , [[paper]](https://arxiv.org/pdf/2012.06852.pdf)
# Workshop and Tutorial
- [International Workshop on Deep Learning Practice for High-Dimensional Sparse Data with RecSys](https://dlp4rec.github.io/)


# Related hub
 https://github.com/CHIANGEL/Awesome-LLM-for-RecSys

# Copyright 
By Xiangyang Li (xiangyangli@pku.edu.cn) from Peking University.  
```
@misc{rs-pretrain-papers,
  author = {Xiangyang Li},
  title = {awesome-recommend-system-pretraining-papers},
  year = {2022},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/archersama/awesome-recommend-system-pretraining-papers/}}
}
```
