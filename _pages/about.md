---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="intro-card">
<p>Hi, I am <strong>Yunfan Gao</strong>, a <a href="https://www.digitalfutures.kth.se/">Digital Futures Postdoctoral Fellow</a> in the Department of Robotics, Perception and Learning (<a href="https://www.kth.se/rpl/">RPL</a>) at KTH Royal Institute of Technology, where I work with <a href="https://www.kth.se/profile/dani">Prof. Danica Kragic Jensfelt</a> and <a href="https://people.kth.se/~dimos/">Prof. Dimos V. Dimarogonas</a>.</p>
<p>From March 2022 to June 2026 I was a PhD student at the University of Freiburg under the academic supervision of <a href="https://www.syscop.de/people/moritz-diehl">Prof. Moritz Diehl</a>, and simultaneously, until September 2025, an industrial PhD student at <a href="https://www.bosch.com/research/bcai/">Bosch Center for AI</a>, under the industrial supervision of Dr. Niels van Duijkeren. Previously, I obtained my master's degree in Robotics, Systems and Control from ETH Zurich in 2022 and my bachelor's degree in Electronic Engineering from Fudan University in 2019.</p>
<p>My research interests include:</p>
<div class="tag-row">
  <span>Motion Planning</span>
  <span>Model Predictive Control</span>
  <span>Robust Optimization</span>
</div>
</div>

<h2 class="section-title" id="research-highlights">Research Highlights</h2>

<div class="highlight-card">
  <p class="highlight-card__text">Using LiDAR point clouds directly as the environment representation, the controller navigates narrow corridors and adapts seamlessly to changes of the environment.</p>
  <video autoplay muted loop playsinline>
    <source src="https://yf-gao.github.io/images/pointcloud-SIP.mp4" type="video/mp4">
  </video>
  <p class="highlight-card__more">See details in <a href="publications#item-Gao2026">Semi-Infinite Programming for Collision-Avoidance in Optimal and Model Predictive Control</a>.</p>
</div>

<div class="highlight-card">
  <p class="highlight-card__text">Collision avoidance between two ellipsoids can be formulated using an over-approximation of the Minkowski sum of the two ellipsoids.</p>
  <video autoplay muted loop playsinline>
    <source src="https://yf-gao.github.io/images/EllipsoidMinkowskiSum.mp4" type="video/mp4">
  </video>
  <p class="highlight-card__more">See details in <a href="publications#item-Gao2024b">Real-Time-Feasible Collision-Free Motion Planning For Ellipsoidal Objects</a>.</p>
</div>

<div class="highlight-card">
  <p class="highlight-card__text">Collision-free motion planning is robustified while maintaining real-time feasibility using zero-order robust optimization (zoRO).</p>
  <video autoplay muted loop playsinline>
    <source src="https://yf-gao.github.io/images/zoRO.mp4" type="video/mp4">
  </video>
  <p class="highlight-card__more">See details in <a href="publications#item-Gao2023">Collision-free Motion Planning for Mobile Robots by Zero-order Robust Optimization-based MPC</a> and <a href="publications#item-Frey2024">Efficient Zero-Order Robust Optimization for Real-Time MPC with acados</a>.</p>
</div>

<h2 class="section-title" id="selected-publications">Selected Publications</h2>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Semi-Infinite Programming for Collision-Avoidance in Optimal and Model Predictive Control</div>
    <div class="pub-authors"><b>Yunfan Gao</b>, Florian Messerer, Niels van Duijkeren, Rashmi Dabir, Moritz Diehl</div>
    <div class="pub-venue"><span class="pub-badge">T-RO'26</span> IEEE Transactions on Robotics, vol. 42, pp. 2399–2418, 2026</div>
    <div class="pub-links">
      <button type="button" class="bib-toggle" data-bib="bib-Gao2026">BibTeX</button>
      <a href="https://arxiv.org/pdf/2508.12335">paper</a>
      <a href="https://github.com/boschresearch/sip_optimal_control">code</a>
    </div>
    <div class="bib" id="bib-Gao2026"><pre>@Article{Gao2026,
  author    = {Gao, Yunfan and Messerer, Florian and van Duijkeren, Niels and Dabir, Rashmi and Diehl, Moritz},
  journal   = {IEEE Transactions on Robotics},
  title     = {Semi-Infinite Programming for Collision Avoidance in Optimal and Model-Predictive Control},
  year      = {2026},
  issn      = {1941-0468},
  pages     = {2399--2418},
  volume    = {42},
  doi       = {10.1109/tro.2026.3686181},
}</pre></div>
  </div>
</div>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Real-Time-Feasible Collision-Free Motion Planning For Ellipsoidal Objects</div>
    <div class="pub-authors"><b>Yunfan Gao</b>, Florian Messerer, Niels van Duijkeren, Boris Houska, Moritz Diehl</div>
    <div class="pub-venue"><span class="pub-badge">CDC'24</span> Proc. of the IEEE Conf. on Decision and Control, 2024</div>
    <div class="pub-links">
      <button type="button" class="bib-toggle" data-bib="bib-Gao2024b">BibTeX</button>
      <a href="http://www.arxiv.org/pdf/2409.12007">paper</a>
      <a href="https://github.com/boschresearch/ca_motion_planning_optimal_control">code</a>
    </div>
    <div class="bib" id="bib-Gao2024b"><pre>@inproceedings{Gao2024b,
  title     = {Real-Time-Feasible Collision-Free Motion Planning For Ellipsoidal Objects},
  author    = {Yunfan Gao and Florian Messerer and Niels van Duijkeren and Boris Houska and Moritz Diehl},
  booktitle = {Proc. of the IEEE Conf. on Decision and Control (CDC)},
  year      = {2024}
}</pre></div>
  </div>
</div>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Efficient Zero-Order Robust Optimization for Real-Time Model Predictive Control with acados</div>
    <div class="pub-authors">Jonathan Frey, <b>Yunfan Gao</b>, Florian Messerer, Amon Lahr, Melanie N. Zeilinger, Moritz Diehl</div>
    <div class="pub-venue"><span class="pub-badge">ECC'24</span> Proc. of the European Control Conf., 2024</div>
    <div class="pub-links">
      <button type="button" class="bib-toggle" data-bib="bib-Frey2024">BibTeX</button>
      <a href="https://publications.syscop.de/Frey2024.pdf">paper</a>
    </div>
    <div class="bib" id="bib-Frey2024"><pre>@inproceedings{Frey2024,
  year      = {2024},
  booktitle = {Proc. of the European Control Conf. (ECC)},
  author    = {Jonathan Frey and Yunfan Gao and Florian Messerer and Amon Lahr and Melanie N Zeilinger and Moritz Diehl},
  title     = {Efficient Zero-Order Robust Optimization for Real-Time Model Predictive Control with acados},
}</pre></div>
  </div>
</div>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Collision-free Motion Planning for Mobile Robots by Zero-order Robust Optimization-based MPC</div>
    <div class="pub-authors"><b>Yunfan Gao</b>, Florian Messerer, Jonathan Frey, Niels van Duijkeren, Moritz Diehl</div>
    <div class="pub-venue"><span class="pub-badge">ECC'23</span> Proc. of the European Control Conf., 2023</div>
    <div class="pub-links">
      <button type="button" class="bib-toggle" data-bib="bib-Gao2023">BibTeX</button>
      <a href="https://publications.syscop.de/Gao2023.pdf">paper</a>
    </div>
    <div class="bib" id="bib-Gao2023"><pre>@inproceedings{Gao2023,
  year      = {2023},
  booktitle = {Proc. of the European Control Conf. (ECC)},
  author    = {Yunfan Gao and Florian Messerer and Jonathan Frey and Niels van Duijkeren and Moritz Diehl},
  title     = {Collision-free Motion Planning for Mobile Robots by Zero-order Robust Optimization-based MPC},
}</pre></div>
  </div>
</div>

<p class="pub-more"><a href="/publications/">See all publications &rarr;</a></p>
