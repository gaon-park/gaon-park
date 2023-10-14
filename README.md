![header](https://capsule-render.vercel.app/api?type=cylinder&color=timeGradient&height=150&section=header&text=Gaon%20Park&fontColor=ffffff&fontSize=70&animation=fadeIn&fontAlignY=55)
# Index

- [Certificates](#certificates)
- [Careers](#careers)
  * teamLab inc (2020-04-01 ~ 2022-09-30)
    + 업무 내용
    + 진행 프로젝트
        1. 중소기업/지원기업 매칭 시스템 (2022.05 ~ 2022.09)
        2. 결혼식장, 쥬얼리숍 예약 시스템 (2021.02 ~ 2022.09.30)
        3. MSA 스타일을 적용한 항공권 예약 시스템 (2020.04 ~ 2021.02)
- [Experience](#experience)
    + 삼성 청년 SW 아카데미 SSAFY 10th Embedded Track
- [Side Project](#side-project)
    + 규모 한 달 이상
        1. 메이플 유틸 사이트 (2023.01 ~ 2023.04)
        2. 레벨업 페이스 계산기 (2022.10 ~ 2022.11)
        3. SpringMVC based Mini Instagram (2019.07 ~ 2019.08)
    + 규모 한 달 미만
        1. Order System (2023.09)
- [Skills](#skills)
- [Algorithm](#algorithm)

# Certificates

| type          | name | level  | issuing authority | issue date |
|---------------|------|--------|-------------------|------------|
| Algorithm       | 삼성 SW 역량 테스트  | B형    | 삼성       | 2023.09.23 |
| Language (EN) | OPIc | IM2    | ACTFL       | 2023.08.27 |
| Language (JP) | JLPT | N1     |  公益財団法人日本国際教育支援協会  | 2021.12.05 |
| CS            | 정보처리 | 기사 |  한국산업인력공단                 | 2019.05.22 |

# Careers

## [@teamLab inc.](https://github.com/team-lab)

Web Backend Developer `2020-04-01 ~ 2022-09-30`

### 업무 내용  

- 백엔드 서버 REST API 개발
- 기존 웹 프로젝트 운영 및 백엔드 서버 기능 추가/유지 보수

### 진행 프로젝트

#### 1. 중소기업/지원기업 매칭 시스템 (2022.05 ~ 2022.09)

> 개요

- 같은 분야에 있는 중소기업과 지원 기업의 협업이 원활히 이루어지도록 도움을 주는 사이트
- 구직자, 기업 간 지원과 구직에 있어 다양한 서비스를 제공
- 유사 사이트
    - 점핏
    - 사람인
    - 잡플래닛

> 기술 스택

| 분류        | 기술                            |
|-----------|-------------------------------|
| Language  | - Kotlin                        |
| Framework | - SpringBoot                    |
| DB        | - PostgreSQL                    |
| AWS       | - ECS<br/>- S3<br/>- Elastic Search |

> 개발 팀 구성

BE 3명 (기여도 40%: *서버 개발 기준*)

> 상세 업무 및 성과

1. 일본 국가, 지방공공단체 행정 시스템 GBiz로부터 개인정보를 연계받아 회원 정보를 등록, 갱신하는 토큰 기반 로그인 시스템 개발
2. 업종, 분기별 매출액, 임직원 수, 본사 위치 등 검색 필터를 위한 마스터 테이블 설계
3. 데이터베이스 검색 쿼리 작성
4. aws s3관련 crud 공통 로직 개발
5. aws eleastic search crud 공통 로직 개발
6. 테스트데이터 자동 입력 배치 프로그램 개발

#### 2. 결혼식장, 쥬얼리숍 예약 시스템 (2021.02 ~ 2022.09.30)

> 개요

- 결혼식장을 검색, 비교, 예약할 수 있는 웹 사이트
- 게재 기업 관리를 위한 관리화면도 웹으로 구현

> 기술 스택

| 분류        | 기술                                       |
|-----------|------------------------------------------|
| Language  | - Java<br/>- JavaScript                  |
| Framework | - Seasar2 (made by Japan- 경량 Spring과 유사) |
| DB        | - MySQL                                  |
| AWS       | - EC2<br/>- S3                           |

> 개발 팀 구성

BE 5명 (기여도 40%: *서버 개발 기준*)

> 상세 업무 및 성과

1. on-premise, (클라우드 이식 후 aws) 환경에서의 시스템 운영
2. Line Webhook API 와 연동하는 비즈니스 분석을 위한 다중 서버 분기 처리 구현
3. 1회용 데이터 자동 갱신 스크립트 파일을 작성하여 달마다 반복되는 업무를 자동화
4. 랭킹 페이지 자동 갱신을 위한 점수 집계 배치 프로그램 개발
5. PageSpeed Insights 분석
6. 웹 사이트 내의 데이터 수집과 간단한 수정의 테스트 자동화

#### 3. MSA 스타일을 적용한 항공권 예약 시스템 (2020.04 ~ 2021.02)

> 개요

- 항공권의 예약, 구매, 운항 상태, 공석, 요금의 확인을 위한 사이트
- 유사 사이트
    - 대한항공과 아시아나의 티켓 예매 사이트

> 기술 스택

| 분류        | 기술                                 |
|-----------|------------------------------------|
| Language  | - Java                             |
| Framework | - Play Framework 2                 |
| DB        | - MySQL                            |
| AWS       | - S3<br/>- X-Ray<br/>- Cloud Watch |
| Tool      | - Apache Jmeter (부하 테스트 툴)         |

> 개발 팀 구성 (소속되어 있던 팀만 작성)

- BE 2명 (기여도 50%: *서버 개발 기준*)
- 부하 테스트팀 3명 (기여도 60%: *테스트 프로세스 기여*)

> 상세 업무 및 성과

<백엔드>
1. 서버 쪽 토큰 기반 인증 시스템 구현(JWT)
2. API 테스트 코드 오류 수정

<QA (부하 테스트 진행)>
1. 전체 시스템 결합 테스트 케이스 작성 및 테스트 시행
2. JMeter 테스트 시나리오 파일 작성(동시 접속자 수, 요청 api 지정)
3. AWS X-ray 를 통해 결과 분석 후 각 팀에 성능 개선 요청
4. Shell Script를 이용한 업무 자동화

# Experience

### 삼성 청년 SW 아카데미 SSAFY 10th Embedded Track

>  교육 내용 (`2023-07-05 ~`)

<web 관련>
1. web 기초
2. JavaScript
3. DB
4. Node.js
5. Vue.js

<Embedded 관련>
1. Linux Shell
2. 임베디드 C언어
3. Linux 시스템 / 네트워크 프로그래밍
4. 라즈베리파이
5. Linux 커널 프로그래밍
6. 임베디드 Firmware
7. 임베디드 GUI - IoT

# Side Project

### 규모 한 달 이상

#### 1. 메이플 유틸 사이트 (2023.01 ~ 2023.04)

> 개요

- 메이플스토리 확률형 아이템 기록 검증기, 공유 캘린더 (유틸 사이트 백엔드 서버)
- [큐브 사용 결과 API](https://developers.nexon.com/Maplestory/api/15/47) 사용
- 확률형 아이템의 기록을 검색하고 공시 확률의 정확도를 검증
- 파티플레이를 위한 공유 캘린더 기능
- 유저 간 팔로우 시스템 구현
- 상세 내용 repo
	- backend: https://github.com/gaon-park/ms-calendar-for-backend
	- frontend: https://github.com/gaon-park/ms-calendar-for-frontend

> 기술 스택 (backend)

| 분류        | 기술                                                            |
|-----------|---------------------------------------------------------------|
| Language  | - Kotlin                                                      |
| Framework | - SprintBoot                                                  |
| DB        | - MySQL                                                       |
| GCP       | - Compute Engine<br/>- IAM<br/>- Cloud Storage<br/>- VPC 네트워크 |
| Server    | - Nginx (Reverse Proxy)                                       |

#### 2. 레벨업 페이스 계산기 (2022.10 ~ 2022.11)

> 개요

- `메이플스토리`의 비공식 SOAP API를 활용하여 등록된 대표캐릭터의 정보를 취득
- 사용자의 경험치 상승 페이스를 분석하여 목표 레벨까지 도달할 수 있는 날짜를 예측
- 상세 내용 repo: https://github.com/gaon-park/viper-backend

> 기술 스택

| 분류        | 기술         |
|-----------|------------|
| Language  | Kotlin     |
| Framework | SpringBoot |
| DB        | MySQL      |

#### 3. SpringMVC based Mini Instagram (2019.07 ~ 2019.08)

> 개요

- Bootstrap을 활용, 이미지 기반의 SNS를 반응형 웹으로 설계 및 제작
- 상세 내용 repo: https://github.com/gaon-park/Image-Video-Upload-Post-Site

> 기술 스택

| 분류        | 기술                                             |
|-----------|------------------------------------------------|
| Language  | - JAVA(JDK 1.8) <br/>- JavaScript              |
| Database  | - MySQL                                        |
| WAS       | - Tomcat 9                                     |
| Back End  | - Spring MVC<br/>- JDBC<br/>- MyBatis          |
| Front End | - jQuery<br/>- AJAX<br/>- JSON<br/>- Bootstrap |
| API       | Google Map API                                 |

### 규모 한 달 미만

#### 1. Order System (2023.09)

> 개요

- 주문 관리 시스템 
- 상세 내용 repo
	- back: https://github.com/gaon-park/order_system_nodejs
	- front: https://github.com/gaon-park/order_system_vue

> 기술 스택

| 분류        | 기술                     |
|-----------|------------------------|
| Language  | - JavaScript           |
| DB        | - MySQL                |
| Framework | - Node.js<br/>- Vue.js |
| AWS       | - EC2                  |

# Skills

| 분류        | 기술                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Language  | - <img  src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=coffeescript&logoColor=white" /><br/>- <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"><br/>- <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=C%2B%2B&&logoColor=white"><br/>- <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&&logoColor=white"><br/>- <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> <br/>- <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> |
| Database  | - <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" /><br/>- <img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Framework | - <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" /><br/>- <img src="https://img.shields.io/badge/Spring_boot-6DB33F?style=for-the-badge&logo=Springboot&logoColor=white"/><br/>- <img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white">                                                                                                                                                                                                                                                                                                                                                  |
| Tools     | - <img src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=aws&logoColor=white"/><br/>- <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"><br/>- <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"><br/>- <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">                                                                                                                                                                                                                                                            |
| IDE       | - <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white"/><br/>- <img src="https://img.shields.io/badge/VSC-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white"><br/>- <img src="https://img.shields.io/badge/Visual Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white"/>                                                                                                                                                                                                                                                                                                                           |

# Algorithm

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=ondol)](https://solved.ac/ondol/)
