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

* I am a PhD student at UC Berkeley [SkyLab](https://sky.cs.berkeley.edu/), working with Prof. [Ion Stoica](http://people.eecs.berkeley.edu/~istoica/).
* My research focuses on building evaluation systems for AI. I'm currently working on [Chatbot Arena](https://lmarena.ai/?about) project, a crowdsourced AI evaluation platform at [LMSYS.org](https://twitter.com/lmsysorg).
* Our work on [Chatbot Arena](https://arxiv.org/abs/2403.04132), [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/), and [FastChat](https://github.com/lm-sys/FastChat) has been recognized with an a16z Open Source AI Grant. Check out our blogs at [LMSYS.org](https://lmsys.org) or follow our updates on [X](https://x.com/lmsysorg).

## News

- [**2024.09**] Launched: [RedTeam Arena](https://x.com/lmsysorg/status/1832201335175049434)
- [**2024.08**] New [blog post](https://lmsys.org/blog/2024-08-28-style-control/): decoupling style and substance in Chatbot Arena
- [**2024.06**] Launched: [Multimodal Arena](https://lmsys.org/blog/2024-06-27-multimodal/) 
- [**2024.05**] We hosted a [Kaggle competition](https://www.kaggle.com/competitions/lmsys-chatbot-arena) for human preference prediction
- [**2024.04**] [Arena Hard](https://github.com/lm-sys/arena-hard-auto) and [BenchBuilder](https://arxiv.org/abs/2406.11939): a data curation pipeline for LLMs benchmarks
- [**2024.03**] Released: technical [report](https://arxiv.org/abs/2403.04132) on Chatbot Arena

## <a name="Projects"></a> Projects

- **Chatbot Arena**: A Crowdsourced AI Evaluation Platform   
  Our website has served millions of users, collecting over one million user votes for the [leaderboard](https://lmarena.ai/leaderboard); We are honored to be recognized by industry leaders and researchers including [Jeff Dean](https://x.com/JeffDean/status/1819121162578022849), [Andrej Karpathy](https://twitter.com/karpathy/status/1734687074350166089), and [Greg Brockman](https://twitter.com/gdb/status/1725595967045398920).  
  | [Paper](https://arxiv.org/abs/2403.04132) | [Blog](https://lmsys.org/blog/2023-05-03-arena/) | [Website](https://chat.lmsys.org) |
- **LLM Judge**: Automating LLM Evaluation   
  We are developing automated evaluation for LLMs, such as [MT-Bench](https://arxiv.org/abs/2306.05685) and [Arena-Hard](https://github.com/lm-sys/arena-hard-auto) benchmarks.  
  | [Paper](https://arxiv.org/abs/2306.05685) | [Code](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge) |  
- **FastChat**: Multi-Model Serving Framework    
  FastChat is an open-source system powering Chatbot Arena and has gained strong developer community (over 30K [GitHub](https://github.com/lm-sys/FastChat) stars and 200+ contributors) 
- **Vicuna**: high-quality LLM chatbot   
  Vicuna has been downloaded over 8 million times with 1000+ citations.    
  | [Blog](https://lmsys.org/blog/2023-03-30-vicuna/) | [Weights](https://github.com/lm-sys/FastChat#vicuna-weights) |
- **SkyPilot**: An Intercloud System for AI and Batch Jobs   
  | [GitHub](https://github.com/skypilot-org/skypilot) | [Paper](https://www.usenix.org/conference/nsdi23/presentation/yang-zongheng) |
- **Cluster-GCN**: Scalable Training for Large GNNs   
  Widely integrated into platforms like [DGL](https://docs.dgl.ai/en/0.8.x/generated/dgl.dataloading.ClusterGCNSampler.html), [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.conv.ClusterGCNConv.html)    
  | [GitHub](https://github.com/google-research/google-research/tree/master/cluster_gcn) | [Paper](https://arxiv.org/abs/1905.07953) |

## Work Experience

- **Intern@Amazon**, *Seattle* (May. 2021 - Aug. 2021)  
  Contrastive learning for information extraction on semi-structure webpages
- **Intern@Google Research**, *Mountain View* (Dec. 2018 - Mar. 2019)  
  Developed algorithms for training large and deep GCN models.  
  [Cluster-GCN paper](https://arxiv.org/abs/1905.07953), [code](https://github.com/google-research/google-research/tree/master/cluster_gcn)
- **Intern@Alibaba Group**, *Hangzhou* (July 2017 - Sept. 2017)  
  Distributed ML algorithms on Alibaba’s parameter server ([KunPeng](https://www.kdd.org/kdd2017/papers/view/kunpeng-parameter-server-based-distributed-learning-systems-and-its-applica))
- **Intern@Microsoft Research Asia**, *Beijing* (Dec. 2016 - Feb. 2017)  
  Distributed training for deep learning frameworks
- **Intern@Microsoft**, *Redmond* (July 2016 - Oct. 2016)  
  Large-scale ML algorithms on Microsoft’s distributed platform ([REEF](https://reef.apache.org/))

## Publications (full list on [Google Scholar](https://scholar.google.com/citations?user=87nZphcAAAAJ&hl=en))

1. [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132)  
  **Wei-Lin Chiang\***, Lianmin Zheng\*, Sheng Ying, Anastasios Nikolas Angelopoulos, Tianle Li, Dacheng Li, Hao Zhang, Banghua Zhu, Michael Jordan, Joseph E. Gonzalez, Ion Stoica  (\*equal contribution)  
  arXiv preprint
1. [LMSYS-Chat-1M: A Large-Scale Real-World LLM Conversation Dataset](https://arxiv.org/abs/2309.11998)  
  Lianmin Zheng\*, **Wei-Lin Chiang\***, Ying Sheng, Tianle Li, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zhuohan Li, Zi Lin, Eric P. Xing, Joseph E. Gonzalez, Ion Stoica, Hao Zhang  (\*equal contribution)  
  ICLR 2024
3. [Llm-assisted code cleaning for training accurate code generators](https://arxiv.org/abs/2311.14904)  
  Naman Jain, Tianjun Zhang, **Wei-Lin Chiang**, Joseph E. Gonzalez, Koushik Sen, Ion Stoica  
  *ICLR 2024*
4. [Rethinking benchmark and contamination for language models with rephrased samples](https://arxiv.org/abs/2311.04850)
  Shuo Yang\*, **Wei-Lin Chiang\***, Lianmin Zheng\*, Joseph E. Gonzalez, Ion Stoica  (\*equal contribution)  
  arXiv preprint
5. [Judging LLM-as-a-judge with MT-Bench and Chatbot Arena](https://arxiv.org/abs/2306.05685)   
  Lianmin Zheng\*, **Wei-Lin Chiang\***, Sheng Ying\*, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zi Lin, Zhouhan Li, Dacheng Li, Eric Xing, Hao Zhang, Joseph Gonzalez, Ion Stoica (\*equal contribution)  
  NeurIPS 2023 Dataset and Benchmarks Track  
6. [Vicuna: An Open-Source Chatbot Impressing GPT-4 with 90%\* ChatGPT Quality](https://lmsys.org/blog/2023-03-30-vicuna/)  
  **Wei-Lin Chiang**, Zhuohan Li, Zi Lin, Ying Sheng, Zhanghao Wu, Hao Zhang, Lianmin Zheng, Siyuan Zhuang, Yonghao Zhuang, Joseph Gonzalez, Ion Stoica, Eric Xing (alphabetical order)  
  Blogpost [model weights](https://github.com/lm-sys/FastChat#vicuna-weights)
7. [Can’t Be Late: Optimizing Spot Instance Savings under Deadlines](https://www.usenix.org/system/files/nsdi24-wu-zhanghao.pdf)   
  Zhanghao Wu, **Wei-Lin Chiang**, Zongheng Yang, Eric Friedman, Scott Shenker, Ion Stoica.  
  *NSDI 2024* (**Outstanding Paper Award**)
8. [SkyPilot: An Intercloud Broker for Sky Computing](https://www.usenix.org/conference/nsdi23/presentation/yang-zongheng)   
  Zongheng Yang, Zhanghao Wu, Michael Luo, **Wei-Lin Chiang**, Romil Bhardwaj, Woosuk Kwon, Siyuan Zhuang, Frank Sifei Luan, Gautam Mittal, Scott Shenker, Ion Stoica  
  *USENIX NSDI 2023*
9. [Balsa: Learning a Query Optimizer Without Expert Demonstrations](https://dl.acm.org/doi/10.1145/3514221.3517885)  
  Zongheng Yang, **Wei-Lin Chiang<sup>+</sup>**, Sifei Luan<sup>+</sup>, Gautam Mittal, Michael Luo, Ion Stoica. (+ equal contribution)  
  *ACM SIGMOD 2022*
10. [Manifold Identification for Ultimately Communication-Efficient Distributed Optimization](http://www.optimization-online.org/DB_HTML/2020/06/7833.html)  
  Yu-Sheng Li, **Wei-Lin Chiang**, and Ching-pei Lee.  
  *International Conference on Machine Learning (ICML), 2020*
11. [Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks](https://arxiv.org/abs/1905.07953) [[code](https://github.com/google-research/google-research/tree/master/cluster_gcn), [dataset (Amazon2M)](http://web.cs.ucla.edu/~chohsieh/data/Amazon2M.tar.gz)]  
  **Wei-Lin Chiang**, Xuanqing Liu, Si Si, Yang Li, Samy Bengio, and Cho-Jui Hsieh.  
  *ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD), 2019 (**Oral**)* [*slides*](https://infwinston.github.io/files/kdd19/slides.pdf), [*poster*](https://infwinston.github.io/files/kdd19/poster.pdf)  
12. [Preconditioned Conjugate Gradient Methods in Truncated Newton Frameworks for Large-scale Linear Classification](http://proceedings.mlr.press/v95/hsia18a.html) [[supplement & code](https://www.csie.ntu.edu.tw/~cjlin/papers/tron_pcg/). Implementation available in [LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/liblinear/) after version 2.20.]  
  Chih-Yang Hsia, **Wei-Lin Chiang**, and Chih-Jen Lin.  
  *Asian Conference on Machine Learning (ACML), 2018 (**Best paper award**)* [*slides*](https://infwinston.github.io/files/acml18/slides.pdf), [*poster*](https://infwinston.github.io/files/acml18/poster.pdf)    
13. [Limited-memory Common-directions Method for Distributed L1-regularized Linear Classification](https://www.csie.ntu.edu.tw/~cjlin/papers/l-commdir-l1/OWL-commdir.pdf) [[supplement & code](https://www.csie.ntu.edu.tw/~cjlin/papers/l-commdir-l1/). Implementation available in [Distributed LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/distributed-liblinear/).]  
  **Wei-Lin Chiang**, Yu-Sheng Li, Ching-pei Lee, and Chih-Jen Lin.  
  *SIAM International Conference on Data Mining (SDM), 2018* [*slides*](https://infwinston.github.io/files/sdm18/slides.pdf), [*poster*](https://infwinston.github.io/files/sdm18/poster.pdf)   
14. [Parallel Dual Coordinate Descent Method for Large-scale Linear Classification in Multi-core Environments](https://www.csie.ntu.edu.tw/~cjlin/papers/multicore_cddual.pdf) [[supplement](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/multicore_cddual_supplement.pdf), [code](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/exp-code.tar.gz). Implementation available in [Multi-core LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/).]  
  **Wei-Lin Chiang**, Mu-Chu Lee, and Chih-Jen Lin.  
  *ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD), 2016* [*poster*](https://infwinston.github.io/files/kdd16/poster.pdf)   
15. [Fast Matrix-vector Multiplications for Large-scale Logistic Regression on Shared-memory Systems](https://www.csie.ntu.edu.tw/~cjlin/papers/multicore_liblinear_icdm.pdf) [[supplement](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/supplement.pdf), [code](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/exp_code.zip). Implementation available in [Multi-core LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/).]  
  Mu-Chu Lee, **Wei-Lin Chiang**, and Chih-Jen Lin.  
  *IEEE International Conference on Data Mining (ICDM), 2015* [*slides*](https://infwinston.github.io/files/icdm15/slides.pdf)   
