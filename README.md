# Multimodal Place Recognition: A Comprehensive Survey
This paper presents a systematic review of multimodal place recognition research.
## Abstract
Place recognition provides global localization cues for Simultaneous Localization and Mapping (SLAM) and serves as a key enabler for autonomous vehicles and mobile robots. However, place recognition approaches dominated by a single sensor modality are inherently constrained by modality-specific limitations, making it difficult to simultaneously satisfy the requirements of accuracy, robustness, and generalization in complex environments. multimodal information fusion has emerged as a mainstream paradigm for overcoming the performance bottlenecks of unimodal methods. Despite the rapid development of this field, a comprehensive survey dedicated to multimodal place recognition (MPR) remains lacking. To bridge this gap, this paper presents a systematic review of MPR research. We first analyze the performance characteristics and complementary properties of core sensing modalities, and clarify their fundamental task formulations. We then establish three representative paradigms from a fusion-oriented perspective: (1) vision-LiDAR fusion, (2) text-involved multimodal fusion, and (3) radar-involved multimodal fusion. we further provide an indepth analysis of their fundamental principles, representative methods, advantages, and limitations. Subsequently, we systematically organize commonly used benchmark datasets, introduce core evaluation metrics, and conduct a comparative analysis of representative approaches. Finally, we discuss the practical significance of MPR in autonomous driving, robotic navigation, and remote sensing-based localization, and outline promising research directions for future exploration.
## Survey Overview
This paper provides a comprehensive review of recent advancements in mutimodal place recognition, focusing on three key methodological paradigms:

1.Vision-LiDAR Fusion

2.Text-Involved Multimodal Fusion

3.Radar-Involved Multimodal Fusion

![Image text](https://github.com/YangShuang168/MPR-Survey/blob/main/01%20structure%20of%20MPR-Survey.jpg)

## 📊 Structure of MPR Survey

[![Preview](./01%20structure%20of%20MPR-Survey.jpg)](./01%20Structure%20of%20MPR-Survey.pdf)

## All the methods are listed below:
### 1.  Vision-LiDAR Fusion
#### 1. 1 Basic Feature Fusion
| No. | Title | First Author | Venue | Github |
|--|--|--|--|--|
|1| [Large-scale place recognition based on camera-lidar fused descriptor](https://www.mdpi.com/1424-8220/20/10/2870) | Shaorong Xie | Sensors |  |
|2| [Robust place recognition based on multi-sensor fusion](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9588194) | Hao Gu | CYBER|  |
|3| [MinkLoc++: Lidar and monocular image fusion for place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9533373) | Jacek Komorowski | IJCNN | [Github](https://github.com/jac99/MinkLocMultimodal) |
|4| [MMDF: Multi-modal deep feature based place recognition of mobile robots with applications on cross-scene navigation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9781852) | Xiang Yu | IEEE Robotics and Automation Letters |  |
|5| [A Fast LiDAR Place Recognition Descriptor Based on Density Classification and Multi-Modal Fusion Place Recognition Strategy](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11155160) | Guoliang Yu | IEEE Robotics and Automation Letters |  |
#### 1. 2 Cross-Modal Interaction-Enhanced Fusion
| No. | Title | First Author | Venue | Github |
|--|--|--|--|--|
|1|[PIC-Net: Point cloud and image collaboration network for large-scale place recognition](https://arxiv.org/pdf/2008.00658) | Yuheng Lu | arXiv |  |
|2| [Spherical multi-modal place recognition for heterogeneous sensor systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561078) | Lukas Bernreiter | ICRA |  |
|3| [Adafusion: Visual-lidar fusion with adaptive weights for place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9905898) | Haowen Lai | IEEE Robotics and Automation Letters |  |
|4| [Transformer Based Multi-modal Fusion For Place Recognition with Self-attention Mechanism](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10055623) | Yan Pan | CAC |  |
|5| [Camera-LiDAR fusion with latent correlation for cross-scene place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10665753) | Yan Pan | IEEE Transactions on Industrial Electronics |  |
|6| [Attention-enhanced cross-modal localization between spherical images and point clouds](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10227896) | Zhipeng Zhao | IEEE Sensors Journal | [Github](https://github.com/Zhaozhpe/AE-CrossModal) |
|7| [Lcpr: A multi-scale attention-based lidar-camera fusion network for place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10373064) | Zijie Zhou | IEEE Robotics and Automation Letters | [Github](https://github.com/ZhouZijie77/LCPR) |
|8| [Poses as queries: End-to-end image-to-lidar map localization with transformers](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10333977) | Jinyu Miao | IEEE Robotics and Automation Letters |  |
|9| [A hierarchical and multi-modal framework for place recognition with a learnable metric](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10508992) | Chengfu Shu | IEEE Transactions on Intelligent Vehicles | [Github](https://github.com/hhuscf/HMPR) |
|10| [Explicit interaction for fusion-based place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10802665) | Jingyi Xu | IROS | [Github](https://github.com/BIT-XJY/EINet) |
|11| [Lip-loc: Lidar image pretraining for cross-modal localization](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/papers/Shubodh_LIP-Loc_LiDAR_Image_Pretraining_for_Cross-Modal_Localization_WACVW_2024_paper.pdf) | Sai Shubodh Puligilla | WACV |  |
|12| [PRFusion: Toward effective and robust multi-modal place recognition with image and point cloud fusion](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10704955) | Sijie Wang | IEEE Transactions on Intelligent Transportation Systems |  |
|13| [VXP: Voxel-Cross-Pixel Large-Scale Camera-LiDAR Place Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11125591) | YunJin Li | 3DV |[Github](https://github.com/yunjinli/vxp) |
|14| [BdFusion: Bi-directional visual-LiDAR fusion for resilient place recognition](https://www.sciencedirect.com/science/article/abs/pii/S0924271625002849) | Anbang Liang | ISPRS Journal of Photogrammetry and Remote Sensing | [Github](https://github.com/ThomasLiangAB/BdFusion) |
|15|  [Contrastive learning-based place descriptor representation for cross-modality place recognition](https://www.sciencedirect.com/science/article/pii/S1566253525004245)| Shiyu Meng | Information Fusion | [Github](https://github.com/emilyemliyM/Cross-PRNet) |
|16| [CrossBEV-PR: Cross-modal Visual-LiDAR Place Recognition via BEV Feature Distillation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11246576) | Jianbo Xu | IROS | [Github](https://github.com/IRMVLab/CrossBEV-PR) |
|17| [InsCMPR: Efficient Cross-Modal Place Recognition via Instance-Aware Hybrid Mamba-Transformer](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11128210) | Shuaifeng Jiao | ICRA | [Github](https://github.com/nubot-nudt/InsCMPR) |
|18| [Monocular visual place recognition in lidar maps via cross-modal state space model and multi-view matching](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11128591)| Gongxin Yao | ICRA | [Github](https://github.com/y2w-oc/I2P-CMPR) |
#### 1. 3 Modality-Unified Fusion
| No.| Title | First Author | Venue | Github |
|--|--|--|--|--|
| 1| [Rgb2lidar: Towards solving large-scale cross-modal visual localization](https://dl.acm.org/doi/epdf/10.1145/3394171.3413647) | Niluthpol Chowdhury Mithun | ACM MM | [Github](https://github.com/niluthpol/RGB2LIDAR) |
| 2| [Coral: Colored structural representation for bi-modal place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9635839)| Yiyuan Pan | IROS | [Github](https://github.com/Panyiyuan96/CORAL_Pytorch) |
| 3| [(LC)2: LiDAR-camera loop constraints for cross-modal place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10105996) | Alex Junho Lee | IEEE Robotics and Automation Letters |  |
| 4| [Cross-Modal 2D-3D Localization with Single-Modal Query](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10282358) | Zhipeng Zhao | IGARSS |  |
| 5| [I2p-rec: Recognizing images on large-scale point cloud maps through bird's eye view projections](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10341907) | Shuhang Zheng | IROS |  |
| 6| [Toward Precise Ambiguity-Aware Cross-Modality Global Self-Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10151856) | Niklas Stannartz | IEEE Access |  |
| 7| [Cross-modal visual relocalization in prior lidar maps utilizing intensity textures](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801498)| Qiyuan Shen | IROS |  |
| 8| [LHMap-loc: Cross-Modal Monocular Localization Using LiDAR Point Cloud Heat Map](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610718)| Xinrui Wu | ICRA | [Github](https://github.com/IRMVLab/LHMap-loc) |
| 9|  [Modalink: Unifying modalities for efficient image-to-pointcloud place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801556)| Weidong Xie | IROS | [Github](https://github.com/haomo-ai/ModaLink) |
| 10| [C2l-pr: Cross-modal camera-to-lidar place recognition via modality alignment and orientation voting](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10586273) |Huaiyuan Xu |IEEE Transactions on Intelligent Vehicles| [Github](https://github.com/lab-sun/C2L-PR) |
| 11| [Range and Bird's Eye View Fused Cross-Modal Visual Place Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11097657) | Jianyi Peng | IV |  |
| 12| [CrossGLoc: Cross-Modal Global Localization Leveraging Pretrained Diffusion Models and Semantic Cues for Intelligent Vehicles](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11106394) | Hengwang Zhao | IEEE Transactions on Intelligent Transportation Systems |  |
| 13| [Large-Scale Visual Re-localization through Cross-Modality Registration of NeRF and Image Features](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11139475)| Yichen Sha | RCAR |  |
### 2.  Text-Involved Multimodal Fusion
#### 2. 1 Text-Vision Fusion
|No.| Title | First Author | Venue | Github |
|--|--|--|--|--|
|1 | [Tell me where you are: Multimodal llms meet place recognition](https://arxiv.org/pdf/2406.17520)| Zonglin Lyu | arXiv | [Github](https://github.com/ai4ce/LLM4VPR) |
|2| [“where am i?” scene retrieval with language](https://link.springer.com/chapter/10.1007/978-3-031-72913-3_12) | Jiaqi Chen | ECCV | [Github](https://github.com/jiaqchen/whereami-text2sgm) |
|3| [Context Graph-Based Visual-Language Place Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11127699) | Soojin Woo |  ICRA| [Github](https://github.com/woo-soojin/context-based-vlpr) |
|4|[Bridging text and vision: a multi-view text-vision registration approach for cross-modal place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11246871) | Tianyi Shang | IROS | [Github](https://github.com/nuozimiaowu/Text4VPR) |
|5| [Mms-vpr: Multimodal street-level visual place recognition dataset and benchmark](https://arxiv.org/pdf/2505.12254) | Yiwei Ou | arXiv | [Github](https://github.com/yiasun/MMS-VPRlib) |
|6| [MSSPlace: Multi-sensor place recognition with visual and text semantics](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11195136) | Alexander Melekhin| IEEE Access | [Github](https://github.com/alexmelekhin/MSSPlace) |
|7| [Text2Graph VPR: A Text-to-Graph Expert System for Explainable Place Recognition in Changing Environments](https://arxiv.org/pdf/2512.18613)| Saeideh Yousefzadeh |arXiv  |  |
#### 2. 2 Text–LiDAR Fusion
|No.| Title | First Author | Venue | Github |
|--|--|--|--|--|
|1| [Text2pos: Text-to-point-cloud cross-modal localization](https://openaccess.thecvf.com/content/CVPR2022/papers/Kolmet_Text2Pos_Text-to-Point-Cloud_Cross-Modal_Localization_CVPR_2022_paper.pdf) | Manuel Kolmet | CVPR | [Github](https://github.com/mako443/Text2Pos-CVPR2022) |
|2| [Text to point cloud localization with relation-enhanced transformer](https://ojs.aaai.org/index.php/AAAI/article/view/25347) | Guangzhi Wang | AAAI | |
|3| [Text2loc: 3d point cloud localization from natural language](https://openaccess.thecvf.com/content/CVPR2024/papers/Xia_Text2Loc_3D_Point_Cloud_Localization_from_Natural_Language_CVPR_2024_paper.pdf)| Yan Xia | CVPR | [Github](https://github.com/Yan-Xia/Text2Loc) |
|4| [Text2Loc++: Generalizing 3D Point Cloud Localization from Natural Language](https://arxiv.org/pdf/2511.15308)| Yan Xia | arXiv |  |
|5| [Text-driven 3d lidar place recognition for autonomous driving](https://arxiv.org/pdf/2503.18035) | Tianyi Shang | arXiv |  |
|6|  [Mambaplace: Text-to-point-cloud cross-modal place recognition with attention mamba mechanisms](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11246747)| Tianyi Shang |  IROS| [Github](https://github.com/nuozimiaowu/MambaPlace) |
|7| [FourierPlace: A Vision-Language Localization Framework Based on Frequency Domain Representations](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11260932)| Tianyi Shang | IEEE Robotics and Automation Letters | |
|8| [Instance-free text to point cloud localization with relative position awareness](https://arxiv.org/pdf/2404.17845)| Lichao Wang |arXiv  |  |
|9|[CMMLoc: Advancing Text-to-PointCloud Localization with Cauchy-Mixture-Model Based Framework](https://openaccess.thecvf.com/content/CVPR2025/papers/Xu_CMMLoc_Advancing_Text-to-PointCloud_Localization_with_Cauchy-Mixture-Model_Based_Framework_CVPR_2025_paper.pdf) | Yanlong Xu | CVPR | [Github](https://github.com/kevin301342/CMMLoc) |
|10| [Text to Point Cloud Localization with Multi-Level Negative Contrastive Learning](https://ojs.aaai.org/index.php/AAAI/article/view/32574) | Dunqiang Liu | AAAI | [Github](https://github.com/dqliua/MNCL) |
|11| [Text-guided scene perception cross-modal place recognition for remote sensing localization](https://www.sciencedirect.com/science/article/pii/S1566253525009297) | Mo Yang | Information Fusion |  |
### 3.  Radar-Involved Multimodal Fusion
|No.| Title | First Author | Venue | Github |
|--|--|--|--|--|
|1|[Rsl-net: Localising in satellite images from a radar on the ground](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8957240) | Tim Yuqing Tang | IEEE Robotics and Automation Letters |  |
|2| [Self-supervised localisation between range sensors and overhead imagery](https://arxiv.org/pdf/2006.02108) | Tim Yuqing Tang | arXiv |  |
|3| [Camera and radar sensor fusion for robust vehicle localization via vehicle part localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9081940) | Daejun Kang| IEEE Access |  |
|4|  [Radar-to-lidar: Heterogeneous place recognition via joint learning](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2021.661199/full)|Huan Yin | Frontiers in Robotics and AI | [Github](https://github.com/HuanYin94/radar-to-lidar-place-recognition) |
|5| [Rall: end-to-end radar localization on lidar map using differentiable measurement model](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9370010) | Huan Yin | IEEE Transactions on Intelligent Transportation Systems | [Github](https://github.com/HuanYin94/RaLL) |
|6| [Radar style transfer for metric robot localisation on lidar maps](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/cit2.12112) | Huan Yin | CAAI Transactions on Intelligence Technology |  |
|7| [Crplace: Camera-radar fusion with bev representation for place recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10802267)| Shaowei Fu| IROS |  |
|8| [RaLF: Flow-based global and metric radar localization in LiDAR maps](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10610626)| Abhijeet Nayak| ICRA | [Github](https://github.com/robot-learning-freiburg/RaLF) |
|9| [LRFusionPR: A Polar BEV-Based LiDAR-Radar Fusion Network for Place Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11177016) | Zhangshuo Qi |IEEE Robotics and Automation Letters  | [Github](https://github.com/QiZS-BIT/LRFusionPR) |
|10| [SHeRLoc: Synchronized Heterogeneous Radar Place Recognition for Cross-Modal Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11206409) |  Hanjun Kim| IEEE Robotics and Automation Letters |  |
