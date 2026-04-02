# UI/UX Pro Max 개요

## 원본 저장소 역할

- repo: `ui-ux-pro-max-skill`
- source: `https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git`
- latest synced commit: `4255c218a676`
- current skill version basis: `2.5.0`
- one-line summary: **다중 플랫폼 AI 어시스턴트를 위한 디자인 인텔리전스 스킬 + 설치 CLI + 데이터 자산 저장소**

## 이번 판단

기존 가이드는 설명이 쉬운 대신, 원본의 실제 강점을 너무 약하게 보여 줬다.

- 초보자 친화성은 높았다
- 하지만 reasoning engine, design-system generation, CLI, platform coverage, industry rule set은 frontdoor에서 약했다

그래서 이번 개정은 이 저장소를 **디자인 입문서**가 아니라 **배포 가능한 디자인 의사결정 시스템**으로 다시 설명하는 데 초점을 맞춘다.

## 최근 upstream 커밋

- `4255c21 Merge pull request #209 from nextlevelbuilder/feat/enhancement-issues`
- `01944c4 merge: resolve conflicts with main branch`
- `49c9fbe Merge pull request #205 from Krishna-Modi12/feat/threejs-stack`
- `ddef277 feat(threejs): complete Three.js stack integration`
- `acc9c74 fix(core): correct threejs STACK_CONFIG format and add missing stacks from main`
- `0d58617 fix(cli): check dir existence before reporting removal in uninstall`

## 원본에서 확인한 핵심 현실

### 1. 이 스킬은 “예쁜 UI 추천기”보다 design-system generator에 가깝다

원본 README의 중심 메시지는 v2.0의 **Intelligent Design System Generation**이다.

즉 흐름은 대략 이렇다.

1. 사용자 요청 입력
2. 제품 유형 / 스타일 / 컬러 / 패턴 / 타이포를 병렬 탐색
3. reasoning rule과 우선순위로 조합
4. 패턴 + 스타일 + 색상 + 폰트 + 안티패턴 + 체크리스트를 출력

이 구조를 이해해야 원본의 가치가 제대로 보인다.

### 2. 숫자 스펙 자체가 이 스킬의 설계 범위를 말해 준다

원본 메타데이터와 README 기준으로 이 저장소는 다음 범위를 다룬다.

- 67 UI styles
- 161 color palettes / industry rules
- 57 font pairings
- 99 UX guidelines
- 25 chart types
- 15+ tech stacks
- 18 AI platform targets

즉 이 저장소는 디자인 감각 조언 몇 개가 아니라 **규칙 기반 선택지 데이터베이스**를 내장한 스킬이다.

### 3. 설치 가능한 제품이기도 하다

원본은 단순 markdown bundle이 아니다.

- `skill.json` — 스킬 메타데이터와 설치 엔트리
- `cli/` — `uipro-cli` 배포 경로
- `cli/assets/` — 실제 데이터/템플릿/스크립트 자산
- platform template — 각 AI 도구별 설치 형식

즉 사용자는 README를 읽고 끝나는 게 아니라, 실제로 스킬을 설치해 자신의 AI 환경에 꽂아 쓸 수 있다.

### 4. 최근 변화도 “카탈로그 확장 + 설치 표면 보강” 쪽이다

최근 커밋 흐름은 다음 신호를 준다.

- Three.js stack 추가
- CLI uninstall 메시지/동작 보정
- draft / Google Fonts data를 CLI assets와 동기화
- enhancement issue 묶음 반영

즉 upstream은 문서 소개문을 다듬는 것보다 **스킬 자산 범위와 설치 제품성**을 계속 넓히고 있다.

## 이 가이드에서 먼저 기억해야 할 것

1. UI/UX Pro Max는 스타일 모음집이 아니다.
2. 이 스킬의 중심은 디자인 선택지를 **한 번에 조합하는 reasoning 구조**다.
3. categories 문서는 단순 참고 목록이 아니라 입력 축을 분해해서 보여 주는 학습 표면이다.
4. 원본 저장소는 스킬 메타데이터, CLI, 데이터 자산까지 포함한 제품이다.
5. 따라서 학습 순서도 “취향 고르기”보다 “결정 구조 이해”가 먼저다.
