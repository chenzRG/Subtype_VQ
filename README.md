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

You can find the implementation in the respective files of "CMPB" and "BIBM".


## Setup

You can install the required dependencies using pip.

```bash
pip install -r requirements.txt
```

If you're using other than CUDA 10.2, you may need to install PyTorch for the proper version of CUDA. See [instructions](https://pytorch.org/get-started/locally/) for more details.



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





