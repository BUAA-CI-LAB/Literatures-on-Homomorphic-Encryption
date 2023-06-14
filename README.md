# **Literatures on Homomorphic Encryption Acceleration**

A reading list for Acceleration on Homomorphic Encryption, including but not limited to related research on software and hardware level. The list covers related papers, conferences, tools and other resources. 

Literatures in this page are arranged from a classification perspective, including the following topics:

- [Algorithmic Acceleration for Homomorphic Encryption](#Algorithmic-Acceleration-for-Homomorphic-Encryption)
- [System Designs for Homomorphic Encryption](#System-Designs-for-Homomorphic-Encryption)
- [Hardware Acceleration for Homomorphic Encryption](#Hardware-Acceleration-for-Homomorphic-Encryption)
- [Surveys and Performance Analysis on Homomorphic Encryption](#Surveys-and-Performance-Analysis-on-Homomorphic-Encryption)
- [Maintainers](#maintainers)

Click [here](./By-Time.md) to view these literatures in a reverse chronological order. You can also find [Related Conferences](./General%20Resources/Conference.md), [Homomorphic Encryption Learning Tools](./General%20Resources/Frameworks%20%26%20Tools/), [Learning Materials on Homomorphic Encryption](./General%20Resources/Learning%20Materials) and Other Resources in [General Resources](./General%20Resources).



---
## **Algorithmic Acceleration** for Homomorphic Encryption


* [**ISPASS 2023**] [**TFHE**] PyTFHE: An End-to-End Compilation and Execution Framework for Fully Homomorphic Encryption Applications.

  >*Jiaao Ma, Lisa Wu Wills et, al.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)

* [**ResearchGate 2023**] [**FHE**] PAF-FHE: Low-Cost Accurate Non-Polynomial Operator Polynomial Approximation in Fully Homomorphic Encryption Based ML Inference.

  >*Dang J, Tong J, Golder A, et al.* [[Paper]](https://www.researchsquare.com/article/rs-2910088/v1)

* [**HCS 2023**] [**Paillier**] PHEP: Paillier Homomorphic Encryption Processors for Privacy Preserving Applications in Cloud Computing.

  >*Guiming Shi, Yi Li,Kaisheng Ma, et al.* [[Paper]](https://www.zhanhongtan.com/publication/hotchip23b/)

* [**DATE 2021**] [**BFV**] Real-time Private Membership Test using Homomorphic Encryption.

  >*Eduardo Chielle, Homer Gamil, Michail Maniatakos.* [[Paper]](https://ieeexplore.ieee.org/document/9473968/)

* [**DATE 2015**] [**CKKS**] Efficient Software Implementation of Ring-LWE Encryption.

  >*Ruan de C, Sujoy R, Frederik V, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-2481.pdf)

* [**TCAD 2020**] [**FHE**] Efficient Comparison and Addition for FHE With Weighted Computational Complexity Model.

  >*Neng Zhang, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9224873/)

* [**TCAD 2022**] [**BGV**] Efficient FHE Radix-2 Arithmetic Operations Based on Redundant Encoding. 

  >*Hou Z, Shaojun Wei, Leibo Liu, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9502150)

* [**ICCAD 2022**] [**BFV, BGV, CKKS**]Accelerating Fully Homomorphic Encryption by Bridging Modular and Bit-Level Arithmetic.

  >*Chielle E, Mazonka O, Maniatakos M* [[Paper]](https://arxiv.org/abs/2204.12201)

* [**ISCAS 2021**] [**BGV**] On Compare-and-Swap Optimization for Fully Homomorphic Encrypted Data.

  >*Chien-Chih Huang, Jyun-Neng Ji, Ming-Der Shieh.* [[Paper]](https://ieeexplore.ieee.org/document/9401078/)

* [**TCAS-I 2020**] [**Modular Multiplication**] Design and Implementation of a Low-Latency Modular Multiplication Algorithm.

  >*Erdinç Öztürk*  [[Paper]](https://ieeexplore.ieee.org/document/8968620)

* [**TCAS-I 2021**] [**Scalar Multiplication**] Radix-2w Arithmetic for Scalar Multiplication in Elliptic Curve Cryptography. 

  >*Abdelkrim Kamel Oudjida, Ahmed Liacha.* [[Paper]](https://ieeexplore.ieee.org/document/9349769)

* [**TCAS-I 2022**] [**Polynomial Multiplication**] Faster NTRU on ARM Cortex-M4 With TMVP-Based Multiplication. 

  >*Irem Keskinkurt Paksoy, Murat Cenk.* [[Paper]](https://ieeexplore.ieee.org/document/9835023/) 

* [**AAAI 2019**] [**FHE**] Logistic Regression on Homomorphic Encrypted Data at Scale.

  >*Kyoohyung H, Seungwan H, Jung C.* [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5000) 

* [**Crypto 2018**] [**BGV**] Faster Homomorphic Linear Transformations in HElib.

  >*Shai Halevi and Victor Shoup.*[[Paper]](https://www.shoup.net/papers/matmul.pdf)

* [**Crypto 2014**] [**BGV**] Algorithms in HElib.

  >*S. Halevi and V. Shoup* [[Paper]](https://www.iacr.org/archive/crypto2014/86160286/86160286.pdf) 

* [**Crypto 2013**] [**Bootstrapping**] Practical Bootstrapping in Quasilinear Time.

  >*Jacob Alperin-Sheriff, Chris Peikert* [[Paper]](https://web.eecs.umich.edu/~cpeikert/pubs/simpleboot.pdf) 

* [**EUPOCRYPT 2018**] [**Bootstrapping**] Homomorphic Lower Digits Removal and Improved FHE Bootstrapping.

  >*Hao Chen, Kyoohyung Han* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/324110348_Homomorphic_Lower_Digits_Removal_and_Improved_FHE_Bootstrapping/links/5b57d4e90f7e9bc79a60a2e0/Homomorphic-Lower-Digits-Removal-and-Improved-FHE-Bootstrapping.pdf) 

* [**EUPOCRYPT 2017**] [**CKKS**] Homomorphic Encryption for Arithmetic of Approximate Numbers.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 

* [**EUPOCRYPT 2015**] [**FHEW**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 

* [**AsiaCrypt 2022**] [**Bootstrapping**] High-Precision Bootstrapping for Approximate Homomorphic Encryption by Error Variance Minimization.

  >*Yongwoo L,  Joon-Woo L, Young K, et al.* [[Paper]](https://iacr.org/submit/files/slides/2022/eurocrypt/eurocrypt2022/239/slides.pdf) 

* [**AsiaCrypt 2021**] [**Bootstrapping, FHEW, TFHE**] Bootstrapping in FHEW-like cryptosystems.

  >*Yongwoo L,  Joon-Woo L, Young K, et al.* [[Paper]](https://iacr.org/submit/files/slides/2022/eurocrypt/eurocrypt2022/239/slides.pdf) 

* [**AsiaCrypt 2020**] [**Bootstrapping**] Bootstrapping for Approximate Homomorphic Encryption.

  >*Micciancio D, Polyakov Y.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3474366.3486924) 

* [**AsiaCrypt 2016**] [**Bootstrapping**] Faster fully homomorphic encryption: Bootstrapping in less than 0.1 seconds.

  >*Ilaria C , Nicolas G, Malika Izabachene, et al.* [[Paper]](https://www.iacr.org/archive/asiacrypt2016/10031271/10031271.pdf) 

* [**HOST 2020**] [**TFHE**] CPU and GPU Accelerated Fully Homomorphic Encryption.

  >*Toufifique M, Md M, Noman M* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9300288/) 

* [**IEEE Access 2020**] [**FHE**] PrivFT: Private and Fast Text Classification With Homomorphic Encryption.

  >*Ahmad B, Louie H, Chan M, et al. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9296754) 

* [**IEEE Access 2020**] [**FHE**] Privacy-Preserving Machine Learning With Fully Homomorphic Encryption for Deep Neural Network.

  >*Joon-woo L, Hyungchul K, Jong-Seon N, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9734024) 

* [**IEEE Access 2018**] [**Bootstrapping**] Faster Bootstrapping With Multiple Addends.

  >*Zhou T, Yang X, Liu L, et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8449914) 

* [**JMIR 2018**] [**FHE, Logistic Regression**] Secure Logistic Regression Based on Homomorphic Encryption: Design and Evaluation.

  >*Miran K, Yongsoo S, Shuang Wang, et al.* [[Paper]](https://www.researchgate.net/profile/Yongsoo-Song/publication/324583361_Secure_Logistic_Regression_Based_on_Homomorphic_Encryption_Design_and_Evaluation/links/5bd3e4b992851c6b27920987/Secure-Logistic-Regression-Based-on-Homomorphic-Encryption-Design-and-Evaluation.pdf) 

* [**PLDI 2019**] [**FHE**] CHET: An Optimizing Compiler for Fully-Homomorphic Neural-Network Inferencing.

  >*Roshan D, Olli S, Todd M, et al.* [[Paper]](https://www.cs.utexas.edu/~roshan/CHET.pdf) 

* [**CHES 2015**] [**FHE NTT**] Accelerating homomorphic evaluation on reconfigurable hardware.

  >*T. Poppelmann, M. Naehrig, A. Macias, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930139/92930139.pdf) 

* [**CHES 2015**] [**FHE NTT**] Accelerating LTV Based Homomorphic Encryption in Reconfigurable Hardware.

  >*Yarkın Doroz, Erdinc Ozturk, Berk Sunar, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930182/92930182.pdf) 

* [**SAC 2018**] [**BFV, RNS**] A Full RNS Variant of Approximate Homomorphic Encryption.

  >*Jung C, Kyoohyung H, Yongsoo S, et al.* [[Paper]](https://www.researchgate.net/profile/Han-Kyoohyung/publication/330341753_A_Full_RNS_Variant_of_Approximate_Homomorphic_Encryption_25th_International_Conference_Calgary_AB_Canada_August_15-17_2018_Revised_Selected_Papers/links/5cd27fdaa6fdccc9dd93a38a/A-Full-RNS-Variant-of-Approximate-Homomorphic-Encryption-25th-International-Conference-Calgary-AB-Canada-August-15-17-2018-Revised-Selected-Papers.pdf) 

* [**SAC 2016**] [**FHE, Logistic Regression**] A Full RNS Variant of FV like Somewhat Homomorphic Encryption Schemes.

  >*Jean-Claude B, Julien E, Vincent Z, et al.* [[Paper]](https://webusers.imj-prg.fr/~jean-claude.bajard/MesPublis/SAC2016.pdf) 

* [**TETCI 2019**] [**BFV, RNS**] Implementation and Performance Evaluation of RNS Variants of the BFV Homomorphic Encryption Scheme.

  >*Ahmad B, Yuriy P, Kurt R, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8657794/)

* [**WAHC 2021**] [**FHE**] Intel HEXL: Accelerating Homomorphic Encryption with Intel AVX512-IFMA52.

  >*Fabian B, Sejun K, Vinodh G, et al.* [[Paper]](https://fabianboemer.com/files/intel-hexl.pdf)

* [**IACR Cryptology ePrint Archive 2020**] [**CKKS**] Efficient Bootstrapping for Approximate Homomorphic Encryption with Non-Sparse Keys.

  >*Bossuat J P, Mouchet C, Troncoso-Pastoriza J, et al.* [[Paper]](https://eprint.iacr.org/2020/1203)


* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)

* [**IACR Cryptology ePrint Archive 2018**] [**BFV, RNS**] An improved RNS variant of the BFV homomorphic encryption scheme.

  >*S. Halevi, Y. Polyakov, and V. Shoup* [[Paper]](https://www.shoup.net/papers/rns-bfv.pdf)

* [**IACR Cryptology ePrint Archive 2015**] [**FHE**] A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)

* [**Commun.ACM 2010**] [**FHE**] Computing Arbitrary Functions of Encrypted Data.

  >*Craig Gentry*[[Paper]](http://www.cs.cmu.edu/afs/cs/project/pscico-guyb/realworld/www/slidesF15/easy-fhe.pdf)

* [**COMM 2014**] [**FHE**] Comparison-Based Computations Over Fully Homomorphic Encrypted Data.

  >*Togan M, Pleşca C* [[Paper]](https://scholar.google.com/scholar?cluster=10454670174768971220&hl=zh-CN&as_sdt=0,5&as_vis=1)

* [**DCC 2014**] [**FHE SIMD**] Fully Homomorphic SIMD Operations.

  >*N.P. Smart and F. Vercauteren* [[Paper]](https://www.researchgate.net/profile/Petter-Smart/publication/220334118_Fully_homomorphic_SIMD_operations/links/56f1f14308ae1cb29a3d1dbd/Fully-homomorphic-SIMD-operations.pdf)



## **System Designs** for Homomorphic Encryption


* [**ISCA 2022**] [**CKKS**] Graphite: optimizing graph neural networks on CPUs through cooperative software-hardware techniques. 

  >*Gong Z, Ji H, Yao Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527403)

* [**ISSCC 2022**] [**CKKS**] A 28nm 48KOPS 3.4J Op Agile Crypto-Processor for Post Quantum Cryptograph on Multi Mathematical Problems.

  >*Zhu Y, Wei S, Liu L et al.* [[Paper]](https://ieeexplore.ieee.org/document/9731783)

* [**CICC 2019**] [**NTT**] A 55nm 50nJ_encode 13nJ_decode Homomorphic Encryption Crypto-Engine for IoT Nodes to Enable Secure Computation on Encrypted Data. 1-4.

  >*Yoon I, Cao N, Amaravati A, et al* [[Paper]](https://ieeexplore.ieee.org/document/8780277)

* [**DAC 2021**] [**Polynomial Multiplication**] Efficient Implementation of Finite Field Arithmetic for Binary Ring-LWE Post Quantum Cryptography Through a Novel Lookup-Table-Like Method. 

  >*Jiafeng Xie,Pengzhou He, Wujie Wen.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9586151/)

* [**DAC 2021**] [**FHE-PIM**] (Invited)Accelerating Fully Homomorphic Encryption with Processing in Memory.

  >*Saransh Gupta, Tajana Simunic Rosing* [[Paper]](https://ieeexplore.ieee.org/document/9586285/)

* [**DATE 2022**] [**CKKS**] coxHE: A software-hardware co-design framework for FPGA acceleration of homomorphic computation.

  >*Han M, Zhu Y, Lei Ju, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9774559)

* [**ESSCIRC 2022**] [**PQC**] Configurable Energy-Efficient Lattice-Based PostQuantum Cryptography Processor for IoT Devices.

  >*Kim B, Park J, Sim J, et al* [[Paper]](https://ieeexplore.ieee.org/document/9911531/)

* [**CHES 2021**] [**Bootstrapping**] Over 100x Faster Bootstrapping in Fully Homomorphic Encryption through Memory-centric Optimization with GPUs.

  >*Wonkyung J, Sangpyo K, Jung A, et al.* [[Paper]](https://tches.iacr.org/index.php/TCHES/article/view/9062) 

* [**CHES 2018**] [**BFV**] High-Performance FV Somewhat Homomorphic Encryption on GPUs: An Implementation using CUDA.

  >*Ahmad B, Bharadwaj V, Chan M, et al.* [[Paper]](https://www.researchgate.net/profile/Ahmad-Al-Badawi/publication/346706228_High-Performance_FV_Somewhat_Homomorphic_Encryption_on_GPUs_An_Implementation_using_CUDA/links/6131df9238818c2eaf7ae5c9/High-Performance-FV-Somewhat-Homomorphic-Encryption-on-GPUs-An-Implementation-using-CUDA.pdf) 

* [**IISWC 2020**] [**NTT, Bootstrapping**] Accelerating Number Theoretic Transformations for Bootstrappable Homomorphic Encryption on GPUs.

  >*Sangpyo K, Wonkyung J, Jaiyoung P, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9251245) 

* [**CHES 2015**] [**FHE NTT**] Accelerating homomorphic evaluation on reconfigurable hardware. *T. Poppelmann.

  >M. Naehrig, A. Macias, et al.* [[Paper]](https://www.iacr.org/archive/ches2015/92930139/92930139.pdf) 

* [**CHES 2014**] [**NTT RLWE**] Compact Ring-LWE Cryptoprocessor.

  >*Sujoy R, Frederik V, Nele M, et al.*[[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-2444.pdf) 

* [**Reconfig 2019**] [**FHE, Modular Multiplier**] FPGA-based Accelerators of Fully Pipelined Modular Multipliers for Homomorphic Encryption.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8994793/) 

* [**TETCI 2016**] [**FHE**] Designing an FPGA-accelerated homomorphic encryption co-processor.

  >*Cousins D B, Rohloff K, Sumorok D.* [[Paper]](https://web.njit.edu/~rohloff/papers/2017/Rohloff_Cousins_Sumorok_TETC.pdf)

* [**SPSL 2021**] [**TFHE**] An FPGA-based Programmable Vector Engine for Fast Fully Homomorphic Encryption over the Torus.

  >*Y. Serhan Gener, Parker Newton, Daniel Tan, et al.* [[Paper]](https://people.ece.ubc.ca/lemieux/publications/gener-spsl2021.pdf)

* [**T-C 2018**] [**BFV**] HEPCloud: An FPGA-based multicore processor for FV somewhat homomorphic function evaluation.

  >*Sujoy R, Kimmo J, Ingrid V, et al.* [[Paper]](https://core.ac.uk/download/pdf/275655528.pdf)

* [**T-C 2018**] [**BFV**] Hardware/Software co-Design of an Accelerator for FV Homomorphic Encryption Scheme using Karatsuba Algorithm.

  >*Migliore V, Real M M, Lapotre V, et al.* [[Paper]](http://people.irisa.fr/Vincent.Migliore/publications/ieee-tc-2017.pdf)

* [**T-C 2015**] [**FHE**] Accelerating fully homomorphic encryption in hardware.

  >*Yarkın Doroz, Erdinc  Ozturk, and Berk Sunar.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6871300)

* [**T-C 2015**] [**FHE**] Optimised Multiplication Architectures for Accelerating Fully Homomorphic Encryption.

  >*Cao X, Moore C, O'Neill M, et al.* [[Paper]](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/17271213/Optimised_Mult_Archs_FHE_Final.pdf)

* [**T-C 2016**] [**FHE**] A Custom Accelerator for Homomorphic Encryption Applications

  >*Erdinc Ozturk, Yarkın Doroz, Erkay Savas.*[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7482844)

* [**DSD 2013**] [**NTT**] Evaluating the Hardware Performance of a Million-Bit Multiplier.

  >*Y. Doroz, E. Ozturk, and B. Sunar* [[Paper]](https://ieeexplore.ieee.org/document/6628381)
  
* [**ISCAS 2013**] [**FHE**] FPGA implementation of a large-number multiplier for fully homomorphic encryption.

  >*Wei Wang and Xinming Huang.* [[Paper]](https://users.wpi.edu/~xhuang/pubs/2013_wang_iscas.pdf)

* [**ISCAS 2020**] [**AES**] Accelerating Post-Quantum Cryptography using an Energy-Efficient TLS Crypto-Processor.

  >*Utsav Banerjee, Siddharth Das, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9180550)

* [**ISCAS 2020**] [**BGV**] VLSI Architecture of Polynomial Multiplication for BGV Fully Homomorphic Encryption.

  >*Hsu H and Shieh M.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9181192)

## **Hardware Acceleration** for Homomorphic Encryption

* [**ISCA 2022**] [**CKKS**] BTS: An Accelerator for Bootstrappable Fully Homomorphic Encryption.
  
  >*Kim S, Kim J, Ahn Jung, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3470496.3527415)
  
* [**ISCA 2022**] [**FHE**] CraterLake: A Hardware Accelerator for Efficient Unbounded Computation on Encrypted Data.

  >*Samardzic N, Feldmann A, Krastev A, et al.* [[Paper]](https://people.csail.mit.edu/devadas/pubs/craterlake.pdf)

* [**MICRO 2022**] [**CKKS**] ARK: Fully Homomorphic Encryption Accelerator with Runtime Data Generation and Inter-Operation Key Reuse.

  >*Kim J, Lee G, Ahn J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9923889/)

* [**MICRO 2021**] [**CKKS**] F1: A Fast and Programmable Accelerator for Fully Homomorphic Encryption (Extended Version)

  >*Feldmann A, Samardzic N, Sanchez D, et al.* [[Paper]](https://dl.acm.org/doi/10.1145/3466752.3480070)

* [**ASPLOS 2022**] [**CKKS, BFV**] CHOCO: Client-Optimized Algorithms and Acceleration for Encrypted Compute Offloading

  >*McKenzie van der Hagen, Brandon Lucia.* [[Paper]](https://dl.acm.org/doi/abs/10.1145/3503222.3507737)

* [**ASPLOS 2020**] [**CKKS**] HEAX: An Architecture for Computing on Encrypted Data.

  >*M. Sadegh Riazi, Blake Pelton, Wei Dai, et al.* [[Paper]](https://arxiv.org/abs/1909.09731)

* [**HPCA 2023**] [**CKKS**] FxHENN: FPGA-based acceleration framework for homomorphic encrypted CNN inference
  
  >*Yilan Zhu Lei Ju et al.* [[Paper]](https://ieeexplore.ieee.org/document/10071133/)
  
* [**HPCA 2023**] [**CKKS**] FAB: An FPGA-based Accelerator for Bootstrappable Fully Homomorphic Encryption
  
  >*Rashmi Agrawal et al.* [[Paper]](https://arxiv.org/abs/2207.11872)
  
* [**HPCA 2023**] [**CKKS**] TensorFHE: Achieving Practical Computation on Encrypted Data using GPGPU.
  
  >*Shengyu Fan,Mingzhe Zhang et al.* [[Paper]](https://arxiv.org/abs/2212.14191)
  
* [**HPCA 2023**] [**CKKS**] Poseidon: Practical Homomorphic Encryption Accelerator.
  
  >*Yinghao Yang Luhang et al.* [[Paper]](https://mingzhe-zhang.github.io/paper/Poseidon-HPCA2023.pdf)
  
* [**HPCA 2021**] [**BFV**] Cheetah: Optimizing and Accelerating Homomorphic Encryption for Private Inference.
  
  >*Reagen B, Choi W, Brooks D, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9407118)
  
* [**HPCA 2019**] [**BFV**] FPGA-Based High-Performance Parallel Architecture for Homomorphic Computing on Encrypted Data.
  
  >*Sujoy S, Furkan, T, Kimmo J, et al.* [[Paper]](https://ieeexplore.ieee.org/document/8675244)
  
* [**DAC 2022**] [**TFHE**] MATCHA: A Fast and Energy-Efficient Accelerator for Fully Homomorphic Encryption over the Torus.
  
  >*Lei Jiang, Qian Lou, Nrushad Joshi* [[Paper]](https://dl.acm.org/doi/10.1145/3489517.3530435)
  
* [**DAC 2020**] [**NTT**] CryptoPIM: In-memory Acceleration for Lattice-based Cryptographic Hardware. 
  
  >*Nejatollahi H, Gupta S, Dut N, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9218730)
  
* [**DAC 2020**] [**TFHE**] ROMEO: Conversion and Evaluation of HDL Designs in the Encrypted Domain.

  >*Charles Gouert, Nektarios Georgios Tsoutsos.* [[Paper]](https://ieeexplore.ieee.org/document/9218579/)

* [**DDECS 2023**] [**FHEW**] Hardware Acceleration of FHEW.

  >*Jonas Bertels, Ingrid Verbauwhede et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3621.pdf)

* [**DATE 2020**] [**CKKS**] A Flexible and Scalable NTT Hardware:Applications from Homomorphically Encrypted Deep Learning to Post-Quantum Cryptography.
  
  >*Mert A, Karabulut E, Aysu A, et al* [[Paper]](https://ieeexplore.ieee.org/document/9116470)
  
* [**HPEC 2022**] [**TFHE**] FPGA Acceleration of Fully Homomorphic Encryption over the Torus.
  
  >*Ye, Tian, Rajgopal Kannan, and Viktor K. Prasanna* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9926381/)
  
* [**CICC 2021**] [**Pairing**] A Low-Power Elliptic Curve Pairing Crypto-Processor for Secure Embedded Blockchain and Functional Encryption.
  
  >*Utsav Banerjee, Anantha P. Chandrakasan* [[Paper]](https://ieeexplore.ieee.org/document/9431552)
  
* [**TCAD 2021**] [**PQC**] Model-Architecture Co-Design for High Performance Temporal GNN Inference on FPGA.
  
  >*Canto A, Kermani M, Azarderakhsh R, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9179769)
  
* [**TPDS 2023**] [**FHE**] HE-Booster: An Efficient Polynomial Arithmetic Acceleration on GPUs for Fully Homomorphic Encryption
  
  >*Zhiwei Wang,Dan Meng et al.* [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10012383)
  
* [**ICCAD 2022**] [**TFHE**] Accelerating N-bit Operations over TFHE on Commodity CPU-FPGA.
  
  >*Nam K, Moon H, Paek Y, et al.* [[Paper]](https://dl.acm.org/doi/10.1016/j.sysarc.2022.102596)
  
* [**ICCAD 2022**] [**Polynomial Multiplication**] Fast and Compact Interleaved Modular Multiplication based on Carry Save Addition. 
  
  >*Mazonka O, Chielle E, Maniatakos M, et al* [[Paper]]( https://www.semanticscholar.org/paper/Faster-Interleaved-Modular-Multiplication-Based-on-Knezevic-Vercauteren/339dbecb72e03aacacdc8651b69a74f1f1dad232) 
  
* [**ICCAD 2022**] [**In-SRAM hash**] Inhale: Enabling High-Performance and Energy-Efficient In-SRAM Cryptographic Hash for IoT. 

  >*Jingyao Zhang, Elaheh Sadredini.* [[Paper]](https://arxiv.org/abs/2208.07570)

* [**IPDPS 2022**] [**CKKS**] Accelerating encrypted computing on intel gpus.
  
  >*Zhai Y, Ibrahim M, Qiu Y, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9820676)
  
* [**T-C 2020**] [**FHE**] HEAWS: An Accelerator for Homomorphic Encryption on the Amazon AWS FPGA.
  
  >*Furkan Turan, Sujoy Sinha Roy, Ingrid Verbauwhede* [[Paper]](https://ieeexplore.ieee.org/abstract/document/9072637)
  
* [**T-C 2015**] [**FHE**] Accelerating Fully Homomorphic Encryption in Hardware.

  >*Yarkın Doroz, Erdinc Ozturk, Berk Sunar* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)

* [**TVLSI 2020**] [**BFV**] Design and Implementation of Encryption/Decryption Architectures for BFV Homomorphic Encryption Scheme. 
  
  >*Ahmet Can Mert , ErdinÖztürk, Erkay Savas* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8866755)
  
* [**TVLSI 2020**] [**BFV**] Computing-in-Memory for Performance and Energy-Efficient Homomorphic Encryption.

  >*Reis D,  Takeshita J, Xiaobo Sharon Hu.* [[Paper]](https://ieeexplore.ieee.org/document/9179010)

* [**TVLSI 2022**] [**BFV, CKKS**] A Highly Unified Reconfigurable Multicore Architecture to Speed Up NTT/INTT for Homomorphic Polynomial Multiplication.

  >*Su Y, Yang B, Liu Y, et al.*  [[Paper]](https://ieeexplore.ieee.org/abstract/document/9761841/)

* [**TVLSI 2022**] [**BFV**] Efficient Homomorphic Convolution Designs on FPGA for Secure Inference.

  >*Xiao Hu, Minghao Li, Zhongfeng Wang, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9866023)

* [**TVLSI 2022**] [**AES**] VLSI Design of Advanced-Features AES Cryptoprocessor in the Framework of the European Processor Initiative.

  >*Nannipieri P, Matteo S, Fanucci L, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9631958/)

* [**ISCAS 2021**] [**NTT, RNS**] A Multi-Layer Parallel Hardware Architecture for Homomorphic Computation in Machine Learning. 
  
  >*Guozhu Xin, Yifan Zhao, Jun Han* [[Paper]](http://arxiv.org/abs/2206.08536)
  
* [**ISCAS 2021**] [**Polynomial Multiplication**] High-throughput Polynomial Multiplier Architecture for Lattice-based Cryptography.

  >*Taishin Shimada, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401755/)

* [**ISCAS 2021**] [**BN curve**] BN-254 based Multi-Core, Multi-Pairing Crypto-Processor for Functional Encryption.

  >*Ryohei Nakayama, Makoto Ikeda* [[Paper]](https://ieeexplore.ieee.org/document/9401283/)

* [**HEPC 2014**] [**FHE**] An FPGA co-processor implementation of Homomorphic Encryption.

  >*David B, John G, Kurt R, et al.* [[Paper]](https://ieee-hpec.org/2014/CD/index_htm_files/FinalPapers/38.pdf)

* [**ASAP 2015**] [**Bootstrapping**] Accelerating Bootstrapping in FHEW using GPUs.

  >*Moon L, Yongje L, Jung H, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/7245720)

* [**DSD 2019**] [**NTT**] Design and Implementation of a Fast and Scalable NTT-Based Polynomial Multiplier Architecture.

  >*Ahmet Can Mert, Erdinc Ozturk, Erkay Savas.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/8875148)

* [**FCCM 2020**] [**NTT, Bootstrapping**] Hardware Architecture of a Number Theoretic Transform for a Bootstrappable RNS-based Homomorphic Encryption Scheme.

  >*Sunwoong K, Keewoo L, Wonhee C, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9114594)

* [**TCAS-I 2020**] [**Modular Multiplication**] Lattice-Based Cryptoprocessor for CCA-Secure Identity-Based Encryption.

  >*Claudia P. Rentería-Mejía, Jaime Velasco-Medina* [[Paper]](https://ieeexplore.ieee.org/document/9046808)

* [**TCAS-I 2022**] [**NTT**] NTT Architecture for a Linux-Ready RISC-V Fully-Homomorphic Encryption Accelerator.

  >*Rogério Paludo, Leonel Sousa.* [[Paper]](https://ieeexplore.ieee.org/document/9763876/)

* [**TCAS-I 2022**] [**BFV**] ReMCA: A Reconfigurable Multi-Core Architecture for Full RNS Variant of BFV Homomorphic Evaluation.

  >*Yang Su, Yang B, Song-Yin Zhao, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9755024/)

* [**IEEE Access 2020**] [**BGV**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Yang Su, Bailong Yang, Luogeng Tian, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9194003)

* [**TETCI 2017**] [**FHE, CRT**] Designing an FPGA-Accelerated Homomorphic Encryption Co-Processor.,

  >*David C, Kurt Rf, Daniel S.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/6871300)
  
* [**Computer Science Machine Learning 2021**] [**Paillier**] FPGA-Based Hardware Accelerator for Leveled Ring-LWE Fully Homorphic Encryption. 

  >*Cheng X, Lu W, Chen S, et al.* [[Paper]](https://arxiv.org/abs/2107.13797)
  
* [**Computing Science Cryptography and Security 2020**] [**Paillier**] FPGA-Based Hardware Accelerator of Homomorphic Encryption for Efficient Federated Learning.

  >*Zhaoxiong Yang, Shuihai Hu, Kai Chen.* [[Paper]](https://arxiv.org/abs/2007.10560)
  
* [**ArXiv 2022**] [**FHE, Bootstrapping**] FAB: An FPGA-based Accelerator for Bootstrappable Fully Homomorphic Encryption. 

  >*Rashmi A, Leo de, Ajay J, et al.*[[Paper]](https://arxiv.org/abs/2207.11872)
  
* [**Cryptology ePrint Archive 2022**] [**BGV**] BASALISC: Programmable Asynchronous Hardware Accelerator for BGV Fully Homomorphic Encryption.

  >*Geelen R, Van Beirendonck M, Pereira H V L, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3492.pdf) 
  
* [**Cryptology ePrint Archive 2022**] [**FHE RNS**] Cuda-accelerated rns multiplication in word-wise homomorphic encryption schemes. 

  >*Shen S, Yang H, Liu Y, et al.* [[Paper]](https://eprint.iacr.org/2022/633) 



---
## **Surveys and Performance Analysis** on Homomorphic Encryption

* [**IEEE proceedings 2022**] [**Survey**] Survey on Fully Homomorphic Encryption, Theory, and Applications.

  >*Chiara M, Victor S, Marc M, et al.* [[Paper]](https://ieeexplore.ieee.org/document/9910347)

* [**CSUR 2022**] [**Survey**] A Survey on Homomorphic Encryption Schemes_Theory and Implementation. 

  >*Abbas Acar, Hidayet Aksu, A. Selcuk Uluagac.* [[Paper]]( https://dl.acm.org/doi/10.1145/3214303)
  
* [**CSUR 2022**] [**Survey**] Fully Homomorphic Encryption Using Ideal Lattices. 

  >*Abbas Acar, Hidayet Aksu, A. Selcuk Uluagac.* [[Paper]]( https://asset-pdf.scinapse.io/prod/2031533839/2031533839.pdf)
  
* [**IACR Cryptology ePrint Archive 2015**] [**Book**] A Guide to Fully Homomorphic Encryption.

  >*Frederik A, Colin B, Martin S, et al.* [[Paper]](https://eprint.iacr.org/2015/1192)
  
* [**IACR Cryptology ePrint Archive 2018**] [**FHE**] Homomorphic Encryption Standard.

  >*Martin A, Melissa C, Vinod V, et al* [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-77287-1_2)
  
* [**STOC 2009**] [**the Lattice-FHE scheme**] Fully homomorphic encryption using ideal lattices.

  >*Craig Gentry* [[Paper]](https://asset-pdf.scinapse.io/prod/2031533839/2031533839.pdf)
  
* [**EUROCRYPT 2010**] [**the DGHV scheme**] Fully Homomorphic Encryption over the Integers.

  >*van Dijk M, Gentry C, Halevi S, et al.* [[Paper]](https://luca-giuzzi.unibs.it/corsi/Support/papers-cryptography/616.pdf)
  
* [**EUROCRYPT 2010**] [**the BFV scheme**] Fully Homomorphic Encryption without Modulus Switching from Classical GapSVP.

  >*Zvika Brakerski* [[Paper]](https://www.iacr.org/archive/crypto2012/74170863/74170863.pdf)
  
* [**Crypto 2013**] [**the GSW scheme**] Homomorphic Encryption from Learning with Errors: Conceptually-Simpler, Asymptotically-Faster, Attribute-Based.

  >*Craig Gentry, Amit Sahai, Brent Waters* [[Paper]](https://seclab.skku.edu/wp-content/uploads/2017/02/340.pdf) 
  
* [**TOCT 2014**] [**the BGV scheme**] (Leveled) Fully Homomorphic Encryption without Bootstrapping.

  >*Brakerski Z, Gentry C, Vaikuntanathan V.* [[Paper]](http://people.csail.mit.edu/vinodv/6892-Fall2013/BGV.pdf) 
  
* [**EUPOCRYPT 2015**] [**the FHEW scheme**] FHEW: Bootstrapping Homomorphic Encryption in less than a second.

  >*Leo D, Daniele M, Centrum W, et al.* [[Paper]](https://ir.cwi.nl/pub/23686/23686B.pdf) 
  
* [**EUPOCRYPT 2017**] [**the CKKS scheme**] Homomorphic Encryption for Arithmetic of Approximate Numbers.

  >*Jung C, Andrey K, Yongsoo S, et al.* [[Paper]](https://eprint.iacr.org/2016/421.pdf?ref=https://codemonkey.link) 
  
* [**Journal of Cryptology 2020**] [**the TFHE scheme**] Fast Fully Homomorphic Encryption over the Torus.

  >*Chillotti, Ilaria, et al.* [[Paper]](https://www.esat.kuleuven.be/cosic/publications/article-3166.pdf) 



---
## **Maintainers**

- Shangtong Zhang, Beihang University. [[GitHub]](https://github.com/Zst0514)

