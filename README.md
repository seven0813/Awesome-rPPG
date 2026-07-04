# Awesome-rPPG

> Last updated: 2026-07-04

This repository is a collection of rPPG methods. I will update it gradually, if you have any suggestions or questions, please feel free to contact me. If you know any other methods, please create a issue or pull request. If you find this repository helpful, please give me a star.

- [Awesome Papers](#awesome-papers)
  - [Survey](#survey)
  - [Traditional Methods](#traditional-methods)
  - [Supervised Learning](#supervised-learning)
  - [Self-Supervised Learning](#self-supervised-learning)
  - [DG/DA/TTA](#dgdattta)
  - [Multimodal](#multimodal)
  - [Other](#other)
    - [Miscellaneous](#miscellaneous)
    - [Data Synthesis](#data-synthesis)
    - [Privacy Protection](#privacy-protection)
    - [Benchmark](#benchmark)
    - [Dataset](#dataset)
- [Acknowledgments](#acknowledgments)


## Awesome Papers

### Survey

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Remote photoplethysmography for heart rate measurement: A review**](https://www.sciencedirect.com/science/article/abs/pii/S1746809423010418)| BSPC 2023 | - |
|[**Camera Measurement of Physiological Vital Signs**](https://arxiv.org/pdf/2111.11547)| ACM Computing Surveys 2021 | - |
|[**Video-Based Heart Rate Measurement: Recent Advances and Future Prospects**](https://ieeexplore.ieee.org/document/8552414) | TIM 2019 | - |


### Traditional Methods

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Face2PPG: An Unsupervised Pipeline for Blood Volume Pulse Extraction From Faces**](https://ieeexplore.ieee.org/document/10227326) (**OMIT**)| IEEE JBHI 2023| - |
|[**Local Group Invariance for Heart Rate Estimation from Face Videos in the Wild**](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w27/Pilz_Local_Group_Invariance_CVPR_2018_paper.pdf) (**LGI**)| CVPRW 2018 | - |
|[**Algorithmic Principles of Remote PPG**](https://ieeexplore.ieee.org/document/7565547) (**POS**)| IEEE TBME 2016 | - |
|[**A Novel Algorithm for Remote Photoplethysmography: Spatial Subspace Rotation**](https://ieeexplore.ieee.org/document/7355301) (**2SR**)| IEEE TBME 2015 | - |
|[**Improved motion robustness of remote-PPG by using the blood volume pulse signature**](https://iopscience.iop.org/article/10.1088/0967-3334/35/9/1913) (**PBV**)| Physiological Measurement 2014 | - |
|[**Robust Pulse Rate From Chrominance-Based rPPG**](https://ieeexplore.ieee.org/document/6523142) (**CHROM**)| IEEE TBME 2013 | - |
|[**Measuring pulse rate with a webcam—a non-contact method for evaluating cardiac activity**](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=7ad15b6fecdb9b2ad49be5bf26efafe22c9a8945) (**PCA**)| FedCSIS 2011 | - |
|[**Remote plethysmographic imaging using ambient light**](https://pdfs.semanticscholar.org/7cb4/46d61a72f76e774b696515c55c92c7aa32b6.pdf?_gl=1*1q7hzyz*_ga*NTEzMzk5OTY3LjE2ODYxMDg1MjE.*_ga_H7P4ZT52H5*MTY4NjEwODUyMC4xLjAuMTY4NjEwODUyMS41OS4wLjA)| Optics Express 2008 | |


### Supervised Learning

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Passive heart-rate monitoring during smartphone use in everyday life**](https://www.nature.com/articles/s41586-026-10507-6)| Nature 2026 | -|
|[**PhysNeXt: Next-Generation Dual-Branch Structured Attention Fusion Network for Remote Photoplethysmography Measurement**](http://arxiv.org/abs/2603.19752) (**PhysNeXt**)| CVPR 2026 | -|
|[**PHASE-Net: Physics-Grounded Harmonic Attention System for Efficient Remote Photoplethysmography Measurement**](http://arxiv.org/abs/2509.24850) (**PHASE-Net**)| CVPR 2026 | [github](https://github.com/Alex036225/PhaseNet)|
|[**FreqPhys: Repurposing Implicit Physiological Frequency Prior for Robust Remote Photoplethysmography**](http://arxiv.org/abs/2604.00534)| ECCV 2026 | -|
|[**PhysVLM: Vision-Language Model for Generalizable Multitask Remote Physiological Measurement**](https://doi.org/10.1109/TIM.2026.3671908) (**PhysVLM**)| IEEE TIM 2026 | -|
|[**RhythmGuassian: Repurposing Generalizable Gaussian Model For Remote Physiological Measurement**](https://openaccess.thecvf.com/content/ICCV2025/papers/Lu_RhythmGuassian_Repurposing_Generalizable_Gaussian_Model_For_Remote_Physiological_Measurement_ICCV_2025_paper.pdf) (**RhythmGuassian**)| ICCV 2025 | [github](https://github.com/LuPaoPao/RhythmGuassian)|
|[**PhysDiff: Physiology-based Dynamicity Disentangled Diffusion Model for Remote Physiological Measurement**](https://ojs.aaai.org/index.php/AAAI/article/view/32704) (**PhysDiff**)| AAAI 2025 Oral | [github](https://github.com/VUT-HFUT/PhysDiff)|
|[**Memory-efficient Low-latency Remote Photoplethysmography through Temporal-Spatial State Space Duality**](http://arxiv.org/abs/2504.01774) (**ME-rPPG**)| arXiv 2025 | -|
|[**Remote Photoplethysmography in Real-World and Extreme Lighting Scenarios**](http://arxiv.org/abs/2503.11465) | CVPR 2025 | -|
|[**Efficient and Robust Multidimensional Attention in Remote Physiological Sensing through Target Signal Constrained Factorization**](http://arxiv.org/abs/2505.07013) (**MMRPhys**)| arXiv 2025 | -|
|[**PhysMamba: Efficient Remote Physiological Measurement with SlowFast Temporal Difference Mamba**](http://arxiv.org/abs/2409.12031) (**PhysMamba**)| CCBR 2024 | [github](https://github.com/Chaoqi31/PhysMamba)|
|[**RhythmMamba: Fast Remote Physiological Measurement with Arbitrary Length Videos**](http://arxiv.org/abs/2404.06483) (**RhythmMamba**)| arXiv 2024 | [github](https://github.com/zizheng-guo/RhythmMamba)|
|[**RhythmFormer: Extracting Patterned rPPG Signals based on Periodic Sparse Attention**](http://arxiv.org/abs/2402.12788) (**RhythmFormer**)| arXiv 2024 | [github](https://github.com/zizheng-guo/RhythmFormer)|
|[**A Plug-and-Play Temporal Normalization Module for Robust Remote Photoplethysmography**](http://arxiv.org/abs/2411.15283) (**TN**)| arXiv 2024 | -|
|[**PhysMLE: Generalizable and Priors-Inclusive Multi-task Remote Physiological Measurement**](http://arxiv.org/abs/2405.06201) (**PhysMLE**)| arXiv 2024 | -|
|[**rPPG-HiBa: Hierarchical Balanced Framework for Remote Physiological Measurement**](https://dl.acm.org/doi/10.1145/3664647.3680986) (**rPPG-HiBa**)| ACM MM 2024 | [github](https://github.com/pywin/HiBa)|
|[**Toward Motion Robustness: A Masked Attention Regularization Framework in Remote Photoplethysmography**](https://openaccess.thecvf.com/content/CVPR2024W/CVPM/papers/Zhao_Toward_Motion_Robustness_A_Masked_Attention_Regularization_Framework_in_Remote_CVPRW_2024_paper.pdf) (**MAR-rPPG**)| CVPRW 2024 | -|
|[**Robust Remote Photoplethysmography Estimation With Environmental Noise Disentanglement**](https://doi.org/10.1109/TIP.2023.3330108) (**ND-DeeprPPG**)| IEEE TIP 2024 | -|
|[**Cluster-Phys: Facial Clues Clustering Towards Efficient Remote Physiological Measurement**](https://dl.acm.org/doi/10.1145/3664647.3680670) (**Cluster-Phys**)| ACM MM 2024 | [github](https://github.com/VUT-HFUT/ClusterPhys)|
|[**FactorizePhys: Matrix Factorization for Multidimensional Attention in Remote Physiological Sensing**](https://openreview.net/pdf?id=qrfp4eeZ47)(**FactorizePhys**) | NeurIPS 2024| [github](https://github.com/PhysiologicAILab/FactorizePhys) |
|[**Dual-bridging with Adversarial Noise Generation for Domain Adaptive rPPG Estimation**](https://openaccess.thecvf.com/content/CVPR2023/papers/Du_Dual-Bridging_With_Adversarial_Noise_Generation_for_Domain_Adaptive_rPPG_Estimation_CVPR_2023_paper.pdf) | CVPR 2023| -|
|[**PhysFormer++: Facial Video-Based Physiological Measurement with SlowFast Temporal Difference Transformer**](https://link.springer.com/article/10.1007/s11263-023-01758-1) (**PhysFormer++**)| IJCV 2023| -|
|[**EfficientPhys: Enabling Simple, Fast and Accurate Camera-Based Cardiac Measurement**](https://openaccess.thecvf.com/content/WACV2023/papers/Liu_EfficientPhys_Enabling_Simple_Fast_and_Accurate_Camera-Based_Cardiac_Measurement_WACV_2023_paper.pdf) (**EfficientPhys**)| WACV 2023| [github](https://github.com/anonymous0paper/EfficientPhys)|
|[**RADIANT: Better rPPG estimation using signal embeddings and Transformer**](https://openaccess.thecvf.com/content/WACV2023/papers/Gupta_RADIANT_Better_rPPG_Estimation_Using_Signal_Embeddings_and_Transformer_WACV_2023_paper.pdf) (**RADIANT**)| WACV 2023| [github](https://github.com/Deep-Intelligence-Lab/RADIANT)|
|[**Augmentation of rPPG Benchmark Datasets: Learning to Remove and Embed rPPG Signals via Double Cycle Consistent Learning from Unpaired Facial Videos**](https://link.springer.com/chapter/10.1007/978-3-031-19787-1_21)(**RErPPGNet**) | ECCV 2022| [github](https://github.com/nthumplab/RErPPGNet) |
|[**PhysFormer: Facial Video-based Physiological Measurement with Temporal Difference Transformer**](https://arxiv.org/pdf/2111.12082) (**PhysFormer**)| CVPR 2022| [github](https://github.com/ZitongYu/PhysFormer)|
|[**ETA-rPPGNet: Effective Time-Domain Attention Network for Remote Heart Rate Measurement**](https://ieeexplore.ieee.org/abstract/document/9353569) (**ETA-rPPGNet**)| IEEE TIM 2021| - |
|[**Deep Super-Resolution Network for rPPG Information Recovery and Noncontact Heart Rate Estimation**](https://ieeexplore.ieee.org/document/9529062) | IEEE TIM 2021| - |
|[**Visual heart rate estimation with convolutional neural network**](https://www.sciencedirect.com/science/article/pii/S2096579620301121) (**NAS-HR**)| VRIH 2021| [github](https://github.com/LuPaoPao/NAS-HR) |
|[**Dual-GAN: Joint BVP and Noise Modeling for Remote Physiological Measurement**](https://openaccess.thecvf.com/content/CVPR2021/papers/Lu_Dual-GAN_Joint_BVP_and_Noise_Modeling_for_Remote_Physiological_Measurement_CVPR_2021_paper.pdf) (**Dual-GAN**)| CVPR 2021| -|
|[**PulseGAN: Learning to Generate Realistic Pulse Waveforms in Remote Photoplethysmography**](https://ieeexplore.ieee.org/document/9320513) (**PulseGAN**)| IEEE JBHI 2021| [github](https://github.com/miki998/PulseGAN)|
|[**Deep-HR: Fast heart rate estimation from face video under realistic conditions**](https://www.sciencedirect.com/science/article/abs/pii/S0957417421009969) (**Deep-HR**)| ESWA 2021| [github](https://github.com/miki998/PulseGAN)|
|[**Multi-Task Temporal Shift Attention Networks for On-Device Contactless Vitals Measurement**](https://arxiv.org/pdf/2006.03790) (**MTTS-CAN**)| NeurIPS 2020| [github](https://github.com/xliucs/MTTS-CAN) |
|[**RhythmNet: End-to-End Heart Rate Estimation From Face via Spatial-Temporal Representation**](http://refhub.elsevier.com/S1746-8094(23)01041-8/sb47) (**RhythmNet**)| IEEE TIP 2020| [github](https://github.com/AnweshCR7/RhythmNet) |
|[**Video-Based Remote Physiological Measurement via Cross-Verified Feature Disentangling**](http://refhub.elsevier.com/S1746-8094(23)01041-8/sb48) (**CVD**)| ECCV 2020 oral| [github](https://github.com/nxsEdson/CVD-Physiological-Measurement) |
|[**Siamese-rPPG network: remote photoplethysmography signal estimation from face videos**](https://dl.acm.org/doi/abs/10.1145/3341105.3373905) (**Siamese-rPPG**)| ACM SAC 2020| - |
|[**AutoHR: A Strong End-to-End Baseline for Remote Heart Rate Measurement With Neural Searching**](https://ieeexplore.ieee.org/document/9133501) (**AutoHR**)| IEEE SPL 2020| - |
|[**HeartTrack: Convolutional neural network for remote video-based heart rate monitoring**](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w19/Perepelkina_HeartTrack_Convolutional_Neural_Network_for_Remote_Video-Based_Heart_Rate_Monitoring_CVPRW_2020_paper.pdf) (**HeartTrack**)| CVPRW 2020| - |
|[**Meta-rPPG: Remote Heart Rate Estimation Using a Transductive Meta-learner**](https://link.springer.com/chapter/10.1007/978-3-030-58583-9_24) (**Meta-rPPG**)| ECCV 2020| [github](https://github.com/eugenelet/Meta-rPPG)|
|[**Long short-term memory deep-filter in remote photoplethysmography**](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w19/Botina-Monsalve_Long_Short-Term_Memory_Deep-Filter_In_Remote_Photoplethysmography_CVPRW_2020_paper.pdf) |CVPRW 2020| -|
|[**Remote Heart Rate Measurement from Highly Compressed Facial Videos: an End-to-end Deep Learning Solution with Video Enhancement**](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Remote_Heart_Rate_Measurement_From_Highly_Compressed_Facial_Videos_An_ICCV_2019_paper.pdf) (**rPPGNet**)| ICCV 2019| [github](https://github.com/ZitongYu/STVEN_rPPGNet) |
|[**Remote Photoplethysmograph Signal Measurement from Facial Videos Using Spatio-Temporal Networks**](https://arxiv.org/abs/1905.02419) (**PhysNet**)| BMCV 2019| [github](https://github.com/ZitongYu/PhysNet) |
|[**3D Convolutional Neural Networks for Remote Pulse Rate Measurement and Mapping from Facial Video**](https://www.mdpi.com/2076-3417/9/20/4364)(**rppg-3dcnn**) | Applied Sci. 2019| [github](https://github.com/frederic-bousefsaf/ippg-3dcnn) |
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
|[**Intervention-Based Self-Supervised Learning: A Causal Probe Paradigm for Remote Photoplethysmography**](http://arxiv.org/abs/2605.00882) (**Interv-rPPG**)| arXiv 2026 | -|
|[**rPPG-VQA: A Video Quality Assessment Framework for Unsupervised rPPG Training**](http://arxiv.org/abs/2604.11156) (**rPPG-VQA**)| CVPR 2026 | [github](https://github.com/Tianyang-Dai/rPPG-VQA)|
|[**Style-rPPG: Exploration and Analysis of Style Transfer in Unsupervised Remote Physiological Measurement**](https://doi.org/10.1016/j.eswa.2024.126310) (**Style-rPPG**)| ESWA 2025 | -|
|[**Semi-rPPG: Semi-Supervised Remote Physiological Measurement with Curriculum Pseudo-Labeling**](http://arxiv.org/abs/2502.03855) (**Semi-rPPG**)| IEEE TIM 2025 | -|
|[**rPPG-NDCL: Unsupervised Remote Physiological Measurement Via Noise-Disentangled Contrastive Learning**](https://doi.org/10.1109/ICIP55913.2025.11084290) (**rPPG-NDCL**)| ICIP 2025 | [github](https://github.com/Tianyang-Dai/rPPG-NDCL)|
|[**Contrast-Phys+: Unsupervised and Weakly-Supervised Video-Based Remote Physiological Measurement via Spatiotemporal Contrast**](https://doi.org/10.1109/TPAMI.2024.3367910) (**Contrast-Phys+**)| IEEE TPAMI 2024 | [github](https://github.com/zhaodongsun/contrast-phys)|
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


### DG/DA/TTA

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**FLOW: Optimal Transport-Driven Feature Warping for Generalized Remote Physiological Measurement**](https://openaccess.thecvf.com/content/CVPR2026/papers/Zhao_FLOW_Optimal_Transport-Driven_Feature_Warping_for_Generalized_Remote_Physiological_Measurement_CVPR_2026_paper.pdf) (**FLOW**)| CVPR 2026 | -|
|[**Rethinking rPPG Supervision: Distribution and Temporal Relation Alignment for Domain Generalization**](https://openaccess.thecvf.com/content/CVPR2026W/SVC/papers/Qian_Rethinking_rPPG_Supervision_Distribution_and_Temporal_Relation_Alignment_for_Domain_CVPRW_2026_paper.pdf) | CVPRW 2026 | -|
|[**Advancing Generalizable Remote Physiological Measurement through the Integration of Explicit and Implicit Prior Knowledge**](http://arxiv.org/abs/2403.06947) (**Greip**)| arXiv 2025 | [github](https://github.com/keke-nice/Greip)|
|[**Generalizable Remote Physiological Measurement via Semantic-Sheltered Alignment and Plausible Style Randomization**](https://doi.org/10.1109/TIM.2024.3497058) (**DG-rPPG**)| IEEE TIM 2025 | [github](https://github.com/WJULYW/DG-rPPG)|
|[**BeatFormer: Efficient Motion-Robust Remote Heart Rate Estimation through Unsupervised Spectral Zoomed Attention Filters**](https://openaccess.thecvf.com/content/ICCV2025W/CVPM/papers/Martinez_BeatFormer_Efficient_motion-robust_remote_heart_rate_estimation_through_unsupervised_spectral_ICCVW_2025_paper.pdf) (**BeatFormer**)| ICCVW 2025 | -|
|[**Bi-TTA: Bidirectional Test-Time Adapter for Remote Physiological Measurement**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01774.pdf)(**Bi-TTA**) | ECCV 2024| - |
|[**Continual Learning for Remote Physiological Measurement: Minimize Forgetting and Simplify Inference**](https://arxiv.org/abs/2407.13974) | ECCV 2024| [github](https://github.com/mayyoy/rppgdil) |
|[**SFDA-rPPG: Source-Free Domain Adaptive Remote Physiological Measurement with Spatio-Temporal Consistency**](http://arxiv.org/abs/2409.12040) (**SFDA-rPPG**)| arXiv 2024 | [github](https://github.com/XieYiping66/SFDA-rPPG)|
|[**Hierarchical Style-Aware Domain Generalization for Remote Physiological Measurement**](https://doi.org/10.1109/JBHI.2023.3346057) (**HSRD**)| IEEE JBHI 2024 | -|
|[**Fully Test-Time rPPG Estimation via Synthetic Signal-Guided Feature Learning**](https://www.ssrn.com/abstract=5063675) | Pattern Recognition 2025 | -|
|[**Resolve Domain Conflicts for Generalizable Remote Physiological Measurement**](https://dl.acm.org/doi/10.1145/3581783.3612265) (**DOHA-rPPG**)| ACM MM 2023| [github](https://github.com/swy666/rppg-doha) |
|[**Domain Generalized RPPG Network: Disentangled Feature Learning with Domain Permutation and Domain Augmentation**](https://link.springer.com/10.1007/978-3-031-26284-5_3) (**DG-rPPGNet**)| ACCV 2022 | -|


### Multimodal

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**PhysLLM: Harnessing Large Language Models for Cross-Modal Remote Physiological Sensing**](http://arxiv.org/abs/2505.03621) (**PhysLLM**)| ICLR 2026 | [github](https://github.com/Alex036225/PhysLLM)|
|[**CardiacMamba: A Multimodal RGB-RF Fusion Framework with State Space Models for Remote Physiological Measurement**](http://arxiv.org/abs/2502.13624) (**CardiacMamba**)| IEEE TIM 2025 | [github](https://github.com/WuZheng42/CardiacMamba)|
|[**Bootstrapping Vision-Language Models for Frequency-Centric Self-Supervised Remote Physiological Measurement**](https://doi.org/10.1007/s11263-025-02388-5) | IJCV 2025 | [github](https://github.com/yuezijie/Bootstrapping-VLM-for-Frequency-centric-Self-supervised-Remote-Physiological-Measurement)|
|[**Spatial Alignment and Temporal Matching Adapter for Video-Radar Remote Physiological Measurement**](https://openaccess.thecvf.com/content/ICCV2025/papers/Liang_Spatial_Alignment_and_Temporal_Matching_Adapter_for_Video-Radar_Remote_Physiological_ICCV_2025_paper.pdf) (**SATM**)| ICCV 2025 | -|
|[**FusionPhys: A Flexible Framework for Fusing Complementary Sensing Modalities in Remote Physiological Measurement**](https://openaccess.thecvf.com/content/ICCV2025/papers/Ying_FusionPhys_A_Flexible_Framework_for_Fusing_Complementary_Sensing_Modalities_in_ICCV_2025_paper.pdf) (**FusionPhys**)| ICCV 2025 | [github](https://github.com/ChH-Ying/FusonPhys)|
|[**Fusion-Vital: Video-RF Fusion Transformer for Advanced Remote Physiological Measurement**](https://ojs.aaai.org/index.php/AAAI/article/view/27898) (**Fusion-Vital**)| AAAI 2024 | -|
|[**Evidential Remote Physiological Measurement via Uncertainty-aware Fusion of Video and RF**](https://dl.acm.org/doi/10.1145/3746027.3754594) | ACM MM 2025 | -|
|[**Blending Camera and 77 GHz Radar Sensing for Equitable, Robust Plethysmography**](https://dl.acm.org/doi/10.1145/3528223.3530161) | ACM TOG 2022 | -|


### Other

#### Miscellaneous

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Orientation-conditioned Facial Texture Mapping for Video-based Facial Remote Photoplethysmography Estimation**](http://arxiv.org/abs/2404.09378) | arXiv 2024 | -|
|[**Evaluation of Video-Based rPPG in Challenging Environments: Artifact Mitigation and Network Resilience**](http://arxiv.org/abs/2405.01230) | arXiv 2024 | -|
|[**Learning Motion-Robust Remote Photoplethysmography through Arbitrary Resolution Videos**](http://arxiv.org/abs/2211.16922) | AAAI 2023 | [github](https://github.com/LJW-GIT/Arbitrary_Resolution_rPPG)|


#### Data Synthesis

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**Syn-rPPG: Improving Unsupervised Remote Photoplethysmography Extraction with Synthesized Videos using Generative Models**](https://doi.org/10.1016/j.engappai.2025.110504) (**Syn-rPPG**)| EAAI 2025 | -|
|[**Motion Matters: Neural Motion Transfer for Better Camera Physiological Measurement**](http://arxiv.org/abs/2303.12059) | WACV 2024 Oral | [github](https://github.com/yahskapar/MA-rPPG-Video-Toolbox)|
|[**PhysFlow: Skin Tone Transfer for Remote Heart Rate Estimation through Conditional Normalizing Flows**](https://bmva-archive.org.uk/bmvc/2024/papers/Paper_136/paper.pdf) (**PhysFlow**)| BMCV 2024 | -|
|[**Video-based Heart Rate Estimation from Challenging Scenarios Using Synthetic Video Generation**](https://doi.org/10.1016/j.bspc.2024.106598) | BSPC 2024 | -|
|[**Training Robust Deep Physiological Measurement Models with Synthetic Video-based Data**](http://arxiv.org/abs/2311.05371) | arXiv 2023 | -|
|[**Style Transfer with Bio-realistic Appearance Manipulation for Skin-tone Inclusive rPPG**](https://doi.org/10.1109/ICCP54855.2022.9887649) | ICCP 2022 | -|
|[**Overcoming Difficulty in Obtaining Dark-skinned Subjects for Remote-PPG by Synthetic Augmentation**](http://arxiv.org/abs/2106.06007) | arXiv 2021 | -|
|[**Synthetic Data for Multi-Parameter Camera-Based Physiological Sensing**](http://arxiv.org/abs/2110.04902) | arXiv 2021 | -|
|[**Multi-task Learning for Simultaneous Video Generation and Remote Photoplethysmography Estimation**](https://openaccess.thecvf.com/content/ACCV2020/papers/Tsou_Multi-Task_Learning_for_Simultaneous_Video_Generation_and_Remote_Photoplethysmography_Estimation_ACCV_2020_paper.pdf) | ACCV 2020 | -|
|[**Advancing Non-Contact Vital Sign Measurement using Synthetic Avatars**](http://arxiv.org/abs/2010.12949) | arXiv 2020 | -|


#### Privacy Protection

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**PulseEdit: Editing Physiological Signals in Facial Videos for Privacy Protection**](https://doi.org/10.1109/TIFS.2022.3142993) (**PulseEdit**)| IEEE TIFS 2022 | - |
|[**Phys-EdiGAN: A privacy-preserving method for editing physiological signals in facial videos**](https://doi.org/10.1016/j.patcog.2025.111966) (**Phys-EdiGAN**)| Pattern Recognition 2026 | - |
|[**Privacy-Phys: Facial Video-Based Physiological Modification for Privacy Protection**](https://doi.org/10.1109/LSP.2022.3185964) (**Privacy-Phys**)| IEEE SPL 2022 | - |
|[**De-identification of facial videos while preserving remote physiological utility**](https://papers.bmvc2023.org/0230.pdf) | BMVC 2023 | [github](https://github.com/marukosan93/De-id_rPPG) |


#### Benchmark

|  Title  |   Publication  |  Code   |
|:--------|:--------:|:--------:|
|[**rPPG-Toolbox: Deep Remote PPG Toolbox**](https://arxiv.org/abs/2210.00716) (**rPPG-Toolbox**)| NeurIPS 2023 | [github](https://github.com/ubicomplab/rPPG-Toolbox)|
|[**Remote Bio-Sensing: Open Source Benchmark Framework for Fair Evaluation of rPPG**](https://arxiv.org/abs/2307.12644) | arXiv 2023 | [github](https://github.com/remotebiosensing/rppg)|
|[**pyVHR: a Python framework for remote photoplethysmography**](https://pubmed.ncbi.nlm.nih.gov/35494872/)(**pyVHR**) | Computer Science 2022 | [github](https://github.com/phuselab/pyVHR)|
|[**Evaluation of biases in remote photoplethysmography methods**](https://www.nature.com/articles/s41746-021-00462-z)(matlab) | npj Digital Medicine 2021 | [github](https://github.com/partofthestars/PPGI-Toolbox)|
|[**iPhys: An Open Non-Contact Imaging-Based Physiological Measurement Toolbox**](https://arxiv.org/pdf/1901.04366)(matlab) | arXiv, 2019 | [github](https://github.com/danmcduff/iphys-toolbox)|


#### Dataset

|  Title  |   Publication  |  Url   |
|:--------|:--------:|:--------:|
|[**PhysDrive: A Multimodal Remote Physiological Measurement Dataset for In-vehicle Driver Monitoring**](http://arxiv.org/abs/2507.19172) (**PhysDrive**) | NeurIPS 2025 | [download](https://github.com/WJULYW/PhysDrive-Dataset)|
|[**Exploring Remote Physiological Signal Measurement under Dynamic Lighting Conditions at Night: Dataset, Experiment, and Analysis**](http://arxiv.org/abs/2507.04306) (**DLCN**) | arXiv 2025 | [download](https://github.com/dalaoplan/Happp-rPPG-Toolkit)|
|[**iBVP Dataset: RGB-Thermal rPPG Dataset with High Resolution Signal Quality Labels**](https://doi.org/10.3390/electronics13071334)(**iBVP**) | Electronics 2024 | [download](https://github.com/PhysiologicAILab/iBVP-Dataset)|
|[**ReactioNet: Learning High-order Facial Behavior from Universal Stimulus-Reaction by Dyadic Relation Reasoning**](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_ReactioNet_Learning_High-Order_Facial_Behavior_from_Universal_Stimulus-Reaction_by_Dyadic_ICCV_2023_paper.pdf)(**BP4D+**) | ICCV 2023 | [download](https://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)|
|[**MMPD: Multi-Domain Mobile Video Physiology Dataset**](https://arxiv.org/pdf/2302.03840)(**MMPD**) | EMBC 2023 | [download](https://github.com/McJackTang/MMPD_rPPG_dataset?tab=readme-ov-file)|
|[**SCAMPS: Synthetics for Camera Measurement of Physiological Signals**](https://proceedings.neurips.cc/paper_files/paper/2022/file/1838feeb71c4b4ea524d0df2f7074245-Paper-Datasets_and_Benchmarks.pdf)(**SCAMPS**) | NeurIPS 2022 | [download](https://github.com/danmcduff/scampsdataset)|
|[**Synthetic Generation of Face Videos with Plethysmograph Physiology**](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Synthetic_Generation_of_Face_Videos_With_Plethysmograph_Physiology_CVPR_2022_paper.pdf) (**UCLA-rPPG**) | CVPR 2022 | [download](http://visual.ee.ucla.edu/rppg_avatars.htm/)|
|[**Deception Detection and Remote Physiological Monitoring: A Dataset and Baseline Experimental Results**](https://arxiv.org/pdf/2106.06583) (**DDPM**) | IEEE TBIOM 2021 | [download](https://cvrl.nd.edu/projects/data/#deception-detection-and-%20physiological-monitoringddpm)|
|[**UBFC-Phys: A Multimodal Database For Psychophysiological Studies Of Social Stress**](https://ieeexplore.ieee.org/document/9346017) (**UBFC-Phys**) | IEEE TAFFC 2021 | [download](https://sites.google.com/view/ybenezeth/ubfc-phys)|
|[**VIPL-HR: A Multi-modal Database for Pulse Estimation from Less-constrained Face Video**](https://arxiv.org/pdf/1810.04927v2) (**VIPL-HR**) | ACCV 2018 | [download](http://vipl.ict.ac.cn/database.php)|
|[**A Reproducible Study on Remote Heart Rate Measurement**](https://arxiv.org/pdf/1709.00962) (**COHFACE**) | arXiv 2017 | [download](https://www.idiap.ch/en/scientific-research/data/cohface)|
|[**Unsupervised skin tissue segmentation for remote photoplethysmography**](https://www.sciencedirect.com/science/article/pii/S0167865517303860) (**UBFC-rPPG**) | Pattern Recognit. Lett. 2017 | [download](https://sites.google.com/view/ybenezeth/ubfcrppg)|
|[**Multimodal Spontaneous Emotion Corpus for Human Behavior Analysis**](https://openaccess.thecvf.com/content_cvpr_2016/papers/Zhang_Multimodal_Spontaneous_Emotion_CVPR_2016_paper.pdf) (**MMSE-HR**) | CVPR 2016 | [download](https://binghamton.technologypublisher.com/tech/MMSE-HR_dataset_(Multimodal_Spontaneous_Expression-Heart_Rate_dataset))|
|[**Non-contact Video-based Pulse Rate Measurement on a Mobile Service Robot**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6926392) (**PURE**) |  2014 | [download](https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-informatik-und-automatisierung/profil/institute-und-fachgebiete/institut-fuer-technische-informatik-und-ingenieurinformatik/fachgebiet-neuroinformatik-und-kognitive-robotik/data-sets-code/pulse-rate-detection-dataset-pure)|
|[**DEAP: A Database for Emotion Analysis Using Physiological Signals**](https://ieeexplore.ieee.org/document/5871728) (**DEAP**) | IEEE TAFFC 2011 | [download](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/)|



## Acknowledgments

- https://github.com/zx-pan/Awesome-rPPG
