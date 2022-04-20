# Awesome-Visual-Diffusion-Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![GitHub stars](https://img.shields.io/github/stars/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=green)  ![GitHub forks](https://img.shields.io/github/forks/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=9cf)

A collection of resources and papers on ***Visual Diffusion Models***.

## Contents

- [Landmark Papers](#landmark-papers)
- [Papers](#papers)
- [Tutorials](#tutorials)
- [Blogs](#blogs)

## Landmark Papers

|  Proceeding  | Title                                                        |                            Assets                            |
| :----------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| NeurIPS 2020 | __Denoising Diffusion Probabilistic Models__<br> *Jonathan Ho, Ajay Jain, Pieter Abbeel* | [Paper](https://papers.nips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf)<br>[TensorFlow](https://github.com/hojonathanho/diffusion)<br>[PyTorch](https://github.com/pesser/pytorch_diffusion) |
| NeurIPS 2021 | __Diffusion Models Beat GANs on Image Synthesis__<br>_Prafulla Dhariwal, Alex Nichol_ | [Paper](https://papers.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf)<br>[PyTorch](https://github.com/openai/guided-diffusion) |
|  arXiv 2022  | __Video Diffusion Models__<br>*Jonathan Ho, Tim Salimans, Alexey Gritsenko, William Chan, Mohammad Norouzi, David J. Fleet* |          [Paper](https://arxiv.org/abs/2204.03458)           |

## Papers

### Conference Papers

|  Proceeding  | Title                                                        |                            Assets                            |
| :----------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
|  CVPR 2022   | __Diffusion Autoencoders: Toward a Meaningful and Decodable Representation__<br>*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* | [Paper](https://arxiv.org/abs/2111.15640)<br/>[Project](https://diff-ae.github.io/) |
|CVPR 2022|**Blended Diffusion: Text-driven Editing of Natural Images**<br>*Omri Avrahami, Dani Lischinski, Ohad Fried*|[Paper](https://arxiv.org/abs/2111.14818)<br>[PyTorch](https://github.com/omriav/blended-diffusion)<br>[Project](https://omriavrahami.com/blended-diffusion-page/)|
|CVPR 2022|**Vector Quantized Diffusion Model for Text-to-Image Synthesis**<br>*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo*|[Paper](https://arxiv.org/abs/2111.14822)<br>[PyTorch](https://github.com/microsoft/VQ-Diffusion)|
|CVPR 2022|**DiffusionCLIP: Text-guided Image Manipulation Using Diffusion Models**<br>_Gwanghyun Kim, Taesung Kwon, Jong Chul Ye_|[Paper](https://arxiv.org/abs/2110.02711)<br/>[PyTorch](https://github.com/gwang-kim/DiffusionCLIP)|
| CVPR 2022 | **RePaint: Inpainting using Denoising Diffusion Probabilistic Models**<br>*Andreas Lugmayr, Martin Danelljan, Andres Romero, Fisher Yu, Radu Timofte, Luc Van Gool* | [Paper](https://arxiv.org/abs/2201.09865)<br/>[PyTorch](https://github.com/andreas128/RePaint) |
|  CVPR 2022   | __High-Resolution Image Synthesis with Latent Diffusion Models__<br>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer* | [Paper](https://arxiv.org/abs/2112.10752)<br/>[PyTorch](https://github.com/CompVis/latent-diffusion) |
|  CVPR 2022   | __Dynamic Dual-Output Diffusion Models__<br>*Yaniv Benny, Lior Wolf* |          [Paper](https://arxiv.org/abs/2203.04304)           |
|  CVPR 2022   | __Perception Prioritized Training of Diffusion Models__<br>*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* | [Paper](https://arxiv.org/abs/2204.00227)<br/>[PyTorch](https://arxiv.org/abs/2204.00227) |
|  CVPR 2022   | __Generating High Fidelity Data from Low-density Regions using Diffusion Models__<br>*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* |          [Paper](https://arxiv.org/abs/2203.17260)           |
|  ICLR 2022   | __SDEdit: Image Synthesis and Editing with Stochastic Differential Equations__<br>*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* | [Paper](https://openreview.net/pdf?id=aBsCjcPu_tE)<br/>[PyTorch](https://github.com/ermongroup/SDEdit)<br/>[Project](https://sde-image-editing.github.io/) |
|  ICLR 2022   | __Denoising Likelihood Score Matching for Conditional Score-based Data Generation__<br>*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* | [Paper](https://openreview.net/pdf?id=LcF-EEt8cCC)<br/>[Code](https://github.com/chen-hao-chao/dlsm) |
|  ICLR 2022   | __Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality__<br>*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* |      [Paper](https://openreview.net/pdf?id=VFBjuF8HEp)       |
|  ICLR 2022   | __Progressive Distillation for Fast Sampling of Diffusion Models__<br>*Tim Salimans, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=TIdIXIpzhoI)<br/>[TensorFlow](https://github.com/google-research/google-research/tree/master/diffusion_distillation) |
|ICLR 2022|**Autoregressive Diffusion Models**<br>*Emiel Hoogeboom, Alexey A. Gritsenko, Jasmijn Bastings, Ben Poole, Rianne van den Berg, Tim Salimans*|[Paper](https://openreview.net/pdf?id=Lm8T39vLDTE)|
|  ICLR 2022   | __Pseudo Numerical Methods for Diffusion Models on Manifolds__<br>*Luping Liu, Yi Ren, Zhijie Lin, Zhou Zhao* | [Paper](https://openreview.net/pdf?id=PlKWVd2yBkY)<br/>[PyTorch](https://github.com/luping-liu/PNDM) |
|ICLR 2022|**Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality**<br>*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi*|[Paper](https://openreview.net/pdf?id=VFBjuF8HEp)|
|ICLR 2022|**Label-Efficient Semantic Segmentation with Diffusion Models**<br>*Dmitry Baranchuk, Andrey Voynov, Ivan Rubachev, Valentin Khrulkov, Artem Babenko*|[Paper](https://openreview.net/pdf?id=SlxSY2UZQT)<br/>[PyTorch](https://github.com/yandex-research/ddpm-segmentation)|
|ICLR 2022|**Step-unrolled Denoising Autoencoders for Text Generation**<br>*Nikolay Savinov, Junyoung Chung, Mikolaj Binkowski, Erich Elsen, Aaron van den Oord*|[Paper](https://openreview.net/pdf?id=T0GpzBQ1Fg6)<br/>[PyTorch](https://github.com/vvvm23/sundae)|
|ICLR 2022|**Tackling the Generative Learning Trilemma with Denoising Diffusion GANs**<br>*Zhisheng Xiao, Karsten Kreis, Arash Vahdat*|[Paper](https://openreview.net/pdf?id=JprM0p-q0Co)<br/>[PyTorch](https://github.com/NVlabs/denoising-diffusion-gan)<br/>[Project](https://nvlabs.github.io/denoising-diffusion-gan/)|
|ICLR 2022|**PriorGrad: Improving Conditional Denoising Diffusion Models with Data-Dependent Adaptive Prior**<br>*Sang-gil Lee, Heeseung Kim, Chaehun Shin, Xu Tan, Chang Liu, Qi Meng, Tao Qin, Wei Chen, Sungroh Yoon, Tie-Yan Liu*|[Paper](https://openreview.net/pdf?id=_BNiN4IjC5)|
|ICLR 2022|**A Conditional Point Diffusion-Refinement Paradigm for 3D Point Cloud Completion**<br>*Zhaoyang Lyu, Zhifeng Kong, Xudong Xu, Liang Pan, Dahua Lin*|[Paper](https://arxiv.org/abs/2112.03530)<br>[PyTorch](https://github.com/ZhaoyangLyu/Point_Diffusion_Refinement)|
|ICLR 2022|**BDDM: Bilateral Denoising Diffusion Models for Fast and High-Quality Speech Synthesis**<br>*Max W. Y. Lam, Jun Wang, Dan Su, Dong Yu*|[Paper](https://arxiv.org/abs/2203.13508)<br>[PyTorch](https://github.com/tencent-ailab/bddm)|
| ICLR 2022 Workshop | **Denoising Diffusion Restoration Models**<br>*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* | [Paper](https://openreview.net/pdf?id=BExXihVOvWq)<br/>[PyTorch](https://github.com/bahjat-kawar/ddrm)<br/>[Project](https://ddrm-ml.github.io/) |
|MIDL 2022|**Diffusion Models for Implicit Image Segmentation Ensembles **<br>*Julia Wolleb, Robin Sandkuehler, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin*|[Paper](https://openreview.net/pdf?id=QNLR05X6uW)<br>[PyTorch](https://github.com/JuliaWolleb/Diffusion-based-Segmentation)|
|NeurIPS 2021|**Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions**<br>*Emiel Hoogeboom, Didrik Nielsen, Priyank Jaini, Patrick Forré, Max Welling*|[Paper](https://arxiv.org/abs/2102.05379)<br>[PyTorch](https://github.com/ehoogeboom/multinomial_diffusion)|
| NeurIPS 2021 | __Diffusion Normalizing Flow__<br>*Qinsheng Zhang, Yongxin Chen* | [Paper](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf)<br/>[Code](https://github.com/qsh-zh/DiffFlow) |
|NeurIPS 2021|**ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis**<br>*Patrick Esser, Robin Rombach, Andreas Blattmann, Bjorn Ommer*|[Paper](https://papers.nips.cc/paper/2021/file/1cdf14d1e3699d61d237cf76ce1c2dca-Paper.pdf)<br/>[PyTorch](https://github.com/CompVis/imagebart)<br/>[Project](https://compvis.github.io/imagebart/)|
| NeurIPS 2021 | __Variational Diffusion Models__<br>*Diederik P. Kingma, Tim Salimans, Ben Poole, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=2LdBqxc1Yv)<br/>[TensorFlow](https://github.com/revsic/jax-variational-diffwave) |
|NeurIPS 2021|**D2C: Diffusion-Decoding Models for Few-Shot Conditional Generation**<br>*Abhishek Sinha, Jiaming Song, Chenlin Meng, Stefano Ermon*|[Paper](https://papers.nips.cc/paper/2021/file/682e0e796084e163c5ca053dd8573b0c-Paper.pdf)<br/>[PyTorch](https://github.com/jiamings/d2c)|
| NeurIPS 2021 | __Structured Denoising Diffusion Models in Discrete State-Spaces__<br>*Jacob Austin, Daniel D. Johnson, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* | [Paper](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf) |
|  ICCV 2021   | __ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models__<br>*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf)<br/>[PyTorch](https://github.com/jychoi118/ilvr_adm) |
|  ICML 2021   | __Improved Denoising Diffusion Probabilistic Models__<br>*Alex Nichol, Prafulla Dhariwal* | [Paper](http://proceedings.mlr.press/v139/nichol21a/nichol21a.pdf)<br/>[PyTorch](https://github.com/openai/guided-diffusion) |
|CVPR 2021|**Diffusion Probabilistic Models for 3D Point Cloud Generation**<br>*Shitong Luo, Wei Hu*|[Paper](https://arxiv.org/abs/2103.01458)<br>[PyTorch](https://github.com/luost26/diffusion-point-cloud)|
|  ICLR 2021   | **Denoising Diffusion Implicit Models**<br>*Jiaming Song, Chenlin Meng, Stefano Ermon* | [Paper](https://arxiv.org/pdf/2010.02502.pdf)<br/>[PyTorch](https://github.com/ermongroup/ddim) |

### Journal Papers

|  Journal  | Title                                                        |                            Assets                            |
| :-------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| JMLR 2022 | __Cascaded Diffusion Models for High Fidelity Image Generation__<br>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* | [Paper](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf)<br/>[Project](https://cascaded-diffusion.github.io/) |
|Neurocomputing 2022|**SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models**<br>*Haoying Li, Yifan Yang, Meng Chang, Huajun Feng, Zhihai Xu, Qi Li, Yueting Chen*|[Paper](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231222X00052/1-s2.0-S0925231222000522/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFsaCXVzLWVhc3QtMSJHMEUCIQCgUMWHjE8gIueL%2Fqp7laxcfNruM%2BvJNEpie9Rw%2ByeqnAIgIVlL6Bqqx4tTAuTDr9GPYYZXJ4m%2Fshz3eCNWIaph5vAq%2BgMIFBAEGgwwNTkwMDM1NDY4NjUiDG5nKs9B4LtwccnXCCrXA984SEbaz8RSWLrQJIwUohsNAK3uInK4x6UclSTVKXsKSRWzHjCiXmnPmjTGeXi7lTn9uxTMyrbNRjJItktlsN6GCi59XJXxKkCeIvIBw3eySch7XxigHE3C5TNKNixPtU%2FfQK8MRRL0GyUkkCYHmF58Y4DgiEx8IcXGZ97G0aemmkFiZStPkF9quDZTLTFUDwi2NTq%2BBZFZlzsgiHmPUzt2z24X6QDMA7%2FX4pnO0XEx%2BaJM2CR7m7WGQjBv7W%2BJ%2BtqxGgk%2BPqfSmLpKQYFehPL8XD16CWWdkamzO18wVSRP%2FRnzVDQqBH5YjP2XeazUaM%2FcNjFR0jtUEEGWhBOHzesR%2FuAyRiMkFs16foyMW%2FdSfn%2B71yhcYAIPqgBr451sxl4UEjMjUFU1XzCmzQVpHm9AksPdKrObG%2BLVd%2BYhkaHO08CjEvuVeSbQ7PzHuHBxxJuz3LTGYi%2BU1Jbl0Nzv9yoy6j0Occ3Eh3mWuRN6b48xp6JRrNKDpyecnXAqYEj%2Fx8hAq%2Bljcx1chD%2B95yqbZot946NOwyl81He%2BZYi%2Fu7WLIw%2FPCLQV80ui58USiABuBThPHu45IKee8K2QB%2BZ9iUF0s8GM%2BQQNTHoLyKeZoy5lDWahxF6UljDYvv%2BSBjqlASaYI59MNS%2BL%2FX3lZlX7A3CV%2For7PFM%2FDJBPcCsAY5WXe7Utwg29HfW%2FKp7kw7Ti%2FyPyKcMTHBC4SjUMKwg3l2PleJ9%2BVjVFMThreeXa5gfAyCvIxsw8KqalritCnQHkm%2Bbcj81Jdbb5Dkd%2BFBsiWlQz9QpkADi%2Fk3cl0tqeiZGT8ZPlklttsJ7BzZdqBvNlE2zI8%2BpRrdwwRXmN9xRWHCTUDqh39g%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220420T104606Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYQWXNHQZT%2F20220420%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=08f9ddf9c8c03b12c2ec412e893fa560dde8a5a2fbb11ba2d51060bd937d14a4&hash=170d482a303e0cff3d45394eefa4c832014aac6a9a2a1884010a423471f8ce15&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231222000522&tid=spdf-8efefece-fdd3-4752-a9bb-1985d4a89198&sid=1016bb248fd9e346f0992e262f73636fef18gxrqa&type=client)|

### Preprints

| Preprints  | Title                                                        |                            Assets                            |
| :--------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
|arXiv 2022|**Hierarchical Text-Conditional Image Generation with CLIP Latents**<br>*Aditya Ramesh, Prafulla Dhariwal, Alex Nichol, Casey Chu, Mark Chen*|[Paper](https://arxiv.org/abs/2204.06125)|
|arXiv 2022|**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models**<br>*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe C. Cattin*|[Paper](https://arxiv.org/abs/2204.02641)|
|arXiv 2022|**Dual Diffusion Implicit Bridges for Image-to-Image Translation**<br>*Xuan Su, Jiaming Song, Chenlin Meng, Stefano Ermon*|[Paper](https://arxiv.org/abs/2203.08382)|
| arXiv 2022 | __DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents__<br>*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* | [Paper](https://arxiv.org/abs/2201.00308)<br/>[PyTorch](https://github.com/kpandey008/DiffuseVAE) |
| arXiv 2022 | __GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models__<br>*Alex Nichol, Prafulla Dhariwal, Aditya Ramesh, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* |          [Paper](https://arxiv.org/abs/2112.10741)           |
|arXiv 2022|**Diffusion Probabilistic Modeling for Video Generation**<br>*Ruihan Yang, Prakhar Srivastava, Stephan Mandt*|[Paper](https://arxiv.org/abs/2203.09481)|
| arXiv 2021 | __More Control for Free! Image Synthesis with Semantic Diffusion Guidance__<br>*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* | [Paper](https://arxiv.org/abs/2112.05744)<br/>[Project](https://xh-liu.github.io/sdg/) |
| arXiv 2021 | __Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation__<br>*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* |          [Paper](https://arxiv.org/abs/2112.01799)           |
| arXiv 2021 | __Conditional Image Generation with Score-Based Diffusion Models__<br>*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* |          [Paper](https://arxiv.org/abs/2111.13606)           |
|arXiv 2021|**Palette: Image-to-Image Diffusion Models**<br>*Chitwan Saharia, William Chan, Huiwen Chang, Chris A. Lee, Jonathan Ho, Tim Salimans, David J. Fleet, Mohammad Norouzi*|[Paper](https://arxiv.org/abs/2111.05826)<br>[Project](https://iterative-refinement.github.io/palette/)|

## Tutorials

- Denoising Diffusion-based Generative Modeling: Foundations and Applications, _CVPR 2022_. [Website](https://cvpr2022-tutorial-diffusion-models.github.io/)

## Blogs

- What are Diffusion Models? _Lilian Weng_. [Website](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)