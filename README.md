# JoVALE: Detecting Human Actions in Video Using Audiovisual and Language Contexts
This repository is created for the paper titled "JoVALE: Detecting Human Actions in Video Using Audiovisual and Language Contexts", which has been accepted at AAAI 2025. The code will be available soon.

## arXiv

**[JoVALE: Detecting Human Actions in Video Using Audiovisual and Language Contexts](https://arxiv.org/abs/1234.56789)**  
AAAI 2025  
Taein Son*, Soo won Seo*, Jisong Kim, Seok Hwan Lee, Jun Won Choi†  
*: Equal Contribution, †: Corresponding Author

## News

- **[2025/03]**: We will release the code of JoVALE.  
- **[2024/12]**: JoVALE is accepted at AAAI 2025. 🔥  


## JoVALE
| <img src="plot/jovale_overall.png" width="600">|
|:--:| 
| **_Figure 1. Overview of JoVALE_** |

## Abstract
Video Action Detection (VAD) involves localizing and categorizing action instances in videos. Videos inherently contain various information sources, including audio, visual cues, and surrounding scene contexts. Effectively leveraging this multi-modal information for VAD is challenging, as the model must accurately focus on action-relevant cues. In this study, we introduce a novel multi-modal VAD architecture called the Joint Actor-centric Visual, Audio, Language Encoder (JoVALE). JoVALE is the first VAD method to integrate audio and visual features with scene descriptive context derived from large image captioning models. The core principle of JoVALE is the actor-centric aggregation of audio, visual, and scene descriptive contexts, where action-related cues from each modality are identified and adaptively combined. We propose a specialized module called the Actor-centric Multi-modal Fusion Network, designed to capture the joint interactions among actors and multi-modal contexts through Transformer architecture. Our evaluation conducted on three popular VAD benchmarks, AVA, UCF101-24, and JHMDB51-21, demonstrates that incorporating multi-modal information leads to significant performance gains. JoVALE achieves state-of-the-art performances.

