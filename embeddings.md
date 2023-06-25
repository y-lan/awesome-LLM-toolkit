
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
- [Text2vec](https://github.com/shibing624/text2vec): Optimized Cosine Similarty Loss $\log \left(1+\sum_{(i, j) \in \Omega_{p o s},(k, l) \in \Omega_{\text {neg }}} e^{\lambda\left(\cos \left(u_k, u_l\right)-\cos \left(u_i, u_j\right)\right)}\right)$ ([CoSENT](https://github.com/bojone/CoSENT)) + CN
- (2022, MS) [SimLM](https://github.com/microsoft/unilm/tree/master/simlm): [Paper](https://arxiv.org/abs/2207.02578)https://arxiv.org/abs/2207.02578
- (2022, MS) [E5](https://github.com/microsoft/unilm/tree/master/e5) & [Multilingual-E5](https://huggingface.co/intfloat/multilingual-e5-base): [paper](https://arxiv.org/pdf/2212.03533.pdf), MiniLM + [CCPairs](https://github.com/y-lan/awesome-LLM-toolkit/blob/main/assets/CCPairs.png) + in-batch negatives (batch-size: 32768), InfoNCE contrastive loss
- others
  - (2022) [ColBERTv2](https://github.com/stanford-futuredata/ColBERT): token-wise late interaction, [paper](https://aclanthology.org/2022.naacl-main.272/)

## Multi-modal Models

- [ONE-PEACE](https://github.com/OFA-Sys/ONE-PEACE): general representation model across video/audio/language, [paper](https://arxiv.org/abs/2305.11172)


## Datasets

- [MS-MARCO](https://huggingface.co/datasets/ms_marco)
- [mMARCO](https://huggingface.co/datasets/unicamp-dl/mmarco/viewer/japanese/train), [Github](https://github.com/unicamp-dl/mMARCO)
- [STSb Multi MT](https://huggingface.co/datasets/stsb_multi_mt)
  - [jSTS](https://github.com/yahoojapan/JGLUE/tree/main/datasets/jsts-v1.1)
- NLIs
  - [SNLI (Stanford Natural Language Inference Corpus)](https://huggingface.co/datasets/snli)
  - [MNLI](https://huggingface.co/datasets/multi_nli)
  - [XNLI](https://huggingface.co/datasets/xnli)
  - [multilingual-NLI-26lang-2mil7](https://huggingface.co/datasets/MoritzLaurer/multilingual-NLI-26lang-2mil7)
- [NQ (Natural_Questions)](https://huggingface.co/datasets/natural_questions)
- [Cohere Wikipedia](https://txt.cohere.com/embedding-archives-wikipedia/)

## Benchmarks
- [BEIR](https://github.com/beir-cellar/beir)
- [MTEB](https://github.com/embeddings-benchmark/mteb): [Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)

