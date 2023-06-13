## Subtype_VQ

This repository contains implementations of two research works.


# [Learning Vector Quantized Representation for Cancer Subtypes Identification](https://www.sciencedirect.com/science/article/abs/pii/S0169260723002080)

Z Chen et al., "Learning vector quantized representation for cancer subtypes identification",Computer Methods and Programs in Biomedicine,
Volume 236,pages 107543,2023.

This paper proposes to leverage a recent strong generative model, Vector-Quantized Varia- tional AutoEncoder, to tackle the data issues and extract discrete representation that are crucial to the quality of subsequent clustering by retaining only information relevant to reconstructing the input.

# [Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping](https://ieeexplore.ieee.org/document/9994928)

Z Yang "Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping," 2022 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), Las Vegas, NV, USA, 2022, pp. 1350-1355.

This paper proposes a novel generative model that directly models the cancer data distribution by which downstream tasks can circumvent the curse of overfitting and achieve better performance. Unlike conventional generative modeling schemes, the proposed method underlines hierarchical categorical latent spaces to extract global features and local details respectively from transcriptomics and genomics profiles, which is the first to be considered in the cancer subtyping literature. 

---------------------------------------------------------------------------------------------------------------------


CMPB Subtype_VQ (Transcriptomics)            |  BIBM Hierarchical Subtype_VQ (Transcriptomics + Genomics)
:-------------------------:|:-------------------------:
<img width="400" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/dc751853-441b-4e50-9feb-c02f59471e97">  | <img width="430" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/e2f4fc41-9dc1-4af8-8947-ec012b8e805e">
<img width="390" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/1e7cf60a-175f-4b5d-8654-5a57d29c8812">  | <img width="450" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/3c980690-d3be-4d1e-a560-e69813bff93b">

## Description

You can find the implementation and details in the respective files of "[CMPB](https://github.com/chenzRG/Subtype_VQ/tree/main/CMPB)" and "[BIBM](https://github.com/chenzRG/Subtype_VQ/tree/main/BIBM22)".


## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.



## Citation
Please consider citing it accordingly based on your needs:

    @article{ChenCMPB,
    title = {Learning vector quantized representation for cancer subtypes identification},
    journal = {Computer Methods and Programs in Biomedicine},
    volume = {236},
    pages = {107543},
    year = {2023},
    author = {Zheng Chen and Ziwei Yang and Lingwei Zhu and Peng Gao and Takashi Matsubara and Shigehiko Kanaya and Md Altaf-Ul-Amin}}

---

    @INPROCEEDINGS{YangBIBM,
    author={Yang, Ziwei and Zhu, Lingwei and Li, Chen and Chen, Zheng and Ono, Naoki and Altaf-Ul-Amin, Md and Kanaya, Shigehiko},
    booktitle={2022 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
    title={Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping}, 
    year={2022},
    pages={1350-1355}}







