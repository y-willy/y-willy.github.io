---
layout: page
title: Home
permalink: /
---

<style>
  .container-custom { line-height: 1.6; color: #ced4da; }
  .hero { text-align: center; margin-bottom: 2rem; }
  .hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; color: #fff; }
  .hero p { color: #adb5bd; font-size: 1.1rem; }

  .header-row { display: flex; justify-content: space-between; gap: 2rem; }
  .left-col { flex: 1; }
  
  /* 섹션 스타일 */
  .section { margin-bottom: 2rem; border-bottom: 1px solid #495057; padding-bottom: 1rem; }
  .section h2 { font-size: 1.5rem; color: #fff; margin-bottom: 1rem; display: flex; align-items: center; border: none; }
  .section h3 { font-size: 1.2rem; color: #e9ecef; margin: 1rem 0 0.5rem; }
  
  ul { list-style: disc; padding-left: 1.5rem; }
  li { margin-bottom: 0.5rem; }
  strong { color: #fff; }

  /* solved.ac 카드 */
  .profile-card { width: 260px; min-width: 240px; border: 1px solid #495057; padding: 1.5rem; border-radius: 10px; background: #212529; height: fit-content; }
  .profile-card .name { font-weight: bold; font-size: 1.1rem; margin-bottom: 0.5rem; color: #fff; }
  .profile-card .tier { color: #fab005; font-weight: 600; margin-bottom: 1rem; }
  .profile-btn { display: block; text-align: center; background: #0b66c3; color: #fff !important; padding: 0.6rem; border-radius: 5px; text-decoration: none !important; font-weight: bold; }

  @media (max-width: 768px) {
    .header-row { flex-direction: column; }
    .profile-card { width: 100%; }
  }
</style>

<div class="container-custom">
  <div class="hero">
    <h1>황윤성 <small style="font-size: 0.6em; color: #868e96;">(Hwang Youn-sung)</small></h1>
    <p> 취약점 분석 · 보안 · Problem Solving 중심 개발자</p>
  </div>

  <div class="header-row">
    <div class="left-col">
      
      <div class="section">
        <h2>🎓 학력</h2>
        <ul>
          <li><strong>경희대학교 / 컴퓨터공학과</strong> (2023.03 ~ 현재)</li>
          <li><strong>인하대학교 / 통계학과</strong> (2022.03 ~ 2022.12)</li>
        </ul>
      </div>

      <div class="section">
        <h2>기술 스택</h2>
        <ul>
          <li><strong>Language:</strong> C, C++, Python</li>
          <li><strong>OSINT,FSB </strong> </li>
          <li><strong>System & Tools:</strong> Linux, Git</li>
          <li><strong>Problem Solving:</strong> Baekjoon (Gold IV)</li>

        </ul>
      </div>

      <div class="section">
        <h2>프로젝트</h2>
        <h3>대한민국 국민들의 여가활동 데이터 분석</h3>
        <ul>
          <li><strong>기간:</strong> 2023.04 ~ 2023.06</li>
          <li><strong>설명:</strong> KOSIS 데이터를 활용한 문화활동 참여 및 선호도 분석</li>
          <li><strong>기술:</strong> Python, Pandas, Matplotlib</li>
          <li><strong>성과:</strong> 데이터 전처리 및 통계적 가설 검정 경험</li>
        </ul>
      </div>

      <div class="section">
        <h2>🏆 수상 경력</h2>
        <ul>
          <li>2025 KHU 가을 프로그래밍 경시대회 장려상 — <a href="/assets/2025.pdf" target="_blank" style="color: #4dabf7;"><strong>[상장 확인]</strong></a></li>
          <li>2025 후마니타스백일장 장려상 — <span style="color: #868e96;">[준비중]</span></li>
        </ul>
      </div>

      <div class="section">
        <h2>대외 활동</h2>
        <ul>
          <li><strong>버그헌팅 실습 훈련 - 초급과정 [12차]</strong> — <a href="/assets/bug.pdf" target="_blank" style="color: #4dabf7;"><strong>[수료증]</strong></a></li>
          <li><strong>성균관대 AX 사이버보안 특강</strong> (최신 보안 트렌드 학습)</li>
        </ul>
      </div>

      <div class="section" style="border: none;">
        <h2>📌 Contact</h2>
        <ul>
          <li><strong>GitHub:</strong> <a href="https://github.com/y-willy" target="_blank" style="color: #4dabf7;">github.com/y-willy</a></li>
          <li><strong>Email:</strong> <a href="mailto:willy0723@naver.com" style="color: #4dabf7;">willy0723@naver.com</a></li>
        </ul>
      </div>

    </div>

    <aside class="profile-card">
      <div class="name">willy · solved.ac</div>
      <div class="tier">Gold IV</div>
      <p style="font-size: 0.9rem; color: #adb5bd; margin-bottom: 1.5rem;"> 알고리즘 및 보안 취약점 분석에 관심이 많습니다.</p>
      <a href="https://solved.ac/profile/willy" class="profile-btn" target="_blank">프로필 보기</a>
    </aside>
  </div>
</div>
