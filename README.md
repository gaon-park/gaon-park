![header](https://capsule-render.vercel.app/api?type=cylinder&color=timeGradient&height=150&section=header&text=Gaon%20Park&fontColor=ffffff&fontSize=70&animation=fadeIn&fontAlignY=55)

# Certificates

| type          | name | level  | issuing authority | issue date |
|---------------|------|--------|-------------------|------------|
| Algorithm       | 삼성 SW 역량 테스트  | B형    | 삼성       | 2023.09.23 |
| Language (EN) | OPIc | IM2    | Multicampus       | 2023.08.27 |
| Language (JP) | JLPT | N1     |  公益財団法人日本国際教育支援協会  | 2021.12.05 |
| CS            | 정보처리 | 기사 |  한국산업인력공단                 | 2019.05.22 |

# Careers

## [@teamLab inc.](https://github.com/team-lab)

Web Backend Developer `2020-04-01 ~ 2022-09-30`

### 업무 내용

- 백엔드 서버 REST API 개발
- 기존 웹 프로젝트 운영 및 백엔드 서버 기능 추가/유지 보수

### 진행 프로젝트

<details>
<summary>
중소기업/지원기업 매칭 시스템 (2022.05 ~ 2022.09)
</summary>
<div markdown="1">

> 개요
>
- 일본 중소 기업청의 의뢰를 받은 프로젝트
- 같은 분야에 있는 중소기업과 지원 기업의 협업이 원활히 이루어지도록 도움을 주는 사이트
- 구직자, 기업 간 지원과 구직에 있어 다양한 서비스를 제공
- 유사 사이트
    - 점핏
    - 사람인
    - 잡플래닛

> 기술 스택
> 

<table>
    <thead>
        <tr>
            <th>분류</th>
            <th>기술</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Language</td>
            <td>Kotlin</td>
        </tr>
        <tr>
            <td>Framework</td>
            <td>SpringBoot</td>
        </tr>
        <tr>
            <td>DB</td>
            <td>PostgreSQL</td>
        </tr>
        <tr>
            <td rowspan="3">AWS</td>
            <td>ECS</td>
        </tr>
        <tr>
            <td>S3</td>
        </tr>
        <tr>
            <td>Elastic Search</td>
        </tr>
    </tbody>
</table>


> 개발 팀 구성
> 
- BE 3명 (기여도 40%: *서버 개발 기준*)

> 상세 업무 및 성과
> 
1. 일본 국가, 지방공공단체 행정 시스템 GBiz로부터 개인정보를 연계받아 회원 정보를 등록, 갱신하는 토큰 기반 로그인 시스템 개발 
2. 업종, 분기별 매출액, 임직원 수, 본사 위치 등 검색 필터를 위한 마스터 테이블 설계 
3. 데이터베이스 검색 쿼리 작성 
4. aws s3관련 crud 공통 로직 개발 
5. aws eleastic search crud 공통 로직 개발
6. 테스트데이터 자동 입력 배치 프로그램 개발
</div>
</details>

<details>
<summary>
결혼식장, 쥬얼리숍 예약 시스템 (2021.02 ~ 2022.09.30)
</summary>
<div markdown="1">

> 개요
> 
- 결혼식장을 검색, 비교, 예약할 수 있는 웹 사이트
- 게재 기업 관리를 위한 관리화면도 웹으로 구현

> 기술 스택
> 

<table>
    <thead>
        <tr>
            <th>분류</th>
            <th>기술</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">Language</td>
            <td>Java</td>
        </tr>
        <tr>
            <td>JavaScript</td>
        </tr>
        <tr>
            <td>Framework</td>
            <td>Seasar2<br>- made by Japan<br>- 경량 Spring과 유사</td>
        </tr>
        <tr>
            <td>DB</td>
            <td>MySQL</td>
        </tr>
        <tr>
            <td rowspan="2">AWS</td>
            <td>EC2</td>
        </tr>
        <tr>
            <td>S3</td>
        </tr>
    </tbody>
</table>

> 개발 팀 구성
> 
- BE 5명 (기여도 40%: *서버 개발 기준*)

> 상세 업무 및 성과
> 
1. on-premise, (클라우드 이식 후 aws) 환경에서의 시스템 운영
2. Line Webhook API 와 연동하는 비즈니스 분석을 위한 다중 서버 분기 처리 구현
3. 1회용 데이터 자동 갱신 스크립트 파일을 작성하여 달마다 반복되는 업무를 자동화
4. 랭킹 페이지 자동 갱신을 위한 점수 집계 배치 프로그램 개발
5. PageSpeed Insights 분석
6. 웹 사이트 내의 데이터 수집과 간단한 수정의 테스트 자동화

</div>
</details>
    
<details>
<summary>
MSA 스타일을 적용한 항공권 예약 시스템 (2020.04 ~ 2021.02)
</summary>
<div markdown="1">

> 개요
> 
- 항공권의 예약, 구매, 운항 상태, 공석, 요금의 확인을 위한 사이트
- 유사 사이트
    - 대한항공과 아시아나의 티켓 예매 사이트

> 기술 스택
> 

<table>
    <thead>
        <tr>
            <th>분류</th>
            <th>기술</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Language</td>
            <td>Java</td>
        </tr>
        <tr>
            <td>Framework</td>
            <td>Play Framework 2</td>
        </tr>
        <tr>
            <td>DB</td>
            <td>MySQL</td>
        </tr>
        <tr>
            <td rowspan="3">AWS</td>
            <td>S3</td>
        </tr>
        <tr>
            <td>X-Ray</td>
        </tr>
        <tr>
            <td>Cloud Watch</td>
        </tr>
        <tr>
            <td>Tool</td>
            <td>Apache Jmeter<br>- 부하 테스트 툴</td>
        </tr>
    </tbody>
</table>

> 개발 팀 구성 (소속되어 있던 팀만 작성)
> 
- BE 2명 (기여도 50%: *서버 개발 기준*)
- 부하 테스트팀 3명 (기여도 60%: *테스트 프로세스 기여*)

> 상세 업무 및 성과
> 

<백엔드>

1. 서버 쪽 토큰 기반 인증 시스템 구현(JWT)
2. API 테스트 코드 오류 수정

<QA (부하 테스트 진행)>

1. 전체 시스템 결합 테스트 케이스 작성 및 테스트 시행
2. JMeter 테스트 시나리오 파일 작성(동시 접속자 수, 요청 api 지정)
3. AWS X-ray 를 통해 결과 분석 후 각 팀에 성능 개선 요청
4. Shell Script를 이용한 업무 자동화

</div>
</details>

# Experience
### 삼성 청년 SW 아카데미 SSAFY 10th
Embedded Track `2023-07-05 ~`

### 사이드 프로젝트

<details>
<summary>메이플 유틸 사이트 (2023.01 ~ 2023.04)</summary>
<div markdown="1">

> 개요
> 
- 메이플스토리 확률형 아이템 기록 검증기, 공유 캘린더 (유틸 사이트 백엔드 서버)
- [큐브 사용 결과 API](https://developers.nexon.com/Maplestory/api/15/47) 사용
- 확률형 아이템의 기록을 검색하고 공시 확률의 정확도를 검증
- 파티플레이를 위한 공유 캘린더 기능
- 유저 간 팔로우 시스템 구현
- repo
    - backend: https://github.com/gaon-park/ms-calendar-for-backend
    - frontend: https://github.com/gaon-park/ms-calendar-for-frontend

> 기술 스택 (backend)
> 

<table>
    <thead>
        <tr>
            <th>분류</th>
            <th>기술</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Language</td>
            <td>Kotlin</td>
        </tr>
        <tr>
            <td>Framework</td>
            <td>SprintBoot</td>
        </tr>
        <tr>
            <td>DB</td>
            <td>MySQL</td>
        </tr>
        <tr>
            <td rowspan="4">GCP</td>
            <td>Compute Engine</td>
        </tr>
        <tr>
            <td>IAM</td>
        </tr>
        <tr>
            <td>Cloud Storage</td>
        </tr>
        <tr>
            <td>VPC 네트워크</td>
        </tr>
        <tr>
            <td>Server</td>
            <td>Nginx (Reverse Proxy)</td>
        </tr>
    </tbody>
</table>

> 운영 관련 (메이플 inven 이용)
>
- [테스트 도움!! 큐브 기록 검색 사이트](https://www.inven.co.kr/board/maple/5974/940125)
- [나의 등업 확률을 확인하자! 기능 설명편](https://www.inven.co.kr/board/maple/5974/989320)
- [서버 내립니다😥](https://www.inven.co.kr/board/maple/5974/1400582)

> 상세 API (swagger)
>

- json 형식: https://github.com/gaon-park/ms-calendar-for-backend/blob/master/api-docs.json
- yaml 형식: https://github.com/gaon-park/ms-calendar-for-backend/blob/master/api-docs.yml
- 로컬 서버 기동시: http://127.0.0.1/api-docs/
- 서비스 서버: https://ms-hero.kr/api-docs/
    ** 관리자 ID/PW 필요

> 개발 내용
>
1. Google OAuth를 사용해 email정보를 연계받아 신규 회원 등록, 로그인하는 시스템 설계 및 개발
2. 토큰 기반 인증 시스템에 refresh token을 도입하여 안정성 강화
3. follow/follwer 관계 기반 테이블 설계
4. 공유 캘린더 관련 테이블 설계
5. 일정 초대, 신규 팔로워 등의 정보 실시간 알림 기능 개발
6. 넥슨 공식 api를 이용한 확률형 아이템 사용 결과 검색 시스템 개발
7. 아이템별 확률형 아이템의 실 확률 검증 시스템 개발
8. quartz 라이브러리를 사용해 주기적으로 등록된 유저의 정보를 수집하는 배치 프로그램 개발
9. nginx reverse proxy로 하나의 서버에서 백, 프론트 운용
10. 검색 속도를 위해 테이블 구조 개선

> 결과
>
- 약 3개월간 회원가입자 950명
- 확률형 아이템 기록 확인에 필요한 key등록자 420명
- 분석가능한 데이터 누적 300만여건 수집

</div>
</details>

<details>
<summary>
레벨업 페이스 계산기 (2022.10 ~ 2022.11)
</summary>
<div markdown="1">

> 개요
> 
- '메이플스토리'의 비공식 SOAP API를 활용하여 등록된 대표캐릭터의 정보를 취득
- 사용자의 경험치 상승 페이스를 분석하여 목표 레벨까지 도달할 수 있는 날짜를 예측
- repo: https://github.com/gaon-park/viper-backend

> 기술 스택
> 

<table>
    <thead>
        <tr>
            <th>분류</th>
            <th>기술</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Language</td>
            <td>Kotlin</td>
        </tr>
        <tr>
            <td>Framework</td>
            <td>SpringBoot</td>
        </tr>
        <tr>
            <td>DB</td>
            <td>MySQL</td>
        </tr>
    </tbody>
</table>

> 블로그 기록
> 
1. **[메이플스토리 API를 이용하여 대표캐릭터 정보를 불러오는 API](https://ondol-diary.tistory.com/3)**
2. **[Jsoup를 이용한 캐릭터 정보 탐색](https://ondol-diary.tistory.com/4)**
3. **[Json PropertyNamingStrategy](https://ondol-diary.tistory.com/5)**

> API List
> 
1. [유저 신규 등록 API](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EC%9C%A0%EC%A0%80-%EC%8B%A0%EA%B7%9C-%EB%93%B1%EB%A1%9D-api)
2. [로그인 API](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EB%A1%9C%EA%B7%B8%EC%9D%B8-api)
3. [캐릭터 정보 요청 API](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EC%BA%90%EB%A6%AD%ED%84%B0-%EC%A0%95%EB%B3%B4-%EC%9A%94%EC%B2%AD-api)
4. [배치 수동 실행](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EB%B0%B0%EC%B9%98-%EC%88%98%EB%8F%99-%EC%8B%A4%ED%96%89)
5. [경험치 분석 API](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EA%B2%BD%ED%97%98%EC%B9%98-%EB%B6%84%EC%84%9D-api)
6. [데이터 이력 API](https://github.com/gaon-park/viper-backend/blob/master/README.md#%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9D%B4%EB%A0%A5-api)

</div>
</details>

# Skills
### Language 
<img 
    src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=coffeescript&logoColor=white"
/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white">
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=C%2B%2B&&logoColor=white">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> 
<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> 

### Database
<img 
    src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"
/>
<img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">

### Framework
<img 
    src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"
/>
<img 
    src="https://img.shields.io/badge/Spring_boot-6DB33F?style=for-the-badge&logo=Springboot&logoColor=white"
/>
<img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white">

### Tools
<img 
    src="https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=aws&logoColor=white"
/>
<img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">

### IDE
<img 
    src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white"
/>
<img src="https://img.shields.io/badge/VSC-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white">
<img 
    src="https://img.shields.io/badge/Visual Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white"
/>

### Algorithm
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=ondol)](https://solved.ac/ondol/)
<br/>
