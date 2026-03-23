# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

- **프로젝트명**: Dragon
- **장르**: SF 리니지 라이크 MMORPG
- **이 폴더의 목적**: 게임 기획서(GDD) 문서 작성 및 관리

## Document Convention

- 모든 기획서는 한국어로 작성
- 문서 형식: Markdown (.md)
- 파일명: 번호 접두사 + 영문 소문자, 하이픈 구분 (예: `01-game-concept.md`)
- 각 문서 상단에 문서 제목, 프로젝트명, 버전, 최종 수정일 명시
- 기획자(P), 프로그래머(D), 디자이너(A) 3인의 토론을 반영하여 작성
- 의견 충돌 시 기획자 의견 우선

## SF Theme Terminology

| 판타지 용어 | SF 용어 |
|------------|---------|
| 마법/MP | 에너지/테크 공격, EP (Energy Point) |
| 혈맹 | 군단 (Corps) |
| 성/성채 | 기지/스테이션/궤도 요새 |
| 공성전 | 기지 쟁탈전 |
| 몬스터 | 호스틸/기계수/드론 |
| 사냥터 | 작전 구역/소탕 구역 |
| 용/드래곤(생물) | 드래곤 AI/기계수 |
| 드래곤 에센스 | 드래곤 코어 |
| 마을 | 기지/거점 |
| 골드 | 크레딧 |
| 물약 | 메디키트/배터리팩 |
| 주문서 | 부스터 칩 |
| 스킬북 | 프로그램 모듈 |
| 전직 | 전환 |
| 전생 | 재기동(리부트) |
| 텔레포트 | 워프게이트 |
| 펫 | 드론/전투 유닛 |
| 탈것 | 호버바이크/전투 워커/강습정 |

## Document Structure

### Phase 1: 기반 설계
- `01-game-concept.md` — 핵심 비전, 타겟 유저, 차별점, 수익화 방향
- `02-world-setting.md` — 세계관(선행자 문명, 5대 드래곤 AI), 종족(4분파), 행성 구성
- `03-character-system.md` — 스탯, 병과(5계열), 전환, 레벨링, 외형

### Phase 2: 핵심 시스템
- `04-combat-system.md` — 타겟팅, 데미지 공식, 속성/상태이상, 사망, 무기, 자동 전투
- `05-skill-system.md` — 스킬 트리, 드래곤 게이지, EP 관리, 프로그램 모듈, 콤보
- `06-item-system.md` — 파워아머, 사이버네틱 임플란트, 강화, 나노 합성/무기공방
- `07-monster-hunting-ground.md` — 호스틸 분류, AI, 작전 구역, 드롭, 스캔/도감

### Phase 3: 사회/경쟁 시스템
- `08-pvp-system.md` — PK, 성향치, 결투, 전장, 현상금
- `09-guild-system.md` — 군단, 연합, 교전 선언, 군단 콘텐츠
- `10-siege-system.md` — 기지 쟁탈전, 영토전, 기지 사령관 보상
- `11-economy-system.md` — 크레딧, 거래 터미널, 개인상점, 경제 밸런스

### Phase 4: 콘텐츠 & 부가
- `12-quest-system.md` — 미션 분류, 메인 스토리, 업적
- `13-dungeon-system.md` — 인스턴스 작전, 보스 기믹, 궤도 타워
- `14-npc-town.md` — 기지, NPC, 안전지대, 기지 투자
- `15-pet-system.md` — 드론/전투 유닛, 해킹, 기동 유닛(탈것)

### Phase 5: 운영 & 수익화
- `16-event-system.md` — 출석, 정기/시즌/동적 이벤트
- `17-monetization.md` — 과금 모델, 캐시샵, 가챠 정책
- `18-ui-ux.md` — 홀로그래픽 HUD, PC/모바일 UI, 조작, 채팅

## Key Design Pillars

- **드래곤 코어**: 선행자 문명 AI의 유산. 링크/제작/강화의 핵심 재료, 경쟁 콘텐츠로만 획득
- **행성 영토 시스템**: 단순 기지 점령이 아닌 작전 구역 단위 영토 지배
- **성향치**: PK에 대가를 부여하되 금지하지 않는 긴장감 설계
- **No P2W**: 캐시로 전투력 직접 구매 불가, 외형/편의/시간 단축만 허용
- **SF 세계관**: 홀로그래픽 UI, 파워아머, 에너지 무기, 드론, 기계수 등 일관된 SF 톤 유지
