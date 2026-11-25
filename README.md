# 김세훈 포트폴리오

**보이지 않는 것은 읽어 주고, 보여선 안 되는 것은 가립니다.**

시각장애인의 일상(화장, 장보기, 옷 고르기, 식사, 음료 고르기)을 음성·OCR·비전 AI로 돕는 서비스와, 문서 속 개인정보가 빠짐없이 가려졌는지 검증하는 도구를 만든 AI 개발자 김세훈의 포트폴리오입니다.

### [사이트 열기 → hooni9807.github.io/portfolio](https://hooni9807.github.io/portfolio/)


> 2026-11-18 ~ 2026-11-25 · 커밋 11개 · 1인 개발 (Claude Code와 함께)

---

## 프로젝트 11개

최신순입니다. 이름을 누르면 사이트의 해당 설명으로 바로 이동합니다.

### 읽어 주기: 시각장애인 보조 AI

| 기간 | 프로젝트 | 핵심 기술 | 사이트에서 볼 수 있는 것 |
|---|---|---|---|
| 2026.10&nbsp;~&nbsp;2026.11 | [What Is This?](https://hooni9807.github.io/portfolio/#whatisthis) · 손끝이 가리킨 음료를 읽어 주는 모바일 웹 | MediaPipe, PaddleOCR, DINOv2 | 화면 예시, 직접 써 보기 버튼(비밀번호 필요) |
| 2026.10&nbsp;~&nbsp;2026.11 | [소리한상](https://hooni9807.github.io/portfolio/#sorihansang) · 가리킨 반찬과 옮겨진 반찬을 알려 주는 식사 안내 | Gemma 4, MediaPipe | 43초 시연 영상과 장면 설명 |
| 2026.11&nbsp;~&nbsp;2026.12 | [손끝옷장](https://hooni9807.github.io/portfolio/#closet) · 말과 사진으로 등록하는 음성 옷장 도우미 | Gemma 4, GPT API, 기상청 API | 55초 실행 영상과 장면 설명 |
| 2025.09&nbsp;~&nbsp;2025.12 | [편하CU](https://hooni9807.github.io/portfolio/#pyeonhacu) · 편의점 행사 상품 음성 안내 앱 | OCR, Gemma3, Android | 프로젝트 시트 |
| 2025.03&nbsp;~&nbsp;2025.07 | [뷰티프렌즈](https://hooni9807.github.io/portfolio/#beautyfriends) · 메이크업 도우미 | Gemma3, OpenCV | 프로젝트 시트 |

### 가리기: 문서 비식별 검증 (인턴십 · 지란지교 1연구소 AI연구팀)

| 기간 | 프로젝트 | 핵심 기술 | 사이트에서 볼 수 있는 것 |
|---|---|---|---|
| 2026.10&nbsp;~&nbsp;2026.11 | [Crawling-Document-Data](https://hooni9807.github.io/portfolio/#cdd) · 공공문서 실제 샘플 수집기 | Playwright, pytest | 실제 수집기 화면 |
| 2026.10&nbsp;~&nbsp;2026.11 | [Nearest AutoClick](https://hooni9807.github.io/portfolio/#macro) · KNN으로 화면을 보정하는 클릭 매크로 | k-NN, OpenCV ORB·RANSAC | KNN 보정 흐름도와 측정 결과 |
| 2026.09&nbsp;~&nbsp;2026.12 | [Auto-Test-Program](https://hooni9807.github.io/portfolio/#deid) · 시험 문서 생성과 마스킹 회귀 테스트 | Python, Docker, FastAPI | 마스킹 전후 애니메이션, 웹 콘솔 미리보기 |

### 그 밖의 프로젝트

| 기간 | 프로젝트 | 구분 |
|---|---|---|
| 2026.10&nbsp;~&nbsp;2026.11 | [문장곁](https://hooni9807.github.io/portfolio/#munjang) · 자기소개서 비교·편집과 AI 면접관 피드백 | 개인 |
| 2026.03&nbsp;~&nbsp;2026.06 | [모르는거없쌤](https://hooni9807.github.io/portfolio/#aitutor) · RAG 기반 AI 튜터 | 팀 |
| 2024.09&nbsp;~&nbsp;2025.02 | [레포트메이트](https://hooni9807.github.io/portfolio/#reportmate) · LLM 자료 조사 협업 플랫폼 | 팀 |

---

## 이 페이지를 만든 방식

- **한 파일:** `index.html` 하나와 `assets/`뿐입니다. 빌드 없이 GitHub Pages로 바로 배포됩니다.
- **데이터와 화면 분리:** 프로젝트 내용은 페이지 안의 `projects` 배열에 시간순으로 적고, 화면에는 최신순으로 그립니다.
- **실제 동작을 먼저:** 시연 영상은 실제 녹화에서 필요한 부분만 잘라 2~3MB로 줄였고, 소리 없이 반복 재생하며 지금 장면을 영상 위에 보여 줍니다.
- **직접 그린 예시는 밝힘:** 개인정보·내부 화면을 쓸 수 없는 곳은 가짜 데이터로 다시 그렸고, 캡션에 그렇게 적었습니다. 숫자는 모두 실제 측정값입니다.
- **접근성:** 그림마다 대체 텍스트, 키보드로 여닫는 접이식 항목과 크게 보기 창, 보이는 포커스 표시, "동작 줄이기" 설정이면 자동 재생과 애니메이션을 멈춥니다. 휴대폰 375px에서도 가로로 넘치지 않습니다.

### 디자인 기준

| 문서 | 내용 |
|---|---|
| [PRODUCT.md](PRODUCT.md) | 보는 사람, 목적, 지켜야 할 규칙 (실존 인물·게임 제외, 내부 정보·개인정보 제외, 실제 측정값만) |
| [DESIGN.md](DESIGN.md) | 색, 글꼴, 배치, 부품 기준. 노란 형광펜은 "읽어 주기", 검은 막대는 "가리기"에만 씁니다 |

---

## 파일 구조

```
index.html          페이지 전체 (스타일, 프로젝트 데이터, 동작)
assets/             프로젝트 시트, 시연 영상·포스터, 스크린샷
PRODUCT.md          페이지 목적과 규칙
DESIGN.md           디자인 기준
```

## 내 컴퓨터에서 보기

```bash
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000`을 엽니다.

## 프로젝트 추가하기

1. `index.html`의 `projects` 배열 맨 끝에 같은 모양의 항목을 넣습니다(시간순). 화면에는 자동으로 맨 위에 나옵니다.
2. 그림은 `assets/`에 webp로, 영상은 mp4(가능하면 3MB 이하)로 넣습니다.
3. [DESIGN.md](DESIGN.md)의 배지 색과 세 칸 구조를 따릅니다.
4. 프로필 README([hooni9807/hooni9807](https://github.com/hooni9807/hooni9807))의 프로젝트 표도 함께 고칩니다.
