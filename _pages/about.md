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

<span class='anchor' id='about-me'></span>

<div class="hero-banner">
  <div class="hero-copy">
    <p class="eyebrow" lang="en">Academic Homepage</p>
    <p class="eyebrow" lang="zh">学术主页</p>

    <h1 lang="en">Luyao Niu</h1>
    <h1 lang="zh">牛璐瑶</h1>

    <p class="hero-summary" lang="en">
      PhD student in Transportation Systems at the <strong>University of Southern California (USC)</strong>, with research interests in spatio-temporal data mining, urban AI, and large language models for spatial intelligence.
    </p>
    <p class="hero-summary" lang="zh">
      现就读于<strong>南加州大学（USC）</strong>交通系统工程博士项目，研究方向为时空数据挖掘、城市人工智能以及面向空间智能的大语言模型。
    </p>

    <div class="hero-highlights" lang="en">
      <span>Trajectory analytics</span>
      <span>Causal inference</span>
      <span>LLM-enabled urban analysis</span>
      <span>Travel behavior modeling</span>
    </div>
    <div class="hero-highlights" lang="zh">
      <span>轨迹分析</span>
      <span>交通因果推断</span>
      <span>LLM 城市分析</span>
      <span>出行行为建模</span>
    </div>
  </div>

  <div class="hero-meta-card">
    <div class="meta-chip">USC</div>
    <div class="meta-chip">PKU</div>
    <div class="meta-chip">BJTU</div>
    <p lang="en">Selected publications, news, and contact details are listed below.</p>
    <p lang="zh">下方列出部分论文、最新动态与联系方式。</p>
  </div>
</div>

<div class="profile-intro-grid">
  <section class="profile-card">
    <h2 lang="en">Background</h2>
    <h2 lang="zh">教育背景</h2>
    <p lang="en">I previously completed my M.S. training in the Smart City and Big Data program at <strong>Peking University</strong> and earned my B.Sc. in Traffic Engineering, with a minor in Finance, from <strong>Beijing Jiaotong University</strong>.</p>
    <p lang="zh">我曾在<strong>北京大学</strong>智慧城市与大数据方向接受硕士阶段培养，本科毕业于<strong>北京交通大学</strong>交通工程专业（辅修金融学）。</p>
  </section>

  <section class="profile-card">
    <h2 lang="en">Research</h2>
    <h2 lang="zh">研究方向</h2>
    <p lang="en">My work focuses on <strong>spatio-temporal data mining</strong>, <strong>urban AI</strong>, and <strong>large language models for spatial intelligence</strong>.</p>
    <p lang="zh">我的研究主要聚焦于<strong>时空数据挖掘</strong>、<strong>城市人工智能</strong>与<strong>面向空间智能的大语言模型</strong>。</p>
  </section>
</div>

<div class="profile-links">
  <a class="fancy-link" href='{{ site.author.googlescholar }}'>Google Scholar</a>
  <a class="fancy-link" href="mailto:{{ site.author.email }}">Email</a>
  <a class="fancy-link" href="/publications/">Publications</a>
  <a class="fancy-link" href="/projects/">Projects</a>
</div>

<div class="news-panel">
  <h2><span lang="en">Latest News</span><span lang="zh">最新动态</span></h2>
  <div lang="en" markdown="1">
  - *2025.12*: **AskNearby** accepted at **ACM SIGSPATIAL GeoAI'25** (Oral).
  - *2025.09*: **MF-AttnBiLSTM** accepted at **IEEE GLOBECOM 2025** (Oral).
  - *2025.08*: A joint SAV–transit design paper published in **Transportation Research Part C**.
  - *2025.xx*: New manuscripts under review at **IEEE T-ITS**, **CIKM 2026**, and more.
  </div>
  <div lang="zh" markdown="1">
  - *2025.12*：**AskNearby** 被 **ACM SIGSPATIAL GeoAI'25**（Oral）接收。
  - *2025.09*：**MF-AttnBiLSTM** 被 **IEEE GLOBECOM 2025**（Oral）接收。
  - *2025.08*：一篇共享自动驾驶车—公交联合设计论文发表于 **Transportation Research Part C**。
  - *2025.xx*：多篇论文在 **IEEE T-ITS**、**CIKM 2026** 等期刊/会议审稿中。
  </div>
</div>

<div class="section-links">
  <span lang="en">See more: </span><span lang="zh">更多内容： </span>
  <a href="/publications/">Publications / 论文</a>
  <a href="/cv/">CV / 履历</a>
  <a href="/talks/">Talks / 报告</a>
  <a href="/projects/">Projects / 项目</a>
</div>
