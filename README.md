
<div align="center">

# ✦ 나의 A+ 플래너

### My Personal Study Planner

**시험부터 과제, 연구 일정, 일상까지.**  
나의 하루를 계획하고 성취를 기록하는 개인 맞춤형 학습 플래너

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)

<br>

### 🌐 [플래너 바로가기](https://h2when.github.io/study-planner/)

*GitHub Pages 배포 후 접속 가능합니다.*

</div>

---

## 01. 프로젝트 소개

**나의 A+ 플래너**는 대학 생활에서 발생하는 다양한 학업 일정과 개인 일정을 효율적으로 관리하기 위한 웹 기반 플래너입니다.

시험 준비, 연구 보고서 작성, 과제 제출, 수업 및 개인 약속을 하나의 화면에서 확인하고, 날짜별로 목표와 실제 수행 현황을 관리할 수 있도록 설계했습니다.

단순한 일정 기록을 넘어 **계획 → 실행 → 점검**으로 이어지는 자기주도적 학습 관리를 목표로 합니다.

### 🎯 프로젝트 목표

- 학업 및 개인 일정의 통합 관리
- 날짜별 세부 시간표와 할 일 목록의 유연한 수정
- 학습 목표 설정과 달성 현황 시각화
- 실제 생활 패턴을 반영한 실행 가능한 계획 수립
- 복잡한 설치 없이 브라우저에서 사용 가능한 환경 구현

---

## 02. 주요 기능

| 기능 | 설명 |
|:---|:---|
| 📅 날짜별 일정 관리 | 날짜를 선택하여 하루의 세부 일정 확인 |
| ⏰ 시간표 편집 | 일정의 시간과 내용을 추가·수정·삭제 |
| ✅ To-Do List | 할 일 등록 및 완료 여부 체크 |
| 📊 목표 달성률 | 완료한 항목을 바탕으로 진행 상황 확인 |
| 🌅 생활 루틴 관리 | 기상 및 취침 시간 설정 |
| 📝 일일 메모 | 하루의 목표와 추가 메모 기록 |
| 💾 자동 저장 | 브라우저 로컬 저장소를 활용한 데이터 유지 |
| 📦 백업 및 복원 | JSON 파일을 이용한 일정 데이터 백업·복원 |

---

## 03. Preview

<div align="center">

### 🖥️ Planner Dashboard

*플래너 메인 화면 스크린샷 추가 예정*

<!--
스크린샷 업로드 후 아래 코드의 주석을 해제하세요.

![Planner Preview](./assets/planner-preview.png)
-->

</div>

---

## 04. 사용 기술

| 기술 | 활용 목적 |
|:---|:---|
| HTML5 | 웹페이지 구조 및 콘텐츠 구성 |
| CSS3 | UI 디자인 및 반응형 레이아웃 |
| JavaScript | 일정 편집, 체크리스트, 상태 관리 |
| LocalStorage | 브라우저 기반 데이터 저장 |
| JSON | 사용자 데이터 백업 및 복원 |
| GitHub Pages | 정적 웹사이트 배포 |

별도의 서버나 데이터베이스 없이 동작하는 **정적 웹 애플리케이션(Static Web Application)**으로 구성했습니다.

---

## 05. 프로젝트 구조

```text
study-planner/
│
├── index.html          # 플래너 웹 애플리케이션
└── README.md           # 프로젝트 설명 문서
```

현재는 HTML, CSS, JavaScript를 단일 HTML 파일로 구성하여 실행과 배포를 간소화했습니다.

---

## 06. 사용 방법

### 🌐 웹에서 실행하기

아래 링크로 접속하여 사용할 수 있습니다.

**[나의 A+ 플래너 실행하기](https://h2when.github.io/study-planner/)**

GitHub Pages 배포 완료 후 이용 가능합니다.

### 💻 로컬에서 실행하기

1. 저장소에서 `index.html` 파일 다운로드
2. Safari, Chrome 등 웹 브라우저로 파일 열기
3. 원하는 날짜를 선택하고 일정 및 할 일 수정
4. 필요할 때 JSON 파일로 데이터 백업

> **데이터 저장 안내**
>
> 일정과 체크리스트 데이터는 사용 중인 브라우저의 LocalStorage에 저장됩니다.
>
> 브라우저 또는 기기가 다르면 데이터가 자동 동기화되지 않습니다. 데이터 손실을 방지하기 위해 정기적인 JSON 백업을 권장합니다.

---

## 07. 활용 사례

학기 중 실제 학습 및 연구 일정 관리를 목적으로 구성했습니다.

### 📚 시험 준비

- 과목별 학습 목표 설정
- 개념 학습 및 문제풀이 일정 관리
- 시험 전 복습 계획 수립
- 일별 학습 목표 달성 확인

### 🔬 연구 및 프로젝트

- 캡스톤 연구 일정 관리
- 연구 보고서 작성 및 제출 일정 기록
- 데이터 분석 프로젝트 단계별 목표 설정
- 연구계획서 작성 진행 상황 관리

### 🌷 일상 관리

- 수업 및 외부 일정 정리
- 개인 약속과 학습 시간 조율
- 기상·취침 시간 관리
- 휴식 시간을 포함한 균형 있는 일과 설계

---

## 08. 향후 개발 계획

- [ ] 🍅 포모도로 타이머 추가
- [ ] 📈 과목별 누적 학습 시간 통계
- [ ] 🗓️ 월간 캘린더 뷰 구현
- [ ] 🖱️ 드래그 앤 드롭 기반 일정 변경
- [ ] 🌙 다크 모드 지원
- [ ] 📱 모바일 UI 개선
- [ ] 🔔 시험 및 과제 마감일 알림
- [ ] ☁️ 기기 간 데이터 동기화
- [ ] 🎮 학습 목표 달성에 따른 게이미피케이션

---

## 09. 프로젝트 정보

| 항목 | 내용 |
|:---|:---|
| 프로젝트명 | 나의 A+ 플래너 |
| 유형 | 개인 학습 및 일정 관리 웹앱 |
| 개발 방식 | HTML · CSS · JavaScript |
| 배포 환경 | GitHub Pages |
| 개발 상태 | 초기 버전 / 지속 개선 예정 |

---

<div align="center">

### ✦ Plan your day, achieve your goals.

작은 계획을 실천으로, 실천을 성취로.

<br>

**Made by [h2when](https://github.com/h2when)**  
*Created with the assistance of ChatGPT*

<br>

© 2026 My A+ Planner

</div>
