# **Papers for Privacy Preserving Machine Learning(PPML) and Privacy Preserving Neural Networks(PPNN)**
Papers for PPML and PPNN: MPC-based, HE-based, DP-based(Differential Privacy), Functional Encryption(FE), Hybrid Privacy Preserving method 

- [Algorithmic Acceleration for PPML/PPNN](#algorithmic-acceleration-for-ppmlppnn)
- [System Designs for PPML/PPNN](#system-designs-for-ppmlppnn)
- [Hardware Acceleration for PPML/PPNN](#hardware-acceleration-for-ppmlppnn)
- [Network Architecture Optimization for PPML/PPNN](#network-architecture-optimizaiton-for-ppmlppnn)
- [Device-Edge-Cloud Collaboration Optimization for PPML/PPNN](#device-edge-cloud-collaboration-for-ppmlppnn)
- [Surveys and Performance Analysis on PPML/PPNN](#surveys-and-performance-analysis-on-ppmlppnn)

---
## **Algorithmic Acceleration** for PPML/PPNN
* [**TIT 2025**] [****] Private Inference in Quantized Models
  >*Deng Z, Ramkumar V, Bitar R, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10896693)

* [**CCS 2024**] [**CKKS, CNN, Boostrapping**] NeuJeans: Private Neural Network Inference with Joint Optimization of
Convolution and Bootstrapping
  >*Ju J H, Park J, Kim J, et al.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3658644.3690375)

* [**TDSC 2024**] [**FHE, RNS-CKKS, CNN**] Batch Inference on Deep Convolutional Neural
Networks With Fully Homomorphic Encryption
Using Channel-By-Channel Convolutions
  >*Cheon J H, Kang M, Kim T, et al.* [[Paper]](https://dl.acm.org/doi/10.1109/TDSC.2024.3448406)

* [**ArXiv 2024**] [**CKKS, GC, Rotation-free**] Efficient Homomorphically Encrypted
Convolutional Neural Network Without Rotation
  >*Akherati S, Zhang X.* [[Paper]](https://arxiv.org/pdf/2409.05205)


* [**ACNS 2024**] [**PPML, FHE**] Memory Efficient Privacy-Preserving Machine Learning Based on Homomorphic Encryption
  >*Podschwadt R, Ghazvinian P, GhasemiGol M, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-54773-7_13)

* [**Journal of Cryptology 2024**] [**CKKS**] BLEACH: cleaning errors in discrete computations over CKKS
  >*Drucker N, Moshkowich G, Pelleg T, et al.* [[Paper]](https://eprint.iacr.org/2022/1298.pdf)

* [**MLSys 2024**] [**HE, Polynomial Approximation**] Accurate Low-Degree Polynomial Approximation of Non-polynomial Operators for Fast Private Inference in Homomorphic Encryption
  >*Dang J, Tong J, Golder A, et al.* [[Paper]](https://proceedings.mlsys.org/paper_files/paper/2024/file/621d0fd41c720ab252e178b77c200d90-Paper-Conference.pdf)

* [**Cryptology ePrint Archive 2024**] [**Bootstrapping, BFV, BGV**] Relaxed Functional Bootstrapping: A New Perspective on BGV/BFV Bootstrapping
  >*Liu Z, Wang Y.* [[Paper]](https://eprint.iacr.org/2024/172.pdf)

* [**ArXiv 2024**] [**HE**] PrivCirNet: Efficient Private Inference via Block Circulant Transformation
  >*Xu T, Wu L, Wang R, et al.* [[Paper]](https://arxiv.org/pdf/2405.14569)

* [**ArXiv 2024**] [**Polynomial Approximation**] Neural Networks with (Low-Precision) Polynomial Approximations:
New Insights and Techniques for Accuracy Improvement
  >*Zhang C, Au M H, Yiu S M.* [[Paper]](https://arxiv.org/pdf/2402.11224.pdf)

* [**KBS 2024**] [**MPC**] FPCNN: A fast privacy-preserving outsourced convolutional neural network with low-bandwidth
  >*Li J, Yan Y, Zhang K, et al.* [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705123009310)

* [**TDSC 2024**] [**FHE**] Efficient FHE-based Privacy-Enhanced Neural Network for Trustworthy AI-as-a-Service
  >*Lam K Y, Lu X, Zhang L, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10398424)

* [**ArXiv 2024**] [**HE**] GuardML: Efficient Privacy-Preserving Machine Learning Services Through Hybrid Homomorphic Encryption
  >*Frimpong E, Nguyen K, Budzys M, et al.* [[Paper]](https://arxiv.org/pdf/2401.14840.pdf)

* [**IEEE Access 2024**] [**Bootstrapping, NTT**] A Bootstrapping-Capable Configurable NTT Architecture for Fully Homomorphic Encryption
  >*Mareta R, Satriawan A, Duong P N, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10496101)

* [**Cryptography 2024**] [**HE, Polynomial Approximation**] An Efficient Homomorphic Argmax Approximation for Privacy-Preserving Neural Networks
  >*Zhang P, Duan A, Lu H.* [[Paper]](https://www.mdpi.com/2410-387X/8/2/18)

* [**ArXiv 2024**] [**Polynomial Approximation**] Batch-oriented Element-wise Approximate Activation for Privacy-Preserving Neural Networks
  >*Zhang P, Duan A, Zou X, et al.* [[Paper]](https://arxiv.org/pdf/2403.10920)

* [**Journal of Systems Architecture 2024**] [**ReLU Pruning**] DReP: Deep ReLU pruning for fast private inference
  >*Hu P, Sun L, Hu C, et al.* [[Paper]](https://www.sciencedirect.com/science/article/pii/S1383762124000936)

* [**ArXiv 2024**] [**LLM**] FastQuery: Communication-efficient Embedding Table Query for Private LLM Inference
  >*Lin C, Xu T, Yang Z, et al.* [[Paper]](https://arxiv.org/pdf/2405.16241)

* [**ArXiv 2024**] [**Quant**] EQO: Exploring Ultra-Efficient Private Inference with Winograd-Based Protocol and Quantization Co-Optimization
  >*Zeng W, Xu T, Li M, et al.* [[Paper]](https://arxiv.org/pdf/2404.09404)

* [**PLDI 2024**] [**Compiler**] A Tensor Compiler with Automatic Data Packing for Simple and Efficient Fully Homomorphic Encryption
  >*Krastev A, Samardzic N, Langowski S, et al.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3656382)

* [**TIFS 2023**] [**CKKS**] Optimized Privacy-Preserving CNN Inference With
Fully Homomorphic Encryption
  >*Kim D, Guyot C.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10089847)

* [**ESORICS 2023**] [**PPML**] Efficient Pruning for Machine Learning Under Homomorphic Encryption
  >*Aharoni, E. et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-51482-1_11?fromPaywallRec=true)

* [**ISPASS 2023**] [**Key-Switch**] CiFlow: Dataflow analysis and optimization of key switching for homomorphic encryption
  >*Neda N, Ebel A, Reynwar B, et al.* [[Paper]](https://arxiv.org/pdf/2311.01598)

* [**Cryptology ePrint Archive 2023**] [**RNS-CKKS, CNN**] High-Throughput Deep Convolutional Neural Networks on Fully Homomorphic Encryption Using Channel-By-Channel Packing
  >*Cheon J H, Kang M, Kim T, et al.* [[Paper]](https://eprint.iacr.org/2023/632.pdf)

* [**Journal of the Korea Institute of Information Security 2023**] [**FHE, Polynomial Approximation**] The Impact of Various Degrees of Composite Minimax ApproximatePolynomials on Convolutional Neural Networks over Fully HomomorphicEncryption
  >*Lee J, No J S.* [[Paper]](https://koreascience.kr/article/JAKO202304562084769.pdf)

* [**Cryptology ePrint Archive 2023**] [**FHE**] High-Throughput Deep Convolutional Neural Networks on Fully Homomorphic Encryption Using Channel-By-Channel Packing
  >*Cheon J H, Kang M, Kim T, et al.* [[Paper]](https://eprint.iacr.org/2023/632.pdf)

* [**ArXiv 2023**] [**HE**] Robust Representation Learning for Privacy-Preserving Machine Learning: A Multi-Objective Autoencoder Approach
  >*Ouaari S, Ünal A B, Akgün M, et al.* [[Paper]](https://arxiv.org/pdf/2309.04427)

* [**Applied Sciences 2023**] [**HE, CKKS**] Lhdnn: Maintaining high precision and low latency inference of deep neural networks on encrypted data
  >*Qian J, Zhang P, Zhu H, et al.* [[Paper]](https://www.mdpi.com/2076-3417/13/8/4815)

* [**ArXiv 2023**] [**FHE, Polynomial Approximation**] Optimizing layerwise polynomial approximation for efficient private inference on fully homomorphic encryption: a dynamic programming approach
  >*Lee J, Lee E, Kim Y S, et al.* [[Paper]](https://arxiv.org/pdf/2310.10349)

* [**ArXiv 2023**] [**Polynomial Approximation**] Regularized PolyKervNets: Optimizing Expressiveness and Efficiency for Private Inference in Deep Neural Networks
  >*Aremu T.* [[Paper]](https://arxiv.org/pdf/2312.15229)

* [**ArXiv 2023**] [**MPC, Polynomial Approximation**] Fast and Private Inference of Deep Neural Networks by Co-designing Activation Functions
  >*Diaa A, Fenaux L, Humphries T, et al.* [[Paper]](https://www.usenix.org/system/files/sec24summer-prepub-373-diaa.pdf)

* [**ArXiv 2023**] [**CKKS, CNN, Boostrapping**] NeuJeans: Private Neural Network Inference with Joint Optimization of
Convolution and Bootstrapping
  >*Ju J H, Park J, Kim J, et al.* [[Paper]](https://arxiv.org/pdf/2312.04356)

* [**S&P 2023**] [**HE**] Poster: Packing-aware Pruning for Efficient Private Inference based on Homomorphic Encryption
  >*Ghazvinian P, Podschwadt R, Panzade P, et al.* [[Paper]](https://sp2023.ieee-security.org/downloads/SP23-posters/sp23-posters-paper35-final_version_2_page_abstract.pdf)

* [**ArXiv 2023**] [**CNN, HE**] Toward practical privacy-preserving convolutional neural networks exploiting fully homomorphic encryption
  >*Park J, Kim D, Kim J, et al.* [[Paper]](https://arxiv.org/pdf/2310.16530.pdf)

* [**ArXiv 2023**] [**MPC, LLMs**] Merge: Fast private text generation
  >*Liang Z, Wang P, Zhang R, et al.* [[Paper]](https://arxiv.org/pdf/2305.15769v3.pdf)

* [**DAC 2023**] [**MPC**] C2PI: An Efficient Crypto-Clear Two-Party Neural
Network Private Inference
  >*Zhang Y, Chen D, Kundu S, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247682/)

* [**ArXiv 2023**] [**HE**] Sensitive tuning of large scale cnns for e2e secure prediction using homomorphic encryption
  >*Baruch M, Drucker N, Ezov G, et al.* [[Paper]](https://arxiv.org/pdf/2304.14836)

* [**ArXiv 2023**] [**HE，CKKS**] Converting Transformers to Polynomial Form for Secure Inference Over Homomorphic Encryption
  >*Zimerman I, Baruch M, Drucker N, et al.* [[Paper]](https://arxiv.org/pdf/2311.08610.pdf)

* [**ArXiv 2023**] [**MPC**] Approximating ReLU on a Reduced Ring for Efficient MPC-based Private Inference
  >*Maeng K, Suh G E.* [[Paper]](https://arxiv.org/pdf/2309.04875.pdf)

* [**ArXiv 2023**] [**MPC**] Compact: Approximating Complex Activation Functions for Secure Computation
  >*Islam M, Arora S S, Chatterjee R, et al.* [[Paper]](https://arxiv.org/pdf/2309.04664.pdf)

* [**ArXiv 2023**] [**MPC**] RRNet: Towards ReLU-Reduced Neural Network for Two-party Computation Based Private Inference
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://arxiv.org/pdf/2302.02292.pdf)

* [**ICCV 2023**] [**MPC**] Autorep: Automatic relu replacement for fast private
network inference
  >*Peng H, Huang S, Zhou T, et al.* [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Peng_AutoReP_Automatic_ReLU_Replacement_for_Fast_Private_Network_Inference_ICCV_2023_paper.pdf)

* [**SaTML 2023**] [**MPC**] PolyKervNets: Activation-free Neural Networks For Efficient Private Inference
  >*Aremu T, Nandakumar K.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10136177)

* [**ICC 2023**] [**MPC**] SecMath: An Efficient 2-Party Cryptographic Framework for Math Functions
  >*Hu J, Li H, Chen H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10278842)

* [**ResearchGate 2023**] [**FHE**] PAF-FHE: Low-Cost Accurate Non-Polynomial Operator Polynomial Approximation in Fully Homomorphic Encryption Based ML Inference.
  >*Dang J, Tong J, Golder A, et al.* [[Paper]](https://www.researchsquare.com/article/rs-2910088/v1)

* [**ArXiv 2023**] [**HE, CNN**] Hyena: Optimizing Homomorphically Encrypted Convolution for Private CNN Inference
  >*Roh H, Choi W S.* [[Paper]](https://arxiv.org/pdf/2311.12519.pdf)

* [**IEEE Access 2023**] [**HE, CNN**] HyPHEN: A Hybrid Packing Method and Optimizations for Homomorphic Encryption-Based Neural Networks
  >*Kim D, Park J, Kim J, et al.* [[Paper]](https://arxiv.org/pdf/2302.02407.pdf)

* [**ICML 2023**] [**HE, Transfer Learning**] HETAL: Efficient Privacy-preserving Transfer Learning with Homomorphic Encryption
  >*Lee S, Lee G, Kim J W, et al.* [[Paper]](https://proceedings.mlr.press/v202/lee23m/lee23m.pdf)

* [**WWW 2023**] [**MPC**] Meteor: Improved Secure 3-Party Neural Network Inference with
Reducing Online Communication Costs
  >*Dong Y, Xiaojun C, Jing W, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3543507.3583272)

* [**TIFS 2023**] [**MPC**] VPiP: Values Packing in Paillier for Communication
Efficient Oblivious Linear Computations
  >*Wu W, Wang J, Zhang Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10167664)

* [**Cryptology eprint Archive 2023**] [**MPC**] FssNN: Communication-Efficient Secure Neural Network Training via Function Secret Sharing
  >*Yang P, Jiang Z L, Gao S, et al.* [[Paper]](https://eprint.iacr.org/2023/073)

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

* [**TDSC 2023**] [**HE**] More efficient secure matrix multiplication for unbalanced recommender systems
  >*Huang Z, Hong C, Weng C, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9665288)

* [**Nature Communications 2022**] [**HE**] Secure human action recognition by encrypted neural network inference
  >*Kim M, Jiang X, Lauter K, et al.* [[Paper]](https://www.nature.com/articles/s41467-022-32168-5.pdf)

* [**ICML 2022**] [**FHE, CKKS**] Low Complexity Deep Convolutional Neural Networks on Fully Homomorphic Encryption Using Multiplexed Parallel Convolutions
  >*Lee E, Lee J W, Lee J, et al.* [[Paper]](https://proceedings.mlr.press/v162/lee22e/lee22e.pdf)

* [**ACL 2022**] [**Transformer, CKKS**] THE-X: Privacy-Preserving Transformer Inference with Homomorphic Encryption
  >*Tianyu Chen et al.* [[Paper]](https://aclanthology.org/2022.findings-acl.277.pdf)

* [**NeurIPS 2022**] [**AHE**] Iron: Private Inference on Transformers
  >*Meng Hao et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/64e2449d74f84e5b1a5c96ba7b3d308e-Paper-Conference.pdf)

* [**ACNS 2022**] [**HE, Training**] A methodology for training homomorphic encryption friendly neural networks
  >*Baruch M, Drucker N, Greenberg L, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16815-4_29)

* [**ICML 2022**] [**MPC, HE**] Selective Network Linearization for Efficient Private Inference
  >*Cho M, Joshi A, Reagen B, et al.* [[Paper]](https://proceedings.mlr.press/v162/cho22a/cho22a.pdf)

* [**ICLR 2021**] [**Polynomial approximation**] SAFENet: A Secure, Accurate and Fast Neural Network Inference
  >*Qian Lou,Yinlin Shen et al.* [[Paper]](https://openreview.net/pdf?id=Cz3dbFm5u-)

* [**ICML 2021**] [**ReLU Pruning**] Deepreduce: Relu reduction for fast private inference
  >*Jha N K, Ghodsi Z, Garg S, et al.* [[Paper]](https://proceedings.mlr.press/v139/jha21a/jha21a.pdf)

* [**ICLR 2021**] [**FHE, BNN**] GATENET: BRIDGING THE GAP BETWEEN BINARIZED NEURAL NETWORK AND FHE EVALUATION
  >*Fu C, Huang H, Chen X, et al.* [[Paper]](https://aisecure-workshop.github.io/aml-iclr2021/papers/9.pdf)

* [**WIHMS 2021**] [**MPC, Replicated Secret Share, BNN**] Banners: Binarized Neural Networks with Replicated Secret Sharing
  >*Ibarrondo A, Chabanne H, Önen M.* [[Paper]](https://eprint.iacr.org/2021/045.pdf)

* [**NeurIPS 2020**] [**HE**] Falcon: Fast spectral inference on encrypted data
  >*Lou Q, Lu W, Hong C, et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2020/file/18fc72d8b8aba03a4d84f66efabce82e-Paper.pdf)

* [**CVPR 2020**] [**HE**] Falcon: A fourier transform based approach for fast and secure convolutional neural network predictions
  >*Li S, Xue K, Zhu B, et al.* [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_FALCON_A_Fourier_Transform_Based_Approach_for_Fast_and_Secure_CVPR_2020_paper.html)

* [**CVPR 2020**] [**HE**] ENSEI: Efficient Secure Inference via Frequency-Domain Homomorphic Convolution for Privacy-Preserving Visual Recognition
  >*Bian S, Wang T, Hiromoto M, et al.* [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Bian_ENSEI_Efficient_Secure_Inference_via_Frequency-Domain_Homomorphic_Convolution_for_Privacy-Preserving_CVPR_2020_paper.pdf)


* [**ICML 2019**] [**HE**] Low Latency Privacy Preserving Inference
  >*Brutzkus A, Gilad-Bachrach R, Elisha O.* [[Paper]](https://proceedings.mlr.press/v97/brutzkus19a/brutzkus19a.pdf)

* [**CCS 2019**] [**MPC**] QUOTIENT: Two-Party Secure Neural Network Training and Prediction
  >*Agrawal N, Shahin Shamsabadi A, Kusner M J, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3319535.3339819)

* [**USENIX 2019**] [**MPC, OT, GC, BNN**] XONN: XNOR-based Oblivious Deep Neural Network Inference
  >*Riazi M S, Samragh M, Chen H, et al.* [[Paper]](https://www.usenix.org/conference/usenixsecurity19/presentation/riazi)

* [**AAAI 2019**] [**Logistic Regression, HE**] Logistic Regression on Homomorphic Encrypted Data at Scale
  >*Han K, Hong S, Cheon J H, et al.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5000)





## **System Designs** for PPML/PPNN
* [**Journal of Cryptographic Engineering 2025**] [**MPC, Transformer**] MLFormer: a high performance MPC linear inference framework for
transformers
  >*Liu S, Liu Z, Chen D, et al.* [[Paper]](https://link.springer.com/article/10.1007/s13389-024-00365-1)

* [**AAAI 2024**] [**MPC**] United We Stand: Accelerating Privacy-Preserving Neural Inference by
Conjunctive Optimization with Interleaved Nexus
  >*Zhang Q, Xiang T, Xin C, et al.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29620)


* [**ArXiv 2025**] [**LHE, Federated Learning**] Secure Distributed Learning for CAVs: Defending
Against Gradient Leakage with Leveled
Homomorphic Encryption
  >*Najjar M A, Huang R Y, Samaraweera D, et al.* [[Paper]](https://arxiv.org/pdf/2506.07894)


* [**TIFS 2025**] [**Secret Share, BFV**] Accelerating Private Large Transformers Inference
through Fine-grained Collaborative Computation
  >*Chen Y, Tang Z, Lu T, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/11059953)

* [**ArXiv 2024**] [**HE**] Privacy-Preserving Diffusion Model Using Homomorphic Encryption
  >*Chen Y, Yan Q.* [[Paper]](https://arxiv.org/pdf/2403.05794)

* [**TIFS 2024**] [**Mutual Information Autoencoder**] Approaching the Information-Theoretic Limit of Privacy Disclosure With Utility Guarantees
  >*ang Q, Wang C, Yuan H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10400514)

* [**Cryptology ePrint Archive 2024**] [**HE, CNN-Transformer,Rotation Reducation**] Low-Latency Linear Transformations with Small Key Transmission for Private Neural Network on Homomorphic Encryption
  >*Min B S, Lee J W.* [[Paper]](https://eprint.iacr.org/2024/883.pdf)

* [**ArXiv 2024**] [**HE, MPC**] Flash: A Hybrid Private Inference Protocol for Deep CNNs with High Accuracy and Low Latency on CPU
  >*Roh H, Yeo J, Ko Y, et al.* [[Paper]](https://arxiv.org/abs/2401.16732)

* [**ArXiv 2024**] [**HE, CNN**] UniHENN: Designing More Versatile Homomorphic Encryption-based CNNs without im2col
  >*Choi H, Kim J, Kim S, et al.* [[Paper]](https://arxiv.org/abs/2402.03060)

* [**AAAI 2024**] [**HE**] Blind-Touch: Homomorphic Encryption-Based Distributed Neural Network Inference for Privacy-Preserving Fingerprint Authentication
  >*Choi H, Woo S S, Kim H.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/30200)

* [**IEEE S&P 2024**] [**MPC, Transformer**] BOLT: Privacy-Preserving, Accurate and Efficient Inference for Transformers
  >*Pang Q, Zhu J, Möllering H, et al.* [[Paper]](https://eprint.iacr.org/2023/1893.pdf)

* [**ArXiv 2024**] [**ZKP**] FairProof : Confidential and Certifiable Fairness for Neural Networks
  >*Yadav C, Chowdhury A R, Boneh D, et al.* [[Paper]](https://arxiv.org/pdf/2402.12572.pdf)

* [**Information Sciences 2024**] [**MPC, Transformer**] SecureTLM: Private inference for transformer-based large model with MPC
  >*Chen Y, Meng X, Shi Z, et al.* [[Paper]](https://www.sciencedirect.com/science/article/pii/S0020025524003426)

* [**Cryptology ePrint Archive 2024**] [**RNS-CKKS, Transformer**] Secure Transformer Inference Made Non-interactive
  >*Zhang J, Liu J, Yang X, et al.* [[Paper]](https://eprint.iacr.org/2024/136.pdf)

* [**ArXiv 2024**] [**MPC, Transformer**] Secformer: Towards fast and accurate privacy-preserving inference for large language models
  >*Luo J, Zhang Y, Zhang J, et al.* [[Paper]](https://arxiv.org/pdf/2401.00793.pdf)

* [**TDSC 2024**] [**FHE**] Efficient FHE-based Privacy-Enhanced Neural Network for Trustworthy AI-as-a-Service
  >*Lam K Y, Lu X, Zhang L, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10398424)

* [**ArXiv 2024**] [**HE**] GuardML: Efficient Privacy-Preserving Machine Learning Services Through Hybrid Homomorphic Encryption
  >*Frimpong E, Nguyen K, Budzys M, et al.* [[Paper]](https://arxiv.org/pdf/2401.14840.pdf)

* [**ArXiv 2024**] [**HE, MPC**] HEQuant: Marrying Homomorphic Encryption and Quantization for
Communication-Efficient Private Inference
  >*Xu T, Li M, Wang R.* [[Paper]](https://arxiv.org/pdf/2401.15970.pdf)

* [**TIFS 2023**] [**MPC, FSS**] FastSecNet: An Efficient Cryptographic Framework for Private Neural Network Inference
  >*Hao M, Li H, Chen H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10081492)

* [**HOST 2023**] [**Bootstrapping**] FHE-Booster: Accelerating Fully Homomorphic
Execution with Fine-tuned Bootstrapping Scheduling
  >*T. White, C. Gouert, C. Yang and N. G.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10132930)

* [**Cryptology ePrint Archive 2023**] [**MPC, CNN**] FANNG-MPC: Framework for Artificial Neural Networks and Generic MPC
  >*Aaraj N, Aly A, Güneysu T, et al.* [[Paper]](https://eprint.iacr.org/2023/1918.pdf)

* [**Cryptology ePrint Archive 2023**] [**MPC, GPT**] Ciphergpt: Secure two-party gpt inference
  >*Hou X, Liu J, Li J, et al.* [[Paper]](https://eprint.iacr.org/2023/1147.pdf)

* [**Cryptology ePrint Archive 2023**] [**MPC, GPT**] SIGMA: secure GPT inference with function secret sharing
  >*Gupta K, Jawalkar N, Mukherjee A, et al.* [[Paper]](https://eprint.iacr.org/2023/1269.pdf)

* [**WAHC 2023**] [**RNS-CKKS**] High-precision RNS-CKKS on fixed but smaller word-size architectures: theory and application
  >*Agrawal R, Ahn J H, Bergamaschi F, et al.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3605759.3625257)

* [**ArXiv 2023**] [**Compiler, FHE**] Orion: A Fully Homomorphic Encryption Compiler for Private Deep Neural Network Inference
  >*Ebel A, Garimella K, Reagen B.* [[Paper]](https://arxiv.org/pdf/2311.03470.pdf)

* [**ArXiv 2023**] [**FHE**] TREBUCHET: Fully Homomorphic Encryption Accelerator for Deep Computation
  >*Cousins D B, Polyakov Y, Badawi A A* [[Paper]](https://arxiv.org/ftp/arxiv/papers/2304/2304.05237.pdf)

* [**ICCAD 2023**] [**HE**] Hyperdimensional Computing as a Rescue for Efficient Privacy-Preserving Machine Learning-as-a-Service
  >*Park J, Quan C, Moon H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10323815)

* [**Cryptology ePrint Archive 2023**] [**HE**] A New Framework for Fast Homomorphic Matrix Multiplication
  >*Zheng X, Li H, Wang D.* [[Paper]](https://eprint.iacr.org/2023/1649.pdf)

* [**PETS 2023**] [**HE**] HeLayers: A tile tensors framework for large neural networks on encrypted data
  >*Aharoni E, Adir A, Baruch M, et al.* [[Paper]](https://www.petsymposium.org/2023/files/papers/issue1/popets-2023-0020.pdf)

* [**SP 2023**] [**MPC**] Orca: FSS-based Secure Training and Inference with GPUs
  >*Jawalkar N, Gupta K, Basu A, et al.* [[Paper]](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a063/1RjEaAAmAAE)

* [**USENIX ATC 2023**] [**MPC**] {SecretFlow-SPU}: A Performant and {User-Friendly} Framework for {Privacy-Preserving} Machine Learning
  >*Ma J, Zheng Y, Feng J, et al.* [[Paper]](https://www.usenix.org/system/files/atc23-ma.pdf)

* [**AsiaCrypt 2023**] [**Rotation, HE**] Rotation Key Reduction for Client-Server
Systems of Deep Neural Network on Fully Homomorphic Encryption
  >*Lee J W, Lee E, Kim Y S, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-981-99-8736-8_2)

* [**ICML 2023**] [**CNN, HE**] SpENCNN: Orchestrating Encoding and Sparsity for Fast Homomorphically Encrypted Neural Network Inference
  >*Ran R, Luo X, Wang W, et al.* [[Paper]](https://proceedings.mlr.press/v202/ran23b/ran23b.pdf)

* [**TIFS 2023**] [**HE, Zero-Knowledge Proof**] pvCNN: Privacy-Preserving and Verifiable Convolutional Neural Network Testing
  >*J. Weng, J. Weng, G. Tang, A. Yang, M. Li and J. -N. Liu.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10086653)

* [**ArXiv 2023**] [**MPC, LLM**] LLMs Can Understand Encrypted Prompt: Towards Privacy-Computing Friendly Transformers
  >*Liu X, Liu Z.* [[Paper]](https://arxiv.org/pdf/2305.18396.pdf)

* [**ArXiv 2023**] [**MPC, Transformer**] East: Efficient and Accurate Secure Transformer Framework for Inference
  >*Ding Y, Guo H, Guan Y, et al.* [[Paper]](https://arxiv.org/pdf/2308.09923.pdf)

* [**Cryptology eprint 2023**] [**MPC, Transformer**] BumbleBee: Secure Two-party Inference Framework for Large Transformers
  >*Lu W, Huang Z, Gu Z, et al.* [[Paper]](https://eprint.iacr.org/2023/1678.pdf)

* [**ArXiv 2023**] [**TFHE, lookup-table**] TT-TFHE: a Torus Fully Homomorphic Encryption-Friendly Neural Network Architecture
  >*Adrien Benamira et al.* [[Paper]](https://arxiv.org/pdf/2302.01584.pdf)

* [**NeurIPS 2023**] [**GCN, HE**] Penguin: Parallel-Packed Homomorphic Encryption for Fast Graph Convolutional Network Inference
  >*Ran R, Xu N, Liu T, et al.* [[Paper]](https://openreview.net/forum?id=eXubleMT0q)

* [**ArXiv 2023**] [**HE, GCN**] LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference
  >*Peng H, Ran R, Luo Y, et al.* [[Paper]](https://arxiv.org/pdf/2309.14331.pdf)

* [**ArXiv 2023**] [**MPC, Polynomial Approximation, LLM**] PUMA: SECURE INFERENCE OF LLAMA-7B IN FIVE MINUTES
  >*Dong Y, Lu W, Zheng Y, et al.* [[Paper]](https://arxiv.org/pdf/2307.12533.pdf)

* [**ISPPASS 2023**] [**FHE**] PyTFHE: An End-to-End Compilation and Execution Framework for Fully Homomorphic Encryption Applications
  >*Ma J, Xu C, Wills L W.* [[Paper]](https://www.entropy-xu.me/attaches/pytfhe-ispass2023.pdf)

* [**TrustCom 2023**] [**HE**] Too Noisy, or Not Too Noisy? A Private Training in Machine Learning
  >*Krzywiecki Ł, Zaborowski G, Zawada M.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10538865)

* [**IEICE 2023**] [**Look-up Tables, HE**] Privacy Preserving Function Evaluation using Lookup Tables with Word-Wise FHE
  >*LI R, YAMANA H.* [[Paper]](https://www.jstage.jst.go.jp/article/transfun/advpub/0/advpub_2023EAP1114/_pdf)

* [**ArXiv 2023**] [**CNN, HE**] Training Large Scale Polynomial CNNs for E2E Inference over Homomorphic Encryption
  >*Baruch M, Drucker N, Ezov G, et al.* [[Paper]](https://arxiv.org/pdf/2304.14836)

* [**DAC 2023**] [**MPC, Polynomial Approximation, NAS**] PASNet: Polynomial Architecture Search Framework for Two-party Computation-based Secure Neural Network Deployment
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247663)

* [**TrustCom 2023**] [**MPC, GAN**] SecGAN: Honest-Majority Maliciously 3PC Framework for Privacy-Preserving Image Synthesis
  >*Yang Y, Liu L, Fu S, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10538551)

* [**TSC 2023**] [**MPC, GCN**] SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service
  >*S. Wang, Y. Zheng and X. Jia* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10035510)

* [**NeurIPS 2022**] [**GCN, CKKS**] CryptoGCN: Fast and Scalable Homomorphically Encrypted Graph Convolutional Network Inference
  >*Ran Ran, Nuo Xu et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/f5332c8273d02729730a9c24dec2135e-Paper-Conference.pdf)

* [**CCS 2022**] [**HE**] Private and Reliable Neural Network Inference
  >*Jovanovic N, Fischer M, Steffen S, et al.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3548606.3560709)

* [**ArXiv 2022**] [**Pruning**] He-pex: Efficient
machine learning under homomorphic encryption using pruning, permutation and expansion.
  >*Ehud Aharoni, Moran Baruch, Pradip Bose, Alper Buyuktosunoglu, Nir Drucker, Subhankar
Pal, Tomer Pelleg, Kanthi Sarpatwar, Hayim Shaul, Omri Soceanu, et al.* [[Paper]](https://arxiv.org/pdf/2207.03384)

* [**TDSC 2021**] [**MPC**] A Lightweight Privacy-Preserving CNN Feature
Extraction Framework for Mobile Sensing
  >*Huang K, Liu X, Fu S, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8700229)

* [**PLDI 2019**] [**Compiler, FHE**] CHET: An Optimizing Compiler for Fully-Homomorphic Neural-Network Inferencing.

  >*Roshan D, Olli S, Todd M, et al.* [[Paper]](https://www.cs.utexas.edu/~roshan/CHET.pdf) 

## **Hardware Acceleration** for PPML/PPNN
* [**DAC 2025**] [**CKKS, ASIC, FPGA**] Hypnos: Memory Efficient Homomorphic Processing Unit
  >*Wang H, Yang Y, Lu H, et al.* [[Paper]](https://luhang-hpu.github.io/files/Hypnos-DAC2025.pdf)


* [**Cryptology ePrint Archive 2025**] [**Compiler**] Bridging Usability and Performance: A Tensor Compiler for Autovectorizing Homomorphic Encryption
  >*Chen E, Brown F, Zheng W.* [[Paper]](https://eprint.iacr.org/2025/1319.pdf)


* [**ASPLOS 2025**] [**CKKS, Compiler, ASIC**] Cinnamon: A Framework for Scale-Out Encrypted AI
  >*Jayashankar S, Chen E, Tang T, et al.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3669940.3707260)


* [**ICML 2025**] [**GPU**] EncryptedLLM: Privacy-Preserving Large Language Model Inference via GPU-Accelerated Fully Homomorphic Encryption
  >*de Castro L, Escudero D, Agrawal A, et al.* [[Paper]](https://openreview.net/pdf?id=PGNff6H1TV)

* [**ArXiv 2024**] [**GPU**] Cheddar: A Swift Fully Homomorphic Encryption Library for CUDA GPUs
  >*Kim J, Choi W, Ahn J H.* [[Paper]](https://arxiv.org/pdf/2407.13055)

* [**MICRO 2023**] [**GPU, FHE**] GME: GPU-based Microarchitectural Extensions to
Accelerate Homomorphic Encryption
  >*Shivdikar K, Bao Y, Agrawal R, et al.* [[Paper]](https://arxiv.org/pdf/2309.11001)

* [**ISCA 2023**] [**CKKS**] SHARP: A Short-Word Hierarchical Accelerator for Robust and Practical Fully Homomorphic Encryption
  >*Jongmin Kim et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3579371.3589053)

* [**Cryptology ePrint Archive 2023**] [**GPU, MPC**] Force: Highly Efficient Four-Party Privacy-Preserving Machine Learning on GPU
  >*Dai T, Duan L, Jiang Y, et al.* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-47748-5_18)

* [**ISQED 2023**] [**CKKS,KS,NTT,RNS**] PriML: An Electro-Optical Accelerator for Private Machine Learning on Encrypted Data
  >*Mengxin Zheng,FanChSen et al.* [[Paper]](https://ieeexplore.ieee.org/document/10129302)

* [**HPCA 2023**] [**CKKS**] FxHENN: FPGA-based acceleration framework for homomorphic encrypted CNN inference
  >*Yilan Zhu Lei Ju et al.* [[Paper]](https://ieeexplore.ieee.org/document/10071133/)

* [**USENIX Security 2022**] [**MPC**] Piranha: A GPU Platform for Secure Computation
  >*Watson J L, Wagh S, Popa R A.* [[Paper]](https://www.usenix.org/conference/usenixsecurity22/presentation/watson)

* [**USENIX 2021**] [**MPC, GPU-friendly, AHE, ASS**] GForce: GPU-Friendly Oblivious and Rapid Neural Network Inference
  >*Ng L K L, Chow S S M.* [[Paper]](https://www.usenix.org/conference/usenixsecurity21/presentation/ng)

* [**TETC 2020**] [**GPU, HE, BFV**] Towards the AlexNet Moment for Homomorphic Encryption: HCNN, the First Homomorphic CNN on Encrypted Data With GPUs
  >*Al Badawi A, Jin C, Lin J, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9160866)

## **Network Architecture Optimizaiton** for PPML/PPNN
* [**Cryptology ePrint Archive 2024**] [**MENN, TFHE**] FHE-MENNs: Opportunities and Pitfalls for Accelerating Fully
Homomorphic Private Inference with Multi-Exit Neural Networks
  >*Folkerts L W, Tsoutsos N G.* [[Paper]](https://eprint.iacr.org/2024/1099.pdf)

* [**ArXiv 2024**] [**MPC, Transformer**] Secformer: Towards fast and accurate privacy-preserving inference for large language models
  >*Luo J, Zhang Y, Zhang J, et al.* [[Paper]](https://arxiv.org/pdf/2401.00793.pdf)

* [**TC 2023**] [**NAS, Secret Share**] Private Inference for Deep Neural Networks:
A Secure, Adaptive, and Efficient Realization
  >*Cheng K, Xi N, Liu X, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10224651)

* [**ArXiv 2023**] [**MPC**] CompactTag: Minimizing Computation Overheads in Actively-Secure MPC for Deep Neural Networks
  >*Wang Y, Sarkar P, Koti N, et al.* [[Paper]](https://arxiv.org/pdf/2311.04406.pdf)

* [**ICLR 2023**] [**MPC, Transformer**] MPCFORMER: FAST, PERFORMANT AND PRIVATE TRANSFORMER INFERENCE WITH MPC
  >*Li D, Shao R, Wang H, et al.* [[Paper]](https://arxiv.org/pdf/2211.01452.pdf)

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

* [**TIFS 2021**] [**CNN, FHE**] DOReN: Toward Efficient Deep Convolutional Neural Networks with Fully Homomorphic Encryption
  >*Meftah S, Tan B H M, Mun C F, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9460962)

* [**USENIX 2021**] [**GPU-friendly, MPC，AHE，ASS**] GForce: GPU-Friendly Oblivious and Rapid Neural Network Inference
  >*Ng L K L, Chow S S M.* [[Paper]](https://www.usenix.org/system/files/sec21-ng.pdf)

* [**ICML 2021**] [**HE, NAS**] HEMET: A Homomorphic-Encryption-Friendly Privacy-Preserving Mobile Neural Network Architecture
  >*Lou Q, Jiang L.* [[Paper]](https://proceedings.mlr.press/v139/lou21a/lou21a.pdf)

* [**ECAI 2020**] [**HE, Garbled Circuit, NAS**] NASS: Optimizing Secure Inference via Neural
Architecture Search
  >*Bian S, Jiang W, Lu Q, et al.* [[Paper]](https://par.nsf.gov/servlets/purl/10244146)

## **Device-Edge-Cloud Collaboration** for PPML/PPNN

* [**Frontiers in Electronics 2023**] [**HE, ASIC**] CoFHE: Software and hardware Co-design for FHE-based machine learning as a service
  >*Zheng M, Ju L, Jiang L.* [[Paper]](https://www.frontiersin.org/articles/10.3389/felec.2022.1091369/full)

* [**JSAC 2022**] [**Shamir Secret Share(MPC), Matrix-vector multiplication**] Privacy-Preserving Coded Mobile Edge Computing for Low-Latency Distributed Inference
  >*Schlegel R, Kumar S, Rosnes E, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9678363)

* [**DAC 2023**] [**MPC, Polynomial Approximation, NAS**] PASNet: Polynomial Architecture Search Framework for Two-party Computation-based Secure Neural Network Deployment
  >*Peng H, Zhou S, Luo Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247663)

* [**TSNE 2022**] [**MPC**] PCNNCEC: Efficient and Privacy-Preserving Convolutional Neural Network Inference Based on Cloud-Edge-Client Collaboration
  >*Wang J, He D, Castiglione A, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9782521)

* [**DATE 2022**] [**HE, FPGA**] coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation
  >*Han M, Zhu Y, Lou Q, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9774559)



## **Surveys and Performance Analysis** on PPML/PPNN

* [**ArXiv 2024**] [**Survey**] On Protecting the Data Privacy of Large Language Models (LLMs): A Survey
  >*Yan B, Li K, Xu M, et al.* [[Paper]](https://arxiv.org/pdf/2403.05156.pdf)

* [**ArXiv 2023**] [**Survey**] Secure Data Computation Using Deep Learning and Homomorphic Encryption: A Survey
  >*Al-Janabi A A, Al-Janabi S T F, Al-Khateeb B.* [[Paper]](https://openurl.ebsco.com/EPDB%3Agcd%3A4%3A17439556/detailv2?sid=ebsco%3Aplink%3Ascholar&id=ebsco%3Agcd%3A169957642&crl=c)

* [**MICRO 2023**] [**Survey**] Fully Homomorphic Encryption for Computer
Architects: A Fundamental Characterization Study
  >*Pal S, Swaminathan K, Aharoni E, et al.* [[Paper]](https://disccworkshop.org/assets/pdfs/DISCC_2023_paper_5.pdf)

* [**S&P 2023**] [**Survey**] SoK: Cryptographic Neural-Network Computation
  >*Lucien K. L. Ng，Sherman S. M. Chow et al.* [[Paper]](https://ieeexplore.ieee.org/document/10179483)

* [**ArXiv 2023**] [**Survey**] Data Privacy with Homomorphic Encryption in Neural Networks Training and Inference
  >*Ivone Amorim et al.* [[Paper]](https://arxiv.org/pdf/2305.02225.pdf)

* [**PPNA 2023**] [**Survey**] Privacy-preserving neural networks with Homomorphic encryption:
Challenges and opportunities
  >*Bernardo Pulido-Gaytan et al.* [[Paper]](https://link.springer.com/article/10.1007/s12083-021-01076-8)

* [**ISPASS 2022**] [**Survey**] Characterization of mpc-based private inference for transformer-based models
  >*Wang Y, Suh G E, Xiong W, et al.* [[Paper]](https://computing.ece.vt.edu/~wenjiex/publications/2022_ispass_mpc.pdf)

[Back to home](./README.md)