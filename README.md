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
     - [Single Animal](#Single-Animal)
       - [Heatmap-Based](#Heatmap-Based)
       - [Regression-Based](#Regression-Based)
     - [Multiple Animals](#Multiple-Animals)
       - [Top-Down](#Top-Down)
       - [Bottom-Up](#Bottom-Up)
       - [Top-Down&Bottom-Up](#Top-DownBottom-Up)
   - [3D RGB-Based APE](#3D-RGB-based-APE)
     - [Single Camera View](#Single-Camera-View)
       - [Skeleton-Only Methods](#Skeleton-only-Methods)
       - [Animal Mesh Recovery (Model-Based)](#Animal-Mesh-Recovery-Model-Based)
       - [Animal Mesh Recovery (Model-Free)](#Animal-Mesh-Recovery-Model-Free)
     - [Multiple Camera Views](#Multiple-Camera-Views)
- [Non-RGB-Based Unimodal APE](#Non-RGB-based-Unimodal-APE)
   - [IMU-Based APE](#IMU-based-APE)    
- [Multi-Modal APE](#Multi-Modal-APE)
   - [RGB+Depth+Thermal](#RGBDepthThermal)
   - [RGB+Depth](#RGBDepth)
   - [RGB+LiDAR](#RGBLiDAR)
   - [RGB+Acoustic](#RGBAcoustic)
   - [RGB+Language](#RGBLanguage)
   - [Animal-Borne Cameras+GPS+IMUs (ego-view)](#Animal-borne-camerasGPSIMUs-ego-view)
- [Datasets](#datasets)
   - [RGB-Based APE Dataset](#RGB-based-APE-Dataset)
     - [Images-Based](#Images-based)
     - [Videos-Based](#Videos-Based)
   - [Other-Sensor-Based APE Dataset](#Other-Sensor-based-APE-Dataset)
     - [RGB+MoCap](#RGBMoCap)
     - [RGB+Depth+MoCap](#RGBDepthMoCap)
     - [RGB+LiDAR](#RGBLiDAR)
     - [Infrared](#Infrared)
     - [3D Scanner](#3D-Scanner)
     - [MoCap+IMU](#MoCapIMU)

## Papers

### RGB-Based APE

#### 2D RGB-Based APE

##### Single Animal

###### Heatmap-Based

- [Decompose to generalize: Species-generalized animal pose estimation.](https://iclr.cc/virtual/2023/poster/12209) Guangrui Li, Yifan Sun, Zongxin Yang, and Yi Yang. ICLR (2023).

- [ScarceNet: Animal Pose Estimation with Scarce Annotations.](https://openaccess.thecvf.com/content/CVPR2023/html/Li_ScarceNet_Animal_Pose_Estimation_With_Scarce_Annotations_CVPR_2023_paper.html) Chen Li and Gim Hee Lee. CVPR (2023).

- [A unified framework for domain adaptive pose estimation.](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930592.pdf) Donghyun Kim, Kaihong Wang, Kate Saenko, Margrit Betke, and Stan Sclaroff. ECCV (2022).

- [From synthetic to real: Unsupervised domain adaptation for animal pose estimation.](https://arxiv.org/abs/2103.14843) Chen Li and Gim Hee Lee. CVPR (2021).

- [Deformation-aware unpaired image translation for pose estimation on laboratory animals.](https://arxiv.org/abs/2001.08601) Siyuan Li, Semih Gunel, Mirela Ostrek, Pavan Ramdya, Pascal Fua, and Helge Rhodin. CVPR (2020).

- [DeepPoseKit, a software toolkit for fast and robust animal pose estimation using deep learning.](https://elifesciences.org/articles/47994) Jacob M Graving, Daniel Chae, Hemal Naik, Liang Li, Benjamin Koger, Blair R Costelloe, and Iain D Couzin. Elife (2019).

- [Fast animal pose estimation using deep neural networks.](https://www.nature.com/articles/s41592-018-0234-5) Talmo D Pereira, Diego E Aldarondo, Lindsay Willmore, Mikhail Kislin, Samuel S-H Wang, Mala Murthy, and Joshua W Shaevitz. Nature methods (2019).

- [DeepLabCut: markerless pose estimation of user-defined body parts with deep learning.](https://www.nature.com/articles/s41593-018-0209-y) Alexander Mathis, Pranav Mamidanna, Kevin M Cury, Taiga Abe, Venkatesh N Murthy, Mackenzie Weygandt Mathis, and Matthias Bethge. Nature neuroscience (2018).

###### Regression-Based

[Few-shot keypoint detection with uncertainty learning for unseen species.](https://openaccess.thecvf.com/content/CVPR2022/papers/Lu_Few-Shot_Keypoint_Detection_With_Uncertainty_Learning_for_Unseen_Species_CVPR_2022_paper.pdf) Changsheng Lu and Piotr Koniusz. CVPR (2022).

##### Multiple Animals

###### Top-Down

- [SuperAnimal pretrained pose estimation models for behavioral analysis.](https://www.nature.com/articles/s41467-024-48792-2) (SuperAnimal-Quadruped) Shaokai Ye, Anastasiia Filippova, Jessy Lauer, and et al. Nature Communications (2024).

- [The Hitchhiker’s Guide to Endangered Species Pose Estimation.](https://openaccess.thecvf.com/content/WACV2024W/CV4Smalls/html/Straka_The_Hitchhikers_Guide_to_Endangered_Species_Pose_Estimation_WACVW_2024_paper.html) Jakub Straka, Marek Hruz, and Lukas Picek. WACV (2024).

- [DepthFormer: A High-Resolution Depth-Wise Transformer for Animal Pose Estimation.](https://www.mdpi.com/2077-0472/12/8/1280) Sicong Liu, Qingcheng Fan, Shanghao Liu, and Chunjiang Zhao. Agriculture (2022).

- [Deep-learning-based identification, tracking, pose estimation and behaviour 389 classification of interacting primates and mice in complex environments.](https://www.nature.com/articles/s42256-022-00477-5) Markus Marks et al . Nature Machine (2022).

###### Bottom-Up

- [Multi-animal pose estimation, identification and tracking with DeepLabCut.](https://www.nature.com/articles/s41592-022-01443-0) Jessy Lauer, Mu Zhou, Shaokai Ye, William Menegas, Steffen Schneider, Tanmay Nath, Mohammed Mostafizur Rahman, Valentina Di Santo, Daniel
Soberanes, Guoping Feng, et al. Nature Methods (2022).

- [Multi-pig Pose Estimation Using DeepLabCut.](https://researchportal.helsinki.fi/en/publications/multi-pig-pose-estimation-using-deeplabcut) Fahimeh Farahnakian, Jukka Heikkonen, and Stefan Björkman. IEEE ICICIP (2021).

- [Multiple monkey pose estimation using openpose.](https://www.biorxiv.org/content/10.1101/2021.01.28.428726v1) Salvador Blanco Negrete, Rollyn Labuguen, Jumpei Matsumoto, Yasuhiro Go, Ken-ichi Inoue, and Tomohiro Shibata. bioRxiv (2021).

[Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields.](https://openaccess.thecvf.com/content_cvpr_2017/papers/Cao_Realtime_Multi-Person_2D_CVPR_2017_paper.pdf) Zhe Cao, Tomas Simon, Shih-En Wei, and Yaser Sheikh. CVPR (2017).

###### Top-Down&Bottom-Up

- [SuperAnimal pretrained pose estimation models for behavioral analysis.](https://www.nature.com/articles/s41467-024-48792-2) (SuperAnimal-TopViewMouse) Shaokai Ye, Anastasiia Filippova, Jessy Lauer, and et al. Nature Communications (2024).

- [SLEAP: A deep learning system for multi-animal pose tracking.](https://www.nature.com/articles/s41592-022-01426-1) Talmo D Pereira, Nathaniel Tabris, Arie Matsliah, et al . Nature methods (2022).

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

- [Automated measurement of livestock body based on pose normalisation using statistical shape model.](https://www.sciencedirect.com/science/article/abs/pii/S1537511023000211) Xinying Luo, Yihu Hu, Zicheng Gao, Hao Guo, and Yang Su. Biosystems Engineering (2023).

- [RGBD-Dog: Predicting Canine Pose from RGBD Sensors.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kearney_RGBD-Dog_Predicting_Canine_Pose_from_RGBD_Sensors_CVPR_2020_paper.pdf) Sinead Kearney, Wenbin Li, Martin Parsons, Kwang In Kim, and Darren Cosker. CVPR (2020).

#### RGB+LiDAR

- [WildPose: A Long-Range 3D Wildlife Motion Capture System.](https://www.biorxiv.org/content/10.1101/2024.02.05.578861v3) Naoya Muramatsu, Sangyun Shin, Qianyi Deng, Andrew Markham, and Amir Patel. BioRxiv (2024).

#### RGB+Acoustic

- [CLHOP: Combined Audio-Video Learning for Horse 3D Pose and Shape Estimation.](https://arxiv.org/abs/2407.01244) Ci Li, Elin Hernlund, Hedvig Kjellström, and Silvia Zuffi. arXiv (2024).

- [The Sound of Motion: Multimodal horse motion estimation from video and audio.](https://sightsound.org/papers/2022/Li_The_Sound_of_Motion_Multimodal_horse_motion_estimation_from_video_and_audio.pdf) Ci Li, Elin Hernlund, Hedvig Kjellström, and Silvia Zuffi. CVPR Workshop (2022).

#### RGB+Language

- [AWOL: Analysis WithOut synthesis using Language.](https://arxiv.org/abs/2404.03042) Silvia Zuffi and Michael J. Black. arXiv (2024).

- [AmadeusGPT: a natural language interface for interactive animal behavioral analysis.](https://proceedings.neurips.cc/paper_files/paper/2023/file/1456560769bbc38e4f8c5055048ea712-Paper-Conference.pdf) Shaokai Ye, Jessy Lauer, Mu Zhou, Alexander Mathis, and Mackenzie W Mathis. NeurIPS (2023).
  
- [CLAMP: Prompt-Based Contrastive Learning for Connecting Language and Animal Pose.](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_CLAMP_Prompt-Based_Contrastive_Learning_for_Connecting_Language_and_Animal_Pose_CVPR_2023_paper.pdf) Xu Zhang, Wen Wang, Zhe Chen, Yufei Xu, Jing Zhang, and Dacheng Tao. CVPR (2023).

#### Animal-Borne Cameras+GPS+IMUs (ego-view)

- [Tracking the cheetah tail using animal-borne cameras, GPS, and an IMU.](https://ieeexplore.ieee.org/document/7950913) Amir Patel, Bradley Stocks, Callen Fisher, Fred Nicolls, and Edward Boje. IEEE sensors letters (2017).

### Datasets

#### RGB-Based APE Dataset

##### Images-Based

- [Animal3D: A Comprehensive Dataset of 3D Animal Pose and Shape.](https://openaccess.thecvf.com/content/ICCV2023/html/Xu_Animal3D_A_Comprehensive_Dataset_of_3D_Animal_Pose_and_Shape_ICCV_2023_paper.html) Jiacong Xu, Yi Zhang, Jiawei Peng, and et al. ICCV (2023).

- [OpenApePose, a database of annotated ape photographs for pose estimation.](https://elifesciences.org/articles/86873) Nisarg Desai, Praneet Bala, Rebecca Richardson, Jessica Raper, Jan Zimmermann, and Benjamin Hayden. ELife (2023).

- [OpenMonkeyChallenge: Dataset and Benchmark Challenges for Pose Estimation of Non-human Primates.](https://link.springer.com/article/10.1007/s11263-022-01698-2) Yuan Yao, Praneet Bala, Abhiraj Mohan, and et al. IJCV (2022).

- [Animal Kingdom: A Large and Diverse Dataset for Animal Behavior Understanding.](https://openaccess.thecvf.com/content/CVPR2022/papers/Ng_Animal_Kingdom_A_Large_and_Diverse_Dataset_for_Animal_Behavior_CVPR_2022_paper.pdf) Xun Long Ng, Kian Eng Ong, Qichen Zheng, Yun Ni, Si Yong Yeo, and Jun Liu. CVPR (2022).

- [MacaquePose: A Novel “In the Wild” Macaque Monkey Pose Dataset for Markerless Motion Capture.](https://www.frontiersin.org/journals/behavioral-neuroscience/articles/10.3389/fnbeh.2020.581154/full) Rollyn Labuguen, Jumpei Matsumoto, Salvador Blanco Negrete, Hiroshi Nishimaru, Hisao Nishijo, Masahiko Takada, Yasuhiro Go, Ken-ichi Inoue, and Tomohiro Shibata. Frontiers in Behavioral Neuroscience (2021).

- [Ap-10k: A benchmark for animal pose estimation in the wild.](https://proceedings.neurips.cc/paper_files/paper/2022/file/fbb10d319d44f8c3b4720873e4177c65-Paper-Conference.pdf) Hang Yu, Yufei Xu, Jing Zhang, Wei Zhao, Ziyu Guan, and Dacheng Tao. NeurIPS (2021).

- [Who Left the Dogs Out? 3D Animal Reconstruction with Expectation Maximization in the Loop.](https://arxiv.org/abs/2007.11110) Benjamin Biggs, Oliver Boyne, James Charles, Andrew Fitzgibbon, and Roberto Cipolla. ECCV (2020).

- [Learning From Synthetic Animals.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mu_Learning_From_Synthetic_Animals_CVPR_2020_paper.pdf) Jiteng Mu, Weichao Qiu, Gregory D. Hager, and Alan L. Yuille. CVPR (2020).

- [Three-D Safari: Learning to Estimate Zebra Pose, Shape, and Texture from Images" In the Wild".](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zuffi_Three-D_Safari_Learning_to_Estimate_Zebra_Pose_Shape_and_Texture_ICCV_2019_paper.pdf) Silvia Zuffi, Angjoo Kanazawa, Tanya Berger-Wolf, and Michael J Black. CVPR (2019).
  
- [Cross-domain adaptation for animal pose estimation.](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cao_Cross-Domain_Adaptation_for_Animal_Pose_Estimation_ICCV_2019_paper.pdf) Jinkun Cao, Hongyang Tang, Hao-Shu Fang, Xiaoyong Shen, Cewu Lu, and Yu-Wing Tai. ICCV (2019).

- [Animals-10 dataset.](https://www.kaggle.com/alessiocorrado99/animals10.) Corrado Alessio. (2018). 

- [Microsoft coco: Common objects in context].(https://cocodataset.org/#download.) Tsung-Yi Lin, Michael Maire, Serge Belongie, James Hays, Pietro Perona, Deva Ramanan, Piotr Dollár, and C Lawrence Zitnick. ECCV (2014).

- [Novel Dataset for Fine-Grained Image Categorization.](https://people.csail.mit.edu/khosla/papers/fgvc2011.pdf) Aditya Khosla, Nityananda Jayadevaprakash, Bangpeng Yao, and Li Fei-Fei. CVPR Workshop (2011).

##### Videos-Based

- [ChimpACT: A Longitudinal Dataset for Understanding Chimpanzee Behaviors.](https://proceedings.neurips.cc/paper_files/paper/2023/file/57a95cd3898bf4912269848a01f53620-Paper-Datasets_and_Benchmarks.pdf) Xiaoxuan Ma, Stephan P. Kaufhold, Jiajun Su, Wentao Zhu, Jack Terwilliger, Andres Meza, Yixin Zhu, Federico Rossano, and Yizhou Wang. NeurIPS (2023).

- [Apt-36k: A large-scale benchmark for animal pose estimation and tracking.](https://proceedings.neurips.cc/paper_files/paper/2022/file/6e566c91d381bd7a45647d9a90838817-Paper-Datasets_and_Benchmarks.pdf) Yuxiang Yang, Junjie Yang, Yufei Xu, Jing Zhang, Long Lan, and Dacheng Tao. NeurIPS (2022).
  
- [Pretraining boosts out-of-domain robustness for pose estimation.](https://arxiv.org/abs/1909.11229) Alexander Mathis, Thomas Biasi, Steffen Schneider, Mert Yuksekgonul, Byron Rogers, Matthias Bethge, and Mackenzie W Mathis. WACV (2021).
  
- [AcinoSet: a 3D pose estimation dataset and baseline models for Cheetahs in the wild.](https://arxiv.org/abs/2103.13282) Daniel Joska, Liam Clark, Naoya Muramatsu, Ricardo Jericevich, Fred Nicolls, Alexander Mathis, Mackenzie W Mathis, and Amir Patel. IEEE ICRA (2021).

- [Automated markerless pose estimation in freely moving macaques with OpenMonkeyStudio.](https://www.nature.com/articles/s41467-020-18441-5) Praneet C Bala, Benjamin R Eisenreich, Seng Bum Michael Yoo, Benjamin Y Hayden, Hyun Soo Park, and Jan Zimmermann. Nature communications (2020).

- [ATRW: A Benchmark for Amur Tiger Re-identification in the Wild.](https://dl.acm.org/doi/10.1145/3394171.3413569) Shuyuan Li, Jianguo Li, Hanlin Tang, Rui Qian, and Weiyao Lin. ACM International Conference on Multimedia (2020).

- [Creatures great and SMAL: Recovering the shape and motion of animals from video.](https://link.springer.com/chapter/10.1007/978-3-030-20873-8_1#citeas) Benjamin Biggs, Thomas Roddick, Andrew Fitzgibbon, and Roberto Cipolla. ACCV (2018).

- [Behavior discovery and alignment of articulated object classes from unstructured video.](https://arxiv.org/pdf/1511.09319) Luca Del Pero, Susanna Ricco, Rahul Sukthankar, and Vittorio Ferrari. IJCV (2017).

- [Articulated motion discovery using pairs of trajectories.](https://openaccess.thecvf.com/content_cvpr_2015/papers/Pero_Articulated_Motion_Discovery_2015_CVPR_paper.pdf) Luca Del Pero, Susanna Ricco, Rahul Sukthankar, and Vittorio Ferrari. CVPR (2015).

#### Other-Sensor-Based APE Dataset

##### RGB+MoCap

- [The Poses for Equine Research Dataset (PFERD).](https://www.nature.com/articles/s41597-024-03312-1) Ci Li, Ylva Mellbin, Johanna Krogager, Senya Polikovsky, Martin Holmberg, Nima Ghorbani, Michael J Black, Hedvig Kjellström, Silvia Zuffi, and Elin Hernlund. Scientific Data (2024).

- [3D-POP - An Automated Annotation Approach to Facilitate Markerless 2D-3D Tracking of Freely Moving Birds With Marker-Based Motion Capture.](https://arxiv.org/pdf/2303.13174) Hemal Naik, Alex Hoi Hang Chan, Junran Yang, Mathilde Delacoux, Iain D. Couzin, Fumihiro Kano, and Máté Nagy. CVPR (2023).

- [Geometric deep learning enables 3D kinematic profiling across species and environments.](https://www.nature.com/articles/s41592-021-01106-6) Timothy W Dunn, Jesse D Marshall, Kyle S Severson, and et al. Nature methods (2021).

- [The PAIR-R24M Dataset for Multi-animal 3D Pose Estimation.](https://datasets-benchmarks-proceedings.neurips.cc/paper_files/paper/2021/hash/1ff8a7b5dc7a7d1f0ed65aaa29c04b1e-Abstract-round1.html) Jesse Marshall, Ugne Klibaite, amanda gellis, Diego Aldarondo, Bence Olveczky, and Timothy W Dunn. NeurIPS (2021).

##### RGB+Depth+MoCap

- [RGBD-Dog: Predicting Canine Pose from RGBD Sensors.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kearney_RGBD-Dog_Predicting_Canine_Pose_from_RGBD_Sensors_CVPR_2020_paper.pdf) Sinead Kearney, Wenbin Li, Martin Parsons, Kwang In Kim, and Darren Cosker. CVPR (2020).

##### RGB+LiDAR

- [WildPose: A Long-Range 3D Wildlife Motion Capture System.](https://www.biorxiv.org/content/10.1101/2024.02.05.578861v1) Naoya Muramatsu, Sangyun Shin, Qianyi Deng, Andrew Markham, and Amir Patel. bioRxiv (2024).

##### Infrared

- [LoTE-Animal: A Long Time-span Dataset for Endangered Animal Behavior Understanding.](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_LoTE-Animal_A_Long_Time-span_Dataset_for_Endangered_Animal_Behavior_Understanding_ICCV_2023_paper.pdf) Dan Liu, Jin Hou, Shaoli Huang, Jing Liu, Yuxin He, Bochuan Zheng, Jifeng Ning, and Jingdong Zhang. ICCV (2023).

##### 3D Scanner

- [VAREN: Very Accurate and Realistic Equine Network.](https://openaccess.thecvf.com/content/CVPR2024/html/Zuffi_VAREN_Very_Accurate_and_Realistic_Equine_Network_CVPR_2024_paper.html) Silvia Zuffi, Ylva Mellbin, Ci Li, Markus Hoeschle, Hedvig Kjellström, Senya Polikovsky, Elin Hernlund, and Michael J. Black. CVPR (2024).

##### MoCap+IMU

- [Wearable inertial sensor-based limb lameness detection and pose estimation for horses.](https://ieeexplore.ieee.org/document/9743494) Tarik Yigit, Feng Han, Ellen Rankins, Jingang Yi, Kenneth H McKeever, and Karyn Malinowski. IEEE Transactions on Automation Science and Engineering (2022).

## Todo

- [x] Create the overall template
- [ ] Add all the papers
