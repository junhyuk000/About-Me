## 👋 About Me

사용자와 사회에 도움이 되는 기술을 만드는 것이 제가 개발을 시작한 이유입니다.  
IoT, AI, 웹을 아우르는 다양한 프로젝트를 통해 **문제를 스스로 정의하고, 설계하고, 구현**하는 경험을 쌓아왔습니다.

하드웨어 제어부터 AI 모델 학습, 웹 서비스 구축, 인프라 배포까지 전 과정을 직접 수행하며  
실제 환경에서도 동작 가능한 서비스를 만드는 데 집중하고 있습니다.

"기술은 실생활과 연결될 때 가장 큰 힘을 발휘한다"는 생각으로,  
**작지만 실질적인 변화를 만드는 개발자**가 되고 싶습니다.

---

## 💼 Experience & Education

- 📚 삼성아카데미 – [인공지능]AIOT를 이용한 빅데이터 분석 산업솔루션 개발  
  *2024.10.04 ~ 2025.04.29*

- 💻 스마트시티 가로등 프로젝트 팀장  
  AI/IoT 융합 프로젝트 기획 및 전체 시스템 설계  
  *[삼성아카데미]*

---

## 🧰 Tech Stack

- **Languages:** Python, JavaScript, HTML, CSS, SQL  
- **Backend:** Flask, RESTful API, MySQL  
- **Frontend:** HTML5, CSS3, Vanilla JS  
- **AI/ML:** YOLOv8, OpenCV, TensorFlow, Scikit-learn  
- **IoT/Hardware:** Arduino, ESP32-CAM, 센서 제어 (초음파, 기울기, 광센서)  
- **DevOps:** Git, Ubuntu Server, IPTime 포트포워딩, Cloudflare  
- **Tools:** VS Code, SQLyog, Tinkercad, Google Cloud Vision API, Kakao API

---

## 📜 Certifications

- 정보처리기사 (2020-08)  
- 컴퓨터활용능력 1급 (2020-11)  
- SQLD (2025-04)  
- 그외 전기기사, 전기공사기사

---

## 📂 Portfolio System

> **두 개의 프로젝트를 하나의 웹 시스템으로 통합한 포트폴리오 서버**

- Flask Blueprint 구조를 활용해 PopcornAPP과 Employment Site를 각각 모듈화  
- HTML 기반 포트폴리오 메인 페이지에서 두 프로젝트에 접근 가능  
- Python + Flask로 서버 구성  
- IPTime 포트포워딩 + Cloudflare를 통해 외부 도메인에 배포  
- 학원 PC에서 Git Push → 집 Ubuntu 서버가 자동 Pull & 실행

---

## 🚦 SmartCity_Pole (SafeLight)

> **AI + IoT + Web이 통합된 스마트 가로등 기반 도시 안전 관리 시스템**

### 🎯 프로젝트 개요  
스마트 가로등에 AI 카메라와 다양한 센서를 탑재하여  
**불법주정차 감지, 인도 위 오토바이 감지, 긴급 상황 자동 신고, 자가 고장 감지**까지 수행하는 통합 시스템입니다.

### 🔧 주요 기능
- 인도 위 오토바이 위반 감지 (YOLOv8)  
- 번호판 인식 (Google OCR 활용 ANPR)  
- 긴급 SOS 버튼 (Arduino + ESP32-CAM + 실시간 영상 스트리밍)  
- 센서 기반 고장 감지 (기울기/밝기)  
- 직원 대시보드로 웹에서 원격으로 LED 제어  
- MIT App Inventor 기반 APP으로 중앙 제어 및 아두이노와 웹 간 통신  
- SOS 버튼 또는 불법주정차 발생 시 **임시 경찰서 Web, 시청 Web**으로 **RESTful API**를 통해 자동 신고

### 🏗️ 아키텍처 구성
- **AI**: YOLOv8 + OpenCV  
- **OCR**: Google Cloud Vision API  
- **하드웨어**: Arduino, ESP32-CAM, 각종 센서  
- **백엔드**: Flask + MySQL  
- **웹**: HTML, JavaScript  
- **인프라**: Git + Ubuntu + 포트포워딩 + Cloudflare

---

## 🍿 PopcornAPP

> **AI + 실시간 영화 정보 + 사용자 참여 시스템이 결합된 영화 분석 플랫폼**

### 🎯 기능 개요  
- 80,000개의 영화 리뷰 데이터를 기반으로 학습된 **AI 모델**을 통해  
  사용자가 입력한 리뷰 텍스트를 긍정/부정으로 자동 분류합니다.  
- 영화진흥위원회 Open API와 YouTube API를 연동하여  
  실시간 **영화 순위 시각화**, **예고편 영상 제공** 기능도 함께 제공됩니다.

### 💡 주요 기능
- 감성 분석: TF-IDF + Logistic Regression 기반 AI 모델 (joblib 저장)  
- 실시간 박스오피스 API 연동: 일일 매출액/관객 수 차트 시각화  
- YouTube API 연동: 해당 영화 예고편 자동 재생  
- 데이터베이스 연동: 리뷰, 유저, 영화 정보 통합 저장  
- POPCORN 코인 시스템:
  - 추천수, 댓글수, 조회수에 따라 가상 코인 획득  
  - 관객 수 500만 이상 예측 이벤트 참여 → 맞추면 영화관 티켓 보상

### 🌐 인프라 구성
- Flask 웹 UI + 데이터 서버 구조  
- AI 모델 연동 및 API 통합  
- MySQL 데이터 저장 및 조회  
- 서버 자동화: Git Push → Ubuntu 서버에서 자동 Pull & Run  
- 외부 도메인 연결: IPTime 포트포워딩 + Cloudflare

---

## 💼 Total Employment Site

> **잡코리아 & 인크루트의 인기 채용공고 및 검색어 실시간 수집**

### 🔍 기능 요약  
- 웹 크롤링을 통해 실시간으로 인기 채용공고 및 검색 키워드 수집  
- 데이터를 기반으로 구직 트렌드를 파악할 수 있는 간단한 정보 플랫폼 구축

### 🧱 기술 스택  
- Python (Selenium, Requests)  
- Flask 기반 웹 서버 구성  
- 실시간 수집 데이터 시각화 예정 (향후 확장 계획)

---

## 📫 Contact

- 📧 Email: junhyuk000@naver.com  
- 🌐 Portfolio: [https://junhyuk000.monster](https://junhyuk000.monster)  
- 🐙 GitHub: [github.com/junhyuk000](https://github.com/junhyuk000)
