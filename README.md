# UI/UX Pro Max 스킬 학습 가이드

UI/UX Pro Max는 단순히 “예쁜 화면을 만들어 달라”고 말하는 프롬프트 모음이 아니다. 이 스킬의 핵심은 **디자인 시스템 추천 엔진**에 가깝다.

원본 저장소 기준으로 이 스킬은 다음 범위를 다룬다.

- **67개 UI 스타일**
- **161개 산업별 컬러 팔레트**
- **57개 폰트 조합**
- **99개 UX 가이드라인**
- **25개 차트 유형**
- **15개 이상 기술 스택**
- **18개 AI 플랫폼 설치 대상**
- 현재 스킬 버전 기준: **`2.5.0`**

즉 이 가이드는 “디자인 초보가 AI에게 물어보는 법”만 설명하는 문서가 아니라, **이 스킬이 어떤 데이터와 추론 규칙을 가지고 어떤 종류의 결과물을 만들어내는지**를 학습용으로 다시 정리한 frontdoor다.

---

## 이 스킬을 한 문장으로 말하면

**제품 유형·스타일·컬러·타이포그래피·컴포넌트·UX 규칙을 함께 검색하고 조합해서, AI가 더 일관된 UI/UX 결정을 내리도록 돕는 디자인 인텔리전스 레이어**다.

원본 README의 v2.0 중심 메시지도 여기에 맞닿아 있다.

- 사용자 요청을 받고
- 여러 도메인에서 후보를 탐색한 뒤
- reasoning rule과 우선순위로 조합하고
- 패턴 + 스타일 + 컬러 + 타이포그래피 + 체크리스트 형태로 결과를 정리한다

핵심은 “예쁜 스타일 하나 추천”이 아니라 **일관된 설계 결정 묶음**을 만들어 주는 데 있다.

---

## 왜 이 가이드를 다시 봐야 하나

### 1. 기존 frontdoor가 너무 입문형이었다

기존 README는 친절했지만, 초점이 주로 아래에 있었다.

- 디자인 경험이 적은 사람도 쉽게 쓸 수 있다
- 어떤 순서로 스타일/색상/컴포넌트를 볼지 안내한다
- AI에게 어떻게 요청할지 예시를 보여 준다

이 자체는 나쁘지 않다. 하지만 이러면 원본의 핵심 강점인 아래 요소가 흐려진다.

- **reasoning engine**
- **industry-specific rule set**
- **platform-aware install surface**
- **CLI 기반 배포 경로**
- **design system generation**

### 2. 원본은 이미 “디자인 카탈로그”를 넘어서 있다

최근 upstream을 기준으로 보면 이 스킬은 단순 참고 자료집이 아니다.

- `skill.json`은 스킬 메타데이터와 18개 플랫폼 설치 표면을 정의한다.
- `cli/`는 `uipro-cli`를 통해 설치·초기화 경로를 제공한다.
- CLI asset/data는 스타일, 색상, 타이포그래피, UX 규칙, 검색/추론 스크립트를 함께 묶는다.
- 최근 커밋은 Three.js stack, CLI asset sync, install/uninstall 안정화 같은 **운영 확장**을 다룬다.

즉 이 저장소는 “문서형 스타일 가이드”보다 **배포 가능한 디자인 지식 시스템**에 더 가깝다.

### 3. 학습 순서도 다시 잡을 필요가 있다

이 스킬을 잘 쓰려면 처음부터 색상표와 폰트표를 외우기보다 먼저 이해해야 한다.

1. 이 스킬이 어떤 입력을 받아 어떤 구조의 결정을 내리는지
2. 어떤 축이 있는지 — 스타일 / 팔레트 / 타이포 / 컴포넌트 / UX / 스택
3. 어떤 산출물이 나오는지 — 랜딩 페이지, 대시보드, 앱 UI, 디자인 시스템 초안
4. 어떤 상황에서 검토용으로 쓰고, 어떤 상황에서 바로 구현 프롬프트로 연결할지

---

## 현재 기준선

- upstream skill version: `2.5.0`
- 최근 upstream 변화 신호:
  - Three.js stack 통합
  - CLI uninstall/reporting 보정
  - CLI 자산 동기화
  - enhancement issue 반영
- 저장소 한줄 요약:
  - **다중 플랫폼 AI 어시스턴트를 위한 디자인 인텔리전스 스킬 + 설치 CLI + 데이터 자산 묶음**

---

## 이 저장소를 읽을 때 먼저 볼 것

### 핵심 파일

- `README.md` — 원본의 현재 제품 메시지
- `skill.json` — 스킬 메타데이터, 설치 표면, 플랫폼 범위
- `cli/package.json` — CLI 배포 버전과 진입점
- `cli/assets/` — 실제 데이터/템플릿/스크립트 자산
- `preview/` / `screenshots/` — 시각적 결과 힌트

### 핵심 해석 포인트

- **스타일 추천**만 하는 스킬이 아니다
- **산업별 규칙 + 디자인 시스템 조합**이 핵심이다
- **설치 가능한 스킬 제품**이라는 점을 함께 봐야 한다

---

## 추천 읽기 순서

1. `sections/01-overview.md` — 이 스킬이 실제로 어떤 시스템인지
2. `01-learning-paths.md` — 어떤 순서로 이해하고 써야 하는지
3. `categories/overview.md` — 업스트림 구조와 최근 변동 요약
4. `categories/ui-styles.md` — 스타일 축
5. `categories/colors-fonts.md` — 팔레트 / 타이포 축
6. `categories/components.md` — UI 조립 축
7. `categories/products-landing.md` — 완성 화면/패턴 축
8. `categories/ux-guidelines.md` — 품질 검수 축
9. `02-glossary.md` — 용어 정리

---

## 누가 이 가이드를 읽어야 하나

### 1. AI로 디자인 결정을 구조화하고 싶은 개발자

이 경우 핵심은 “예쁜 화면을 뽑는 법”보다:

- 어떤 제품군 규칙을 먼저 잡아야 하는지
- 어떤 스타일과 팔레트를 같이 묶어야 하는지
- 출력 결과를 어떻게 구현용 프롬프트로 연결할지

를 배우는 것이다.

### 2. 디자인 초안을 빠르게 만드는 PM / 메이커

이 경우 이 스킬은 무드보드 생성기가 아니라,
**제품 유형에 맞는 설계 결정을 빠르게 압축하는 시스템**으로 보는 편이 맞다.

### 3. 스킬/CLI 제품 관점으로 원본 저장소를 읽고 싶은 사람

이 경우 `skill.json`, `uipro-cli`, platform template, asset sync 구조까지 함께 봐야 한다.

---

## 흔한 오해

### 오해 1 — 그냥 스타일 모음집이다

아니다. 스타일만 있는 게 아니라 산업 규칙, 컬러, 타이포, UX, 차트, 스택까지 이어진다.

### 오해 2 — 디자이너가 아닌 사람에게 프롬프트 몇 개 주는 입문서다

그것도 가능하지만, 원본의 진짜 힘은 **reasoning-based design system generation**에 있다.

### 오해 3 — 결과는 전부 감각적인 취향 문제다

아니다. 이 스킬은 제품 유형, 안티패턴, 접근성, 체크리스트까지 함께 다뤄서 설계 결정을 구조화한다.

---

## 다음 문서

- 이 스킬의 구조적 역할부터 보려면 `sections/01-overview.md`
- 실제 사용 흐름을 잡으려면 `01-learning-paths.md`
- 세부 카테고리 축을 빠르게 훑으려면 `categories/` 문서들

<!-- GUIDE_SYNC:START -->
## 자동 동기화 상태

- origin repo: `ui-ux-pro-max-skill`
- latest source commit: `b7e3af80f6e3`
- sync mode: `update`
- 영향 분류: 소스코드, 테스트/검증

### 이번 반영 포인트

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 소스코드, 테스트/검증.

### 최근 upstream 커밋

- `b7e3af8 Merge pull request #184 from Jenser77/feat/design-system-visual-improvements`
- `7faef3e Merge pull request #191 from amyragan3297/amyragan3297-patch-1`
- `83692f7 Create python-package-conda.yml`
- `e3102cb Improve design system output with Unicode borders, ANSI color swatches, extended palette, and dark/light mode`

### 변경 파일 샘플

- `.github/workflows/python-package-conda.yml`
- `cli/assets/scripts/core.py`
- `cli/assets/scripts/design_system.py`
- `src/ui-ux-pro-max/scripts/core.py`
- `src/ui-ux-pro-max/scripts/design_system.py`

> 이 블록은 guide sync가 자동 갱신합니다.
<!-- GUIDE_SYNC:END -->
