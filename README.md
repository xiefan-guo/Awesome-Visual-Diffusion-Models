# Awesome-Visual-Diffusion-Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![GitHub stars](https://img.shields.io/github/stars/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=green)  ![GitHub forks](https://img.shields.io/github/forks/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=9cf)

A collection of resources and papers on ***Visual Diffusion Models***.

## Contents

- [Landmark Papers](#landmark-papers)
- [Papers](#papers)
- [Tutorials](#tutorials)

## Landmark Papers

|  Proceeding  | Title                                                        |                            Assets                            |
| :----------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| NeurIPS 2020 | __Denoising Diffusion Probabilistic Models__<br> *Jonathan Ho, Ajay Jain, Pieter Abbeel* | [Paper](https://papers.nips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf), [TensorFlow](https://github.com/hojonathanho/diffusion), [PyTorch](https://github.com/pesser/pytorch_diffusion) |
| NeurIPS 2021 | __Diffusion Models Beat GANs on Image Synthesis__<br>_Prafulla Dhariwal, Alex Nichol_ | [Paper](https://papers.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf), [PyTorch](https://github.com/openai/guided-diffusion) |
|  arXiv 2022  | __Video Diffusion Models__<br>*Jonathan Ho, Tim Salimans, Alexey Gritsenko, William Chan, Mohammad Norouzi, David J. Fleet* |          [Paper](https://arxiv.org/abs/2204.03458)           |

## Papers

### Conference Papers

|  Proceeding  | Title                                                        |                            Assets                            |
| :----------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
|  CVPR 2022   | __Diffusion Autoencoders: Toward a Meaningful and Decodable Representation__<br>*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* | [Paper](https://arxiv.org/abs/2111.15640), [Project](https://diff-ae.github.io/) |
|  CVPR 2022   | __High-Resolution Image Synthesis with Latent Diffusion Models__<br>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer* | [Paper](https://arxiv.org/abs/2112.10752), [PyTorch](https://github.com/CompVis/latent-diffusion) |
|  CVPR 2022   | __Dynamic Dual-Output Diffusion Models__<br>*Yaniv Benny, Lior Wolf* |          [Paper](https://arxiv.org/abs/2203.04304)           |
|  CVPR 2022   | __Perception Prioritized Training of Diffusion Models__<br>*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* | [Paper](https://arxiv.org/abs/2204.00227), [PyTorch](https://arxiv.org/abs/2204.00227) |
|  CVPR 2022   | __Generating High Fidelity Data from Low-density Regions using Diffusion Models__<br>*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* |          [Paper](https://arxiv.org/abs/2203.17260)           |
|  ICLR 2022   | __SDEdit: Image Synthesis and Editing with Stochastic Differential Equations__<br>*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* | [Paper](https://openreview.net/pdf?id=aBsCjcPu_tE), [PyTorch](https://github.com/ermongroup/SDEdit), [Project](https://sde-image-editing.github.io/) |
|  ICLR 2022   | __Denoising Likelihood Score Matching for Conditional Score-based Data Generation__<br>*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* | [Paper](https://openreview.net/pdf?id=LcF-EEt8cCC), [Code](https://github.com/chen-hao-chao/dlsm) |
|  ICLR 2022   | __Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality__<br>*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* |      [Paper](https://openreview.net/pdf?id=VFBjuF8HEp)       |
|  ICLR 2022   | __Progressive Distillation for Fast Sampling of Diffusion Models__<br>*Tim Salimans, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=TIdIXIpzhoI), [TensorFlow](https://github.com/google-research/google-research/tree/master/diffusion_distillation) |
|  ICLR 2022   | __Pseudo Numerical Methods for Diffusion Models on Manifolds__<br>*Luping Liu, Yi Ren, Zhijie Lin, Zhou Zhao* | [Paper](https://openreview.net/pdf?id=PlKWVd2yBkY), [PyTorch](https://github.com/luping-liu/PNDM) |
| NeurIPS 2021 | __Diffusion Normalizing Flow__<br>*Qinsheng Zhang, Yongxin Chen* | [Paper](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf), [Code](https://github.com/qsh-zh/DiffFlow) |
| NeurIPS 2021 | __Variational Diffusion Models__<br>*Diederik P. Kingma, Tim Salimans, Ben Poole, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=2LdBqxc1Yv), [TensorFlow](https://github.com/revsic/jax-variational-diffwave) |
| NeurIPS 2021 | __Structured Denoising Diffusion Models in Discrete State-Spaces__<br>*Jacob Austin, Daniel D. Johnson, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* | [Paper](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf) |
|  ICCV 2021   | __ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models__<br>*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf), [PyTorch](https://github.com/jychoi118/ilvr_adm) |
|  ICML 2021   | __Improved Denoising Diffusion Probabilistic Models__<br>*Alex Nichol, Prafulla Dhariwal* | [Paper](http://proceedings.mlr.press/v139/nichol21a/nichol21a.pdf), [PyTorch](https://github.com/openai/guided-diffusion) |

### Journal Papers

|  Journal  | Title                                                        |                            Assets                            |
| :-------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| JMLR 2022 | __Cascaded Diffusion Models for High Fidelity Image Generation__<br>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* | [Paper](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf), [Project](https://cascaded-diffusion.github.io/) |

### Preprints

| Preprints  | Title                                                        |                            Assets                            |
| :--------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| arXiv 2022 | __DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents__<br>*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* | [Paper](https://arxiv.org/abs/2201.00308), [PyTorch](https://github.com/kpandey008/DiffuseVAE) |
| arXiv 2022 | __GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models__<br>*Alex Nichol, Prafulla Dhariwal, Aditya Ramesh, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* |          [Paper](https://arxiv.org/abs/2112.10741)           |
| arXiv 2021 | __More Control for Free! Image Synthesis with Semantic Diffusion Guidance__<br>*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* | [Paper](https://arxiv.org/abs/2112.05744), [Project](https://xh-liu.github.io/sdg/) |
| arXiv 2021 | __Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation__<br>*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* |          [Paper](https://arxiv.org/abs/2112.01799)           |
| arXiv 2021 | __Conditional Image Generation with Score-Based Diffusion Models__<br>*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* |          [Paper](https://arxiv.org/abs/2111.13606)           |

## Tutorials

- Denoising Diffusion-based Generative Modeling: Foundations and Applications, _CVPR 2022_. [Website](https://cvpr2022-tutorial-diffusion-models.github.io/)