# 김민욱 | Backend Developer

Java와 Spring Boot로 API를 만들고, 데이터 정합성부터 배포 후 관찰과 복구까지 챙깁니다.

[포트폴리오 PDF](https://kr-uk.github.io/portfolio/portfolio-backend.pdf) · [웹에서 보기](https://kr-uk.github.io/portfolio/) · [이메일](mailto:kmwpcpk@gmail.com)

## 대표 프로젝트

### [DotShelf](https://github.com/kr-Uk/dotshelf) — 독서 기록·가상 책장 서비스

- **역할:** 6인 팀(백엔드 2명)의 배포 인프라와 백엔드 구조 설계 담당
- **판단:** 현재 버전을 유지한 채 새 버전을 health·smoke 검증한 뒤 Nginx를 전환하는 Blue-Green 배포 구성
- **운영:** Prometheus·Grafana·Loki로 색상별 상태를 확인하고, 문제 발생 시 이전 색으로 수동 복구하는 절차 마련

[데모](https://dotshelf-demo.pages.dev/) · [코드와 설계 기록](https://github.com/kr-Uk/dotshelf)

### [Itto](https://github.com/kr-Uk/itto-backend) — 위치 기반 소셜 매칭 서비스

- **역할:** 기획자 1명과 함께 Flutter 앱, Spring Boot 백엔드, 배포 환경을 개발
- **판단:** Firebase 중심의 데이터·매칭 처리를 서버로 옮기고 Redis와 H3 셀로 스침 후보를 축소
- **검증:** 20명 셀 기준 `User`·`UserSetting` 조회를 약 400회에서 2회로 축소. 차단·기존 관계 조회는 별도

[데모](https://itto-demo.pages.dev/) · [백엔드](https://github.com/kr-Uk/itto-backend) · [Flutter 앱](https://github.com/kr-Uk/itto-frontend) · [배포 구성](https://github.com/kr-Uk/itto-server)

### [BoneToBe](https://github.com/kr-Uk/bone-to-be) — AI 골격 분석 기반 의류 추천 서비스

- **역할:** 6인 팀(백엔드 3명)의 피드 도메인 API, 상세 조회, 좋아요 정합성 담당
- **조회:** 개별 조회 대조 구현의 핵심 9회와 QueryDSL 통합 조회 1회를 비교하고, 파일 조회 포함 DB 경로를 9회에서 3회로 축소
- **검증:** 로컬 PostgreSQL 15 Testcontainers에서 DB 경로 p50 `19.399ms → 7.883ms` 확인

[데모](https://bonetobe-demo.pages.dev/) · [코드와 측정 조건](https://github.com/kr-Uk/bone-to-be)

## 주로 다루는 영역

- **Backend:** Java 17/21, Spring Boot, Spring Security, JPA, QueryDSL
- **Data:** PostgreSQL, Redis, Flyway
- **Infra:** Docker, Nginx, GitLab CI/CD, AWS S3
- **Observability:** Prometheus, Grafana, Loki, Promtail

## 더 보기

- [PizzaEatHo](https://github.com/kr-Uk/pizzaeatho) — Flutter 피자 주문·커스터마이징 앱
- 알고리즘 풀이 기록: [Java](https://github.com/kr-Uk/boj-java) · [Python](https://github.com/kr-Uk/boj-python)
