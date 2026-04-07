# Hi, I'm Taeyoung Park 👋
### Backend Developer who builds with design thinking and judgment

> *"AI 시대, 설계력과 판단력으로 진짜 생산성을 만드는 백엔드 개발자 박태영입니다"*

---

## 🛠 Tech Stack

**Core**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![MSA](https://img.shields.io/badge/MSA-FF6B6B?style=flat-square&logoColor=white)


**Experience**

![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![OAuth2.0](https://img.shields.io/badge/OAuth2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-0078D4?style=flat-square&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0078D4?style=flat-square&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 🚀 Projects
 
### 🏆 RareGO — 실시간 레고 경매 이커머스 플랫폼
> 팀 프로젝트 (6인) | 2026.01 ~ 2026.02 | **최우수상 수상** (8팀 중 1위)
 
| 기여 | 성과 |
|---|---|
| Kafka **Outbox / Inbox / DLT** 패턴 도입 | K8s Rolling Update 환경에서 이벤트 유실·중복 처리율 **0%** 달성 |
| **CQRS + Elasticsearch** 도입, 상품·경매 데이터 비정규화 설계 | 에러율 **0%**, p95 **184.94ms** (100 VU 기준) / 모듈 간 내부 API 호출 완전 제거 |
| AWS S3 **Presigned URL** 직접 업로드 구조 전환 | 상품 등록 API 응답시간 820ms → 120ms (**85% 단축**) / 요청당 힙 점유 6MB → 0MB |
| **Vector DB + RAG** / **ChatClient + Flux** AI 시작가 추천 | 내부・외부 데이터 기반 경매 시작가 추천 시스템, 외부 API 장애 시 서비스 정상 동작 보장 |
 
`Java 21` `Spring Boot` `Kafka` `Elasticsearch` `MySQL` `Redis` `AWS S3` `K8s` `Spring AI`
 
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prgrms-be-adv-devcourse/beadv4_4_BugZero_BE)
 
---
 
### 🪙 CoinWash — 세탁소 기기 실시간 현황·예약·알림 플랫폼
> 개인 프로젝트 | 2025.05 ~ 2025.07
 
| 기여 | 성과 |
|---|---|
| Redis **Hash 구조**로 N+1 문제 해소 (String+Set → Hash 단일 조회) | 응답속도 2,000ms → 1,000ms (**50% 향상**) / 평균 API 5.4ms → 2.2ms (**60% 개선**) |
| **인덱스** 설계, Full Table Scan → Index Scan 전환 | 조회성능 98.5% 향상 |
| Docker 배포 스크립트 단계별 메모리 관리 전략 도입 | EC2 t2.micro 환경 메모리 50% 이상 감소, 배포 성공률 **100%** 달성 |
| 비관적 락(예약) / 낙관적 락(포인트) 상황별 동시성 전략 분리 | 동시 요청 시 데이터 정합성 보장 |
 
`Java` `Spring Boot` `MySQL` `Redis` `AWS EC2·RDS·ElastiCache` `SSE` `Docker` `JMeter`
 
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/P-Taeyoung/coinwash)
 
---
 
### 💬 BootTalk — 부트캠프 정보 공유 플랫폼
> 팀 프로젝트 (6인, Back 4) | 2025.03 ~ 2025.04
 
| 기여 | 성과 |
|---|---|
| **Nginx 리버스 프록시** 도입으로 교차 출처 문제 근본 해결 | 배포 환경 CORS·쿠키 전송 문제 완전 해소, 소셜 로그인 정상 동작 |
| **OAuth2.0** 기반 네이버 소셜 로그인 + JWT 쿠키 인증 구현 | 신규·기존 사용자 분기 처리 및 인증 필요 API 접근 제어 |
| SSE + **이벤트 발행 패턴** + 전용 스레드 풀 격리 | 알림 로직과 비즈니스 로직 결합도 제거 / 대량 알림 시에도 메인 로직 자원 보호 |
| 비관적 락 기반 포인트 동시성 제어, **목적별 쿼리 분리** | 불필요한 락 제거로 단순 조회 리소스 낭비 방지 |
 
`Java 17` `Spring Boot` `Spring Security` `MySQL` `Redis` `OAuth2.0` `JWT` `SSE` `Nginx` `Docker`
 
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BootTalk-Service/boot-talk-back)
 

---

## 📝 Latest Blog Posts
<!-- BLOG-POST-LIST:START -->
- [디스크 저장 방식](https://velog.io/@zipmandu/%EB%94%94%EC%8A%A4%ED%81%AC-%EC%A0%80%EC%9E%A5-%EB%B0%A9%EC%8B%9D)
- [Elasticsearch  원리](https://velog.io/@zipmandu/Elasticsearch-%EC%9B%90%EB%A6%AC)
- [Elasticsearch란 무엇인가](https://velog.io/@zipmandu/Elasticsearch%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80)
- [RabbitMQ가 라우팅에 정말 유리한가?](https://velog.io/@zipmandu/RabbitMQ%EA%B0%80-%EB%9D%BC%EC%9A%B0%ED%8C%85%EC%97%90-%EC%A0%95%EB%A7%90-%EC%9C%A0%EB%A6%AC%ED%95%9C%EA%B0%80)
- [RabbitMQ Exchange 라우팅](https://velog.io/@zipmandu/RabbitMQ-Exchange-%EB%9D%BC%EC%9A%B0%ED%8C%85)
<!-- BLOG-POST-LIST:END -->

---

## 🏅 Awards & Education

| | |
|---|---|
| 🥇 **최우수상** | 프로그래머스 백엔드 단기심화 데브코스 최종 프로젝트 평가 8팀 중 1위 |
| 📚 **프로그래머스 백엔드 단기심화 데브코스** | 2025.12 ~ 2026.02 |
| 📚 **제로베이스 백엔드 스쿨** | 2024.10 ~ 2025.04 |

---


<p align="left">
  <a href="mailto:pty10510@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://velog.io/@zipmandu/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white"/></a>
</p>
