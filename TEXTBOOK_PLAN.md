# Interactive Textbook Expansion Plan

## Overview

기존 2개 시리즈(촉매 10장 + 시뮬레이션 5장)에 교과서 3권을 추가하여
총 5개 시리즈로 확장. 모든 결과물은 MIT License 오픈소스로 GitHub Pages 배포.

## 현재 완성된 시리즈

| # | 시리즈 | 폴더명 | 챕터 수 | Figure 수 |
|---|---|---|---|---|
| 1 | Fundamental Concepts in Heterogeneous Catalysis | `fundamental-concepts-in-heterogeneous-catalysis/` | 10 | 41 |
| 2 | Computational Materials Science Tutorials | `simulation-tutorials/` | 5 | 27 |

## 추가할 교과서 3권

### A. Fundamentals of Engineering Thermodynamics
- **참고 교재**: Moran, Shapiro, Boettner, Bailey — 9th Edition (Wiley, 2018)
- **폴더**: `engineering-thermodynamics/`
- **원본 챕터**: 14장 → 인터랙티브 챕터: 14장

| Ch | 제목 (interactive textbook) | 핵심 인터랙티브 요소 | 원서 대응 |
|---|---|---|---|
| 1 | Getting Started: 열역학의 기초 개념 | 시스템/경계 시각화, 단위 변환기, p-T 스케일 비교 | Ch 1 |
| 2 | Energy & the First Law | W-Q 다이어그램, 팽창일 적분 슬라이더, 에너지 밸런스 | Ch 2 |
| 3 | Evaluating Properties | **p-v-T 3D surface**, 상변화 다이어그램, 증기표 interpolation 도구 | Ch 3 |
| 4 | Control Volume Analysis | 터빈/노즐/열교환기 에너지 밸런스 시뮬레이터 | Ch 4 |
| 5 | The Second Law | **Carnot 사이클 애니메이션**, 효율 한계, Kelvin-Planck/Clausius | Ch 5 |
| 6 | Using Entropy | T-s 다이어그램 인터랙티브, 엔트로피 생성 계산 | Ch 6 |
| 7 | Exergy Analysis | 엑서지 흐름도, dead state 비교, 2nd law efficiency | Ch 7 |
| 8 | Vapor Power Systems | **Rankine 사이클 시뮬레이터** (T-s, h-s), 재열/재생 | Ch 8 |
| 9 | Gas Power Systems | **Otto/Diesel/Brayton 사이클** 비교, 효율 슬라이더 | Ch 9 |
| 10 | Refrigeration & Heat Pumps | 냉동/히트펌프 사이클, **COP 슬라이더** | Ch 10 |
| 11 | Thermodynamic Relations | Maxwell relations 매트릭스, Joule-Thomson 계수 | Ch 11 |
| 12 | Ideal Gas Mixtures & Psychrometrics | **습공기선도** 인터랙티브, 이슬점/습구온도 | Ch 12 |
| 13 | Reacting Mixtures & Combustion | **단열 화염 온도** 계산기, 연소 밸런스 | Ch 13 |
| 14 | Chemical & Phase Equilibrium | **상평형 다이어그램**, van't Hoff, Gibbs phase rule | Ch 14 |

### B. Atkins' Physical Chemistry
- **참고 교재**: Atkins, de Paula, Keeler — 11th Edition (Oxford, 2018)
- **폴더**: `physical-chemistry/`
- **원본 Focus**: 19개 → 인터랙티브 챕터: 19장

| Ch | 제목 (interactive textbook) | 핵심 인터랙티브 요소 | 원서 대응 |
|---|---|---|---|
| 1 | Properties of Gases | **Maxwell-Boltzmann 분포** 슬라이더, van der Waals 등온선 | Focus 1 |
| 2 | The First Law | 열용량, 단열 과정, Joule-Thomson 효과 | Focus 2 |
| 3 | Second & Third Laws | Carnot 사이클, **엔트로피 통계적 해석** (W = microstates) | Focus 3 |
| 4 | Physical Transformations | **상평형 다이어그램** (H2O, CO2), Clausius-Clapeyron | Focus 4 |
| 5 | Simple Mixtures | **2성분 상평형** (T-x, p-x 다이어그램), Raoult/Henry 법칙 | Focus 5 |
| 6 | Chemical Equilibrium | **K vs T** (van't Hoff), 전기화학 전지 전위 | Focus 6 |
| 7 | Quantum Theory | **파동함수 시각화** (particle-in-box, 터널링 확률) | Focus 7 |
| 8 | Atomic Structure & Spectra | **수소 오비탈 시각화** (s,p,d), 에너지 준위도 | Focus 8 |
| 9 | Molecular Structure | **MO 다이어그램 빌더**, 혼성 궤도 | Focus 9 |
| 10 | Molecular Symmetry | 대칭 조작 인터랙티브, 점군 분류 | Focus 10 |
| 11 | Molecular Spectroscopy | **회전/진동 스펙트럼** 시뮬레이터, selection rules | Focus 11 |
| 12 | Magnetic Resonance | NMR chemical shift 예측, coupling pattern | Focus 12 |
| 13 | Statistical Thermodynamics | **분배함수** vs T, 에너지 분포, 열용량 유도 | Focus 13 |
| 14 | Molecular Interactions | **Lennard-Jones 포텐셜** 슬라이더 (ε, σ) | Focus 14 |
| 15 | Solids | **결정 구조** (FCC/BCC/HCP), band theory, 밀러 지수 | Focus 15 |
| 16 | Molecules in Motion | 확산 방정식, 이온 전도도, 점성 | Focus 16 |
| 17 | Chemical Kinetics | **반응 차수** 피팅 도구, Arrhenius plot | Focus 17 |
| 18 | Reaction Dynamics | **포텐셜 에너지 표면**, 충돌 이론, TST | Focus 18 |
| 19 | Processes at Solid Surfaces | **흡착 등온선** (Langmuir, BET, Freundlich) | Focus 19 |

### C. Elements of Chemical Reaction Engineering
- **참고 교재**: H. Scott Fogler — 5th Edition (Pearson, 2016)
- **폴더**: `chemical-reaction-engineering/`
- **원본 챕터**: 18장 → 인터랙티브 챕터: 18장

| Ch | 제목 (interactive textbook) | 핵심 인터랙티브 요소 | 원서 대응 |
|---|---|---|---|
| 1 | Mole Balances | 반응기 타입 비교 (BR, CSTR, PFR, PBR) 시각화 | Ch 1 |
| 2 | Conversion & Reactor Sizing | **Levenspiel 플롯** 인터랙티브, 반응기 직렬 조합 | Ch 2 |
| 3 | Rate Laws | **Arrhenius plot** 슬라이더, 반응 차수 결정 | Ch 3 |
| 4 | Stoichiometry | 농도 vs 전환율 그래프 (기상/액상), 화학양론표 빌더 | Ch 4 |
| 5 | Isothermal Reactor Design: Conversion | **CSTR/PFR 부피 비교** 시뮬레이터, 압력강하 | Ch 5 |
| 6 | Isothermal Design: Molar Flow Rates | 멤브레인 반응기, semibatch 시뮬레이션 | Ch 6 |
| 7 | Collection & Analysis of Rate Data | 미분법/적분법 **데이터 피팅** 인터랙티브 | Ch 7 |
| 8 | Multiple Reactions | **선택도 vs 조건** (T, C) 맵, 직렬/병렬 반응 비교 | Ch 8 |
| 9 | Reaction Mechanisms & Bioreactions | **Michaelis-Menten** 인터랙티브, Lineweaver-Burk | Ch 9 |
| 10 | Catalysis & Catalytic Reactors | 흡착 등온선, **rate-limiting step** 시각화 | Ch 10 |
| 11 | Nonisothermal: Adiabatic PFR | **단열 반응기** T-X 다이어그램, 평형 전환율 | Ch 11 |
| 12 | Nonisothermal: Heat Exchange | **Multiple steady states** (ignition-extinction), 안정성 분석 | Ch 12 |
| 13 | Unsteady Nonisothermal | **Runaway reaction** 시뮬레이션, 배치 반응기 열폭주 | Ch 13 |
| 14 | Mass Transfer Limitations | Fick's law, **경계층 농도 프로파일**, Mears/Weisz-Prater | Ch 14 |
| 15 | Diffusion & Reaction | **Thiele modulus vs effectiveness factor**, pellet 농도 분포 | Ch 15 |
| 16 | Residence Time Distributions | **E(t), F(t) 곡선** 인터랙티브, pulse/step tracer | Ch 16 |
| 17 | Conversion from RTD | Segregation vs maximum mixedness 비교 | Ch 17 |
| 18 | Models for Nonideal Reactors | **Tanks-in-series** (N 슬라이더), dispersion model | Ch 18 |

## 구현 사양

### 기술 스택
- Single-file HTML (standalone, 서버 불필요)
- Inter font (Google Fonts CDN)
- KaTeX (수식 렌더링)
- Plotly.js (인터랙티브 차트)
- CSS custom properties 기반 통일 디자인 시스템

### 디자인 시스템
- 현재: OpenAI-inspired 스타일 (white canvas, Inter, minimal borders)
- 새 챕터 제작 시 `/design2html` 스킬의 디자인 토큰/규칙을 따를 것
- CSS variables (기존): `--color-void`, `--color-fog-border`, `--color-chalk`, 
  `--color-graphite`, `--color-ash`, `--color-canvas`
- 반응형: max-width 1200px, mobile-friendly

### 이중 언어 (KO/EN)
- **모든 텍스트**에 `<span class="lang-ko">` / `<span class="lang-en">` 적용
- 기본 표시: 한국어 (`lang-en`은 `display:none`)
- 우상단 KO/EN 토글 버튼 (기존 index.html 패턴 재사용)
- 수식: 언어 무관 (KaTeX 그대로)
- 인터랙티브 요소: 레이블/readout/설명만 이중 언어, 차트 자체는 영어 유지
- 구현 참고: `index.html:64-77` (CSS), `index.html:378-382` (JS setLang 함수)
```html
<!-- 토글 버튼 -->
<div class="lang-toggle">
  <button class="lang-btn active" id="btnKO" onclick="setLang('ko')">KO</button>
  <button class="lang-btn" id="btnEN" onclick="setLang('en')">EN</button>
</div>
<!-- 텍스트 패턴 -->
<p>
  <span class="lang-ko">촉매는 활성화 에너지를 낮춥니다.</span>
  <span class="lang-en" style="display:none;">A catalyst lowers the activation energy.</span>
</p>
```

### 챕터 공통 구성요소
1. **KO/EN 토글**: 우상단 고정 (nav 안 또는 position:fixed)
2. **Syllabus 헤더**: 참고 교재명, 대응 원서 챕터, 학습 목표 (이중 언어)
3. **Sections**: 개념 설명 (이중 언어) + 핵심 수식 (KaTeX, 언어 무관)
4. **Interactive Figures**: Plotly 차트 + 슬라이더 컨트롤 + readout 패널
5. **What-if Cards**: 클릭 시 확장되는 사고 실험 (이중 언어)
6. **Quizzes**: 객관식 + 설명 팝업 (이중 언어)
7. **Step-by-step 탐색**: 접기/펼치기 가이드 (이중 언어)
8. **Navigation**: 이전/다음 챕터 링크, index로 돌아가기

### 각 교과서 index.html 구조
- 교과서 제목/저자 정보 (참고 교재 명시, 이중 언어)
- Syllabus: 주차별 커리큘럼 제안 (이중 언어)
- 챕터 카드 그리드 (제목 + 핵심 figure 수)

## 저작권 & 라이선스

### 원칙
- **과학적 사실, 수식, 개념**: 저작권 대상 아님 (public domain)
- **원서 텍스트/그림**: 직접 복사 절대 금지
- **인터랙티브 교과서**: 100% 독자적 창작물 (설명, 시각화, 퀴즈 모두 새로 작성)
- **접근 방식**: 원서를 syllabus/참고문헌으로만 인용

### 라이선스
- 코드 (HTML/CSS/JS): MIT License
- 콘텐츠 (설명 텍스트, 퀴즈): CC BY-SA 4.0
- 각 교과서 index.html에 "Based on topics covered in [교재명]. 
  All explanations, visualizations, and exercises are original works." 명시

## 작업 순서

### Phase 0: 인프라 ✅
- [x] Google Drive 중복 파일 정리 (archive) — 16개 HTML → ~/.archive/2026-05-13/
- [x] git repo에 3개 폴더 생성
- [x] 메인 index.html에 3권 추가 (3열 그리드, KO/EN 이중언어)
- [x] 각 교과서 index.html (syllabus + 챕터 목록) 생성
- [x] 기존 2개 시리즈 index.html에 KO/EN 토글 소급 적용

### Phase 1: Engineering Thermodynamics (Moran)
- 14 chapters, 한 세션에 2~3 챕터씩
- 우선순위: Ch1→2→3→5→6→8→9→4→7→10→11→12→13→14

### Phase 2: Chemical Reaction Engineering (Fogler)
- 18 chapters
- 우선순위: Ch1→2→3→5→8→9→10→4→6→7→11→12→13→14→15→16→17→18
- 기존 촉매 시리즈와 연계 (Ch10 Catalysis ↔ 촉매 교과서 전체)

### Phase 3: Physical Chemistry (Atkins)
- 19 chapters (최대 분량)
- 우선순위: Focus 1→2→3→4→5→6→17→7→8→13→9→14→15→19→10→11→12→16→18
- 기존 시리즈와 중복 주제 있음 (Focus 19 Surfaces ↔ 촉매, Focus 13 StatThermo ↔ 시뮬레이션)

### Phase 4: 통합 & 배포
- [ ] 메인 index.html hero 섹션 업데이트
- [ ] 교차 참조 링크 (관련 챕터 간)
- [ ] README.md 업데이트
- [ ] 최종 push to GitHub Pages

## 작업 방식

### 세션당 작업 흐름
1. 이 TEXTBOOK_PLAN.md + HANDOVER.md 읽기
2. PDF에서 해당 챕터 핵심 내용 읽기 (개념 + 수식 + 예제)
3. 인터랙티브 요소 설계 (어떤 슬라이더, 어떤 플롯)
4. `/design2html` 스킬로 디자인 규칙 로드
5. subagent 2~3개 parallel로 챕터 HTML 생성
6. 브라우저 검증
7. git commit & push
8. 이 문서의 진행 상황 체크박스 업데이트

### Subagent briefing 템플릿
각 subagent에 전달할 것:
- 기존 챕터 HTML 1개 (템플릿 겸 디자인 참고, e.g. ch1.html 앞 200줄)
- 챕터별 내용 요약 (PDF에서 추출한 개념 + 수식 + 예제)
- 인터랙티브 요소 명세 (어떤 Plotly 차트, 어떤 슬라이더, 범위)
- KO/EN 이중 언어 필수 (lang-ko/lang-en 패턴)
- 네이밍: `{textbook-prefix}-ch{N}.html`

### 파일 네이밍 컨벤션
- `engineering-thermodynamics/thermo-ch1.html`
- `physical-chemistry/pchem-ch1.html`
- `chemical-reaction-engineering/cre-ch1.html`
- 각 폴더에 `index.html` (syllabus + 챕터 목록)
