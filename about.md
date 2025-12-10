---
layout: page
title: "About"
permalink: /about/
---



<div class="about-container">

  <!-- 왼쪽: 사진 + 연락처 -->
  <div class="about-left">
    <!-- 프로필 사진 경로만 바꿔 주세요 -->
    <img src="/images/Profile.jpg" alt="Hyeonmo Koo">

    <div class="about-name">
      Hyeonmo Koo
    </div>

    <div class="about-contact">
      Ph.D. Candidate in Physics<br>
      [Department of Physics, Your University]<br><br>

      Email: <a href="mailto:[your_email]">[your_email]</a><br>
      GitHub: <a href="https://github.com/koohm1919" target="_blank">koohm1919</a><br>
      <!-- 필요 없으면 아래 줄은 지우세요 -->
      Research Profiles: <a href="[arxiv_or_inspire_link]" target="_blank">arXiv / INSPIRE</a>
    </div>
  </div>

  <!-- 오른쪽: 경력 / 학력 / 연구분야 -->
  <div class="about-right">
    <div class="about-section-title">Academic Affiliations</div>
    <ul class="about-list">
      <li>
        [20XX – present] <b>Ph.D. Candidate</b>, Department of Physics, [Your University]
      </li>
      <li>
        [20XX – 20XX] <b>Research Assistant</b>, [Group or Institute], [Location]
      </li>
      <!-- 필요하면 더 추가 -->
    </ul>

    <div class="about-section-title">Education</div>
    <ul class="about-list">
      <li>
        [Expected Feb. 20XX] <b>Ph.D.</b> in Physics, [Your University]
      </li>
      <li>
        [Year] <b>B.S.</b> in Physics, [Your University]
      </li>
    </ul>

    <div class="about-section-title">Research Interests</div>
    <ul class="about-list">
      <li>Ultralight / fuzzy dark matter and self-interacting ULDM</li>
      <li>Dynamical friction in wave-like dark matter halos</li>
      <li>Supermassive black hole binaries and the final-parsec problem</li>
      <li>Head-on collisions and dynamics of dark matter subhalos</li>
      <li>Astrophysical and cosmological probes of dark matter microphysics</li>
    </ul>
  </div>

</div>
<style>
.about-container {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: flex-start;
}

.about-left {
  flex: 0 0 220px;
  text-align: center;
}

.about-left img {
  width: 100%;
  max-width: 220px;
  border-radius: 4px;
}

.about-name {
  font-weight: 700;
  margin-top: 0.8rem;
}

.about-contact {
  font-size: 0.9rem;
  line-height: 1.4;
  margin-top: 0.5rem;
}

.about-contact a {
  text-decoration: none;
}

.about-right {
  flex: 1 1 260px;
  min-width: 260px;
}

.about-section-title {
  font-weight: 700;
  margin-top: 0.5rem;
  margin-bottom: 0.4rem;
  font-size: 1.05rem;
}

.about-list {
  list-style-type: square;
  padding-left: 1.2rem;
  margin-top: 0.2rem;
  margin-bottom: 0.8rem;
}

.about-list li {
  margin-bottom: 0.25rem;
}
</style>
