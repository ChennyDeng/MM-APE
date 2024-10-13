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
- [RGB-Based APE](#RGB-based-APE)
   - [2D RGB-Based APE](#2D-RGB-based-APE)
   - [3D RGB-Based APE](#3D-RGB-based-APE)
     - [Single Camera View](#Single-Camera-View)
       - [Skeleton-Only Methods](#Skeleton-only-Methods)
       - [Animal Mesh Recovery (Model-Based)](#Animal-Mesh-Recovery-Model-Based)
       - [Animal Mesh Recovery (Model-Free)](#Animal-Mesh-Recovery-Model-Free)
     - [Multiple Camera Views](#Multiple-Camera-Views)
- [Non-RGB-Based Unimodal APE](#Non-RGB-based-Unimodal-APE)
   - [IMU-Based APE](#IMU-based-APE)    
- [Multi-Modal APE](#Multi-Modal-APE)
   - [RGB+Depth+Thermal](#RGB+Depth+Thermal)
   - [RGB+Depth](#RGBDepth)
   - [RGB+LiDAR](#RGBLiDAR)
   - [RGB+Acoustic](#RGBAcoustic)
   - [RGB+Language](#RGBLanguage)
   - [Animal-Borne Cameras+GPS+IMUs (ego-view)](#Animal-borne-camerasGPSIMUs-ego-view)
- [Datasets](#datasets)
   - [RGB-Based APE Dataset](#RGB-based-APE-Dataset)
   - [Other-Sensor-Based APE Dataset](#Other-Sensor-based-APE-Dataset)

## Papers

### RGB-Based APE

#### 2D RGB-Based APE
- [DeepLabCut: markerless pose estimation of user-defined body parts with deep learning.](https://www.nature.com/articles/s41593-018-0209-y) Alexander Mathis, Pranav Mamidanna, Kevin M Cury, Taiga Abe, Venkatesh N Murthy, Mackenzie Weygandt Mathis, and Matthias Bethge. Nature neuroscience (2018).

#### 3D RGB-Based APE

##### Single Camera View

###### Skeleton-Only Methods

- [DigiDogs: Single-View 3D Pose Estimation of Dogs Using Synthetic Training Data.](https://openaccess.thecvf.com/content/WACV2024W/CV4Smalls/papers/Shooter_DigiDogs_Single-View_3D_Pose_Estimation_of_Dogs_Using_Synthetic_Training_WACVW_2024_paper.pdf) Moira Shooter, Charles Malleson, and Adrian Hilton. WACV (2024).

- [A Horse with no Labels: Self-Supervised Horse Pose Estimation from Unlabelled Images and Synthetic Prior.](https://openaccess.thecvf.com/content/ICCV2023W/LIMIT/papers/Sosa_A_Horse_with_no_Labels_Self-Supervised_Horse_Pose_Estimation_from_ICCVW_2023_paper.pdf) Jose Sosa and David Hogg. CVPR (2023). 

- [Unsupervised 3D Animal Canonical Pose Estimation with Geometric Self-
Supervision.](https://ieeexplore.ieee.org/document/10042785) Xiaowei Dai, Shuiwang Li, Qijun Zhao, and Hongyu Yang. IEEE Automatic Face and Gesture Recognition (2023).

- [3D mouse pose from single-view video and a new dataset.](https://www.nature.com/articles/s41598-023-40738-w) Bo Hu, Bryan Seybold, Shan Yang, Avneesh Sud, Yi Liu, Karla Barron, Paulyn Cha, Marcelo Cosino, Ellie Karlsson, Janessa Kite, et al. Scientific Reports (2023).

- [LiftPose3D, a deep learning-based approach for transforming two-dimensional to three-dimensional poses in laboratory animals.](https://www.nature.com/articles/s41592-021-01226-z) Adam Gosztolai, Semih Günel, Victor Lobato-Ríos, Marco Pietro Abrate, Daniel Morales, Helge Rhodin, Pascal Fua, and Pavan Ramdya. Nature methods (2021).

- [Three-dimensional pose estimation for laboratory mouse from monocular images.](https://ieeexplore.ieee.org/document/8678850) Ghadi Salem, Jonathan Krynitsky, Monson Hayes, Thomas Pohida, and Xavier Burgos-Artizzu. IEEE Transactions on Image Processing (2019).

###### Animal Mesh Recovery (Model-Based)

- [BITE: Beyond priors for improved three-D dog pose estimation.](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruegg_BITE_Beyond_Priors_for_Improved_Three-D_Dog_Pose_Estimation_CVPR_2023_paper.pdf) Nadine Rüegg, Shashank Tripathi, Konrad Schindler, Michael J Black, and Silvia Zuffi. CVPR (2023).

- [Barc: Learning to regress 3d dog shape from images by exploiting breed information.](https://arxiv.org/abs/2203.15536) Nadine Rüegg, Silvia Zuffi, Konrad Schindler, and Michael J Black. CVPR (2022).
  
- [Birds of a feather: Capturing avian shape models from images.](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Birds_of_a_Feather_Capturing_Avian_Shape_Models_From_Images_CVPR_2021_paper.pdf) Yufu Wang, Nikos Kolotouros, Kostas Daniilidis, and Marc Badger. CVPR (2021).

- [Coarse-to-fine animal pose and shape estimation.](https://proceedings.neurips.cc/paper/2021/file/6195f47dcff14b8f242aa333cdb2703e-Paper.pdf) Chen Li and Gim Hee Lee. NeurIPS (2021).

- [Who Left the Dogs Out? 3D Animal Reconstruction with Expectation Maximization in the Loop.](https://arxiv.org/abs/2007.11110) Benjamin Biggs, Oliver Boyne, James Charles, Andrew Fitzgibbon, and Roberto Cipolla. ECCV (2020).

- [Three-D Safari: Learning to Estimate Zebra Pose, Shape, and Texture from Images" In the Wild".](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zuffi_Three-D_Safari_Learning_to_Estimate_Zebra_Pose_Shape_and_Texture_ICCV_2019_paper.pdf) Silvia Zuffi, Angjoo Kanazawa, Tanya Berger-Wolf, and Michael J Black. CVPR (2019).

- [3D menagerie: Modeling the 3D shape and pose of animals.](https://arxiv.org/abs/1611.07700) Silvia Zuffi, Angjoo Kanazawa, David W Jacobs, and Michael J Black. CVPR (2017).

###### Animal Mesh Recovery (Model-Free)

- [Learning the 3D Fauna of the Web.](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Learning_the_3D_Fauna_of_the_Web_CVPR_2024_paper.pdf) Zizhang Li, Dor Litvak, Ruining Li, Yunzhi Zhang, Tomas Jakab, Christian Rupprecht, Shangzhe Wu, Andrea Vedaldi, and Jiajun Wu. CVPR (2024).

- [Banmo: Building animatable 3d neural models from many casual videos.](https://arxiv.org/abs/2112.12761) Gengshan Yang, Minh Vo, Natalia Neverova, Deva Ramanan, Andrea Vedaldi, and Hanbyul Joo. CVPR (2022).

- [Magicpony: Learning articulated 3d animals in the wild.](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_MagicPony_Learning_Articulated_3D_Animals_in_the_Wild_CVPR_2023_paper.pdf) Shangzhe Wu, Ruining Li, Tomas Jakab, Christian Rupprecht, and Andrea Vedaldi. CVPR (2023). 

- [Dove: Learning deformable 3d objects by watching videos.](https://arxiv.org/abs/2107.10844) Shangzhe Wu, Tomas Jakab, Christian Rupprecht, and Andrea Vedaldi. IJCV (2023).

##### Multiple Camera Views 

- [Multi-animal 3D social pose estimation, identification and behaviour embedding with a few-shot learning
framework.](https://www.nature.com/articles/s42256-023-00776-5) Yaning Han, Ke Chen, Yunke Wang, and et al. Nature Machine Intelligence (2024).

- [Three-dimensional surface motion capture of multiple freely moving pigs using MAMMAL.](https://www.nature.com/articles/s41467-023-43483-w) Liang An, Jilong Ren, Tao Yu, Tang Hai, Yichang Jia, and Yebin Liu. Nature Communications (2023). 

- [Three-dimensional unsupervised probabilistic pose reconstruction (3D-UPPER) for freely moving animals.](https://www.nature.com/articles/s41598-022-25087-4) Aghileh S Ebrahimi, Patrycja Orlowska-Feuer, Qian Huang, Antonio G Zippo, Franck P Martial, Rasmus S Petersen, and Riccardo Storchi. Scientific Reports (2023).

- [Improving 3D Markerless Pose Estimation of Animals in the
Wild using Low-Cost Cameras.](https://ieeexplore.ieee.org/document/9981746) Naoya Muramatsu, Zico da Silva, Daniel Joska, Fred Nicolls, and Amir Patel. 2022. IEEE IROS (2022).

- [Anipose: a toolkit for robust markerless 3D pose estimation.](https://www.cell.com/cell-reports/fulltext/S2211-1247(21)01179-7?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2211124721011797%3Fshowall%3Dtrue) Pierre Karashchuk, Katie L Rupp, Evyn S Dickinson, Sarah Walling-Bell, Elischa Sanders, Eiman Azim, Bingni W Brunton, and John C Tuthill. Cell reports (2021).

- [Geometric deep learning enables 3D kinematic profiling across species and environments.](https://www.nature.com/articles/s41592-021-01106-6
) Timothy W Dunn, Jesse D Marshall, Kyle S Severson, Diego E Aldarondo, David GC Hildebrand, Selmaan N Chettih, William L Wang, Amanda J
Gellis, David E Carlson, Dmitriy Aronov, et al. Nature methods (2021).

- [Animal pose estimation from video data with a hierarchical von Mises-Fisher-Gaussian model.](https://proceedings.mlr.press/v130/zhang21h.html) Libby Zhang, Tim Dunn, Jesse Marshall, Bence Olveczky, and Scott Linderman. PMLR (2021).

- [Automated markerless pose estimation in freely moving macaques with OpenMonkeyStudio.](https://www.nature.com/articles/s41467-020-18441-5) Praneet C Bala, Benjamin R Eisenreich, Seng Bum Michael Yoo, Benjamin Y Hayden, Hyun Soo Park, and Jan Zimmermann. Nature Communications (2020).

- [Monet: Multiview semi-supervised keypoint detection via epipolar divergence.](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yao_MONET_Multiview_Semi-Supervised_Keypoint_Detection_via_Epipolar_Divergence_ICCV_2019_paper.pdf) Yuan Yao, Yasamin Jafarian, and Hyun Soo Park. ICCV (2019).

### Non-RGB-Based Unimodal APE

#### IMU-Based APE

- [Wearable inertial sensor-based limb lameness detection and pose estimation for horses.](https://ieeexplore.ieee.org/document/9743494) Tarik Yigit, Feng Han, Ellen Rankins, Jingang Yi, Kenneth H McKeever, and Karyn Malinowski.  IEEE Transactions on Automation Science and Engineering (2022).

### Multi-Modal APE

#### RGB+Depth+Thermal

- [Animal Pose Tracking: 3D Multimodal Dataset and Token-based Pose Optimization.](https://link.springer.com/article/10.1007/s11263-022-01714-5) Mahir Patel, Yiwen Gu, Lucas C Carstensen, Michael E Hasselmo, and Margrit Betke. IJCV (2023).

#### RGB+Depth

- [RGBD-Dog: Predicting Canine Pose from RGBD Sensors.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kearney_RGBD-Dog_Predicting_Canine_Pose_from_RGBD_Sensors_CVPR_2020_paper.pdf) Sinead Kearney, Wenbin Li, Martin Parsons, Kwang In Kim, and Darren Cosker. CVPR (2020).

#### RGB+LiDAR

- [WildPose: A Long-Range 3D Wildlife Motion Capture System.](https://www.biorxiv.org/content/10.1101/2024.02.05.578861v3) Naoya Muramatsu, Sangyun Shin, Qianyi Deng, Andrew Markham, and Amir Patel. BioRxiv (2024).

#### RGB+Acoustic

- [The Sound of Motion: Multimodal horse motion estimation from video and audio.](https://sightsound.org/papers/2022/Li_The_Sound_of_Motion_Multimodal_horse_motion_estimation_from_video_and_audio.pdf) Ci Li, Elin Hernlund, Hedvig Kjellström, and Silvia Zuffi. CVPR Workshop (2022).

#### RGB+Language

- [CLAMP: Prompt-Based Contrastive Learning for Connecting Language and Animal Pose.](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_CLAMP_Prompt-Based_Contrastive_Learning_for_Connecting_Language_and_Animal_Pose_CVPR_2023_paper.pdf) Xu Zhang, Wen Wang, Zhe Chen, Yufei Xu, Jing Zhang, and Dacheng Tao. CVPR (2023).

#### Animal-Borne Cameras+GPS+IMUs (ego-view)

- [Tracking the cheetah tail using animal-borne cameras, GPS, and an IMU.](https://ieeexplore.ieee.org/document/7950913) Amir Patel, Bradley Stocks, Callen Fisher, Fred Nicolls, and Edward Boje. IEEE sensors letters (2017).

### Datasets

#### RGB-Based APE Dataset

- [Apt-36k: A large-scale benchmark for animal pose estimation and tracking.](https://proceedings.neurips.cc/paper_files/paper/2022/file/6e566c91d381bd7a45647d9a90838817-Paper-Datasets_and_Benchmarks.pdf) Yuxiang Yang, Junjie Yang, Yufei Xu, Jing Zhang, Long Lan, and Dacheng Tao. NeurIPS (2022).

#### Other-Sensor-Based APE Dataset

- [LoTE-Animal: A Long Time-span Dataset for Endangered Animal Behavior Understanding.](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_LoTE-Animal_A_Long_Time-span_Dataset_for_Endangered_Animal_Behavior_Understanding_ICCV_2023_paper.pdf) Dan Liu, Jin Hou, Shaoli Huang, Jing Liu, Yuxin He, Bochuan Zheng, Jifeng Ning, and Jingdong Zhang. ICCV (2023).

## Todo

- [x] Create the overall template
- [ ] Add all the papers
