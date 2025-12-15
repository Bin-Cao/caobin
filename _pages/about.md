---
permalink: /about-me
title: "About Me"
excerpt: "Mr. CAO Bin's Profile"
author_profile: true
redirect_from: 
  - /
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**CAO Bin 曹斌**


Bin Cao received his Bachelor’s, MPhil, and PhD degrees from [Beijing University of Chemical Technology](https://www.buct.edu.cn/main.htm), [Shanghai University](https://www.shu.edu.cn/) (supervisor : [Prof. ZHANG Tong-Yi](https://english.casad.cas.cn/members/casm/dots/202404/t20240418_660476.html)), and [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/) (supervisor : [Prof. ZHANG Tong-Yi](https://english.casad.cas.cn/members/casm/dots/202404/t20240418_660476.html)) in 2020, 2023, and 2026 (expected), respectively. His research focuses on artificial intelligence for materials science, with particular emphasis on crystallography and spectroscopy. He has developed a series of machine learning algorithms for crystal structure determination ([XQueryer](https://github.com/Bin-Cao/XQueryer)), crystal property prediction(PRDNet), and novel crystal discovery([SimXRD](https://github.com/Bin-Cao/SimXRD)). He has published high-impact **first-author** research papers in *National Science Review*, *Science Bulletin*, *npj Computational Materials*, among other journals, and has also presented work at top-tier AI conferences such as *ICLR*. In 2025, he received support from the Shanghai Artificial Intelligence Open Source Award Project Support Plan as [principle developer](https://github.com/Bin-Cao/Bgolearn/blob/main/figures/funding.png), with RMB 500,000 in funding for the development of the [Bgolearn](https://github.com/Bin-Cao/Bgolearn) platform.



# 📝 Selected Publications (co-/first author)


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




...