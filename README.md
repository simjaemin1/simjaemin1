## 심재민

백엔드 개발자를 지향하고 있습니다. 데이터 정합성과 동시성 제어에 관심이 있어, 동시 쓰기 경합에서 상태가 어긋나지 않도록 구성하는 문제를 주로 다뤄 왔습니다.

서울대학교 컴퓨터공학부 · 2027년 2월 졸업예정 · simjaemin1@naver.com

---

### 프로젝트

| 프로젝트 | 내용 | 링크 |
|---|---|---|
| Slotlink (운영판) | 선착순 신청 시스템입니다. 실제 고등학교 설명회에 투입하여 800명 정원이 32초 만에 마감되는 상황을 정원 초과 없이 처리했습니다. 신청 번호는 1번부터 800번까지 중복과 누락 없이 배정되었습니다. Firestore 트랜잭션과 지수 백오프·지터 재시도를 적용했습니다 | [slotlink-school](https://github.com/simjaemin1/slotlink-school) |
| Slotlink (락 비교 실험) | 동일한 요구사항을 Spring으로 재구현하여 비관적 락, 낙관적 락, 분산 락(Redisson) 세 전략을 Strategy 패턴으로 교체 가능하도록 구성하고, 부하 조건 두 가지에서 k6로 측정·비교했습니다. Testcontainers 통합 테스트 15개를 함께 작성했습니다 | [slotlink-spring](https://github.com/simjaemin1/slotlink-spring) |
| 미니 | 51개 NPC 마을이 자율적으로 운영되는 경제 시뮬레이션입니다. 복수의 AI 에이전트에 작업을 분배하며 진행 중이고, 설계 원칙과 검증 기준을 수립하여 산출물을 검사하는 방식을 실험하고 있습니다 | [Mini](https://github.com/simjaemin1/Mini) |
| Franchat | 지인 기반 익명 채팅·SNS 앱입니다. 개발을 담당하여 두 스토어에 출시하고 1년 넘게 운영하고 있습니다. 매칭 레이스 컨디션 해결, 연결과 활동 상태 분리 등을 다뤘습니다 *(저장소 비공개 · 앱 소유자는 팀원)* | [App Store](https://apps.apple.com/kr/app/franchat/id6743160010) · [Google Play](https://play.google.com/store/apps/details?id=com.sjsong.franchat) |
| Daily Insight | 한국 주식 추천 서비스 백엔드입니다(6인 팀). Django REST Framework를 사용했으며, 요청마다 발생하던 S3 왕복을 제거하여 조회 응답을 단축하고 테스트 커버리지를 74%에서 99%로 개선했습니다 *(수업 팀 프로젝트로 저장소 비공개)* | — |

비공개 저장소의 코드는 면접 시 화면 공유로 설명드릴 수 있습니다.

---

### 기술 스택

언어 — Java · Python · TypeScript / JavaScript

백엔드 — Spring Boot · Spring Data JPA · Django REST Framework · Firebase Cloud Functions

데이터 — MySQL · Redis · Firestore · Realtime Database

테스트·측정 — JUnit 5 · Testcontainers · k6

클라이언트 — React · React Native (Expo)

인프라 — AWS · Firebase · Vercel · Docker

---

### 글

Slotlink의 설계 과정과 의사결정을 10편으로 연재했습니다 — [블로그](https://blog.naver.com/simjaemin1)
