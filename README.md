# Awesome-Visual-Diffusion-Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![GitHub stars](https://img.shields.io/github/stars/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=green)  ![GitHub forks](https://img.shields.io/github/forks/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=9cf)

A collection of resources and papers on ***Visual Diffusion Models***.

## Contents

- [Landmark Papers](#landmark-papers)
- [Papers](#papers)
- [Tutorials](#tutorials)

## Landmark Papers

- Denoising Diffusion Probabilistic Models
  - _NeurIPS 2020_. [Paper](https://papers.nips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf) | [TensorFlow](https://github.com/hojonathanho/diffusion) | [PyTorch](https://github.com/pesser/pytorch_diffusion)
- Diffusion Models Beat GANs on Image Synthesis
  - _NeurIPS 2021_. [Paper](https://papers.nips.cc/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf) | [PyTorch](https://github.com/openai/guided-diffusion)
- Video Diffusion Models
  - _arXiv 2022_. [Paper](https://arxiv.org/abs/2204.03458)

## Papers

### Conference Papers

- Diffusion Autoencoders: Toward a Meaningful and Decodable Representation
  - _CVPR 2022_. [Paper](https://arxiv.org/abs/2111.15640) | [Project](https://diff-ae.github.io/)
- High-Resolution Image Synthesis with Latent Diffusion Models
  - _CVPR 2022_. [Paper](https://arxiv.org/abs/2112.10752) | [PyTorch](https://github.com/CompVis/latent-diffusion)
- Dynamic Dual-Output Diffusion Models
  - _CVPR 2022_. [Paper](https://arxiv.org/abs/2203.04304)
- Perception Prioritized Training of Diffusion Models
  - _CVPR 2022_. [Paper](https://arxiv.org/abs/2204.00227) | [PyTorch](https://arxiv.org/abs/2204.00227)
- Generating High Fidelity Data from Low-density Regions using Diffusion Models
  - _CVPR 2022_. [Paper](https://arxiv.org/abs/2203.17260)
- SDEdit: Image Synthesis and Editing with Stochastic Differential Equations
  - _ICLR 2022_. [Paper](https://openreview.net/pdf?id=aBsCjcPu_tE) | [PyTorch](https://openreview.net/pdf?id=aBsCjcPu_tE) | [Project](https://sde-image-editing.github.io/)
- Denoising Likelihood Score Matching for Conditional Score-based Data Generation
  - _ICLR 2022_. [Paper](https://openreview.net/pdf?id=LcF-EEt8cCC) | [Code](https://github.com/chen-hao-chao/dlsm)
- Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality
  - _ICLR 2022_. [Paper](https://openreview.net/pdf?id=VFBjuF8HEp)
- Progressive Distillation for Fast Sampling of Diffusion Models
  - _ICLR 2022_. [Paper](https://openreview.net/pdf?id=TIdIXIpzhoI) | [TensorFlow](https://github.com/google-research/google-research/tree/master/diffusion_distillation)
- Pseudo Numerical Methods for Diffusion Models on Manifolds
  - _ICLR 2022_. [Paper](https://openreview.net/pdf?id=PlKWVd2yBkY) | [PyTorch](https://github.com/luping-liu/PNDM)
- Diffusion Normalizing Flow
  - _NeurIPS 2021_. [Paper](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf) | [Code](https://github.com/qsh-zh/DiffFlow)
- Variational Diffusion Models
  - _NeurIPS 2021_. [Paper](https://openreview.net/pdf?id=2LdBqxc1Yv) | [TensorFlow](https://github.com/revsic/jax-variational-diffwave)
- Structured Denoising Diffusion Models in Discrete State-Spaces
  - _NeurIPS 2021_. [Paper](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf)
- ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models
  - _ICCV 2021_. [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf) | [PyTorch](https://github.com/jychoi118/ilvr_adm)
- Improved Denoising Diffusion Probabilistic Models
  - _ICML 2021_. [Paper](http://proceedings.mlr.press/v139/nichol21a/nichol21a.pdf) | [PyTorch](https://github.com/openai/guided-diffusion)

### Journal Papers

- Cascaded Diffusion Models for High Fidelity Image Generation
  - _JMLR 2022_. [Paper](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf) | [Project](https://cascaded-diffusion.github.io/)

### Preprints

- DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents
  - _arXiv 2022_. [Paper](https://arxiv.org/abs/2201.00308) | [PyTorch](https://github.com/kpandey008/DiffuseVAE)
- GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models
  - _arXiv 2022_. [Paper](https://arxiv.org/abs/2112.10741)
- More Control for Free! Image Synthesis with Semantic Diffusion Guidance
  - _arXiv 2021_. [Paper](https://arxiv.org/abs/2112.05744) | [Project](https://xh-liu.github.io/sdg/)
- Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation
  - _arXiv 2021_. [Paper](https://arxiv.org/abs/2112.01799)
- Conditional Image Generation with Score-Based Diffusion Models
  - _arXiv 2021_. [Paper](https://arxiv.org/abs/2111.13606)

## Tutorials

- Denoising Diffusion-based Generative Modeling: Foundations and Applications, _CVPR 2022_. [Website](https://cvpr2022-tutorial-diffusion-models.github.io/)