# CEO 파이프라인

> 🇺🇸 [English README](./README.md)

**CEO 청사진에서 로드맵에서 액션리스트로 — 팀 인수인계 요약 및 카테고리 자동 할당.**

## 사전 요구사항

- **Obsidian Vault** — 로드맵 및 액션리스트는 기본적으로 Obsidian 호환 `.md`로 산출
- **Claude Cowork 또는 Claude Code** 환경

## 목적

전략적 비전이 실행 가능한 액션 없이는 꿈에 불과합니다. CEO-Pipeline은 상위 레벨 청사진 또는 로드맵을 도메인(기획, 디자인, 개발)별로 자동 카테고리되는 액션리스트로 변환하고, 각 액션에 팀 인수인계 요약을 생성합니다. "샤워 효과"는 아이디어가 생각에서 실행으로 흐르도록 합니다.

## 사용 시점 및 방법

CEO 레벨 청사진, 전략 성명, 로드맵이 실행 가능하게 되어야 할 때 이 스킬을 사용하세요. 비전을 제공하고 스킬은 세 계층으로 연쇄: 액션을 기획, 디자인, 개발로 자동 카테고리화; 각 카테고리별 팀 특정 인수인계 요약 생성; 종속성과 순서 지표화. 입력 청사진 → 팀 요약이 포함된 카테고리화 액션리스트.

## 사용 예시

| 상황 | 프롬프트 | 결과 |
|---|---|---|
| 제품 전략→스프린트 계획 | `"CEO-pipeline: Q2에 3개 신규 통합 배포"` | 청사진→기획 액션 + 디자인 액션 + 개발 액션; 각각 팀 요약 포함 |
| 조직 개편 | `"파이프라인: Q3까지 제품 주도 GTM으로 이동"` | 청사진→기획 (채용, 인센티브) + 디자인 (플레이북) + 개발 (자동화); 각 팀별 인수인계 |
| 시장 확장 | `"APAC 확장 — 6개월 계획으로 변환"` | 전략→기획 (지역화, 채용) + 디자인 (지역 GTM) + 개발 (제품 적응) |

## 핵심 기능

- 자동 액션 카테고리화: 기획, 디자인, 개발, 또는 혼합
- AI 생성 팀 인수인계 요약 각 액션별—맥락, 성공 기준, 담당자 가이드
- 종속성 추적 및 순서 권장사항
- 자원 추정 및 시간표 매핑
- 전체 전략 이니셔티브에서 작동: 제품, 조직, 시장, 위기

## 연관 스킬

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — planning-skill이 청사진 구조화; ceo-pipeline은 실행
- **[deliverable-engine](https://github.com/jasonnamii/deliverable-engine)** — deliverable-engine이 로드맵과 액션리스트를 프레젠테이션 포맷
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill이 진단; ceo-pipeline이 권장 전략 실행

## 설치

```bash
git clone https://github.com/jasonnamii/ceo-pipeline.git ~/.claude/skills/ceo-pipeline
```

## 업데이트

```bash
cd ~/.claude/skills/ceo-pipeline && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용할 수 있습니다.

## Cowork 스킬 생태계

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT 라이선스 — 자유롭게 사용, 수정, 공유하세요.