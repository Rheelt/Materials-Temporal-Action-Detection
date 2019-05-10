# Papers: weakly temporal action detection
- (WSGN) **Weakly Supervised Gaussian Networks for Action Detection** (Arxiv 2019.4)
- (RefineLoc) **RefineLoc: Iterative Refinement for Weakly-Supervised Action Localization** (Arxiv 2019.4)
- (STAR) **Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection** (AAAI 2019)
- (TSRNet) **Learning Transferable Self-attentive Representations for Action Recognition in Untrimmed Videos with Weak Supervision** (AAAI 2019)
- (StepByStep) **Step-by-step Erasion, One-by-one Collection: AWeakly Supervised Temporal Action Detector** (MM 2018)
- (W-TALC) **W-TALC: Weakly-supervised Temporal Activity Localization and Classification** (ECCV 2018)
- (AutoLoc) **AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos** (ECCV 2018)
- (STPN) **Weakly Supervised Action Localization by Sparse Temporal Pooling Network** (CVPR 2018)
- (H&S) **Hide-and-seek: Forcing a network to be meticulous for weakly-supervised object and action localization** (ICCV 2017)
- (UNet) **UntrimmedNets for Weakly Supervised Action Recognition and Detection** (CVPR 2017)

# Benchmark Results (THUMOS14 Results)
These methods are listed in chronological order.


| Method | Feature | IoU-> | 0.1 | 0.2 | 0.3   | 0.4    | 0.5    | 0.6    | 0.7 |
| :----: | :----: | :----:|:----:|:----:|:----:| :----: | :----: | :----: |:----:|
| WSGN | I3D |       | 55.3 | 47.6  | 38.9 | 30.0 | 21.1 |  **13.9**   |  **8.3**|
| RefineLoc | UNet |       |     |     |   33.9 |      |   22.1 |     |     6.1 |
| STAR      | I3D |       |  **68.8**|  **60.0**| **48.7**|    **34.7**|   **23.0** |     |      |
| TSRNet    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| StepByStep    | TSN |       |  45.8| 39.0| 31.1 | 22.5 | 15.9 |  |   |
| W-TALC    | UNet |       |  49.0|  42.8| 32.0 | 26.0 | 18.8 |   |  6.2 |
| W-TALC    | I3D |       |  55.2|  49.6| 40.1 |  31.1 |  22.8 |   |  7.6 |
| AutoLoc    | UNet |       |  |   |35.8 |  29.0 | 21.2 |13.4 | 5.8 |
| STPN    |I3D |       |  52.0|  44.7| 35.5 |  25.8 |  16.9 | 9.9 |  4.3 |
| H&S    |C3D |       |  36.4|  27.8| 19.5 |  12.7 |  6.8|   |    |
| UNet    | UNet |       |  44.4|  37.7| 28.2 |  21.1 |  13.7 |   |    |

