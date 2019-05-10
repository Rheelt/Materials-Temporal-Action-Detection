# Papers: weakly temporal action detection
- (WSGN) Weakly Supervised Gaussian Networks for Action Detection (Arxiv 2019.4)
- (RefineLoc) RefineLoc: Iterative Refinement for Weakly-Supervised Action Localization (Arxiv 2019.4)
- (STAR) Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection (AAAI 2019)
- (TSRNet) Learning Transferable Self-attentive Representations for Action Recognition in Untrimmed Videos with Weak Supervision (AAAI 2019)
- (StepByStep) Step-by-step Erasion, One-by-one Collection: AWeakly Supervised Temporal Action Detector (MM 2018)
- (W-TALC) W-TALC: Weakly-supervised Temporal Activity Localization and Classification (ECCV 2018)
- (AutoLoc) AutoLoc: Weakly-supervised Temporal Action Localization in Untrimmed Videos (ECCV 2018)
- (STPN) Weakly Supervised Action Localization by Sparse Temporal Pooling Network (CVPR 2018)
- (H&S) Hide-and-seek: Forcing a network to be meticulous for weakly-supervised object and action localization (ICCV 2017)
- (UntrimmedNet) UntrimmedNets for Weakly Supervised Action Recognition and Detection (CVPR 2017)

# Benchmark Results (THUMOS14 Results)
These methods are listed in chronological order.


| Method | Feature | IoU-> | 0.1 | 0.2 | 0.3   | 0.4    | 0.5    | 0.6    | 0.7 |
| :----: | :----: | :----:|:----:|:----:|:----:| :----: | :----: | :----: |:----:|
| WSGN | UNet |       |     |     |   33.9 |      |   22.1 |     |     6.1 |
| RefineLoc | UNet |       |     |     |   33.9 |      |   22.1 |     |     6.1 |
| STAR      | I3D |       |  68.8|  60.0| 48.7|    34.7|   23.0 |     |      |
| TSRNet    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| StepByStep    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| W-TALC    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| AutoLoc    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| STPN    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| H&S    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |
| UntrimmedNet    | 2-Stream(ResNet101) |       |  55.9|  46.9| 38.3 |  28.1 |  18.6 | 11.0 |  5.59 |

