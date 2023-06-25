[MTEB leaderboard](https://huggingface.co/spaces/mteb/leaderboard)

## Text Models

- (2020, Meta) [xlm-roberta](https://github.com/facebookresearch/fairseq/tree/main/examples/xlmr): multilingual(100 languages), pre-trained on CommonCrawl
- (2021) [DeCLUTR](https://github.com/JohnGiorgi/DeCLUTR): [paper](https://arxiv.org/abs/2006.03659), Contrastive Learning
- (2021) [SimCSE](https://github.com/princeton-nlp/SimCSE): [paper](https://arxiv.org/pdf/2104.08821.pdf): dropout masks for constructing positive samples
- [sentence transformers](https://www.sbert.net/docs/pretrained_models.html#model-overview): [fine-tune](https://www.sbert.net/docs/training/overview.html)
  - [sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2](https://huggingface.co/sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2)
  - [GPL: Generative Pseudo Labeling for Unsupervised Domain Adaptation of Dense Retrieval](https://arxiv.org/abs/2112.07577) & [Domain Adaptation
](https://www.sbert.net/examples/domain_adaptation/README.html#adaptive-pre-training)
  - [mmarco-mMiniLMv2-L12-H384-v1](https://huggingface.co/cross-encoder/mmarco-mMiniLMv2-L12-H384-v1): multilingual cross-encoder on MMARCO dataset
- (2022) [Onstructor](https://instructor-embedding.github.io/): EN, 768D, [Paper](https://arxiv.org/abs/2212.09741), use one-sentence instruction to generate task-specific embedding
- (2022, OpenAI) text-embedding-ada-002: [Paper](https://arxiv.org/abs/2201.10005), GPT + DeCLUTR
- (2022, MS) [E5](https://github.com/microsoft/unilm/tree/master/e5) & [Multilingual-E5](https://huggingface.co/intfloat/multilingual-e5-base): [paper](https://arxiv.org/pdf/2212.03533.pdf)
- [Text2vec](https://github.com/shibing624/text2vec): Optimized Cosine Similarty Loss $\log \left(1+\sum_{(i, j) \in \Omega_{p o s},(k, l) \in \Omega_{\text {neg }}} e^{\lambda\left(\cos \left(u_k, u_l\right)-\cos \left(u_i, u_j\right)\right)}\right)$ + CN
- [SimLM](https://github.com/microsoft/unilm/tree/master/simlm)
- others
  - (2022) [ColBERTv2](https://github.com/stanford-futuredata/ColBERT): token-wise late interaction, [paper](https://aclanthology.org/2022.naacl-main.272/)

## Multi-modal Models

- [ONE-PEACE](https://github.com/OFA-Sys/ONE-PEACE): general representation model across video/audio/language, [paper](https://arxiv.org/abs/2305.11172)


## Datasets

- [Cohere Wikipedia](https://txt.cohere.com/embedding-archives-wikipedia/)
- [unicamp-dl/mmarco](https://huggingface.co/datasets/unicamp-dl/mmarco/viewer/japanese/train), [Github](https://github.com/unicamp-dl/mMARCO)
- [STSb Multi MT](https://huggingface.co/datasets/stsb_multi_mt)
  - [jSTS](https://github.com/yahoojapan/JGLUE/tree/main/datasets/jsts-v1.1)
