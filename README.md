# A Paper List for Recommend-system PreTrained Models
This is a paper list for pretrained recommend system (recommendation) models. It also contains some related research areas.

**Keyword:** *Recommend System, pretrained models*

# Paper List

## Review
- Knowledge Transfer via Pre-training for Recommendation: A Review and Prospect, arXiv, 2020, [[paper]](https://arxiv.org/abs/2009.09226)

## Dataset

## Sequential / Session-Based Recommendation
- BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer, CIKM 2019 ,  [[paper]](https://arxiv.org/abs/1904.06690)[[code]](https://github.com/FeiSun/BERT4Rec)
- S3-Rec: Self-Supervised Learning for Sequential Recommendation with Mutual Information Maximization
, CIKM-2020 , [[paper]](https://arxiv.org/abs/2008.07873)[[code]](https://github.com/RUCAIBox/CIKM2020-S3Rec)
- Transformers4Rec: Bridging the Gap between NLP and Sequential / Session-Based Recommendation, Recsys 2021
 , [[paper]](https://dl.acm.org/doi/abs/10.1145/3460231.3474255?casa_token=b4-oEoLXZycAAAAA:khQBoMBHAS5TXADNUar92RYFH4bq68KSjk3VvD5FDJzazv3jXXfcj_LHdnREjvfUgYj-4dipepKs)[[code]](https://github.com/NVIDIA-Merlin/Transformers4Rec)
 - Towards Universal Sequence Representation Learning for Recommender Systems , KDD 2022 , [[paper]](https://arxiv.org/pdf/2206.05941.pdf)[[code]](https://github.com/RUCAIBox/UniSRec)

## User Representation Pretraining 
- Parameter-Efficient Transfer from Sequential Behaviors for User Modeling and Recommendation, SIGIR 2020, [[paper]](https://arxiv.org/pdf/2001.04253.pdf), [[code]](https://github.com/fajieyuan/sigir2020_peterrec)
- One Person, One Model, One World: Learning Continual User Representation without Forgetting, SIGIR 2021, [[paper]](https://arxiv.org/pdf/2001.04253.pdf)


## Graph Pretraining
- Semi-supervised Text Style Transfer: Cross Projection in Latent Space, EMNLP, 2019, [[paper]](https://arxiv.org/pdf/1909.11493)
- Parallel Data Augmentation for Formality Style Transfer, ACL, 2020, [[paper]](https://arxiv.org/pdf/2005.07522.pdf)
- Semi-Supervised Formality Style Transfer with Consistency Training, ACL, 2022, [[paper]](https://aclanthology.org/2022.acl-long.321.pdf), [[code]]([https://www.github](https://github.com/Aolius/semi-fst))

## Evaluation and Analysis
- Evaluating Style Transfer for Text, NAACL, 2019, [[paper1]](https://arxiv.org/pdf/1904.02295), [[paper2]](https://dspace.mit.edu/bitstream/handle/1721.1/119569/1076275047-MIT.pdf?sequence=1)
- Rethinking Text Attribute Transfer: A Lexical Analysis, INLG, 2019, [[paper]](https://arxiv.org/pdf/1909.12335), [[code]](https://github.com/FranxYao/pivot_analysis)
- Unsupervised Evaluation Metrics and Learning Criteria for Non-Parallel Textual Transfer, EMNLP Workshop on Neural Generation and Translation (WNGT), 2019, [[paper]](https://arxiv.org/pdf/1810.11878)
- The Daunting Task of Real-World Textual Style Transfer Auto-Evaluation, WNGT, 2019, [[paper]](https://arxiv.org/pdf/1910.03747)
- Style-transfer and Paraphrase: Looking for a Sensible Semantic Similarity Metric, Arxiv, 2020, [[paper]](https://arxiv.org/pdf/2004.05001.pdf)
- What is wrong with style transfer for texts? Arxiv, [[paper]](https://arxiv.org/pdf/1808.04365)
- Style versus Content: A distinction without a (learnable) difference?, COLING 2020,	[[paper]](https://www.aclweb.org/anthology/2020.coling-main.197.pdf)

## Stylistic Related Papers
- Controlling Politeness in Neural Machine Translation via Side Constraints, NAACL 2016, [[paper]](https://www.aclweb.org/anthology/N16-1005.pdf)
- A Study of Style in Machine Translation: Controlling the Formality of Machine Translation Output, EMNLP 2017, [[paper]](https://www.aclweb.org/anthology/D17-1299.pdf)
- Controlling Linguistic Style Aspects in Neural Language Generation, EMNLP-2017 Workshop, [[paper]](https://arxiv.org/pdf/1707.02633)
- Is writing style predictive of scientific fraud?, EMNLP-2017 Workshop, [[paper]](http://www.aclweb.org/anthology/W17-4905)
- Incorporating Pseudo-Parallel Data for Quantifiable Sequence Editing, EMNLP-2018, [[paper]](https://arxiv.org/pdf/1804.07007)
- Polite Dialogue Generation Without Parallel Data, TACL, [[paper]](https://arxiv.org/pdf/1805.03162)
- Adversarial Decomposition of Text Representation, Arxiv, [[paper]](https://arxiv.org/pdf/1808.09042)
- Unsupervised Stylish Image Description Generation via Domain Layer Norm, AAAI 2019, [[paper]](https://arxiv.org/pdf/1809.06214)
- Transfer Learning for Style-Specific Text Generation, UNK, 2018, [[paper]](https://nips2018creativity.github.io/doc/Transfer%20Learning%20for%20Style-Specific%20Text%20Generation.pdf)
- Generating lyrics with variational autoencoder and multi-modal artist embeddings, Arxiv, 2018, [[paper]](https://arxiv.org/pdf/1812.08318)
- Generating Sentences by Editing Prototypes, TACL, 2018, [[paper]](https://www.aclweb.org/anthology/Q18-1031/)
- ALTER: Auxiliary Text Rewriting Tool for Natural Language Generation, EMNLP, 2019, [[paper]](https://arxiv.org/pdf/1909.06564)
- Stylized Text Generation Using Wasserstein Autoencoders with a Mixture of Gaussian Prior, Arxiv, 2019, [[paper]](https://arxiv.org/pdf/1911.03828)
- Adapting Language Models for Non-Parallel Author-Stylized Rewriting, AAAI, 2020 [[paper]](https://arxiv.org/pdf/1909.09962)
- Structuring Latent Spaces for Stylized Response Generation, EMNLP, 2019, [[paper]](https://arxiv.org/pdf/1909.05361)
- Complementary Auxiliary Classifiers for Label-Conditional Text Generation, AAAI, 2020, [[paper]](http://people.ee.duke.edu/~lcarin/AAAI_LiY_6828.pdf), [[code]](https://github.com/s1155026040/CARA)
- Hooks in the Headline: Learning to Generate Headlines with Controlled Styles, ACL, 2020, [[paper]](https://arxiv.org/pdf/2004.01980.pdf)
- Exploring Contextual Word-level Style Relevance for Unsupervised Style Transfer, ACL, 2020, [[paper]](https://arxiv.org/pdf/2005.02049.pdf)
- Parallel Data Augmentation for Formality Style Transfer, ACL, 2020, [[paper]](https://arxiv.org/pdf/2005.07522.pdf)
- Politeness Transfer: A Tag and Generate Approach, ACL, 2020, [[paper]](https://arxiv.org/pdf/2004.14257.pdf)
- Towards A Friendly Online Community: An Unsupervised Style Transfer Framework for Profanity Redaction, COLING 2020, [[paper]](https://arxiv.org/pdf/2011.00403.pdf)
- Generating similes effortlessly like a Pro: A Style Transfer Approach for Simile Generation, EMNLP 2020, [[paper]](https://arxiv.org/pdf/2009.08942.pdf)
- PowerTransformer: Unsupervised Controllable Revision for Biased Language Correction, EMNLP 2020, [[paper]](https://www.aclweb.org/anthology/2020.emnlp-main.602.pdf)

## Controlled Text Generation (Similar, but not exactly style transfer)
- Toward Controlled Generation of Text, ICML 2017. [[paper]](https://arxiv.org/pdf/1703.00955.pdf) 
- CTRL: A Conditional Transformer Language Model for Controllable Generation, arXiv 2019. [[paper]](https://arxiv.org/pdf/1909.05858.pdf)
- Defending Against Neural Fake News, NeurIPS 2019. (about conditional generation of neural fake news) [[paper]](https://arxiv.org/pdf/1905.12616.pdf)
- Plug and Play Language Models: A Simple Approach to Controlled Text Generation, ICLR 2020. [[paper]](https://openreview.net/pdf?id=H1edEyBKDS)
- COCON: A Self-Supervised Approach for Controlled Text Generation, ICLR 2021. [[paper]](https://openreview.net/pdf?id=VD_ozqvBy4W)

# Unsupervised Seq2Seq
- Unsupervised neural machine translation, 2017. [[paper]](https://arxiv.org/pdf/1710.11041.pdf)


# Workshop and Tutorial
- Stylistic Variation, EMNLP-2017, [[link]](https://sites.google.com/site/workshoponstylisticvariation/)
- Stylistic Variation, NAACL-HLT-2018, [[link]](https://sites.google.com/view/2ndstylisticvariation/home)
- Stylized Text Generation, ACL-2020, [[link]](https://sites.google.com/view/2020-stylized-text-generation/tutorial) [[video-part1]](https://vimeo.com/436479481) [[video-part2]](https://www.youtube.com/watch?v=qSbqVjM-Vik)

# Copyright 
By Xiangyang Li (xiangyangli@pku.edu.cn) from Peking University.  
**Welcome to open an issue or make a pull request!**
