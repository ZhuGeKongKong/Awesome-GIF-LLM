# Awesome-Clip-LLM
 Part of the information comes from [Awesome-LLMs-for-Video-Understanding](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding/tree/main).
## Datasets 
### GIF

|Name|Paper|Number Videos|Number Sens| Ave Duration|Comments|
| :----:| :-------------| :----: |:----:| :----: |:---|
|TGIF|[TGIF: A New Dataset and Benchmark on Animated GIF Description](https://arxiv.org/pdf/1604.02748v2.pdf)|100k|120k Des|3.1s|Captioning|
|TGIF-QA|[TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering](https://arxiv.org/pdf/1704.04497.pdf)|72k|165k QAs|-|VQAs|
|Ani-GIFs|[Ani-GIFs: A benchmark dataset for domain generalization of action recognition from GIFs](https://www.frontiersin.org/articles/10.3389/fcomp.2022.876846/full)|17k|536 cls|2.1s|Action Recognitaion & Animated GIFs|
|Vid2GIF|[Video2gif: automatic generation of animated gifs from video](https://arxiv.org/pdf/1605.04850.pdf)|100k|-|5.8s|Generating GIF from Video|
|GifGIF|[Predicting viewer perceived emotions in animated GIFs](https://www.ee.columbia.edu/ln/dvmm/publications/14/grand14-jou.pdf)|3.8k|17 emotions|<=303 frames (15s)|emotions recg|
|Gifgif+|[Gifgif+: Collecting emotional animated gifs with clustered multi-task learning](https://ieeexplore.ieee.org/document/8273647)|23k|17 emotions|-|emotions recg|



### Video
|Name|Paper|Number Videos|Number Sens| Ave Duration|Comments|
| :----:| :-------------| :----: |:----: | :----: |:---|
|MSR-VTT|[MSR-VTT: A Large Video Description Dataset for Bridging Video and Language](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)|10k (200k clips)|200k Des|14s|Captiong|
|MSVD|[Collecting Highly Parallel Data for Paraphrase Evaluation](https://aclanthology.org/P11-1020.pdf)|2k|85k Des|4-10s|Captioning|
|ActivityNet|[ActivityNet: A Large-Scale Video Benchmark for Human Activity Understanding](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf)|27k (849h)|203 cls|109 s|activity reg|

## Methods

### Pre-trained 
|Name|Paper|Code|Comments|
|:----:|:-------------|:----:|:----|
|LanguageBind|[LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment](https://arxiv.org/pdf/2310.01852.pdf)|[Link](https://github.com/PKU-YuanGroup/LanguageBind)![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LanguageBind.svg?style=social&label=Star)|OpenCLIP|
|BLIP-2|[BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/pdf/2301.12597.pdf)|[Link](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)|ViT+Q-former+OPT/FlanT5|

### Instruction-tuned for Lanuage Task
|Name|Paper|Code|Video Datasets|Comments|
|:----:|:-------------|:---|:----:|:----|
|Video-LLaMA|[Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/pdf/2306.02858.pdf)|[Link](https://github.com/DAMO-NLP-SG/Video-LLaMA)![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)| Pertraining: Webvid+CC3M<br>Finetune: Video-Chat+LLaVa+MiniGPT4-4|BLIP2+Q-Former+Vicuna/LLaMa |
|Video-LLaVA|[Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/pdf/2311.10122.pdf)|[Link](https://github.com/PKU-YuanGroup/Video-LLaVA)![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Video-LLaVA.svg?style=social&label=Star)| Pertraining: WebVid+CC3M<br>Finetune:Video-ChatGPT+LLaVa|LanguageBind+Vicuna|

