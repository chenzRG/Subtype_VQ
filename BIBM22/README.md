
# [Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping](https://ieeexplore.ieee.org/document/9994928)

Z. Yang "Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping," 2022 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), Las Vegas, NV, USA, 2022, pp. 1350-1355.

This paper proposes a novel generative model that directly models the cancer data distribution by which downstream tasks can circumvent the curse of overfitting and achieve better performance. Unlike conventional generative modeling schemes, the proposed method underlines hierarchical categorical latent spaces to extract global features and local details respectively from transcriptomics and genomics profiles, which is the first to be considered in the cancer subtyping literature. By extensive experiments, we verify that the proposed architecture achieves more clearly separated subtypes, as well as medically significant insights into real subtyping.

---------------------------------------------------------------------------------------------------------------------

Cancer Subtyping            |  System Overview
:-------------------------:|:-------------------------:
<img width="400" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/5ab34887-02c5-4d98-8f23-f80c19202587">  | <img width="430" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/e2f4fc41-9dc1-4af8-8947-ec012b8e805e">

<img width="753" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/338d3b1c-6109-4b2c-83f1-bce380aee13c">

:-------------------------:|:-------------------------:
<img width="400" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/9247172c-9e79-4ca2-b397-0cb3deac8eb6">  | <img width="430" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/2c4442da-228f-40d6-98a2-5b81f383b803">

<img width="832" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/9247172c-9e79-4ca2-b397-0cb3deac8eb6">

<img width="683" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/2c4442da-228f-40d6-98a2-5b81f383b803">


## Description

You can find the implementation and details in the respective files of "[CMPB](https://github.com/chenzRG/Subtype_VQ/tree/main/CMPB)" and "[BIBM](https://github.com/chenzRG/Subtype_VQ/tree/main/BIBM22)".



## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.



## Citation
Please consider citing it accordingly based on your need:

    @article{ChenCMPB,
    author = {Zheng Chen and Ziwei Yang and Lingwei Zhu and Peng Gao and Takashi Matsubara and Shigehiko Kanaya and Md Altaf-Ul-Amin},
    title = {Learning vector quantized representation for cancer subtypes identification},
    journal = {Computer Methods and Programs in Biomedicine},
    volume = {236},
    pages = {107543},
    year = {2023}}

---

    @INPROCEEDINGS{YangBIBM,
    author={Yang, Ziwei and Zhu, Lingwei and Li, Chen and Chen, Zheng and Ono, Naoki and Altaf-Ul-Amin, Md and Kanaya, Shigehiko},
    booktitle={2022 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)}, 
    title={Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping}, 
    year={2022},
    pages={1350-1355}}







