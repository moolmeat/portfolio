<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>우문식 포트폴리오</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        section#projects {
            padding: 20px;
            background: #fff;
        }
        section#projects h2, section#intro h2 {
            text-align: center;
            color: #333;
        }
        .project {
            margin: 20px 0;
            padding: 20px;
            background: #f4f4f4;
            border: #ddd 1px solid;
        }
        .project h3 {
            margin: 0;
            padding-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>우문식 포트폴리오</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#intro">Intro</a></li>
                    <li><a href="#projects">Projects</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="intro">
        <div class="container">
            <h2>Intro</h2>
            <p>안녕하세요. 신입 자바 개발자 우문식입니다. Java 기반 백엔드 개발을 하고 있습니다.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>

            <div class="project">
                <h3>Muse</h3>
                <p>악기 후기 게시판 (엘리트트랙 - 개인프로젝트)</p>
                <p>개발기간: 2024.04.22 - 2024.05.03</p>
                <p>핵심 역할: 팀장, TSP 알고리즘을 활용한 여행추천 알고리즘 작성, React를 사용한 SPA 개발</p>
                <p>Language: Java17</p>
                <p>Skill: Spring Boot, MySQL, Thymeleaf, RestAPI, CSS</p>
                <p><a href="https://github.com/moolmeat/project_1" target="_blank">[Backend & Frontend]</a></p>
            </div>

            <div class="project">
                <h3>BookPanda</h3>
                <p>도서 쇼핑몰 (엘리스트랙 - 4조 팀프로젝트)</p>
                <p>개발기간: 2024.05.27 - 2024.06.21</p>
                <p>핵심 역할: 발표, JWT토큰, auth기능, GoogleSMTP 메일 인증, GCP 배포</p>
                <p>Language: Java17, JavaScript</p>
                <p>Skill: Spring Boot, Spring Security, MySQL, Redis, React, RestAPI, CSS, GCP, NginX, Docker</p>
                <p><a href="https://github.com/moolmeat/project_2_back" target="_blank">[Backend]</a></p>
                <p><a href="https://github.com/moolmeat/project_2_front" target="_blank">[Frontend]</a></p>
            </div>

            <div class="project">
                <h3>미정 (진행중)</h3>
                <p>보드게임 추천 & 커뮤니티 (엘리스트랙 - 10조 팀프로젝트)</p>
                <p>개발기간: 2024.07.22 - 2024.08.16</p>
                <p>핵심 역할: 팀장, 회원별 선호하는 장르 수집 및 데이터처리, 하이브리드 필터링을 이용한 장르별 게임 추천, date에 가중치를 둔 실시간 인기순위 기능 개발</p>
                <p>Language: Java17, JavaScript</p>
                <p>Skill: Spring Boot, Spring Security, MySQL, React, RestAPI, CSS, AWS, GCP, NginX, Docker</p>
                <p><a href="https://github.com/moolmeat/project_3_back" target="_blank">[Backend]</a></p>
                <p><a href="https://github.com/moolmeat/project_3_front" target="_blank">[Frontend]</a></p>
            </div>
        </div>
    </section>
</body>
</html>

<h1 align="center">💻 Tech Stack 💻</h1>

<h3 align="center">Backend</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white" alt="Spring Security"/>
</p>

<h3 align="center">Database</h3>
<p align="center">
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</p>

<h3 align="center">DevOps</h3>
<p align="center">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="GCP"/>
</p>

<h3 align="center">Frontend</h3>
<p align="center">
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
</p>

<h3 align="center">Tools</h3>
<p align="center">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA"/>
  <img src="https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg" alt="VSCode"/>
</p>

<h3 align="center">💡 My Most Used Languages 💡</h3>
<p align="center">
  <a href="https://github.com/moolmeat">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=moolmeat&layout=compact&show_icons=true&theme=radical" alt="Top Languages"/>
  </a>
</p>

<h3 align="center">💡 My Git Stats 💡</h3>
<p align="center">
  <a href="https://github.com/moolmeat">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=moolmeat&show_icons=true&include_all_commits=true&theme=radical" alt="GitHub Stats"/>
  </a>
</p>

<h3 align="center">Let's Connect!</h3>
<p align="center">
  <a href="https://chatgptonline.tech/ko/">
    <img src="https://img.shields.io/badge/Visit_My_Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Visit My Website"/>
  </a>
</p>
