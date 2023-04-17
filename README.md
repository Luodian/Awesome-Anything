# Awesome-Anything
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Awesome Anything](https://img.shields.io/badge/Awesome-Anything-blue)](https://github.com/topics/awesome)

A curated list of **general AI methods for Anything**: AnyObject, AnyGeneration, AnyModel, AnyTask, etc.

[Contributions](https://github.com/VainF/Awesome-Anything/pulls) are welcome!

- [Awesome-Anything](#awesome-anything)
  - [AnyObject](#anyobject) - Segmentation, Detection, Classification, Medical Image, OCR, etc.
  - [AnyGeneration](#anygeneration) - Text-to-Image Generation, Editing, Inpainting, 3D, Style Transfer, etc.
  - [AnyModel](#anymodel) - Any Pruning, Any Quantization, Model Reuse.
  - [AnyTask](#anytask) - LLM Controller + ModelZoo, General Decoding, Multi-Task Learning.
  - [AnyX](#anyx) - Other Topics: Captioning, etc.
  - [Paper List](#paper-list-for-anything-ai)
  
## AnyObject

| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [![Star](https://img.shields.io/github/stars/facebookresearch/segment-anything.svg?style=social&label=Star)](https://github.com/facebookresearch/segment-anything) <br> [**Segment Anything**](https://arxiv.org/abs/2304.02643) <br> *Alexander Kirillov, Eric Mintun, Nikhila Ravi, Hanzi Mao, Chloe Rolland, Laura Gustafson, Tete Xiao, Spencer Whitehead, Alex Berg, Wan-Yen Lo, Piotr Dollar, Ross Girshick* <br> > Meta Research <br> > Preprint'23 <br><br> [[**Segment Anything (Project)**](https://github.com/facebookresearch/segment-anything)] | ![intro](https://github.com/facebookresearch/segment-anything/blob/main/assets/masks2.jpg?raw=true) | [[Github](https://github.com/facebookresearch/segment-anything)] <br> [[Page](https://segment-anything.com/)] <br> [[Demo](https://segment-anything.com/demo)] |
| [![Star](https://img.shields.io/github/stars/facebookresearch/ov-seg.svg?style=social&label=Star)](https://github.com/facebookresearch/ov-seg) <br> [**OVSeg: Open-Vocabulary Semantic Segmentation with Mask-adapted CLIP**](https://arxiv.org/abs/2210.04150) <br> *Feng Liang, Bichen Wu, Xiaoliang Dai, Kunpeng Li, Yinan Zhao, Hang Zhang, Peizhao Zhang, Peter Vajda, Diana Marculescu* <br> > Meta Research <br> > Preprint'23 <br><br> [[**OVSeg (Project)**](https://github.com/facebookresearch/segment-anything)] | <img width="855" alt="image" src="https://user-images.githubusercontent.com/18592211/232279307-cf00ebe2-0751-48dc-b4ac-47ff343c28dc.png"> | [[Github](https://github.com/facebookresearch/ov-seg)] <br> [[Page](https://jeff-liangf.github.io/projects/ovseg/)]  |
| [![Star](https://img.shields.io/github/stars/facebookresearch/ov-seg.svg?style=social&label=Star)](https://github.com/ronghanghu/seg_every_thing) <br> [**Learning to Segment Every Thing**](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Learning_to_Segment_CVPR_2018_paper.pdf) <br> *Ronghang Hu, Piotr Dollar, Kaiming He, Trevor Darrell, Ross Girshick<br> > UC Berkeley, FAIR <br> > CVPR'18 <br><br> [[**seg_every_thing (Project)**](https://github.com/ronghanghu/seg_every_thing)] | <img width="989" alt="image" src="https://user-images.githubusercontent.com/18592211/232575250-4e6fa0cf-507b-40bb-b71b-c0bcc2a85aaf.png"> | [[Github](https://github.com/ronghanghu/seg_every_thing)] <br> [[Page](https://github.com/ronghanghu/seg_every_thing)]  |
| [![Star](https://img.shields.io/github/stars/IDEA-Research/Grounded-Segment-Anything.svg?style=social&label=Star)](https://github.com/IDEA-Research/Grounded-Segment-Anything) <br> [**Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection**](https://arxiv.org/abs/2303.05499) <br> *Shilong Liu and Zhaoyang Zeng and Tianhe Ren and Feng Li and Hao Zhang and Jie Yang and Chunyuan Li and Jianwei Yang and Hang Su and Jun Zhu and Lei Zhang* <br> > IDEA-Research <br> > Preprint'23 <br><br> [[**Grounded-SAM**](https://github.com/IDEA-Research/Grounded-Segment-Anything), [**GroundingDINO (Project)**](https://github.com/IDEA-Research/GroundingDINO)] | ![intro](https://github.com/IDEA-Research/Grounded-Segment-Anything/raw/main/assets/grounded_sam_demo3_demo4.png) | [[Github](https://github.com/IDEA-Research/Grounded-Segment-Anything)] <br> [[Demo](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/zero-shot-object-detection-with-grounding-dino.ipynb)] |
| [![Star](https://img.shields.io/github/stars/baaivision/Painter.svg?style=social&label=Star)](https://github.com/baaivision/Painter)  <br> [**SegGPT: Segmenting Everything In Context**](https://arxiv.org/abs/2304.03284) <br> *Xinlong Wang, Xiaosong Zhang, Yue Cao, Wen Wang, Chunhua Shen, Tiejun Huang* <br> > BAAI-Vision <br> > Preprint'23 <br><br>[[**SegGPT (Project)**](https://github.com/baaivision/Painter)] | <img width="903" alt="image" src="https://user-images.githubusercontent.com/18592211/230897227-c797f375-a44d-4536-a06b-41f0d9f4dbc4.png"> | [[Github](https://github.com/baaivision/Painter)] |
| [**V3Det: Vast Vocabulary Visual Detection Dataset**](https://arxiv.org/abs/2304.03752) <br> *Jiaqi Wang, Pan Zhang, Tao Chu, Yuhang Cao, Yujie Zhou, Tong Wu, Bin Wang, Conghui He, Dahua Lin* <br> > Shanghai AI Laboratory, CUHK <br> > Preprint'23  | ![image](https://user-images.githubusercontent.com/18592211/230936730-4837c3ea-1af5-470c-8532-d0d7bd245df7.png) | -- |
| [![Star](https://img.shields.io/github/stars/kadirnar/segment-anything-video.svg?style=social&label=Star)](https://github.com/kadirnar/segment-anything-video)  <br> [**segment-anything-video (Project)**](https://github.com/kadirnar/segment-anything-video) <br> Kadir Nar | ![intro](https://github.com/kadirnar/segment-anything-pip/releases/download/v0.2.2/metaseg_demo.gif)  | [[Github](https://github.com/kadirnar/segment-anything-video)] |
| [![Star](https://img.shields.io/github/stars/achalddave/segment-any-moving.svg?style=social&label=Star)](https://github.com/achalddave/segment-any-moving) <br> [**Towards Segmenting Anything That Moves**](https://arxiv.org/abs/1902.03715) <br> *Achal Dave, Pavel Tokmakov, Deva Ramanan* <br> > ICCV'19 Workshop <br><br> [[**segment-any-moving (Project)**](https://github.com/achalddave/segment-any-moving)] | [<img src="http://www.achaldave.com/projects/anything-that-moves/videos/ZXN6A-tracked-with-objectness-trimmed.gif" width="32%" />](http://www.achaldave.com/projects/anything-that-moves/videos/ZXN6A-tracked-with-objectness-trimmed.mp4)[<img src="http://www.achaldave.com/projects/anything-that-moves/videos/c95cd17749.gif" width="32%" />](http://www.achaldave.com/projects/anything-that-moves/videos/c95cd17749.mp4)<img src="http://www.achaldave.com/projects/anything-that-moves/videos/e0bdb5dfae.gif" width="32%" /> | [[Github](https://github.com/achalddave/segment-any-moving)] |
| [![Star](https://img.shields.io/github/stars/fudan-zvg/Semantic-Segment-Anything.svg?style=social&label=Star)](https://github.com/fudan-zvg/Semantic-Segment-Anything) <br> [**Semantic Segment Anything**](https://github.com/fudan-zvg/Semantic-Segment-Anything) <br> *Jiaqi Chen, Zeyu Yang, Li Zhang* <br><br> [[**Semantic-Segment-Anything (Project)**](https://github.com/fudan-zvg/Semantic-Segment-Anything)] | <img width="903" alt="image" src="https://github.com/fudan-zvg/Semantic-Segment-Anything/blob/main/figures/SSA_motivation.png"> | [[Github](https://github.com/fudan-zvg/Semantic-Segment-Anything)] |
| [![Star](https://img.shields.io/github/stars/Cheems-Seminar/segment-anything-and-name-it.svg?style=social&label=Star)](https://github.com/Cheems-Seminar/segment-anything-and-name-it) <br> [Grounded Segment Anything: From Objects to **Parts** (Project)](https://github.com/Cheems-Seminar/segment-anything-and-name-it) <br> *Peize Sun* and *Shoufa Chen* | ![intro](https://github.com/Cheems-Seminar/segment-anything-and-name-it/raw/main/assets/logo.png) | [[Github](https://github.com/Cheems-Seminar/segment-anything-and-name-it)]
| [![Star](https://img.shields.io/github/stars/caoyunkang/GroundedSAM-zero-shot-anomaly-detection.svg?style=social&label=Star)](https://github.com/caoyunkang/GroundedSAM-zero-shot-anomaly-detection) <br>  [**GroundedSAM-zero-shot-anomaly-detection (Project)**](https://github.com/caoyunkang/GroundedSAM-zero-shot-anomaly-detection) <br> *Yunkang Cao*  | <img width="677" alt="image" src="https://user-images.githubusercontent.com/18592211/231068964-ddeae0ea-4e83-40d6-b73e-2811d46f808d.png"> | [[Github](https://github.com/caoyunkang/GroundedSAM-zero-shot-anomaly-detection)] |
| [![Star](https://img.shields.io/github/stars/anuragxel/salt.svg?style=social&label=Star)](https://github.com/anuragxel/salt) <br> [**Segment Anything Labelling Tool (SALT) (Project)**](https://github.com/anuragxel/salt) <br> *Anurag Ghosh*  | ![intro](https://github.com/anuragxel/salt/raw/main/assets/how-it-works.gif) | [[Github](https://github.com/caoyunkang/GroundedSAM-zero-shot-anomaly-detection)] |
| [![Star](https://img.shields.io/github/stars/RockeyCoss/Prompt-Segment-Anything.svg?style=social&label=Star)](https://github.com/RockeyCoss/Prompt-Segment-Anything) <br> [**Prompt-Segment-Anything (Project)**](https://github.com/RockeyCoss/Prompt-Segment-Anything) <br> *Rockey*  | ![intro](https://github.com/RockeyCoss/Prompt-Segment-Anything/raw/master/assets/example1.jpg) | [[Github](https://github.com/RockeyCoss/Prompt-Segment-Anything)]|
| [![Star](https://img.shields.io/github/stars/Li-Qingyun/sam-mmrotate.svg?style=social&label=Star)](https://github.com/Li-Qingyun/sam-mmrotate) <br> [**SAM-RBox (Project)**](https://github.com/Li-Qingyun/sam-mmrotate) <br> *Qingyun Li*  | ![intro](https://user-images.githubusercontent.com/79644233/230732578-649086b4-7720-4450-9e87-25873bec07cb.png) | [[Github](https://github.com/Li-Qingyun/sam-mmrotate)] |
| [![Star](https://img.shields.io/github/stars/BingfengYan/VISAM.svg?style=social&label=Star)](https://github.com/BingfengYan/VISAM) <br>  [**VISAM (Project)**](https://github.com/BingfengYan/VISAM) <br> *Feng Yan, Weixin Luo, Yujie Zhong, Yiyang Gan, Lin Ma* | ![intro](https://raw.githubusercontent.com/BingfengYan/MOTSAM/main/tmp.gif) | [[Github](https://github.com/BingfengYan/VISAM)] <br> |
| [![Star](https://img.shields.io/github/stars/aliaksandr960/segment-anything-eo.svg?style=social&label=Star)](https://github.com/aliaksandr960/segment-anything-eo) <br> [**Segment Anything EO tools: Earth observation tools for Meta AI Segment Anything (Project)**](https://github.com/aliaksandr960/segment-anything-eo) <br> *Aliaksandr Hancharenka, Alexander Chichigin*  | ![intro](https://github.com/aliaksandr960/segment-anything-eo/raw/main/title_sameo.png?raw=true) | [[Github](https://github.com/aliaksandr960/segment-anything-eo)] |
| [![Star](https://img.shields.io/github/stars/JoOkuma/napari-segment-anything.svg?style=social&label=Star)](https://github.com/JoOkuma/napari-segment-anything) <br> [**napari-segment-anything: Segment Anything Model (SAM) native Qt UI (Project)**](https://github.com/JoOkuma/napari-segment-anything) <br> *Jordão Bragantini, Kyle I S Harrington, Ajinkya Kulkarni*  | <img width="658" alt="image" src="https://user-images.githubusercontent.com/18592211/231413725-661fb2a9-1951-40b1-8239-6896eeb7eb4c.png"> | [[Github](https://github.com/JoOkuma/napari-segment-anything)] |
| [![Star](https://img.shields.io/github/stars/amine0110/SAM-Medical-Imaging.svg?style=social&label=Star)](https://github.com/amine0110/SAM-Medical-Imaging) <br> [**SAM-Medical-Imaging: Segment Anything Model (SAM) native Qt UI (Project)**](https://github.com/amine0110/SAM-Medical-Imaging) <br> *Jordão Bragantini, Kyle I S Harrington, Ajinkya Kulkarni*  | ![image](https://user-images.githubusercontent.com/18592211/231660993-4b7fbdc8-8f0d-44ab-b8f4-1b330f9168e5.png) | [[Github](https://github.com/amine0110/SAM-Medical-Imaging)] |
| [![Star](https://img.shields.io/github/stars/yeungchenwa/OCR-SAM.svg?style=social&label=Star)](https://github.com/yeungchenwa/OCR-SAM) <br> [**OCR-SAM: Combining MMOCR with Segment Anything & Stable Diffusion. (Project)**](https://github.com/yeungchenwa/OCR-SAM) <br> *Zhenhua Yang, Qing Jiang*  | ![image](https://github.com/yeungchenwa/OCR-SAM/raw/main/imgs/sam_vis.png) | [[Github](https://github.com/yeungchenwa/OCR-SAM)] |
| [![Star](https://img.shields.io/github/stars/Maybeshewill-CV/segment-anything-u-specify.svg?style=social&label=Star)](https://github.com/MaybeShewill-CV/segment-anything-u-specify) <br> [**segment-anything-u-specify: using sam+clip to segment any objs u specify with text prompts. (Project)**](https://github.com/MaybeShewill-CV/segment-anything-u-specify) <br> *MaybeShewill-CV* | ![image](https://github.com/MaybeShewill-CV/segment-anything-u-specify/blob/main/data/resources/test_baseball_insseg_result.jpg) | [[Github](https://github.com/MaybeShewill-CV/segment-anything-u-specify)] |
| [![Star](https://img.shields.io/github/stars/dvlab-research/3D-Box-Segment-Anything.svg?style=social&label=Star)](https://github.com/dvlab-research/3D-Box-Segment-Anything) <br> [**3D-Box via Segment Anything. (Project)**](https://github.com/dvlab-research/3D-Box-Segment-Anything) <br> *dvlab-research* | ![image](https://github.com/dvlab-research/3D-Box-Segment-Anything/raw/main/images/sam-voxelnext.png) | [[Github](https://github.com/dvlab-research/3D-Box-Segment-Anything)] |
| [![Star](https://img.shields.io/github/stars/UX-Decoder/Segment-Everything-Everywhere-All-At-Once.svg?style=social&label=Star)](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once) <br> [**Segment Everything Everywhere All at Once**](https://arxiv.org/abs/2304.06718) <br> *Xueyan Zou, Jianwei Yang, Hao Zhang, Feng Li, Linjie Li, Jianfeng Gao, Yong Jae Lee* <br><br> [[SEEM (Project)](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)] | ![image](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once/raw/main/assets/referring_video_visualize.png?raw=true) | [[Github](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)] |
| [![Star](https://img.shields.io/github/stars/lujiazho/SegDrawer.svg?style=social&label=Star)](https://github.com/lujiazho/SegDrawer) <br> [**SegDrawer: Simple static web-based mask drawer (Project)**](https://github.com/lujiazho/SegDrawer) <br> *Harry* | ![image](https://github.com/lujiazho/SegDrawer/raw/main/example/demo1.gif) | [[Github](https://github.com/lujiazho/SegDrawer)] |
| [![Star](https://img.shields.io/github/stars/kevmo314/magic-copy.svg?style=social&label=Star)](https://github.com/kevmo314/magic-copy) <br> [**Magic Copy: a Chrome extension  (Project)**](https://github.com/kevmo314/magic-copy) <br> *Harry* | <img width="546" alt="image" src="https://user-images.githubusercontent.com/18592211/232190851-1dc85342-3d50-42a7-a8e2-f45c4c862d70.png"> | [[Github](https://github.com/kevmo314/magic-copy)] |
| [![Star](https://img.shields.io/github/stars/gaomingqi/Track-Anything.svg?style=social&label=Star)](https://github.com/gaomingqi/Track-Anything) <br> [**Track-Anything (Project)**](https://github.com/gaomingqi/Track-Anything) <br> *Mingqi Gao* | <img width="545" alt="image" src="https://user-images.githubusercontent.com/18592211/232538442-2af90c47-9122-489e-b054-8ee2f43467be.png"> | [[Github](https://github.com/gaomingqi/Track-Anything)]|
| [![Star](https://img.shields.io/github/stars/ylqi/Count-Anything.svg?style=social&label=Star)](https://github.com/ylqi/Count-Anything) <br> [**Count Anything (Project)**](https://github.com/ylqi/Count-Anything) <br> *Liqi Yan* | <img width="549" alt="image" src="https://user-images.githubusercontent.com/18592211/232305466-ad68546f-b5b1-4c2a-a543-78dea66c7151.png"> | [[Github](https://github.com/ylqi/Count-Anything)]|



<br><br>

## AnyGeneration
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [![Star](https://img.shields.io/github/stars/CompVis/stable-diffusion.svg?style=social&label=Star)](https://github.com/CompVis/stable-diffusion) <br>  [**High-Resolution Image Synthesis with Latent Diffusion Models**](https://arxiv.org/abs/2112.10752) <br> *Robin Rombach and Andreas Blattmann and Dominik Lorenz and Patrick Esser and Björn Ommer* <br> > LMU München, Runway ML <br> > CVPR'22 <br><br> [[**Stable-Diffusion (Project)**](https://github.com/CompVis/stable-diffusion)] | ![intro](https://r2.stablediffusionweb.com/images/stable-diffusion-demo-2.webp) | [[Github](https://github.com/CompVis/stable-diffusion)] <br> [[Page](https://stablediffusionweb.com/)] <br> [[Demo](https://stablediffusionweb.com/#demo)] |
| [![Star](https://img.shields.io/github/stars/lllyasviel/ControlNet.svg?style=social&label=Star)](https://github.com/lllyasviel/ControlNet) <br> [**Adding Conditional Control to Text-to-Image Diffusion Models**](https://arxiv.org/abs/2302.05543) <br> *Lvmin Zhang, Maneesh Agrawala* <br> > Stanford University <br> > Preprint'23 <br><br> [[**ControlNet (Project)**](https://github.com/lllyasviel/ControlNet)] | ![intro](https://huggingface.co/datasets/YiYiXu/test-doc-assets/resolve/main/blog_post_cell_16_output_1.jpeg) | [[Github](https://github.com/lllyasviel/ControlNet)] <br>  [[Demo](https://huggingface.co/spaces/hysts/ControlNet)] |
| [**GigaGAN: Large-scale GAN for Text-to-Image Synthesis**](https://arxiv.org/abs/2303.05511) <br> *Minguk Kang, Jun-Yan Zhu, Richard Zhang, Jaesik Park, Eli Shechtman, Sylvain Paris, Taesung Park* <br> > POSTECH, Carnegie Mellon University, Adobe Research <br> > CVPR'23 | <img alt="image" src="https://user-images.githubusercontent.com/18592211/230898538-84da51ee-f686-422d-9892-c1c47ab10b75.png"></img> | [[Page](https://mingukkang.github.io/GigaGAN/)] |
| [![Star](https://img.shields.io/github/stars/geekyutao/Inpaint-Anything.svg?style=social&label=Star)](https://github.com/geekyutao/Inpaint-Anything) <br> [**Inpaint-Anything: Segment Anything Meets Image Inpainting (Project)**](https://github.com/geekyutao/Inpaint-Anything) <br> *Tao Yu*  | ![intro](https://github.com/geekyutao/Inpaint-Anything/raw/main/example/MainFramework.png) | [[Github](https://github.com/geekyutao/Inpaint-Anything)] |
| [![Star](https://img.shields.io/github/stars/feizc/IEA.svg?style=social&label=Star)](https://github.com/feizc/IEA) <br> [**IEA: Image Editing Anything (Project)**](https://github.com/feizc/IEA) <br> *Zhengcong Fei*  | ![intro](https://user-images.githubusercontent.com/37614046/230707537-206c0714-de32-41cd-a277-203fd57cd300.png) | [[Github](https://github.com/feizc/IEA)] |
| [![Star](https://img.shields.io/github/stars/sail-sg/EditAnything.svg?style=social&label=Star)](https://github.com/sail-sg/EditAnything) <br> [**EditAnything (Project)**](https://github.com/sail-sg/EditAnything) <br> *Shanghua Gao, Pan Zhou*  | ![intro](https://github.com/sail-sg/EditAnything/raw/main/images/edit_sample1.jpg) | [[Github](https://github.com/sail-sg/EditAnything)] |
| [![Star](https://img.shields.io/github/stars/continue-revolution/sd-webui-segment-anything.svg?style=social&label=Star)](https://github.com/continue-revolution/sd-webui-segment-anything) <br> [**Segment Anything for Stable Diffusion Webui (Project)**](https://github.com/continue-revolution/sd-webui-segment-anything) <br> *Chengsong Zhang*  | <img width="659" alt="image" src="https://user-images.githubusercontent.com/18592211/231410895-eac4c4b6-ee61-487b-9333-8dcd1befc610.png"> | [[Github](https://github.com/continue-revolution/sd-webui-segment-anything)] |
| [![Star](https://img.shields.io/github/stars/Curt-Park/segment-anything-with-clip.svg?style=social&label=Star)](https://github.com/Curt-Park/segment-anything-with-clip) <br> [**Segment Anything with Clip (Project)**](https://github.com/Curt-Park/segment-anything-with-clip) <br> *Jinwoo Park*  | ![intro](https://user-images.githubusercontent.com/14961526/230437084-79ef6e02-a254-421e-bd4c-32e87415c623.png) | [[Github](https://github.com/Curt-Park/segment-anything-with-clip)] |
| [![Star](https://img.shields.io/github/stars/showlab/ShowAnything.svg?style=social&label=Star)](https://github.com/showlab/ShowAnything) <br>[**ShowAnything: Edit and Generate Anything In Image and Video (Project)**](https://github.com/showlab/ShowAnything) <br> *Showlab, NUS* | ![intro](https://github.com/showlab/ShowAnything/blob/main/assets/video/showcase_3.gif) | [Github](https://github.com/showlab/ShowAnything) |
| [![Star](https://img.shields.io/github/stars/Anything-of-anything/Anything-3D.svg?style=social&label=Star)](https://github.com/Anything-of-anything/Anything-3D) <br>[**Anything-3D: Segment-Anything + 3D, Let's lift the anything to 3D (Project)**](https://github.com/Anything-of-anything/Anything-3D) <br> *LV-Lab, NUS* | ![intro](https://github.com/Anything-of-anything/Anything-3D/raw/main/novel-view/assets/3.jpeg) <br> ![intro2](https://github.com/Anything-of-anything/Anything-3D/raw/main/novel-view/assets/2.jpeg) | [Github](https://github.com/Anything-of-anything/Anything-3D) |
| [![Star](https://img.shields.io/github/stars/Huage001/Transfer-Any-Style.svg?style=social&label=Star)](https://github.com/Huage001/Transfer-Any-Style) <br>[**Transfer-Any-Style: About An interactive demo based on Segment-Anything for style transfer (Project)**](https://github.com/Huage001/Transfer-Any-Style) <br> *LV-Lab, NUS* |  ![intro](https://github.com/Huage001/Transfer-Any-Style/raw/main/picture/demo1.gif) | [Github](https://github.com/Huage001/Transfer-Any-Style) |
| [![Star](https://img.shields.io/github/stars/nexuslrf/SAM-3D-Selector.svg?style=social&label=Star)](https://github.com/nexuslrf/SAM-3D-Selector) <br>[**SAM 3D Selector: Utilizing segment-anything to help the region selection of 3D point cloud or mesh. (Project)**](https://github.com/Huage001/Transfer-Any-Style) <br> *Nexuslrf* |  ![intro](https://github.com/nexuslrf/SAM-3D-Selector/raw/main/figs/demo_1.gif) | [Github](https://github.com/nexuslrf/SAM-3D-Selector) |

<br><br>

## AnyModel
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [![Star](https://img.shields.io/github/stars/VainF/Torch-Pruning.svg?style=social&label=Star)](https://github.com/VainF/Torch-Pruning) <br> [**DepGraph: Towards Any Structural Pruning**](https://arxiv.org/abs/2301.12900) <br> *Gongfan Fang, Xinyin Ma, Mingli Song, Michael Bi Mi, Xinchao Wang* <br>  > Learning and Vision Lab @ NUS<br> > CVPR'23 <br><br> [[**Torch-Pruning (Project)**](https://github.com/VainF/Torch-Pruning)] | ![intro](https://github.com/VainF/Torch-Pruning/raw/master/assets/intro.png) | [[Github](https://github.com/VainF/Torch-Pruning)] <br> [[Demo](https://colab.research.google.com/drive/1TRvELQDNj9PwM-EERWbF3IQOyxZeDepp?usp=sharing)] |
| [![Star](https://img.shields.io/github/stars/ModelTC/MQBench.svg?style=social&label=Star)](https://github.com/ModelTC/MQBench) <br> [**MQBench: Towards Reproducible and Deployable Model Quantization Benchmark**](https://arxiv.org/abs/2111.03759) <br> *Yuhang Li and Mingzhu Shen and Jian Ma and Yan Ren and Mingxin Zhao and Qi Zhang and Ruihao Gong and Fengwei Yu and Junjie Yan* <br> > SenseTime Research <br> > NeurIPS'21 <br><br> [[**MQBench (Project)**](https://github.com/ModelTC/MQBench)] | ![intro](http://mqbench.tech/assets/img/overview.png) | [[Github](https://github.com/ModelTC/MQBench)] <br> [[Page](http://mqbench.tech/)] |
| [![Star](https://img.shields.io/github/stars/tianyic/only_train_once.svg?style=social&label=Star)](https://github.com/tianyic/only_train_once) <br> [**OTOv2: Automatic, Generic, User-Friendly**](https://openreview.net/pdf?id=7ynoX1ojPMt) <br> *Tianyi Chen, Luming Liang, Tianyu Ding, Ilya Zharkov* <br>  > Microsoft <br> > ICLR'23 <br><br> [[**Only Train Once (Project)**](https://github.com/tianyic/only_train_once)] | ![intro](https://user-images.githubusercontent.com/8930611/230513048-e07b09a2-b29b-49ad-a47f-52630337ab2a.png) | [[Github](https://github.com/tianyic/only_train_once)] |
| [![Star](https://img.shields.io/github/stars/Adamdad/DeRy.svg?style=social&label=Star)](https://github.com/Adamdad/DeRy) <br> [**Deep Model Reassembly**](https://arxiv.org/abs/2210.17409) <br> *Xingyi Yang, Daquan Zhou, Songhua Liu, Jingwen Ye, Xinchao Wang* <br> LV Lab, NUS <br> > NeurIPS'22 <br><br> [[**Deep Model Reassembly (Project)**](https://github.com/Adamdad/DeRy)] <br> | ![intro](https://github.com/Adamdad/DeRy/raw/main/assets/pipeline.png) | [[Github](https://github.com/Adamdad/DeRy)] <br> [[Page](https://adamdad.github.io/dery/)] |


<br><br>

## AnyTask
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS) <br> [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace**](https://arxiv.org/abs/2303.17580) <br> *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* <br> > Zhejiang University, MSRA <br> Preprint'23 <br><br> [[**Jarvis (Project)**](https://github.com/microsoft/JARVIS)] |  <img  src="https://github.com/microsoft/JARVIS/raw/main/assets/overview.jpg"><img> | [[Github](https://github.com/microsoft/JARVIS)] <br> [[Demo](https://huggingface.co/spaces/microsoft/HuggingGPT)] |
| [**TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs**](https://arxiv.org/abs/2303.16434) <br> *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan* <br> > Microsoft <br> > > Preprint'23 | ![intro](https://github.com/microsoft/visual-chatgpt/raw/main/assets/overview.png) | [[Github](https://github.com/microsoft/visual-chatgpt/tree/main/TaskMatrix.AI)] |
| [![Star](https://img.shields.io/github/stars/microsoft/X-Decoder.svg?style=social&label=Star)](https://github.com/microsoft/X-Decoder) <br> [**Generalized Decoding for Pixel, Image and Language**](https://arxiv.org/abs/2212.11270) <br> *Xueyan Zou, Zi-Yi Dou, Jianwei Yang, Zhe Gan, Linjie Li, Chunyuan Li, Xiyang Dai, Harkirat Behl, Jianfeng Wang, Lu Yuan, Nanyun Peng, Lijuan Wang, Yong Jae Lee, Jianfeng Gao* <br> > Microsoft <br> > CVPR'23 <br><br> [[**X-Decoder (Project)**](https://github.com/microsoft/X-Decoder/)] | ![intro](https://user-images.githubusercontent.com/11957155/210801832-c9143c42-ef65-4501-95a5-0d54749dcc52.gif)  | [[Github](https://github.com/microsoft/X-Decoder/)] <br> [[Page](https://x-decoder-vl.github.io)] <br> [[Demo](https://huggingface.co/spaces/xdecoder/Demo)]  |
| [![Star](https://img.shields.io/github/stars/huawei-noah/Pretrained-IPT.svg?style=social&label=Star)](https://github.com/huawei-noah/Pretrained-IPT) <br>  [**Pre-Trained Image Processing Transformer**]() <br> *Chen, Hanting and Wang, Yunhe and Guo, Tianyu and Xu, Chang and Deng, Yiping and Liu, Zhenhua and Ma, Siwei and Xu, Chunjing and Xu, Chao and Gao, Wen* <br> > Huawei-Noah <br> > CVPR'21 <br><br> [[**Pretrained-IPT (Project)**](https://github.com/huawei-noah/Pretrained-IPT)] | ![intro](https://github.com/huawei-noah/Pretrained-IPT/raw/main/images/intro.png) | [[Github](https://github.com/huawei-noah/Pretrained-IPT)] |
| [![Star](https://img.shields.io/github/stars/agiresearch/OpenAGI.svg?style=social&label=Star)](https://github.com/agiresearch/OpenAGI) <br>[**OpenAGI: When LLM Meets Domain Experts**](https://arxiv.org/pdf/2304.04370.pdf) <br> *Yingqiang Ge, Wenyue Hua, Jianchao Ji, Juntao Tan, Shuyuan Xu, Yongfeng Zhang* <br> > Rutgers University  <br> > Preprint'23 <br><br> [[**OpenAGI (Project)**](https://github.com/agiresearch/OpenAGI)] | ![intro](https://github.com/agiresearch/OpenAGI/raw/main/image/pipeline.png) | [Github](https://github.com/agiresearch/OpenAGI) |

<br><br>

## AnyX
| Title & Authors | Intro | Useful Links |
|:----|  :----: | :---:|
| [![Star](https://img.shields.io/github/stars/ttengwang/Caption-Anything.svg?style=social&label=Star)](https://github.com/ttengwang/Caption-Anything) <br> [**Caption Anything (Project)**](https://github.com/ttengwang/Caption-Anything) <br> *Teng Wang, Jinrui Zhang, Junjie Fei, Yunlong Tang, Zhe Li, Mingqi Gao*  | ![intro](https://github.com/ttengwang/Caption-Anything/blob/main/Image/demo1.png)  | [[Github](https://github.com/ttengwang/Caption-Anything)] <br> [[Demo](https://huggingface.co/spaces/TencentARC/Caption-Anything)] |
| [![Star](https://img.shields.io/github/stars/showlab/Image2Paragraph.svg?style=social&label=Star)](https://github.com/showlab/Image2Paragraph) <br>[**Image2Paragraph:Transform Image into Unique Paragraph (Project)**](https://github.com/showlab/Image2Paragraph) <br> *Jinpeng Wang* | ![intro](https://github.com/showlab/Image2Paragraph/raw/main/output/2_result.png) | [Github](https://github.com/showlab/Image2Paragraph) |
...

<br><br>

# Paper List for Anything AI

A paper list for Anything AI

## AnyObejct
| Paper | First Author | Venue | Topic |
| :--- | :---: | :--: | :--: |
| [Segment Anything](https://arxiv.org/abs/2304.02643) | Alexander Kirillov | Preprint'23 | Segmentation |
| [Learning to Segment Every Thing](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Learning_to_Segment_CVPR_2018_paper.pdf) | Ronghang Hu | CVPR'18 |
| [Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection](https://arxiv.org/abs/2303.05499) | Shilong Liu | Preprint'23 | Grouding+Detection |
| [SegGPT: Segmenting Everything In Context](https://arxiv.org/abs/2304.03284) | Xinlong Wang | Preprint'23 | Segmentation  |
| [V3Det: Vast Vocabulary Visual Detection Dataset](https://arxiv.org/abs/2304.03752) | Jiaqi Wang | Preprint'23 | Dataset |

## AnyGeneration
| Paper | First Author | Venue | Topic |
| :--- | :---: | :--: | :--: |
| [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) | Robin Rombach | CVPR'22 | Text-to-Image Generation |
| [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543) | Lvmin Zhang | Preprint'23 | Controlllable Generation |
| [GigaGAN: Large-scale GAN for Text-to-Image Synthesis](https://arxiv.org/abs/2303.05511) | Minguk Kang | CVPR'23 | Large-scale GAN |

## AnyModel
| Paper | First Author | Venue | Topic |
| :--- | :---: | :--: | :--: |
| [DepGraph: Towards Any Structural Pruning](https://arxiv.org/abs/2301.12900) | Gongfan Fang | CVPR'23 | Network Pruning |
| [MQBench: Towards Reproducible and Deployable Model Quantization Benchmark](https://arxiv.org/abs/2111.03759) | Yuhang Li | NeurIPS'21 | Network Quantization |
| [OTOv2: Automatic, Generic, User-Friendly](https://openreview.net/pdf?id=7ynoX1ojPMt) | Tianyi Chen | ICLR'23 | Network Pruning |
| [Deep Model Reassembly](https://arxiv.org/abs/2210.17409) | Xingyi Yang | NeurIPS'22 | Model Reuse |

## AnyTask
| Paper | First Author | Venue | Topic |
| :--- | :---: | :--: | :--: |
| [HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace](https://arxiv.org/abs/2303.17580) | Yongliang Shen | Preprint'23 | Modelzoo + LLM |
| [TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs](https://arxiv.org/abs/2303.16434) | Yaobo Liang | Preprint'23 | Modelzoo + LLM |
| [Generalized Decoding for Pixel, Image and Language](https://arxiv.org/abs/2212.11270) | Xueyan Zou | CVPR'23 | Multi Tasking  |
| [Pre-Trained Image Processing Transformer](https://arxiv.org/abs/2012.00364) | Chen, Hanting | CVPR'21 | Low-level Vision |

