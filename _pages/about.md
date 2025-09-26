---
title: ''
permalink: /
author_profile: true
selected_papers: true
redirect_from: 
  - /about/
  - /about.html
---

## about me
I am an alum of Sogang University, where I earned a Master's degree in Artificial Intelligence with a specialization in Computer Vision in 2025, and a Bachelor's degree in Computer Science and Engineering at 2023.
<!-- My previous research focuses on image retrieval and visual copy detection, as well as in the development of lightweight neural networks. Recently, I am pursuing strong interest in visual continual learning with a data-constrained environment.  -->

## news
- **Aug 2025**: Graduated from Sogang University with a Master's degree in Artificial Intelligence.
- **Jul 2025**: One paper is accepted as a poster at ICCV 2025 workshop on Continual Learning in Computer Vision.
- **Nov 2024**: One paper is accepted as a poster in WACV 2025.
- **Aug 2024**: I have been granted as a visiting scholar at CMU hosted by IITP.

## selected publications
<!-- - **Neural Collapse-Driven, Uncertainty-Aware Framework for Few-Shot Class-Incremental Learning** [[paper]](https://drive.google.com/file/d/1vA2BNZxMgJ7aVPw_HE4tprMWLa5eWo5u/view?usp=drive_link)  
**Sungwon Woo**  
**M.S. Thesis**, Sogang University

- **Does Prior Data Matter? Exploring Joint Training in the Context of Few-Shot Class-Incremental Learning** [[paper]](https://arxiv.org/pdf/2503.10003)  
Shiwon Kim\*, Dongjun Hwang\*, **Sungwon Woo***, Rita Singh+ **(*co-first author)**  
**<span style="color: #2196F3;">CLVision Workshop at ICCV'25</span>

- **Relational Self-supervised Distillation with Compact Descriptors for Image Copy Detection** [[paper]](https://openaccess.thecvf.com/content/WACV2025/papers/Kim_Relational_Self-Supervised_Distillation_with_Compact_Descriptors_for_Image_Copy_Detection_WACV_2025_paper.pdf)  
Juntae Kim\*, **Sungwon Woo***, Jongho Nang+ **(*co-first author)**  
**<span style="color: #2196F3;">WACV'25</span> -->

<ul class="pub-list">
{%- assign pubs = site.publications | sort: "date" | reverse -%}
{%- for p in pubs limit: 6 -%}
  <li class="pub-item">
    <div class="pub-thumb">
      {% if p.header.teaser %}
        <img src="{{ p.header.teaser | relative_url }}" alt="{{ p.title | escape }}">
      {% endif %}
    </div>

    <div class="pub-meta">
      <div class="pub-title" style="font-weight: normal; color:#333333;">
        {{ p.title }}
      </div>

      {% if p.authors %}<div class="pub-authors">{{ p.authors }}</div>{% endif %}
      {% if p.venue %}<div class="pub-venue"><em>{{ p.venue }}</em></div>{% endif %}

      {% if p.tags %}
      <div class="tag-list">
        {% for tag in p.tags %}
          <span class="tag-pill"
            style="display:inline-flex; align-items:center; gap:4px;
                   padding:3px 8px; border:1px solid rgba(0,0,0,.15);
                   border-radius:999px; font-size:.8em; margin-right:6px; color:#00BFFF;">
            <i class="fas fa-tag"></i>
            #{{ tag }}
          </span>
        {% endfor %}
      </div>
      {% endif %}

      {% if post.buttons %}
      <p style="font-size: 0.9em; margin-top: 0.2rem; margin-bottom: 0;">
        {% for btn in post.buttons %}
        <a href="{{ btn.url }}" target="_blank" style="margin-right: 0.8rem; text-decoration: none;">
          {% if btn.type == "paper" %}📄 Paper{% endif %}
          {% if btn.type == "video" %}🎥 Video{% endif %}
          {% if btn.type == "code" %}💻 Code{% endif %}
          {% if btn.type == "website" %}🌐 Website{% endif %}
          {% if btn.type == "presentation" %}🖥️ Slides{% endif %}
        </a>
        {% endfor %}
      </p>
      {% endif %}
    </div>
  </li>
{%- endfor -%}
</ul>

## selected projects
<ul class="pub-list">
{%- assign projs = site.projects | where: "selected", true | sort: "date" | reverse -%}
{%- for p in projs -%}
  <li class="pub-item">
    <div class="pub-thumb">
      {% if p.header.teaser %}
        <img src="{{ p.header.teaser | relative_url }}" alt="{{ p.title | escape }}">
      {% endif %}
    </div>

    <div class="pub-meta">
      <!-- 제목: 링크 제거 + 색상 적용 -->
      <div class="pub-title" style="font-weight: normal; color:#333333;">
        {{ p.title }}
      </div>

      {% if p.period %}<div class="pub-venue">{{ p.period }}</div>{% endif %}
      {% if p.description %}
        <div class="pub-authors">{{ p.description }}</div>
      {% elsif p.summary %}
        <div class="pub-authors">{{ p.summary }}</div>
      {% elsif p.excerpt %}
        <div class="pub-authors">{{ p.excerpt | strip_html | truncate: 180 }}</div>
      {% endif %}

      {% if p.tags %}
      <div class="tag-list">
        {% for tag in p.tags %}
          <span class="tag-pill"
             style="display:inline-flex; align-items:center; gap:4px;
                    padding:3px 8px; border:1px solid rgba(0,0,0,.15);
                    border-radius:999px; font-size:.8em; margin-right:6px; color:#00BFFF;">
            <i class="fas fa-tag"></i>
            #{{ tag }}
          </span>
        {% endfor %}
      </div>
      {% endif %}

      {% if p.links %}
      <div class="pub-links">
        {% for L in p.links %}
          <a href="{{ L.url }}" target="_blank" rel="noopener">{{ L.label }}</a>
        {% endfor %}
      </div>
      {% endif %}
    </div>
  </li>
{%- endfor -%}
</ul>

## Education

- **M.S. in Department of Artificial Intelligence**, Sogang University, Mar.2023 - Aug.2025  
  - Thesis: Neural Collapse-Driven, Uncertainty-Aware Framework for Few-Shot Class-Incremental Learning
- **B.S. in Department of Computer Science and Engineering**, Sogang University, Mar.2017 - Feb.2023

## Experience
- **Visiting Student at Carnegie Mellon Univeristy**, Aug.2024 - Feb.2025
  - Sponsored by Institute of Information & Communications Technology Planning & Evaluation (IITP)
  - Achieved <b>2nd place (2/34)</b> in the Best Student Award
- **Student Researcher at Smilegate**, June.2024 - Jul.2024

## Awards & Scholarship
  - Smilegate AI Major (DHE) Scholarship, Smilegate, Mar.2023 - Aug.2025
  - 5th place on Video Similarity Challenge, CVPRW2023, VCDW by META Jan.2023 - Mar.2023
  - 4th place on Food Classification Challenge, KT GenieLabs Aug.2022 - Sep.2022