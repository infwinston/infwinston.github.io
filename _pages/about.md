---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to Wei-Lin Chiang's page!

* I am a CS PhD student in UC Berkeley [Sky Computing Lab](https://sky.cs.berkeley.edu/) (previously [RISElab](https://rise.cs.berkeley.edu/)), working with Prof. [Ion Stoica](http://people.eecs.berkeley.edu/~istoica/).
* I obtained my bachelor's and Master's degree from National Taiwan University under the supervision of Prof. [Chih-Jen Lin](https://scholar.google.com/citations?user=SLMkts8AAAAJ&hl=en).
* My research interests include AI systems, Cloud ML, optimization for ML, and scalable ML algorithms. Currently building an intercloud broker system, [SkyPilot](https://github.com/skypilot-org/skypilot), to bring them all together.
* I enjoy developing open-source ML software and I am always happy to learn how they are being used! Email me if you have questions or find [our projects](#Projects) useful.
* More details can be found in my [CV](https://infwinston.github.io/files/docs/CV.pdf).

## Work Experience

- **Intern@Amazon**, *Seattle* (May. 2021 - Aug. 2021)  
  Contrastive learning with Graph Neural Nets for information extraction on the web
- **Intern@Google Research**, *Mountain View* (Dec. 2018 - Mar. 2019)  
  Efficient algorithms for training large and deep GCN models.  
  [Cluster-GCN paper](https://arxiv.org/abs/1905.07953), [code](https://github.com/google-research/google-research/tree/master/cluster_gcn)
- **Intern@Alibaba Group**, *Hangzhou* (July 2017 - Sept. 2017)  
  Distributed ML algorithms on Alibaba’s parameter server ([KunPeng](https://www.kdd.org/kdd2017/papers/view/kunpeng-parameter-server-based-distributed-learning-systems-and-its-applica))
- **Intern@Microsoft Research Asia**, *Beijing* (Dec. 2016 - Feb. 2017)  
  Distributed training for deep learning frameworks
- **Intern@Microsoft**, *Redmond* (July 2016 - Oct. 2016)  
  Large-scale ML algorithms on Microsoft’s distributed platform ([REEF](https://reef.apache.org/))

## <a name="Projects"></a> Projects


- **SkyPilot** ([Project](https://github.com/skypilot-org/skypilot))  
  SkyPilot is an intercloud broker system for easily and cost-effectively deploying ML workloads on any cloud
- **Balsa** ([Project](https://github.com/balsa-project/balsa) | [Paper](https://arxiv.org/abs/2201.01441))  
  Balsa is a ML-based query optimizer, learning to optimize SQL queries by trial-and-error using deep RL and sim-to-real learning
- **Cluster-GCN** ([Project](https://github.com/google-research/google-research/tree/master/cluster_gcn) | [Paper](https://arxiv.org/abs/1905.07953))  
  One of the first scalable methods for training large (million-scale) and deep GCN  
  Achieved state-of-the-art performance on public datasets (e.g., PPI, Reddit)
- **Distributed LIBLINEAR** ([Project](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/distributed-liblinear/) | [Paper](https://epubs.siam.org/doi/pdf/10.1137/1.9781611975321.57))  
  Distributed extension of a widely-used linear classification package, [LIBLINEAR](https://github.com/cjlin1/liblinear)  
  Developed L1-regularized LR solver for solving large (billion-scale) tasks.
- **Multi-core LIBLINEAR** ([Project](https://github.com/cjlin1/liblinear) | [Paper](https://dl.acm.org/doi/10.1145/2939672.2939826))  
  Multi-core extension of a widely-used linear classification package, [LIBLINEAR](https://github.com/cjlin1/liblinear)  
  Developed efficient parallel algorithms for primal and dual solvers

## Publications ([Google Scholar Profile](https://scholar.google.com/citations?user=87nZphcAAAAJ&hl=en))


- [Balsa: Learning a Query Optimizer Without Expert Demonstrations](https://dl.acm.org/doi/10.1145/3514221.3517885)  
  Zongheng Yang, **Wei-Lin Chiang<sup>+</sup>**, Sifei Luan<sup>+</sup>, Gautam Mittal, Michael Luo, Ion Stoica. (+ equal contribution)  
  *ACM SIGMOD 2022*
- [Manifold Identification for Ultimately Communication-Efficient Distributed Optimization](http://www.optimization-online.org/DB_HTML/2020/06/7833.html)  
  Yu-Sheng Li, **Wei-Lin Chiang**, and Ching-pei Lee.  
  *International Conference on Machine Learning (ICML), 2020*
- [Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks](https://arxiv.org/abs/1905.07953) [[code](https://github.com/google-research/google-research/tree/master/cluster_gcn), [dataset (Amazon2M)](http://web.cs.ucla.edu/~chohsieh/data/Amazon2M.tar.gz)]  
  **Wei-Lin Chiang**, Xuanqing Liu, Si Si, Yang Li, Samy Bengio, and Cho-Jui Hsieh.  
  *ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD), 2019 (**Oral**)* [*slides*](https://infwinston.github.io/files/kdd19/slides.pdf), [*poster*](https://infwinston.github.io/files/kdd19/poster.pdf)  
- [Preconditioned Conjugate Gradient Methods in Truncated Newton Frameworks for Large-scale Linear Classification](http://proceedings.mlr.press/v95/hsia18a.html) [[supplement & code](https://www.csie.ntu.edu.tw/~cjlin/papers/tron_pcg/). Implementation available in [LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/liblinear/) after version 2.20.]  
  Chih-Yang Hsia, **Wei-Lin Chiang**, and Chih-Jen Lin.  
  *Asian Conference on Machine Learning (ACML), 2018 (**Best paper award**)* [*slides*](https://infwinston.github.io/files/acml18/slides.pdf), [*poster*](https://infwinston.github.io/files/acml18/poster.pdf)    
- [Limited-memory Common-directions Method for Distributed L1-regularized Linear Classification](https://www.csie.ntu.edu.tw/~cjlin/papers/l-commdir-l1/OWL-commdir.pdf) [[supplement & code](https://www.csie.ntu.edu.tw/~cjlin/papers/l-commdir-l1/). Implementation available in [Distributed LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/distributed-liblinear/).]  
  **Wei-Lin Chiang**, Yu-Sheng Li, Ching-pei Lee, and Chih-Jen Lin.  
  *SIAM International Conference on Data Mining (SDM), 2018* [*slides*](https://infwinston.github.io/files/sdm18/slides.pdf), [*poster*](https://infwinston.github.io/files/sdm18/poster.pdf)   
- [Parallel Dual Coordinate Descent Method for Large-scale Linear Classification in Multi-core Environments](https://www.csie.ntu.edu.tw/~cjlin/papers/multicore_cddual.pdf) [[supplement](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/multicore_cddual_supplement.pdf), [code](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/exp-code.tar.gz). Implementation available in [Multi-core LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/).]  
  **Wei-Lin Chiang**, Mu-Chu Lee, and Chih-Jen Lin.  
  *ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD), 2016* [*poster*](https://infwinston.github.io/files/kdd16/poster.pdf)   
- [Fast Matrix-vector Multiplications for Large-scale Logistic Regression on Shared-memory Systems](https://www.csie.ntu.edu.tw/~cjlin/papers/multicore_liblinear_icdm.pdf) [[supplement](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/supplement.pdf), [code](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/exp_code.zip). Implementation available in [Multi-core LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/).]  
  Mu-Chu Lee, **Wei-Lin Chiang**, and Chih-Jen Lin.  
  *IEEE International Conference on Data Mining (ICDM), 2015* [*slides*](https://infwinston.github.io/files/icdm15/slides.pdf)   
