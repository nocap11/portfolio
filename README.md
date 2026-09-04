# 최민규 | Mingyu Choe

Python·FastAPI 기반 백엔드를 개발하고 있습니다. API 구현과 함께 데이터의 변경 흐름, 외부 서비스 연동, 테스트로 확인할 수 있는 동작을 기록합니다.

[GitHub · nocap11](https://github.com/nocap11)

## 기술

- **Backend:** Python, FastAPI, Pydantic
- **Database:** PostgreSQL, SQLAlchemy 2.x, Alembic
- **Test & Development:** pytest, Docker, GitHub Actions, Git

## 프로젝트

### I-SPOT — AI 상담 기록 서비스

상담 음성의 전사와 AI 요약을 상담사가 검수·수정·승인할 수 있도록 지원하는 팀 프로젝트입니다. 현재 개발 중입니다.

**담당:** Backend 개발 및 팀 산출물 통합 작업

- 사례·상담 회차 API, 인증·권한, 음성 업로드
- 전사 버전 관리와 AI 결과 저장
- 상담사 검수·승인, 수정본 보존과 Audit Log
- STT·AI 어댑터, Mock Provider, API 테스트와 개발 환경

[프로젝트 상세와 구현 근거](projects/I-SPOT.md) · [팀 저장소](https://github.com/jeongin721/I-SPOT) · [통합 PR #6](https://github.com/jeongin721/I-SPOT/pull/6)

## 개발 기록

문제의 재현, 선택한 방법, 검증 결과와 남은 한계를 작업 단위로 정리합니다.

- [개발 기록 목록](logs/README.md)
- [2026-09-04 · I-SPOT 산출물 점검과 후속 작업](logs/2026-09-04-ispot-integration-review.md)

이 저장소는 개인 포트폴리오와 개발 기록을 관리합니다. 팀 전체 산출물과 개인 담당 범위를 구분하고, 진행 중인 작업은 완료된 성과와 분리해 표시합니다.
