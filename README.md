## 조진석 포트폴리오

### 프로젝트
#### AI 기반 진로 상담 지원 플랫폼 개발 - 너 내 진로가 되라

[너 내 진로가 되라 (바로가기)](https://github.com/wlstjr1123/JINRO_IS_BACK)

### 개요
* 기존 진로 상담은 학생의 주관적 응답과 상담사의 메모에 크게 의존하기 때문에, 상담 내용을 객관적으로 구조화하고 이후 판단에 활용하기 어렵다는 한계가 있습니다. 이 프로젝트는 학생의 영상 시청 반응, 설문 결과, 상담 대화처럼 서로 다른 형태의 데이터를 AI로 통합 분석해 상담 과정의 보조 도구로 활용하고자 기획 되었습니다.
* AI 모델 자체보다도 AI가 실제 상담 서비스 안에서 어떻게 입력을 받고, 어떤 형태의 결과로 정리되어 의사결정에 도움을 줄 수 있는지를 보여주는 것이 핵심 기획의도입니다.

### 프로젝트 참여도 및 기술 스택
* 기간 : 2026-02-12 ~ 2026-03-25
* 참여도 : 20%
  - 내담자가 영상 분석을 하기전 웹캠을 정면으로 응시하고있는지 판단하기 위해 미디어파이스 페이스매쉬를 활용하여 단순히 화면에 얼굴이 있는지 확인하는것을 넘어 사용자가 정확히 정면을 응시하고있는 계산하는 로직을 구현
  - AffectNet데이터셋을 활용하여 흥미도 모델을 학습
  - AffectNet의 8개의 감정을 흥미있음과 흥미없음 이진분류로 나누어 데이터를 재정의 하여 전이학습 수행
* 개발 언어 및 프레임워크 : Python, JavaScript, FastAPI, React, Vite
* 데이터베이스 : MySQL
* 프론트엔드 및 상태관리 : React Router, Redux Toolkit, Axios
* AI 및 데이터 분석 도구 : OpenCV, MediaPipe, TensorFlow, PyTorch, scikit-learn, Whisper, Ollama, OpenAI API
* 시각화 및 문서화 도구 : Recharts, FullCalendar, html2canvas, jsPDF
* 외부 연독 API 및 서비스 : YouTube IFrame API, OpenAI API
* 협업 및 관리 도구 : GitHub, Google Drive
* 활용 장비 : 웹캠, 마이크, PC/노트북
* 서버 및 실행 환경 : FastAPI 서버, Uvicorn, GitHub 기반 형상관리 환경

<hr/>

#### 공공데이터 및 웹 크롤링 활용하여 병원(의료)정보 데이터 시각화 대시보드 제작 - 케어브릿지

[Carebridge 병원시스템 (바로가기)](https://github.com/wlstjr1123/carebridge)

### 개요
* 기존 서비스들은 응급실 현황이나 감염병 정보처럼 의사결정에 중요한 정보가 없거나 제한적으로 제공되는 한계가 있었습니다. 이러한 한계를 프로젝트 주제로 다룰 가치가 있다고 판단해 본 프로젝트를 선정했습니다.
* 응급실 정보와 병원 예약 기능을 하나의 플랫폼으로 통합해** 사용자가 여러 서비스를 오가지 않도록 했습니다.
* 단순 병상 정보 나열이 아닌, 필터 기능과 종합점수를 활용해 사용자가 자신의 상황에 맞는 응급실을 빠르게 선별할 수 있도록 설계했습니다
* 의료 정보라는 다소 복잡한 데이터를 누구나 빠르고 쉽게 이해할 수 있도록 직관적인 UI/UX로 제공하는 것을 기획의 핵심 목표로 삼았습니다.

### 프로젝트 참여도 및 기술 스택
* 기간 : 2024-11-17 ~ 2025-12-24
* 참여도 : 20%
  - 의사가 한눈에 진료받을 환자의 정보나 7일간 환자 통계 등 볼수있는 의사 대시보드 구현, 의료진이 빠르게 환자의 오더를 처리할수 있도록 실시간 데이터 통신인 웹소켓을 이용한 의료진 대시보드 구현, 의료진이 오더를 처리하기 위한 치료기록 작성 및 검사기록 작성 페이지 구현
* 프론트 : HTML, CSS, JavaScript(AJAX), Jquery, WebSocket
* 벡엔드 : Django, redis
* DB : MySQL, Django ORM
* 서버 : AWS EC2
* API : Kakao Map API, 공공데이터포털 API(XML)
* 형상관리 : GitHub, gitFlow방식 관리
* 개발툴 : VS Code

<hr/>

#### 플러터로 만든 영화정보 앱

[플러터 영화정보 앱 (바로가기)](https://github.com/wlstjr1123/flutter_movie)

### 개요
플러터 bloc, riverpod으로 상태관리를 연습하고 클린 아키택처공데이터 및 웹 크롤링 활용하여 병원(의료)정보 데이터 시각화 대시보드 제작 - 케어브릿지

### 프로젝트 참여도 및 기술 스택
* 참여도 : 개인 프로젝트
* 사용 기술 : flutter, bloc, riverpod, freezed, firebase, Clean Architecture, drift, shared_preferences
* 개발툴 : Android Studio

<hr/>

### 안드로이드 네이티브로 만든 영화정보 앱

[안드로이드 영화정보 앱 (바로가기)](https://github.com/wlstjr1123/MoviePortfolio)

### 개요
안드로이드 코틀린을 연습하고 새로나온 컴포즈와 클린 아키택처 구조를 체험 하기 위해 만든 영화정보 앱

### 프로젝트 참여도 및 기술 스택
* 참여도 : 개인 프로젝트
* 사용 기술 : Kotlin, Room, Compose, Navigation Component, Databinding, hilt, Coroutines, ViewModel, Firebase
* 개발툴 : Android Studio

<hr/>

### 칸반차트로 업무관리하는 하루 프로젝트

[하루 프론트(바로가기)](https://github.com/wlstjr1123/harufront)<br>
[하루 백엔드(바로가기)](https://github.com/wlstjr1123/harubackend)

### 개요
* 칸반차트로 팀을 구성해 업무를 관리하는 웹 시스템

### 프로젝트 참여도 및 기술스택
* 참여도 : 25%
  - 칸반차트 대시보드 DnD시스템 구현
  - 칸반차트 팀 초대 기능 구현
  - 소켓통신으로 실시간 알림 기능 구현
* 프론트 : JavaScript, React, Axios 
* 벡엔드 : JAVA, Spring Boot, Mybatis
* DB : MySql
* 형상관리 : GitHub
* 개발툴 : VS Code, Eclipse

## 코리아IT아카데미 이수 교육 내역

[코리아IT아카데미 (바로가기)](http://gangnam.koreaisacademy.com/)

### 과정명
* K-digital 랭체인을 활용한 AI 영상객체탐지분석 플랫폼 구축과정

### 교육기간
* 2025.08.27 ~ 2025.03.30 (총 1100시간)

### 교육내용 
- **Python 프로그래밍 (104시간)**<br>
 기본자료타입, 입출력, 컬렉션, 함수, 표준라이브러리, 데코레이터, 정규표현식, 클래스, 상속, 오버라이딩, pydantic, typehint, iterable, generator, coroutine, asyncio
- **RDBMS(56시간)**<br>
 DML, DDL, DCL, 단일행/그룹함수, Join, SubQuery, View, 트랜잭션, ER-diagram, 정규화
- **웹 표준  (128시간)** <br>
 HTML 5 / CSS3 / JavaScript / jQuery
 반응형웹 / BootStrap / AJAX. fetch API / JSON / XML /
- **데이터분석, 웹크롤링 (64시간)**<br>
numpy, pandas, matplotlib, seaborn, EDA, Split-Apply-Combine
BeautifulSoup, Selenium,
- **django 웹프레임워크  (64시간)**<br>
MTV, URL conv, template, cookie session, ORM, Model, pagination, file, debug, admin, 인증
- **Git, GitHub (8시간)**<br>
- **머신러닝, 딥러닝**<br>
Scikit-learn, CNN, RNN, TensorFlow/Keras, Pytorch
- **랭체인, RAG, 랭그래프**<br>
