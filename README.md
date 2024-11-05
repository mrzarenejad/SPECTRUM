# SPECTRUM

repository for **SPECTRUM : Semantic Processing and Emotion-informed video-Captioning Through Retrieval and Understanding Modalities** paper

We provide some details about our paper in our research paper:

[https://arxiv.org/abs/1912.04870](http://arxiv.org/abs/2411.01975)

---------------------------------

## Code

We will release our Framework for further research soon.

------------------------

## Description

Capturing a video's meaning and critical concepts by analyzing the subtle details is a fundamental yet challenging task in video captioning. Identifying the dominant emotional tone in a video significantly enhances the perception of its context. Despite a strong emphasis on video captioning, existing models often need to adequately address emotional themes, resulting in suboptimal captioning results. To address these limitations, this paper proposes a novel Semantic Processing and Emotion-informed video-Captioning Through Retrieval and Understanding Modalities (SPECTRUM) framework to empower the generation of emotionally and semantically credible captions. Leveraging our pioneering structure, SPECTRUM discerns multimodal semantics and emotional themes using Visual Text Attribute Investigation (VTAI) and determines the orientation of descriptive captions through a Holistic Concept-Oriented Theme (HCOT), expressing emotionally-informed and field-acquainted references. They exploit video-to-text retrieval capabilities and the multifaceted nature of video content to estimate the emotional probabilities of candidate captions. Then, the dominant theme of the video is determined by appropriately weighting embedded attribute vectors and applying coarse- and fine-grained emotional concepts, which define the video's contextual alignment. Furthermore, using two loss functions, SPECTRUM is optimized to integrate emotional information and minimize prediction errors. Extensive experiments on the **EmVidCap**, **MSVD**, and **MSRVTT** video captioning datasets demonstrate that **our model significantly surpasses state-of-the-art methods**. Quantitative and qualitative evaluations highlight the model's ability to accurately capture and convey video emotions and multimodal attributes.

[!overalview](./Fig_1.jpg)

## main Framework


[!mainframework](./Fig_2.jpg)

