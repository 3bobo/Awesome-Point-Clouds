# Awesome-Point-Clouds
Awesome paper/code for point clouds with deep learning methods in detection and tracking. If you find some novel methods or have suggestions, please contact ybcui95@163.com

## Datasets
- KITTI: [Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite](http://www.cvlibs.net/publications/Geiger2012CVPR.pdf) [[Project Page](http://www.cvlibs.net/datasets/kitti/index.php)] [CVPR'2012]
- Apolloscape: [The ApolloScape Dataset for Autonomous Driving](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Huang_The_ApolloScape_Dataset_CVPR_2018_paper.pdf) [[Project Page](http://apolloscape.auto/)] [CVPR'2018]
- Argoverse: [Argoverse: 3D Tracking and Forecasting with Rich Maps](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf) [[Project Page](https://www.argoverse.org/index.html)] [CVPR'2019]
- Nuscenes: [nuScenes: A multimodal dataset for autonomous driving](https://arxiv.org/pdf/1903.11027.pdf) [[Project Page](https://www.nuscenes.org/)] [arXiv'2019]
- H3D: [The H3D Dataset for Full-Surround 3D Multi-Object Detection and Tracking in Crowded Urban Scenes](https://arxiv.org/pdf/1903.01568.pdf) [[Project Page](https://usa.honda-ri.com//H3D)] [ICAR'2019]
- BLVD: [BLVD: Building A Large-scale 5D Semantics Benchmark for Autonomous Driving](https://arxiv.org/pdf/1903.06405v1.pdf) [[Project Page](https://github.com/VCCIV/BLVD)] [ICAR'2019]
- Waymo: [Scalability in Perception for Autonomous Driving: Waymo Open Dataset](https://arxiv.org/pdf/1912.04838.pdf) [[Project Page](https://waymo.com/open/)] [arXiv'2019]
- A* 3D: [A* 3D: An Autonomous Driving Dataset in Challeging Environments](https://arxiv.org/pdf/1909.07541.pdf) [[Project Page](https://github.com/I2RDL2/ASTAR-3D)] [ICRA'2020]
- Ford AV Dataset : [Ford Multi-AV Seasonal Dataset](https://s23.q4cdn.com/258866874/files/doc_downloads/2020/03/2003.07969.pdf) [[Project Page](https://avdata.ford.com/home/default.aspx)] [arXiv'2020]
- A2D2 : [A2D2: Audi Autonomous Driving Dataset](https://arxiv.org/pdf/2004.06320.pdf) [[Project Page](https://www.a2d2.audi/a2d2/en.html)] [arXiv'2020]

## Detection
The collected methods do not include all papers in point cloud object detection. The condition is that either the paper has released code or its result is at the top in leaderboard. 

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
- VoteNet: [Deep Hough Voting for 3D Object Detection in Point Clouds](http://openaccess.thecvf.com/content_ICCV_2019/papers/Qi_Deep_Hough_Voting_for_3D_Object_Detection_in_Point_Clouds_ICCV_2019_paper.pdf) [[Code](https://github.com/facebookresearch/votenet)] [ICCV'2019]
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

## Tracking
- Complexer-YOLO: [Complexer-YOLO: Real-Time 3D Object Detection and Tracking on Semantic Point Clouds](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Autonomous%20Driving/Simon_Complexer_YOLO_Real-Time_3D_Object_Detection_and_Tracking_on_Semantic_CVPRW_2019_paper.pdf) [[Code](https://github.com/AI-liu/Complex-YOLO)] [CVPR'2019 Workshop]
- 3DSiamese: [Leveraging Shape Completion for 3D Siamese Tracking](http://openaccess.thecvf.com/content_CVPR_2019/papers/Giancola_Leveraging_Shape_Completion_for_3D_Siamese_Tracking_CVPR_2019_paper.pdf) [[Code](https://github.com/SilvioGiancola/ShapeCompletion3DTracking)] [CVPR'2019]
- AB3DMOT: [A Baseline for 3D Multi-Object Tracking](https://arxiv.org/pdf/1907.03961.pdf) [[Code](https://github.com/xinshuoweng/AB3DMOT)] [arXiv'2019]
- mmMOT: [Robust Multi-Modality Multi-Object Tracking](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Robust_Multi-Modality_Multi-Object_Tracking_ICCV_2019_paper.pdf) [[Code](https://github.com/ZwwWayne/mmMOT)] [ICCV'2019]
- DSM: [End-to-end Learning of Multi-sensor 3D Tracking by Detection](https://arxiv.org/pdf/1806.11534.pdf) [ICRA'2019]
- PointTrackNet: [PointTrackNet: An End-to-End Network for 3-D
Object Detection and Tracking from Point Clouds](https://www.ram-lab.com/papers/2020/wang2020pointtracknet.pdf) [ICRA'2020]
- Mahalanobis-KF: [Probabilistic 3D Multi-Object Tracking for Autonomous Driving](https://arxiv.org/pdf/2001.05673.pdf) [[Code](https://github.com/eddyhkchiu/mahalanobis_3d_multi_object_tracking)] [arXiv'2020]
- P2B: [P2B: Point-to-Box Network for 3D Object Tracking in Point Clouds](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qi_P2B_Point-to-Box_Network_for_3D_Object_Tracking_in_Point_Clouds_CVPR_2020_paper.pdf) [[Code](https://github.com/HaozheQi/P2B)] [CVPR'2020]

## Segmentation
Segmentation part includes instance segmentation and semantic segmentation papers.

- SqueezeSeg: [SqueezeSeg: Convolutional Neural Nets with Recurrent CRF for Real-Time Road-Object Segmentation from 3D LiDAR Point Cloud](https://arxiv.org/pdf/1710.07368.pdf) [[Code](https://github.com/BichenWuUCB/SqueezeSeg)] [ICRA'2018]
- SGPN: [SGPN: Similarity Group Proposal Network for 3D Point Cloud Instance Segmentation](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_SGPN_Similarity_Group_CVPR_2018_paper.pdf) [[Code](https://github.com/laughtervv/SGPN)] [CVPR'2018]
- SqueezeSegV2: [SqueezeSegV2: Improved Model Structure and Unsupervised Domain Adaptation for Road-Object Segmentation from a LiDAR Point Cloud](https://arxiv.org/pdf/1809.08495.pdf) [[Code](https://github.com/xuanyuzhou98/SqueezeSegV2)] [ICRA'2019]
- RangeNet++: [RangeNet++: Fast and Accurate LiDAR Semantic Segmentation](http://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/milioto2019iros.pdf) [[Code](https://github.com/PRBonn/lidar-bonnetal)] [IROS'2019]
- LU-Net: [LU-Net: An Efficient Network for 3D LiDAR Point Cloud Semantic Segmentation Based on End-to-End-Learned 3D Features and U-Net](https://arxiv.org/pdf/1908.11656.pdf) [[Code](https://github.com/pbias/lunet)] [CVPR'2019 Workshop]
- PolarNet: [PolarNet: An Improved Grid Representation for Online LiDAR Point Clouds Semantic Segmentation](https://arxiv.org/pdf/2003.14032.pdf) [[Code](https://github.com/edwardzhou130/PolarSeg)] [CVPR'2020]
- RandLA-Net: [RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds](https://arxiv.org/pdf/1911.11236.pdf) [[Code](https://github.com/QingyongHu/RandLA-Net)] [CVPR'2020]
- 3D-MiniNet: [3D-MiniNet: Learning a 2D Representation from Point Clouds for Fast and Efficient 3D LIDAR Semantic Segmentation](https://arxiv.org/pdf/2002.10893v2.pdf) [[Code](https://github.com/Shathe/3D-MiniNet)] [arXiv'2020]
- 3D-MPA: [3D-MPA: Multi Proposal Aggregation for 3D Semantic Instance Segmentation](https://arxiv.org/pdf/2003.13867v1.pdf)  [CVPR'2020]
