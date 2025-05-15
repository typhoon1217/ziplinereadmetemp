<!-- logo -->

![Image](https://github.com/doc/user-attachments/assets/pic/zipline-logo)



## 당신의 중개 업무에 필요한 단 하나의 라인 ZIPLINE


<div align="center">
  <a href="https://zip-line.kr">
    <img src="https://img.shields.io/badge/ZIPLINE-배포_사이트-4285F4?style=for-the-badge&logoColor=white" alt="배포 링크" />
  </a>
  <p><code>https://zip-line.kr</code></p>
    <img src="https://img.shields.io/badge/-readme.md-important?style=flat&logoColor=white" />
    <img src="https://img.shields.io/badge/release-v1.0.0-yellow?style=flat&logoColor=white" />
    <br/>
    <img src="https://img.shields.io/badge/프로젝트 기간-2025.03.17~2025.05.16-green?style=flat&logo=&logoColor=white" />
</div>



</div>

## 🎬 시연 영상
![Image](https://github.com/doc/user-attachments/assets/video/demo)


## 📝 서비스 소개
> 집라인(Zipline)은 "집(Home)"과 "라인(Line)"의 합성어로, 공인중개사가 부동산과 고객을 최적의 경로로 연결하는 다리 역할을 할 수 있도록 돕습니다.

## 🚀 주요 기능
### 📊 통계

> 대시보드 화면에서 계약, 고객, 상담 현황을 요약해 제공하여, 중개사가 현재 업무 상황을 한눈에 파악할 수 있도록 돕습니다.

---

### 📅 일정

> 주간/월간 단위로 계약 일정과 상담 일정을 조회하고 관리할 수 있으며, 일정을 추가, 수정, 삭제하는 기능을 통해 체계적인 스케줄 관리를 지원합니다.

---

### 📋 설문

> 신규 고객 유입 시 필요한 정보를 사전에 수집할 수 있는 설문 기능을 지원합니다.
> 
> QR코드 및 URL 링크를 통해 간편하게 설문을 배포하고, 제출된 답변을 통해 고객의 니즈를 빠르게 파악할 수 있습니다.

---

### 📄 계약

> 고객과 매물 간의 계약 과정을 체계적이고 효율적으로 관리합니다.

---

### 🗨️ 상담

> 고객과의 상담 기록을 등록하고 조회할 수 있으며, 상담 일시나 고객 정보를 기준으로 빠르게 검색할 수 있습니다.

---

### 🏢 매물

> 매물을 등록하고, 상세 조건(가격, 면적, 반려동물 여부 등)을 기준으로 조회 및 필터링할 수 있으며, 매물 히스토리도 관리할 수 있습니다.

---

### 👥 고객

> 고객 정보를 등록하고, 다양한 필터링 및 라벨링 기능을 통해 고객을 체계적으로 분류 및 관리할 수 있으며, 고객별 계약/상담/매물 내역도 손쉽게 관리할 수 있습니다.

---

### 📩 문자

> 단체 문자 발송, 문자 템플릿 관리, 생일 및 계약 기간 만료 전 알림 문자 발송 기능을 통해 고객 커뮤니케이션을 손쉽게 자동화하고 관리할 수 있도록 합니다.

---

### 🌐 외부 매물 데이터 조회

> 외부 부동산 플랫폼(네이버, 직방)에서 매물 정보를 확인할 수 있도록 하여, 중개사의 정보 수집 업무를 간편하게 만듭니다.

<br />

## ⚙ 인프라 구성

1. **GithubAction + DockerHub**
    - Jenkins를 활용한 CI/CD 파이프라인 구축

2. **Vercel**
    - Vercel을 사용한 프론트엔드 배포

3. **Redis, S3, RDS를 용도에 맞게 분리**
    - Redis, S3, RDS를 분리 배포해서 확장성을 보장

---

## 📌 기타 기능
1. **사용자 인증 및 권한 관리**
    - JWT 기반 로그인 및 권한 부여

<br />

## ⚙ 기술 스택

### Front-end
<div>
<img src="https://img.shields.io/badge/react-0769AD?style=for-the-badge&logo=react&logoColor=white">
<img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white">
<img src="https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
<img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">
<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/mui-007FFF?style=for-the-badge&logo=mui&logoColor=white">
</div>

### Back-end
<div>
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens">
<img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/querydsl-0769AD?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/jpa-59666C?style=for-the-badge&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white">
<img src="https://img.shields.io/badge/liquibase-2962FF?style=for-the-badge&logo=liquibase&logoColor=white">
<img src="https://img.shields.io/badge/rest_api-009688?style=for-the-badge&logo=postman&logoColor=white">
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
<img src="https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515">
</div>

### Infra
<div>
<img src="https://img.shields.io/badge/forgejo-%23FB923C.svg?style=for-the-badge&logo=forgejo&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=Github&logoColor=white">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/zsh-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white">
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=black">
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazons3&logoColor=black">
<img src="https://img.shields.io/badge/AWS_ElastiCache-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white">
<img src="https://img.shields.io/badge/Amazon_Linux-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white">
</div>

### Tools
<div>
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
<img src="https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white">
<img src="https://img.shields.io/badge/Cursor-1d9bf0?style=for-the-badge&logo=cursor&logoColor=white">
<img src="https://img.shields.io/badge/github_copilot-8957E5?style=for-the-badge&logo=github-copilot&logoColor=white">

</div>

<br />

## 🛠️ 프로젝트 아키텍처

![Image](https://github.com/doc/user-attachments/assets/pic/architecture)

## 🛠️ CI / CD 파이프라인

![Image](https://github.com/doc/user-attachments/assets/00ff56f)

<br />

## 🗂️ 기술 문서
[![📄 API 명세서](https://github.com/doc/user-attachments/assets/video/demo)](-)

[![📋 기능 명세서](https://github.com/doc/user-attachments/assets/video/demo)](-)

[![📊 ERD](https://github.com/doc/user-attachments/assets/video/demo)](-)

[![🔧 트러블 슈팅](https://github.com/doc/user-attachments/assets/video/demo)](-)

[![📖 기술 메뉴얼](https://github.com/doc/user-attachments/assets/video/demo)](-)

[![📈 시퀀스 다이어그램](https://github.com/doc/user-attachments/assets/video/demo)](-)

<br />

## 💁‍♂️ 프로젝트 팀원

| 이름  | 역할           | 담당 업무                                                                            |
|-----|--------------|----------------------------------------------------------------------------------|
| 채지원 | 백엔드 개발자 (팀장) | 단체 문자 발송기능, Vercel 배포, 프론트 엔드  |
| 신중우 | 백엔드 개발자      | AWS(EC2,RDS,Redis), CICD, 공개매물 크롤링, 조회, 대쉬보드 통계, 구조 리펙토링|
| 신윤상 | 백엔드 개발자      | 고객 관리, 설문 관리, 상담 관리, ExcelImport|
| 조수연 | 백엔드 개발자      | 로그인/회원가입, 매물 관리, 계약 관리 |

<br />

## 🐛 이슈 보고 & 개선사항 제안

<div align="center">
  <a href="https://docs.google.com/forms/d/e/1FAIpQLScIPclLeQxwTgsHOG_xAJ6ofQHC9oqUHbCUsKPzYhVFMwv5iw/viewform?usp=dialog">
    <img src="https://img.shields.io/badge/이슈_및_개선사항_제안하기-FF5722?style=for-the-badge&logo=googleforms&logoColor=white" alt="이슈 및 개선사항 제안하기" />
  </a>
</div>
<p align="center"><i>이슈 및 개선사항은 위 설문폼을 통해 남겨주시면 감사하겠습니다</i> 😊</p>

<br />

## 📁 관련 레포지토리

<div align="center">
  <a href="https://github.com/Kernel360/Kernel360-KDEV4-ZIPLINE-FE">
    <img src="https://img.shields.io/badge/프론트엔드_레포지토리-181717?style=for-the-badge&logo=github&logoColor=white" alt="프론트엔드 레포지토리" />
  </a>
</div>

<!--

## 📝 추가 개선사항

### 🏆 주요 성과 및 통계
> 

### 🌟 핵심 차별점 
> 

### 📱 서비스 스크린샷 
> 

### 🔄 현재 개발 진행 상황
> 

### 📊 성능 지표
> 

### 📋 빠른 시작 가이드
> 로컬 환경에서 프로젝트를 실행하는 방법에 대한 간단한 가이드.
<div align="center">


-->
