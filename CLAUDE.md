# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

- **프로젝트명**: Dragon
- **장르**: 리니지 라이크 MMORPG
- **이 폴더의 목적**: 게임 기획서(GDD) 문서 작성 및 관리

## Document Convention

- 모든 기획서는 한국어로 작성
- 문서 형식: Markdown (.md)
- 파일명: 번호 접두사 + 영문 소문자, 하이픈 구분 (예: `01-game-concept.md`)
- 각 문서 상단에 문서 제목, 프로젝트명, 버전, 최종 수정일 명시
- 기획자(P), 프로그래머(D), 디자이너(A) 3인의 토론을 반영하여 작성
- 의견 충돌 시 기획자 의견 우선

## Document Structure

### Phase 1: 기반 설계
- `01-game-concept.md` — 핵심 비전, 타겟 유저, 차별점, 수익화 방향
- `02-world-setting.md` — 세계관, 종족, 대륙 구성, 주요 세력
- `03-character-system.md` — 스탯, 직업, 전직, 레벨링, 외형

### Phase 2: 핵심 시스템
- `04-combat-system.md` — 타겟팅, 데미지 공식, 상태이상, 사망
- `05-skill-system.md` — 스킬 트리, 드래곤 스킬, 강화, 콤보
- `06-item-system.md` — 장비, 강화, 제작, 인벤토리
- `07-monster-hunting-ground.md` — 몬스터 분류, AI, 사냥터, 드롭

### Phase 3: 사회/경쟁 시스템
- `08-pvp-system.md` — PK, 성향치, 결투, 전장, 현상금
- `09-guild-system.md` — 혈맹, 동맹, 적대, 혈맹 콘텐츠
- `10-siege-system.md` — 공성전, 영토전, 성주 보상
- `11-economy-system.md` — 재화, 거래소, 개인상점, 경제 밸런스

### Phase 4: 콘텐츠 & 부가
- `12-quest-system.md` — 퀘스트 분류, 메인 스토리, 업적
- `13-dungeon-system.md` — 던전 유형, 보스 기믹, 천공의 탑
- `14-npc-town.md` — 마을, NPC, 안전지대
- `15-pet-system.md` — 펫, 테이밍, 탈것

### Phase 5: 운영 & 수익화
- `16-event-system.md` — 출석, 정기/시즌/동적 이벤트
- `17-monetization.md` — 과금 모델, 캐시샵, 가챠 정책
- `18-ui-ux.md` — HUD, PC/모바일 UI, 조작, 채팅

## Key Design Pillars

- **드래곤 에센스**: 시조룡의 유산. 각성/제작/강화의 핵심 재료, 경쟁 콘텐츠로만 획득
- **영토 시스템**: 단순 성 점령이 아닌 사냥터 단위 영토 지배
- **성향치**: PK에 대가를 부여하되 금지하지 않는 긴장감 설계
- **No P2W**: 캐시로 전투력 직접 구매 불가, 외형/편의/시간 단축만 허용
