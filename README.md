# 김민욱 | Backend Developer

Java와 Spring Boot로 도메인과 API를 설계하고, 데이터베이스부터 배포·모니터링까지 연결합니다.  
기능 구현에 그치지 않고 장애 원인을 확인하고 운영할 수 있는 구조를 만드는 데 관심이 있습니다.

[포트폴리오 보기](https://kr-uk.github.io/portfolio/) · [PDF 바로 열기](https://kr-uk.github.io/portfolio/portfolio-backend.pdf)

## 주로 다루는 영역

- **Backend**: Java 17/21, Spring Boot, Spring Security, JPA, QueryDSL
- **Data**: PostgreSQL, Redis, Flyway
- **Infra**: Docker, Nginx, GitLab CI/CD, AWS S3
- **Observability**: Prometheus, Grafana, Loki, Promtail

## 대표 프로젝트

### [DotShelf](https://github.com/kr-Uk/dotshelf) — 멀티플랫폼 독서 기록·가상 책장 서비스

- 6인 팀에서 인프라 총괄과 백엔드 구조 설계를 담당했습니다.
- App·DB 서버를 분리하고 Blue-Green 배포, GitLab CI/CD, 모니터링 환경을 구성했습니다.
- 첫 성공 배포에서 공개 요청 28건 모두 200 응답, 배포 중 5xx 0건을 확인했습니다.

`Java 21` `Spring Boot` `PostgreSQL` `Redis` `Docker` `Grafana`

### [Bone To Be](https://github.com/kr-Uk/bone-to-be) — AI 골격 인식 기반 의류 추천 서비스

- 커뮤니티 피드의 게시글·댓글·좋아요·스크랩·검색 기능을 담당했습니다.
- QueryDSL 통합 조회로 게시글 상세 조회의 N+1 문제를 제거했습니다.
- Actuator, Micrometer, Prometheus, Grafana 기반 애플리케이션 메트릭 환경을 구성했습니다.

`Java 17` `Spring Boot` `QueryDSL` `PostgreSQL` `Prometheus`

### [ITTO](https://github.com/kr-Uk/itto-backend) — 위치 기반 인연 연결 서비스

- 기획자 1명과 개발자 1명으로 진행해 Flutter 앱, Spring Boot 백엔드, 배포 환경을 구현했습니다.
- Firebase 중심 구조를 백엔드 중심 구조로 전환하고, H3와 Redis로 위치 후보 탐색 범위를 줄였습니다.
- 20명 기준 후보 탐색 쿼리를 약 400회에서 2회로 줄였습니다.

`Java 21` `Spring Boot` `Flutter` `H3` `Redis` `Docker`

## 더 보기

- [ITTO Frontend](https://github.com/kr-Uk/itto-frontend) · [Server](https://github.com/kr-Uk/itto-server)
- [PizzaEatHo](https://github.com/kr-Uk/pizzaeatho) — Flutter 기반 피자 주문·커스터마이징 앱
- [알고리즘 기록 — Java](https://github.com/kr-Uk/boj-java) · [Python](https://github.com/kr-Uk/boj-python)

