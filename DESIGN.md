---
name: 김세훈 포트폴리오
description: ATP 인수인계서의 다크 화면 위에서, 형광펜으로 읽어 주고 밝은 테이프로 가리는 한 페이지 포트폴리오
colors:
  paper: "#111418"
  card: "#181C21"
  panel: "#1F242B"
  ink: "#E6E8EB"
  muted: "#9AA4AE"
  indigo: "#7FB0FF"
  brand2: "#1C2A3D"
  accent: "#FF8A50"
  marker: "#FFD84A"
  on-marker: "#111418"
  line: "#2B3138"
  pass: "#5FD38A"
  pass-bg: "#163A24"
  warn: "#FFC65C"
  warn-bg: "#3A2E12"
  fail: "#FF7B72"
  fail-bg: "#3D1A1A"
  terminal: "#0D1117"
typography:
  display:
    fontFamily: "Pretendard Variable, Pretendard, Apple SD Gothic Neo, Malgun Gothic, sans-serif"
    fontSize: "clamp(1.7rem, 5.4vw, 4.5rem)"
    fontWeight: 800
    lineHeight: 1.5
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "clamp(1.5rem, 2.6vw, 2rem)"
    fontWeight: 800
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "clamp(1.35rem, 2.4vw, 1.85rem)"
    fontWeight: 800
    lineHeight: 1.35
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.75
  lead:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.75
  body-small:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.65
  caption:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.55
  mock-text:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Pretendard Variable, Pretendard, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
    lineHeight: 1.7
  code:
    fontFamily: "ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "0.6875rem"
rounded:
  bar: "2px"
  tag: "3px"
  panel: "4px"
  card: "6px"
  pill: "999px"
  mock-button: "8px"
  mock-screen: "10px"
  mock-shape: "14px"
  mock-device: "22px"
spacing:
  gutter: "1.5rem"
  container: "72rem"
  project-gap: "3rem"
components:
  badge-team:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "0.1rem 0.6rem"
  badge-solo:
    backgroundColor: "{colors.marker}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "0.1rem 0.6rem"
  badge-intern:
    backgroundColor: "{colors.indigo}"
    textColor: "{colors.card}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "0.1rem 0.6rem"
  card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "1.1rem"
  chip:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.1rem 0.65rem"
  button-try:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.card}"
    padding: "0.6rem 1rem"
  button-try-hover:
    backgroundColor: "{colors.indigo}"
  segmented-on:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
---

# Design System: 김세훈 포트폴리오

## Overview

**Creative North Star: 형광펜과 마스킹 테이프.**
첫 화면 문장 "보이지 않는 것은 읽어 주고, 보여선 안 되는 것은 가립니다."가 시스템 전체를 정한다. 노란 형광펜(marker)은 **읽어 주기**, 검은 테이프(ink)는 **가리기**를 뜻한다. 두 색은 장식이 아니라 의미를 가진 도구로만 쓴다. 나머지는 차분한 회청색 종이 위에 흰 카드를 놓은 문서처럼 조용하게 둔다.

포트폴리오는 작품이 주인공이다. 화면 장식보다 실제 시연 영상, 실제 화면, 실제 측정값이 먼저 보이게 한다. 기준이 되는 페이지 목적과 규칙은 `PRODUCT.md`에 있다.

## Colors

- **paper `#EEF0F6`**: 페이지 바탕. 차가운 회청색 종이.
- **card `#FFFFFF`**: 표, 예시 화면, 스크린샷 테두리 안쪽.
- **ink `#14162B`**: 본문 글자, 굵은 구분선, 가리기 막대, 팀 프로젝트 배지, 주요 버튼.
- **muted `#565B78`**: 보조 글자(캡션, 표 머리, 기관 이름). paper 위 대비 4.5:1 이상.
- **indigo `#3A32C8`**: 유일한 강조색. 별칭, 목록 점, 인턴십 배지, 포커스 테두리, 진행 막대, 링크 hover.
- **marker `#FFD84A`**: 형광펜. 히어로 첫 줄, 표의 프로젝트 이름 밑줄, 개인 프로젝트 배지, 텍스트 선택색. 넓은 면적에 칠하지 않는다.
- **line `#C9CDDC`**: 1px 구분선과 카드 테두리.
- 보조 면: table-head `#E3E6F0`, panel `#F3F4F8`(로그·흐름도 칸), indigo-tint `#ECEBFA`(AI 피드백 칸).
- 경고: alert `#B4352B` 글자, alert-tint `#F8E4E1` 배경. FAIL, 노출, 지운 글자에만 쓴다.
- 기기 틀 `#1B2440`: 휴대폰 영상·예시 화면의 테두리.
- `mock-*` 색: 직접 그린 What Is This 화면은 실제 앱의 녹색 계열(`mock-wit-*`)과 캔·손가락 색을 따로 쓴다. 예시 화면 안에서만 쓰고 페이지 다른 곳에는 쓰지 않는다.

## Typography

- 글꼴은 **Pretendard Variable** 하나(jsDelivr). 한글은 `word-break: keep-all`로 단어 단위 줄바꿈, 너무 긴 묶음은 `overflow-wrap: anywhere`로 넘치지 않게 한다.
- 크기 단계: display(히어로) → headline(섹션 제목) → title(프로젝트 제목) → lead 1.125rem(히어로 소개) → body 1rem/1.75 → body-small 0.9375rem(스킬 파일 카드) → caption 0.875rem(표 보조 글, 기관) → label 0.8125rem → mock-text 0.75rem(직접 그린 예시 안). 제목은 모두 800 굵기, 글자 간격은 -0.01~-0.02em.
- 날짜와 기간은 `font-variant-numeric: tabular-nums`로 자릿수를 맞춘다.
- 고정폭 글꼴은 코드, 명령, 로그, 파일 이름에만 쓴다.
- 본문 한 줄 길이는 40rem 이하.

## Layout

- 가운데 정렬 컨테이너 72rem, 좌우 여백 1.5rem.
- 순서: 상단 이름·메뉴 → 히어로 → 활동 이력 표 → 프로젝트 → 기술 → 바닥글.
- 프로젝트 한 개: `11rem | 본문 | 17rem` 세 칸. 왼쪽은 기간·구분·기관, 가운데는 글, 오른쪽은 그림. 가로로 긴 영상이 있는 프로젝트만 화면이 72rem 이상일 때 오른쪽 칸을 24rem으로 넓힌다.
- 60rem 이하: 그림이 글 아래로 내려간다(최대 22rem). 44rem 이하: 날짜 칸도 위로 올라가고, 활동 이력 표는 카드형 목록이 된다.
- 프로젝트 사이는 위아래 3rem과 2px ink 선으로 나눈다. 최신 작업이 위에 온다.

## Elevation & Depth

평면 시스템이다. 그림자를 쓰지 않고, 깊이는 paper → card의 밝기 차이와 1px line 테두리로만 만든다. 한 요소에 테두리와 그림자를 함께 쓰지 않는다.

## Shapes

- 직접 그린 예시 안: 버튼 8px, 화면 10px, 점선 도형 14px, 휴대폰 틀 22px.
- 2px: 진행·결과 막대. 3px: 배지, 태그. 4px: 패널 안 칸. 6px: 카드, 스크린샷, 버튼. 999px: 기술 칩과 전후 비교 토글처럼 작은 조작 요소만.
- 휴대폰 예시는 실제 기기처럼 큰 둥근 모서리와 두꺼운 device-frame 테두리를 쓴다.

## Components

- **주제 표시:** 프로젝트 왼쪽 칸과 프로젝트 바로가기에서 읽어 주기는 형광펜 밑칠(`t-read`), 가리기는 검은 테이프(`t-hide`).
- **프로젝트 바로가기:** 프로젝트 목록 위 흰 카드. 읽어 주기 / 가리기 / 그 밖의 작업 세 줄로 묶고 이름에 형광펜 밑줄.

- **구분 배지:** 팀 = ink, 개인 = marker, 인턴십 = indigo. 이 세 가지 외에 늘리지 않는다.
- **활동 이력 표:** 프로젝트 이름(별칭)을 형광펜 밑줄 링크로 크게, 긴 제목은 아래에 muted로. 링크를 누르면 해당 프로젝트로 이동한다.
- **접이식 상세(`details.more`):** 위쪽 1px 선, indigo 꺾쇠가 회전하고 오른쪽에 "펼치기/접기". 설계 결정, 트러블슈팅, 검증처럼 긴 내용은 여기에 넣는다.
- **오른쪽 그림:** 시트·스크린샷은 누르면 크게 보기 창(`dialog`)으로 열린다. 영상은 소리 없이 자동 반복하고 위에 indigo 글씨로 지금 장면을 보여 준다. 직접 그린 예시(`.mock`)는 흰 카드에 6px 모서리.
- **직접 써 보기 버튼:** ink 바탕, hover 시 indigo. 아래에 작은 안내 문구(비밀번호 필요 여부 등).
- **기술 칩:** 흰 바탕 pill, 1px line 테두리.
- **마스킹 전후 예시:** 검은 막대가 왼쪽에서 오른쪽으로 하나씩 덮는 애니메이션. 이 페이지의 대표 움직임이다.

## Do's and Don'ts

- **Do** marker는 "읽어 주기", ink 막대는 "가리기"에만 쓴다.
- **Do** 새 프로젝트도 같은 세 칸 구조와 같은 배지 색을 쓴다.
- **Do** 직접 그린 예시와 덧붙인 그림은 캡션에 그렇다고 적는다.
- **Do** 움직임은 `prefers-reduced-motion`에서 멈추거나 마지막 상태로 보여 준다.
- **Don't** 카드에 3px 이상 왼쪽 색 띠를 두지 않는다. 테두리 1px이나 옅은 배경을 쓴다.
- **Don't** 그림자, 그라데이션 글자, 유리 효과를 넣지 않는다.
- **Don't** 제목 위에 작은 머리말(eyebrow)을 달지 않는다. 영상 위 장면 설명은 영상과 함께 바뀌는 캡션이라 예외다.
- **Don't** 클래스 이름을 다른 요소와 겹치게 짓지 않는다(`.say`, `.now`는 히어로·영상 캡션이 이미 쓴다).
- **Don't** indigo 외의 강조색을 새로 들이지 않는다.
