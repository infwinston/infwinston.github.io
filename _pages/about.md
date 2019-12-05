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

* I am a Masters student in the Department of Computer Science at National Taiwan University, advised by Prof. [Chih-Jen Lin](https://www.csie.ntu.edu.tw/~cjlin/).
* My research interests include optimization for machine learning, data mining, scalable ML algorithms and its system design.
* I enjoy developing ML softwares and I am always happy to learn how it is being used! Email me if you have questions or find [our softwares](#softwares) useful.
* More details can be found in my [CV](https://infwinston.github.io/files/docs/CV.pdf).

## Work Experience

- **Intern@Google Research**, *Mountain View* (Dec. 2018 - Mar. 2019)  
  Developing efficient algorithms for training large and deep GCN models
- **Intern@Alibaba Group**, *Hangzhou* (July 2017 - Sept. 2017)  
  Developing distributed ML algorithms on Alibaba’s parameter server ([KunPeng](https://www.kdd.org/kdd2017/papers/view/kunpeng-parameter-server-based-distributed-learning-systems-and-its-applica))
- **Intern@Microsoft Research Asia**, *Beijing* (Dec. 2016 - Feb. 2017)  
  Investigating distributed training methods on deep learning frameworks
- **Intern@Microsoft**, *Redmond* (July 2016 - Oct. 2016)  
  Developing large-scale ML algorithms on Microsoft’s distributed platform ([REEF](https://reef.apache.org/))

## Publications ([Google Scholar Profile](https://scholar.google.com/citations?user=87nZphcAAAAJ&hl=en))

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

## Softwares

- [Cluster-GCN](https://github.com/google-research/google-research/tree/master/cluster_gcn)  
  TensorFlow implementation of an efficient algorithm for large (million-scale) and deep GCN  
  Achieved state-of-the-art performance on some public datasets (e.g., PPI, Reddit)
- [Distributed LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/distributed-liblinear/)  
  Distributed extension of a widely-used linear classification package, [LIBLINEAR](https://github.com/cjlin1/liblinear)  
  Developed L1-regularized LR solver for solving large (billion-scale) tasks
- [Multi-core LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/)  
  Multi-core extension of a widely-used linear classification package, [LIBLINEAR](https://github.com/cjlin1/liblinear)  
  Developed efficient parallel algorithms for primal and dual solvers
