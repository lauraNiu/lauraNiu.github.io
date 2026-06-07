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

<span lang="en" markdown="1">
Hi, I'm **Luyao Niu (牛璐瑶)**.
</span>
<span lang="zh" markdown="1">
你好，我是**牛璐瑶**。
</span>

<span lang="en" markdown="1">
I am a PhD student in Transportation Systems at the **University of Southern California (USC)**. I earned my B.Sc. in Traffic Engineering, with a minor in Finance, from **Beijing Jiaotong University**, and completed my M.S. training in the Smart City and Big Data program at **Peking University**.
</span>
<span lang="zh" markdown="1">
我现为**南加州大学（USC）**交通系统工程博士生，曾在**北京大学**智慧城市与大数据方向接受硕士阶段培养，本科毕业于**北京交通大学**交通工程专业（辅修金融学）。
</span>

<span lang="en" markdown="1">
My research focuses on **spatio-temporal data mining, urban AI, and large language models for spatial intelligence**. I am particularly interested in trajectory analytics, causal inference in transportation, LLM-enabled urban analysis, and travel-behavior modeling.
</span>
<span lang="zh" markdown="1">
我的研究主要聚焦于**时空数据挖掘、城市人工智能（Urban AI）与面向空间智能的大语言模型**，尤其关注轨迹分析、交通因果推断、LLM 驱动的城市分析以及出行行为建模。
</span>

<span lang="en" markdown="1">
Selected publications and updates are available on <a href='{{ site.author.googlescholar }}'>Google Scholar</a> <a href='{{ site.author.googlescholar }}'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. For correspondence, feel free to reach me at <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>.
</span>
<span lang="zh" markdown="1">
更多论文与动态可见我的 <a href='{{ site.author.googlescholar }}'>Google Scholar</a> <a href='{{ site.author.googlescholar }}'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。如需联系，欢迎邮件交流：<a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>。
</span>


# <span lang="en">🔥 News</span><span lang="zh">🔥 最新动态</span> {#news}
<div lang="en" markdown="1">
- *2025.12*: &nbsp;🎉 **AskNearby** accepted at **ACM SIGSPATIAL GeoAI'25** (Oral).
- *2025.09*: &nbsp;🎉 **MF-AttnBiLSTM** accepted at **IEEE GLOBECOM 2025** (Oral).
- *2025.08*: &nbsp;🎉 Our joint SAV–transit design paper is published in **Transportation Research Part C**.
- *2025.xx*: &nbsp;📝 New manuscripts under review at **IEEE T-ITS**, **CIKM 2026**, and more.
</div>
<div lang="zh" markdown="1">
- *2025.12*：&nbsp;🎉 **AskNearby** 被 **ACM SIGSPATIAL GeoAI'25**（Oral）接收。
- *2025.09*：&nbsp;🎉 **MF-AttnBiLSTM** 被 **IEEE GLOBECOM 2025**（Oral）接收。
- *2025.08*：&nbsp;🎉 共享自动驾驶车—公交联合设计论文发表于 **Transportation Research Part C**。
- *2025.xx*：&nbsp;📝 多篇论文在 **IEEE T-ITS**、**CIKM 2026** 等期刊/会议审稿中。
</div>

<div lang="en" markdown="1">
See more: [Publications](/publications/) · [CV](/cv/) · [Talks](/talks/) · [Projects](/projects/)
</div>
<div lang="zh" markdown="1">
更多内容：[论文](/publications/) · [履历](/cv/) · [报告](/talks/) · [项目](/projects/)
</div>
