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
| NeurIPS 2020 | Denoising Diffusion Probabilistic Models<br> *Jonathan Ho, Ajay Jain, Pieter Abbeel* | [Paper](https://papers.nips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf), [TensorFlow](https://github.com/hojonathanho/diffusion), [PyTorch](https://github.com/pesser/pytorch_diffusion) |
| NeurIPS 2021 | Diffusion Models Beat GANs on Image Synthesis<br>_Prafulla Dhariwal, Alex Nichol_ | [Paper](https://papers.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf), [PyTorch](https://github.com/openai/guided-diffusion) |
|  arXiv 2022  | Video Diffusion Models<br>*Jonathan Ho, Tim Salimans, Alexey Gritsenko, William Chan, Mohammad Norouzi, David J. Fleet* |          [Paper](https://arxiv.org/abs/2204.03458)           |

## Papers

### Conference Papers

|  Proceeding  | Title                                                        |                            Assets                            |
| :----------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
|  CVPR 2022   | Diffusion Autoencoders: Toward a Meaningful and Decodable Representation<br>*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* | [Paper](https://arxiv.org/abs/2111.15640), [Project](https://diff-ae.github.io/) |
|  CVPR 2022   | High-Resolution Image Synthesis with Latent Diffusion Models<br>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer* | [Paper](https://arxiv.org/abs/2112.10752), [PyTorch](https://github.com/CompVis/latent-diffusion) |
|  CVPR 2022   | Dynamic Dual-Output Diffusion Models<br>*Yaniv Benny, Lior Wolf* |          [Paper](https://arxiv.org/abs/2203.04304)           |
|  CVPR 2022   | Perception Prioritized Training of Diffusion Models<br>*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* | [Paper](https://arxiv.org/abs/2204.00227), [PyTorch](https://arxiv.org/abs/2204.00227) |
|  CVPR 2022   | Generating High Fidelity Data from Low-density Regions using Diffusion Models<br>*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* |          [Paper](https://arxiv.org/abs/2203.17260)           |
|  ICLR 2022   | SDEdit: Image Synthesis and Editing with Stochastic Differential Equations<br>*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* | [Paper](https://openreview.net/pdf?id=aBsCjcPu_tE), [PyTorch](https://github.com/ermongroup/SDEdit), [Project](https://sde-image-editing.github.io/) |
|  ICLR 2022   | Denoising Likelihood Score Matching for Conditional Score-based Data Generation<br>*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* | [Paper](https://openreview.net/pdf?id=LcF-EEt8cCC), [Code](https://github.com/chen-hao-chao/dlsm) |
|  ICLR 2022   | Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality<br>*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* |      [Paper](https://openreview.net/pdf?id=VFBjuF8HEp)       |
|  ICLR 2022   | Progressive Distillation for Fast Sampling of Diffusion Models<br>*Tim Salimans, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=TIdIXIpzhoI), [TensorFlow](https://github.com/google-research/google-research/tree/master/diffusion_distillation) |
|  ICLR 2022   | Pseudo Numerical Methods for Diffusion Models on Manifolds<br>*Luping Liu, Yi Ren, Zhijie Lin, Zhou Zhao* | [Paper](https://openreview.net/pdf?id=PlKWVd2yBkY), [PyTorch](https://github.com/luping-liu/PNDM) |
| NeurIPS 2021 | Diffusion Normalizing Flow<br>*Qinsheng Zhang, Yongxin Chen* | [Paper](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf), [Code](https://github.com/qsh-zh/DiffFlow) |
| NeurIPS 2021 | Variational Diffusion Models<br>*Diederik P. Kingma, Tim Salimans, Ben Poole, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=2LdBqxc1Yv), [TensorFlow](https://github.com/revsic/jax-variational-diffwave) |
| NeurIPS 2021 | Structured Denoising Diffusion Models in Discrete State-Spaces<br>*Jacob Austin, Daniel D. Johnson, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* | [Paper](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf) |
|  ICCV 2021   | ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models<br>*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf), [PyTorch](https://github.com/jychoi118/ilvr_adm) |
|  ICML 2021   | Improved Denoising Diffusion Probabilistic Models<br>*Alex Nichol, Prafulla Dhariwal* | [Paper](http://proceedings.mlr.press/v139/nichol21a/nichol21a.pdf), [PyTorch](https://github.com/openai/guided-diffusion) |

### Journal Papers

|  Journal  | Title                                                        |                            Assets                            |
| :-------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| JMLR 2022 | Cascaded Diffusion Models for High Fidelity Image Generation<br>*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* | [Paper](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf), [Project](https://cascaded-diffusion.github.io/) |

### Preprints

| Preprints  | Title                                                        |                            Assets                            |
| :--------: | ------------------------------------------------------------ | :----------------------------------------------------------: |
| arXiv 2022 | DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents<br>*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* | [Paper](https://arxiv.org/abs/2201.00308), [PyTorch](https://github.com/kpandey008/DiffuseVAE) |
| arXiv 2022 | GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models<br>*Alex Nichol, Prafulla Dhariwal, Aditya Ramesh, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* |          [Paper](https://arxiv.org/abs/2112.10741)           |
| arXiv 2021 | More Control for Free! Image Synthesis with Semantic Diffusion Guidance<br>*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* | [Paper](https://arxiv.org/abs/2112.05744), [Project](https://xh-liu.github.io/sdg/) |
| arXiv 2021 | Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation<br>*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* |          [Paper](https://arxiv.org/abs/2112.01799)           |
| arXiv 2021 | Conditional Image Generation with Score-Based Diffusion Models<br>*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* |          [Paper](https://arxiv.org/abs/2111.13606)           |

## Tutorials

- Denoising Diffusion-based Generative Modeling: Foundations and Applications, _CVPR 2022_. [Website](https://cvpr2022-tutorial-diffusion-models.github.io/)