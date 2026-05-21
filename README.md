# Coding Now — 배포 저장소

[coding-now.com](https://coding-now.com) 에서 제작한 프로그램들의 **배포용 저장소**입니다.
실행 파일(Portable zip)·스크린샷·릴리스 노트가 이곳에 올라옵니다.

> 제작자: **Joseph.han** · 블로그: [coding-now.com](https://coding-now.com)

---

## 📦 배포 프로그램

### 1. GUI Apps Controller

트레이에 상주하면서 등록한 프로그램을 **지정한 시간에 자동 실행**해 주는 작은 도구.
Windows 작업 스케줄러보다 훨씬 단순하게, **한 화면에서 표로 모든 일정을 관리**합니다.
자동매매 HTS 기동, 매일 백업 스크립트, PC 자동 잠금 등 일상 자동화에 최적.

![GUI Apps Controller 메인 창](GuiAppsController/app_control.png)

- **버전**: 1.5.1
- **OS**: Windows 10/11 (x64)
- **다운로드**: [GuiAppsController-Setup-1.5.1.exe](GuiAppsController/GuiAppsController-Setup-1.5.1.exe)
- **소스 코드**: [github.com/cflab2017/GUI_Apps_Controler](https://github.com/cflab2017/GUI_Apps_Controler)
- **사용법**: [상세 가이드 보기](GuiAppsController/blog.md)
- **인터랙티브 데모**: [브라우저에서 미리보기](https://htmlpreview.github.io/?https://github.com/cflab2017/codingnow_release/blob/main/GuiAppsController/demo.html) · [HTML 소스](GuiAppsController/demo.html)

**주요 기능**
- 매일 / 매주(요일 선택) / 1회 일정 — 클릭 두 번이면 등록·편집·삭제
- "다음 실행" 시각 자동 계산 표시 — 일정이 의도대로 잡혔는지 한눈에 확인
- **[지금 실행]** 버튼으로 일정과 무관하게 즉시 실행 (등록 직후 검증용)
- 실행 히스토리 영구 저장 (최근 500개, 성공/실패 컬러 강조)
- JSON 가져오기 / 내보내기 — PC 간 일정 동기화
- **Telegram 봇** — 외부에서 `/list`·`/run`·`/screenshot`·`/lock`·`/shutdown` 등 원격 제어
- Windows 절전/재개 이벤트 감지 — 노트북을 닫았다 열어도 일정 정상 동작
- 다크 모드 자동 전환, 다중 선택 일괄 작업, 검색 필터

---

### 2. StarCraft Minimap Radar

SC:R 미니맵을 픽셀로 감시해 **적의 이동·본진 침입을 실시간으로 알려주는** 무료 오버레이.
게임 메모리·D3D에 일절 손대지 않고 화면 픽셀만 분석하므로 EULA 위반 위험 없음.

![StarCraft Minimap Radar](StarCraftMinimapRadar/StarCraftMinimapRadar_03.png)

- **버전**: 0.5.1
- **OS**: Windows 10/11 (x64)
- **다운로드**: [StarCraftMinimapRadar-0.5.1-portable-x64.zip](StarCraftMinimapRadar/StarCraftMinimapRadar-0.5.1-portable-x64.zip)
- **소스 코드**: [github.com/cflab2017/StarCraftMinimapRadar](https://github.com/cflab2017/StarCraftMinimapRadar)
- **사용법**: [상세 가이드 보기](StarCraftMinimapRadar/blog-promo.md)

**주요 기능**
- 미니맵의 빨강 픽셀(=적) 변화를 감지해 상태창에 즉시 표시
- 본진 영역에 적이 진입한 순간 시스템 사운드 + 빨간 펄스로 경고
- 클릭 통과(click-through) 오버레이 — 게임 조작에 영향 없음
- 단축키로 미니맵/본진 영역 지정, 알람 토글
- 한국어 / English 지원
- Portable — 설치 불필요, .NET 런타임 내장

---

## 🚀 사용 방법

각 프로그램의 **다운로드** 링크에서 파일 받기:
- **GUI Apps Controller**: `.exe` 설치 파일 실행 → 트레이 아이콘 확인
- **StarCraft Minimap Radar**: zip 압축 풀고 `.exe` 실행 (설치 불필요)

> Windows SmartScreen 경고가 뜨면 **추가 정보 → 실행**으로 진행하세요. (자체 서명 도구)

---

## 📜 라이선스

각 프로그램의 라이선스는 해당 소스 코드 저장소를 참고해주세요.

---

## 💬 문의 / 제보

- 블로그: [coding-now.com](https://coding-now.com)
- 버그 / 제안: 각 프로그램의 소스 저장소 Issues 페이지
