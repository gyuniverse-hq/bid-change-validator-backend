# bid-change-validator-backend

Backend and data workspace for the Bid Change Validator project.

## Owners

- Backend / API: 전진환
- DB / Data: 정예린

## Scope

- Backend API 구현
- DB 스키마 및 데이터 관리
- 나라장터 실제 데이터 연결 및 정제
- Frontend 요청 처리용 비즈니스 로직
- LLM / RAG 결과 연동 및 저장

## Out of Scope

- Frontend UI / UX 구현
- LLM / RAG 내부 추론 로직 구현
- 공고문 기반 평가 프롬프트 및 Evaluation 설계 소유권

## Weekend Parallel Work

이 저장소는 메인 통합 저장소에 반영하기 전 주말 병렬 작업을 위한 Backend / Data workspace입니다.
빠른 API·DB 프로토타이핑을 우선하되, Frontend 및 LLM·RAG와 맞닿는 인터페이스는 메인 저장소의 공통 계약 문서를 기준으로 정리합니다.

## Branches

- `main`: 현재 Backend / Data 기준선
- `develop`: 병렬 개발 통합 브랜치
- 작업 브랜치: `feat/SKN34-XX-summary`, `fix/SKN34-XX-summary`

## Main Repository

- https://github.com/gyuniverse-hq/bid-change-validator
