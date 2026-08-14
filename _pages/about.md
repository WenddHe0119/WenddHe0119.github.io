---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-top: 1px;
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .submission-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }

  .spotlight {
    color: #B02418;
  }
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# Short Bio

Hi there! This is Wenwen He (何文文), I am a first-year PhD student at [The College of Computing and Data Science (CCDS) at Nanyang Technological Univeristy (NTU)](https://www.ntu.edu.sg/computing), advised by Prof. [Wei Yang Bryan Lim](https://scholar.google.com/citations?user=K2CHjf0AAAAJ&hl=en). Previously, I received my Master degree from the [Wuhan University](http://tsh.whu.edu.cn/) under the supervision of Prof. [Mang Ye](https://scholar.google.com/citations?user=j-HxRy0AAAAJ&hl=en) in 2026. If you are interested in collaborating with me or want to have a chat, always feel free to contact me through e-mail！

My research mainly focuses on **Federated Learning**, **Trustworthy AI** and **Multi-Agent System**.



# 🔥 News
<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2026.05:</em> ✨ Two papers were accepted to <strong>ICML 2026</strong>.</li>
  <li><em>2026.02:</em> ✨ Two papers were accepted to <strong>CVPR 2026</strong>.</li>
  <li><em>2025.05:</em> 🌟 SPMC was accepted to <strong>ICML 2025</strong>.</li>
</ul>
</div>

# 📝 Publications 

&dagger;: equal contribution, * : corresponding author

<hr>

<dl>
  <dt><img align="left" width="400" src="../images/paper/Batman.png" alt="Batman"></dt>
  <dd><a class="submission-title">Batman: Benign Knowledge Alignment Through Malicious Null Space in Federated Backdoor Attack</a></dd>
  <dd><strong>Wenwen He</strong>, Wenke Huang*, Yiyang Fang, Wenjie Qu, Jiaheng Zhang, Mang Ye*</dd>
  <dd>IEEE/CVF Conference on Computer Vision and Pattern Recognition  <strong>(CVPR)</strong>, 2026</dd>
</dl>

<dl>
  <dt><img align="left" width="400" src="../images/paper/SPMC.png" alt="SPMC"></dt>
  <dd><a class="publication-title">SPMC: Self-Purifying Federated Backdoor Defense via Margin Contribution</a></dd>
  <dd><strong>Wenwen He<sup>&dagger;</sup></strong>, Wenke Huang<sup>&dagger;</sup>, Bin Yang*, Shukan Liu, Mang Ye*</dd>
  <dd>International Conference on Machine Learning  <strong>(ICML)</strong>, 2025</dd>
</dl>

<hr>



<!-- <hr> -->

<!-- <dl>
  <dt><img align="left" width="400" src="../images/paper/Batman.png" alt="Batman"></dt>
  <dd><a class="submission-title">Batman: Benign Knowledge Alignment Through Malicious Null Space in Federated Backdoor Attack</a></dd>
  <dd><strong>Wenwen He</strong></dd>
  <dd>Under Review</dd>
</dl> -->

<!-- <dl>
  <dt><img align="left" width="400" src="../images/paper/FedPissa.png" alt="FedPissa"></dt>
  <dd><a class="submission-title">FedPissa: Towards Federated Personalized Adaptation of Foundation Models via LoRA Subspace Mapping</a></dd>
  <dd><strong>Wenwen He</strong></dd>
  <dd>Under Review</dd>
</dl> -->

<!-- <dl>
  <dt><img align="left" width="400" src="../images/paper/FLoRA-Chef.png" alt="FLoRA-Chef"></dt>
  <dd><a class="submission-title">FLoRA-Chef: Making A Good LoRA Recipe in Federated Generalization</a></dd>
  <dd><strong>Wenwen He</strong></dd>
  <dd>Under Review</dd>
</dl> -->

<!-- <hr> -->


# 📖 Educations

- *2024.08 - now*, PhD Student, Nanyang Technological University, Singapore.
- *2024.09 - 2026.06*, Master Student, School of National Cybersecurity, Wuhan University, China.
- *2020.09 - 2024.06*, Bachelor, School of Computer Science and Technology, Guangdong University of Technology, China.
