# Papers: temporal action proposals & detection
- (TGM) **Temporal Gaussian Mixture Layer for Videos** (ICML 2019)
- (MGG) **Multi-granularity Generator for Temporal Action Proposal** (CVPR 2019)

# Papers: weakly temporal action detection
- (CMCS) **Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization** (CVPR19)[CODE.pytorch](https://github.com/Finspire13/CMCS-Temporal-Action-Localization)
- **Weakly-Supervised Temporal Localization via Occurrence Count Learning** (ICML 2019)
- (WSGN) **Weakly Supervised Gaussian Networks for Action Detection** (Arxiv 2019.4) 
- (RefineLoc) **RefineLoc: Iterative Refinement for Weakly-Supervised Action Localization** (Arxiv 2019.4)
- (STAR) **Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection** (AAAI 2019)
- (TSRNet) **Learning Transferable Self-attentive Representations for Action Recognition in Untrimmed Videos with Weak Supervision** (AAAI 2019)
- (StepByStep) **Step-by-step Erasion, One-by-one Collection: AWeakly Supervised Temporal Action Detector** (MM 2018)
- (W-TALC) **W-TALC: Weakly-supervised Temporal Activity Localization and Classification** (ECCV 2018) [CODE.pytorch](https://github.com/sujoyp/wtalc-pytorch)
- (AutoLoc) **AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos** (ECCV 2018) [CODE.caffe](https://github.com/zhengshou/AutoLoc)
- (STPN) **Weakly Supervised Action Localization by Sparse Temporal Pooling Network** (CVPR 2018) [CODE.tensorflow.unofficial](https://github.com/bellos1203/STPN)
- (H&S) **Hide-and-seek: Forcing a network to be meticulous for weakly-supervised object and action localization** (ICCV 2017)
- (UNet) **UntrimmedNets for Weakly Supervised Action Recognition and Detection** (CVPR 2017) [CODE.caffe](https://github.com/wanglimin/UntrimmedNet)

# Features: Download link
**THUMOS14**
- C3D: [link](https://github.com/wzmsltw/BSN-boundary-sensitive-network/issues/24)
- I3D: Video is sampled at 25 frames per second. 16 frames as a video unit. [link](https://github.com/sujoyp/wtalc-pytorch)
- UNet: [link](https://github.com/zhengshou/AutoLoc)
- ANet2016-cuhk(4096dims): 6 frames as a video unit. [link](https://github.com/jiyanggao/CTAP)
- ANet2016-cuhk(3072dims): 5 frames as a video unit. [link](https://drive.google.com/open?id=1gCNYPf6Fxeht1HO3eIzuyj84gtbkPETx)

**ActivityNet v1.2**
- I3D: Video is sampled at 25 frames per second. 16 frames as a video unit. [link](https://github.com/sujoyp/wtalc-pytorch)
- UNet: [link](https://github.com/zhengshou/AutoLoc)

**ActivityNet v1.3**
- C3D: [link](http://activity-net.org/challenges/2016/download.html)
- ANet2016-cuhk(400dims): 16 frames as a video unit. [link](https://github.com/wzmsltw/BSN-boundary-sensitive-network) 
- I3D: 16 frames as a video unit. wait...
- ANet2016-cuhk(3072dims): 16 frames as a video unit. wait...

# Benchmark Results (THUMOS14 Results)
These methods are listed in chronological order.


| Method | Feature | IoU-> | 0.1 | 0.2 | 0.3   | 0.4    | 0.5    | 0.6    | 0.7 |
| :----: | :----: | :----:|:----:|:----:|:----:| :----: | :----: | :----: |:----:|
| CMCS | I3D |       | 57.4 | 50.8  | 41.2 | 32.1 | **23.1** |  **15.0**   |  7.0|
| WSGN | I3D |       | 55.3 | 47.6  | 38.9 | 30.0 | 21.1 |  13.9   |  **8.3**|
| RefineLoc | UNet |       |     |     |   33.9 |      |   22.1 |     |     6.1 |
| STAR      | I3D |       |  **68.8**|  **60.0**| **48.7**|    **34.7**|   23.0 |     |      |
| TSRNet    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| StepByStep    | TSN |       |  45.8| 39.0| 31.1 | 22.5 | 15.9 |  |   |
| W-TALC    | UNet |       |  49.0|  42.8| 32.0 | 26.0 | 18.8 |   |  6.2 |
| W-TALC    | I3D |       |  55.2|  49.6| 40.1 |  31.1 |  22.8 |   |  7.6 |
| AutoLoc    | UNet |       |  |   |35.8 |  29.0 | 21.2 |13.4 | 5.8 |
| STPN    |I3D |       |  52.0|  44.7| 35.5 |  25.8 |  16.9 | 9.9 |  4.3 |
| H&S    |C3D |       |  36.4|  27.8| 19.5 |  12.7 |  6.8|   |    |
| UNet    | UNet |       |  44.4|  37.7| 28.2 |  21.1 |  13.7 |   |    |

