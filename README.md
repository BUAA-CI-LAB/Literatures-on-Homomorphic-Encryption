# **Literatures on Homomorphic Encryption Acceleration**

A reading list for Acceleration on Homomorphic Encryption, including but not limited to related research on software and hardware level. The list covers related papers, conferences, tools and other resources. 

Literatures in this page are arranged from a classification perspective, including the following topics:

- [Algorithmic Acceleration for Homomorphic Encryption](#Algorithmic-Acceleration-for-Homomorphic-Encryption)
- [System Designs for Homomorphic Encryption](#System-Designs-for-Homomorphic-Encryption)
- [Hardware Acceleration for Homomorphic Encryption](#Hardware-Acceleration-for-Homomorphic-Encryption)
- [Surveys and Performance Analysis on Homomorphic Encryption](#Surveys-and-Performance-Analysis-on-Homomorphic-Encryption)
- [Maintainers](#maintainers)

Click [here](./By-Time.md) to view these literatures in a reverse chronological order. You can also find [Related Conferences](./General%20Resources/Conference.md), [Homomorphic Encryption Learning Tools](./General%20Resources/Frameworks%20%26%20Tools/), [Learning Materials on Homomorphic Encryption](./General%20Resources/Learning%20Materials) and Other Resources in [General Resources](./General%20Resources). 

Click [here](./privacy_preserving_ML.md) to view papers for Privacy Preserving Machine Learning(Neural Networks)(PPML/PPNN).



---
## **Algorithmic Acceleration** for Homomorphic Encryption

* [**Cryptology ePrint Archive 2024**] [**Bootstrapping**] Relaxed Functional Bootstrapping: A New Perspective on BGV/BFV Bootstrapping
  >*Liu Z, Wang Y.* [[Paper]](https://eprint.iacr.org/2024/172.pdf)

* [**IEEE Access 2024**] [**Bootstrapping, NTT**] A Bootstrapping-Capable Configurable NTT Architecture for Fully Homomorphic Encryption
  >*Mareta R, Satriawan A, Duong P N, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10496101)

* [**Cryptology eprint 2024**] [**NTT**] Exploring the Advantages and Challenges of Fermat NTT in FHE Acceleration
  >*Kim A, Mert A C, Mukherjee A, et al.* [[Paper]](https://eprint.iacr.org/2024/314.pdf)

* [**Cryptology eprint Archive 2024**] [**FHE**] Application-Aware Approximate Homomorphic Encryption: Configuring FHE for Practical Use
  >*Alexandru A, Al Badawi A, Micciancio D, et al.* [[Paper]](https://eprint.iacr.org/2024/203.pdf)

* [**ArXiv 2023**] [**Key Switching**] CiFlow: Dataflow Analysis and Optimization of Key Switching for Homomorphic Encryption
  >*Neda N, Ebel A, Reynwar B, et al.* [[Paper]](https://arxiv.org/html/2311.01598v2)

* [**USENIX 2023**] [**Bootstrapping, Compiler**] DaCapo: Automatic Bootstrapping Management for Efficient Fully Homomorphic Encryption
  >*Cheon S, Lee Y, Kim D, et al.* [[Paper]](https://www.usenix.org/system/files/sec24summer-prepub-336-cheon.pdf)

* [**HOST 2023**] [**Bootstrapping**] FHE-Booster: Accelerating Fully Homomorphic Execution with Fine-tuned Bootstrapping Scheduling
  >*White T, Gouert C, Yang C, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10132930)

* [**TIFS 2023**] [**CNN**] Optimized Privacy-Preserving CNN Inference With Fully Homomorphic Encryption.
  >*DongWoo King et al.* [[Paper]](https://ieeexplore.ieee.org/document/10089847)


* [**ISPASS 2023**] [**TFHE**] PyTFHE: An End-to-End Compilation and Execution Framework for Fully Homomorphic Encryption Applications.

  >*Jiaao Ma, Lisa Wu Wills et, al.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)

* [**Arxiv 2023**] [**FHE**] HyPHEN: A Hybrid Packing Method and Optimizations for Homomorphic Encryption-Based Neural Networks.

  >*Donghwan Kim, Jaiyoung Park and Jung Ho Ahn, et, al* [[Paper]](https://www.zhanhongtan.com/publication/hotchip23b/) 

* [**ACL 2022**] [**Transformer, CKKS**] THE-X: Privacy-Preserving Transformer Inference with Homomorphic Encryption
  >*Tianyu Chen et al.* [[Paper]](https://aclanthology.org/2022.findings-acl.277.pdf)

* [**NeurIPS 2022**] [**AHE**] Iron: Private Inference on Transformers
  >*Meng Hao et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/64e2449d74f84e5b1a5c96ba7b3d308e-Paper-Conference.pdf)
  

* [**PAAP 2022**] [**Montgomery Modular**] The Fast Paillier Decryption with Montgomery Modular Multiplication Based on OpenMP
  >*Decong Lin et al.* [[Paper]](https://ieeexplore.ieee.org/document/10010630)
  
* [**TCAD 2022**] [**BGV**] Efficient FHE Radix-2 Arithmetic Operations Based on Redundant Encoding. 

  >*Hou Z, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9502150)
  
* [**ICCAD 2022**] [**BFV, BGV, CKKS**]Accelerating Fully Homomorphic Encryption by Bridging Modular and Bit-Level Arithmetic.

  >*Chielle E, Mazonka O, Maniatakos M* [[Paper]](https://arxiv.org/abs/2204.12201)

* [**TCAS-I 2022**] [**Polynomial Multiplication**] Faster NTRU on ARM Cortex-M4 With TMVP-Based Multiplication. 

  >*Irem Keskinkurt Paksoy, Murat Cenk.* [[Paper]](https://ieeexplore.ieee.org/document/9835023/) 

* [**AsiaCrypt 2022**] [**Bootstrapping**] High-Precision Bootstrapping for Approximate Homomorphic Encryption by Error Variance Minimization.

  >*Yongwoo L,  Joon-Woo L, Young K, et al.* [[Paper]](https://iacr.org/submit/files/slides/2022/eurocrypt/eurocrypt2022/239/slides.pdf) 

* [**DATE 2021**] [**BFV**] Real-time Private Membership Test using Homomorphic Encryption.

  >*Eduardo Chielle, Homer Gamil, Michail Maniatakos.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)

* [**WAHC 2021**] [**FHE**] Intel HEXL: Accelerating Homomorphic Encryption with Intel AVX512-IFMA52.

  >*Fabian B, Sejun K, Vinodh G, et al.* [[Paper]](https://fabianboemer.com/files/intel-hexl.pdf)

* [**ISCAS 2021**] [**BGV**] On Compare-and-Swap Optimization for Fully Homomorphic Encrypted Data.

  >*Chien-Chih Huang, Jyun-Neng Ji, Ming-Der Shieh.* [[Paper]](https://ieeexplore.ieee.org/document/9401078/)

* [**TCAS-I 2021**] [**Scalar Multiplication**] Radix-2w Arithmetic for Scalar Multiplication in Elliptic Curve Cryptography. 

  >*Abdelkrim Kamel Oudjida, Ahmed Liacha.* [[Paper]](https://ieeexplore.ieee.org/document/9349769)

* [**AsiaCrypt 2021**] [**Bootstrapping, FHEW, TFHE**] Bootstrapping in FHEW-like cryptosystems.

  >*Yongwoo L,  Joon-Woo L, Young K, et al.* [[Paper]](https://iacr.org/submit/files/slides/2022/eurocrypt/eurocrypt2022/239/slides.pdf)

* [**ICLR 2021**] [**TFHE**]  GATENET: BRIDGING THE GAP BETWEEN BINARIZED NEURAL NETWORK AND FHE EVALUATION
  >*Chen Fu,Hanxian Huang et al.* [[Paper]](https://aisecure-workshop.github.io/aml-iclr2021/papers/9.pdf)

* [**IJCAI 2021**] [**BFV, BGV**] Learning DNN Model with Error – Exposing the Hidden Model of BAYHENN
  >*Harry W. H. Wong et al.* [[Paper]](https://www.ijcai.org/proceedings/2020/0488.pdf)

* [**S&P 2021**] [**CKKS, FHEW, Bootstrapping**] PEGASUS: bridging polynomial and non-polynomial evaluations in homomorphic encryption
  >*Wenjie Lu,Yiping Ma et al.* [[Paper]](https://eprint.iacr.org/2020/1606.pdf)

* [**Cryptology ePrint Archive 2021**] [**TFHE, BNN**] REDsec: Running encrypted discretized neural networks in seconds
  >*Folkerts L, Gouert C, Tsoutsos N G.* [[Paper]](https://eprint.iacr.org/2021/1100.pdf)

* [**EUROCRYPT 2021**] [**Bootstrapping, RNS-CKKS, Polynomial approximation**] High-Precision Bootstrapping of RNS-CKKS Homomorphic Encryption Using Optimal Minimax Polynomial Approximation and Inverse Sine Function
  >*Joon-Woo Lee* [[Paper]](https://eprint.iacr.org/2020/552.pdf)

* [**TDSC 2021**] [**Polynomial approximation**] Minimax Approximation of Sign Function by Composite Polynomial for Homomorphic Comparison
  >*Eunsang Lee et al.* [[Paper]](https://ieeexplore.ieee.org/document/9517029)

* [**CT-RSA 2020**] [**Bootstrapping**] Better Bootstrapping for Approximate Homomorphic Encryption
  >*Kyoohyung Han et al.* [[Paper]](https://eprint.iacr.org/2019/688.pdf)

* [**TCAD 2020**] [**FHE**] Efficient Comparison and Addition for FHE With Weighted Computational Complexity Model.

  >*Neng Zhang, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9224873/)

* [**TCAS-I 2020**] [**Modular Multiplication**] Design and Implementation of a Low-Latency Modular Multiplication Algorithm.

  >*Erdinç Öztürk*  [[Paper]](https://ieeexplore.ieee.org/document/8968620)

* [**AsiaCrypt 2020**] [**Bootstrapping**] Bootstrapping for Approximate Homomorphic Encryption.

  >*Micciancio D, Polyakov Y.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3474366.3486924) 

* [**IACR Cryptology ePrint Archive 2020**] [**CKKS**] Efficient Bootstrapping for Approximate Homomorphic Encryption with Non-Sparse Keys.

  >*Bossuat J P, Mouchet C, Troncoso-Pastoriza J, et al.* [[Paper]](https://eprint.iacr.org/2020/1203)

* [**HOST 2020**] [**TFHE**] CPU and GPU Accelerated Fully Homomorphic Encryption.

  >*Toufifique M, Md M, Noman M* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9300288/) 

* [**IEEE Access 2020**] [**FHE**] PrivFT: Private and Fast Text Classification With Homomorphic Encryption.

  >*Ahmad B, Louie H, Chan M, et al. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9296754) 

* [**IEEE Access 2020**] [**FHE**] Privacy-Preserving Machine Learning With Fully Homomorphic Encryption for Deep Neural Network.

  >*Joon-woo L, Hyungchul K, Jong-Seon N, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9734024) 

* [**NeurIPS 2019**] [**TFHE**] SHE: A Fast and Accurate Privacy-Preserving Deep Neural Network Via Leveled TFHE and Logarithmic Data Representation
  >*Qian Lou, Lei Jiang* [[Paper]](https://www.researchgate.net/profile/Qian-Lou-4/publication/333600728_SHE_A_Fast_and_Accurate_Privacy-Preserving_Deep_Neural_Network_Via_Leveled_TFHE_and_Logarithmic_Data_Representation/links/5d76588c92851cacdb2cabb0/SHE-A-Fast-and-Accurate-Privacy-Preserving-Deep-Neural-Network-Via-Leveled-TFHE-and-Logarithmic-Data-Representation.pdf)

* [**IJCAI 2019**] [**BFV, BGV**] BAYHENN: Combining Bayesian Deep Learning and Homomorphic Encryption for Secure DNN Inference
  >*Peichen Xie,Guangyu Sun et al.* [[Paper]](https://arxiv.org/pdf/1906.00639.pdf)

* [**PLDI 2019**] [**Compiler, FHE**] CHET: An Optimizing Compiler for Fully-Homomorphic Neural-Network Inferencing.

  >*Roshan D, Olli S, Todd M, et al.* [[Paper]](https://www.cs.utexas.edu/~roshan/CHET.pdf) 

* [**TETCI 2019**] [**BFV, RNS**] Implementation and Performance Evaluation of RNS Variants of the BFV Homomorphic Encryption Scheme.

  >*Ahmad B, Yuriy P, Kurt R, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8657794/)

* [**AAAI 2019**] [**FHE**] Logistic Regression on Homomorphic Encrypted Data at Scale.

  >*Kyoohyung H, Seungwan H, Jung C.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5000) 

* [**Crypto 2018**] [**BGV**] Faster Homomorphic Linear Transformations in HElib.

  >*Shai Halevi and Victor Shoup.*[[Paper]](https://www.shoup.net/papers/matmul.pdf)

* [**IEEE Access 2018**] [**Bootstrapping**] Faster Bootstrapping With Multiple Addends.

  >*Zhou T, Yang X, Liu L, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8449914) 

* [**JMIR 2018**] [**FHE, Logistic Regression**] Secure Logistic Regression Based on Homomorphic Encryption: Design and Evaluation.

  >*Miran K, Yongsoo S, Shuang Wang, et al.* [[Paper]](https://www.researchgate.net/profile/Yongsoo-Song/publication/324583361_Secure_Logistic_Regression_Based_on_Homomorphic_Encryption_Design_and_Evaluation/links/5bd3e4b992851c6b27920987/Secure-Logistic-Regression-Based-on-Homomorphic-Encryption-Design-and-Evaluation.pdf) 

* [**SAC 2018**] [**BFV, RNS**] A Full RNS Variant of Approximate Homomorphic Encryption.

  >*Jung C, Kyoohyung H, Yongsoo S, et al.* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/330341753_A_Full_RNS_Variant_of_Approximate_Homomorphic_Encryption_25th_International_Conference_Calgary_AB_Canada_August_15-17_2018_Revised_Selected_Papers/links/5cd27fdaa6fdccc9dd93a38a/A-Full-RNS-Variant-of-Approximate-Homomorphic-Encryption-25th-International-Conference-Calgary-AB-Canada-August-15-17-2018-Revised-Selected-Papers.pdf) 

* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)

* [**IACR Cryptology ePrint Archive 2018**] [**BFV, RNS**] An improved RNS variant of the BFV homomorphic encryption scheme.

  >*S. Halevi, Y. Polyakov, and V. Shoup* [[Paper]](https://www.shoup.net/papers/rns-bfv.pdf)

* [**EUPOCRYPT 2018**] [**Bootstrapping**] Homomorphic Lower Digits Removal and Improved FHE Bootstrapping.

  >*Hao Chen, Kyoohyung Han* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/324110348_Homomorphic_Lower_Digits_Removal_and_Improved_FHE_Bootstrapping/links/5b57d4e90f7e9bc79a60a2e0/Homomorphic-Lower-Digits-Removal-and-Improved-FHE-Bootstrapping.pdf) 

* [**EUPOCRYPT 2017**] [**CKKS**] Homomorphic Encryption for Arithmetic of Approximate Numbers.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 

* [**SAC 2016**] [**FHE, Logistic Regression**] A Full RNS Variant of FV like Somewhat Homomorphic Encryption Schemes.

  >*Jean-Claude B, Julien E, Vincent Z, et al.* [[Paper]](https://webusers.imj-prg.fr/~jean-claude.bajard/MesPublis/SAC2016.pdf) 

* [**AsiaCrypt 2016**] [**Bootstrapping**] Faster fully homomorphic encryption: Bootstrapping in less than 0.1 seconds.

  >*Ilaria C , Nicolas G, Malika Izabachene, et al.* [[Paper]](https://www.iacr.org/archive/asiacrypt2016/10031271/10031271.pdf) 

* [**EUPOCRYPT 2015**] [**FHEW**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 

* [**CHES 2015**] [**FHE NTT**] Accelerating homomorphic evaluation on reconfigurable hardware.

  >*T. Poppelmann, M. Naehrig, A. Macias, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930139/92930139.pdf) 

* [**CHES 2015**] [**FHE NTT**] Accelerating LTV Based Homomorphic Encryption in Reconfigurable Hardware.

  >*Yarkın Doroz, Erdinc Ozturk, Berk Sunar, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930182/92930182.pdf) 


* [**IACR Cryptology ePrint Archive 2015**] [**FHE**] A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)

* [**DATE 2015**] [**CKKS**] Efficient Software Implementation of Ring-LWE Encryption.

  >*Ruan de C, Sujoy R, Frederik V, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-2481.pdf)

* [**COMM 2014**] [**FHE**] Comparison-Based Computations Over Fully Homomorphic Encrypted Data.

  >*Togan M, Pleşca C* [[Paper]](https://scholar.google.com/scholar?cluster=10454670174768971220&hl=zh-CN&as_sdt=0,5&as_vis=1)

* [**DCC 2014**] [**FHE SIMD**] Fully Homomorphic SIMD Operations.

  >*N.P. Smart and F. Vercauteren* [[Paper]](https://www.researchgate.net/profile/Petter-Smart/publication/220334118_Fully_homomorphic_SIMD_operations/links/56f1f14308ae1cb29a3d1dbd/Fully-homomorphic-SIMD-operations.pdf)

* [**Crypto 2014**] [**BGV**] Algorithms in HElib.

  >*S. Halevi and V. Shoup* [[Paper]](https://www.iacr.org/archive/crypto2014/86160286/86160286.pdf) 

* [**Crypto 2013**] [**Bootstrapping**] Practical Bootstrapping in Quasilinear Time.

  >*Jacob Alperin-Sheriff, Chris Peikert* [[Paper]](https://web.eecs.umich.edu/~cpeikert/pubs/simpleboot.pdf) 

* [**Commun.ACM 2010**] [**FHE**] Computing Arbitrary Functions of Encrypted Data.

  >*Craig Gentry*[[Paper]](http://www.cs.cmu.edu/afs/cs/project/pscico-guyb/realworld/www/slidesF15/easy-fhe.pdf)



## **System Designs** for Homomorphic Encryption

* [**ArXiv 2024**] [**FHE**] Taiyi: A high-performance CKKS accelerator for Practical Fully Homomorphic Encryption
  >*Fan S, Deng X, Tian Z, et al.* [[Paper]](https://arxiv.org/pdf/2403.10188.pdf)

* [**Cryptology ePrint Archive 2024**] [**AHE**] Application-Aware Approximate Homomorphic Encryption:
Configuring FHE for Practical Use
  >*Alexandru A, Al Badawi A, Micciancio D, et al.* [[Paper]](https://eprint.iacr.org/2024/203.pdf)

* [**MICRO 2023**] [**FHE**] MAD: Memory-Aware Design Techniques for Accelerating
Fully Homomorphic Encryption
  >*Agrawal R, De Castro L, Juvekar C, et al.* [[Paper]](https://dspace.mit.edu/bitstream/handle/1721.1/153275/3613424.3614302.pdf?sequence=1&isAllowed=y)

* [**ArXiv 2023**] [**FHE**] TREBUCHET: Fully Homomorphic Encryption Accelerator for Deep Computation
  >*Cousins D B, Polyakov Y, Badawi A A* [[Paper]](https://arxiv.org/ftp/arxiv/papers/2304/2304.05237.pdf)

* [**TDSC 2023**] [**HE**] HEaaN-STAT: a privacy-preserving statistical analysis toolkit for large-scale numerical, ordinal, and categorical data
  >*Lee Y, Seo J, Name Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10123977)

* [**PLDI 2023**] [**Compiler**] HEaaN.MLIR: An Optimizing Compiler for Fast Ring-Based
Homomorphic Encryption
  >*Park S, Song W, Nam S, et al. HEaaN.* [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3591228)

* [**Cryptology ePrint Archive 2023**] [**Compiler**] HEIR: A Unified Representation for Cross-Scheme Compilation of Fully Homomorphic Computation
  >*Bian S, Zhao Z, Zhang Z, et al.* [[Paper]](https://eprint.iacr.org/2023/1445.pdf)

* [**ArXiv 2023**] [**FHE**] ArctyrEX: Accelerated Encrypted Execution of General-Purpose Applications
  >*Gouert C, Joseph V, Dalton S, et al.* [[Paper]](https://arxiv.org/pdf/2306.11006.pdf)

* [**ArXiv 2023**] [**TFHE, lookup-table**] TT-TFHE: a Torus Fully Homomorphic Encryption-Friendly Neural Network Architecture
  >*Adrien Benamira et al.* [[Paper]](https://arxiv.org/pdf/2302.01584.pdf)

* [**DAC 2023**] [**NTT**] BP-NTT: Fast and Compact in-SRAM Number Theoretic Transform with Bit-Parallel Modular Multiplication
  >*Jinyao Zhang et al.* [[Paper]](https://arxiv.org/pdf/2303.00173.pdf)

* [**DAC 2023**] [**NTT**] NTT-PIM: Row-Centric Architecture and Mapping for Efficient Number-Theoretic Transform on PIM
  >*Jaewoo Park et al.* [[Paper]](https://arxiv.org/pdf/2310.09715.pdf)

* [**DAC 2023**] [**CKKS**] CHAM: A Customized Homomorphic Encryption Accelerator for Fast Matrix-Vector Product
  >*Xuanle Ren et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10247696)

* [**DAC 2023**] [**RNS, NTT, SIMD**] Towards A Formally Verified Fully Homomorphic Encryption Compute Engine
  >*Jeremy Casas et al.* [[Paper]](https://web.cecs.pdx.edu/~zhenkun/pub/dac2023.pdf)

* [**DAC 2023**] [**AHE, Transformer**] Primer: Fast Private Transformer Inference on Encrypted Data
  >*Mengxin Zheng, Qian Lou, Lei Jiang* [[Paper]](https://arxiv.org/pdf/2303.13679.pdf)

* [**NeurIPS 2022**] [**GCN, CKKS**] CryptoGCN: Fast and Scalable Homomorphically Encrypted Graph Convolutional Network Inference
  >*Ran Ran, Nuo Xu et al.* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/f5332c8273d02729730a9c24dec2135e-Paper-Conference.pdf)

* [**TCSII 2022**] [**NTT**] PipeNTT: A Pipelined Number Theoretic Transform Architecture
  >*Zewen Ye et al.* [[Paper]](https://ieeexplore.ieee.org/document/9802731)

* [**TVLSI 2022**] [**NTT-PIM**] MeNTT: A Compact and Efficient Processing-in-Memory Number Theoretic Transform (NTT) Accelerator
  >*Dai Li et al.* [[Paper]](https://ieeexplore.ieee.org/document/9725242)

* [**JXCDC 2022**] [**NTT-CIM**] RM-NTT: An RRAM-Based Compute-in-Memory Number Theoretic Transform Accelerator
  >*Yongmo Park et al.* [[Paper]](https://ieeexplore.ieee.org/document/9870678)

* [**ACNS 2022**] [**CKKS, BGV**] A methodology for training homomorphic encryption friendly neural networks
  >*Moran Baruch et al.* [[Paper]](https://arxiv.org/pdf/2111.03362.pdf)

* [**ISCA 2022**] [**CKKS**] Graphite: optimizing graph neural networks on CPUs through cooperative software-hardware techniques. 

  >*Gong Z, Ji H, Yao Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527403)

* [**ISSCC 2022**] [**CKKS**] A 28nm 48KOPS 3.4J Op Agile Crypto-Processor for Post Quantum Cryptograph on Multi Mathematical Problems.

  >*Zhu Y, Wei S, Liu L et al.* [[Paper]](https://ieeexplore.ieee.org/document/9731783)

* [**DATE 2022**] [**CKKS**] coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation.

  >*Han M, Zhu Y, Lei Ju, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9774559)

* [**ESSCIRC 2022**] [**PQC**] Configurable Energy-Efficient Lattice-Based PostQuantum Cryptography Processor for IoT Devices.

  >*Kim B, Park J, Sim J, et al* [[Paper]](https://ieeexplore.ieee.org/document/9911531/)

* [**DAC 2021**] [**Polynomial Multiplication**] Efficient Implementation of Finite Field Arithmetic for Binary Ring-LWE Post Quantum Cryptography Through a Novel Lookup-Table-Like Method. 

  >*Jiafeng Xie,Pengzhou He, Wujie Wen.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9586151/)

* [**DAC 2021**] [**FHE-PIM**] (Invited)Accelerating Fully Homomorphic Encryption with Processing in Memory.

  >*Saransh Gupta, Tajana Simunic Rosing* [[Paper]](https://ieeexplore.ieee.org/document/9586285/)

* [**CHES 2021**] [**Bootstrapping**] Over 100x Faster Bootstrapping in Fully Homomorphic Encryption through Memory-centric Optimization with GPUs.

  >*Wonkyung J, Sangpyo K, Jung A, et al.* [[Paper]](https://tches.iacr.org/index.php/TCHES/article/view/9062) 

* [**SPSL 2021**] [**TFHE**] An FPGA-based Programmable Vector Engine for Fast Fully Homomorphic Encryption over the Torus.

  >*Y. Serhan Gener, Parker Newton, Daniel Tan, et al.* [[Paper]](https://people.ece.ubc.ca/lemieux/publications/gener-spsl2021.pdf)

* [**IISWC 2020**] [**NTT, Bootstrapping**] Accelerating Number Theoretic Transformations for Bootstrappable Homomorphic Encryption on GPUs.

  >*Sangpyo K, Wonkyung J, Jaiyoung P, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9251245) 

* [**ISCAS 2020**] [**AES**] Accelerating Post-Quantum Cryptography using an Energy-Efficient TLS Crypto-Processor.

  >*Utsav Banerjee, Siddharth Das, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9180550)

* [**ISCAS 2020**] [**BGV**] VLSI Architecture of Polynomial Multiplication for BGV Fully Homomorphic Encryption.

  >*Hsu H and Shieh M.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9181192)

* [**DAC 2020**] [**NTT, RLWE**] CryptoPIM: In-memory Acceleration for Lattice-based Cryptographic Hardware
  >*Hamid Nejatollahi et al.* [[Paper]](https://ieeexplore.ieee.org/document/9218730)

* [**ICAR 2019**] [**NTT, Lattice**] Sapphire: A Configurable Crypto-Processor for Post-Quantum Lattice-based Protocols (Extended Version)
  >*Utsav Banerjee et al.* [[Paper]](https://tches.iacr.org/index.php/TCHES/article/view/8344)

* [**CICC 2019**] [**NTT**] A 55nm 50nJ_encode 13nJ_decode Homomorphic Encryption Crypto-Engine for IoT Nodes to Enable Secure Computation on Encrypted Data. 1-4.

  >*Yoon I, Cao N, Amaravati A, et al* [[Paper]](https://ieeexplore.ieee.org/document/8780277)

* [**Reconfig 2019**] [**FHE, Modular Multiplier**] FPGA-based Accelerators of Fully Pipelined Modular Multipliers for Homomorphic Encryption.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8994793/) 

* [**CHES 2018**] [**BFV**] High-Performance FV Somewhat Homomorphic Encryption on GPUs: An Implementation using CUDA.

  >*Ahmad B, Bharadwaj V, Chan M, et al.* [[Paper]](https://www.researchgate.net/profile/Ahmad-Al-Badawi/publication/346706228_High-Performance_FV_Somewhat_Homomorphic_Encryption_on_GPUs_An_Implementation_using_CUDA/links/6131df9238818c2eaf7ae5c9/High-Performance-FV-Somewhat-Homomorphic-Encryption-on-GPUs-An-Implementation-using-CUDA.pdf) 

* [**T-C 2018**] [**BFV**] HEPCloud: An FPGA-based multicore processor for FV somewhat homomorphic function evaluation.

  >*Sujoy R, Kimmo J, Ingrid V, et al.* [[Paper]](https://core.ac.uk/download/pdf/275655528.pdf)

* [**T-C 2018**] [**BFV**] Hardware/Software co-Design of an Accelerator for FV Homomorphic Encryption Scheme using Karatsuba Algorithm.

  >*Migliore V, Real M M, Lapotre V, et al.* [[Paper]](http://people.irisa.fr/Vincent.Migliore/publications/ieee-tc-2017.pdf)

* [**TETCI 2016**] [**FHE**] Designing an FPGA-accelerated homomorphic encryption co-processor.

  >*Cousins D B, Rohloff K, Sumorok D.* [[Paper]](https://web.njit.edu/~rohloff/papers/2017/Rohloff_Cousins_Sumorok_TETC.pdf)

* [**T-C 2016**] [**FHE**] A Custom Accelerator for Homomorphic Encryption Applications

  >*Erdinc Ozturk, Yarkın Doroz, Erkay Savas.*[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7482844)

* [**CHES 2015**] [**FHE NTT**] Accelerating homomorphic evaluation on reconfigurable hardware. *T. Poppelmann.

  >M. Naehrig, A. Macias, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930139/92930139.pdf) 

* [**T-C 2015**] [**FHE**] Accelerating fully homomorphic encryption in hardware.

  >*Yarkın Doroz, Erdinc  Ozturk, and Berk Sunar.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6871300)

* [**T-C 2015**] [**FHE**] Optimised Multiplication Architectures for Accelerating Fully Homomorphic Encryption.

  >*Cao X, Moore C, O'Neill M, et al.* [[Paper]](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/17271213/Optimised_Mult_Archs_FHE_Final.pdf)

* [**CHES 2014**] [**NTT RLWE**] Compact Ring-LWE Cryptoprocessor.

  >*Sujoy R, Frederik V, Nele M, et al.*[[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-2444.pdf) 

* [**DSD 2013**] [**NTT**] Evaluating the Hardware Performance of a Million-Bit Multiplier.

  >*Y. Doroz, E. Ozturk, and B. Sunar* [[Paper]](https://ieeexplore.ieee.org/document/6628381)
  
* [**ISCAS 2013**] [**FHE**] FPGA implementation of a large-number multiplier for fully homomorphic encryption.

  >*Wei Wang and Xinming Huang.* [[Paper]](https://users.wpi.edu/~xhuang/pubs/2013_wang_iscas.pdf)



## **Hardware Acceleration** for Homomorphic Encryption
* [**ArXiv 2024**] [**GPU**] Cheddar: A Swift Fully Homomorphic Encryption Library for CUDA GPUs
  >*Kim J, Choi W, Ahn J H.* [[Paper]](https://arxiv.org/pdf/2407.13055)

* [**TDSC 2024**] [**GPU**] Phantom: A CUDA-Accelerated Word-Wise Homomorphic Encryption Library
  >*Yang H, Shen S, Dai W, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10428046)

* [**Cryptology ePrint Archive 2024**] [**NTT, BGV**] Hardware Acceleration of the Prime-Factor and Rader NTT for BGV Fully Homomorphic Encryption
  >*Du Pont D, Bertels J, Turan F, et al.* [[Paper]](https://eprint.iacr.org/2024/217.pdf)

* [**MICRO 2023**] [**GPU, HE**] GME: GPU-based Microarchitectural Extensions to
Accelerate Homomorphic Encryption
  >*Shivdikar K, Bao Y, Agrawal R, et al.* [[Paper]](https://arxiv.org/pdf/2309.11001)

* [**Cryptology ePrint Archive 2023**] [**CKKS，FPGA**] Aloha-HE: A Low-Area Hardware Accelerator for Client-Side Operations in Homomorphic Encryption
  >*Krieger F, Hirner F, Mert A C, et al.* [[Paper]](https://eprint.iacr.org/2023/1736.pdf)

* [**ArXiv 2023**] [**PIM, FHE**] FHEmem: A Processing In-Memory Accelerator for Fully Homomorphic Encryption
  >*Zhou M, Nam Y, Gangwar P, et al.* [[Paper]](https://arxiv.org/pdf/2311.16293.pdf)

* [**ArXiv 2023**] [**Chiplet, FHE**] CiFHER: A Chiplet-Based FHE Accelerator with a
Resizable Structure
  >*Kim S, Kim J, Choi J.* [[Paper]](https://arxiv.org/abs/2308.04890)

* [**ArXiv 2023**] [**HE,Garbled Circuit**] Privacy Preserving In-memory Computing Engine 
  >*Haoran Geng et al.* [[Paper]](https://arxiv.org/pdf/2308.02648.pdf)

* [**Cryptology ePrint Archive 2023**] [**NTT, RNS, FHE**] REED: Chiplet-Based Scalable Hardware Accelerator for Fully Homomorphic Encryption
  >*Aikata Aikata et al.* [[Paper]](https://eprint.iacr.org/2023/1190.pdf)

* [**ISCA 2023**] [**CKKS**] SHARP: A Short-Word Hierarchical Accelerator for Robust and Practical Fully Homomorphic Encryption
  >*Jongmin Kim et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3579371.3589053)

* [**ISQED 2023**] [**CKKS,KS,NTT,RNS**] PriML: An Electro-Optical Accelerator for Private Machine Learning on Encrypted Data
  >*Mengxin Zheng,FanChSen et al.* [[Paper]](https://ieeexplore.ieee.org/document/10129302)

* [**HPCA 2023**] [**CKKS**] FxHENN: FPGA-based acceleration framework for homomorphic encrypted CNN inference
  >*Yilan Zhu Lei Ju et al.* [[Paper]](https://ieeexplore.ieee.org/document/10071133/)
  
* [**HPCA 2023**] [**CKKS**] FAB: An FPGA-based Accelerator for Bootstrappable Fully Homomorphic Encryption

  >*Rashmi Agrawal et al.* [[Paper]](https://arxiv.org/abs/2207.11872)

* [**HPCA 2023**] [**CKKS**] TensorFHE: Achieving Practical Computation on Encrypted Data using GPGPU.

  >*Shengyu Fan,Mingzhe Zhang et al.* [[Paper]](https://arxiv.org/abs/2212.14191)

* [**HPCA 2023**] [**CKKS**] Poseidon: Practical Homomorphic Encryption Accelerator.

  >*Yinghao Yang Luhang et al.* [[Paper]](https://mingzhe-zhang.github.io/paper/Poseidon-HPCA2023.pdf)

* [**DDECS 2023**] [**FHEW**] Hardware Acceleration of FHEW.

  >*Jonas Bertels, Ingrid Verbauwhede et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3621.pdf)

* [**TPDS 2023**] [**FHE**] HE-Booster: An Efficient Polynomial Arithmetic Acceleration on GPUs for Fully Homomorphic Encryption

  >*Zhiwei Wang,Dan Meng et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10012383)

* [**ISCA 2022**] [**CKKS**] BTS: An Accelerator for Bootstrappable Fully Homomorphic Encryption.
  
  >*Kim S, Kim J, Ahn Jung, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527415)
  
* [**ISCA 2022**] [**FHE**] CraterLake: A Hardware Accelerator for Efficient Unbounded Computation on Encrypted Data.

  >*Samardzic N, Feldmann A, Krastev A, et al.* [[Paper]](https://people.csail.mit.edu/devadas/pubs/craterlake.pdf)

* [**MICRO 2022**] [**CKKS**] ARK: Fully Homomorphic Encryption Accelerator with Runtime Data Generation and Inter-Operation Key Reuse.

  >*Kim J, Lee G, Ahn J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9923889/)

* [**ASPLOS 2022**] [**CKKS, BFV**] CHOCO: Client-Optimized Algorithms and Acceleration for Encrypted Compute Offloading

  >*McKenzie van der Hagen, Brandon Lucia.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503222.3507737)

* [**DAC 2022**] [**TFHE**] MATCHA: A Fast and Energy-Efficient Accelerator for Fully Homomorphic Encryption over the Torus.

  >*Lei Jiang, Qian Lou, Nrushad Joshi* [[Paper]](https://dl.acm.org/doi/10.1145/3489517.3530435)

* [**HPEC 2022**] [**TFHE**] FPGA Acceleration of Fully Homomorphic Encryption over the Torus.

  >*Ye, Tian, Rajgopal Kannan, and Viktor K. Prasanna* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9926381/)

* [**ICCAD 2022**] [**TFHE**] Accelerating N-bit Operations over TFHE on Commodity CPU-FPGA.

  >*Nam K, Moon H, Paek Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1016/j.sysarc.2022.102596)

* [**ICCAD 2022**] [**Polynomial Multiplication**] Fast and Compact Interleaved Modular Multiplication based on Carry Save Addition. 

  >*Mazonka O, Chielle E, Maniatakos M, et al* [[Paper]]( https://www.semanticscholar.org/paper/Faster-Interleaved-Modular-Multiplication-Based-on-Knezevic-Vercauteren/339dbecb72e03aacacdc8651b69a74f1f1dad232) 

* [**ICCAD 2022**] [**In-SRAM hash**] Inhale: Enabling High-Performance and Energy-Efficient In-SRAM Cryptographic Hash for IoT. 

  >*Jingyao Zhang, Elaheh Sadredini.* [[Paper]](https://arxiv.org/abs/2208.07570)

* [**IPDPS 2022**] [**CKKS**] Accelerating encrypted computing on intel gpus.

  >*Zhai Y, Ibrahim M, Qiu Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9820676)

* [**TVLSI 2022**] [**BFV, CKKS**] A Highly Unified Reconfigurable Multicore Architecture to Speed Up NTT/INTT for Homomorphic Polynomial Multiplication.

  >*Su Y, Yang B, Liu Y, et al.*  [[Paper]](https://ieeexplore.ieee.org/abstract/document/9761841/)

* [**TVLSI 2022**] [**BFV**] Efficient Homomorphic Convolution Designs on FPGA for Secure Inference.

  >*Xiao Hu, Minghao Li, Zhongfeng Wang, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9866023)

* [**TVLSI 2022**] [**AES**] VLSI Design of Advanced-Features AES Cryptoprocessor in the Framework of the European Processor Initiative.

  >*Nannipieri P, Matteo S, Fanucci L, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9631958/)

* [**TCAS-I 2022**] [**NTT**] NTT Architecture for a Linux-Ready RISC-V Fully-Homomorphic Encryption Accelerator.

  >*Rogério Paludo, Leonel Sousa.* [[Paper]](https://ieeexplore.ieee.org/document/9763876/)

* [**TCAS-I 2022**] [**BFV**] ReMCA: A Reconfigurable Multi-Core Architecture for Full RNS Variant of BFV Homomorphic Evaluation.

  >*Yang Su, Yang B, Song-Yin Zhao, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9755024/)

* [**ArXiv 2022**] [**FHE, Bootstrapping**] FAB: An FPGA-based Accelerator for Bootstrappable Fully Homomorphic Encryption. 

  >*Rashmi A, Leo de, Ajay J, et al.*[[Paper]](https://arxiv.org/abs/2207.11872)

* [**Cryptology ePrint Archive 2022**] [**BGV**] BASALISC: Programmable Asynchronous Hardware Accelerator for BGV Fully Homomorphic Encryption.

  >*Geelen R, Van Beirendonck M, Pereira H V L, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3492.pdf) 

* [**Cryptology ePrint Archive 2022**] [**FHE RNS**] Cuda-accelerated rns multiplication in word-wise homomorphic encryption schemes. 

  >*Shen S, Yang H, Liu Y, et al.* [[Paper]](https://eprint.iacr.org/2022/633) 

* [**FPL 2021**] [**BFV**] Performance Modeling and FPGA Acceleration of Homomorphic Encrypted Convolution
  >*Tian Ye et al.* [[Paper]](https://par.nsf.gov/servlets/purl/10339686)

* [**ISC 2021**] [**NTT**] FPGA Acceleration of Number Theoretic Transform
  >*Tian Ye, Yang Yang et al.* [[Paper]](https://par.nsf.gov/servlets/purl/10339679)

* [**HPCA 2021**] [**BFV**] Cheetah: Optimizing and Accelerating Homomorphic Encryption for Private Inference.
  
  >*Reagen B, Choi W, Brooks D, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9407118)
  
* [**MICRO 2021**] [**CKKS**] F1: A Fast and Programmable Accelerator for Fully Homomorphic Encryption (Extended Version)
  
  >*Feldmann A, Samardzic N, Sanchez D, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3466752.3480070)
  
* [**CICC 2021**] [**Pairing**] A Low-Power Elliptic Curve Pairing Crypto-Processor for Secure Embedded Blockchain and Functional Encryption.
  
  >*Utsav Banerjee, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9431552)
  
* [**TCAD 2021**] [**PQC**] Model-Architecture Co-Design for High Performance Temporal GNN Inference on FPGA.

  >*Canto A, Kermani M, Azarderakhsh R, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9179769)

* [**ISCAS 2021**] [**NTT, RNS**] A Multi-Layer Parallel Hardware Architecture for Homomorphic Computation in Machine Learning. 

  >*Guozhu Xin, Yifan Zhao, Jun Han* [[Paper]](http://arxiv.org/abs/2206.08536)

* [**ISCAS 2021**] [**Polynomial Multiplication**] High-throughput Polynomial Multiplier Architecture for Lattice-based Cryptography.

  >*Taishin Shimada, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401755/)

* [**ISCAS 2021**] [**BN curve**] BN-254 based Multi-Core, Multi-Pairing Crypto-Processor for Functional Encryption.

  >*Ryohei Nakayama, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401283/)

* [**Computer Science Machine Learning 2021**] [**Paillier**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Cheng X, Lu W, Chen S, et al.* [[Paper]](https://arxiv.org/abs/2107.13797)

* [**ASPLOS 2020**] [**CKKS**] HEAX: An Architecture for Computing on Encrypted Data.
  
  >*M. Sadegh Riazi, Blake Pelton, Wei Dai, et al.* [[Paper]](https://arxiv.org/abs/1909.09731)
  
* [**DAC 2020**] [**NTT**] CryptoPIM: In-memory Acceleration for Lattice-based Cryptographic Hardware. 
  
  >*Nejatollahi H, Gupta S, Dut N, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9218730)
  
* [**DAC 2020**] [**TFHE**] ROMEO: Conversion and Evaluation of HDL Designs in the Encrypted Domain.

  >*Charles Gouert, Nektarios Georgios Tsoutsos.* [[Paper]](https://ieeexplore.ieee.org/document/9218579/)

* [**DATE 2020**] [**CKKS**] A Flexible and Scalable NTT Hardware:Applications from Homomorphically Encrypted Deep Learning to Post-Quantum Cryptography.

  >*Mert A, Karabulut E, Aysu A, et al* [[Paper]](https://ieeexplore.ieee.org/document/9116470)

* [**T-C 2020**] [**FHE**] HEAWS: An Accelerator for Homomorphic Encryption on the Amazon AWS FPGA.
  
  >*Furkan Turan, Sujoy Sinha Roy, Ingrid Verbauwhede* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9072637)
  
* [**TVLSI 2020**] [**BFV**] Design and Implementation of Encryption/Decryption Architectures for BFV Homomorphic Encryption Scheme. 
  
  >*Ahmet Can Mert , ErdinÖztürk, Erkay Savas* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8866755)
  
* [**TVLSI 2020**] [**BFV**] Computing-in-Memory for Performance and Energy-Efficient Homomorphic Encryption.

  >*Reis D,  Takeshita J, Xiaobo Sharon Hu.* [[Paper]](https://ieeexplore.ieee.org/document/9179010)

* [**FCCM 2020**] [**NTT, Bootstrapping**] Hardware Architecture of a Number Theoretic Transform for a Bootstrappable RNS-based Homomorphic Encryption Scheme.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9114594)

* [**TCAS-I 2020**] [**Modular Multiplication**] Lattice-Based Cryptoprocessor for CCA-Secure Identity-Based Encryption.

  >*Claudia P. Rentería-Mejía, Jaime Velasco-Medina* [[Paper]](https://ieeexplore.ieee.org/document/9046808)

* [**IEEE Access 2020**] [**BGV**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Yang Su, Bailong Yang, Luogeng Tian, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9194003)

* [**Computing Science Cryptography and Security 2020**] [**Paillier**] FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning.

  >*Zhaoxiong Yang, Shuihai Hu, Kai Chen.* [[Paper]](https://arxiv.org/abs/2007.10560)

* [**HPCA 2019**] [**BFV**] FPGA-Based High-Performance Parallel Architecture for Homomorphic Computing on Encrypted Data.
  
  >*Sujoy S, Furkan, T, Kimmo J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/8675244)
  
* [**DSD 2019**] [**NTT**] Design and Implementation of a Fast and Scalable NTT-Based Polynomial Multiplier Architecture.
  
  >*Ahmet Can Mert, Erdinc Ozturk, Erkay Savas.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8875148)
  
* [**TETCI 2017**] [**FHE, CRT**] Designing an FPGA-Accelerated Homomorphic Encryption Co-Processor.,
  
  >*David C, Kurt Rf, Daniel S.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)
  
* [**T-C 2015**] [**FHE**] Accelerating Fully Homomorphic Encryption in Hardware.

  >*Yarkın Doroz, Erdinc Ozturk, Berk Sunar* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)

* [**ASAP 2015**] [**Bootstrapping**] Accelerating Bootstrapping in FHEW using GPUs.

  >*Moon L, Yongje L, Jung H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/7245720)

* [**HEPC 2014**] [**FHE**] An FPGA co-processor implementation of Homomorphic Encryption.

  >*David B, John G, Kurt R, et al.* [[Paper]](https://ieee-hpec.org/2014/CD/index_htm_files/FinalPapers/38.pdf)

  

---
## **Surveys and Performance Analysis** on Homomorphic Encryption

* [**MICRO 2023**] [**Survey**] Fully Homomorphic Encryption for Computer Architects: A Fundamental Characterization Study
  >*Pal S, Swaminathan K, Aharoni E, et al.* [[Paper]](https://disccworkshop.org/assets/pdfs/DISCC_2023_paper_5.pdf)

* [**S&P 2023**] [**Survey**] SoK: Cryptographic Neural-Network Computation
  >*Lucien K. L. Ng，Sherman S. M. Chow et al. * [[Paper]](https://ieeexplore.ieee.org/document/10179483)

* [**ArXiv 2023**] [**Survey**] Data Privacy with Homomorphic Encryption in Neural Networks Training and Inference
  >*Ivone Amorim et al.* [[Paper]](https://arxiv.org/pdf/2305.02225.pdf)

* [**PPNA 2023**] [**Survey**] Privacy-preserving neural networks with Homomorphic encryption:
Challenges and opportunities
  >*Bernardo Pulido-Gaytan et al.* [[Paper]](https://link.springer.com/article/10.1007/s12083-021-01076-8)

* [**IEEE proceedings 2022**] [**Survey**] Survey on Fully Homomorphic Encryption, Theory, and Applications.

  >*Chiara M, Victor S, Marc M, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9910347)

* [**CSUR 2022**] [**Survey**] A Survey on Homomorphic Encryption Schemes_Theory and Implementation. 

  >*Abbas Acar, Hidayet Aksu, A. Selcuk Uluagac.* [[Paper]]( https://dl.acm.org/doi/10.1145/3214303)
  
* [**CSUR 2022**] [**Survey**] Fully Homomorphic Encryption Using Ideal Lattices. 

  >*Abbas Acar, Hidayet Aksu, A. Selcuk Uluagac.* [[Paper]]( https://asset-pdf.scinapse.io/prod/2031533839/2031533839.pdf)
  
* [**Journal of Cryptology 2020**] [**the TFHE scheme**] Fast Fully Homomorphic Encryption over the Torus.

  >*Chillotti, Ilaria, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3166.pdf) 
  
* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)
  
* [**EUPOCRYPT 2017**] [**the CKKS scheme**] Homomorphic Encryption for Arithmetic of Approximate Numbers.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 
  
* [**IACR Cryptology ePrint Archive 2015**] [**Book**] A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)
  
* [**EUPOCRYPT 2015**] [**the FHEW scheme**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 
  
* [**TOCT 2014**] [**the BGV scheme**] (Leveled) Fully Homomorphic Encryption without Bootstrapping.

  >*Brakerski Z, Gentry C, Vaikuntanathan V.* [[Paper]](http://people.csail.mit.edu/vinodv/6892-Fall2013/BGV.pdf) 
  
* [**Crypto 2013**] [**the GSW scheme**] Homomorphic Encryption from Learning with Errors: Conceptually-Simpler, Asymptotically-Faster, Attribute-Based.

  >*Craig Gentry, Amit Sahai, Brent Waters* [[Paper]](https://seclab.skku.edu/wp-content/uploads/2017/02/340.pdf) 
  
* [**EUROCRYPT 2010**] [**the DGHV scheme**] Fully Homomorphic Encryption over the Integers.

  >*van Dijk M, Gentry C, Halevi S, et al.* [[Paper]](https://luca-giuzzi.unibs.it/corsi/Support/papers-cryptography/616.pdf)
  
* [**EUROCRYPT 2010**] [**the BFV scheme**] Fully Homomorphic Encryption without Modulus Switching from Classical GapSVP.

  >*Zvika Brakerski* [[Paper]](https://www.iacr.org/archive/crypto2012/74170863/74170863.pdf)

* [**STOC 2009**] [**the Lattice-FHE scheme**] Fully homomorphic encryption using ideal lattices.

  >*Craig Gentry* [[Paper]](https://asset-pdf.scinapse.io/prod/2031533839/2031533839.pdf)
  
  



---
## **Maintainers**

- Shangtong Zhang, Beihang University. [[GitHub]](https://github.com/Zst0514)
- Jiangtao Mu, Beihang University. [[Github]](https://github.com/Mujt)

