# awesome-LLM-toolkit
Collect information about all the necessary tools and dataset required for building a high-quality customized LLM

## Core Model/Training Techniques

- FlashAttention: [Github](https://github.com/HazyResearch/flash-attention), [Paper](https://arxiv.org/abs/2205.14135)
- ALiBi: [Paper](https://arxiv.org/abs/2108.12409)
- Faster Inference
   - FasterTransformer: [Github](https://github.com/NVIDIA/FasterTransformer)
   - 
- bitsandbytes: 8-bit optimizer, [Github](https://github.com/TimDettmers/bitsandbytes)
- PEFT: [Github](https://github.com/huggingface/peft), [LoRA Paper](https://arxiv.org/abs/2106.09685)
  - [QLoRA](https://github.com/artidoro/qlora): GPU memory efficient fine-tuning by training LoRA on quantized models
- [BLIP-2/LAVIS](https://github.com/salesforce/LAVIS): Connect image encoder with LLM to enable multi-modal, [Paper](https://arxiv.org/pdf/2212.10846.pdf)
- RLHF frameworks: [DeepSpeed Chat](https://github.com/microsoft/DeepSpeed/tree/master/blogs/deepspeed-chat), [trlx](https://github.com/CarperAI/trlx), [Colossal AI](https://github.com/hpcaitech/ColossalAI)

## Data

| Name | Type | Language | License | Note |
| -------- | -------- | -------- | -------- | -------- |
| [mc4](https://huggingface.co/datasets/mc4) | Raw Text | multilingual (100+) | ODC-By | | [Paper](https://arxiv.org/pdf/1910.10683.pdf) |
| [bloom](https://huggingface.co/datasets/sil-ai/bloom-lm) | Raw Text | multilingual (46) | Depend on data| | 
| [wmt22](https://www.statmt.org/wmt22E/translation-task.html) | translation | multilingual | Depend on data | | 
| [RedPajama](https://www.together.xyz/blog/redpajama) | Raw Text | mostly EN | Apache 2.0 | |
| [WuDaoCorpora](https://www.sciencedirect.com/science/article/pii/S2666651021000152) | Raw Text | zh-CN | | 5TB |
| [The Stack](https://huggingface.co/datasets/bigcode/the-stack-dedup) | Code | 
| [openwebtext](https://huggingface.co/datasets/openwebtext) | Raw Text | EN | CC0 1.0 | used to train GPT-2 | 
| [self-instruct-seed](https://huggingface.co/datasets/HuggingFaceH4/self-instruct-seed) | Instruction | EN | Apache 2.0 |  |
| [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json) | Instruction | EN | CC BY-NC 4.0 | |
| [Alpaca Cleaned](https://github.com/gururise/AlpacaDataCleaned) | Instruction | EN | CC BY-NC 4.0 | |
| [ShareGPT Vicuna](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) | Instruction | EN | 🤐 | Collected from [sharegpt](https://sharegpt.com/)|
| [evol_instruct_70k](https://huggingface.co/datasets/victor123/evol_instruct_70k) | Instruction | EN | CC BY-NC ? | [Generated by Evol-Instruct](https://github.com/nlpxucan/WizardLM#training-data)
| [HH-RLHF](https://huggingface.co/datasets/Anthropic/hh-rlhf) | RLHF | EN |  MIT | |
| [databricks-dolly-15k](https://huggingface.co/datasets/databricks/databricks-dolly-15k) | Instruction | EN | CC BY-SA 3.0 | |
| [GuanacoDataset](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset) | Instruction | EN, zh-CN, zh-TW, JA, DE | GPL 3.0 | desgined for multilingual |
| [dolly_hhrlhf](https://huggingface.co/datasets/mosaicml/dolly_hhrlhf) | Instruction | EN | CC BY-SA 3.0 | MosaicAI's filtered version of HH-RLHF and databricks-dolly-15k |  
| [HC3](https://huggingface.co/datasets/Hello-SimpleAI/HC3), [Chinese](https://huggingface.co/datasets/Hello-SimpleAI/HC3-Chinese) | RLHF | EN, CN | CC BY-SA 3.0 | [Paper](https://arxiv.org/abs/2301.07597), [Github](https://github.com/Hello-SimpleAI/chatgpt-comparison-detection) | 
| [Lamini](https://github.com/lamini-ai/lamini#data-release)   | Instruction   | EN   |  CC-BY-4.0  |  |
| [the_pile_books3](https://huggingface.co/datasets/the_pile_books3) | Raw Text | mostly EN | MIT | part of [the pile](https://github.com/EleutherAI/the-pile)|
| [CoNaLa](https://huggingface.co/datasets/neulab/conala) | Coding | EN | MIT | |
| [GPTeacher](https://github.com/teknium1/GPTeacher) | Instruction | EN | MIT | Generated by GPT-4 |
| [Alpaca-CoT](https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/) | Instruction | EN, CN | Apache 2.0 | Collection of instruction datasets|
| [OpenAssistant/oasst1](https://huggingface.co/datasets/OpenAssistant/oasst1) | Conversation | multilingual | Apache 2.0 | [Paper](https://arxiv.org/abs/2304.07327), Collected from [Open Assistant](https://open-assistant.io/) | 

### Others
- [Stack Exchange](https://stackexchange.com/sites)
- [wikihow](https://www.wikihow.com/)
- [Pushshift Reddit API](https://reddit-api.readthedocs.io/en/latest/)
- [awesome-legal-nlp](https://github.com/maastrichtlawtech/awesome-legal-nlp)

## Evaluation
- [Perplexity & NLL](https://huggingface.co/docs/transformers/perplexity)
- [Vicuna Evaluation(Using GPT-4)](https://github.com/lm-sys/FastChat/tree/main/fastchat/eval)

## Community


## Others
- [LLM Arena](https://arena.lmsys.org/)
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui)
- [LlamaChat](https://github.com/alexrozanski/LlamaChat) MacOS Client
- [llama.cpp](https://github.com/ggerganov/llama.cpp) 
