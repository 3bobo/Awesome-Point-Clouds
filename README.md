# Awesome-Point-Clouds
Awesome paper/code for point clouds with deep learning methods in detection and tracking. If you find some novel methods or have suggestions, please contact ybcui95@163.com

## Datasets
- KITTI: [Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite](http://www.cvlibs.net/publications/Geiger2012CVPR.pdf) [[Project Page](http://www.cvlibs.net/datasets/kitti/index.php)] [CVPR'2012]
- Apolloscape: [The ApolloScape Dataset for Autonomous Driving](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Huang_The_ApolloScape_Dataset_CVPR_2018_paper.pdf) [[Project Page](http://apolloscape.auto/)] [CVPR'2018]
- Argoverse: [Argoverse: 3D Tracking and Forecasting with Rich Maps](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf) [[Project Page](https://www.argoverse.org/index.html)] [CVPR'2019]
- Nuscenes: [nuScenes: A multimodal dataset for autonomous driving](https://arxiv.org/pdf/1903.11027.pdf) [[Project Page](https://www.nuscenes.org/)] [arXiv'2019]
- H3D: [The H3D Dataset for Full-Surround 3D Multi-Object Detection and Tracking in Crowded Urban Scenes](https://arxiv.org/pdf/1903.01568.pdf) [[Project Page](https://usa.honda-ri.com//H3D)] [ICRA'2019]
- BLVD: [BLVD: Building A Large-scale 5D Semantics Benchmark for Autonomous Driving](https://arxiv.org/pdf/1903.06405v1.pdf) [[Project Page](https://github.com/VCCIV/BLVD)] [ICRA'2019]
- Waymo: [Scalability in Perception for Autonomous Driving: Waymo Open Dataset](https://arxiv.org/pdf/1912.04838.pdf) [[Project Page](https://waymo.com/open/)] [arXiv'2019]
- A* 3D: [A* 3D: An Autonomous Driving Dataset in Challeging Environments](https://arxiv.org/pdf/1909.07541.pdf) [[Project Page](https://github.com/I2RDL2/ASTAR-3D)] [ICRA'2020]
- Ford AV Dataset : [Ford Multi-AV Seasonal Dataset](https://s23.q4cdn.com/258866874/files/doc_downloads/2020/03/2003.07969.pdf) [[Project Page](https://avdata.ford.com/home/default.aspx)] [arXiv'2020]
- A2D2 : [A2D2: Audi Autonomous Driving Dataset](https://arxiv.org/pdf/2004.06320.pdf) [[Project Page](https://www.a2d2.audi/a2d2/en.html)] [arXiv'2020]
- ONCE : [One Million Scenes for Autonomous Driving: ONCE Dataset](https://arxiv.org/pdf/2106.11037.pdf) [[Project Page](https://once-for-auto-driving.github.io/index.html)] [NeurIPS'2021]
- Argoverse 2 : [Argoverse 2: Next Generation Datasets for Self-Driving Perception and Forecasting](https://openreview.net/pdf?id=vKQGe36av4k) [[Project Page](https://www.argoverse.org/av2.html)] [NeurIPS'2021]
- DAIR-V2X : [DAIR-V2X : A Large-Scale Dataset for Vehicle-Infrastructure Cooperative 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2022/papers/Yu_DAIR-V2X_A_Large-Scale_Dataset_for_Vehicle-Infrastructure_Cooperative_3D_Object_Detection_CVPR_2022_paper.pdf) [[Project Page](https://thudair.baai.ac.cn/index)] [CVPR'2022]

## Detection
### Toolbox
- [MMDetection3D](https://github.com/bostondiditeam/MV3D): MMDetection3D is an open source object detection toolbox based on PyTorch, towards the next-generation platform for general 3D detection. 
- [OpenPCDet](https://github.com/open-mmlab/OpenPCDet): OpenPCDet is a clear, simple, self-contained open source project for LiDAR-based 3D object detection.
### Outdoors
- MV3D: [Multi-View 3D Object Detection Network for Autonomous Driving](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Multi-View_3D_Object_CVPR_2017_paper.pdf) [[Code](https://github.com/bostondiditeam/MV3D)] [CVPR'2017]
- Frustum-Pointnets: [Frustum PointNets for 3D Object Detection from RGB-D Data](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf) [[Code](https://github.com/charlesq34/frustum-pointnets)] [CVPR'2018]
- PIXOR: [PIXOR: Real-time 3D Object Detection from Point Clouds](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf) [[Code](https://github.com/philip-huang/PIXOR)] [CVPR'2018]
- IPOD: [IPOD: Intensive Point-based Object Detector for Point Cloud](https://arxiv.org/pdf/1812.05276.pdf) [arXiv'2018]
- VoxelNet: [VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_VoxelNet_End-to-End_Learning_CVPR_2018_paper.pdf) [[Code](https://github.com/qianguih/voxelnet)] [CVPR'2018]
- FaF: [Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion
Forecasting with a Single Convolutional Net](http://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf) [CVPR'2018]
- Second: [SECOND: Sparsely Embedded Convolutional Detection](https://www.mdpi.com/1424-8220/18/10/3337) [[Code](https://github.com/traveller59/second.pytorch)] [Sensors'2018]
- AVOD: [Joint 3D Proposal Generation and Object Detection from View Aggregation](https://arxiv.org/pdf/1712.02294v4.pdf) [[Code](https://github.com/kujason/avod)] [IROS'2018]
- RoarNet: [RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement](https://arxiv.org/pdf/1811.03818.pdf) [[Code](https://github.com/reinforcementdriving/RoarNet)] [IV'2019]
- PointPillars: [PointPillars: Fast Encoders for Object Detection from Point Clouds](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lang_PointPillars_Fast_Encoders_for_Object_Detection_From_Point_Clouds_CVPR_2019_paper.pdf) [[Code](https://github.com/nutonomy/second.pytorch)] [CVPR'2019]
- PointRCNN: [PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_PointRCNN_3D_Object_Proposal_Generation_and_Detection_From_Point_Cloud_CVPR_2019_paper.pdf) [[Code](https://github.com/sshaoshuai/PointRCNN)] [CVPR'2019]
- Pseudo-LiDAR: [Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Pseudo-LiDAR_From_Visual_Depth_Estimation_Bridging_the_Gap_in_3D_CVPR_2019_paper.pdf) [[Code](https://github.com/mileyan/pseudo_lidar)] [CVPR'2019]
- LaserNet: [LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving](http://openaccess.thecvf.com/content_CVPR_2019/papers/Meyer_LaserNet_An_Efficient_Probabilistic_3D_Object_Detector_for_Autonomous_Driving_CVPR_2019_paper.pdf) [CVPR'2019]
- LaserNet++: [Sensor Fusion for Joint 3D Object Detection and Semantic Segmentation](http://openaccess.thecvf.com/content_CVPRW_2019/papers/WAD/Meyer_Sensor_Fusion_for_Joint_3D_Object_Detection_and_Semantic_Segmentation_CVPRW_2019_paper.pdf) [CVPR'2019 Workshop]
- Fast Point R-CNN: [Fast Point R-CNN](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chen_Fast_Point_R-CNN_ICCV_2019_paper.pdf) [ICCV'2019]
- STD: [STD: Sparse-to-Dense 3D Object Detector for Point Cloud](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_STD_Sparse-to-Dense_3D_Object_Detector_for_Point_Cloud_ICCV_2019_paper.pdf) [[Code](https://github.com/tomztyang/3DSSD)] [ICCV'2019]
- PointPainting: [PointPainting: Sequential Fusion for 3D Object Detection](https://arxiv.org/pdf/1911.10150.pdf)[arXiv'2019]
- Part-A^2: [From Points to Parts: 3D Object Detection from Point Cloud with Part-aware and Part-aggregation Network](https://arxiv.org/pdf/1907.03670v3.pdf) [[Code](https://github.com/sshaoshuai/PCDet)] [TPAMI'2020]
- Pseudo-LiDAR++: [Pseudo-LiDAR++: Accurate Depth for 3D Object Detection in Autonomous Driving](https://openreview.net/pdf?id=BJedHRVtPB) [[Code](https://github.com/mileyan/Pseudo_Lidar_V2)] [ICLR'2020]
- PV-RCNN: [PV-RCNN: Point-Voxel Feature Set Abstraction for 3D Object Detection](https://arxiv.org/pdf/1912.13192.pdf) [[Code](https://github.com/sshaoshuai/PV-RCNN)] [CVPR'2020]
- Point-GNN: [Point-GNN: Graph Neural Network for 3D Object Detection in a Point Cloud](https://arxiv.org/pdf/2003.01251v1.pdf) [[Code](https://github.com/WeijingShi/Point-GNN)] [CVPR'2020]
- SA-SSD: [Structure Aware Single-stage 3D Object Detection from Point Cloud](https://www4.comp.polyu.edu.hk/~cslzhang/paper/SA-SSD.pdf) [[Code](https://github.com/skyhehe123/SA-SSD)] [CVPR'2020]
- 3DSSD: [3DSSD: Point-based 3D Single Stage Object Detector](https://arxiv.org/pdf/2002.10187.pdf) [[Code](https://github.com/tomztyang/3DSSD)] [CVPR'2020]
- EPNet: [EPNet: Enhancing Point Features with Image Semantics for 3D Object Detection](https://arxiv.org/pdf/2007.08856.pdf) [[Code](https://github.com/happinesslz/EPNet)] [ECCV'2020]
- HotSpot: [Object as Hotspots: An Anchor-Free 3D Object Detection Approach via Firing of Hotspots](https://arxiv.org/pdf/1912.12791.pdf) [ECCV'2020]
- Pillar-MVF: [Pillar-based Object Detection for Autonomous Driving](https://arxiv.org/pdf/2007.10323.pdf) [ECCV'2020]
- Pyramid R-CNN: [Pyramid R-CNN: Towards Better Performance and Adaptability for 3D Object Detection](https://arxiv.org/pdf/2109.02499.pdf) [[Code](https://github.com/PointsCoder/Pyramid-RCNN)] [ICCV'2021]
- VoTr: [Voxel Transformer for 3D Object Detection](https://arxiv.org/pdf/2109.02497.pdf) [[Code](https://github.com/PointsCoder/VOTR)] [ICCV'2021]
- 4D-Net: [4D-Net for Learned Multi-Modal Alignment](https://openaccess.thecvf.com/content/ICCV2021/papers/Piergiovanni_4D-Net_for_Learned_Multi-Modal_Alignment_ICCV_2021_paper.pdf) [ICCV'2021]
- RangeDet: [RangeDet: In Defense of Range View for LiDAR-based 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2021/papers/Fan_RangeDet_In_Defense_of_Range_View_for_LiDAR-Based_3D_Object_ICCV_2021_paper.pdf) [[Code](https://github.com/TuSimple/RangeDet)] [ICCV'2021]
- LiDAR R-CNN: [LiDAR R-CNN: An Efficient and Universal 3D Object Detector](https://arxiv.org/pdf/2103.15297.pdf) [CVPR'2021]
- MVP: [Multimodal Virtual Point 3D Detection](https://arxiv.org/pdf/2111.06881.pdf) [[Code](https://github.com/tianweiy/MVP)] [NeurIPS'2021]
- RSN: [RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection](https://arxiv.org/pdf/2106.13365.pdf) [CVPR'2021]
- PDV: [Point Density-Aware Voxels for LiDAR 3D Object Detection](https://arxiv.org/pdf/2203.05662.pdf) [[Code](https://github.com/TRAILab/PDV)] [CVPR'2022]
- VoxSeT: [Voxel Set Transformer: A Set-to-Set Approach to 3D Object Detection from Point Clouds](https://www4.comp.polyu.edu.hk/~cslzhang/paper/VoxSeT_cvpr22.pdf) [[Code](https://github.com/skyhehe123/VoxSeT)] [CVPR'2022]
- Point2Seq: [Point2Seq: Detecting 3D Objects as Sequences](https://openaccess.thecvf.com/content/CVPR2022/papers/Xue_Point2Seq_Detecting_3D_Objects_As_Sequences_CVPR_2022_paper.pdf) [[Code](https://github.com/ocNflag/point2seq)] [CVPR'2022]
- PillarNet: [PillarNet : Real-Time and High-Performance Pillar-based 3D Object Detection](https://arxiv.org/pdf/2205.07403.pdf) [[Code](https://github.com/agent-sgs/PillarNet)] [ECCV'2022]


### Indoors
- VoteNet: [Deep Hough Voting for 3D Object Detection in Point Clouds](http://openaccess.thecvf.com/content_ICCV_2019/papers/Qi_Deep_Hough_Voting_for_3D_Object_Detection_in_Point_Clouds_ICCV_2019_paper.pdf) [[Code](https://github.com/facebookresearch/votenet)] [ICCV'2019]
- ImVoteNet: [ImVoteNet: Boosting 3D Object Detection in Point Clouds with Image Votes](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_ImVoteNet_Boosting_3D_Object_Detection_in_Point_Clouds_With_Image_CVPR_2020_paper.pdf) [[Code](https://github.com/facebookresearch/imvotenet)] [CVPR'2020]
- 3DETR: [An End-to-End Transformer Model for 3D Object Detection](https://arxiv.org/pdf/2109.08141.pdf) [[Code](https://facebookresearch.github.io/3detr)] [ICCV'2021]
- VENet: [VENet: Voting Enhancement Network for 3D Object Detection](https://openaccess.thecvf.com/content/ICCV2021/papers/Xie_VENet_Voting_Enhancement_Network_for_3D_Object_Detection_ICCV_2021_paper.pdf) [ICCV'2021]
- Group-Free: [Group-Free 3D Object Detection via Transformers](https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Group-Free_3D_Object_Detection_via_Transformers_ICCV_2021_paper.pdf) [[Code](https://github.com/zeliu98/Group-Free-3D)] [ICCV'2021]
- RBGNet: [RBGNet: Ray-based Grouping for 3D Object Detection](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_RBGNet_Ray-Based_Grouping_for_3D_Object_Detection_CVPR_2022_paper.pdf) [[Code](https://github.com/haiyang-w/rbgnet)] [CVPR'2022]
- FCAF3D: [FCAF3D: Fully Convolutional Anchor-Free 3D Object Detection](https://arxiv.org/pdf/2112.00322.pdf) [[Code](https://github.com/SamsungLabs/fcaf3d)] [ECCV'2022]

## Tracking
### MOT
- Complexer-YOLO: [Complexer-YOLO: Real-Time 3D Object Detection and Tracking on Semantic Point Clouds](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Autonomous%20Driving/Simon_Complexer_YOLO_Real-Time_3D_Object_Detection_and_Tracking_on_Semantic_CVPRW_2019_paper.pdf) [[Code](https://github.com/AI-liu/Complex-YOLO)] [CVPR'2019 Workshop]
- 3DSiamese: [Leveraging Shape Completion for 3D Siamese Tracking](http://openaccess.thecvf.com/content_CVPR_2019/papers/Giancola_Leveraging_Shape_Completion_for_3D_Siamese_Tracking_CVPR_2019_paper.pdf) [[Code](https://github.com/SilvioGiancola/ShapeCompletion3DTracking)] [CVPR'2019]
- AB3DMOT: [A Baseline for 3D Multi-Object Tracking](https://arxiv.org/pdf/1907.03961.pdf) [[Code](https://github.com/xinshuoweng/AB3DMOT)] [arXiv'2019]
- mmMOT: [Robust Multi-Modality Multi-Object Tracking](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Robust_Multi-Modality_Multi-Object_Tracking_ICCV_2019_paper.pdf) [[Code](https://github.com/ZwwWayne/mmMOT)] [ICCV'2019]
- DSM: [End-to-end Learning of Multi-sensor 3D Tracking by Detection](https://arxiv.org/pdf/1806.11534.pdf) [ICRA'2019]
- PointTrackNet: [PointTrackNet: An End-to-End Network for 3-D
Object Detection and Tracking from Point Clouds](https://www.ram-lab.com/papers/2020/wang2020pointtracknet.pdf) [ICRA'2020]
- Mahalanobis-KF: [Probabilistic 3D Multi-Object Tracking for Autonomous Driving](https://arxiv.org/pdf/2001.05673.pdf) [[Code](https://github.com/eddyhkchiu/mahalanobis_3d_multi_object_tracking)] [arXiv'2020]
- GNN3DMOT: [GNN3DMOT: Graph Neural Network for 3D Multi-Object Tracking with 2D-3D Multi-Feature Learning](https://openaccess.thecvf.com/content_CVPR_2020/papers/Weng_GNN3DMOT_Graph_Neural_Network_for_3D_Multi-Object_Tracking_With_2D-3D_CVPR_2020_paper.pdf) [[Code](https://github.com/xinshuoweng/GNN3DMOT)] [CVPR'2020]
- PC-TCNN: [Tracklet Proposal Network for Multi-Object Tracking on Point Clouds](https://www.ijcai.org/proceedings/2021/0161.pdf) [IJCAI'2021]
- LOGR: [Learnable Online Graph Representations for 3D Multi-Object Tracking](https://arxiv.org/pdf/2104.11747.pdf) [arXiv'2021]
- CenterPoint: [Center-based 3D Object Detection and Tracking](https://openaccess.thecvf.com/content/CVPR2021/papers/Yin_Center-Based_3D_Object_Detection_and_Tracking_CVPR_2021_paper.pdf) [[Code](https://github.com/tianweiy/CenterPoint)] [CVPR'2021]
- Immortal-Tracker: [Immortal Tracker: Tracklet Never Dies](https://arxiv.org/pdf/2111.13672.pdf) [[Code](https://github.com/immortaltracker/immortaltracker)] [arXiv'2021]
- SimpleTrack: [SimpleTrack: Understanding and Rethinking 3D Multi-object Tracking](https://arxiv.org/pdf/2111.09621.pdf) [[Code](https://github.com/TuSimple/SimpleTrack)] [arXiv'2021]
### SOT
- P2B: [P2B: Point-to-Box Network for 3D Object Tracking in Point Clouds](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_P2B_Point-to-Box_Network_for_3D_Object_Tracking_in_Point_Clouds_CVPR_2020_paper.pdf) [[Code](https://github.com/HaozheQi/P2B)] [CVPR'2020]
- PTT: [PTT: Point-Track-Transformer Module for 3D Single Object Tracking in Point Clouds](https://arxiv.org/pdf/2108.06455.pdf) [[Code](https://github.com/shanjiayao/PTT)] [IROS'2021]
- BAT: [Box-Aware Feature Enhancement for Single Object Tracking on Point Clouds](https://openaccess.thecvf.com/content/ICCV2021/papers/Zheng_Box-Aware_Feature_Enhancement_for_Single_Object_Tracking_on_Point_Clouds_ICCV_2021_paper.pdf) [[Code](https://github.com/Ghostish/BAT)] [ICCV'2021]
- LTTR: [3D Object Tracking with Transformer](https://arxiv.org/pdf/2110.14921.pdf) [[Code](https://github.com/3bobo/lttr)] [BMVC'2021]
- V2B: [3D Siamese Voxel-to-BEV Tracker for Sparse Point Clouds](https://arxiv.org/pdf/2111.04426.pdf) [[Code](https://github.com/fpthink/V2B)] [NeurIPS'2021]
- PTTR: [PTTR: Relational 3D Point Cloud Object Tracking with Transformer](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_PTTR_Relational_3D_Point_Cloud_Object_Tracking_With_Transformer_CVPR_2022_paper.pdf) [[Code](https://github.com/Jasonkks/PTTR)] [CVPR'2022]
- M2-Tracker: [Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Beyond_3D_Siamese_Tracking_A_Motion-Centric_Paradigm_for_3D_Single_CVPR_2022_paper.pdf) [[Code](https://github.com/Ghostish/Open3DSOT)] [CVPR'2022]
- STNet: [3D Siamese Transformer Network for Single Object Tracking on Point Clouds](https://arxiv.org/pdf/2207.11995.pdf) [[Code](https://github.com/fpthink/STNet)] [ECCV'2022]
- SMAT: [Exploiting More Information in Sparse Point Cloud for 3D Single Object Tracking](https://ieeexplore.ieee.org/document/9899707) [[Code](https://github.com/3bobo/smat)] [RAL]