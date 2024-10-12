# Towards Multi-Modal Animal Pose Estimation: An In-Depth Analysis  [[Paper]()]

A repository of unimodal and multi-modal animal pose estimation datasets and papers. This repository is associated with our systematic review, entitled "Towards Multi-Modal Animal Pose Estimation: An In-Depth Analysis".

Authors: [Qianyi Deng](https://www.cs.ox.ac.uk/people/publications/date/Qianyi.Deng.html), 
[Oishi Deb](https://www.linkedin.com/in/oishi-deb-61737386/?originalSubdomain=uk), 
[Amir Patel](https://scholar.google.com/citations?user=RxMigV4AAAAJ&hl=en&oi=ao),
[Christian Rupprecht](https://scholar.google.com/citations?hl=en&user=IrYlproAAAAJ), 
[Philip Torr](https://scholar.google.com/citations?user=kPxa2w0AAAAJ&hl=en),
[Niki Trigoni](https://scholar.google.com/citations?hl=en&user=185g9ckAAAAJ),
[Andrew Markham](https://scholar.google.com/citations?hl=en&user=g3JTO9EAAAAJ).

If you find this work useful for your research, please feel free to cite the paper and leave a ⭐.

## News

📌 We are continuously monitoring the latest research and encourage contributions to our repository. If your work aligns with our focus, don't hesitate to submit an issue or a pull request. Feedback and contributions are welcome!

## Table of Contents
- [RGB-based APE](#RGB-based-APE)
   - [2D RGB-based APE](#2D-RGB-based-APE)
   - [3D RGB-based APE](#3D-RGB-based-APE)
- [Non-RGB-based Unimodal APE](#Non-RGB-based-Unimodal-APE)
   - [IMU-based APE](#IMU-based-APE)    
- [Multi-Modal APE](#Multi-Modal-APE)
   - [RGB + Depth + Thermal](#RGB-+-Depth-+-Thermal)
   - [RGB + Depth](#RGB-+-Depth)
   - [RGB + LiDAR](#RGB-+-LiDAR)
   - [RGB + Acoustic](#RGB-+-Acoustic)
   - [RGB + Language](#RGB-+-Language)
   - [Animal-borne cameras + GPS + IMUs (ego-view)](#Animal-borne-cameras-+-GPS-+-IMUs)
- [Datasets](#datasets)
   - [RGB-based APE Dataset](#RGB-based-APE-Dataset)
   - [Other-Sensor-based APE Dataset](#Other-Sensor-based-APE-Dataset)

## Papers

### RGB-based APE

#### 2D RGB-based APE
- [DeepLabCut: markerless pose estimation of user-defined body parts with deep learning.](https://www.nature.com/articles/s41593-018-0209-y) Alexander Mathis, Pranav Mamidanna, Kevin M Cury, Taiga Abe, Venkatesh N Murthy, Mackenzie Weygandt Mathis, and Matthias Bethge. Nature neuroscience (2018).

#### 3D RGB-based APE
- [LiftPose3D, a deep learning-based approach for transforming two-dimensional to three-dimensional poses in laboratory animals.](https://www.nature.com/articles/s41592-021-01226-z) Adam Gosztolai, Semih Günel, Victor Lobato-Ríos, Marco Pietro Abrate, Daniel Morales, Helge Rhodin, Pascal Fua, and Pavan Ramdya. Nature methods (2021).

### Non-RGB-based Unimodal APE

#### IMU-based APE

- [Wearable inertial sensor-based limb lameness detection and pose estimation for horses.](https://ieeexplore.ieee.org/document/9743494) Tarik Yigit, Feng Han, Ellen Rankins, Jingang Yi, Kenneth H McKeever, and Karyn Malinowski.  IEEE Transactions on Automation Science and Engineering (2022).

### Multi-Modal APE

#### RGB + Depth + Thermal

- [Animal Pose Tracking: 3D Multimodal Dataset and Token-based Pose Optimization.](https://link.springer.com/article/10.1007/s11263-022-01714-5) Mahir Patel, Yiwen Gu, Lucas C Carstensen, Michael E Hasselmo, and Margrit Betke. IJCV (2023).

#### RGB + Depth

- [RGBD-Dog: Predicting Canine Pose from RGBD Sensors.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kearney_RGBD-Dog_Predicting_Canine_Pose_from_RGBD_Sensors_CVPR_2020_paper.pdf) Sinead Kearney, Wenbin Li, Martin Parsons, Kwang In Kim, and Darren Cosker. CVPR (2020).

#### RGB + LiDAR

- [WildPose: A Long-Range 3D Wildlife Motion Capture System.](https://www.biorxiv.org/content/10.1101/2024.02.05.578861v3) Naoya Muramatsu, Sangyun Shin, Qianyi Deng, Andrew Markham, and Amir Patel. BioRxiv (2024).

#### RGB + Acoustic

- [The Sound of Motion: Multimodal horse motion estimation from video and audio.](https://sightsound.org/papers/2022/Li_The_Sound_of_Motion_Multimodal_horse_motion_estimation_from_video_and_audio.pdf) Ci Li, Elin Hernlund, Hedvig Kjellström, and Silvia Zuffi. CVPR Workshop (2022).

#### RGB + Language

- [CLAMP: Prompt-Based Contrastive Learning for Connecting Language and Animal Pose.](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_CLAMP_Prompt-Based_Contrastive_Learning_for_Connecting_Language_and_Animal_Pose_CVPR_2023_paper.pdf) Xu Zhang, Wen Wang, Zhe Chen, Yufei Xu, Jing Zhang, and Dacheng Tao. CVPR (2023).

#### Animal-borne cameras + GPS + IMUs (ego-view)

- [Tracking the cheetah tail using animal-borne cameras, GPS, and an IMU.](https://ieeexplore.ieee.org/document/7950913) Amir Patel, Bradley Stocks, Callen Fisher, Fred Nicolls, and Edward Boje. IEEE sensors letters (2017).

### Datasets

#### RGB-based APE Dataset

- [Apt-36k: A large-scale benchmark for animal pose estimation and tracking.](https://proceedings.neurips.cc/paper_files/paper/2022/file/6e566c91d381bd7a45647d9a90838817-Paper-Datasets_and_Benchmarks.pdf) Yuxiang Yang, Junjie Yang, Yufei Xu, Jing Zhang, Long Lan, and Dacheng Tao. NeurIPS (2022).

#### Other-Sensor-based APE Dataset

- [LoTE-Animal: A Long Time-span Dataset for Endangered Animal Behavior Understanding.](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_LoTE-Animal_A_Long_Time-span_Dataset_for_Endangered_Animal_Behavior_Understanding_ICCV_2023_paper.pdf) Dan Liu, Jin Hou, Shaoli Huang, Jing Liu, Yuxin He, Bochuan Zheng, Jifeng Ning, and Jingdong Zhang. ICCV (2023).

## Todo

- [x] Create the overall template
- [ ] Add all the papers
