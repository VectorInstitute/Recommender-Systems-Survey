<h1 align="center">A Comprehensive Review of Recommender Systems:
Transitioning from Theory to Practice</h1>

Welcome to the official repository for the paper **"A Comprehensive Review of Recommender Systems: Transitioning from Theory to Practice"**.

This repository is dedicated to continuously exploring and disseminating knowledge on Recommender Systems. It aims to bridge theory and practice, offering valuable insights for both researchers and industry professionals.

![image](https://github.com/user-attachments/assets/3111db0f-1aa9-49f3-ad4e-68bc57668853)

## 📌 **Table of Contents**
1. [Introduction](#introduction)
2. [Key Contributions](#key-contributions)
3. [Paper Summary](#summary)
4. [News](#news)
5. [Highlighted Papers](#highlighted-papers)
6. [Challenges in Recommender Systems](#challenges-in-recommender-systems)
7. [Advanced Techniques](#advanced-techniques)
8. [Impact of the Research](#Impact-of-the-research)
9. [Limitations](#limitations)
10. [Future Directions](#future-directions)

## 🔍**Introduction**
This survey acts as a comprehensive benchmark and cookbook to determine where, when, and why specific recommender system methodologies from academia should be applied across various industry sectors. It covers advancements in recommender systems from 2017 to 2024, and includes 65 pages of in-depth analysis with over 500 references. The document features 11 comprehensive analysis tables and addresses 19 sets of recommender system techniques, ranging from traditional methods to advanced specialized AI techniques, across ten diverse sectors including e-commerce, healthcare, and finance.


## Key Contributions
1. Comprehensive review tracing the development of RS from 2017 to 2024.
2. Around 500+ high impact papers were reviewed. 
3. Thorough examination of different RS types, challenges, datasets, and metrics.
4. Emphasis on bridging theoretical advancements with real-world applications.
5. Highlights on emerging trends such as **Explainable AI**, **FATE (Fairness, Accountability, Transparency, Ethics)**, and **Large Language Models**.

## Summary
This paper presents a comprehensive exploration of the development of Recommender Systems (RS), beginning with traditional techniques such as content-based filtering, collaborative filtering, and hybrid approaches. While these traditional RS have been widely implemented, they encounter significant challenges in adapting to dynamic user preferences, providing real-time recommendations, and addressing issues such as the cold start problem and data privacy. To overcome these limitations, there is a clear need for more advanced methods, particularly those involving deep learning.

In response to these challenges, the paper transitions to discussing advanced methods, including four key deep learning models such as Autoencoders. These models have substantially improved the ability to personalize recommendations and capture complex user-item interactions, resulting in enhanced performance in sectors like e-commerce, news, and entertainment. The evolution of these models has further led to the development of even more sophisticated techniques, such as Graph Neural Networks (GNNs), which are capable of boosting both accuracy and diversity in recommendations. These advancements are explored in detail within the section on advanced modeling techniques.

Building on the discussion of deep learning, the paper delves into six advanced modeling techniques, including graph-based models, reinforcement learning, and large language models. Additionally, it examines six specialized RS areas, such as context-aware, review-based, and fairness-aware systems. These specialized RS are tailored to address unique user preferences and situations across various domains. Unlike general RS, these systems focus on specialized functions and targeted recommendations, utilizing advanced techniques to deliver context-aware, review-based, aspect-based, explainable, and fairness-focused recommendations.

The overarching goal of this survey is to bridge the gap between theoretical advancements and practical applications in RS. By addressing challenges across 10 diverse sectors, including e-commerce, healthcare, and finance, the paper emphasizes the importance of developing scalable, real-time, and trustworthy RS solutions. Furthermore, the survey highlights how these advancements are already being applied in industry settings to tackle domain-specific challenges. The insights provided are intended to guide industry professionals in optimizing RS deployment and to inspire future research, particularly in addressing the emerging technological and societal trends that will shape the future of Recommender Systems.

## News
Stay updated with the latest research and trends in RS:
- **August 2024**: Paper is under review at Elsevier Computer Science Review (IF = 13.3)!

## Highlighted Papers

#### Foundational Recommender Systems:

- [01/2013] **Probabilistic Models for Unified Collaborative
and Content-Based Recommendation in Sparse-Data Environments** *Alexandrin Popescul et. al. arXiv.* [[paper]](https://arxiv.org/abs/1301.2303)
- [01/2018] **Joint Deep Modeling of Users and Items Using Reviews for Recommendation** *Lei Zheng et. al arXiv* [[paper](https://arxiv.org/abs/1701.04783)]
- [02/2018] **Content-Based Citation Recommendation** *Chandra Bhagavatula et. al arXiv* [[paper](https://arxiv.org/abs/1802.08301)]
- [1999] **An algorithmic framework for performing collaborative filtering** *Jonathan L. Herlocker et. al SIGIR'99* [[paper](https://doi.org/10.1145/312624.312682)]
- [2001] **Item-based collaborative filtering recommendation algorithms** *Badrul Sarwar et. al KDD'99* [[paper](https://doi.org/10.1145/371920.372071)]
- [2012] **Factorization machines with libfm** *S Rendle TIST'12* [[paper](https://doi.org/10.1145/2168752.2168771)]
- [06/2016] **Wide & Deep Learning for Recommender Systems** *Heng-Tze Cheng et. al arXiv* [[paper](https://arxiv.org/abs/1606.07792)]
- [08/2017] **Neural Factorization Machines for Sparse Predictive Analytics** *Xiangnan He et. al arXiv* [[paper](https://arxiv.org/abs/1708.05027)]
- [03/2017] **DeepFM: A Factorization-Machine based Neural Network for CTR Prediction** *Huifeng Guo et. al arXiv* [[paper](https://arxiv.org/abs/1703.04247)]

#### Graph-based Recommender Systems:
  
- [07/2021] **Dynamic Graph Neural Networks for Sequential Recommendation** *Mengqi Zhang et al. arXiv.* [[paper](https://arxiv.org/abs/2104.07368)]
- [11/2019] **Graph Neural Networks for Social Recommendation** *Wenqi Fan et al. arXiv.* [[paper](https://arxiv.org/pdf/1902.07243)]
- [06/2019] **KGAT: Knowledge Graph Attention Network for Recommendation** *Xiang Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/1905.07854)]

#### Sequential and Session-based Recommender Systems: 
- [08/2023] **Knowledge Prompt-tuning for Sequential Recommendation** *Jianyang Zhai et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.08459)]
- [05/2023] **Frequency Enhanced Hybrid Attention Network for Sequential Recommendation** *Xinyu Du et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.09184)]
- [04/2022] **CORE: Simple and Effective Session-based Recommendation within Consistent Representation Space** *Yupeng Hou et al. arXiv.* [[paper](https://arxiv.org/pdf/2204.11067)]

#### Knowledge-based Recommender Systems: 
- [12/2023] **DiffKG: Knowledge Graph Diffusion Model for Recommendation** *Yangqin Jiang et al. arXiv.* [[paper](https://arxiv.org/pdf/2312.16890)]
- [06/2021] **Personalized News Recommendation with Knowledge-aware Interactive Matching** *Tao Qi et al. arXiv.* [[paper](https://arxiv.org/pdf/2104.10083)]
- [06/2019] **Reinforcement Knowledge Graph Reasoning for Explainable Recommendation** *Yikun Xian et al. arXiv.* [[paper](https://arxiv.org/pdf/1906.05237)]

####  Large Language Model based Recommender Systems: 
- [03/2024] **RecMind: Large Language Model Powered Agent For Recommendation** *Yancheng Wang et al. arXiv.* [[paper](https://arxiv.org/pdf/2308.14296)]
- [04/2023] **Prompt Learning for News Recommendation** *Zizhuo Zhang et al. arXiv.* [[paper](https://arxiv.org/pdf/2304.05263)]
- [02/2023] **Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5)** *Shijie Geng et al. arXiv.* [[paper](https://arxiv.org/pdf/2203.13366)]

Explore the **[Complete List](https://arxiv.org/pdf/2407.13699)(#)** of referenced works.

## Challenges in Recommender Systems
Key challenges:
1. Balancing **personalization** and **privacy**.
2. Addressing **cold-start** problems.
3. Ensuring **diversity and fairness** in recommendations.
4. Handling large-scale **real-time data** in **e-commerce**, **healthcare**, and **news**.

---

## Advanced Techniques
Explore state-of-the-art models:
- **Deep Learning**:
  - Neural Collaborative Filtering (NCF)
  - Variational Autoencoders (VAE)
- **Graph Neural Networks**:
  - LightGCN, KGAT
- **Transformer Models**:
  - BERT4Rec, Transformers4Rec
 
## Impact of the Research

This review profoundly influences future research and industry practices in Recommender Systems (RS). It highlights areas needing further investigation, particularly in advanced modeling techniques Graph neural networks, Knowledge based, LLMs and many recent methods. The detailed summaries and 11 comprehensive analysis tables serve as educational tools and practical guides for industry professionals. By tracing the evolution of RS, the paper offers insights into how theoretical advancements can address real-world challenges in sectors like e-commerce, healthcare, and finance, bridging the gap between theory and practice. 

---

## Limitations

Despite significant advancements, current Recommender Systems (RS) face critical limitations, including challenges in scalability, adaptability, and computational efficiency, particularly in dynamic and real-time environments. These systems often struggle with integrating diverse data sources, maintaining transparency, and addressing ethical concerns such as bias and privacy issues. Additionally, the heavy reliance on explicit feedback and the substantial computational resources required for deep learning models further complicate their deployment, especially for smaller organizations.

---

## Future Directions
The survey emphasizes:
- Real-time, scalable RS solutions.
- Integration of **Explainable AI** for user trust.
- Expanding RS applications in healthcare, finance, and education.

Future works in RS must focus on responsible AI practices to minimize biases and prevent the spread of misinformation. Evaluating RS beyond accuracy, with an emphasis on diversity and serendipity, will be crucial for enhancing user experiences. The growing need for transparency and explainability requires more interpretable models. Addressing computation and storage challenges by developing on-device RS can improve efficiency and privacy. Additionally, exploring causality in recommendations and leveraging generative AI for conversational RS must be done with a focus on safety and responsible practices.

---

**Target Audience:**

- **Researchers and Students**: A guide for theory and practice.
- **Industry Professionals and Engineers**: A cookbook for applying state-of-the-art techniques.
- **Tech Companies and Startups**: Insights on integrating advanced RS solutions and staying updated on trends.


## 🌟 **How to Cite**
If you find our paper helpful, please cite:

```

@article{raza2024comprehensive,
  title={A Comprehensive Review of Recommender Systems: Transitioning from Theory to Practice},
  author={Raza, Shaina and Rahman, Mizanur and Kamawal, Safiullah and Toroghi, Armin and Raval, Ananya and Navah, Farshad and Kazemeini, Amirmohammad},
  journal={arXiv preprint arXiv:2407.13699},
  year={2024}
}
```
## 📫 **Contact**
For queries or collaborations:
- **Email**: [shaina.raza@vectorinstitute.ai], [mizanur.rahman@rbc.com], [amirmohammad.kazemeini@vectorinstitute.ai]
- **Contributions**: Feel free to submit a pull request for updates or suggestions!

---

## 🎉 **Contributions and Feedback**
We welcome your feedback and contributions to make this repository a valuable resource for the RS community. Follow for updates!
