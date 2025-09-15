# Findex

프로젝트 상세 구현 기능은 <b>노션</b>에서 확인할 수 있습니다.(<b>이미지 클릭</b>)<br>

[![Findex Logo](./Findex-logo.png)](https://example.com)
---
📌 지수 정보 제공 웹사이트<br>
💡 목표: 사용자 친화적인 지수 정보와 자동화 데이터 제공<br>


---

## 🚀 프로젝트 소개
💹 한눈에 보는 금융 지수 데이터!<br>
Findex는 외부 Open API와 연동하여 금융 지수 데이터를 제공하는 <b>대시보드 서비스</b>입니다.<br>
사용자는 직관적인 UI에서 금융 지수의 흐름을 파악하고, 자동 연동 기능을 통해 최신 데이터를 분석할 수 있습니다.<br>
지수별 <b>성과 분석, 이동평균선 계산, 자동 데이터 업데이트 기능</b>을 통해 가볍고 강력한 금융 분석 도구를 경험해 보세요! 📈📊

---
## 🔧 기술 스택

- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40"/> Java
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="40" height="40"/> Spring Boot
- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" /> PostgreSQL
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="40"/> Git hub
- <img src="https://static1.smartbear.co/swagger/media/assets/swagger_fav.png" width="40" height="40"/> Swagger




- ![H2 Database](https://img.shields.io/badge/H2-Database-blue)
  ![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?logoColor=white)
  ![MapStruct](https://img.shields.io/badge/MapStruct-5C4EE5?style=flat&logoColor=white)
  ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
  ![Temurin](https://img.shields.io/badge/Temurin-17-339933?style=flat&logoColor=white)
---
## 구현 기능
### 1) Open API 연동
- 공공데이터포털 등 외부 Open API 연동 준비/구성 (인증키/요청 파라미터/쿼터 관리)
### 2) 지수 정보 관리
- 지수 정보(메타) 조회
- 지수 정보 등록 / 수정 / 삭제
- 지수 정보 목록 조회
### 3) 지수 데이터 관리
- 지수 데이터(시계열) 조회
- 지수 데이터 등록 / 수정 / 삭제
- 지수 데이터 목록 조회
- 지수 데이터 Export (CSV 등)
### 4) 연동 작업 관리
- 연동 작업 정보 조회
- 지수 정보 연동 (메타 싱크)
- 지수 데이터 연동 (시계열 싱크)
- 연동 작업 목록 조회
### 5) 자동 연동 설정 관리
- 자동 연동 정보/상태 조회
- 자동 연동 설정 등록 / 수정 / 목록 조회
- 배치(스케줄러)에 의한 자동 갱신
### 6) 대시보드
- 주요 지수 현황 요약
- 지수 차트 (이동평균선 등 보조지표)
- 지수 성과 분석 랭킹



---
## 📊 Class-diagram

프로젝트의 주요 엔티티 클래스 구조는 다음과 같습니다. 수평적 레이아웃으로 설계되어 있어 클래스 간의 관계를 쉽게 파악할 수 있습니다.

클래스 다이어그램은 `class-diagram.puml` 파일에서 확인할 수 있으며, PlantUML을 사용하여 생성되었습니다.

---
