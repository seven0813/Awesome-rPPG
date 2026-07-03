# Awesome-rPPG-Method-List

> Last updated: 2026-07-02

This repository is a collection of rPPG methods. I will update it gradually, if you have any suggestions or questions, please feel free to contact me. If you know any other methods, please create a issue or pull request. If you find this repository helpful, please give me a star.

- [Awesome Papers](#Awesome-Papers)
  - [Survey](#survey)
  - [Traditional Methods](#traditional-methods)
  - [Supervised Learning](#supervised-learning)
  - [Self-Supervised Learning](#self-supervised-learning)
  - [Multimodal](#multimodal)
  - [Other Methods](#other-methods)
  - [Benchmark](#benchmark)
  - [Dataset](#dataset)
- [Acknowledgments](#acknowledgments)


## Awesome Papers

### Survey

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Remote photoplethysmography for heart rate measurement: A review**](https://www.sciencedirect.com/science/article/abs/pii/S1746809423010418)| Biomedical Signal Processing and Control 2023 | - |
|[**Camera Measurement of Physiological Vital Signs**](https://arxiv.org/pdf/2111.11547)| ACM Computing Surveys 2021 | - |
|[**Video-Based Heart Rate Measurement: Recent Advances and Future Prospects**](https://ieeexplore.ieee.org/document/8552414) | TIM 2019 | - |


### Traditional Methods

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Face2PPG: An Unsupervised Pipeline for Blood Volume Pulse Extraction From Faces**](https://ieeexplore.ieee.org/document/10227326) (**OMIT**)| IEEE JBHI 2023| - |
|[**Local Group Invariance for Heart Rate Estimation from Face Videos in the Wild**](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w27/Pilz_Local_Group_Invariance_CVPR_2018_paper.pdf) (**LGI**)| CVPR Workshop 2018 | - |
|[**Algorithmic Principles of Remote PPG**](https://ieeexplore.ieee.org/document/7565547) (**POS**)| IEEE TBME 2016 | - |
|[**A Novel Algorithm for Remote Photoplethysmography: Spatial Subspace Rotation**](https://ieeexplore.ieee.org/document/7355301) (**2SR**)| IEEE TBME 2015 | - |
|[**Improved motion robustness of remote-PPG by using the blood volume pulse signature**](https://iopscience.iop.org/article/10.1088/0967-3334/35/9/1913) (**PBV**)| Physiological Measurement 2014 | - |
|[**Robust Pulse Rate From Chrominance-Based rPPG**](https://ieeexplore.ieee.org/document/6523142) (**CHROM**)| IEEE TBME 2013 | - |
|[**Measuring pulse rate with a webcam—a non-contact method for evaluating cardiac activity**](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=7ad15b6fecdb9b2ad49be5bf26efafe22c9a8945) (**PCA**)| FedCSIS 2011 | - |
|[**Remote plethysmographic imaging using ambient light**](https://pdfs.semanticscholar.org/7cb4/46d61a72f76e774b696515c55c92c7aa32b6.pdf?_gl=1*1q7hzyz*_ga*NTEzMzk5OTY3LjE2ODYxMDg1MjE.*_ga_H7P4ZT52H5*MTY4NjEwODUyMC4xLjAuMTY4NjEwODUyMS41OS4wLjA)| Optics Express 2008 | |


### Supervised Learning

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**FactorizePhys: Matrix Factorization for Multidimensional Attention in Remote Physiological Sensing**](https://openreview.net/pdf?id=qrfp4eeZ47)(**FactorizePhys**) | NeurIPS 2024| [github](https://github.com/PhysiologicAILab/FactorizePhys) |
|[**Dual-bridging with Adversarial Noise Generation for Domain Adaptive rPPG Estimation**](https://openaccess.thecvf.com/content/CVPR2023/papers/Du_Dual-Bridging_With_Adversarial_Noise_Generation_for_Domain_Adaptive_rPPG_Estimation_CVPR_2023_paper.pdf) | CVPR 2023| -|
|[**PhysFormer++: Facial Video-Based Physiological Measurement with SlowFast Temporal Difference Transformer**](https://link.springer.com/article/10.1007/s11263-023-01758-1) (**PhysFormer++**)| IJCV 2023| -|
|[**EfficientPhys: Enabling Simple, Fast and Accurate Camera-Based Cardiac Measurement**](https://openaccess.thecvf.com/content/WACV2023/papers/Liu_EfficientPhys_Enabling_Simple_Fast_and_Accurate_Camera-Based_Cardiac_Measurement_WACV_2023_paper.pdf) (**EfficientPhys**)| WACV 2023| [github](https://github.com/anonymous0paper/EfficientPhys)|
|[**RADIANT: Better rPPG estimation using signal embeddings and Transformer**](https://openaccess.thecvf.com/content/WACV2023/papers/Gupta_RADIANT_Better_rPPG_Estimation_Using_Signal_Embeddings_and_Transformer_WACV_2023_paper.pdf) (**RADIANT**)| WACV 2023| [github](https://github.com/Deep-Intelligence-Lab/RADIANT)|
|[**Augmentation of rPPG Benchmark Datasets: Learning to Remove and Embed rPPG Signals via Double Cycle Consistent Learning from Unpaired Facial Videos**](https://link.springer.com/chapter/10.1007/978-3-031-19787-1_21)(**RErPPGNet**) | ECCV 2022| [github](https://github.com/nthumplab/RErPPGNet) |
|[**PhysFormer: Facial Video-based Physiological Measurement with Temporal Difference Transformer**](https://arxiv.org/pdf/2111.12082) (**PhysFormer**)| CVPR 2022| [github](https://github.com/ZitongYu/PhysFormer)|
|[**ETA-rPPGNet: Effective Time-Domain Attention Network for Remote Heart Rate Measurement**](https://ieeexplore.ieee.org/abstract/document/9353569) (**ETA-rPPGNet**)| IEEE TIM 2021| - |
|[**Deep Super-Resolution Network for rPPG Information Recovery and Noncontact Heart Rate Estimation**](https://ieeexplore.ieee.org/document/9529062) | IEEE TIM 2021| - |
|[**Visual heart rate estimation with convolutional neural network**](https://www.sciencedirect.com/science/article/pii/S2096579620301121) (**NAS-HR**)| Virtual Reality & Intelligent Hardware 2021| [github](https://github.com/LuPaoPao/NAS-HR) |
|[**Dual-GAN: Joint BVP and Noise Modeling for Remote Physiological Measurement**](https://openaccess.thecvf.com/content/CVPR2021/papers/Lu_Dual-GAN_Joint_BVP_and_Noise_Modeling_for_Remote_Physiological_Measurement_CVPR_2021_paper.pdf) (**Dual-GAN**)| CVPR 2021| -|
|[**PulseGAN: Learning to Generate Realistic Pulse Waveforms in Remote Photoplethysmography**](https://ieeexplore.ieee.org/document/9320513) (**PulseGAN**)| IEEE JBHI 2021| [github](https://github.com/miki998/PulseGAN)|
|[**Deep-HR: Fast heart rate estimation from face video under realistic conditions**](https://www.sciencedirect.com/science/article/abs/pii/S0957417421009969) (**Deep-HR**)| Expert Systems with Applications 2021| [github](https://github.com/miki998/PulseGAN)|
|[**Multi-Task Temporal Shift Attention Networks for On-Device Contactless Vitals Measurement**](https://arxiv.org/pdf/2006.03790) (**MTTS-CAN**)| NeurIPS 2020| [github](https://github.com/xliucs/MTTS-CAN) |
|[**RhythmNet: End-to-End Heart Rate Estimation From Face via Spatial-Temporal Representation**](http://refhub.elsevier.com/S1746-8094(23)01041-8/sb47) (**RhythmNet**)| IEEE TIP 2020| [github](https://github.com/AnweshCR7/RhythmNet) |
|[**Video-Based Remote Physiological Measurement via Cross-Verified Feature Disentangling**](http://refhub.elsevier.com/S1746-8094(23)01041-8/sb48) (**CVD**)| ECCV 2020 oral| [github](https://github.com/nxsEdson/CVD-Physiological-Measurement) |
|[**Siamese-rPPG network: remote photoplethysmography signal estimation from face videos**](https://dl.acm.org/doi/abs/10.1145/3341105.3373905) (**Siamese-rPPG**)| ACM SAC 2020| - |
|[**AutoHR: A Strong End-to-End Baseline for Remote Heart Rate Measurement With Neural Searching**](https://ieeexplore.ieee.org/document/9133501) (**AutoHR**)| IEEE SPL 2020| - |
|[**HeartTrack: Convolutional neural network for remote video-based heart rate monitoring**](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w19/Perepelkina_HeartTrack_Convolutional_Neural_Network_for_Remote_Video-Based_Heart_Rate_Monitoring_CVPRW_2020_paper.pdf) (**HeartTrack**)| CVPR Workshop 2020| - |
|[**Meta-rPPG: Remote Heart Rate Estimation Using a Transductive Meta-learner**](https://link.springer.com/chapter/10.1007/978-3-030-58583-9_24) (**Meta-rPPG**)| ECCV 2020| [github](https://github.com/eugenelet/Meta-rPPG)|
|[**Long short-term memory deep-filter in remote photoplethysmography**](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w19/Botina-Monsalve_Long_Short-Term_Memory_Deep-Filter_In_Remote_Photoplethysmography_CVPRW_2020_paper.pdf) |CVPR Workshop 2020| -|
|[**Remote Heart Rate Measurement from Highly Compressed Facial Videos: an End-to-end Deep Learning Solution with Video Enhancement**](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Remote_Heart_Rate_Measurement_From_Highly_Compressed_Facial_Videos_An_ICCV_2019_paper.pdf) (**rPPGNet**)| ICCV 2019| [github](https://github.com/ZitongYu/STVEN_rPPGNet) |
|[**Remote Photoplethysmograph Signal Measurement from Facial Videos Using Spatio-Temporal Networks**](https://arxiv.org/abs/1905.02419) (**PhysNet**)| BMCV 2019| [github](https://github.com/ZitongYu/PhysNet) |
|[**3D Convolutional Neural Networks for Remote Pulse Rate Measurement and Mapping from Facial Video**](https://www.mdpi.com/2076-3417/9/20/4364)(**rppg-3dcnn**) | Applied Science 2019| [github](https://github.com/frederic-bousefsaf/ippg-3dcnn) |
|[**Vision-Based Heart Rate Estimation Via A Two-Stream CNN**](https://ieeexplore.ieee.org/document/8803649) |ICIP 2019| -|
|[**An Accurate LSTM Based Video Heart Rate Estimation Method**](https://link.springer.com/chapter/10.1007/978-3-030-31726-3_35) |PRCV 2019| -|
|[**SynRhythm: Learning a Deep Heart Rate Estimator from General to Specificn**](https://ieeexplore.ieee.org/document/8546321)(**SynRhythm**) | ICPR 2018| - |
|[**EVM-CNN: Real-Time Contactless Heart Rate Estimation From Facial Video**](https://ieeexplore.ieee.org/abstract/document/8552438) (**EVM-CNN**)| IEEE TMM 2018| - |
|[**DeepPhys: Video-Based Physiological Measurement Using Convolutional Attention Networks**](https://openaccess.thecvf.com/content_ECCV_2018/papers/Weixuan_Chen_DeepPhys_Video-Based_Physiological_ECCV_2018_paper.pdf) (**DeepPhys**)| ECCV 2018| [github](https://github.com/ubicomplab/rPPG-Toolbox) |
|[**Visual heart rate estimation with convolutional neural network**](https://cmp.felk.cvut.cz/~spetlrad/ecg-fitness/visual-heart-rate.pdf) (**HR-CNN**)| BMVC 2018| [github](https://github.com/radimspetlik/hr-cnn) |
|[**Instantaneous Physiological Estimation Using Video Transformers**](https://link.springer.com/chapter/10.1007/978-3-031-14771-5_22) (**instantaneous_transformer**)| -| [github](https://github.com/revanurambareesh/instantaneous_transformer)|

### Self-Supervised Learning

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**rPPG-VQA: A Video Quality Assessment Framework for Unsupervised rPPG Training**](http://arxiv.org/abs/2604.11156) (**rPPG-VQA**)| CVPR 2026 | [github](https://github.com/Tianyang-Dai/rPPG-VQA)|
|[**Style-rPPG: Exploration and Analysis of Style Transfer in Unsupervised Remote Physiological Measurement**](https://doi.org/10.1016/j.eswa.2024.126310) (**Style-rPPG**)| Expert Systems with Applications 2025 | -|
|[**Semi-rPPG: Semi-Supervised Remote Physiological Measurement with Curriculum Pseudo-Labeling**](http://arxiv.org/abs/2502.03855) (**Semi-rPPG**)| IEEE TIM 2025 | -|
|[**rPPG-NDCL: Unsupervised Remote Physiological Measurement Via Noise-Disentangled Contrastive Learning**](https://doi.org/10.1109/ICIP55913.2025.11084290) (**rPPG-NDCL**)| ICIP 2025 | [github](https://github.com/Tianyang-Dai/rPPG-NDCL)|
|[**Contrast-Phys+: Unsupervised and Weakly-Supervised Video-Based Remote Physiological Measurement via Spatiotemporal Contrast**](https://doi.org/10.1109/TPAMI.2024.3367910) (**Contrast-Phys+**)| IEEE TPAMI 2024 | -|
|[**RS-rPPG: Robust Self-Supervised Learning for rPPG**](https://brosdocs.net/fg2024/013.pdf) (**RS-rPPG**)| IEEE FG 2024 | [github](https://github.com/marukosan93/RS-rPPG)|
|[**SiNC+: Adaptive Camera-Based Vitals with Unsupervised Learning of Periodic Signals**](http://arxiv.org/abs/2404.13449) (**SiNC+**)| arXiv 2024 | -|
|[**Self-Similarity Prior Distillation for Unsupervised Remote Physiological Measurement**](https://doi.org/10.1109/TMM.2024.3405720) (**SSPD**)| IEEE TMM 2024 | -|
|[**rPPG-MAE: Self-supervised Pre-training with Masked Autoencoders for Remote Physiological Measurement**](https://arxiv.org/abs/2306.02301) (**rPPG-MAE**)| arXiv 2023 | [github](https://github.com/keke-nice/rPPG-MAE)|
|[**Non-Contrastive Unsupervised Learning of Physiological Signals from Video**](https://openaccess.thecvf.com/content/CVPR2023/papers/Speth_Non-Contrastive_Unsupervised_Learning_of_Physiological_Signals_From_Video_CVPR_2023_paper.pdf) (**SiNC-rPPG**)| CVPR 2023 Highlight | [github](https://github.com/CVRL/SiNC-rPPG)|
|[**SimPer: Simple Self-Supervised Learning of Periodic Targets**](https://arxiv.org/abs/2210.03115) (**SimPer**)| ICLR 2023 Oral | [github](https://github.com/yyzharry/simper)|
|[**Facial Video-based Remote Physiological Measurement via Self-supervised Learning**](https://arxiv.org/abs/2210.15401) | IEEE TPAMI 2023 | [github](https://github.com/yuezijie/video-based-remote-physiological-measurement-via-self-supervised-learning)|
|[**Contactless Pulse Estimation Leveraging Pseudo Labels and Self-Supervision**](https://doi.org/10.1109/ICCV51070.2023.01882) | ICCV 2023 | -|
|[**Contrast-Phys: Unsupervised Video-Based Remote Physiological Measurement via Spatiotemporal Contrast**](https://link.springer.com/chapter/10.1007/978-3-031-19775-8_29)(**Contrast-Phys**) | ECCV 2022 | [github](https://github.com/zhaodongsun/contrast-phys)|
|[**Self-Supervised RGB-NIR Fusion Video Vision Transformer Framework for rPPG Estimation**](https://ieeexplore.ieee.org/abstract/document/9931758)| IEEE TIM 2022 | -|
|[**Self-supervised Representation Learning Framework for Remote Physiological Measurement Using Spatiotemporal Augmentation Loss**](https://arxiv.org/abs/2107.07695)(**SLF-RPM**)| AAAI  2022 | [github](https://github.com/Dylan-H-Wang/SLF-RPM)|
|[**The Way to my Heart is through Contrastive Learning: Remote Photoplethysmography from Unlabelled Video**](https://arxiv.org/abs/2111.09748)| ICCV  2021 | [github](https://github.com/ToyotaResearchInstitute/RemotePPG)|


### Multimodal

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**CardiacMamba: A Multimodal RGB-RF Fusion Framework with State Space Models for Remote Physiological Measurement**](http://arxiv.org/abs/2502.13624) (**CardiacMamba**)| arXiv 2025 | [github](https://github.com/WuZheng42/CardiacMamba)|
|[**Spatial Alignment and Temporal Matching Adapter for Video-Radar Remote Physiological Measurement**](https://openaccess.thecvf.com/content/ICCV2025/papers/Liang_Spatial_Alignment_and_Temporal_Matching_Adapter_for_Video-Radar_Remote_Physiological_ICCV_2025_paper.pdf) (**SATM**)| ICCV 2025 | -|
|[**FusionPhys: A Flexible Framework for Fusing Complementary Sensing Modalities in Remote Physiological Measurement**](https://openaccess.thecvf.com/content/ICCV2025/papers/Ying_FusionPhys_A_Flexible_Framework_for_Fusing_Complementary_Sensing_Modalities_in_ICCV_2025_paper.pdf) (**FusionPhys**)| ICCV 2025 | [github](https://github.com/ChH-Ying/FusonPhys)|
|[**Fusion-Vital: Video-RF Fusion Transformer for Advanced Remote Physiological Measurement**](https://ojs.aaai.org/index.php/AAAI/article/view/27898) (**Fusion-Vital**)| AAAI 2024 | -|
|[**Blending Camera and 77 GHz Radar Sensing for Equitable, Robust Plethysmography**](https://dl.acm.org/doi/10.1145/3528223.3530161) | ACM TOG 2022 | -|


### Other Methods

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Continual Learning for Remote Physiological Measurement: Minimize Forgetting and Simplify Inference**](https://arxiv.org/abs/2407.13974) | ECCV 2024| [github](https://github.com/mayyoy/rppgdil) |
|[**Bi-TTA: Bidirectional Test-Time Adapter for Remote Physiological Measurement**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01774.pdf)(**Bi-TTA**) | ECCV 2024| - |
|[**Resolve Domain Conflicts for Generalizable Remote Physiological Measurement**](https://dl.acm.org/doi/10.1145/3581783.3612265) (**DOHA-rPPG**)| ACM MM 2023| [github](https://github.com/swy666/rppg-doha) |


### Benchmark

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**rPPG-Toolbox: Deep Remote PPG Toolbox**](https://arxiv.org/abs/2210.00716) (**rPPG-Toolbox**)| NeurIPS 2023 | [github](https://github.com/ubicomplab/rPPG-Toolbox)|
|[**Remote Bio-Sensing: Open Source Benchmark Framework for Fair Evaluation of rPPG**](https://arxiv.org/abs/2307.12644) | arXiv 2023 | [github](https://github.com/remotebiosensing/rppg)|
|[**pyVHR: a Python framework for remote photoplethysmography**](https://pubmed.ncbi.nlm.nih.gov/35494872/)(**pyVHR**) | Computer Science 2022 | [github](https://github.com/phuselab/pyVHR)|
|[**Evaluation of biases in remote photoplethysmography methods**](https://www.nature.com/articles/s41746-021-00462-z)(matlab) | npj Digital Medicine 2021 | [github](https://github.com/partofthestars/PPGI-Toolbox)|
|[**iPhys: An Open Non-Contact Imaging-Based Physiological Measurement Toolbox**](https://arxiv.org/pdf/1901.04366)(matlab) | arXiv, 2019 | [github](https://github.com/danmcduff/iphys-toolbox)|


### Dataset

|  Title  |   Publication  |  Url   |
|:--------|:--------:|:--------:|
|[**iBVP Dataset: RGB-Thermal rPPG Dataset with High Resolution Signal Quality Labels**](https://doi.org/10.3390/electronics13071334)(**iBVP**) | Electronics 2024 | [download](https://github.com/PhysiologicAILab/iBVP-Dataset)|
|[**ReactioNet: Learning High-order Facial Behavior from Universal Stimulus-Reaction by Dyadic Relation Reasoning**](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_ReactioNet_Learning_High-Order_Facial_Behavior_from_Universal_Stimulus-Reaction_by_Dyadic_ICCV_2023_paper.pdf)(**BP4D+**) | ICCV 2023 | [download](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)|
[**MMPD: Multi-Domain Mobile Video Physiology Dataset**](https://arxiv.org/pdf/2302.03840)(**MMPD**) | EMBC 2023 | [download](https://github.com/McJackTang/MMPD_rPPG_dataset?tab=readme-ov-file)|
|[**SCAMPS: Synthetics for Camera Measurement of Physiological Signals**](https://proceedings.neurips.cc/paper_files/paper/2022/file/1838feeb71c4b4ea524d0df2f7074245-Paper-Datasets_and_Benchmarks.pdf)(**SCAMPS**) | NeurIPS 2022 | [download](https://github.com/danmcduff/scampsdataset)|
|[**Synthetic Generation of Face Videos with Plethysmograph Physiology**](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Synthetic_Generation_of_Face_Videos_With_Plethysmograph_Physiology_CVPR_2022_paper.pdf) (**UCLA-rPPG**) | CVPR 2022 | [download](http://visual.ee.ucla.edu/rppg_avatars.htm/)|
|[**Deception Detection and Remote Physiological Monitoring: A Dataset and Baseline Experimental Results**](https://arxiv.org/pdf/2106.06583) (**DDPM**) | IEEE TBIOM 2021 | [download](https://cvrl.nd.edu/projects/data/#deception-detection-and-%20physiological-monitoringddpm)|
|[**UBFC-Phys: A Multimodal Database For Psychophysiological Studies Of Social Stress**](https://ieeexplore.ieee.org/document/9346017) (**UBFC-Phys**) | IEEE TAFFC 2021 | [download](https://sites.google.com/view/ybenezeth/ubfc-phys)|
|[**VIPL-HR: A Multi-modal Database for Pulse Estimation from Less-constrained Face Video**](https://arxiv.org/pdf/1810.04927v2) (**VIPL-HR**) | ACCV 2018 | [download](http://vipl.ict.ac.cn/database.php)|
|[**A Reproducible Study on Remote Heart Rate Measurement**](https://arxiv.org/pdf/1709.00962) (**COHFACE**) | arXiv 2017 | [download](https://www.idiap.ch/en/scientific-research/data/cohface)|
|[**Unsupervised skin tissue segmentation for remote photoplethysmography**](https://www.sciencedirect.com/science/article/pii/S0167865517303860) (**UBFC-rPPG**) | Pattern Recognition Letters 2017 | [download](https://sites.google.com/view/ybenezeth/ubfcrppg)|
|[**Multimodal Spontaneous Emotion Corpus for Human Behavior Analysis**](https://openaccess.thecvf.com/content_cvpr_2016/papers/Zhang_Multimodal_Spontaneous_Emotion_CVPR_2016_paper.pdf) (**MMSE-HR**) | CVPR 2016 | [download](https://binghamton.technologypublisher.com/tech/MMSE-HR_dataset_(Multimodal_Spontaneous_Expression-Heart_Rate_dataset))|
|[**Non-contact Video-based Pulse Rate Measurement on a Mobile Service Robot**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6926392) (**PURE**) |  2014 | [download](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-informatik-und-automatisierung/profil/institute-und-fachgebiete/institut-fuer-technische-informatik-und-ingenieurinformatik/fachgebiet-neuroinformatik-und-kognitive-robotik/data-sets-code/pulse-rate-detection-dataset-pure)|
|[**DEAP: A Database for Emotion Analysis Using Physiological Signals**](https://ieeexplore.ieee.org/document/5871728) (**DEAP**) | IEEE TAFFC 2011 | [download](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/)|




## Acknowledgments

- https://github.com/zx-pan/Awesome-rPPG
