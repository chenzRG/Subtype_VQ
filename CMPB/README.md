# [Learning Vector Quantized Representation for Cancer Subtypes Identification](https://www.sciencedirect.com/user/identity/landing?code=W2vgnySYS2MGjyFoFBESBYYyDNYhbvHU4WE5co1j&state=retryCounter%3D0%26csrfToken%3D8aa8350e-a6b5-45f6-b21c-59ebe0a591da%26idpPolicy%3Durn%253Acom%253Aelsevier%253Aidp%253Apolicy%253Aproduct%253Ainst_assoc%26returnUrl%3D%252Fscience%252Farticle%252Fpii%252FS0169260723002080%26prompt%3Dnone%26cid%3Darp-b4b57868-8f7d-4c1c-beda-ee23531fdeba)

Z. Chen et al., "Learning vector quantized representation for cancer subtypes identification",Computer Methods and Programs in Biomedicine,
Volume 236, pages 107543, 2023.

This paper proposes to leverage a recent strong generative model, Vector-Quantized Varia- tional AutoEncoder, to tackle the data issues and extract discrete representation that are crucial to the quality of subsequent clustering by retaining only information relevant to reconstructing the input.

---------------------------------------------------------------------------------------------------------------------


System overview             
:-------------------------:
![alt text](https://github.com/chenzRG/Subtype_VQ/assets/125750017/dc751853-441b-4e50-9feb-c02f59471e97)  | <img width="2100" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/e2f4fc41-9dc1-4af8-8947-ec012b8e805e">

<img width="664" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/3d8761a3-ac12-44e9-bd0f-9d6ab4d8fdba">

<img width="669" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/2ec75520-1061-4402-bdcc-b5a23752b999">

<img width="856" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/0d7aee9c-8361-430e-ba0f-efea76cd1a10">

<img width="1024" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/1a3acb3e-cb64-4f5a-b509-7e809f337db8">


## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.

## Training



You can set up different hyperparameters by --args.xx in _main.py_.

## Reference

[1] H. Chefer, S. Gur, and L. Wolf, “Generic attention-model explainability for interpreting bi-modal and encoder-decoder transformers,” CoRR, vol. abs/2103.15679, 2021. [Online]. Available: https://arxiv.org/abs/2103.15679

[2] Hila Chefer, Shir Gur, Lior Wolf, “Transformer interpretability beyond attention visualization,” arXiv preprint arXiv:2012.09838, 2020.

## Citation
If you find this code useful in your research, please consider citing:

    @ARTICLE{TNSREchen23,
  	author={Chen, Zheng and Yang, Ziwei and Zhu, Lingwei and Chen, Wei and Tamura, Toshiyo and Ono, Naoaki and Altaf-Ul-Amin, Md and Kanaya, Shigehiko and Huang, Ming},
  	journal={IEEE Transactions on Neural Systems and Rehabilitation Engineering}, 
  	title={Automated Sleep Staging via Parallel Frequency-Cut Attention}, 
  	year={2023},
  	volume={31},
  	pages={1974-1985},
  }

## Subtype_VQ

This repository contains implementations of two research works.


# [Learning Vector Quantized Representation for Cancer Subtypes Identification](https://www.sciencedirect.com/science/article/abs/pii/S0169260723002080)

Z. Chen et al., "Learning vector quantized representation for cancer subtypes identification",Computer Methods and Programs in Biomedicine,
Volume 236, pages 107543, 2023.

This paper proposes to leverage a recent strong generative model, Vector-Quantized Varia- tional AutoEncoder, to tackle the data issues and extract discrete representation that are crucial to the quality of subsequent clustering by retaining only information relevant to reconstructing the input.

# [Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping](https://ieeexplore.ieee.org/document/9994928)

Z. Yang "Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping," 2022 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), Las Vegas, NV, USA, 2022, pp. 1350-1355.

This paper proposes a novel generative model that directly models the cancer data distribution by which downstream tasks can circumvent the curse of overfitting and achieve better performance. Unlike conventional generative modeling schemes, the proposed method underlines hierarchical categorical latent spaces to extract global features and local details respectively from transcriptomics and genomics profiles, which is the first to be considered in the cancer subtyping literature. 

---------------------------------------------------------------------------------------------------------------------


CMPB Subtype_VQ (Transcriptomics)            |  BIBM Hierarchical Subtype_VQ (Transcriptomics + Genomics)
:-------------------------:|:-------------------------:
<img width="400" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/dc751853-441b-4e50-9feb-c02f59471e97">  | <img width="430" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/e2f4fc41-9dc1-4af8-8947-ec012b8e805e">
<img width="390" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/1e7cf60a-175f-4b5d-8654-5a57d29c8812">  | <img width="450" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/3c980690-d3be-4d1e-a560-e69813bff93b">

## Description

You can find the implementation and details in the respective files of "[CMPB](https://github.com/chenzRG/Subtype_VQ/tree/main/CMPB)" and "[BIBM](https://github.com/chenzRG/Subtype_VQ/tree/main/BIBM22)".




## Citation

    @article{ChenCMPB,
    author = {Zheng Chen and Ziwei Yang and Lingwei Zhu and Peng Gao and Takashi Matsubara and Shigehiko Kanaya and Md Altaf-Ul-Amin},
    title = {Learning vector quantized representation for cancer subtypes identification},
    journal = {Computer Methods and Programs in Biomedicine},
    volume = {236},
    pages = {107543},
    year = {2023}}












