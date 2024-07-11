---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?hl=zh-CN&user=6lMg5eoAAAAJ)

## Research Outlines
My main research interests lie in *__i) optimization, generalization, and personalization of deep learning models__*, especially under *distributed/federated/collaborative* setups, which are generally empowered by deep learning phenomena and mechanistic interpretability;  *__ii) trustworthy model manipulation for foundation models__*: understanding and improving foundation models (e.g., large language model, vision transformer, and diffusion transformer) from the *__model parameter perspective__*, i.e., model *fusion, editing, pruning, stitching, growth, unlearning, and generation*.

* **Optimization, Generalization, and Personalization of Deep Learning under Collaboration**
  * Federated deep Learning.
    * *Generalization and optimization*: improving generalization and gaining insights in training dynamics \[9, 15\].
    * *Personalization*: general personalization \[8\], personalization under clustered heterogeneity \[4\], personalization under feature skew \[11\].
    * *Robustness*: joint problem of noisy labels and non-IID data \[5\].
    * *Federated large language model* \[12, 15\].
  * Edge-cloud collaborative & domain-transferred machine learning.
    *  *Edge-cloud collaboration in recommender systems* \[6\].
    *  *Transfer learning of regression models* \[2\].
    *  *Domain adaptation* \[7\].
  * Train-once-for-all personalization \[17\].
  * Socio-technical issues brought by big data and machine learning.
    *  *Data collaboration and open science* \[3\].
    *  *Big data driven medical reform studies* \[1\].

* **Model Manipulation for Foundation Models**
  * *Model fusion* and *linear mode connectivity* \[10\].
  * *Model editing* of large language models \[16\].
  * *Model generation*: text-to-model generative diffusion transformer \[17\].
  * *Model tailor*: mitigating catastrophic forgetting in multi-modal large language models \[14\].
  * *Neural-collapse-inspired representation learning*: i) federated learning \[8\]; ii) prompt tuning for CLIP \[13\].
    
--------
## Publications
\* indicates equal contributions, \# indicates corresponding author.

## 2024
- \[17\] Text-to-Model: Text-Conditioned Neural Network Diffusion for Train-Once-for-All Personalization  
   **Zexi Li\***, Lingzhi Gao\*, Chao Wu\#  
  _**preprint**_. \[[arxiv](https://arxiv.org/pdf/2405.14132)\]
- \[16\] WISE: Rethinking the Knowledge Memory for Lifelong Model Editing of Large Language Models  
   Peng Wang\*, **Zexi Li\***, Ningyu Zhang\#, Ziwen Xu, Yunzhi Yao, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen\#  
  _**preprint**_. \[[arxiv](https://arxiv.org/pdf/2405.14768)\]
- \[15\] Improving Group Connectivity for Generalization of Federated Deep Learning  
  **Zexi Li\***, Jie Lin\*, Zhiqi Li\*, Didi Zhu, Tao Lin\#, Chao Wu\#  
  _**preprint**_. \[[arxiv](https://arxiv.org/pdf/2402.18949.pdf)\]
- \[14\] Model Tailor: Mitigating Catastrophic Forgetting in Multi-modal Large Language Models  
  Didi Zhu, Zhongyi Sun, **Zexi Li**, Tao Shen, Ke Yan, Shouhong Ding, Kun Kuang\#, Chao Wu\#  
  _**International Conference on Machine Learning (ICML) 2024**_. (CCF A, Top Conference in Machine Learning) \[[arxiv](https://arxiv.org/pdf/2402.12048.pdf)\]
- \[13\] Neural Collapse Anchored Prompt Tuning for Generalizable Vision-Language Models  
  Didi Zhu, **Zexi Li**, Min Zhang, Junkun Yuan, yunfeng shao, Yinchuan Li, Jiashuo Liu, Kun Kuang, Chao Wu\#  
  _**ACM KDD 2024**_. (CCF A, Top Conference in Data Mining) \[[arxiv](https://arxiv.org/pdf/2306.15955.pdf)\]
- \[12\] OpenFedLLM: Training Large Language Models on Decentralized Private Data via Federated Learning   
  Rui Ye, Wenhao Wang, Jingyi Chai, Dihan Li, **Zexi Li**, Yinda Xu, Yaxin Du, Yanfeng Wang, Siheng Chen  
  _**ACM KDD 2024**_. (CCF A, Top Conference in Data Mining) \[[arxiv](https://arxiv.org/pdf/2402.06954)\]


## 2023
<!--  
- \[13\] Towards Universal Personalization in Federated Learning via Collaborative Foundation Generative Models  
  Chenrui Wu\*, **Zexi Li\***, Fangxin Wang, Hongyang Chen, Jiajun Bu, and Haishuai Wang\*  
  _**preprint**_. 
- \[12\] Unveiling Linear Mode Connectivity of Re-basin from Neuron Distribution Perspective  
  Zhiqi Li\*, **Zexi Li\***, Mian Wu\*, Cheng Wan, and Chao Wu\#  
  _**preprint**_.  -->
- \[11\] FediOS: Decoupling Orthogonal Subspaces for Personalization in Feature-skew Federated Learning  
  Lingzhi Gao\*, **Zexi Li\***, Yang Lu, and Chao Wu\#  
  _**preprint**_. \[[arxiv](https://arxiv.org/pdf/2311.18559.pdf)\]
- \[10\] Training-time Neuron Alignment through Permutation Subspace for Improving Linear Mode Connectivity and Model Fusion  
  **Zexi Li**, Zhiqi Li, Jie Lin, Tao Shen, Tao Lin\#, and Chao Wu\#  
  _**preprint**_. \[[arxiv](https://arxiv.org/abs/2402.01342)\]
- \[9\] Revisiting Weighted Aggregation in Federated Learning with Neural Networks  
  **Zexi Li**, Tao Lin\#, Xinyi Shang, and Chao Wu\#  
  _**International Conference on Machine Learning (ICML) 2023**_. (CCF A, Top Conference in Machine Learning) \[[paper](https://proceedings.mlr.press/v202/li23s.html)\]\[[github](https://github.com/ZexiLee/ICML-2023-FedLAW)\]\[[arxiv](https://arxiv.org/abs/2302.10911)\]
- \[8\] No Fear of Classifier Biases: Neural Collapse Inspired Federated Learning with Synthetic and Fixed Classifier  
  **Zexi Li**, Xinyi Shang, Rui He, Tao Lin\#, and Chao Wu\#  
  _**International Conference on Computer Vision (ICCV) 2023**_. (CCF A, Top Conference in Computer Vision) \[[paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_No_Fear_of_Classifier_Biases_Neural_Collapse_Inspired_Federated_Learning_ICCV_2023_paper.pdf)\]\[[arxiv](https://arxiv.org/abs/2303.10058)\]
- \[7\] Universal Domain Adaptation via Compressive Attention Matching  
  Didi Zhu\*, Yinchuan Li\*, Junkun Yuan, **Zexi Li**, Kun Kuang\#, Chao Wu\#  
  _**International Conference on Computer Vision (ICCV) 2023**_. (CCF A, Top Conference in Computer Vision) \[[paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhu_Universal_Domain_Adaptation_via_Compressive_Attention_Matching_ICCV_2023_paper.pdf)\]
- \[6\] Edge-cloud Collaborative Learning with Federated and Centralized Features  
  **Zexi Li\***, Qunwei Li\*, Yi Zhou, Wenliang Zhong\#, Guannan Zhang, and Chao Wu\#  
  _**International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR) 2023**_. (CCF A, Top Conference in Data Mining and Information Retrieval) \[[paper](https://dl.acm.org/doi/abs/10.1145/3539618.3591976)\]\[[arxiv](https://arxiv.org/abs/2304.05871)\]
- \[5\] Learning Cautiously in Federated Learning with Noisy and Heterogeneous Clients  
  Chenrui Wu\*, **Zexi Li**\*, Fangxin Wang\#, and Chao Wu\#  
  _**(Oral) IEEE International Conference on Multimedia and Expo (ICME) 2023**_. (CCF B, Top Conference in Multimedia) \[[paper](https://www.computer.org/csdl/proceedings-article/icme/2023/689100a660/1PTNcsYjSRG)\]\[[arxiv](https://arxiv.org/abs/2304.02892)\]
--

  
## 2022
- \[4\] Towards Effective Clustered Federated Learning: A Peer-to-peer Framework with Adaptive Neighbor Matching  
  **Zexi Li**, Jiaxun Lu, Shuang Luo, Didi Zhu, Yunfeng Shao, Yinchuan Li, Zhimeng Zhang, Yongheng Wang\#, and Chao Wu\#   
  - Long version in _**IEEE Transactions on Big Data**_. (JCR Q1, IF: 7.2) \[[paper](https://www.computer.org/csdl/journal/bd/5555/01/09954190/1Inoq0EldXG)\]\[[arxiv](https://arxiv.org/pdf/2203.12285.pdf)\]
  - Short version in _**MLSys2022 Workshop**_. \[[poster](https://crossfl2022.github.io/abstracts/Abstract4.pdf)\]
- \[3\] Can We Share Models If Sharing Data Is Not an Option?  
  **Zexi Li**, Feng Mao\#, and Chao Wu\#  
  _**Patterns, Cell Press**._ (JCR Q1, IF: 6.5) \[[paper](https://www.cell.com/patterns/fulltext/S2666-3899(22)00228-8#%20)\]
  
## 2021
- \[2\] Boosting the generalization ability of Vis-NIR-spectroscopy-based regression models through dimension reduction and transfer learning  
  Xiaoli Li\*, **Zexi Li**\*, Xufeng Yang, and Yong He\#  
  _**Computers and Electronics in Agriculture**_. (JCR Q1, CAS Top, IF: 8.3) \[[paper](https://www.sciencedirect.com/science/article/pii/S0168169921001757)\] 
- \[1\] An early assessment of the County Medical Community reform in China: a case study of Zhejiang province  
  Chao Wu, Yixin Tu, **Zexi Li**, Jianxing Yu\#  
  _**Journal of Chinese Governance**_. (SSCI, JCR Q1, IF: 3.0) \[[paper](https://www.tandfonline.com/doi/abs/10.1080/23812346.2021.1978722)\]
