
<div align="center">

![Project Banner](https://github.com/user-attachments/assets/f1a58b53-07e8-4da9-8fe6-16525f270af3)

</div>

---

## 📋 목차

- [프로젝트 소개](#-프로젝트-소개)
- [기획 배경](#-기획-배경)
- [사용자 플로우](#-사용자-플로우)
- [팀원 소개](#-팀원-소개)
- [기술 스택](#-기술-스택)
- [아키텍처](#-아키텍처)
- [ERD](#-erd)
- [주요 기능](#-주요-기능)
- [상세 기술 문서](#-상세-기술-문서)

---

## 💡 프로젝트 소개

다예약은 **MSA 기반의 통합 예약 서비스**입니다. 공연, 전시, 음식점 예약을 하나의 플랫폼에서 관리할 수 있는 문화 슈퍼앱을 지향합니다.

- **프로젝트 기간**: 2025.09.01 - 2025.10.02
- **배포 주소**: [http://3.37.156.94:10000](http://3.37.156.94:10000)
- **팀 노션**: [팀 노션 바로가기](https://www.notion.so/4-2612dc3ef51480679e40c1af55c69c0d?pvs=21)

---

## ❓ 기획 배경

#### 문제 정의

현재 사용자들은 문화 생활을 계획할 때 다음과 같은 불편함을 겪고 있습니다.

- 공연, 전시, 음식점 정보를 각각 다른 플랫폼에서 조회해야 함
- 예약 시 동일한 정보를 반복 입력해야 하는 번거로움
- 공연·전시·음식점 일정을 하나의 흐름으로 연계하여 계획하기 어려움
- 분산된 예약 관리로 인한 효율성 저하

#### 고객 페르소나

- 커플/친구/가족: 데이트나 모임 일정을 하나의 애플리케이션으로 관리하고 싶은 사용자
- 단체 관광객: 여행 일정 중 문화 공연과 식사를 효율적으로 계획하고 싶은 그룹

#### 사용자 인사이트

- "공연이나 전시 관람 후 식사까지 이어지는 일정을 하나의 앱으로 계획하고 싶다"
- "여러 앱을 오가며 예약하지 않고, 한 곳에서 정보를 비교하고 관리할 수 있으면 좋겠다"

#### 해결 방향

- **통합 예매 시스템**을 통한 '문화 슈퍼앱' 구현
- 공연·전시·음식점 예약 테마를 하나의 플랫폼에서 제공
- 각 테마 정보를 한 곳에서 비교할 수 있는 통합 조회 기능 제공

---

## 📱 사용자 플로우

### 🍽️ 일반 사용자 음식점 예약

![음식점 예약 플로우](https://github.com/user-attachments/assets/c9d7b203-b5cc-422c-a05c-01bc070784e6)

### 🎤 일반 사용자 공연 예약

![공연 예약 플로우](https://github.com/user-attachments/assets/8cc69e10-b32e-4ecb-8bf8-b0b250c7f64e)

### 🛍 셀러 서비스 등록

![셀러 서비스 등록 플로우](https://github.com/user-attachments/assets/7a9aa43a-ba5b-48fa-9e0f-04ec88d75380)

---

## 👥 팀원 소개

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Stock05">
        <img src="https://github.com/Stock05.png" width="100px;" alt="이경민"/><br />
        <sub><b>이경민</b></sub>
      </a><br />
      <sub>👑 팀장</sub><br />
      <sub>예약·결제 서비스</sub>
    </td>
    <td align="center">
      <a href="https://github.com/pigglehyun">
        <img src="https://github.com/pigglehyun.png" width="100px;" alt="이승현"/><br />
        <sub><b>이승현</b></sub>
      </a><br />
      <sub>👑 부팀장</sub><br />
      <sub>알림·대기열 서비스</sub>
    </td>
    <td align="center">
      <a href="https://github.com/dayaelee">
        <img src="https://github.com/dayaelee.png" width="100px;" alt="이다예"/><br />
        <sub><b>이다예</b></sub>
      </a><br />
      <sub>🖊️ 기록관</sub><br />
      <sub>웨이팅·검색 서비스</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/ktkt1413">
        <img src="https://github.com/ktkt1413.png" width="100px;" alt="정다겸"/><br />
        <sub><b>정다겸</b></sub>
      </a><br />
      <sub>🚀 팀원</sub><br />
      <sub>음식점·백오피스 서비스</sub>
    </td>
    <td align="center">
      <a href="https://github.com/legoChoi">
        <img src="https://github.com/legoChoi.png" width="100px;" alt="최우탁"/><br />
        <sub><b>최우탁</b></sub>
      </a><br />
      <sub>🚀 팀원</sub><br />
      <sub>게이트웨이·인증·전시회</sub>
    </td>
    <td align="center">
      <a href="https://github.com/dinahland">
        <img src="https://github.com/dinahland.png" width="100px;" alt="황선영"/><br />
        <sub><b>황선영</b></sub>
      </a><br />
      <sub>🚀 팀원</sub><br />
      <sub>공연 서비스</sub>
    </td>
  </tr>
</table>

---

## 🛠️ 기술 스택

### Backend

<p>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white">
</p>


### Database

<p>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
<img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/QueryDSL-0769AD?style=for-the-badge&logoColor=white">
</p>

### Infra & CI/CD

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
<img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=Amazon%20AWS&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white">
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
</p>

### Authentication & Security

<p>
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white">
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
</p>

### Message Queue & Real-time

<p>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
<img src="https://img.shields.io/badge/SSE-FF6600?style=for-the-badge&logoColor=white">
</p>

### Test

<p>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white">
<img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white">
</p>

### Cooperation Tools

<p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white">
<img src="https://img.shields.io/badge/ZEP-AD29B6?style=for-the-badge&logoColor=white">
</p>

---

## 🏗️ 아키텍처

![System Architecture](https://github.com/user-attachments/assets/9be78450-0b8c-44f4-b2ab-40c4405eb54d)

---

## 📊 ERD

![ERD Diagram](https://github.com/user-attachments/assets/8c6e3c3d-a97e-4c62-ae27-20303c841014)

**ERD 상세 보기**: [ERDCloud](https://www.erdcloud.com/d/LbMdMjtF48WoL7GWt)

---

## 🎯 주요 기능

### ✨ 예약 서비스

표준화된 예약 처리  
- 서비스별 예약 요청을 하나의 표준화된 형식으로 처리
- 공연, 전시, 음식점 예약을 통합 관리  

좌석 선점 시스템  
- Redis Lua 스크립트를 활용한 원자성 보장  
- 동시성 제어를 통한 안정적인 예약 처리  

### ✨ 대기열 서비스

대규모 트래픽 대응  
- 국내 공연 좌석 최대 예약 규모(약 10만 명)를 기준으로 설계  
- Redis Sorted Set 기반 FIFO 순차 입장 관리  

보안 및 권한 제어  
- 토큰 이중 구조로 위변조 방지  
- 스케줄러를 통한 활성 토큰 발급으로 순차 입장 제어  

### ✨ 웨이팅 서비스

음식점 웨이팅 관리  
- 점주/손님 간 상호작용을 통한 웨이팅 상태 관리  
- 호출 및 응답 시 실시간 알림 제공  
- 무응답 2회 시 자동 노쇼 처리  

웨이팅 순서 관리  
- Redis 캐시 기반 빠른 상태 조회  
- 완료되지 않은 웨이팅만 캐시에 저장하여 효율적인 메모리 관리  

### 공연 서비스

계층적 데이터 구조  
- 공연 → 회차 → 구역 → 좌석 4단계 구조  
- 각 계층별 무결성 검증으로 데이터 일관성 보장  

회차별 좌석 관리  
- 예매 완료/취소 시 실시간 좌석 상태 변경  
- 구역별 잔여 좌석 수 즉시 업데이트  

데이터 무결성  
- 티켓 오픈 후 공연/회차 정보 변경 불가  
- 예매 안정성 확보  

### 음식점 서비스

운영 정보 관리  
- 음식점 → 운영일 → 잔여 좌석 계층 구조  
- 검색, 페이지네이션, 정렬 기능 제공  
- S3 연동 이미지 업로드 지원  

좌석 관리 자동화  
- Redisson과 Lua 스크립트 활용  
- 스케줄러로 90분 간격 잔여 좌석 테이블 자동 생성  
- 오픈 시간부터 마감 시간까지 정책 기반 알고리즘 적용  

### 전시회 서비스

- 전시회 및 아티스트 정보 관리  
- 전시회 목록 조회 및 페이지네이션 지원  

### 유저 서비스

소셜 로그인  
- 구글, 카카오 소셜 로그인 지원  
- 기존 계정 자동 연동  
- 전략 패턴으로 소셜 서비스 확장성 확보  

백오피스 기능  
- 유저 목록 조회 및 페이지네이션  

### 백오피스 서비스

신청서 기반 서비스 등록  
- 관리자 승인 시 FeignClient로 서비스 등록 요청  
- Kafka Producer를 통한 알림 이벤트 발행  

권한 기반 접근 제어  
- 관리자/판매자별 역할에 따른 기능 차등 제공  

### 검색 서비스

- 공연, 전시, 음식점 통합 검색  
- 생성일자 기준 정렬 기능  
- 페이지네이션 지원  

### 알림 서비스

이벤트 기반 실시간 알림  
- Kafka Message 기반 이벤트 수신  
- SSE 방식으로 실시간 알림 전달  
- 예약 완료, 웨이팅 호출 등 다양한 이벤트 처리  

---

## 상세 기술 문서

각 서비스 레포지토리에서 **상세 기능, API 명세, 기술적 의사결정, 트러블슈팅** 등을 확인할 수 있습니다.  

- [예약 서비스](https://github.com/Lucky-Bikini-City-4/booking-service)
- [대기열 서비스](https://github.com/Lucky-Bikini-City-4/queue)  
- [웨이팅 서비스](https://github.com/Lucky-Bikini-City-4/waiting-service)  
- [공연 서비스](https://github.com/Lucky-Bikini-City-4/performance-service)  
- [음식점 서비스](https://github.com/Lucky-Bikini-City-4/restaurants-service)  
- [전시회 서비스](https://github.com/Lucky-Bikini-City-4/exhibition-service)  
- [검색 서비스](https://github.com/Lucky-Bikini-City-4/search-service)  
- [알림 서비스](https://github.com/Lucky-Bikini-City-4/alarm-service)  
- [유저 서비스](https://github.com/Lucky-Bikini-City-4/user-service)  
- [백오피스 서비스](https://github.com/Lucky-Bikini-City-4/backoffice-service)  

