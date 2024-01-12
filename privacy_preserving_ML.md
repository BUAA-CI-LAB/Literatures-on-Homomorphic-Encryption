# **Papers for Privacy Preserving Machine Learning(PPML) and Privacy Preserving Neural Networks(PPNN)**
Papers for PPML and PPNN: MPC-based, HE-based, DP-based(Differential Privacy), Functional Encryption(FE), Hybrid Privacy Preserving method 

- [Algorithmic Acceleration for PPML/PPNN](#algorithmic-acceleration-for-ppmlppnn)
- [System Designs for PPML/PPNN](#system-designs-for-ppmlppnn)
- [Hardware Acceleration for PPML/PPNN](#hardware-acceleration-for-ppmlppnn)
- [Network Architecture Optimization for PPML/PPNN](#network-architecture-optimizaiton-for-ppmlppnn)
- [Device-Edge-Cloud Collaboration Optimization for PPML/PPNN](#device-edge-cloud-collaboration-for-ppmlppnn)
- [Surveys and Performance Analysis on PPML/PPNN](#surveys-and-performance-analysis-on-ppmlppnn)

## **Algorithmic Acceleration** for PPML/PPNN

* [**KBS 2024**] [**MPC**] FPCNN: A fast privacy-preserving outsourced convolutional neural network with low-bandwidth
  >*Li J, Yan Y, Zhang K, et al.* [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705123009310)

* [**ICML 2023**] [**HE, Transfer Learning**] HETAL: Efficient Privacy-preserving Transfer Learning with Homomorphic Encryption
  >*Lee S, Lee G, Kim J W, et al.* [[Paper]](https://proceedings.mlr.press/v202/lee23m/lee23m.pdf)

* [**S&P 2023**] [**MPC, Training, DP**] Private, Efficient, and Accurate: Protecting Models Trained by Multi-party Learning with Differential Privacy
  >*Ruan W, Xu M, Fang W, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10179422)

* [**ICML 2023**] [**DP, Training**] Label Differential Privacy and Private Training Data Release
  >*Busa-Fekete R I, Medina A M, Syed U, et al.* [[Paper]](https://proceedings.mlr.press/v202/busa-fekete23a/busa-fekete23a.pdf)

* [**Cryptology eprint Archive 2023**] [**MPC, Training**] Secure Floating-Point Training
  >*Rathee D, Bhattacharya A, Gupta D, et al.* [[Paper]](https://www.usenix.org/system/files/sec23fall-prepub-212-rathee.pdf)

* [**ASIACRYPT 2023**] [**CKKS, BFV, Rotation**] Rotation Key Reduction for Client-Server Systems of Deep Neural Network on Fully Homomorphic Encryption
  >*Lee J W, Lee E, Kim Y S, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-981-99-8736-8_2)

* [**TDSC 2023**] [**SIMD, Garbled Circuit**] SIMC 2.0: Improved Secure ML Inference Against Malicious Clients
  >*Guowen Xu,Xing shuo Han et al.* [[Paper]](https://arxiv.org/pdf/2207.04637.pdf)

* [**TIFS 2023**] [**MPC, BNN**] FLEXBNN: Fast Private Binary Neural Network Inference With Flexible Bit-Width
  >*Dong Y, Chen X, Song X, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10093909)

* [**IWSPA 2023**] [**FE**] FENet: Privacy-preserving Neural Network Training with Functional Encryption
  >*Panzade P, Takabi D.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3579987.3586566)

* [**ArXiv 2023**] [**HE-based 2PC, depth-wise Packing Optimization**] Falcon: Accelerating Homomorphically Encrypted Convolutions for Efficient Private Mobile Network Inference
  >*Xu T, Li M, Wang R, et al.* [[Paper]](https://arxiv.org/pdf/2308.13189.pdf)

* [**Euro S&P 2023**] [**MPC, Transformer**] Privformer: Privacy-preserving Transformer with MPC
  >*Akimoto Y, Fukuchi K, Akimoto Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10190506)

* [**ACL 2022**] [**Transformer, CKKS**] THE-X: Privacy-Preserving Transformer Inference with Homomorphic Encryption
  >*Tianyu Chen et al.* [[Paper]](https://aclanthology.org/2022.findings-acl.277.pdf)

* [**NeurIPS 2022**] [**AHE**] Iron: Private Inference on Transformers
  >*Meng Hao et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/64e2449d74f84e5b1a5c96ba7b3d308e-Paper-Conference.pdf)


* [**ACNS 2022**] [**HE, Training**] A methodology for training homomorphic encryption friendly neural networks
  >*Baruch M, Drucker N, Greenberg L, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16815-4_29)

* [**ICLR 2021**] [**FHE, BNN**] GATENET: BRIDGING THE GAP BETWEEN BINARIZED NEURAL NETWORK AND FHE EVALUATION
  >*Fu C, Huang H, Chen X, et al.* [[Paper]](https://aisecure-workshop.github.io/aml-iclr2021/papers/9.pdf)

* [**WIHMS 2021**] [**MPC, Replicated Secret Share, BNN**] Banners: Binarized Neural Networks with Replicated Secret Sharing
  >*Ibarrondo A, Chabanne H, Önen M.* [[Paper]](https://eprint.iacr.org/2021/045.pdf)

* [**SIGSAC 2019**] [**MPC**] QUOTIENT: Two-Party Secure Neural Network Training and Prediction
  >*Agrawal N, Shahin Shamsabadi A, Kusner M J, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3319535.3339819)

* [**USENIX 2019**] [**MPC, OT, GC, BNN**] XONN: XNOR-based Oblivious Deep Neural Network Inference
  >*Riazi M S, Samragh M, Chen H, et al.* [[Paper]](https://www.usenix.org/conference/usenixsecurity19/presentation/riazi)

## **System Designs** for PPML/PPNN

* [**ArXiv 2023**] [**MPC, LLM**] LLMs Can Understand Encrypted Prompt: Towards Privacy-Computing Friendly Transformers
  >*Liu X, Liu Z.* [[Paper]](https://arxiv.org/pdf/2305.18396.pdf)

* [**ArXiv 2023**] [**MPC, Transformer**] East: Efficient and Accurate Secure Transformer Framework for Inference
  >*Ding Y, Guo H, Guan Y, et al.* [[Paper]](https://arxiv.org/pdf/2308.09923.pdf)

* [**Cryptology eprint 2023**] [**MPC, Transformer**] BumbleBee: Secure Two-party Inference Framework for Large Transformers
  >*Lu W, Huang Z, Gu Z, et al.* [[Paper]](https://eprint.iacr.org/2023/1678.pdf)

* [**ArXiv 2023**] [**TFHE, lookup-table**] TT-TFHE: a Torus Fully Homomorphic Encryption-Friendly Neural Network Architecture
  >*Adrien Benamira et al.* [[Paper]](https://arxiv.org/pdf/2302.01584.pdf)

* [**ArXiv 2023**] [**HE, GCN**] LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference
  >*Peng H, Ran R, Luo Y, et al.* [[Paper]](https://arxiv.org/pdf/2309.14331.pdf)

* [**ArXiv 2023**] [**MPC, Polynomial Approximation, LLM**] PUMA: SECURE INFERENCE OF LLAMA-7B IN FIVE MINUTES
  >*Dong Y, Lu W, Zheng Y, et al.* [[Paper]](https://arxiv.org/pdf/2307.12533.pdf)

* [**DAC 2023**] [**MPC, Polynomial Approximation, NAS**] PASNet: Polynomial Architecture Search Framework for Two-party Computation-based Secure Neural Network Deployment
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247663)

* [**NeurIPS 2022**] [**GCN, CKKS**] CryptoGCN: Fast and Scalable Homomorphically Encrypted Graph Convolutional Network Inference
  >*Ran Ran, Nuo Xu et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/f5332c8273d02729730a9c24dec2135e-Paper-Conference.pdf)

* [**TDSC 2021**] [**MPC**] A Lightweight Privacy-Preserving CNN Feature
Extraction Framework for Mobile Sensing
  >*Huang K, Liu X, Fu S, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8700229)

## **Hardware Acceleration** for PPML/PPNN

* [**ISQED 2023**] [**CKKS,KS,NTT,RNS**] PriML: An Electro-Optical Accelerator for Private Machine Learning on Encrypted Data
  >*Mengxin Zheng,FanChSen et al.* [[Paper]](https://ieeexplore.ieee.org/document/10129302)

* [**HPCA 2023**] [**CKKS**] FxHENN: FPGA-based acceleration framework for homomorphic encrypted CNN inference
  >*Yilan Zhu Lei Ju et al.* [[Paper]](https://ieeexplore.ieee.org/document/10071133/)

* [**USENIX 2021**] [**MPC, GC, GPU**] GForce: GPU-Friendly Oblivious and Rapid Neural Network Inference
  >*Ng L K L, Chow S S M.* [[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/ng)

## **Network Architecture Optimizaiton** for PPML/PPNN

* [**NeurIPS 2023**] [**MPC, Winograd Convolution**] CoPriv: Network/Protocol Co-Optimization for Communication-Efficient Private Inference
  >*Zeng W, Li M, Yang H, et al.* [[Paper]](https://arxiv.org/pdf/2311.01737.pdf)

* [**ArXiv 2023**] [**MPC, ViT, NAS**] PRIVIT: VISION TRANSFORMERS FOR FAST PRIVATE INFERENCE
  >*Dhyani N, Mo J, Cho M, et al.* [[Paper]](https://arxiv.org/pdf/2310.04604.pdf)

* [**ICCV 2023**] [**MPC, NAS, Transformer**] SAL-ViT: Towards Latency Efficient Private Inference on ViT using Selective Attention Search with a Learnable Softmax Approximation
  >*Zhang Y, Chen D, Kundu S, et al.* [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_SAL-ViT_Towards_Latency_Efficient_Private_Inference_on_ViT_using_Selective_ICCV_2023_paper.pdf)

* [**ICCV 2023**] [**MPC, ViT, NAS**] MPCViT: Searching for Accurate and Efficient MPC-Friendly Vision Transformer with Heterogeneous Attention
  >*Zeng W, Li M, Xiong W, et al.* [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zeng_MPCViT_Searching_for_Accurate_and_Efficient_MPC-Friendly_Vision_Transformer_with_ICCV_2023_paper.pdf)

* [**USENIX 2023**] [**FHE,RNS-CKKS, Polynomial Approximation**] AutoFHE: Automated Adaption of CNNs for Efficient Evaluation over FHE
  >*Ao W, Boddeti V N.* [[Paper]](https://www.usenix.org/system/files/sec23winter-prepub-559-ao.pdf)

* [**ArXiv 2023**] [**HE, Pruning**] Artemis: HE-Aware Training for Efficient Privacy-Preserving Machine Learning
  >*Jeon Y, Erez M, Orshansky M.* [[Paper]](https://arxiv.org/pdf/2310.01664.pdf)

* [**CCS 2022**] [**HE, Pruning**] Hunter: HE-Friendly Structured Pruning for Efficient Privacy-Preserving Deep Learning
  >*Cai Y, Zhang Q, Ning R, et al.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3488932.3517401)

* [**DAC 2023**] [**MPC, Polynomial Approximation, NAS**] PASNet: Polynomial Architecture Search Framework for Two-party Computation-based Secure Neural Network Deployment
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247663)

* [**AAAI 2022**] [**DP, NAS**] DPNAS: Neural Architecture Search for Deep Learning with Differential Privacy
  >*Cheng A,Wang J, Zhang X S, et al.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20586)

* [**SMC 2022**] [**HE, NAS**] CNAS: Constrained Neural Architecture Search
  >*Gambella M, Falcetta A, Roveri M.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9945080)

* [**USENIX 2021**] [**GPU-aware, MPC, Garbled Circuit**] GForce: GPU-Friendly Oblivious and Rapid Neural Network Inference
  >*Ng L K L, Chow S S M.* [[Paper]](https://www.usenix.org/system/files/sec21-ng.pdf)

* [**ICML 2021**] [**HE, NAS**] HEMET: A Homomorphic-Encryption-Friendly Privacy-Preserving Mobile Neural Network Architecture
  >*Lou Q, Jiang L.* [[Paper]](https://proceedings.mlr.press/v139/lou21a/lou21a.pdf)

* [**ECAI 2020**] [**HE, Garbled Circuit, NAS**] NASS: Optimizing Secure Inference via Neural
Architecture Search
  >*Bian S, Jiang W, Lu Q, et al.* [[Paper]](https://par.nsf.gov/servlets/purl/10244146)

## **Device-Edge-Cloud Collaboration** for PPML/PPNN

* [**JSAC 2022**] [**Shamir Secret Share(MPC), Matrix-vector multiplication**] Privacy-Preserving Coded Mobile Edge Computing for Low-Latency Distributed Inference
  >*Schlegel R, Kumar S, Rosnes E, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9678363)

* [**DAC 2023**] [**MPC, Polynomial Approximation, NAS**] PASNet: Polynomial Architecture Search Framework for Two-party Computation-based Secure Neural Network Deployment
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247663)

* [**TSNE 2022**] [**MPC**] PCNNCEC: Efficient and Privacy-Preserving Convolutional Neural Network Inference Based on Cloud-Edge-Client Collaboration
  >*Wang J, He D, Castiglione A, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9782521)



## **Surveys and Performance Analysis** on PPML/PPNN

* [**S&P 2023**] [**Survey**] SoK: Cryptographic Neural-Network Computation
  >*Lucien K. L. Ng，Sherman S. M. Chow et al. * [[Paper]](https://ieeexplore.ieee.org/document/10179483)

* [**ArXiv 2023**] [**Survey**] Data Privacy with Homomorphic Encryption in Neural Networks Training and Inference
  >*Ivone Amorim et al.* [[Paper]](https://arxiv.org/pdf/2305.02225.pdf)

* [**PPNA 2023**] [**Survey**] Privacy-preserving neural networks with Homomorphic encryption:
Challenges and opportunities
  >*Bernardo Pulido-Gaytan et al.* [[Paper]](https://link.springer.com/article/10.1007/s12083-021-01076-8)

* [**ISPASS 2022**] [**Survey**] Characterization of mpc-based private inference for transformer-based models
  >*Wang Y, Suh G E, Xiong W, et al.* [[Paper]](https://computing.ece.vt.edu/~wenjiex/publications/2022_ispass_mpc.pdf)

[Back to home](./README.md)