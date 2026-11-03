# 👩‍💻 API를 쓰는 쪽과 만드는 쪽을 모두 경험한 개발자, 손주희입니다.

프론트엔드 인턴으로 10개월간 AI SaaS 4개 서비스를 만들며, 서버 응답 때문에 화면이 멈추는 문제를 자주 겪었습니다.<br/>
그 API를 직접 설계하고 싶어 백엔드로 영역을 넓혔고, Spring Boot 기반 MSA 프로젝트에서 상품·주문 서비스를 맡았습니다.

<br/>

## 🖥 Backend

**🛒 Fitzza** · 패션 커머스 MSA 플랫폼 (8인 팀, 2026.10 - 2026.11) · [Repository](https://github.com/duckfairy-wak/fitzza_msa_finalproject)

- **Role**: 상품·주문 서비스 백엔드 (Java 21, Spring Boot 3, JPA, PostgreSQL)
- **Key Work**: 장바구니 비관적 락 적용과 8개 스레드 동시성 테스트, 주문 시점 결제 단가 스냅샷, API별 허용 서비스를 선언하는 서비스 간 토큰 인증
- **Ops**: 크롤링 상품 약 3,000건 upsert 적재, 비공개 S3 이미지 Presigned URL 제공, Flyway 스키마 관리, 로컬 Jaeger 분산 추적, k6 스모크 테스트

**🏦 FIN-M** · MSA 기반 디지털 계좌 플랫폼 (4인 팀, 2026.07 - 2026.08) · [Repository](https://github.com/sonjoohee/fin-account-hub)

- **Role**: 계좌 서비스 백엔드 + 프론트엔드 전담 (Spring Boot 3.5, Spring Cloud, MariaDB, React)
- **Key Work**: 이체 서비스의 OpenFeign 호출이 JWT 필터에 막힌 401 문제를 인증 책임 분리로 해결

**🎪 Festival AI** · 공공데이터 기반 지역 축제 큐레이션 (2026.07 - 2026.08) · [Repository](https://github.com/sonjoohee/festival_ai)

- **Role**: 리뷰 도메인 백엔드 + 프론트엔드 전반 (Spring Boot 3.5, JPA, React)
- **Key Work**: 내부 DB에 없는 축제를 리뷰 작성 시 먼저 저장하는 Lazy Create, AI 요약 실패 시에도 축제 정보를 보여 주는 장애 분리

<br/>

## 🎨 Frontend

**🚀 AutoDisplay** · AI 기반 디지털 사이니지 SaaS ((주)유저커넥트 인턴, 2025.09 - 2025.12)

- **Role**: Frontend Developer (React, Jotai)
- **Key Work**: 기준 해상도 비율 스케일링 엔진으로 단일 코드베이스에서 여러 해상도 대응(CLS 0.01), 메모이제이션 후 INP 88ms, 1분 폴링을 10분 주기 Heartbeat로 전환

**🤖 InterviewX** · 생성형 AI 페르소나 인터뷰 SaaS ((주)유저커넥트 인턴, 2025.01 - 2025.06)

- **Role**: Frontend Developer (React, Jotai)
- **Key Work**: 백엔드 팀과 응답 구조를 재정의하고 최대 10회 자동 재시도를 넣어 데이터 수신 성공률 약 90% 확보, D3.js 분석 리포트 시각화

**🎬 CineStream** · TMDB API 기반 영화 탐색 서비스 · [Repository](https://github.com/sonjoohee/CineStream_ver2)

- **Key Work**: CRA + JavaScript 레거시를 Next.js App Router와 TypeScript로 전환

**👥 ITeaMoa** · IT 특화 팀 빌딩 플랫폼 (2024.07 - 2024.12) · [Repository](https://github.com/ITeaMoa/frontend-service)

- **Key Work**: Spring·Django 두 백엔드 팀과 에러 응답 규약 합의, GitHub Actions로 배포 시간 15분 → 2분

**🏫 DSchool** · AI 추천 학부모 커뮤니티 (캡스톤, 2023.08 - 2024.05) · [Repository](https://github.com/sonjoohee/DSchool-AI-Community)

- **Key Work**: KoNLPy와 Doc2Vec으로 게시글을 벡터화해 유사 게시글 추천, Elasticsearch 연동, React 화면 구현

<br/>

## 🏆 Awards & Certifications
| Date | Title | Organizer |
| --- | --- | --- |
| 2025.12 | OPIc IH | ACTFL |
| 2024.12 | SQL 개발자 (SQLD) | 한국데이터베이스진흥센터 |
| 2024.06 | 캡스톤 디자인 경진대회 장려상 (DSchool) | 한양대학교 ERICA SW중심사업단 |
| 2024.05 | SID 본선 진출 | 한양대학교 ERICA 창업교육센터 |
| 2023.08 | PRE-스타트업톤 마라톤 최우수상 | 한양대학교 ERICA 창업교육센터 |
| 2023.04 | SW 창업아이디어톤 우수상 | 한양대학교 ERICA 소프트웨어융합대학 |
| 2022.11 | SWIM PRE-스타트업톤 최우수상 | 한양대학교 ERICA 창업교육센터 |

<br/>

## 📚 Tech Stack
| Category | Technologies |
| --- | --- |
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat&logo=spring&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat&logo=flyway&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white) ![Jotai](https://img.shields.io/badge/Jotai-000000?style=flat&logo=ghost&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) |
| **Infra & Ops** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) ![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?style=flat&logo=jaeger&logoColor=black) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat&logo=k6&logoColor=white) |

<br/>

## 📬 Contact & Channel
- **Email**: star7613@naver.com
- **Tech Blog**: [실무 트러블슈팅 및 학습 기록 (Tistory)](https://joohee0826.tistory.com/category/React%20%EC%83%9D%ED%83%9C%EA%B3%84/TroubleShooting)
