> **2026-10-25 신규 미션 작성 경로(B1-2):** [`training/round-04-agent/`](training/round-04-agent/README.md) — 신규 코드는 `training/round-04-agent/04-src/`에만 작성합니다. 기존 Round 01~03 및 루트의 내용은 과거 수행·참고 이력으로 보존합니다. **현재 새 Round는 PLAN_ONLY / NOT_STARTED이며 사용자 개발 승인 전 코드 실행·수정·배포 금지**입니다. 중앙 기준: [15개 미션 신규 실행 허브](https://github.com/MetaStudy999/codyssey-basic/tree/main/training/round-04-agent).

# Codyssey Basic B4-2

## 구분
- 선택 미션 (OPTIONAL)
- 현재 훈련 체계: Round 01 — CLEAR
- 현재 작업 모드: Phase A — REFERENCE BUILD

## 시작 위치
`training/round-01-clear/BEGINNER-GUIDE.md`부터 진행합니다.

## 공식 원본
- `b4-2-mission.pdf`
- `b4-2-mission.md`
- `b4-2-evaluation.md`

공식 원본은 수정하지 않습니다.

## Round 01 Reference Build

현재 `training/round-01-clear/reference/`에 React Study Cards SPA 기준본을 준비했습니다.

핵심:
- React 18 + Vite + React Router
- 6개 named route + Not Found
- 10개 reusable components
- `useItems()` / `useItemDetail()` custom hooks
- controlled form + required validation + submitting UI
- common loading/error/empty states
- Supabase remote CRUD
- `.env.example` + Supabase schema
- deployment SPA rewrite
- Requirements Mapping / Evaluation Q&A / Evidence Guide

## 상태

**Reference 핵심 기준본 준비 완료 / Runtime 미시작 / `✅ CLEAR` 아님**

실제 Supabase project/remote CRUD, production build, Vercel/Netlify URL과 deployed CRUD는 Phase C에서 검증합니다.
