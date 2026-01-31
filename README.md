# <h1 align="center">🎮 넥슨네트워크 QA 포트폴리오</h1>
<p align="center">
  <b>넥슨네트워크 QA 채용연계형 인턴 지원서</b><br>
  엘소드 레이드 시스템 검증 프로젝트
</p>

<p align="center">
  <img width="300" height="300" alt="캐릭터 일러스트" src="https://github.com/user-attachments/assets/3dcc4e98-b16f-4f4d-87d6-423ac4d7f077" />
</p>

<p align="center">
  <a href="https://careers.nexon.com/recruit/9298">👉 [넥슨네트워크 채용 공고 바로가기]</a>
</p>

---

## 🔍 프로젝트 개요
**"17년 숙련도의 유저 관점을 반영한 결함 탐색"**
* **목적**: 엘소드 주요 레이드 콘텐츠의 기능 정상 작동 여부 검증
* **산출물**: 
  * [테스트 계획서(TP)](./docs/Test_Plan.md)
  * [테스트 케이스(TC)](./docs/Test_Case.xlsx)
  * [결함 보고서(Bug Report)](./docs/Bug_Report.md)

## 테스트 전략
* **리스크 기반 테스트** : 최근 업데이트된 레이드 싱글 모드 콘텐츠및 신규 레이드 진행 시 리스크를 우선순위로 설정
* **회귀 테스트** : 신규 모드 업데이트 시 기존 바니미르, 프뤼나움 레이드 보상 시스템이나 권한 초기화 기능에 영향이 없는지 확인.



## 테스트 범위
| 대상 콘텐츠 | 테스트 유형 | 주요 검증 포인트 |
| :--- | :--- | :--- |
| **바니미르 / 프뤼나움** | 회귀 테스트 | 싱글·일반 모드 보상 지급 및 주간 초기화 로직 |
| **서펜티움 / 둠 아포리아** | 기능 테스트 | 페이즈 전환 트리거 및 주요 패턴 파훼 기믹 |
| **시스템 공통** | UI/UX 테스트 | 레이드 전용 UI 반응성 및 파티 상태 가시성 |


## 테스트 환경
### -하드 웨어-
CPU: Intel(R) Core(TM) i5-10400F
<br>GPU: NVIDIA GeForce RTX 3050
<br>운영체제: Windows 11 Pro (23H2)

### -게임 버전-


