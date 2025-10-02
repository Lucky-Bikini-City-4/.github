
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
- [기술적 의사결정](#-기술적-의사결정)
- [트러블 슈팅](#-트러블-슈팅)
- [프로젝트 회고](#-프로젝트-회고)

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
<img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
<img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=Amazon%20AWS&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white">
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
</p>

### Authentication & Security

<p>
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white">
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
</p>

### Message Queue & Real-time

<p>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
<img src="https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logoColor=white">
<img src="https://img.shields.io/badge/SSE-FF6600?style=for-the-badge&logoColor=white">
</p>

### Test

<p>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white">
<img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white">
</p>

### Tools

<p>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
<img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=IntelliJ%20IDEA&logoColor=white">
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
</p>

---

## 🏗️ 아키텍처

![System Architecture](https://github.com/user-attachments/assets/9be78450-0b8c-44f4-b2ab-40c4405eb54d)

---

## 📊 ERD

![ERD Diagram](https://github.com/user-attachments/assets/8c6e3c3d-a97e-4c62-ae27-20303c841014)

**ERD 상세 보기**: [ERDCloud 링크](https://www.erdcloud.com/d/LbMdMjtF48WoL7GWt)

---

## ✨ 주요 기능

### 1️⃣ 예약 서비스

**표준화된 예약 처리**
- 서비스별 예약 요청을 하나의 표준화된 형식으로 처리
- 공연, 전시, 음식점 예약을 통합 관리

**좌석 선점 시스템**
- Redis Lua 스크립트를 활용한 원자성 보장
- 동시성 제어를 통한 안정적인 예약 처리

### 2️⃣ 대기열 서비스

**대규모 트래픽 대응**
- 국내 공연 좌석 최대 예약 규모(약 10만 명)를 기준으로 설계
- Redis Sorted Set 기반 FIFO 순차 입장 관리

**보안 및 권한 제어**
- 토큰 이중 구조로 위변조 방지
- 스케줄러를 통한 활성 토큰 발급으로 순차 입장 제어

### 3️⃣ 웨이팅 서비스

**음식점 웨이팅 관리**
- 점주/손님 간 상호작용을 통한 웨이팅 상태 관리
- 호출 및 응답 시 실시간 알림 제공
- 무응답 2회 시 자동 노쇼 처리

**웨이팅 순서 관리**
- Redis 캐시 기반 빠른 상태 조회
- 완료되지 않은 웨이팅만 캐시에 저장하여 효율적인 메모리 관리

### 4️⃣ 공연 서비스

**계층적 데이터 구조**
- 공연 → 회차 → 구역 → 좌석 4단계 구조
- 각 계층별 무결성 검증으로 데이터 일관성 보장

**회차별 좌석 관리**
- 예매 완료/취소 시 실시간 좌석 상태 변경
- 구역별 잔여 좌석 수 즉시 업데이트

**데이터 무결성**
- 티켓 오픈 후 공연/회차 정보 변경 불가
- 예매 안정성 확보

### 5️⃣ 음식점 서비스

**운영 정보 관리**
- 음식점 → 운영일 → 잔여 좌석 계층 구조
- 검색, 페이지네이션, 정렬 기능 제공
- S3 연동 이미지 업로드 지원

**좌석 관리 자동화**
- Redisson과 Lua 스크립트 활용
- 스케줄러로 90분 간격 잔여 좌석 테이블 자동 생성
- 오픈 시간부터 마감 시간까지 정책 기반 알고리즘 적용

### 6️⃣ 전시회 서비스

- 전시회 및 아티스트 정보 관리
- 전시회 목록 조회 및 페이지네이션 지원

### 7️⃣ 유저 서비스

**소셜 로그인**
- 구글, 카카오 소셜 로그인 지원
- 기존 계정 자동 연동
- 전략 패턴으로 소셜 서비스 확장성 확보

**백오피스 기능**
- 유저 목록 조회 및 페이지네이션

### 8️⃣ 백오피스 서비스

**신청서 기반 서비스 등록**
- 관리자 승인 시 FeignClient로 서비스 등록 요청
- Kafka Producer를 통한 알림 이벤트 발행

**권한 기반 접근 제어**
- 관리자/판매자별 역할에 따른 기능 차등 제공

### 9️⃣ 검색 서비스

- 공연, 전시, 음식점 통합 검색
- 생성일자 기준 정렬 기능
- 페이지네이션 지원

### 🔟 알림 서비스

**이벤트 기반 실시간 알림**
- Kafka Message 기반 이벤트 수신
- SSE 방식으로 실시간 알림 전달
- 예약 완료, 웨이팅 호출 등 다양한 이벤트 처리

---

## 🎯 기술적 의사결정

### 1. 실시간 예약을 위한 동시성 제어 기술

#### 🔒 요구 사항
- 대규모 동시 접속에도 안정적으로 작동하는 예약 서비스

#### 🔐 비교 대안

| 방안 | 장점 | 단점 |
|------|------|------|
| RDB와 Redis 캐시 | 초기 구현 용이 | 확인 과정이 여러 번 발생, 높은 부하 환경에서 성능 병목 |
| **Redis + Lua 스크립트** ✅ | 인메모리 기반으로 빠른 처리, 높은 처리량 | DB 저장을 위한 별도 구현 필요, 러닝 커브 존재 |

#### 🔑 결정 및 근거
- Lua 스크립트 사용 시 대규모 요청에 대한 성능이 우수
- 좌석 선점에 대한 **원자성 보장**
- Redis의 인메모리 특성으로 빠른 응답 시간 확보

---

### 2. 공연 예매 서비스와 좌석 관리 간 비동기 통신

#### 🔒 요구 사항
- 예약 완료 시 공연 서비스의 좌석 상태 업데이트
- 서비스 간 느슨한 결합 유지
- 동시성 문제 최소화

#### 🔐 비교 대안

| 방안 | 장점 | 단점 |
|------|------|------|
| **Apache Kafka** ✅ | 높은 처리량 및 내구성, 분산 로그 시스템 | 설정과 운영이 복잡 |
| RabbitMQ | 설정 간단, 다양한 라우팅 패턴 | 대규모 동시 요청 처리 한계 |
| AWS SQS | 완전 관리형, 운영 부담 최소화 | 대규모 트래픽 시 지연 가능, FIFO 큐 비용 증가 |

#### 🔑 결정 및 근거
- **높은 처리량**: 분산 로그 시스템과 순차 디스크 쓰기로 대규모 트래픽 처리
- **내구성**: 브로커 디스크에 로그 저장으로 데이터 손실 방지
- **확장성**: 새로운 컨슈머 추가만으로 기능 확장 가능

---

### 3. Server-Sent Event를 통한 알림 발송

#### 🔒 요구 사항
- 예매 완료, 웨이팅 호출 등 실시간 알림 필요
- 서버에서 클라이언트로의 단방향 통신

#### 🔐 비교 대안

| 방안 | 장점 | 단점 |
|------|------|------|
| Polling | 구현 단순 | 주기 사이 변화 수신 불가, 불필요한 트래픽 증가 |
| Web Socket | 양방향 통신, 지연 거의 없음 | 운영 복잡성 증가, API Gateway 설정 비용 |
| **SSE** ✅ | 단방향 통신 최적화, 표준 HTTP 기반 | 브라우저 연결 수 제한 (약 6개) |

#### 🔑 결정 및 근거
- 알림은 **서버→클라이언트 단방향 중심**
- Polling 대비 **불필요한 트래픽 크게 감소**
- WebSocket 대비 **운영 복잡도 감소**
- 표준 HTTP 기반으로 프록시/방화벽 친화적

---

### 4. Token 기반 대기열 구현

#### 🔒 요구 사항
- 공정한 FIFO 방식 입장 관리
- 입장권을 가진 사용자는 1번만 입장 가능
- 위/변조 방지 및 제한 시간 설정

#### 🔐 비교 대안

| 방안 | 장점 | 단점 |
|------|------|------|
| **Token 기반** ✅ | 간단한 위변조 방지, 서버 부하 감소 | 토큰 TTL 튜닝 필요 |
| Session 기반 | 서버가 상태 소유, 강제 종료 즉시 가능 | 복구 금지를 위한 추가 로직 필요 |

#### 🔑 결정 및 근거
- 유저 정보와 시간 기반 토큰으로 **원자성 확보**
- **중복 입장 방지**
- Redis Sorted Set으로 **FIFO 원칙 보장**
- 스케줄러로 **순차 입장 제어**

---

### 5. 데이터베이스 선택: PostgreSQL vs MySQL

#### 🔒 요구 사항

**백오피스**
- 다양한 마이크로서비스 연계 데이터 처리
- 추후 로그/사용자 분석 가능

**음식점**
- 예약 가능 좌석 수 실시간 제공
- 예약 데이터 접근 빈도 높음

#### 🔐 비교 및 결정

| 서비스 | 선택 | 이유 |
|--------|------|------|
| 백오피스 | *
