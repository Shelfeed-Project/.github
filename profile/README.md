<div align="center">
  <h1>📚 SHELFEED 📚</h1>
  <p>
    <b><!-- 프로젝트 기간 예: 2026.03.01 - 2026.06.30 --></b>
  </p>
  <br/>
  <!-- 대표 배너 이미지 첨부 (GitHub 이슈/PR에 드래그해서 나온 링크 사용) -->
  <!-- <img width="100%" alt="Shelfeed Banner" src="이미지_링크" /> -->
  <br/>
  <br/>
</div>

# 📖 Table of Contents
* [Introduction](#introduction)
* [Demo](#demo)
* [API](#api)
* [System Architecture](#system-architecture)
* [ERD](#erd)
* [Tech Stack](#tech-stack)
* [Monitoring](#monitoring)
* [How to start](#how-to-start)
* [Directory Structure](#directory-structure)
* [Team Members](#team-members)

<br>

<a id="introduction"></a>
# 📣 Introduction
### URL
> https://www.shelfeed.co.kr (현재 배포 중단)

### API
> https://api.shelfeed.co.kr

### 프로젝트 소개
- **읽은 책의 감상을 기록하고 공유하는 독서 기반 소셜 플랫폼**
- **바코드 스캔·검색으로 책을 등록하고, 나만의 서재를 채워나가는 독서 아카이빙**
- **완독한 책을 쌓아 올리는 '지혜의 탑'으로 독서 성취를 시각화**
- **감상에 좋아요·댓글·팔로우로 이어지는 독자 간 소셜 인터랙션**
- **Elasticsearch 기반 도서 검색으로 방대한 도서 데이터를 빠르게 탐색**

<br>

<a id="demo"></a>
# 🕺🏻 Demo

### 온보딩 / 로그인
> 소셜 로그인(OAuth)으로 간편하게 시작합니다.
<!-- <img src="이미지_링크" width="100%" alt="Onboarding" /> -->
https://github.com/user-attachments/assets/13d4087c-c265-43f4-9f7f-029428c647bf


### 도서 검색 및 등록 (바코드 스캔)
> 책 제목·저자 검색 또는 ISBN 바코드 스캔으로 책을 빠르게 찾아 서재에 담습니다.
<!-- <img src="이미지_링크" width="100%" alt="Book Search" /> -->
https://github.com/user-attachments/assets/492e88d2-2b73-49eb-81c4-269c8bed682b

### 감상 작성 및 공유
> 책을 읽고 느낀 점을 감상으로 기록하고 다른 독자와 공유합니다.
<!-- <img src="이미지_링크" width="100%" alt="Review" /> -->
https://github.com/user-attachments/assets/843ed5d6-16c1-407b-a41d-c0e2058889b2

### 나의 서재 · 지혜의 탑
> 읽은 책으로 서재를 채우고, 완독한 책이 쌓여 '지혜의 탑'이 성장합니다.
<!-- <img src="이미지_링크" width="100%" alt="Library" /> -->
https://github.com/user-attachments/assets/4c83ea35-bff9-4451-8a48-e0e313765974

### 피드 · 소셜 인터랙션 ·  알림
> 팔로우한 독자들의 감상을 피드에서 만나고, 좋아요·댓글로 소통합니다.
<!-- <img src="이미지_링크" width="100%" alt="Feed" /> -->
<br>

<a id="api"></a>
# 📁 API
### Swagger
> SpringDoc OpenAPI 기반 Swagger UI 로 전체 API 명세를 제공합니다. (`/swagger-ui/index.html`)
<!-- <img width="100%" alt="Swagger" src="이미지_링크" /> -->
<img width="400" height="300" alt="스웨거" src="https://github.com/user-attachments/assets/8bd92293-26d9-4c45-97b1-dfb7d128be5f" />

<br>

<a id="system-architecture"></a>
# 🏛️ System Architecture
<!-- 시스템 아키텍처 다이어그램 첨부 -->
<!-- <img width="100%" alt="System Architecture" src="이미지_링크" /> -->

<img width="861" height="433" alt="스크린샷 2026-07-12 오후 7 56 56" src="https://github.com/user-attachments/assets/d80453c9-7c75-4a0e-8faa-226c30f8e448" />


<br>

<a id="erd"></a>
# 🗝️ ERD
<!-- ERD 이미지 첨부 -->
<!-- <img src="이미지_링크" width="100%" alt="ERD" /> -->

<img width="1057" height="836" alt="스크린샷 2026-07-12 오후 7 58 16" src="https://github.com/user-attachments/assets/0f8337cf-e852-4376-8d31-888da4ea14f5" />


<br>

<a id="tech-stack"></a>
# 💻 Tech Stack

<div align="center">
  <table>
    <tr>
      <th width="15%">Field</th>
      <th width="85%">Technology of Use</th>
    </tr>
    <tr>
      <td align="center"><b>Frontend</b></td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
        <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
        <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
        <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
        <img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white">
        <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white">
        <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white">
        <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white">
        <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white">
        <img src="https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white">
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
        <img src="https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white">
        <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white">
      </td>
    </tr>
    <tr>
      <td align="center"><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/Java_21-007396?style=for-the-badge&logo=openjdk&logoColor=white">
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
        <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
        <img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
        <img src="https://img.shields.io/badge/QueryDSL-0769AD?style=for-the-badge">
        <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
        <img src="https://img.shields.io/badge/OAuth2-EB5424?style=for-the-badge&logo=auth0&logoColor=white">
        <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
      </td>
    </tr>
    <tr>
      <td align="center"><b>Database</b></td>
      <td>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
        <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
      </td>
    </tr>
    <tr>
      <td align="center"><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
        <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
      </td>
    </tr>
    <tr>
      <td align="center"><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white">
        <img src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white">
        <img src="https://img.shields.io/badge/Tempo-F46800?style=for-the-badge&logo=grafana&logoColor=white">
        <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white">
        <img src="https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white">
      </td>
    </tr>
    <tr>
      <td align="center"><b>ETC</b></td>
      <td>
        <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
      </td>
    </tr>
  </table>
</div>

<br>

<a id="monitoring"></a>

### k6 부하 테스트 (Elasticsearch 도입 전/후 비교)
> 도서 검색 성능 개선을 위해 `%LIKE%` 풀스캔 → Elasticsearch 역인덱스로 전환하고,
> k6 로 AS-IS/TO-BE 를 동일 조건에서 측정해 개선 효과를 검증했습니다.
<!-- <img src="이미지_링크" width="100%" alt="k6" /> -->
<img width="1168" height="1076" alt="스크린샷 2026-07-12 오후 7 59 33" src="https://github.com/user-attachments/assets/b9168c47-e625-4f5a-af21-8bbd32d11ced" />
<img width="1168" height="947" alt="스크린샷 2026-07-12 오후 7 59 49" src="https://github.com/user-attachments/assets/ae2da3ef-1e6b-4941-9d54-e024f3915183" />
<img width="1168" height="1046" alt="스크린샷 2026-07-12 오후 8 00 01" src="https://github.com/user-attachments/assets/6a444942-cb2b-410a-be32-b7549a2bfe4d" />
<img width="1168" height="770" alt="스크린샷 2026-07-12 오후 8 00 20" src="https://github.com/user-attachments/assets/124ebd38-e88b-4bbb-bbe8-93c8120f0844" />
<img width="1168" height="1069" alt="스크린샷 2026-07-12 오후 8 00 32" src="https://github.com/user-attachments/assets/bc5690ce-28b4-4a79-a84a-ea5cbc17706f" />


<img width="1335" height="1069" alt="스크린샷 2026-07-12 오후 8 07 37" src="https://github.com/user-attachments/assets/afd6aa21-bbd2-4fbb-af9f-9a37015cc6ac" />
<img width="1335" height="1086" alt="스크린샷 2026-07-12 오후 8 08 05" src="https://github.com/user-attachments/assets/7f405ae6-8bf1-4b2d-a5e7-4d5344748206" />
<img width="1335" height="1086" alt="스크린샷 2026-07-12 오후 8 08 20" src="https://github.com/user-attachments/assets/e442cd4f-f75c-44dd-853c-6528ab466843" />



<br>

<a id="how-to-start"></a>
# 📓 How To Start

### Clone The Repository
```bash
git clone https://github.com/Shelfeed-Project/BackEnd_Project.git
git clone https://github.com/Shelfeed-Project/FrontEnd_Project.git
```

### Backend — env setting (`.env`)
```
# Database
DB_URL=
DB_USERNAME=
DB_PASSWORD=

# Redis
REDIS_HOST=
REDIS_PORT=
REDIS_PASSWORD=

# JWT
JWT_SECRET=

# OAuth2 (소셜 로그인)
OAUTH_CLIENT_ID=
OAUTH_CLIENT_SECRET=

# AWS (S3 · SSM Parameter Store)
AWS_REGION=
S3_BUCKET=

# Elasticsearch
ELASTICSEARCH_URIS=

# Mail
MAIL_USERNAME=
MAIL_PASSWORD=
```

### Backend — Run (Docker)
```bash
cd BackEnd_Project
docker compose up -d              # MySQL · Redis · Elasticsearch · 모니터링 스택 기동
./gradlew bootRun                 # Spring Boot 실행
```

### Frontend — env setting (`.env`)
```
VITE_API_BASE_URL=
```

### Frontend — Install & Run
```bash
cd FrontEnd_Project
npm install
npm run dev
```

<br/>

<a id="directory-structure"></a>
# 📁 Directory Structure

<details>
<summary>📂 FrontEnd_Project (펼치기/접기)</summary>
<pre>
📂 src
 ┣ 📂 api            # 도메인별 API 호출 (auth·book·review·feed·library·follow·notification·search·ocr …)
 ┣ 📂 components     # 공통·UI·레이아웃·댓글·OCR 컴포넌트
 ┃ ┣ 📂 common
 ┃ ┣ 📂 ui
 ┃ ┣ 📂 layout
 ┃ ┣ 📂 comment
 ┃ ┗ 📂 ocr
 ┣ 📂 constants      # form·library·validation 상수
 ┣ 📂 features       # 기능 단위 모듈 (search …)
 ┣ 📂 hooks          # useAuthBootstrap·useDragScroll·useModalA11y …
 ┣ 📂 lib            # barcodeDecoder·authProvider·device·share·utils …
 ┣ 📂 mocks          # 목 데이터
 ┣ 📂 pages          # 라우트 페이지 (BookDetail·BookReviewsList·AuthCallback·BlockedUsers …)
 ┣ 📂 store          # Zustand 전역 상태
 ┣ 📜 App.tsx
 ┣ 📜 main.tsx
 ┗ 📜 index.css
</pre>
</details>

<details>
<summary>📂 BackEnd_Project (펼치기/접기)</summary>
<pre>
📂 src/main/java/com/shelfeed/backend
 ┣ 📂 domain
 ┃ ┣ 📂 admin        # 관리자
 ┃ ┣ 📂 auth         # 인증 · OAuth2 · JWT
 ┃ ┣ 📂 block        # 사용자 차단
 ┃ ┣ 📂 book         # 도서 (Elasticsearch 검색 · 외부 API 연동)
 ┃ ┣ 📂 comment      # 댓글 · 대댓글
 ┃ ┣ 📂 feed         # 피드
 ┃ ┣ 📂 follow       # 팔로우
 ┃ ┣ 📂 genre        # 장르
 ┃ ┣ 📂 library      # 서재 · 지혜의 탑
 ┃ ┣ 📂 member       # 회원
 ┃ ┣ 📂 notification # 알림
 ┃ ┣ 📂 review       # 감상 (좋아요 · 댓글)
 ┃ ┗ 📂 (report · search …)
 ┃    ┗ (각 도메인: controller · service · repository · entity · dto)
 ┣ 📂 global         # 공통 설정 · 예외 · 시큐리티 · 응답 포맷
 ┗ 📜 BackendApplication.java

📂 (root)
 ┣ 📂 docker         # nginx · prometheus · grafana · loki · tempo · elasticsearch
 ┣ 📂 k6             # 부하 테스트 스크립트 (ramping · constant · setup-tokens)
 ┣ 📜 docker-compose.yml · docker-compose.prod.yml · Dockerfile
 ┗ 📜 build.gradle.kts
</pre>
</details>

<br />

<a id="team-members"></a>
# 👥 Team Members

<div align="center">
  <table width="100%">
    <thead>
      <tr>
        <th width="20%">name</th>
        <th width="20%">김승조</th>
        <th width="20%">김민규</th>
        <th width="20%">조민정</th>
        <th width="20%">백현준</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center"><b>Profile</b></td>
        <td align="center"><img src="https://github.com/SeungJo-02.png" width="100"></td>
        <td align="center"><img src="https://github.com/sincereQK.png" width="100"></td>
        <td align="center"><img src="https://github.com/chocandy.png" width="100"></td>
        <td align="center"><img src="https://github.com/Bhyunjun.png" width="100"></td>
      </tr>
      <tr>
        <td align="center"><b>Position</b></td>
        <td align="center">Full Stack<br>DevOps</td>
        <td align="center">Frontend<br>Design</td>
        <td align="center">Frontend</td>
        <td align="center">Backend</td>
      </tr>
      <tr>
        <td align="center"><b>GitHub</b></td>
        <td align="center">
          <a href="https://github.com/SeungJo-02">
            <img src="http://img.shields.io/badge/SeungJo02-181717?style=social&logo=github"/>
          </a>
        </td>
        <td align="center">
          <a href="https://github.com/sincereQK">
            <img src="http://img.shields.io/badge/sincereQK-181717?style=social&logo=github"/>
          </a>
        </td>
        <td align="center">
          <a href="https://github.com/chocandy">
            <img src="http://img.shields.io/badge/chocandy-181717?style=social&logo=github"/>
          </a>
        </td>
        <td align="center">
          <a href="https://github.com/Bhyunjun">
            <img src="http://img.shields.io/badge/Bhyunjun-181717?style=social&logo=github"/>
          </a>
        </td>
      </tr>
    </tbody>
  </table>
</div>
<br />
<br />
