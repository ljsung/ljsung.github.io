---
layout: about
image: /assets/img/blog/hydejack-9.jpg
description: >
  A boutique Jekyll theme for hackers, nerds, and academics,
  with a focus on personal sites that are meant to impress.
hide_description: true
redirect_from:
  - /download/
---

# About

<!--author-->

<html lang="ko">
<head>
<meta charset="UTF-8">


<style>
  body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    background: #f7f7f7;
    margin: 0;
    padding: 40px;
    color: #333;
  }
  .skills-container {
    max-width: 680px;
    margin: 20px auto;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  .skill {
    margin: 20px 0;
  }
  .skill-name {
    font-size: 16px;
    color: #333;
    margin-bottom: 5px;
    letter-spacing: 1px
  }
  .skill-bar {
    background-color: #eaeaea;
    border-radius: 4px;
    height: 10px;
    width: 100%;
    position: relative;
  }
  .skill-percentage {
    background-color: #4caf50;
    height: 10px;
    border-radius: 4px;
    width: 0;
    transition: width 1s ease;
    position: absolute;
  }
  .percentage-label {
    position: absolute;
    right: 10px;
    top: -25px;
    color: #333;
    font-size: 14px;
    white-space: nowrap;
  }
   table tr {
    background-color: #fff; 
  }
</style>
</head>
<body>

<div class="education-container">
  <div class="title">학력</div>
  <table>
    <tr>
      <th>학교</th>
      <th>전공</th>
      <th>기간</th>
    </tr>
    <tr>
      <td>수원과학대학교</td>
      <td>컴퓨터정보</td>
      <td>2019년 3월 - 2023년 3월</td>
    </tr>
    <!-- 다른 학력 정보를 이곳에 추가할 수 있습니다. -->
  </table>
</div>

<div class="title">경력</div>
  <table>
    <tr>
      <th>교육명</th>
      <th>기간</th>
    </tr>
    <tr>
      <td>인공지능 프로젝트 부트캠프(AI협업)</td>
      <td>2023년 9월 - 2023년 11월</td>
    </tr>
    <tr>
      <td>응용sw 개발(자바,리액트 기반 프로젝트)</td>
      <td>2022년 12월 - 2023년 7월</td>
    </tr>
    <!-- 추가적인 경력 정보를 이곳에 추가할 수 있습니다. -->

  </table>

<h2>보유 기술</h2>

<title>보유 기술</title>

  <div class="skills-container">
    <!-- Skill Item -->
    <div class="skill">
      <div class="skill-name">Java</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 90%;" data-value="90%"></div>
        <div class="percentage-label">90%</div>
      </div>
    </div>
    <!-- Repeat for other skills -->
    <div class="skill">
      <div class="skill-name">React</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 85%;" data-value="85%"></div>
        <div class="percentage-label">85%</div>
      </div>
    </div>
    <div class="skill">
      <div class="skill-name">Spring Boot</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 80%;" data-value="80%"></div>
        <div class="percentage-label">80%</div>
      </div>
    </div>
    <div class="skill">
      <div class="skill-name">MyBatis</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 65%;" data-value="65%"></div>
        <div class="percentage-label">65%</div>
      </div>
    </div>
    <div class="skill">
      <div class="skill-name">Oracle</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 90%;" data-value="90%"></div>
        <div class="percentage-label">90%</div>
      </div>
    </div>
    <div class="skill">
      <div class="skill-name">MySQL</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 80%;" data-value="80%"></div>
        <div class="percentage-label">80%</div>
      </div>
    </div>
      <div class="skill">
      <div class="skill-name">Github</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 100%;" data-value="100%"></div>
        <div class="percentage-label">100%</div>
      </div>
    </div>
      <div class="skill">
      <div class="skill-name">SourceTree</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 100%;" data-value="100%"></div>
        <div class="percentage-label">100%</div>
      </div>
    </div>
  <div class="skill">
      <div class="skill-name">Notion</div>
      <div class="skill-bar">
        <div class="skill-percentage" style="width: 100%;" data-value="100%"></div>
        <div class="percentage-label">100%</div>
      </div>
    </div>
    <!-- ... other skills here ... -->
  </div>

<script>
// This script will gradually fill the skill bars on page load.
document.addEventListener('DOMContentLoaded', () => {
  document.querySelectorAll('.skill-percentage').forEach(bar => {
    const percentageValue = bar.getAttribute('data-value');
    setTimeout(() => {
      bar.style.width = percentageValue;
    }, 100);
  });
});
</script>

</body>
</html>