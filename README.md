# [Learning Vector Quantized Representation for Cancer Subtypes Identification](https://www.sciencedirect.com/user/identity/landing?code=W2vgnySYS2MGjyFoFBESBYYyDNYhbvHU4WE5co1j&state=retryCounter%3D0%26csrfToken%3D8aa8350e-a6b5-45f6-b21c-59ebe0a591da%26idpPolicy%3Durn%253Acom%253Aelsevier%253Aidp%253Apolicy%253Aproduct%253Ainst_assoc%26returnUrl%3D%252Fscience%252Farticle%252Fpii%252FS0169260723002080%26prompt%3Dnone%26cid%3Darp-b4b57868-8f7d-4c1c-beda-ee23531fdeba)

Zheng Chen, Ziwei Yang, Lingwei Zhu, Wei Chen, Toshiyo Tamura, Naoaki Ono, MD Altaf-Ul-Amin, Shigehiko Kanaya and Ming Huang

This paper proposes to leverage a recent strong generative model, Vector-Quantized Varia- tional AutoEncoder, to tackle the data issues and extract discrete representation that are crucial to the quality of subsequent clustering by retaining only information relevant to reconstructing the input.

# [Hierarchical Categorical Generative Modeling for Multi-omics Cancer Subtyping](https://www.sciencedirect.com/user/identity/landing?code=W2vgnySYS2MGjyFoFBESBYYyDNYhbvHU4WE5co1j&state=retryCounter%3D0%26csrfToken%3D8aa8350e-a6b5-45f6-b21c-59ebe0a591da%26idpPolicy%3Durn%253Acom%253Aelsevier%253Aidp%253Apolicy%253Aproduct%253Ainst_assoc%26returnUrl%3D%252Fscience%252Farticle%252Fpii%252FS0169260723002080%26prompt%3Dnone%26cid%3Darp-b4b57868-8f7d-4c1c-beda-ee23531fdeba)

Ziwei Yang, Lingwei Zhu, Chen Li, Zheng Chen, Naoki Ono, Md Altaf-Ul-Amin, Shigehiko Kanaya

Identifying a specific cancer subtype from a variety of candidates is vital for precise and effective treatment. However, cancer subtyping is highly non-trivial as a result of cancer heterogeneity. While significant efforts have been put into understanding the mechanism of cancer subtypes via studying the omics data, existing methods run the risk of presenting biased analyses resulted from overfitting the high-dimensional and scarce omics data. In this paper, we propose a novel generative model that directly models the cancer data distribution by which downstream tasks can circumvent the curse of overfitting and achieve better performance. Unlike conventional generative modeling schemes, the proposed method underlines hierarchical categorical latent spaces to extract global features and local details respectively from transcriptomics and genomics profiles, which is the first to be considered in the cancer subtyping literature. By extensive experiments we verify that the proposed architecture achieves more clearly separated subtypes, as well as medically significant insights into real subtyping.

---------------------------------------------------------------------------------------------------------------------


System overview             |  System overview
:-------------------------:|:-------------------------:
![alt text](https://github.com/chenzRG/Subtype_VQ/assets/125750017/dc751853-441b-4e50-9feb-c02f59471e97)  | <img width="2100" alt="image" src="https://github.com/chenzRG/Subtype_VQ/assets/125750017/e2f4fc41-9dc1-4af8-8947-ec012b8e805e">



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





