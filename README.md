# Awesome-3D-Image-Editing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)&nbsp;</a>![Static Badge](https://img.shields.io/badge/Maintain-yes!-%23727EB4?logo=yes&logoColor=C7A5C0&logoSize=727EB4&label=Maintain&labelColor=%23925D88) <a href="" target='_blank'><img src="https://visitor-badge.laobi.icu/badge?page_id=Cuzyoung.Awesome-3D-Image-Editing&left_color=%23DFA3CB&right_color=%23CEE75F">


<!-- <a href="" target='_blank'><img src="https://visitor-badge.laobi.icu/badge?page_id=Cuzyoung.Awesome-3D-Image-Editing&left_color=%23DFA3CB&right_color=%23CEE75F"> </a>  -->
# 🏡Home
Here is a collection of papers on the topic of 3D Image Editing, which encompasses research on Diffusion Models (DM), Neural Radiance Fields (NeRF), 3D Gaussian Splatting (3DGS) ,Large Language Models (LLMs), Large Multimodal Models (LMMs), Vision Foundation Models (VFMs), and various other methodologies.

## 🌟🌟🌟Updating
[2024-5-24] [Ziyang Gong](https://scholar.google.com/citations?user=cWip8QgAAAAJ&hl=zh-CN&oi=ao) and [Deblina Bhattacharjee](https://scholar.google.com/citations?user=F3YYEmMAAAAJ&hl=zh-CN&oi=ao) curate this collection aiming to help researchers to know the development of this area. This repo also will be continually updating. If you have any question or advice, please feel free to contact us. 

Ziyang Gong📧: gongzy23@sysu.mail2.edu.cn   
Deblina Bhattacharjee📧: deblina.bhattacharjee@epfl.ch

<!-- <a href="" target='_blank'><img src="https://visitor-badge.laobi.icu/badge?page_id=Cuzyoung.Awesome-3D-Image-Editing&left_color=blue&right_color=%23CEE75F"> </a>   -->

# Table of Content
- [Awesome-3D-Image-Editing](#Awesome-3D-Image-Editing)
  - [NeRF-Based](#nerf-based)
  - [Diffusion Model-Based](#diffusion-model-based)
  - [3DGS with Diffusion Models](#3dgs-with-diffusion-models)
  - [NeRF with Diffusion Models](#nerf-with-diffusion-models)
  - [NeRF with Vision Foundation Models](#nerf-with-detection-or-segmentation-models)



# NeRF-Based
| <p align="center"> Date | Institute (first) |<p align="center">Paper Name | <p align="center"> Architecture |<p align="center"> Publication|<p align="center"> Others |
| :-----: | :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------:| :---------:
| 2024 | Tel Aviv |<p align="center"> Consolidating Attention Features for Multi-view Image Editing|  - |[Arxiv](https://arxiv.org/pdf/2402.14792) | [Github](https://qnerf-consolidation.github.io/qnerf-consolidation/) |
| 2023 | SYSU |<p align="center">DreamEditor: Text-Driven 3D Scene Editing with Neural Fields|  - |[SIGGRAPH Asia 2023](https://arxiv.org/pdf/2306.13455) | [Github](https://github.com/zjy526223908/DreamEditor)|
| 2023 | Google|<p align="center"> Zip-NeRF: Anti-Aliased Grid-Based Neural Radiance Fields |  - |[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Barron_Zip-NeRF_Anti-Aliased_Grid-Based_Neural_Radiance_Fields_ICCV_2023_paper.pdf) | - |
| 2023 | UIUC |<p align="center">ViCA-NeRF: View-Consistency-Aware 3D Editing of Neural Radiance Fields|  - |[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/c1e2faff6f588870935f114ebe04a3e5-Paper-Conference.pdf) | [Github](https://github.com/Dongjiahua/VICA-NeRF)|
| 2023 | Samsung |<p align="center">SPIn-NeRF: Multiview Segmentation and Perceptual Inpainting with Neural Radiance Fields |  - |[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Mirzaei_SPIn-NeRF_Multiview_Segmentation_and_Perceptual_Inpainting_With_Neural_Radiance_Fields_CVPR_2023_paper.pdf) | [Github](https://github.com/SamsungLabs/SPIn-NeRF) |
| 2022 | CUHK|<p align="center"> NeRF-Art: Text-Driven Neural Radiance Fields Stylization|  - |[Arxiv](https://arxiv.org/pdf/2212.08070) | [Github](https://github.com/cassiePython/NeRF-Art) |

# Diffusion Model-Based
| <p align="center"> Date | Institute (first) |<p align="center">Paper Name | <p align="center"> Architecture |<p align="center"> Publication|<p align="center"> Others |
| :-----: | :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------:| :---------:
| 2024 | MIT |<p align="center"> Alchemist: Parametric Control of Material Properties with Diffusion Models |  SD |[Arxiv](https://arxiv.org/abs/2312.02970) | [Github](https://www.prafullsharma.net/alchemist/) |
| 2024 | TUM |<p align="center"> LightIt: Illumination Modeling and Control for Diffusion Models |  SD |[CVPR 2024](https://arxiv.org/pdf/2403.10615) | [Github](https://peter-kocsis.github.io/LightIt/) |
| 2024 | SJTU|<p align="center">FocalDreamer: Text-Driven 3D Editing via Focal-Fusion Assembly|  SD |[AAAI 2024](https://ojs.aaai.org/index.php/AAAI/article/download/28113/28230) | [Github](https://github.com/colorful-liyu/focaldreamer)|
| 2023 | AI2 |<p align="center">OBJECT 3DIT: Language-guided 3D-aware Image Editing|  DiT |[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/0b0153a91f827b14e8bfea4e211362f3-Paper-Conference.pdf) | [Page](https://prior.allenai.org/projects/object-edit)|
| 2022 | Google |<p align="center">Prompt-to-Prompt Image Editing with Cross Attention Control |  - |[Arxiv](https://arxiv.org/pdf/2208.01626) | [Github](https://github.com/google/prompt-to-prompt) |

# 3DGS with Diffusion Models
| <p align="center"> Date | Institute (first) |<p align="center">Paper Name | <p align="center"> Architecture |<p align="center"> Publication|<p align="center"> Others |
| :-----: | :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------:| :---------:
| 2024-04 | SYSU+Tencent AI Lab |<p align="center"> TIP-Editor: An Accurate 3D Editor Following Both Text-Prompts And Image-Prompts | 3DGS+SD |[Arxiv](https://arxiv.org/pdf/2401.14828) | [Github](https://github.com/zjy526223908/TIP-Editor) |


# NeRF with Diffusion Models
| <p align="center"> Date | Institute (first) |<p align="center">Paper Name | <p align="center"> Architecture |<p align="center"> Publication|<p align="center"> Others |
| :-----: | :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------:| :---------:
| 2024-04 | USTC |<p align="center"> InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior | NeRF+SD |[Arxiv](https://arxiv.org/pdf/2404.11613) | [Github](https://johanan528.github.io/Infusion/) |
| 2023-12 | Apple |<p align="center"> Efficient-NeRF2NeRF: Streamlining Text-Driven 3D Editing with Multiview Correspondence-Enhanced Diffusion Models | IN2N |[Arxiv](https://arxiv.org/pdf/2312.08563) | [Github](https://lsongx.github.io/projects/en2n.html) |
| 2023-11 | Huawei |<p align="center"> GaussianEditor: Editing 3D Gaussians Delicately with Text Instructions | IN2N |[CVPR 2024](https://arxiv.org/pdf/2303.12048) | [Github](https://gaussianeditor.github.io/) |
| 2023-06 | UCB |<p align="center"> Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions | NeRF+SD |[ICCV 2023 (Oral)](https://arxiv.org/pdf/2303.12789) | [Github](https://instruct-nerf2nerf.github.io/) |
| 2023-03 | Tel Aviv|<p align="center"> Vox-E: Text-guided Voxel Editing of 3D Objects | - |[ICCV 2023](https://arxiv.org/pdf/2303.12048) | [Github](https://github.com/TAU-VAILab/Vox-E?tab=readme-ov-file) |
| 2022 | Google |<p align="center"> DREAMFUSION: TEXT-TO-3D USING 2D DIFFUSION|  - |[Arxiv](https://arxiv.org/pdf/2209.14988) | [Github](https://dreamfusion3d.github.io/) |


# Nerf with Detection or Segmentation Models
| <p align="center"> Date | Institute (first) |<p align="center">Paper Name | <p align="center"> Architecture |<p align="center"> Publication|<p align="center"> Others |
| :-----: | :-------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------:| :---------:
| 2024 | EPFL |<p align="center"> InNeRF360: Text-Guided 3D-Consistent Object Inpainting on 360◦ Neural Radiance Fields | NeRF+Detection+SAM |[CVPR 2024](https://arxiv.org/pdf/2305.15094) | [Github](https://ivrl.github.io/InNeRF360/) |
