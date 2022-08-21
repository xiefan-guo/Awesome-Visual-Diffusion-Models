# Awesome-Visual-Diffusion-Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![GitHub stars](https://img.shields.io/github/stars/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=green)  ![GitHub forks](https://img.shields.io/github/forks/Xiefan-Guo/Awesome-Visual-Diffusion-Models?color=9cf)

A collection of resources and papers on ***Visual Diffusion Models***.

## Contents

- [Awesome-Visual-Diffusion-Models](#awesome-visual-diffusion-models)
  - [Contents](#contents)
  - [Landmark Papers](#landmark-papers)
  - [Papers](#papers)
    - [Conference Papers](#conference-papers)
    - [Journal Papers](#journal-papers)
    - [Preprints](#preprints)
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
|ACM MM 2022|**ProDiff: Progressive Fast Diffusion Model For High-Quality Text-to-Speech**<br>*Rongjie Huang, Zhou Zhao, Huadai Liu, Jinglin Liu, Chenye Cui, Yi Ren*|[Paper](https://arxiv.org/abs/2207.06389)|
|ECCV 2022|**Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling**<br>*Hengyuan Ma, Li Zhang, Xiatian Zhu, Jianfeng Feng*|[Paper](https://arxiv.org/abs/2207.02196)<br>[PyTorch](https://github.com/fudan-zvg/PDS)|
|MICCAI 2022|**Diffusion Deformable Model for 4D Temporal Medical Image Generation**<br>*Boah Kim, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2206.13295)|
|ICML 2022|**Diffusion bridges vector quantized Variational AutoEncoders**<br>*Max Cohen, Guillaume Quispe, Sylvain Le Corff, Charles Ollion, Eric Moulines*|[Paper](https://arxiv.org/abs/2202.04895)|
|ICML 2022|**Maximum Likelihood Training for Score-based Diffusion ODEs by High Order Denoising Score Matching**<br>*Cheng Lu, Kaiwen Zheng, Fan Bao, Chongxuan Li, Jianfei Chen, Jun Zhu*||
|ICML 2022|**Equivariant Diffusion for Molecule Generation in 3D**<br>*Emiel Hoogeboom, Victor Garcia Satorras, Clément Vignac, Max Welling*|[Paper](https://arxiv.org/abs/2203.17003)|
|ICML 2022|**Soft Truncation: A Universal Training Technique of Score-based Diffusion Model for High Precision Score Estimation**<br>*Dongjun Kim, Seungjae Shin, Kyungwoo Song, Wanmo Kang, Il-Chul Moon*|[Paper](https://arxiv.org/abs/2106.05527)|
|ICML 2022|**Latent Diffusion Energy-Based Model for Interpretable Text Modeling**<br>*Peiyu Yu, Sirui Xie, Baoxiong Jia, Bo Pang, Ruiqi Gao, Yixin Zhu, Song-Chun Zhu, Ying Nian Wu*||
|ICML 2022|**Estimating the Optimal Covariance with Imperfect Mean in Diffusion Probabilistic Models**<br>*Fan Bao, Chongxuan Li, Jiacheng Sun, Jun Zhu, Bo Zhang*|[Paper](https://arxiv.org/abs/2206.07309)<br>[PyTorch](https://github.com/baofff/Extended-Analytic-DPM)|
|ICML 2022|**Guided-TTS: A Diffusion Model for Text-to-Speech via Classifier Guidance**<br>*Heeseung Kim, Sungwon Kim, Sungroh Yoon*|[Paper](http://arxiv-export-lb.library.cornell.edu/abs/2111.11755)|
| ICML 2022 | __GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models__<br>*Alex Nichol, Prafulla Dhariwal, Aditya Ramesh, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* |          [Paper](https://arxiv.org/abs/2112.10741)           |
|ICML 2022|**Diffusion Models for Adversarial Purification**<br>*Weili Nie, Brandon Guo, Yujia Huang, Chaowei Xiao, Arash Vahdat, Anima Anandkumar*|[Paper](https://diffpure.github.io/)<br>[Project](https://diffpure.github.io/)|
|IJCAI 2022|**FastDiff: A Fast Conditional Diffusion Model for High-Quality Speech Synthesis**<br>*Rongjie Huang, Max W. Y. Lam, Jun Wang, Dan Su, Dong Yu, Yi Ren, Zhou Zhao*|[Paper](https://arxiv.org/abs/2204.09934)|
|  CVPR 2022   | __Diffusion Autoencoders: Toward a Meaningful and Decodable Representation__<br>*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* | [Paper](https://arxiv.org/abs/2111.15640)<br/>[Project](https://diff-ae.github.io/) |
|CVPR 2022|**Blended Diffusion: Text-driven Editing of Natural Images**<br>*Omri Avrahami, Dani Lischinski, Ohad Fried*|[Paper](https://arxiv.org/abs/2111.14818)<br>[PyTorch](https://github.com/omriav/blended-diffusion)<br>[Project](https://omriavrahami.com/blended-diffusion-page/)|
|CVPR 2022|**Vector Quantized Diffusion Model for Text-to-Image Synthesis**<br>*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo*|[Paper](https://arxiv.org/abs/2111.14822)<br>[PyTorch](https://github.com/microsoft/VQ-Diffusion)|
|CVPR 2022|**DiffusionCLIP: Text-guided Image Manipulation Using Diffusion Models**<br>_Gwanghyun Kim, Taesung Kwon, Jong Chul Ye_|[Paper](https://arxiv.org/abs/2110.02711)<br/>[PyTorch](https://github.com/gwang-kim/DiffusionCLIP)|
| CVPR 2022 | **RePaint: Inpainting using Denoising Diffusion Probabilistic Models**<br>*Andreas Lugmayr, Martin Danelljan, Andres Romero, Fisher Yu, Radu Timofte, Luc Van Gool* | [Paper](https://arxiv.org/abs/2201.09865)<br/>[PyTorch](https://github.com/andreas128/RePaint) |
|  CVPR 2022   | __High-Resolution Image Synthesis with Latent Diffusion Models__<br>*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer* | [Paper](https://arxiv.org/abs/2112.10752)<br/>[PyTorch](https://github.com/CompVis/latent-diffusion) |
|  CVPR 2022   | __Dynamic Dual-Output Diffusion Models__<br>*Yaniv Benny, Lior Wolf* |          [Paper](https://arxiv.org/abs/2203.04304)           |
|  CVPR 2022   | __Perception Prioritized Training of Diffusion Models__<br>*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* | [Paper](https://arxiv.org/abs/2204.00227)<br/>[PyTorch](https://arxiv.org/abs/2204.00227) |
|  CVPR 2022   | __Generating High Fidelity Data from Low-density Regions using Diffusion Models__<br>*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* |          [Paper](https://arxiv.org/abs/2203.17260)           |
|CVPR 2022|**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction**<br>*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2112.05146)|
|CVPRW 2022|**On Conditioning the Input Noise for Controlled Image Generation with Diffusion Models**<br>*Vedant Singh, Surgan Jandial, Ayush Chopra, Siddharth Ramesh, Balaji Krishnamurthy, Vineeth N. Balasubramanian*|[Paper](https://arxiv.org/abs/2205.03859)|
|ICLR 2022|**Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models**<br>*Fan Bao, Chongxuan Li, Jun Zhu, Bo Zhang*|[Paper](https://openreview.net/pdf?id=0xiJLKH-ufZ)<br>[PyTorch](https://github.com/baofff/Analytic-DPM)|
|  ICLR 2022   | __SDEdit: Image Synthesis and Editing with Stochastic Differential Equations__<br>*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* | [Paper](https://openreview.net/pdf?id=aBsCjcPu_tE)<br/>[PyTorch](https://github.com/ermongroup/SDEdit)<br/>[Project](https://sde-image-editing.github.io/) |
|  ICLR 2022   | __Denoising Likelihood Score Matching for Conditional Score-based Data Generation__<br>*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* | [Paper](https://openreview.net/pdf?id=LcF-EEt8cCC)<br/>[Code](https://github.com/chen-hao-chao/dlsm) |
|  ICLR 2022   | __Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality__<br>*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* |      [Paper](https://openreview.net/pdf?id=VFBjuF8HEp)       |
|ICLR 2022|**Score-Based Generative Modeling with Critically-Damped Langevin Diffusion**<br>*Tim Dockhorn, Arash Vahdat, Karsten Kreis*|[Paper](https://arxiv.org/abs/2112.07068)<br>[PyTorch](https://github.com/nv-tlabs/CLD-SGM)|
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
|MIDL 2022|**Diffusion Models for Implicit Image Segmentation Ensembles**<br>*Julia Wolleb, Robin Sandkuehler, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin*|[Paper](https://openreview.net/pdf?id=QNLR05X6uW)<br>[PyTorch](https://github.com/JuliaWolleb/Diffusion-based-Segmentation)|
|NeurIPS 2021|**Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions**<br>*Emiel Hoogeboom, Didrik Nielsen, Priyank Jaini, Patrick Forré, Max Welling*|[Paper](https://arxiv.org/abs/2102.05379)<br>[PyTorch](https://github.com/ehoogeboom/multinomial_diffusion)|
| NeurIPS 2021 | __Diffusion Normalizing Flow__<br>*Qinsheng Zhang, Yongxin Chen* | [Paper](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf)<br/>[Code](https://github.com/qsh-zh/DiffFlow) |
|NeurIPS 2021|**ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis**<br>*Patrick Esser, Robin Rombach, Andreas Blattmann, Bjorn Ommer*|[Paper](https://papers.nips.cc/paper/2021/file/1cdf14d1e3699d61d237cf76ce1c2dca-Paper.pdf)<br/>[PyTorch](https://github.com/CompVis/imagebart)<br/>[Project](https://compvis.github.io/imagebart/)|
|NeurIPS 2021|**Maximum Likelihood Training of Score-Based Diffusion Models**<br>*Yang Song, Conor Durkan, Iain Murray, Stefano Ermon*|[Paper](https://proceedings.neurips.cc/paper/2021/hash/0a9fdbb17feb6ccb7ec405cfb85222c4-Abstract.html)<br>[TensorFlow](https://github.com/yang-song/score_flow)|
| NeurIPS 2021 | __Variational Diffusion Models__<br>*Diederik P. Kingma, Tim Salimans, Ben Poole, Jonathan Ho* | [Paper](https://openreview.net/pdf?id=2LdBqxc1Yv)<br/>[TensorFlow](https://github.com/revsic/jax-variational-diffwave) |
|NeurIPS 2021|**D2C: Diffusion-Decoding Models for Few-Shot Conditional Generation**<br>*Abhishek Sinha, Jiaming Song, Chenlin Meng, Stefano Ermon*|[Paper](https://papers.nips.cc/paper/2021/file/682e0e796084e163c5ca053dd8573b0c-Paper.pdf)<br/>[PyTorch](https://github.com/jiamings/d2c)|
| NeurIPS 2021 | __Structured Denoising Diffusion Models in Discrete State-Spaces__<br>*Jacob Austin, Daniel D. Johnson, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* | [Paper](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf) |
|NeurIPS 2021|**CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation**<br>*Yusuke Tashiro, Jiaming Song, Yang Song, Stefano Ermon*|[Paper](https://arxiv.org/abs/2107.03502)<br>[PyTorch](https://github.com/ermongroup/CSDI)|
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
|arXiv 2022|**Riemannian Diffusion Models**<br>*Chin-Wei Huang, Milad Aghajohari, Avishek Joey Bose, Prakash Panangaden, Aaron Courville*|[Paper](https://arxiv.org/abs/2208.07949)|
|arXiv 2022|**High-Frequency Space Diffusion Models for Accelerated MRI**<br>*Chentao Cao, Zhuo-Xu Cui, Shaonan Liu, Dong Liang, Yanjie Zhu*|[Paper](https://arxiv.org/abs/2208.05481)|
|arXiv 2022|**Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning**<br>*Ting Chen, Ruixiang Zhang, Geoffrey Hinton*|[Paper](https://arxiv.org/abs/2208.04202)|
|arXiv 2022|**Pyramidal Denoising Diffusion Probabilistic Models**<br>*Dohoon Ryu, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2208.01864)|
|arXiv 2022|**DeScoD-ECG: Deep Score-Based Diffusion Model for ECG Baseline Wander and Noise Removal**<br>*Huayu Li, Gregory Ditzler, Janet Roveda, Ao Li*|[Paper](https://arxiv.org/abs/2208.00542)|
|arXiv 2022|**Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models**<br>*Ozan Özdenizci, Robert Legenstein*|[Paper](https://arxiv.org/abs/2207.14626)|
|arXiv 2022|**Text-Guided Synthesis of Artistic Images with Retrieval-Augmented Diffusion Models**<br>*Robin Rombach, Andreas Blattmann, Björn Ommer*|[Paper](https://arxiv.org/abs/2207.13038)|
|arXiv 2022|**Progressive Deblurring of Diffusion Models for Coarse-to-Fine Image Synthesis**<br>*Sangyun Lee, Hyungjin Chung, Jaehyeon Kim, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2207.11192)|
|arXiv 2022|**Deep Diffusion Models for Seismic Processing**<br>*Ricard Durall, Ammar Ghanim, Mario Fernandez, Norman Ettrich, Janis Keuper*|[Paper](https://arxiv.org/abs/2207.10451)|
|arXiv 2022|**Diffsound: Discrete Diffusion Model for Text-to-sound Generation**<br>*Dongchao Yang, Jianwei Yu, Helin Wang, Wen Wang, Chao Weng, Yuexian Zou, Dong Yu*|[Paper](https://arxiv.org/abs/2207.09983)|
|arXiv 2022|**Non-Uniform Diffusion Models**<br>*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann*|[Paper](https://arxiv.org/abs/2207.09786)|
|arXiv 2022|**Diffsound: Discrete Diffusion Model for Text-to-sound Generation**<br>*Dongchao Yang, Jianwei Yu, Helin Wang, Wen Wang, Chao Weng, Yuexian Zou, Dong Yu*|[Paper](https://arxiv.org/abs/2207.09983)|
|arXiv 2022|**Adaptive Diffusion Priors for Accelerated MRI Reconstruction**<br>*Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Alper Güngör, Tolga Çukur*|[Paper](https://arxiv.org/abs/2207.05876)|
|arXiv 2022|**Unsupervised Medical Image Translation with Adversarial Diffusion Models**<br>*Muzaffer Özbey, Salman UH Dar, Hasan A Bedel, Onat Dalmaz, Şaban Özturk, Alper Güngör, Tolga Çukur*|[Paper](https://arxiv.org/abs/2207.08208)|
|arXiv 2022|**Threat Model-Agnostic Adversarial Defense using Diffusion Models**<br>*Tsachi Blau, Roy Ganz, Bahjat Kawar, Alex Bronstein, Michael Elad*|[Paper](https://arxiv.org/abs/2207.08089)|
|arXiv 2022|**Improving Diffusion Model Efficiency Through Patching**<br>*Troy Luhman, Eric Luhman*|[Paper](https://arxiv.org/abs/2207.04316)|
|arXiv 2022|**Semantic Image Synthesis via Diffusion Models**<br>*Weilun Wang, Jianmin Bao, Wengang Zhou, Dongdong Chen, Dong Chen, Lu Yuan, Houqiang Li*|[Paper](https://arxiv.org/abs/2207.00050)|
|arXiv 2022|**DDPM-CD: Remote Sensing Change Detection using Denoising Diffusion Probabilistic Models**<br>*Wele Gedara Chaminda Bandara, Nithin Gopalakrishnan Nair, Vishal M. Patel*|[Paper](https://arxiv.org/abs/2206.11892)<br>[PyTorch](https://github.com/wgcban/ddpm-cd)|
|arXiv 2022|**Guided Diffusion Model for Adversarial Purification from Random Noise**<br>*Quanlin Wu, Hang Ye, Yuntian Gu*|[Paper](https://arxiv.org/abs/2206.10875)|
|arXiv 2022|**A Flexible Diffusion Model**<br>*Weitao Du, Tao Yang, He Zhang, Yuanqi Du*|[Paper](https://arxiv.org/abs/2206.10365)|
|arXiv 2022|**Diffusion models as plug-and-play priors**<br>*Alexandros Graikos, Nikolay Malkin, Nebojsa Jojic, Dimitris Samaras*|[Paper](https://arxiv.org/abs/2206.09012)<br>[PyTorch](https://github.com/AlexGraikos/diffusion_priors)|
|arXiv 2022|**CARD: Classification and Regression Diffusion Models**<br>*Xizewen Han, Huangjie Zheng, Mingyuan Zhou*|[Paper](https://arxiv.org/abs/2206.07275)|
|arXiv 2022|**Diffusion Models for Video Prediction and Infilling**<br>*Tobias Höppe, Arash Mehrjou, Stefan Bauer, Didrik Nielsen, Andrea Dittadi*|[Paper](https://arxiv.org/abs/2206.07696)|
|arXiv 2022|**gDDIM: Generalized denoising diffusion implicit models**<br>*Qinsheng Zhang, Molei Tao, Yongxin Chen*|[Paper](https://arxiv.org/abs/2206.05564)<br>[Code](https://github.com/qsh-zh/gDDIM)|
|arXiv 2022|**How Much is Enough? A Study on Diffusion Times in Score-based Generative Models**<br>*Giulio Franzese, Simone Rossi, Lixuan Yang, Alessandro Finamore, Dario Rossi, Maurizio Filippone, Pietro Michiardi*|[Paper](https://arxiv.org/abs/2206.05173)|
|arXiv 2022|**Image Generation with Multimodal Priors using Denoising Diffusion Probabilistic Models**<br>*Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M Patel*|[Paper](https://arxiv.org/abs/2206.05039)|
|arXiv 2022|**SAR Despeckling using a Denoising Diffusion Probabilistic Model**<br>*Malsha V. Perera, Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel*|[Paper](https://arxiv.org/abs/2206.04514)|
|arXiv 2022|**Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem**<br>*Brian L. Trippe, Jason Yim, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola*|[Paper](https://arxiv.org/abs/2206.04119)|
|arXiv 2022|**Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models**<br>*Walter H. L. Pinaya, Mark S. Graham, Robert Gray, Pedro F Da Costa, Petru-Daniel Tudosiu, Paul Wright, Yee H. Mah, Andrew D. MacKinnon, James T. Teo, Rolf Jager, David Werring, Geraint Rees, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso*|[Paper](https://arxiv.org/abs/2206.03461)|
|arXiv 2022|**Blended Latent Diffusion**<br>*Omri Avrahami, Ohad Fried, Dani Lischinski*|[Paper](https://arxiv.org/abs/2206.02779)<br>[PyTorch](https://github.com/omriav/blended-latent-diffusion)<br>[Project](https://omriavrahami.com/blended-latent-diffusion-page/)|
|arXiv 2022|**Diffusion-GAN: Training GANs with Diffusion**<br>*Zhendong Wang, Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou*|[Paper](https://arxiv.org/abs/2206.02262)|
|arXiv 2022|**Compositional Visual Generation with Composable Diffusion Models**<br>*Nan Liu, Shuang Li, Yilun Du, Antonio Torralba, Joshua B. Tenenbaum*|[Paper](https://arxiv.org/abs/2206.01714)|
|arXiv 2022|**Improving Diffusion Models for Inverse Problems using Manifold Constraints**<br>*Hyungjin Chung, Byeongsu Sim, Dohoon Ryu, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2206.00941)|
|arXiv 2022|**DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps**<br>*Cheng Lu, Yuhao Zhou, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu*|[Paper](https://arxiv.org/abs/2206.00927)|
|arXiv 2022|**On Analyzing Generative and Denoising Capabilities of Diffusion-based Deep Generative Models**<br>*Kamil Deja, Anna Kuzina, Tomasz Trzciński, Jakub M. Tomczak*|[Paper](https://arxiv.org/abs/2206.00070)|
|arXiv 2022|**Elucidating the Design Space of Diffusion-Based Generative Models**<br>*Tero Karras, Miika Aittala, Timo Aila, Samuli Laine*|[Paper](https://arxiv.org/abs/2206.00364)|
|arXiv 2022|**Improved Vector Quantized Diffusion Models**<br>*Zhicong Tang, Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen*|[Paper](https://arxiv.org/abs/2205.16007)<br>[PyTorch](https://github.com/microsoft/VQ-Diffusion)|
|arXiv 2022|**Few-Shot Diffusion Models**<br>*Giorgio Giannone, Didrik Nielsen, Ole Winther*|[Paper](https://arxiv.org/abs/2205.15463)<br>[PyTorch](https://github.com/submission-neurips22/few-shot-diffusion-models)|
|arXiv 2022|**Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models**<br>*Namrata Anand, Tudor Achim*|[Paper](https://arxiv.org/abs/2205.15019)<br>[Project](https://nanand2.github.io/proteins/)|
|arXiv 2022|**Guided Diffusion Model for Adversarial Purification**<br>*Jinyi Wang, Zhaoyang Lyu, Dahua Lin, Bo Dai, Hongfei Fu*|[Paper](https://arxiv.org/abs/2205.14969)|
|arXiv 2022|**Pretraining is All You Need for Image-to-Image Translation**<br>*Tengfei Wang, Ting Zhang, Bo Zhang, Hao Ouyang, Dong Chen, Qifeng Chen, Fang Wen*|[Paper](https://arxiv.org/abs/2205.12952)<br>[PyTorch](https://github.com/PITI-Synthesis/PITI)<br>[Project](https://tengfei-wang.github.io/PITI/index.html)|
|arXiv 2022|**Maximum Likelihood Training of Implicit Nonlinear Diffusion Models**<br>*Dongjun Kim, Byeonghu Na, Se Jung Kwon, Dongsoo Lee, Wanmo Kang, Il-Chul Moon*|[Paper](https://arxiv.org/abs/2205.13699)|
|arXiv 2022|**Accelerating Diffusion Models via Early Stop of the Diffusion Process**<br>*Zhaoyang Lyu, Xudong XU, Ceyuan Yang, Dahua Lin, Bo Dai*|[Paper](https://arxiv.org/abs/2205.12524)|
|arXiv 2022|**Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation**<br>*Vikram Voleti, Alexia Jolicoeur-Martineau, Christopher Pal*|[Paper](https://arxiv.org/abs/2205.09853)<br>[Project](https://mask-cond-video-diffusion.github.io/)|
|arXiv 2022|**Flexible Diffusion Modeling of Long Videos**<br>*William Harvey, Saeid Naderiparizi, Vaden Masrani, Christian Weilbach, Frank Wood*|[Paper](https://arxiv.org/abs/2205.11495)|
|arXiv 2022|**Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding**<br>*Chitwan Saharia, William Chan, Saurabh Saxena, Lala Li, Jay Whang, Emily Denton, Seyed Kamyar Seyed Ghasemipour, Burcu Karagol Ayan, S. Sara Mahdavi, Rapha Gontijo Lopes, Tim Salimans, Jonathan Ho, David J Fleet, Mohammad Norouzi*|[Paper](https://arxiv.org/abs/2205.11487)|
|arXiv 2022|**Subspace Diffusion Generative Models**<br>*Bowen Jing, Gabriele Corso, Renato Berlinghieri, Tommi Jaakkola*|[Paper](https://arxiv.org/abs/2205.01490)<br>[PyTorch](https://github.com/bjing2016/subspace-diffusion)|
|arXiv 2022|**Fast Sampling of Diffusion Models with Exponential Integrator**<br>*Qinsheng Zhang, Yongxin Chen*|[Paper](https://arxiv.org/abs/2204.13902)|
|arXiv 2022|**Retrieval-Augmented Diffusion Models**<br>*Andreas Blattmann, Robin Rombach, Kaan Oktay, Björn Ommer*|[Paper](https://arxiv.org/abs/2204.11824)|
|arXiv 2022|**Hierarchical Text-Conditional Image Generation with CLIP Latents**<br>*Aditya Ramesh, Prafulla Dhariwal, Alex Nichol, Casey Chu, Mark Chen*|[Paper](https://arxiv.org/abs/2204.06125)|
|arXiv 2022|**Truncated Diffusion Probabilistic Models**<br>*Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou*|[Paper](https://arxiv.org/abs/2202.09671)|
|arXiv 2022|**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models**<br>*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe C. Cattin*|[Paper](https://arxiv.org/abs/2204.02641)|
|arXiv 2022|**Dual Diffusion Implicit Bridges for Image-to-Image Translation**<br>*Xuan Su, Jiaming Song, Chenlin Meng, Stefano Ermon*|[Paper](https://arxiv.org/abs/2203.08382)|
| arXiv 2022 | __DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents__<br>*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* | [Paper](https://arxiv.org/abs/2201.00308)<br/>[PyTorch](https://github.com/kpandey008/DiffuseVAE) |
|arXiv 2022|**Diffusion Probabilistic Modeling for Video Generation**<br>*Ruihan Yang, Prakhar Srivastava, Stephan Mandt*|[Paper](https://arxiv.org/abs/2203.09481)|
| arXiv 2021 | __More Control for Free! Image Synthesis with Semantic Diffusion Guidance__<br>*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* | [Paper](https://arxiv.org/abs/2112.05744)<br/>[Project](https://xh-liu.github.io/sdg/) |
|arXiv 2021|**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models**<br>*Boah Kim, Inhwa Han, Jong Chul Ye*|[Paper](https://arxiv.org/abs/2112.05149)|
| arXiv 2021 | __Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation__<br>*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* |          [Paper](https://arxiv.org/abs/2112.01799)           |
| arXiv 2021 | __Conditional Image Generation with Score-Based Diffusion Models__<br>*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* |          [Paper](https://arxiv.org/abs/2111.13606)           |
|arXiv 2021|**SegDiff: Image Segmentation with Diffusion Probabilistic Models**<br>*Tomer Amit, Eliya Nachmani, Tal Shaharbany, Lior Wolf*|[Paper](https://arxiv.org/abs/2112.00390)|
|arXiv 2021|**Palette: Image-to-Image Diffusion Models**<br>*Chitwan Saharia, William Chan, Huiwen Chang, Chris A. Lee, Jonathan Ho, Tim Salimans, David J. Fleet, Mohammad Norouzi*|[Paper](https://arxiv.org/abs/2111.05826)<br>[Project](https://iterative-refinement.github.io/palette/)|
|arXiv 2021|**UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models**<br>*Hiroshi Sasaki, Chris G. Willcocks, Toby P. Breckon*|[Paper](https://arxiv.org/abs/2104.05358)|

## Tutorials

- Denoising Diffusion-based Generative Modeling: Foundations and Applications, _CVPR 2022_. [Website](https://cvpr2022-tutorial-diffusion-models.github.io/)

## Blogs

- What are Diffusion Models? _Lilian Weng_. [Website](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)