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

* I am a CS PhD student at UC Berkeley [SkyLab](https://sky.cs.berkeley.edu/), working with Prof. [Ion Stoica](http://people.eecs.berkeley.edu/~istoica/).
* My research focus on building evaluation system for large language models. I'm currently co-leading the [Chatbot Arena](https://chat.lmsys.org/?about) project, a live LLM leaderboard at [LMSYS.org](https://twitter.com/lmsysorg).
* I am honored to receive the a16z [Open Source AI Grant](https://a16z.com/announcing-our-latest-open-source-ai-grants/) for our works in [Chatbot Arena](https://arxiv.org/abs/2403.04132), [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/), and [FastChat](https://github.com/lm-sys/FastChat).
* Check out our works at [LMSYS.org](https://lmsys.org) in advancing open LLM research! Or find my random thoughts on [X](https://twitter.com/infwinston) :)

## News

- [**2024.05**] Coming ICLR trip to Vienna to present our work [LMSYS-Chat-1M](https://arxiv.org/abs/2309.11998). Hit me up if you're around!
- [**2024.04**] New blog: [Arena Hard](https://lmsys.org/blog/2024-04-19-arena-hard/) -- a pipeline to produce LLMs benchmark from live data.
- [**2024.04**] Chatbot Arena ([chat.lmsys.org](chat.lmsys.org)) has served over 1 million users and collected over 700,000 user votes.
- [**2024.03**] We've published the technical [report](https://arxiv.org/abs/2403.04132) of Chatbot Arena.

## <a name="Projects"></a> Projects


- **Chatbot Arena**: a live platform for evaluating LLMs by human preference  
  Our platform has served millions of users and gathered over 700K user votes; Our LLM [leaderboard](https://chat.lmsys.org/?leaderboard) has been widely cited by AI leaders and researchers including [Jeff Dean](https://twitter.com/JeffDean/status/1750930658900517157), [Andrej Karpathy](https://twitter.com/karpathy/status/1734687074350166089), [Greg Brockman](https://twitter.com/gdb/status/1725595967045398920), and Stanford HAI [annual report](https://aiindex.stanford.edu/wp-content/uploads/2024/04/HAI_AI-Index-Report-2024.pdf)  
  | [Paper](https://arxiv.org/abs/2403.04132) | [Blog](https://lmsys.org/blog/2023-05-03-arena/) | [Website](https://chat.lmsys.org) |  
- **FastChat**: a multi-model serving system for large language models  
  FastChat is an open-source system powering Chatbot Arena and has gained strong developer community (over 30K [GitHub](https://github.com/lm-sys/FastChat) stars and 200+ contributors) 
- **LLM Judge**: model-based evaluation for LLM chatbots  
  Our LLM benchmark [MT-Bench](https://huggingface.co/spaces/lmsys/mt-bench) has been widely adopted by leading model developers (e.g., [Mistral](https://mistral.ai/news/mixtral-of-experts/), [HuggingFace](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta), [Databricks](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)) and recently upgraded to [Arena Hard](https://lmsys.org/blog/2024-04-19-arena-hard/)  
  | [Paper](https://arxiv.org/abs/2306.05685) | [Code](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge) |  
- **Vicuna**: one of the first open-weight models demonstrating multi-turn ChatGPT capability  
  The model has received over 5 million downloads and 1000+ citations   
  | [Blog](https://lmsys.org/blog/2023-03-30-vicuna/) | [Weights](https://github.com/lm-sys/FastChat#vicuna-weights) |
- **SkyPilot**: An intercloud system for running AI and Batch jobs on any cloud  
  Support 10+ major clouds; adopted by leading AI startups such as [Mistral](https://docs.mistral.ai/deployment/self-deployment/skypilot/), [Covariant](https://blog.skypilot.co/covariant/)   
  | [GitHub](https://github.com/skypilot-org/skypilot) | [Paper](https://www.usenix.org/conference/nsdi23/presentation/yang-zongheng) |
- **Cluster-GCN**: one of the first scalable methods for training large and deep GNNs  
  Our method has been widely adopted in academia and industry (see [DGL](https://docs.dgl.ai/en/0.8.x/generated/dgl.dataloading.ClusterGCNSampler.html), [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.conv.ClusterGCNConv.html) integration, [Stanford CS224W](https://web.stanford.edu/class/cs224w/slides/15-scalable.pdf))  
  | [GitHub](https://github.com/google-research/google-research/tree/master/cluster_gcn) | [Paper](https://arxiv.org/abs/1905.07953) |

## Work Experience

- **Intern@Amazon**, *Seattle* (May. 2021 - Aug. 2021)  
  Contrastive learning for information extraction on semi-structure webpages
- **Intern@Google Research**, *Mountain View* (Dec. 2018 - Mar. 2019)  
  Efficient algorithms for training large and deep GCN models.  
  [Cluster-GCN paper](https://arxiv.org/abs/1905.07953), [code](https://github.com/google-research/google-research/tree/master/cluster_gcn)
- **Intern@Alibaba Group**, *Hangzhou* (July 2017 - Sept. 2017)  
  Distributed ML algorithms on Alibaba’s parameter server ([KunPeng](https://www.kdd.org/kdd2017/papers/view/kunpeng-parameter-server-based-distributed-learning-systems-and-its-applica))
- **Intern@Microsoft Research Asia**, *Beijing* (Dec. 2016 - Feb. 2017)  
  Distributed training for deep learning frameworks
- **Intern@Microsoft**, *Redmond* (July 2016 - Oct. 2016)  
  Large-scale ML algorithms on Microsoft’s distributed platform ([REEF](https://reef.apache.org/))

## Publications (full list on [Google Scholar](https://scholar.google.com/citations?user=87nZphcAAAAJ&hl=en))

1. [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132)  
  **Wei-Lin Chiang**<sup>*</sup>, Lianmin Zheng<sup>*</sup>, Sheng Ying, Anastasios Nikolas Angelopoulos, Tianle Li, Dacheng Li, Hao Zhang, Banghua Zhu, Michael Jordan, Joseph E. Gonzalez, Ion Stoica  (\*equal contribution)  
  arXiv preprint
1. [LMSYS-Chat-1M: A Large-Scale Real-World LLM Conversation Dataset](https://arxiv.org/abs/2309.11998)  
  Lianmin Zheng<sup>*</sup>, **Wei-Lin Chiang**<sup>*</sup>, Ying Sheng, Tianle Li, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zhuohan Li, Zi Lin, Eric P. Xing, Joseph E. Gonzalez, Ion Stoica, Hao Zhang  (\*equal contribution)  
  ICLR 2024
3. [Llm-assisted code cleaning for training accurate code generators](https://arxiv.org/abs/2311.14904)  
  Naman Jain, Tianjun Zhang, **Wei-Lin Chiang**, Joseph E. Gonzalez, Koushik Sen, Ion Stoica  
  *ICLR 2024*
4. [Rethinking benchmark and contamination for language models with rephrased samples](https://arxiv.org/abs/2311.04850)
  Shuo Yang<sup>*</sup>, **Wei-Lin Chiang<sup>*</sup>**, Lianmin Zheng<sup>*</sup>, Joseph E. Gonzalez, Ion Stoica  (\*equal contribution)  
  arXiv preprint
5. [Judging LLM-as-a-judge with MT-Bench and Chatbot Arena](https://arxiv.org/abs/2306.05685)   
  Lianmin Zheng<sup>*</sup>, **Wei-Lin Chiang**<sup>*</sup>, Sheng Ying<sup>*</sup>, Siyuan Zhuang, Zhanghao Wu, Yonghao Zhuang, Zi Lin, Zhouhan Li, Dacheng Li, Eric Xing, Hao Zhang, Joseph Gonzalez, Ion Stoica (\*equal contribution)  
  NeurIPS 2023 Dataset and Benchmarks Track  
6. [Vicuna: An Open-Source Chatbot Impressing GPT-4 with 90%<sup>*</sup> ChatGPT Quality](https://lmsys.org/blog/2023-03-30-vicuna/)  
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
