---
permalink: /
title: "CAO Bin - AI for Materials Science"
excerpt: "Dr. CAO Bin's Academic Profile"
author_profile: true
redirect_from:
  - /about-me
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div class="hero-section">
  <h1 class="hero-title">CAO Bin <span class="chinese-name">曹斌</span></h1>
  <p class="hero-subtitle">Artificial Intelligence for Computational Materials</p>
  <div class="hero-divider"></div>
</div>

<span class='anchor' id='about-me'></span>

## About Me

I am a PhD student at [HKUST (Guangzhou)](https://www.hkust-gz.edu.cn/), working with [Prof. ZHANG Tong-Yi](https://english.casad.cas.cn/members/casm/dots/202404/t20240418_660476.html). My research focuses on **artificial intelligence for materials science**, with particular emphasis on algorithm development for **crystallography and spectroscopy**. During my PhD, I also served as a visiting student at **City University of Hong Kong**, working with [Prof. REN Yang](https://scholars.cityu.edu.hk/en/persons/yangren/).

Before joining HKUST (Guangzhou), I earned an **MPhil in Mechanics** at [Shanghai University](https://www.shu.edu.cn/), working with [Prof. ZHANG Tong-Yi](https://english.casad.cas.cn/members/casm/dots/202404/t20240418_660476.html). During this period, I also interned  at [Zhejiang Laboratory](https://www.zhejianglab.org/), where I worked on **transfer learning for materials science**. I received my **BEng in Chemical Machinery** from [Beijing University of Chemical Technology](https://www.buct.edu.cn/main.htm), where my work focused on **finite element and chemistry**.

In recent years, I developed a series of machine-learning algorithms for **crystal structure determination** ([XQueryer](https://github.com/Bin-Cao/XQueryer)), **crystal property prediction** (PRDNet), and **novel crystal discovery** ([SimXRD](https://github.com/Bin-Cao/SimXRD)). My first-author papers have appeared in materials science journals (e.g., *National Science Review* and *Science Bulletin*) and AI conferences such as *ICLR*.

One of my long-term projects, **Bgolearn**, received support from the *Shanghai Artificial Intelligence Open Source Award Project Support Plan*, where I serve as the [principal developer](https://github.com/Bin-Cao/Bgolearn/blob/main/figures/funding.png). The project was awarded **RMB 500,000** to support the development of the open-source [Bgolearn](https://github.com/Bin-Cao/Bgolearn) platform. Outside of research, I enjoy **jogging** and **watching movies**.

---


# 📝 Selected Publications (co-/first author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> VSGenerator </div><img src='images/scibull.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [Spatial-adaptive active learning identifies ultra-durable and highly active catalysts for acidic oxygen evolution reaction](https://www.sciencedirect.com/science/article/pii/S2095927325012678?via%3Dihub)

  **Bin Cao**, Yin Qi+, Yan Luo, Zhehan Ying, Zilin Yan, Lu-Tao Weng, Kaikai Li+, Tong-Yi Zhang+.

  [**VSGenerator**](https://github.com/Bgolearn/VSGenerator) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - Here, we present a **spatially adaptive active-learning framework** with **closed-loop experimentation** for targeted catalyst optimization. Bayesian optimization and a conditional variational autoencoder first identify a low-overpotential stability subspace, followed by active learning to pinpoint the most stable candidate. This strategy leads to the discovery of a **Cu–RuO₂ catalyst** with outstanding durability (**625 h**) and a low overpotential of **177 mV at 10 mA cm⁻²**. Our results highlight an efficient AI-driven pathway for accelerating the design of stable acidic OER catalysts.

</div>
</div>
- [Spatial-adaptive active learning identifies ultra-durable and highly active catalysts for acidic oxygen evolution reaction](https://www.sciencedirect.com/science/article/pii/S2095927325012678?via%3Dihub) **Bin Cao**, Yin Qi+, Yan Luo, Zhehan Ying, Zilin Yan, Lu-Tao Weng, Kaikai Li+, Tong-Yi Zhang+. **Science Bulletin**




<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> XQueryer </div><img src='images/XQueryer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [XQueryer: an intelligent crystal structure identifier for powder X-ray diffraction](https://doi.org/10.1093/nsr/nwaf421)

  **Bin Cao**, Zinan Zheng, Yang Liu, Longhan Zhang, Lawrence W-Y Wong, LuTao Weng, Jia Li, Haoxiang Li, Tong-Yi Zhang*.

  [**XQueryer**](https://doi.org/10.1093/nsr/nwaf421) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - We developed XQueryer, an intelligent agent for simulating, recognizing, and analyzing powder X-ray diffraction (PXRD) patterns. Trained on over two million high-fidelity simulated spectra, XQueryer achieves significantly higher accuracy—28.9% better than existing AI models and traditional methods. Integrated with a powder diffractometer, it enables real-time structural analysis of crystal samples.

  </div>
</div>
- [XQueryer: an intelligent crystal structure identifier for powder X-ray diffraction](https://doi.org/10.1093/nsr/nwaf421) **Bin Cao**, Zinan Zheng, Yang Liu, Longhan Zhang, Lawrence W-Y Wong, LuTao Weng, Jia Li, Haoxiang Li, Tong-Yi Zhang*, **Natl. Sci. Rev.**




<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> PRDNet </div><img src='images/PRDNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [BEYOND STRUCTURE: Invariant Crystal Property Prediction with Pseudo-Particle Ray Diffraction](https://arxiv.org/pdf/2509.21778)

  **Bin Cao**, Yang Liu*, Longhan Zhang, Yifan Wu, Zhixun Li, Yuyu Luo, Hong Cheng, Yang Ren*, Tong-Yi Zhang*

  [**PRDNet**](https://arxiv.org/pdf/2509.21778) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - We propose PRDNet, a novel architecture that integrates graph embeddings with a learned pseudoparticle diffraction module. It generates synthetic diffraction patterns that are invariant to crystallographic symmetries. We extensively evaluate PRDNet on multiple large-scale benchmarks, including Materials Project, JARVIS-DFT, and MatBench. Our model achieves state-of-the-art performance across a wide range of crystal property prediction tasks, demonstrating its effectiveness.

  </div>
</div>
- [BEYOND STRUCTURE: Invariant Crystal Property Prediction with Pseudo-Particle Ray Diffraction](https://arxiv.org/pdf/2509.21778) **Bin Cao**, Yang Liu*, Longhan Zhang, Yifan Wu, Zhixun Li, Yuyu Luo, Hong Cheng, Yang Ren*, Tong-Yi Zhang*, **arXiv**




<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> MGE advances 2025 </div><img src='images/bgoface.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [Optimize the quantum yield of G‐quartet‐based circularly polarized luminescence materials via active learning strategy‐BgoFace](https://onlinelibrary.wiley.com/doi/epdf/10.1002/mgea.70031)

  Tianliang Li, Lifei Chen(co-first author) **Bin Cao(co-first author)**, Siyuan Liu,..., Tong-Yi Zhang*, Lingyan Feng*

  [**BgoFace**](https://github.com/Bgolearn/BgoFace) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - This work developed an integrated AL software, BgoFace, which satisfies most material property optimization re-quirements. The application of BgoFace (with default setting) successfully accel-erated the discovery of G4-based CPL materials, achievingresults within six iterations and synthesizing 24 experimentalgroups. The final QY nearly doubled the initial best QY inthe training dataset. 

  </div>
</div>
- [Optimize the quantum yield of G‐quartet‐based circularly polarized luminescence materials via active learning strategy‐BgoFace](https://onlinelibrary.wiley.com/doi/epdf/10.1002/mgea.70031) Tianliang Li, Lifei Chen(co-first author) **Bin Cao(co-first author)**, Siyuan Liu,..., Tong-Yi Zhang*, Lingyan Feng*, **MGE advances**




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/mg_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [Materials Generation in the Era of Artificial Intelligence: A Comprehensive Survey](https://arxiv.org/pdf/2505.16379)

  Zhixun Li, **Bin Cao(co-first author)**,  Rui Jiao(co-first author), Liang Wang(co-first author), Ding Wang, Yang Liu, Dingshuo Chen, Jia Li, Qiang Liu, Yu Rong, Liang Wang, Tong-Yi Zhang, Jeffrey Xu Yu
  [**MatGen**](https://github.com/ZhixunLEE/Awesome-AI-for-Materials-Generation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - We first organize various types of materials and illustrate multiple representations of crystalline materials. We then provide a detailed summary and taxonomy of current AI-driven materials generation approaches. Furthermore, we discuss the common evaluation metrics and summarize open-source codes and benchmark datasets. Finally, we conclude with potential future directions and challenges in this fast-growing field. 
  </div>
</div>
- [Materials Generation in the Era of Artificial Intelligence: A Comprehensive Survey](https://arxiv.org/pdf/2505.16379) Zhixun Li, **Bin Cao(co-first author)**,  Rui Jiao(co-first author), Liang Wang(co-first author), Ding Wang, Yang Liu, Dingshuo Chen, Jia Li, Qiang Liu, Yu Rong, Liang Wang, Tong-Yi Zhang, Jeffrey Xu Yu, **arXiv**



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Aggregate 2025</div><img src='images/aggregateshap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [Interpretable Active Learning Identifies Iron-Doped Carbon Dots With High Photothermal Conversion Efficiency for Antitumor Synergistic Therapy](https://onlinelibrary.wiley.com/doi/epdf/10.1002/agt2.70060)

  Tianliang Li, **Bin Cao(co-first author)**,  Yitong Wang, Lixing Lin, ..., Lingyan Feng, Tong-yi Zhang

  [**SHAP-AL**](https://github.com/Bin-Cao/ShapEV) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - We apply an interpretable AL strategy to efficiently optimize the photothermal conversion efficiency (PCE) of carbon dots (CDs) in photothermal therapy (PTT). Using this approach, we successfully synthesized irondoped CDs (Fe-CDs) with PCE exceeding 78.7% after only 16 experimental trials over four iterations.
  </div>
</div>
- [Interpretable Active Learning Identifies Iron-Doped Carbon Dots With High Photothermal Conversion Efficiency for Antitumor Synergistic Therapy](https://onlinelibrary.wiley.com/doi/epdf/10.1002/agt2.70060) Tianliang Li, **Bin Cao(co-first author)**,  Yitong Wang, Lixing Lin, ..., Lingyan Feng, Tong-yi Zhang, **Aggregate** (JCR Q1)





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/simxrdiclr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [SimXRD-4M: Big Simulated X-ray Diffraction Data and Crystal Symmetry Classification Benchmark](https://openreview.net/pdf?id=mkuB677eMM)

  **Bin Cao**,  Yang Liu, Zinan Zheng, Ruifeng Tan, Jia Li, Tong-yi Zhang

  [**SimXRD-4M**](https://openreview.net/pdf?id=mkuB677eMM) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - We developed a novel XRD simulation method that incorporates comprehensive physical interactions, resulting in a high-fidelity database.
  </div>
</div>
- [SimXRD-4M: Big Simulated X-ray Diffraction Data and Crystal Symmetry Classification Benchmark](https://openreview.net/pdf?id=mkuB677eMM) **Bin Cao**,  Yang Liu, Zinan Zheng, Ruifeng Tan, Jia Li, Tong-yi Zhang, **ICLR2025** (Top-tier AI conference)




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SMALL 2024</div><img src='images/small_li.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [Machine Learning-Engineered Nanozyme System for Synergistic Anti-Tumor Ferroptosis/Apoptosis Therapy](https://onlinelibrary.wiley.com/doi/10.1002/smll.202408750)

  Tianliang Li, **Bin Cao(co-first author)**,  Tianhao Su, ..., Lingyan Feng, Tong-yi Zhang

  [**TCGPR+Bgolearn**](https://onlinelibrary.wiley.com/doi/10.1002/smll.202408750) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - A novel ML model, termed the sequential backward Tree-Classifier for Gaussian Process Regression (TCGPR), is proposed to improve data pattern recognition following the divide-and-conquer principle.
  </div>
</div>
- [Machine Learning-Engineered Nanozyme System for Synergistic Anti-Tumor Ferroptosis/Apoptosis Therapy](https://onlinelibrary.wiley.com/doi/10.1002/smll.202408750) Tianliang Li, **Bin Cao(co-first author)**,  Tianhao Su, ..., Lingyan Feng, Tong-yi Zhang **SMALL** (JCR Q1)





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMI 2024</div><img src='images/cgwgan.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [CGWGAN: crystal generative framework based on Wyckoff generative adversarial network](https://www.oaepublish.com/articles/jmi.2024.24)

  Tianhao Su, **Bin Cao(co-first author)**, Shunbo Hu, Musen Li, Tong-yi Zhang

  [**Crystal Generative Framework**](https://www.oaepublish.com/articles/jmi.2024.24) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - In this work, we present a crystal generative framework based on Wyckoff generative adversarial network (CGWGAN) to efficiently discover novel crystals.
  </div>
</div>
- [CGWGAN: crystal generative framework based on Wyckoff generative adversarial network](https://www.oaepublish.com/articles/jmi.2024.24)Tianhao Su, **Bin Cao(co-first author)**, Shunbo Hu, Musen Li, Tong-yi Zhang **JMI** (New journal led by my supervisor, Prof. Zhang Tongyi.)








<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/simxrd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  [SimXRD-4M: Big Simulated X-ray Diffraction Data Accelerate the Crystalline Symmetry Classification](https://arxiv.org/html/2406.15469v1)

  **Bin Cao**, Yang Liu, Zinan Zheng, Ruifeng Tan, Jia Li, Tong-yi Zhang

  [**Database & Benchmark**](https://arxiv.org/html/2406.15469v1) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - In this work, a large open-source dataset of powder XRD patterns designed for symmetry identification. 21 existing ML models are assessed, summarizing the XRD sequence data characteristics, and providing suggestions for the further development of ML models best suited for analyzing XRD patterns.
  </div>
</div>
- [SimXRD-4M: Big Simulated X-ray Diffraction Data Accelerate the Crystalline Symmetry Classification](https://arxiv.org/html/2406.15469v1)**Bin Cao**, Yang Liu, Zinan Zheng, Ruifeng Tan, Jia Li, Tong-yi Zhang **arXiv**

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IUCrJ 2024</div>
      <img src='images/cpi.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Crystallographic Phase Identifier of a Convolutional Self-Attention Neural Network (CPICANN) on Powder Diffraction Patterns](https://doi.org/10.1107/S2052252524005323)

  Shouyang Zhang, **Bin Cao (co-first)**, Tianhao Su, Yue Wu, Zhenjie Feng, Jie Xiong, Tong-Yi Zhang

  [**Phase**](https://doi.org/10.1107/S2052252524005323) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

  - In this work, we developed a machine learning phase identifier that achieved excellent performance within a relatively small scope.
</div>
</div>
- [Crystallographic Phase Identifier of a Convolutional Self-Attention Neural Network (CPICANN) on Powder Diffraction Patterns](https://doi.org/10.1107/S2052252524005323)Shouyang Zhang, **Bin Cao (co-first)**, Tianhao Su, Yue Wu, Zhenjie Feng, Jie Xiong, Tong-Yi Zhang **IUCrJ** (JCR Q1)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">M&D 2024</div><img src='images/bgolearn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Active Learning Accelerates the Discovery of High Strength and High Ductility Lead-Free Solder Alloys](https://doi.org/10.1016/j.matdes.2024.112921)

**B Cao**, T Su, S Yu, T Li, T Zhang, Z Dong, TY Zhang

[**Project**](https://github.com/Bin-Cao/Bgolearn) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- To facilitate materials informatics development, all active learning algorithms were made open-source in our designed framework, Bgolearn... 
</div>
</div>

- [Active Learning Accelerates the Discovery of High Strength and High Ductility Lead-Free Solder Alloys](https://doi.org/10.1016/j.matdes.2024.112921) B Cao, T Su, S Yu, T Li, T Zhang, Z Dong, TY Zhang **Material & Design** (JCR Q1)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NPJ 2024</div><img src='images/MLMD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MLMD: a programming-free AI platform to predict and design materials](https://www.nature.com/articles/s41524-024-01243-4)

Jiaxuan Ma, **Bin Cao (co-first author)**, Shuya Dong, Yuan Tian, Menghuan Wang, Jie Xiong, Sheng Sun 

[**Project**](https://github.com/Jiaxuan-Ma/MLMD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We developed MLMD, an AI platform for materials design. It is capable of effectively discovering novel materials with high-potential advanced properties end-to-end, utilizing model inference, surrogate optimization, and even working in situations of data scarcity based on active learning.. 
</div>
</div>

- [MLMD: a programming-free AI platform to predict and design materials](https://doi.org/10.1038/s41524-024-01243-4) Ma, J., **Cao, B(co-first)**., Dong, S. et al. **npj Comput Mater 10, 59 (2024)** (JCR Q1)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NPJ 2023</div><img src='images/tcgprr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Divide and conquer: Machine learning accelerated design of lead-free solder alloys with high strength and high ductility](https://www.nature.com/articles/s41524-023-01150-0)
Qinghua Wei, **Bin Cao (co-first author)**, Hao Yuan (co-first author), Youyang Chen, Kangdong You, Shuting Yu, Tixin Yang, Ziqiang Dong, Tong-Yi Zhang 

[**Project**](https://github.com/Bin-Cao/TCGPR/blob/main/Intro/TCGPR.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In general, small in size and big in noise, while the design space is huge, by a newly developed data preprocessing algorithm, named the Tree-Classifier for Gaussian Process Regression (TCGPR)... 
</div>
</div>

- [Divide and conquer: Machine learning accelerated design of lead-free solder alloys with high strength and high ductility](https://www.nature.com/articles/s41524-023-01150-0). Qinghua Wei, **Bin Cao (co-first author)**, Hao Yuan (co-first author), Youyang Chen, Kangdong You, Shuting Yu, Tixin Yang, Ziqiang Dong, Tong-Yi Zhang **npj Comput Mater 201 (2023)** (JCR Q1)



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JMI 2022</div><img src='images/TCLR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**(Cover paper)**[Domain knowledge-guided interpretive machine learning: formula discovery for the oxidation behavior of ferritic-martensitic steels in supercritical water](https://www.oaepublish.com/articles/jmi.2022.04)
**Bin Cao**, Shuang Yang, Ankang Sun, Ziqiang Dong, Tong-Yi Zhang

[**Project**](https://github.com/Bin-Cao/TCLRmodel) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this study, we propose a domain knowledge-guided interpretive machine learning strategy and demonstrate it by studying the oxidation behavior of ferritic-martensitic steels in supercritical water... 
</div>
</div>

- [Domain knowledge-guided interpretive machine learning: formula discovery for the oxidation behavior of ferritic-martensitic steels in supercritical water](https://www.oaepublish.com/articles/jmi.2022.04) **Cao B**, Yang S, Sun A, Dong Z, Zhang TY. **Journal of Materials Informatics(2022)** (New journal led by my supervisor, Prof. Zhang Tongyi.)

---

<span class='anchor' id='news'></span>

## 🔥 News

- *2025.07*: 🎉🎉  I am honored to have received two awards: the Invited Academic Talk by Promising Young Talent and the High-Level Academic Poster. [2025 China Materials Conference](https://cmc2025.scimeeting.cn/cn/web/speaker-detail/27167?user_id=ZXvycJpgjG2WSbabyEmiSA_d_d).
- *2025.7*: 🎉🎉 I conduct a half-year research exchange at the Department of Physics, City University of Hong Kong, under the supervision of [Prof. Ren Yang](https://scholars.cityu.edu.hk/en/persons/yang-ren(7c17617b-dd79-43a0-ad19-b83053f4370a).html).
- *2025.4*: 🎉🎉 My paper received the [2024 Best Paper Award](https://mp.weixin.qq.com/s/T5zgliCfTwcD-WqkcQefuA) from JMI.
- *2024.11*: 🎉🎉 Successfully passed the Ph.D. qualification examination. Topic: Diffraction Theory-Informed AI for Crystal Analysis via Powder X-ray Diffraction
- *2024.07*: 🎉🎉 Outstanding Young Academic Presentation Award at the [2024 China Materials Conference](https://gdstc.gd.gov.cn/gkmlpt/content/4/4455/post_4455625.html#726).
- *2024.03*: 🎉🎉 Contributed to the material community by developing [MLMD](https://www.nature.com/articles/s41524-024-01243-4).
- *2023.09*: 🎉🎉 Embarked on a Ph.D. journey at [Hong Kong University of Science and Technology (Gangzhou)](https://www.hkust-gz.edu.cn/zh/).
- *2023.07*: 🎉🎉 Established new organization [WPEM](https://github.com/WPEM).
- *2023.06*: 🎉🎉 Successfully graduated from [SHU](https://www.shu.edu.cn/).
- *2023.04*: 🎉🎉 Contributed to the community by open-sourcing [TrAdaboost](https://github.com/Bin-Cao/TrAdaboost), a package on transfer learning.
- *2023.02*: 🎉🎉 Contributed to the community by open-sourcing [Bgolearn](https://github.com/Bin-Cao/Bgolearn), a package on materials optimization.
- *2022.07*: 🎉🎉 Fostered innovation by releasing [TCGPR](https://github.com/Bin-Cao/TCGPR) as an open-source package.
- *2022.05*: 🎉🎉 My paper has been selected as the cover paper for the May 2022 issue (2:4) of [JMI](https://www.oaepublish.com/articles/jmi.2022.04)
- *2021.09*: 🎉🎉 Fostered innovation by releasing [TCLR](https://github.com/Bin-Cao/TCLRmodel) as an open-source package.
- *2020.06*: 🎉🎉 Successfully graduated from [BUCT](https://www.buct.edu.cn/main.htm), equipped with essential knowledge and skills.

---

<span class='anchor' id='educations'></span>

## 📖 Education

- *2025.07 - 2025.12*: I conduct a half-year research exchange at the Department of Physics, City University of Hong Kong, under the supervision of [Prof. Ren Yang](https://scholars.cityu.edu.hk/en/persons/yang-ren(7c17617b-dd79-43a0-ad19-b83053f4370a).html).
- *2023.09 - 2026.06 (Ongoing)*: Doctorate in Advanced Materials, AI4CM, Hong Kong University of Science and Technology, Guangzhou, China. (SV : Prof. [Zhang Tong-yi](https://gbaaa.org.hk/en-us/article/67))
- *2020.09 - 2023.06*: Master of Philosophy in Materials Informatics, Shanghai University, Shanghai, China (SV : Prof. [Zhang Tong-yi](https://gbaaa.org.hk/en-us/article/67))
- *2016.09 - 2020.06*: Bachelor of Mechanical Engineering, Beijing University of Chemical Technology, Beijing, China

---

<span class='anchor' id='honors-and-awards'></span>

## 🎖 Honors and Awards

- *2025.7* Invited Academic Talk by Promising Young Talent Award at the 2025 China Materials Conference
- *2025.7* High-Level Academic Poster Award at the 2025 China Materials Conference
- *2024.7* Outstanding Young Academic Presentation Award at the 2024 China Materials Conference
- *2023.6* Outstanding Graduate of Shanghai University, [Valedictorian](https://mp.weixin.qq.com/s/gtqNaz4TG2yMZvm5KLtTdg)
- *2023.3* Roundtable Forum - Academician Gu Binglin Discusses the Spirit of Qian Weichang, [Student Representative](https://mp.weixin.qq.com/s/j0duVxBSHm0QrNAQ5Df7OQ)
- *2022.10* National Scholarship Winner, [Interview](https://mp.weixin.qq.com/s/-JNh1awMfR--bfX9XA2W9w?from=message&isappinstalled=0)

---

<span class='anchor' id='invited-talks'></span>

## 💬 Invited Talks

- *2025, 12*: CCF ChinaData 2025, Guiyang, Oral report. Topic : [Intelligent Structure Identification and Property Prediction](https://ccf.org.cn/chinadata2025/schedule_d_4038), Cao Bin, HKUST(GZ)
- *2025, 11*: International forum of materials genome engineering 2025, Xi'an, Oral report. Topic : Intelligent Structure Identification of Powder X-ray Diffraction Patterns, Cao Bin, HKUST(GZ)
- *2025, 7*: Chinese Materials Conference 2025 (Session E06), Xiameng, Oral report. Topic : [BGOLearn: An End-to-End Active Learning Framework for Materials Optimization](https://cmc2025.scimeeting.cn/cn/web/speaker-detail/27167?user_id=ZXvycJpgjG2WSbabyEmiSA_d_d), Cao Bin, HKUST(GZ)
- *2025, 4*: The Thirteenth International Conference on Learning Representations (ICLR 2025), Singapore. Topic : [SimXRD-4M: Big Simulated X-ray Diffraction Data and Crystal Symmetry Classification Benchmark](https://iclr.cc/virtual/2025/poster/28452), Cao Bin, HKUST(GZ)
- *2025,4*: Materials Research Conference 2025, Seattle USA, Oral report. Topic : [XQueryer—Intelligent Phase Identification for Powder X-Ray Diffraction](https://www.mrs.org/meetings-events/annual-meetings/archive/meeting/presentations/view/2025-mrs-spring-meeting/2025-mrs-spring-meeting-4205765), Cao Bin, HKUST(GZ)
- *2024, 7*: Chinese Materials Conference 2024 (Session E06-5-1), Guangzhou, Oral report. Topic : AI Deciphers crystal Materials, Cao Bin, HKUST(GZ)
- *2024, 6*: CATL-HKUST(GZ) AI Lab seminar, Oral report. Topic : intelligent characterization in the AI Lab Blueprint, Cao Bin, HKUST(GZ)
- *2024, 5*: X-ray technology progress seminar, Guangzhou, Oral report. Topic : WPEM : From Characterization to Structural analysis, Cao Bin, HKUST(GZ)
- *2023, 5*: National Symposium on Data-Driven Computational Mechanics, Dalian, Oral report. Topic : Formula discovery for the oxidation behavior of ferritic-martensitic steels in supercritical water, Cao Bin, ZheJiang Lab

---

<span class='anchor' id='internships'></span>

## 💻 Internships

- *2023.03 - 2023.09*: [Zhejiang Lab](https://www.zhejianglab.cn/lab/home), China.

---

<span class='anchor' id='service'></span>

## 🤝 Service

- Reviewer for International Conference on Learning Representations ([ICLR](https://iclr.cc/))
- Reviewer for Engineering Applications of Artificial Intelligence ([EAAI](https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence))
- Member of China Materials Research Society (C-MRS).
- Member of Chinese Crystallographic Society (CCrS).
- Member of China Computer Federation (CCF).

---

<span class='anchor' id='wpem'></span>

## 🔬 WPEM Project

[WPEM](https://github.com/Bin-Cao/WPEM) specializes in elucidating intricate crystal structures and untangling heavily overlapping Bragg peaks in mixed X-rays and polycrystalline powder diffraction. Our endeavors have yielded noteworthy research outcomes, including the precise detection of subtle structural differences, such as the α phase and α' phase of Ti-Ni alloy, the differentiation of amorphous and crystalline contributions in Polybutene, the investigation of complex solid solution structures, and the computation of scattering information within organized processes.

We are open to extensive collaborations and offer support in X-ray diffraction pattern refinement. For inquiries or assistance, please contact us at **bcao686@connect.hkust-gz.edu.cn (Dr. CAO Bin)**. **Homepage:** [bin-cao](https://bin-cao.github.io/caobin/)

---

<span class='anchor' id='publications'></span>

## 📚 Full Publications List

- `Science Bulletin 2025` [Spatial-adaptive active learning identifies ultra-durable and highly active catalysts for acidic oxygen evolution reaction](https://www.sciencedirect.com/science/article/pii/S2095927325012678?via%3Dihub) **Bin Cao**, Yin Qi+, Yan Luo, Zhehan Ying, Zilin Yan, Lu-Tao Weng, Kaikai Li+, Tong-Yi Zhang+. **Science Bulletin** (JCR Q1)

- `Angewandte Chemie 2025` [First‐Order Phase Transformation in Highly Concentrated Electrolyte for High‐Rate and Long‐Cycle Aqueous Zn‐Ion Battery](https://doi.org/10.1002/anie.202520628) Xiuling Shi, Yuchuan Sun, **Bin Cao** et al., **Angewandte Chemie 2025** (JCR Q1)

- `Advanced Materials 2025` [Metal–Insulator Transition Driven by the Interplay of Vacancies and Charge Orders in Square‐Net Materials GdSbxTe2‐x‐δ](https://advanced.onlinelibrary.wiley.com/doi/10.1002/adma.202510303?af=R) Qun Wang et al., **Advanced Materials 2025** (JCR Q1)

- `Natl. Sci. Rev. 2025` [XQueryer: an intelligent crystal structure identifier for powder X-ray diffraction](https://doi.org/10.1093/nsr/nwaf421) **Bin Cao**, Zinan Zheng, Yang Liu, Longhan Zhang, Lawrence W-Y Wong, LuTao Weng, Jia Li*, Haoxiang Li*, Tong-Yi Zhang*, **Natl. Sci. Rev. 2025** (JCR Q1)

- `arXiv 2025` [BEYOND STRUCTURE: Invariant Crystal Property Prediction with Pseudo-Particle Ray Diffraction](https://arxiv.org/pdf/2509.21778)  **Bin Cao**, Yang Liu*, Longhan Zhang, Yifan Wu, Zhixun Li, Yuyu Luo, Hong Cheng, Yang Ren*, Tong-Yi Zhang*, **arXiv 2025**.

- `ACS nano 2025` [Ferromagnetic Surface Segregation via Stress-Concentration Coupling Boosts the Oxygen Evolution Reaction in RuO2](https://pubs.acs.org/doi/abs/10.1021/acsnano.5c06052)  Qin, Y., Deng, S., Zhou, X. Y., **Cao, B.**, Ying, Z., Yan, Z., ... & Zhang, T. Y.  **ACS nano 2025**.

- `MGE advances 2025` [Optimize the quantum yield of G‐quartet‐based circularly polarized luminescence materials via active learning strategy‐BgoFace](https://onlinelibrary.wiley.com/doi/epdf/10.1002/mgea.70031) Tianliang Li, Lifei Chen(co-first author) **Bin Cao(co-first author)**, Siyuan Liu,..., Tong-Yi Zhang*, Lingyan Feng* **MGE advances 2025**

- `Scripta Materialia 2025` [Dissecting the chemical strain in inactive components of sodium-ion battery cathodes](https://www.sciencedirect.com/science/article/pii/S1359646225003434?dgcid=coauthor) Xiuling Shi, Jiaqi Zhu, Bingxu Chen, **Bin Cao**, Binfeng Lv, Zihan Wang, Sheng Sun, Kaikai Li, Tong-Yi Zhang. **Scripta Materialia** (JCR Q1)

- `ICLR 2025` [SimXRD-4M: Big Simulated X-ray Diffraction Data and Crystal Symmetry Classification Benchmark](https://openreview.net/pdf?id=mkuB677eMM) **Bin Cao**,  Yang Liu, Zinan Zheng, Ruifeng Tan, Jia Li, Tong-yi Zhang. **ICLR2025** (Top-tier AI conference)

- `SMALL 2024` [Machine Learning-Engineered Nanozyme System for Synergistic Anti-Tumor Ferroptosis/Apoptosis Therapy](https://onlinelibrary.wiley.com/doi/10.1002/smll.202408750) Tianliang Li, **Bin Cao(co-first author)**,  Tianhao Su, ..., Lingyan Feng, Tong-yi Zhang. **SMALL** (JCR Q1)

- `npj 2024` [MLMD: a programming-free AI platform to predict and design materials](https://www.nature.com/articles/s41524-024-01243-4) Jiaxuan Ma, **Bin Cao (co-first author)**, Shuya Dong, Yuan Tian, Menghuan Wang, Jie Xiong, Sheng Sun (JCR Q1)

- `npj 2023` [Divide and conquer: Machine learning accelerated design of lead-free solder alloys with high strength and high ductility](https://www.nature.com/articles/s41524-023-01150-0) Qinghua Wei, **Bin Cao (co-first author)**, Hao Yuan (co-first author), Youyang Chen, Kangdong You, Shuting Yu, Tixin Yang, Ziqiang Dong, Tong-Yi Zhang (JCR Q1)

- `JMI 2022` **(Cover paper)**[Domain knowledge-guided interpretive machine learning: formula discovery for the oxidation behavior of ferritic-martensitic steels in supercritical water](https://www.oaepublish.com/articles/jmi.2022.04) **Bin Cao**, Shuang Yang, Ankang Sun, Ziqiang Dong, Tong-Yi Zhang (JCR Q2 ｜ Editor-in-Chief ： Tong-Yi Zhang)