---
permalink: /
title: "[中文](http://jasonyanglu.github.io/about_cn)"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm now an Assistant Professor and PhD supervisor in Department of Computer Science and Technology, School of Informatics, Xiamen University. I'm also the joint supervisor at the Institute of Artificial Intelligence, Xiamen University. I received my PhD degree in computer science from Hong Kong Baptist University in 2019, supervised by [Prof. Yiu-ming Cheung](http://www.comp.hkbu.edu.hk/~ymc/), and received my bachelor and master degrees in software engineering from University of Macau in 2012 and 2014, supervised by [Prof. Yuan Yan Tang](https://www.fst.um.edu.mo/personal/yytang/). I was a research intern at Tencent in 2018. I have published over 40 top-tier papers, many of which have been featured in top-tier machine learning journals (JCR Q1) such as IEEE TNNLS and IEEE TCYB, as well as top-tier AI and computer vision conferences (CCF-A class) like CVPR, NeurIPS, ICCV, AAAI, IJCAI, and MM. I have led several projects, including the Key Project, General Project and Youth Project of the National Natural Science Foundation of China, the Fujian Provincial Excellent Youth Project, the Major Project of the Fujian New Think Tank, the General Project of the Fujian Natural Science Foundation, and open projects at the Zhejiang Lab. I serve as a member of the Machine Vision Committee, the Secretary-General of the Xiamen Member Activity Center of the China Society of Image and Graphics, and IEEE senior member. I also serve as the Associate Editor of the international journal IEEE Transactions on Emerging Topics in Computational Intelligence. I was honored as the "Xiaomi Young Scholar" in 2023, and obtained the best paper award on DOCS 2024. My research interests include deep learning and computer vision. My research direction is trustworthy deep learning, including long-tail learning, federated learning, label-noise learning and continual learning.

For undergraduate students, please check [本科招生简章](http://jasonyanglu.github.io/undergraduate). For postgraduate students, please check [硕士招生简章](http://jasonyanglu.github.io/postgraduate).

<span style="color:red">**There is still a few postgraduate quota in Fall 2027. Please contact me ASAP. **</span>


## Recent News
* **July 5 2025**: One paper about semi-supervised fine-tuning is accepted by ACMMM . Congrats to Hezhao!
* **June 26 2025**: Two ICCV papers are accepted! Congrats to Shanshan and Chikai!
* **Feb 27 2025**: One paper about semi-supervised federated learning is accepted by CVPR . Congrats to Yijie!
* **Feb 2 2025**: Upgrade to IEEE Senior Member!
* **Dec 10 2024**: Two AAAI papers are accepted!
* **Oct 10 2024**: Two IJCV papers are accepted!
* **Oct 10 2024**: Win the second prize in the MICCAI long-tail chest x-ray challenge. Congrats to Ruichi!
* **Sep 26 2024**: Two NeurIPS papers are accepted!
* **Sep 10 2024**: One provincial excellent youth project is granted.
* **Aug 17 2024**: Our paper about federated clustering wins the best paper award on DOCS 2024!
* **July 16 2024**: Three ACMMM papers are accepted!
* **Apr 17 2024**: One paper about long-tailed continual learning is accepted by IJCAI . Congrats to Chenxing!
* **Dec 27 2023**: Receive Xiaomi Youth Scholar Award.
* **Dec 9 2023**: Three AAAI papers are accepted!
* **Aug 24 2023**: One NSFC general project is granted.
* **July 14 2023**: One paper about long-tailed label-noise learning is accepted by ICCV . Congrats to Yiliang!
* **Mar 28 2023**: Congrats to Xinyi for receiving the PhD offer from UCL supported by UCL-CSC scholarship!
* **Feb 28 2023**: One paper about long-tailed learning is accepted by CVPR. Congrats to Yan!

* [...](http://jasonyanglu.github.io/archieved_news)

## Research Interests

### Deep Learning with Incomplete Labels

<div style="display: flex; align-items: flex-start;">  
    <div style="flex: 1;">         
        <p>             
    Machine learning with incomplete labels addresses effective model training in the presence of significant label deficiencies, such as imbalanced label distribution or noisy labels. The goal is to achieve accurate predictions despite low data quality. We enhance model performance on incomplete labeled data by introducing more effective label processing and integration strategies.     
        </p>     
    </div>     
    <img src="./images/machine_learning_with_incomplete_labels.jpg" style="width: 40%; margin-left: 10px;">
</div>


- Long-tailed Visual Recognition ([CVPR'23](https://openaccess.thecvf.com/content/CVPR2023/html/Jin_Long-Tailed_Visual_Recognition_via_Self-Heterogeneous_Integration_With_Knowledge_Excavation_CVPR_2023_paper.html), [CVPR'22](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Long-Tailed_Visual_Recognition_via_Gaussian_Clouded_Logit_Adjustment_CVPR_2022_paper.html), [IJCAI'22](https://www.ijcai.org/proceedings/2022/308), [AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/29262), [AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/29416), [NeurIPS'24](https://arxiv.org/abs/2410.21042))
- Imbalance Learning ([IJCAI'24](https://arxiv.org/abs/2404.14721), [IJCAI'17](https://www.ijcai.org/Proceedings/2017/0333.pdf), [TNNLS'20](https://ieeexplore.ieee.org/document/8890005), [TNNLS'20](https://ieeexplore.ieee.org/document/8924892), [TCYB'21](https://ieeexplore.ieee.org/document/8725928), [TNNLS'25](https://ieeexplore.ieee.org/document/11027917))
- Label-Noise Learning ([ICCV'23](https://openaccess.thecvf.com/content/ICCV2023/html/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.html), [AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/29329), [TCYB'23](https://ieeexplore.ieee.org/document/9780248), [ECML-PKDD'21](https://link.springer.com/chapter/10.1007/978-3-030-86523-8_44))

### Trustworthy Federated Learning

<div style="display: flex; align-items: flex-start;">   
    <div style="flex: 1;">         
        <p>             
    Trustworthy federated learning aims to perform model training in a distributed data environment, ensuring data privacy and security while maintaining high model performance. It also explores personalization and fairness within the federated learning framework. Our work focuses on data heterogeneity, long-tailed distribution, missing labels, and noise issues, improving the robustness and performance of models in heterogeneous data and noisy environments.
        </p>     
    </div>     
    <img src="./images/trustworthy_federated_learning.jpg" style="width: 40%; margin-left: 20px;  margin-left: 10px;"> 
</div>


- Long-tailed Federated Learning ([IJCAI'22](https://www.ijcai.org/proceedings/2022/308), [AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/29416), [ICCV'25](https://arxiv.org/abs/2503.06916), [ICME'22](https://arxiv.org/abs/2205.00172), [ICASSP'23](https://arxiv.org/abs/2303.15168))
- Extreme Label-Noise in Federated Learning ([AAAI'24](https://ojs.aaai.org/index.php/AAAI/article/view/29329))
- Semi-supervised Federated Learning ([CVPR'25](https://arxiv.org/abs/2503.13227), [Arxiv'23](https://arxiv.org/abs/2303.02445))

### Continual Learning and Prompt Learning

<div style="display: flex; align-items: flex-start;"> 
    <div style="flex: 1;">         
        <p>             
    In real-world applications, the data environment is dynamically changing, and models need to continuously learn new knowledge while retaining existing knowledge without forgetting. Our research involves task-imbalanced continual learning, concept drift handling in incremental learning, and domain generalization, aiming to enhance model stability and adaptability in dynamic and imbalanced data environments.
        </p>     
    </div>     
    <img src="./images/continual_learning_and_prompt_learning.jpg" style="width: 40%; margin-left: 10px;"> 
</div>

- Task-Imbalanced Continual Learning  ([IJCAI'24](https://arxiv.org/abs/2404.14721))
- Incremental Learning with Concept Drift ([IJCAI'17](https://www.ijcai.org/Proceedings/2017/0333.pdf), [TNNLS'20](https://ieeexplore.ieee.org/document/8924892))
- Vision-Language Prompt Learning ([ICCV'25](https://arxiv.org/abs/2503.06901), [MM'25](https://arxiv.org/abs/2504.09828), [Arxiv'24](https://arxiv.org/abs/2404.18758))



## Supervised Students

### PhD

* Jiacheng Yang (2025-): Long-tail learning

### Master

* Pinxin Qian (2020-2023, Employed in Alibaba): Federated learning
* [Xinyi Shang](https://shangxinyi.github.io/) (2020-2023, Pursuing PhD at UCL): Federated learning
* Yiliang Zhang (2021-2024, Employed in Alibaba): Label-noise learning
* Yan Jin (2021-2024, Pursuing PhD at BUAA): Long-tail learning
* Xiaolin Huang (2021-2024, Employed in JD): Semi-supervised learning
* Fengling Lv (2021-2024, Employed in Xiaomi): Federated learning
* Chengbin Zheng (2021-2024, Employed in CATL): Graph neural networks
* Chenxing Hong (2022-2025, Employed in Tencent): Continual learning
* Lin Chen (2022-2025, Employed in Baidu): Federated learning
* Liyuan Wang (2022-2025, Employed in Industrial Bank): Long-tail learning
* Yijie Liu (2023-): Federated learning
* Shanshan Yan (2023-): Federated learning
* Yizhou Chen (2023-): Anomaly detection
* Hezhao Liu (2023-): Semi-supervised learning
* Shu Chen (2023-): Label-noise learning
* Zenghui Huang (2024-): Long-tail learning
* Ruichi Zhang (2024-): Long-tail learning
* Junpeng Chen (2024-): Anomaly detection
* Shihao Hou (2024-): Federated learning
* Chikai Shang (2025-): Long-tail learning
* Wenxin Nian (2025-): Anomaly detection
* Zijian Kang (2025-): Continual learning
* Zhiheng Yang (2025-): Federated learning

