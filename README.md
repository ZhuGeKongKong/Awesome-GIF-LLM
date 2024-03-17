# Awesome-Clip-LLM
## Datasets 
### GIF

|Name|Paper|Number Videos|Number Sens| Ave Duration|
| :----:| :-------------| :----: |:----:| :----: |
|TGIF|[TGIF: A New Dataset and Benchmark on Animated GIF Description](https://arxiv.org/pdf/1604.02748v2.pdf)|100k|120k Des|3.1s|
|TGIF-QA|[TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering](https://arxiv.org/pdf/1704.04497.pdf)|72k|165k QAs|-|

### Video
|Name|Paper|Number Videos|Number Sens| Ave Duration|
| :----:| :-------------| :----: |:----: | :----: |
|MSR-VTT|[MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)|10k (200k clips)|200k Des|14s|
|MSVD|[Collecting Highly Parallel Data for Paraphrase Evaluation](https://aclanthology.org/P11-1020.pdf)|2k|85k Des|4-10s|

## Methods

### Pre-trained 
|Name|Paper|Code|Comments|
|:----:|:-------------|:----:|:----|
|LanguageBind|[LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment](https://arxiv.org/pdf/2310.01852.pdf)|[Link](https://github.com/PKU-YuanGroup/LanguageBind)![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LanguageBind.svg?style=social&label=Star)|OpenCLIP|
|BLIP-2|[BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/pdf/2301.12597.pdf)|[Link](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)|ViT+Q-former+OPT|

### Instruction-tuned
|Name|Paper|Code|Comments|
|:----:|:-------------|:----:|:----|
|Video-LLaMA|[Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/pdf/2306.02858.pdf)|[Link](https://github.com/DAMO-NLP-SG/Video-LLaMA)![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)|Video Q-Former+Audio Q-Former+Vicuna|
|Video-LLaVA|[Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/pdf/2311.10122.pdf)|[Link](https://github.com/PKU-YuanGroup/Video-LLaVA)![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Video-LLaVA.svg?style=social&label=Star)|LanguageBind+Vicuna|

