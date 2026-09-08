---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
/* ---------- Homepage polish: self-contained and AcademicPages-friendly ---------- */
.home-hero {
  margin: 0.25rem 0 2rem;
  padding: 1.55rem 1.7rem;
  border: 1px solid #e6edf5;
  border-radius: 14px;
  background: linear-gradient(135deg, #f8fbff 0%, #ffffff 72%);
  box-shadow: 0 8px 24px rgba(31, 78, 121, 0.06);
}
.home-hero h1 {
  margin: 0.15rem 0 0.35rem;
  font-size: 2rem;
  line-height: 1.15;
  letter-spacing: -0.02em;
}
.home-kicker {
  margin-bottom: 0.45rem;
  color: #4b6f91;
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}
.home-role {
  margin: 0 0 0.9rem;
  color: #53606d;
  font-size: 0.98rem;
}
.home-intro {
  margin: 0.6rem 0 0.9rem;
  line-height: 1.75;
}
.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin: 0.9rem 0 1rem;
}
.research-tag {
  display: inline-block;
  padding: 0.26rem 0.66rem;
  border: 1px solid #d9e6f2;
  border-radius: 999px;
  background: #f4f8fc;
  color: #315f86;
  font-size: 0.84rem;
  line-height: 1.4;
}
.home-contact {
  margin: 0.2rem 0 0;
  color: #53606d;
  font-size: 0.93rem;
}
.home-contact a { font-weight: 600; }

.section-lead {
  margin-top: -0.2rem;
  margin-bottom: 1rem;
  color: #6a737d;
  font-size: 0.94rem;
}
.timeline {
  margin: 0.8rem 0 1.8rem;
  padding-left: 0.2rem;
}
.timeline-item {
  display: grid;
  grid-template-columns: 8.2rem 1fr;
  gap: 0.8rem;
  padding: 0.62rem 0 0.62rem 0.95rem;
  border-left: 2px solid #dbe8f3;
}
.timeline-date {
  color: #4b6f91;
  font-size: 0.9rem;
  font-weight: 700;
  white-space: nowrap;
}
.timeline-main { line-height: 1.55; }
.timeline-main strong { font-weight: 650; }

.news-list {
  margin: 0.6rem 0 1.8rem;
  padding-left: 0;
  list-style: none;
}
.news-list li {
  position: relative;
  margin: 0;
  padding: 0.48rem 0 0.48rem 5.2rem;
  line-height: 1.55;
}
.news-date {
  position: absolute;
  left: 0;
  top: 0.49rem;
  width: 4.45rem;
  color: #4b6f91;
  font-size: 0.86rem;
  font-weight: 700;
}
.news-badge {
  display: inline-block;
  margin-right: 0.4rem;
  padding: 0.05rem 0.38rem;
  border-radius: 999px;
  background: #edf6ff;
  color: #28679e;
  font-size: 0.72rem;
  font-weight: 700;
  vertical-align: 0.08rem;
}

.pub-note {
  display: inline-block;
  margin-left: 0.25rem;
  padding: 0.05rem 0.38rem;
  border: 1px solid #dfe7ef;
  border-radius: 999px;
  color: #5b6773;
  font-size: 0.72rem;
  vertical-align: 0.08rem;
}

.archive-box {
  margin: 0.6rem 0 1.8rem;
  padding: 0.1rem 0.9rem;
  border: 1px solid #e7edf3;
  border-radius: 10px;
  background: #fbfcfe;
}
.archive-box summary {
  padding: 0.7rem 0;
  cursor: pointer;
  color: #53606d;
  font-weight: 600;
}

.page__content h1 {
  margin-top: 2.1rem;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid #e8edf2;
  font-size: 1.48rem;
}
.page__content h2,
.page__content h3 { margin-top: 1.45rem; }
.page__content ul li { margin-bottom: 0.45rem; }
.page__content a { text-decoration-thickness: 1px; text-underline-offset: 2px; }

@media (max-width: 650px) {
  .home-hero { padding: 1.2rem 1.15rem; }
  .home-hero h1 { font-size: 1.72rem; }
  .timeline-item { grid-template-columns: 1fr; gap: 0.1rem; }
  .news-list li { padding-left: 0; padding-top: 1.55rem; }
  .news-date { top: 0.35rem; }
}
</style>

<span class='anchor' id='about-me'></span>

<div class="home-hero">
  <div class="home-kicker">Optimization · Numerical Algorithms</div>
  <h1>Kangkang Deng</h1>
  <p class="home-role"><strong>Associate Professor</strong> · College of Science, National University of Defense Technology · Changsha, China</p>

  <p class="home-intro">
    My research focuses on optimization algorithms, with particular interests in <strong>manifold optimization</strong>, <strong>nonsmooth optimization</strong>, <strong>augmented Lagrangian / ADMM methods</strong>, and <strong>decentralized optimization</strong>.
  </p>

  <div class="research-tags">
    <span class="research-tag">Manifold Optimization</span>
    <span class="research-tag">Nonsmooth Optimization</span>
    <span class="research-tag">Augmented Lagrangian &amp; ADMM</span>
    <span class="research-tag">Decentralized Optimization</span>
  </div>

  <p class="home-contact">I am always happy to discuss research and potential collaborations. Email: <a href="mailto:freedeng1208@gmail.com">freedeng1208@gmail.com</a></p>
</div>

I received my bachelor's degree from Fujian Normal University and my Ph.D. from the Research Center for Discrete Mathematics (离散数学研究中心), Fuzhou University, under the supervision of <a href="http://www.pzhengxtu.com/" target="_blank">Zheng Peng (彭拯)</a>. I subsequently conducted postdoctoral research at the Beijing International Center for Mathematical Research (BICMR，北京国际数学研究中心), Peking University, under the supervision of <a href="http://faculty.bicmr.pku.edu.cn/~wenzw/index.html" target="_blank">Zaiwen Wen (文再文)</a>.

# Academic Appointments & Education

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026.04 – Present</div>
    <div class="timeline-main"><strong>Associate Professor</strong>, College of Science, National University of Defense Technology, Changsha</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2023.04 – 2026.04</div>
    <div class="timeline-main"><strong>Assistant Researcher</strong>, College of Science, National University of Defense Technology, Changsha</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2020.09 – 2023.04</div>
    <div class="timeline-main"><strong>Postdoctoral Researcher</strong>, Beijing International Center for Mathematical Research, Peking University, Beijing</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2015.06 – 2020.06</div>
    <div class="timeline-main"><strong>Ph.D.</strong>, Research Center for Discrete Mathematics, Fuzhou University, Fuzhou</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2011.09 – 2015.06</div>
    <div class="timeline-main"><strong>B.Sc.</strong>, School of Mathematics and Computer Science, Fujian Normal University, Fuzhou</div>
  </div>
</div>

# Recent News

<ul class="news-list">
  <li><span class="news-date">2026.09</span><span class="news-badge">NEW</span>One paper accepted by <strong>Mathematics of Operations Research</strong>.</li>
  <li><span class="news-date">2026.02</span>One paper accepted by <strong>Applied Mathematical Modelling</strong>.</li>
  <li><span class="news-date">2026.01</span>One paper accepted by <strong>IMA Journal of Numerical Analysis</strong>.</li>
  <li><span class="news-date">2025.12</span>One paper accepted by <strong>Applied Numerical Mathematics</strong>.</li>
  <li><span class="news-date">2025.09</span>One paper accepted by <strong>SIAM Review</strong>.</li>
  <li><span class="news-date">2025.09</span>Two papers accepted by <strong>NeurIPS 2025</strong>.</li>
  <li><span class="news-date">2025.09</span>One paper accepted by <strong>Journal of Optimization Theory and Applications</strong>.</li>
  <li><span class="news-date">2025.09</span>One paper accepted by <strong>Numerische Mathematik</strong>.</li>
</ul>

<details class="archive-box">
<summary>Earlier news in 2025</summary>
<ul class="news-list">
  <li><span class="news-date">2025.08</span>One paper accepted by <strong>Mathematics of Operations Research</strong>.</li>
  <li><span class="news-date">2025.07</span>One paper accepted by <strong>Journal of Applied Analysis and Computation</strong>.</li>
  <li><span class="news-date">2025.05</span>One paper accepted by <strong>Journal of Scientific Computing</strong>.</li>
  <li><span class="news-date">2025.02</span>One paper accepted by <strong>IEEE Transactions on Automatic Control</strong>.</li>
  <li><span class="news-date">2025.02</span>One paper accepted by <strong>Journal of the Operations Research Society of China</strong>.</li>
</ul>
</details>

# Preprints

- [**A Single-loop Stochastic Riemannian ADMM for Nonsmooth Optimization**](https://arxiv.org/abs/2512.22750)  
  Jiachen Jin, **Kangkang Deng**, Hongxia Wang, 2025.
- [**Single-loop $\mathcal{O}(\epsilon^{-3})$ stochastic smoothing algorithms for nonsmooth Riemannian optimization**](https://arxiv.org/abs/2505.09485)  
  **Kangkang Deng**, Zheng Peng, Weihe Wu, 2025.
- [**Stochastic Momentum ADMM for nonconvex and nonsmooth optimization with application to PnP algorithm**](https://arxiv.org/abs/2504.08223)  
  **Kangkang Deng**, Shuchang Zhang, Boyu Wang, Jiachen Jin, Juan Zhou, Hongxia Wang, 2025.
- [**Improving the communication in decentralized manifold optimization through single-step consensus and compression**](https://arxiv.org/abs/2407.08904)  
  Jiang Hu, **Kangkang Deng**, 2024.

# Publications

<span class="section-lead">Selected links to papers and code are provided below. Publication years follow the journal/conference year (rather than the acceptance year) whenever a final publication year is available.</span>

### Forthcoming

- [**An efficient primal dual semismooth Newton method for semidefinite programming**](https://arxiv.org/abs/2504.14333)  
  Zhanwang Deng, Jiang Hu, **Kangkang Deng**, Zaiwen Wen. *Mathematics of Operations Research*, accepted / forthcoming.

### 2026

- [**SAM-DNN: Bilevel Convergent Sequential Averaging Methods with Denoising Neural Network**](https://www.sciencedirect.com/science/article/abs/pii/S0307904X26000788)  
  Shuchang Zhang, **Kangkang Deng**, Hui Zhang, Hongxia Wang. *Applied Mathematical Modelling*, 2026.
- [**A cut-and-project perspective for linearized Bregman iterations**](https://arxiv.org/abs/2404.09776)  
  Yu-Hong Dai, **Kangkang Deng**, Hui Zhang. *IMA Journal of Numerical Analysis*, 2026.
- [**The Augmented Lagrangian Methods: Overview and Recent Advances**](https://arxiv.org/abs/2510.16827)  
  **Kangkang Deng**, Rui Wang, Zhenyuan Zhu, Junyu Zhang, Zaiwen Wen. *SIAM Review*, 2026.
- [**Stochastic ADMM with batch size adaptation for nonconvex nonsmooth optimization**](https://arxiv.org/pdf/2505.06921)  
  Jiachen Jin, **Kangkang Deng**, Boyu Wang, Hongxia Wang. *Applied Numerical Mathematics*, 2026.
- [**A Novel Riemannian Conjugate Gradient Method with Iteration Complexity Guarantees**](https://www.jaac-online.com/article/doi/10.11948/20240564)  
  Juan Zhou, **Kangkang Deng**, Hongxia Wang, Zheng Peng. *Journal of Applied Analysis and Computation*, 2026.
- [**Anderson acceleration of derivative-free projection methods for constrained monotone nonlinear equations**](https://link.springer.com/article/10.1007/s10957-025-02841-y)  
  Jiachen Jin, Hongxia Wang, **Kangkang Deng**. *Journal of Optimization Theory and Applications*, 2026.

### 2025

- [**Rethinking Gradient Step Denoiser: Towards Truly Pseudo-Contractive Operator**](https://openreview.net/pdf?id=J5XXBS6wPz)  
  Shuchang Zhang, Yaoyun Zeng, **Kangkang Deng**, Hongxia Wang. *NeurIPS 2025*, 2025.
- [**Adaptive Riemannian ADMM for Nonsmooth Optimization: Optimal Complexity without Smoothing**](https://openreview.net/pdf/5c7956363acef5755a1562c7b6c43efbf7e80be3.pdf)  
  **Kangkang Deng**, Jiachen Jin, Jiang Hu, Hongxia Wang. *NeurIPS 2025*, 2025. [Code](https://github.com/KKDeng/Adaptive-Riemannian-ADMM) <span class="pub-note">Code</span>
- [**Decentralized projected Riemannian gradient method for smooth optimization on compact submanifolds embedded in the Euclidean space**](https://link.springer.com/article/10.1007/s00211-025-01497-0)  
  **Kangkang Deng**, Jiang Hu. *Numerische Mathematik*, 2025.
- [**Oracle complexities of augmented Lagrangian methods for nonsmooth manifold optimization**](https://pubsonline.informs.org/doi/abs/10.1287/moor.2024.0498)  
  **Kangkang Deng**, Jiang Hu, Jiayuan Wu, Zaiwen Wen. *Mathematics of Operations Research*, 2025. [Code](https://github.com/KKDeng/ManIAL) <span class="pub-note">Code</span>
- [**Inexact Riemannian Gradient Descent Method for Nonconvex Optimization with Strong Convergence**](https://link.springer.com/article/10.1007/s10915-025-02913-1)  
  Juan Zhou, **Kangkang Deng***, Hongxia Wang, Zheng Peng. *Journal of Scientific Computing*, 2025.
- [**Decentralized Riemannian Natural Gradient Methods with Kronecker Product Approximations**](https://link.springer.com/article/10.1007/s40305-025-00583-2)  
  Jiang Hu, **Kangkang Deng***, Quanzheng Li. *Journal of the Operations Research Society of China*, 2025.
- [**Decentralized Projected Riemannian Stochastic Recursive Momentum Method for Nonconvex Optimization**](https://ojs.aaai.org/index.php/AAAI/article/view/33218/35373)  
  **Kangkang Deng**, Jiang Hu. *AAAI 2025*, 2025.
- [**LDPP-MIG Detectors in Sample-Starved Nonhomogeneous Clutter**](https://ieeexplore.ieee.org/abstract/document/10909414)  
  Xiaoqiang Hua, Chuanfu Xu, Zhenghua Wang, Weijian Liu, **Kangkang Deng**, Alfonso Farina, Danilo Orlando. *IEEE Transactions on Aerospace and Electronic Systems*, 2025.
- [**An augmented lagrangian primal-dual semismooth newton method for multi-block composite optimization**](https://link.springer.com/article/10.1007/s10915-025-02794-4)  
  Zhanwang Deng, **Kangkang Deng**, Jiang Hu, Zaiwen Wen. *Journal of Scientific Computing*, 2025. [Code](https://github.com/optsuite/SSNCVX) <span class="pub-note">Code</span>
- [**Achieving local consensus over compact submanifolds**](https://ieeexplore.ieee.org/abstract/document/10903988/)  
  Jiang Hu, Jiaojiao Zhang, **Kangkang Deng***. *IEEE Transactions on Automatic Control*, 2025.
- [**Decentralized Douglas-Rachford splitting methods for smooth optimization over compact submanifolds**](https://doc.global-sci.org/uploads/admin/article_pdf/20240923/2d8aa1569348748c89fc56f44cd8abd9.pdf)  
  **Kangkang Deng**, Jiang Hu, Hongxia Wang. *Journal of Computational Mathematics*, 2025.

### 2024

- [**New vector transport operators extending a Riemannian CG algorithm to generalized Stiefel manifold with low-rank applications**](https://www.sciencedirect.com/science/article/pii/S0377042724002747)  
  Xuejie Wang, **Kangkang Deng***, Zheng Peng, Chengcheng Yan. *Journal of Computational and Applied Mathematics*, 2024.
- [**Trace lasso regularization for adaptive sparse canonical correlation analysis via manifold optimization approach**](https://link.springer.com/article/10.1007/s40305-022-00449-x)  
  **Kangkang Deng**, Zheng Peng. *Journal of the Operations Research Society of China*, 2024. [Code](https://github.com/KKDeng/ASCCA) <span class="pub-note">Code</span>
- [**A projected semismooth Newton method for a class of nonconvex composite programs with strong prox-regularity**](http://www.jmlr.org/papers/v25/23-0371.html)  
  Jiang Hu, **Kangkang Deng***, Jiayuan Wu, Quanzheng Li. *Journal of Machine Learning Research*, 2024. [Code](https://github.com/KKDeng/Prox-Regular-SSN) <span class="pub-note">Code</span>
- [**High-performance placement engine for modern large-scale FPGAs with heterogeneity and clock constraints**](https://ieeexplore.ieee.org/abstract/document/10309844/)  
  Ziran Zhu, Yangjie Mei, **Kangkang Deng**, Huan He, Jianli Chen, Jun Yang, Yao-Wen Chang. *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*, 2024.

### 2023

- [**Riemannian Smoothing Gradient Type Algorithms for Nonsmooth Optimization Problem on Compact Riemannian Submanifold Embedded in Euclidean Space**](https://link.springer.com/article/10.1007/s00245-023-10061-x)  
  Zheng Peng, Weihe Wu, Jiang Hu, **Kangkang Deng***. *Applied Mathematics & Optimization*, 2023.
- [**An entropy-regularized ADMM for binary quadratic programming**](https://link.springer.com/article/10.1007/s10898-022-01144-0)  
  Haoming Liu, **Kangkang Deng**, Haoyang Liu, Zaiwen Wen. *Journal of Global Optimization*, 2023.
- [**A decomposition augmented Lagrangian method for low-rank semidefinite programming**](https://epubs.siam.org/doi/abs/10.1137/22M1474539)  
  Yifei Wang, **Kangkang Deng**, Haoyang Liu, Zaiwen Wen. *SIAM Journal on Optimization*, 2023. [Code](http://github.com/optsuite/SDPDAL) <span class="pub-note">Code</span>
- [**A manifold inexact augmented Lagrangian method for nonsmooth optimization on Riemannian submanifolds in Euclidean space**](https://academic.oup.com/imajna/article-abstract/43/3/1653/6590238)  
  **Kangkang Deng**, Zheng Peng. *IMA Journal of Numerical Analysis*, 2023. [Code](https://github.com/KKDeng/mialm_code_share) <span class="pub-note">Code</span>

### 2020

- [**A Discriminative Projection and Representation-Based Classification Framework for Face Recognition**](https://epubs.siam.org/doi/abs/10.1137/19M1253873)  
  **Kangkang Deng**, Zheng Peng, Wenxing Zhu. *SIAM Journal on Imaging Sciences*, 2020. [Code](https://github.com/KKDeng/DPRC_code) <span class="pub-note">Code</span>

# Honors & Awards

- **2025.12** · 湖南省计算数学应用软件学会青年优秀论文一等奖
- **2025.11** · 中国运筹学会数学与智能分会青年理事
- **2025.08** · 湖南省芙蓉计划青年托举
- **2025.04** · 湖南省运筹学会理事

# Invited Talks

- **2025.08** · *Iteration Complexity of Riemannian ADMM*, The First Youth Scholars Conference of the Operations Research Society, Taiyuan.
- **2025.05** · *Nonsmooth Optimization on Riemannian Manifold*, Annual Meeting of the Mathematical Programming Society of the Operations Research Society, Shanghai.
