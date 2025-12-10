---
layout: page
title: "About Mw"
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
      [Department of Physics, University of Seoul]<br><br>
      Email: <a href="mailto:[mike1919@naver.com]">[mike1919@naver.com]</a><br>
      <GitHub: <a href="https://github.com/koohm1919" target="_blank">koohm1919</a><br>>
      <!-- 필요 없으면 아래 줄은 지우세요 -->
    </div>
  </div>

  <!-- 오른쪽: 경력 / 학력 / 연구분야 -->
  <div class="about-right">
    <div class="about-section-title">Educations</div>
    <ul class="about-list">
      <li>
        <div class="talk-date">[2019 - 2025]</div>
        <div class="talk-icon">🔖</div>
        <div class="talk-text"><b>Ph.D.</b>, University of Seoul</div>
      </li>
      <li>
        <div class="talk-date">[2013 - 2019]</div>
        <div class="talk-icon">🔖</div>
        <div class="talk-text"><b>B.S.</b>, University of Seoul</div>
      </li>
      <!-- 필요하면 더 추가 -->
    </ul>
    <div class="about-section-title">Research Interests</div>
    <ul class="about-list">
      <li>
        <div class="talk-date">General</div>
        <div class="talk-icon">🔖</div>
        <div class="talk-text">Black Hole, Cosmology, Dark Matter, Gravitational Waves</div>
      </li>
      <li>
        <div class="talk-date">Specific</div>
        <div class="talk-icon">🔖</div>
        <div class="talk-text">Ultralight Scalar Field Dark Matter, Black Hole Superradiance, Cosmological Perturbation Theory, Galactic Dynamics, Stochastic Gravitational Wave Background (First-Order Phase Transition, Inflation, Supermassive Black Hole Binary...), Preheating, CMB</div>
      </li>
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

.talk-list {
  max-width: 900px;
}

.talk-row {
  display: grid;
  grid-template-columns: 6rem 1.5rem auto; /* 날짜 / 아이콘 / 내용 */
  column-gap: 0.6rem;
  margin-bottom: 0.25rem;
}

.talk-date {
  font-style: italic;
  white-space: nowrap;
}

.talk-icon {
  text-align: center;
}

.talk-text {
  line-height: 1.3;
}

</style>
