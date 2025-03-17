---
layout: page
permalink: /team/
title: Team
description: members of the lab or group
nav: true
nav_order: 1
---

<!-- 通用样式定义 -->
<style>
.profile-grid {
  display: grid;
  gap: 1.5rem 1rem;
  padding: 1rem;
  max-width: 1200px;
  margin: 0 auto;
}

.profile-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 0.5rem;
  background: var(--global-card-bg-color);
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  height: fit-content;
  width: 100%;
  color: var(--global-text-color);
}

.profile-image {
  width: 100%;
  max-width: 150px;
  aspect-ratio: 3/4;
  height: auto;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 0.25rem;
}

.profile-name {
  font-size: 1.25rem;
  font-weight: 600;
  margin: 0.15rem 0;
  color: var(--global-theme-color);
}

.profile-social {
  display: flex;
  gap: 0.5rem;
  justify-content: center;
  flex-wrap: wrap;
  margin: 0.15rem 0;
}

.profile-social a {
  color: var(--global-text-color);
}

.profile-social a:hover {
  color: var(--global-theme-color);
}

.profile-description {
  font-size: 0.9rem;
  line-height: 1.4;
  margin: 0.15rem 0;
  color: var(--global-text-color-light);
}

/* 响应式布局类 */
.grid-1-col { grid-template-columns: repeat(1, 1fr); }
.grid-2-col { grid-template-columns: repeat(2, 1fr); }
.grid-3-col { grid-template-columns: repeat(3, 1fr); }
.grid-4-col { grid-template-columns: repeat(4, 1fr); }

@media (max-width: 992px) {
  .grid-4-col {
    grid-template-columns: repeat(3, 1fr);
  }
}

@media (max-width: 768px) {
  .grid-3-col, .grid-4-col {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .profile-grid {
    grid-template-columns: repeat(1, 1fr) !important;
  }
}
</style>

## Lab Director
<div class="profile-grid grid-1-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/HuanWang.jpg" alt="Profile"/>
    <h3 class="profile-name">Huan Wang</h3>
    <div class="profile-social">
      <a href="https://huanwang.tech/" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:wanghuan@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=0-On0y4AAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/mingsun-tse" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://www.linkedin.com/in/huanwangx" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://twitter.com/huanwangx" title="X"><i class="fa-brands fa-x-twitter"></i></a>
    </div>
    <p class="profile-description">Assistant Professor</p>
  </div>
</div>

## Postdoc researchers
<div class="profile-grid grid-3-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Xinjun Lin.jpg" alt="Profile"/>
    <h3 class="profile-name">Xinjun Lin</h3>
    <div class="profile-social">
      <a href="mailto:linxinjun@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://instagram.com/sangwanlam7" title="Instagram"><i class="fa-brands fa-instagram"></i></a>
    </div>
    <p class="profile-description">Administrative Assistant <br> CSC 2022, Intern@SISU/Alibaba/Louis Vuitton/Gagosian</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Ying Li.jpg" alt="Profile"/>
    <h3 class="profile-name">Ying Li</h3>
    <div class="profile-social">
      <a href="mailto:liying06@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <p class="profile-description">Postdoc Researchers</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Simin Xu.jpg" alt="Profile"/>
    <h3 class="profile-name">Simin Xu</h3>
    <div class="profile-social">
      <a href="mailto:xusimin@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <p class="profile-description">Postdoc Researchers</p>
  </div>
</div>

[//]: # (按照加入时间顺序排序)

## Ph.D. students

<div class="profile-grid grid-3-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Kele Shao.jpg" alt="Profile"/>
    <h3 class="profile-name">Kele Shao</h3>
    <div class="profile-social">
      <a href="https://cokeshao.github.io/" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:shaokele@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.li/citations?user=f4-ER1kAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/cokeshao" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <!-- <p class="profile-description">First profile in three-column layout.</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Keda Tao.JPEG" alt="Profile"/>
    <h3 class="profile-name">Keda Tao</h3>
    <div class="profile-social">
      <a href="https://kd-tao.github.io" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:KD.TAO@outlook.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=ek8xaLUAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/KD-TAO" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://www.linkedin.com/in/Keda Tao" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
    </div>
    <!-- <p class="profile-description">Second profile in three-column layout.</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Hesong Wang.jpg" alt="Profile"/>
    <h3 class="profile-name">Hesong Wang</h3>
    <div class="profile-social">
      <a href="https://viridisgreen.github.io" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:viridisgreen27@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/viridisGreen" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <!-- <p class="profile-description">Third profile in three-column layout.</p> -->
  </div>
</div>
## Research interns
<div class="profile-grid grid-4-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Zefang Wang.jpg" alt="Profile"/>
    <h3 class="profile-name">Zefang Wang</h3>
    <div class="profile-social">
      <a href="mailto:qw946032590@163.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/aden9460" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <!-- <p class="profile-description">Assistant Professor</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Mingluo Su.jpg" alt="Profile"/>
    <h3 class="profile-name">Mingluo Su</h3>
    <div class="profile-social">
      <a href="mailto:mingluosu0903@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <!-- <p class="profile-description">Assistant Professor</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Wenzhe Qian.JPEG" alt="Profile"/>
    <h3 class="profile-name">Wenzhe Qian</h3>
    <div class="profile-social">
      <a href="mailto:wenzheqian1021@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/WenzheQian" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <p class="profile-description">National Scholarship</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Siyong Jian.jpg" alt="Profile"/>
    <h3 class="profile-name">Siyong Jian</h3>
    <div class="profile-social">
      <a href="mailto:syjian5@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <!-- <p class="profile-description">Assistant Professor</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Haolei Bai.jpg" alt="Profile"/>
    <h3 class="profile-name">Haolei Bai</h3>
    <div class="profile-social">
      <a href="mailto:baih0011@e.ntu.edu.sg" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <p class="profile-description">Intern@A*STAR</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Haoyu Shen.jpg" alt="Profile"/>
    <h3 class="profile-name">Haoyu Shen</h3>
    <div class="profile-social">
      <a href="mailto:petershencs@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/Petershen-csworld" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <!-- <p class="profile-description">Assistant Professor</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Yufan Zhou.jpg" alt="Profile"/>
    <h3 class="profile-name">Yufan Zhou</h3>
    <div class="profile-social">
      <a href="https://wiserzhou.github.io" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:yfzhou@stu.hit.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=dNe36RoAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/WiserZhou" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>
    <p class="profile-description">National Scholarship</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Haopeng Li.png" alt="Profile"/>
    <h3 class="profile-name">Haopeng Li</h3>
    <div class="profile-social">
      <a href="https://github.com/hp-l33" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:haopeng.l33@foxmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <!-- <p class="profile-description">Assistant Professor</p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Kaiwen Tuo.jpg" alt="Profile"/>
    <h3 class="profile-name">Kaiwen Tuo</h3>
    <div class="profile-social">
      <a href="https://cfintech.github.io/" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:cfintuo@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/CFinTech" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://www.linkedin.com/in/%E5%87%AF%E6%96%87-%E6%8B%93-0824242b8" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
    </div>
    <p class="profile-description">National Scholarship </p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Zhenyu Sun.jpg" alt="Profile"/>
    <h3 class="profile-name">Zhenyu Sun</h3>
    <div class="profile-social">
      <a href="https://zhenyusun-walker.github.io/" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:sunz88313@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=ADd-qVsAAAAJ&hl" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/ZhenyuSun-Walker" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://orcid.org/0009-0004-8382-0502" title="ORCID"><i class="ai ai-orcid"></i></a>
    </div>
    <p class="profile-description">National Scholarship</p>
  </div>
</div>

## Undergraduate students

<div class="profile-grid grid-4-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Wenxi Zhu.jpg" alt="Profile"/>
    <h3 class="profile-name">Wenxi Zhu</h3>
    <div class="profile-social">
      <a href="mailto:zhuwenxi@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <!-- <p class="profile-description">Previous: Visiting Student </p> -->
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Junhan Zhu.jpg" alt="Profile"/>
    <h3 class="profile-name">Junhan Zhu</h3>
    <div class="profile-social">
      <a href="mailto:zhujunhan@westlake.edu.cn" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <!-- <p class="profile-description">Previous: Visiting Student </p> -->
  </div>
</div>

## Alumni
<div class="profile-grid grid-4-col">
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Sicheng Feng.jpg" alt="Profile"/>
    <h3 class="profile-name">Sicheng Feng</h3>
    <div class="profile-social">
      <a href="https://fscdc.github.io/" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:fscnkucs@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://scholar.google.com/citations?user=v8z7VvwAAAAJ&hl=en" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://github.com/fscdc" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://orcid.org/0009-0006-0211-0870" title="ORCID"><i class="ai ai-orcid"></i></a>
    </div>
    <p class="profile-description">Previous: Visiting Student <br> Current: Visiting student at LV Lab <br> National Scholarship</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Hanzhang Shen.jpeg" alt="Profile"/>
    <h3 class="profile-name">Hanzhang Shen</h3>
    <div class="profile-social">
      <a href="https://hanzhangshen03.github.io" title="Homepage"><i class="fa-solid fa-house"></i></a>
      <a href="mailto:shenhanzhang@outlook.com" title="email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://github.com/hanzhangshen03" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="https://www.linkedin.com/in/hanzhang-shen-747629224/" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
    </div>
    <p class="profile-description">Previous: Visiting Student <br> Current: SWE Intern at Meta</p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/Zhenxin Ai.jpg" alt="Profile"/>
    <h3 class="profile-name">Zhenxin Ai</h3>
    <div class="profile-social">
      <a href="mailto:aikunkun34@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <p class="profile-description">Previous: Visiting Student </p>
  </div>
  <div class="profile-item">
    <img class="profile-image" src="../assets/img/people/XianzuWu.jpg" alt="Profile"/>
    <h3 class="profile-name">XianzuWu</h3>
    <div class="profile-social">
      <a href="mailto:xianzuwu@gmail.com" title="email"><i class="fa-solid fa-envelope"></i></a>
    </div>
    <p class="profile-description">Previous: Research intern <br> Current: Reserch Intern at HKUST</p>
  </div>
</div>
