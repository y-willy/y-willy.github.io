---
layout: page
title: Home
permalink: /
---

<style>
  :root { --max-width: 850px; --accent:#0b66c3; --muted:#666; }
  .container-custom { font-family: "Noto Sans KR", sans-serif; line-height: 1.7; color: #333; }
  .hero { text-align: center; margin-bottom: 30px; padding: 20px 0; border-bottom: 1px solid #eee; }
  .hero h1 { margin: 0; font-size: 2.2rem; color: #111; }
  .hero p { margin: 10px 0 0; font-size: 1.1rem; font-weight: 600; color: var(--muted); }
  
  .header-row { display: flex; justify-content: space-between; align-items: flex-start; gap: 30px; margin-top: 20px; }
  .left-col { flex: 1; }
  
  /* 섹션 스타일 */
  .section { margin-bottom: 35px; }
  .section h2 { font-size: 1.4rem; color: #111; margin-bottom: 15px; display: flex; align-items: center; gap: 8px; border-bottom: 2px solid #f0f0f0; padding-bottom: 5px; }
  .section h3 { font-size: 1.1rem; margin: 15px 0 5px; color: #222; }
  
  ul { padding-left: 1.2rem; margin: 10px 0; }
  li { margin-bottom: 6px; }
  
  /* solved.ac 카드 */
  .profile-card { width: 240px; min-width: 220px; border: 1px solid #e1e4e8; padding: 20px; border-radius: 12px; background: #fcfcfc; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
  .profile-card .title { font-weight: 700; font-size: 1.1rem; margin-bottom: 5px; }
  .profile-card .tier { color: #d49819; font-weight: 600; margin-bottom: 15px; }
  .profile-link { display: inline-block; background: var(--accent); color: #fff !important; padding: 8px 12px; border-radius: 6px; text-decoration: none !important; font-size: 0.9rem; font-weight: 600; }
  
  /* 링크 스타일 */
  a { color: var(--accent); text-decoration: none; }
  a:hover { text-decoration: underline; }
  
  @media (max-width: 760px) {
    .header-row { flex-direction: column; }
    .profile-card { width: 100%; box-sizing: border-box; }
  }
</style>

<div class="container-custom">
  <div class="hero">
    <h1>황윤성 <small style="font-weight:normal; font-size:0.6em; color:#999;">(Hwang Youn-sung)</small></h1>
    <p>취약점 분석 · 보안 · Problem Solving 중심 개발자</p>
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
        <h2>🛠 기술 스택</h2>
        <ul>
          <li><strong>Language:</strong> C, C++, Python</li>
          <li><strong>System & Tools:</strong> Linux, Git</li>
          <li><strong>Problem Solving:</strong> Baekjoon (Gold IV)</li>
        </ul>
      </div>

      <div class="section">
        <h2>💻 프로젝트</h2>
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
          <li>2025 KHU 가을 프로그래밍 경시대회 장려상 — <a href="{{ site.baseurl }}/assets/2025.pdf" target="_blank"><strong>[상장 확인]</strong></a></li>
          <li>2025 후마니타스백일장 장려상 — <strong>[상장 준비중]</strong></li>
        </ul>
      </div>

      <div class="section">
        <h2>🏃 대외 활동</h2>
        <ul>
          <li><strong>버그헌팅 실습 훈련 - 초급과정 [12차]</strong> — <a href="{{ site.baseurl }}/assets/bug.pdf" target="_blank"><strong>[수료증]</strong></a>
            <br><small style="color:#666;">(2025.08.04 ~ 2025.08.16 | 웹해킹 기법 학습)</small>
          </li>
          <li><strong>성균관대 AX 사이버보안 특강</strong> <small style="color:#666;">(최신 보안 트렌드 학습)</small></li>
        </ul>
      </div>

      <div class="section">
        <h2>📌 Contact</h2>
        <ul>
          <li><strong>GitHub:</strong> <a href="https://github.com/y-willy" target="_blank">github.com/y-willy</a></li>
          <li><strong>Email:</strong> <a href="mailto:willy0723@naver.com">willy0723@naver.com</a></li>
        </ul>
      </div>

    </div>

    <aside class="profile-card">
      <div class="title">willy</div>
      <div class="tier">Solved.ac Gold IV</div>
      <p style="font-size:0.85rem; color:#666; margin-bottom:15px;">알고리즘 문제 해결 및 보안 취약점 분석에 관심이 많습니다.</p>
      <a href="https://solved.ac/profile/willy" class="profile-link" target="_blank">solved.ac 프로필</a>
    </aside>
  </div>
</div>