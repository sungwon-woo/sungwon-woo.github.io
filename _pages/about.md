---
title: ''
permalink: /
layout: home
author_profile: true
selected_papers: true
redirect_from: 
  - /about/
  - /about.html

preprints:
  - title: "Prior-Constrained Explorative Guidance for Diffusion Motion Planning"
    authors: "—"
    venue: "Submitted to ICRA 2026 (Under double-blind review)"
    img: /images/PCEG.gif
  - title: "Multi-Objective DRL for Eco-Friendly AMoD Fleet Rebalancing"
    authors: "—"
    venue: "Submitted to AAMAS 2026 (Under double-blind review)"
    img: /images/drl_rideshare.gif


---

## about me
I am an alum of Sogang University, where I earned a Master's degree in Artificial Intelligence with a specialization in Computer Vision in 2025, and a Bachelor's degree in Computer Science and Engineering at 2023.
<!-- My previous research focuses on image retrieval and visual copy detection, as well as in the development of lightweight neural networks. Recently, I am pursuing strong interest in visual continual learning with a data-constrained environment.  -->

## news
- **Aug 2025**: Graduated from Sogang University with a Master's degree in Artificial Intelligence.
- **Jul 2025**: Our paper is accepted as a poster at ICCV 2025 workshop on Continual Learning in Computer Vision.
- **Nov 2024**: Our paper is accepted as a poster in WACV 2025.
- **Aug 2024**: I have been granted as a visiting scholar at CMU hosted by IITP.

## selected publications
- **Neural Collapse-Driven, Uncertainty-Aware Framework for Few-Shot Class-Incremental Learning** [[paper]](https://drive.google.com/file/d/1vA2BNZxMgJ7aVPw_HE4tprMWLa5eWo5u/view?usp=drive_link)  
**Sungwon Woo**  
**M.S. Thesis**, Sogang University

- **Does Prior Data Matter? Exploring Joint Training in the Context of Few-Shot Class-Incremental Learning** [[paper]](https://arxiv.org/pdf/2503.10003)  
Shiwon Kim\*, Dongjun Hwang\*, **Sungwon Woo***, Rita Singh+ **(*co-first author)**  
**<span style="color: #2196F3;">CLVision Workshop at ICCV'25</span>

- **Relational Self-supervised Distillation with Compact Descriptors for Image Copy Detection** [[paper]](https://openaccess.thecvf.com/content/WACV2025/papers/Kim_Relational_Self-Supervised_Distillation_with_Compact_Descriptors_for_Image_Copy_Detection_WACV_2025_paper.pdf)  
Juntae Kim\*, **Sungwon Woo***, Jongho Nang+ **(*co-first author)**  
**<span style="color: #2196F3;">WACV'25</span>

## Preprints
<ul class="teaser-tiles">
{% for x in page.preprints %}
  <li class="teaser-tile">
    {% if x.img %}<img class="teaser" src="{{ x.img | relative_url }}" alt="{{ x.title }}">{% endif %}
    <div class="teaser-meta">
      <div class="teaser-title">{{ x.title }}</div>
      {% if x.authors %}<div class="teaser-authors">{{ x.authors }}</div>{% endif %}
      {% if x.venue %}<div class="teaser-venue">{{ x.venue }}</div>{% endif %}
    </div>
  </li>
{% endfor %}
</ul>

## Education

- **M.S. in Department of Artificial Intelligence**, Sogang University, Mar.2023 - Aug.2025  
  - Advisor: Jongho Nang
  - Thesis: Neural Collapse-Driven, Uncertainty-Aware Framework for Few-Shot Class-Incremental Learning
- **B.S. in Department of Computer Science and Engineering**, Sogang University, Mar.2017 - Feb.2023

## Experience
- **Visiting Student at Carnegie Mellon Univeristy**, Aug.2024 - Feb.2025
  - Sponsored by Institute of Information & Communications Technology Planning & Evaluation (IITP)
  - Achieved 2nd place (2/34) in the Best Student Award

## Awards & Scholarship
  - Smilegate AI Major (DHE) Scholarship, Smilegate, Mar.2023 - Aug.2025
  - 5th place on Video Similarity Challenge, CVPRW2023, VCDW by META Jan.2023 - Mar.2023
  - 4th place on Food Classification Challenge, KT GenieLabs Aug.2022 - Sep.2022