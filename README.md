# 윤희혁 | Backend Developer

안녕하세요. **앞으로 나아가는 백엔드 개발자 윤희혁입니다.**

Java와 Spring Boot를 기반으로 REST API 및 웹 서비스를 개발한 경험이 있으며,
PostgreSQL과 Oracle을 활용한 데이터베이스 설계 및 데이터 처리 경험을 가지고 있습니다.

또한 LLM, RAG, Ollama 등의 기술을 활용하여 AI 서비스를 개발하며
기존 웹 서비스에 AI 기술을 적용하는 것에도 관심을 가지고 있습니다.

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Node.js
* REST API

### Database

* PostgreSQL
* MySQL
* Oracle

### AI / Machine Learning

* LLM
* RAG
* Ollama
* TensorFlow
* YOLOv8

### Frontend

* HTML
* CSS
* JavaScript
* React

### Tools & Environment

* Git / GitHub
* SVN
* Maven
* AWS
* Jupyter Notebook

---

# 📂 Projects

## 1. 해외 배송 관리 웹 서비스

**팀 프로젝트 | 2025.06 ~ 2025.10**

### 프로젝트 소개

삼성전자 로지텍의 해외 배송 업무를 관리하기 위한
웹 서비스를 개발했습니다.

### 담당 업무

* 배송 상태 조회 및 관리 기능 구현
* 배송 취소 및 승인 기능 구현
* 배송 자재 관리 기능 구현
* 게시판 기능 구현
* REST API 개발
* PostgreSQL 데이터베이스 설계 및 연동
* SVN을 이용한 형상 관리

### Tech Stack

* Java
* Spring Boot
* PostgreSQL
* SVN

### 주요 경험

Spring Boot를 기반으로 REST API를 개발하고
PostgreSQL을 활용하여 배송 및 자재 데이터를 관리했습니다.

실제 업무에서 사용되는 서비스 개발에 참여하면서
백엔드 API 설계 및 데이터베이스 연동 경험을 쌓았습니다.

---

## 2. 광주대학교 캠퍼스 가이드 AI - GuBot

**팀 프로젝트 | 2024.11 ~ 2025.06**

### 프로젝트 소개

광주대학교 학생들에게 학교 생활에 필요한 정보를 제공하는
AI 기반 캠퍼스 도우미 서비스입니다.

학생이 질문을 입력하면 광주대학교의 다양한 정보를 기반으로
답변을 제공하며, 학점 계산 등의 기능을 통해 학생들의 학교생활을 지원하도록 개발했습니다.

### 담당 업무

* 외부 API 연동 및 데이터 통신
* AI 관련 기능 구현 지원
* 서비스 기능 구현
* 서버 관리 지원
* Spring Boot 기반 백엔드 개발

### Tech Stack

* Spring Boot
* React
* Python
* LLM
* Hugging Face

### 주요 기능

* 학교 관련 정보 질의응답
* AI 기반 정보 제공
* 학점 계산 기능
* 학교 생활 관련 편의 기능

### 프로젝트 경험

AI 모델과 웹 서비스 사이의 데이터 흐름을 이해하고
Spring Boot를 활용하여 API 및 서비스 기능을 구현했습니다.

### Repository

https://github.com/rmflsdl4/PortfolioProject.git

---

## 3. Discord Movie Bot

**개인 프로젝트 | 2026.08 ~ 진행 중**

### 프로젝트 소개

Discord에서 사용자의 영화 관련 질문을 받아
영화 정보와 AI 기반 답변을 제공하는 Discord Bot입니다.

Spring Boot를 백엔드 서버로 사용하고
JDA를 통해 Discord와 통신하며, TMDB API와 RAG, Ollama를 연동하여
영화 정보를 검색하고 AI 답변을 생성하도록 개발하고 있습니다.

### 시스템 구조

```text
Discord
   │
   ▼
JDA
   │
   ▼
Spring Boot
   │
   ├──────────────► TMDB API
   │
   ▼
RAG / Vector Store
   │
   ▼
Ollama
   │
   ▼
LLM
   │
   ▼
AI Response
   │
   ▼
Discord
```

### 주요 기능

* Discord 영화 질의응답
* TMDB API 영화 정보 검색
* 영화 관련 문서 검색
* RAG 기반 정보 검색
* Vector Store를 이용한 문서 저장 및 검색
* Ollama 기반 로컬 LLM 연동
* Spring Boot REST API 구현

### Tech Stack

* Java
* Spring Boot
* JDA
* Ollama
* LLM
* RAG
* Vector Store
* TMDB API
* Maven

### 주요 경험

LLM을 단순히 호출하는 방식에서 벗어나
영화 관련 데이터를 검색한 뒤 검색 결과를 LLM의 답변 생성에 활용하는
RAG 구조를 직접 구현하고 있습니다.

또한 Discord → Spring Boot → AI 서버로 이어지는
서비스 간 데이터 통신 구조를 직접 구성하며 백엔드 개발 경험을 확장하고 있습니다.

### Repository

https://github.com/Wjfjs/movie-bot

---

## 4. AI 건물 균열 검사

**팀 프로젝트 | 2023.09 ~ 2023.11**

🏆 **한전KDN 2023 빛가람 에너지밸리 소프트웨어 작품 경진대회 대상**

### 프로젝트 소개

건물 사진을 분석하여 균열의 종류를 확인하고
전문가의 의견을 확인할 수 있도록 제작한 AI 기반 웹 서비스입니다.

Node.js를 기반으로 웹 서버를 구축했으며,
TensorFlow를 활용하여 건물 균열을 분석하는 기능을 구현했습니다.

### 담당 업무

* Git을 이용한 프로젝트 버전 관리
* JavaScript 기반 웹 기능 구현
* 전문가 관련 기능 구현
* 관리자 기능 구현
* 회원가입 및 로그인 기능 구현
* 백엔드 개발

### Tech Stack

* HTML
* JavaScript
* Node.js
* TensorFlow
* AWS
* Git

### 프로젝트 성과

한전KDN 2023 빛가람 에너지밸리
소프트웨어 작품 경진대회에서 **대상**을 수상했습니다.

### Repository

https://github.com/rmflsdl4/ProjectSinerva

---

## 5. 영화 정보 사이트

**개인 프로젝트 → 팀 프로젝트 | 대학교 2~3학년**

### 프로젝트 소개

영화 정보를 제공하고 사용자가 원하는 영화를 검색할 수 있는
영화 정보 웹 사이트를 개발했습니다.

### 담당 업무

* 웹 페이지 디자인
* Oracle 데이터베이스 설계
* 영화 검색 기능 구현
* 영화 추천 기능 구현
* 좋아요 기능 구현
* 댓글 CRUD 구현
* 영화 데이터 처리

### Tech Stack

* HTML
* JavaScript
* PHP
* Oracle
* Apache

### 주요 경험

Oracle 데이터베이스를 직접 설계하고
PHP와 Oracle을 연동하여 영화 검색 및 사용자 기능을 구현했습니다.

웹 서비스의 프론트엔드부터 데이터베이스까지
전체적인 서비스 개발 과정을 경험했습니다.

### Repository

https://github.com/Wjfjs/MovieWebSite

---

## 6. YOLOv8 기반 교통 관리 시스템

**팀 프로젝트**

### 프로젝트 소개

도로의 차량을 실시간으로 감지하여
교통량에 따라 신호를 자동으로 변경하고
불필요한 교통 체증을 줄이는 것을 목표로 한 교통 관리 시스템입니다.

### 담당 업무

* 차량 객체 인식 기능 구현
* 객체 학습
* 학습 데이터 및 파일 관리
* 객체 인식 결과 처리

### Tech Stack

* Python
* HTML
* JavaScript
* Node.js
* YOLOv8

### 주요 경험

YOLOv8을 활용하여 차량 객체를 학습하고
영상에서 차량을 인식하는 기능을 구현했습니다.

AI 모델의 학습부터 웹 서비스와의 연동까지
AI 기반 서비스 개발 과정을 경험했습니다.

### Repository

https://github.com/Wjfjs/Capstone

---

## 7. 빅데이터를 활용한 범죄 발생 통계 분석

**개인 프로젝트**

### 프로젝트 소개

연간 범죄 데이터를 수집하고 분석하여
지역별 범죄 발생 분포를 시각화하는 데이터 분석 프로젝트입니다.

범죄 데이터를 분석하고 지도에 범죄 발생 밀집 지역을 표시하여
지역별 범죄 위험도를 확인할 수 있도록 구현했습니다.

### 담당 업무

* 범죄 데이터 수집
* 데이터 전처리 및 분석
* 통계 분석
* 그래프 제작
* WMS를 활용한 지도 데이터 표시
* 범죄 분포 시각화

### Tech Stack

* Python
* Jupyter Notebook
* WMS

### Repository

https://github.com/Wjfjs/bigData

---

# 📈 Development Experience

제가 경험한 프로젝트를 통해 다음과 같은 개발 경험을 쌓았습니다.

### Backend

* Spring Boot 기반 REST API 개발
* Node.js 기반 서버 개발
* 외부 API 연동
* 서버와 클라이언트 간 데이터 통신
* 데이터베이스 설계 및 연동

### Database

* PostgreSQL
* Oracle
* MySQL
* SQL 작성 및 데이터 처리

### AI / LLM

* TensorFlow
* YOLOv8
* Hugging Face
* LLM
* Ollama
* RAG
* Vector Store

### Collaboration

* Git / GitHub
* SVN
* 팀 프로젝트 협업 경험
* 실제 서비스 개발 경험

---

# 🎯 Currently Learning

현재는 **Spring Boot 기반 백엔드 개발과 AI 기술의 결합**에 관심을 가지고 학습하고 있습니다.

특히 다음 기술을 중심으로 개인 프로젝트를 진행하고 있습니다.

* Spring Boot
* REST API
* LLM
* RAG
* Ollama
* Vector Store
* AI 서비스 개발

앞으로는 백엔드 개발 역량을 기반으로
AI 기술을 실제 서비스에 적용할 수 있는 개발자를 목표로 하고 있습니다.
