<!-- 헤더 영역 -->
<div align="center">

# 👋 안녕하세요. 전경환입니다.

문제를 확인하고, 해결하며, 공유하는 풀스택 개발자입니다.

</div>

---

## 💡 About Me
- 🧑‍🏫 전산실 출신으로 꼼꼼함과 계획력을 바탕으로 업무를 주도적으로 수행  
- 🧩 구조 설계부터 실행, 정리(문서화)까지 책임지는 개발자 지향  
- 🧠 사용자 흐름 중심의 UI/UX 구성 경험  
- 🤖 LangGraph 기반 AI 에이전트 파이프라인 설계 및 실시간 자동화 시스템 구축 경험  
- 📚 정보처리기사, SQLD, 리눅스마스터2급, ADsP, MOS 마스터, BSCM 합격, 빅분기 필기합격  


---

<br>

## 🖥️ **기술 스택**
| 구분 | 기술 |
|------|------|
| **AI / Automation** | ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) |
| **Backend** | ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)  ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)  ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)  ![MaterialUI](https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=MUI&logoColor=white)  ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) |
| **Database** | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)  ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)   ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)|
| **Tools** | ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)    ![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)  ![VS Code Insiders](https://img.shields.io/badge/VS%20Code%20Insiders-35b393.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) |
| **Collaboration** | ![Kakao](https://img.shields.io/badge/kakao-FFCD00?style=for-the-badge&logo=kakao&logoColor=black) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)  ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)   ![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)   ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) | 

<br>

---

## 🤖 AI Agent / Automation Projects

### 🪙 BTC/ETH 실시간 자동매매 + LangGraph AI 에이전트 (개인 프로젝트)
[![260616_bitsum](https://img.shields.io/badge/GitHub-260616__bitsum-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gatsby6060/260616_bitsum)
[![실시간 자동매매 + LangGraph AI 에이전트](https://github.com/gatsby6060/260616_bitsum/blob/main/main1.png?raw=true )](https://github.com/gatsby6060/260616_bitsum )


- **BTC/ETH 다중 타임프레임(일봉·시간봉·분봉) 분석 기반 자동매매 시스템** 구축
- **LangGraph `StateGraph`** 를 활용하여 매매 체결 이벤트 발생 시 LLM(Gemini/OpenAI)이 매매 이유를 자동 분석하고 텔레그램·이메일로 알림을 발송하는 **AI 에이전트 파이프라인** 설계 및 구현
- **n8n Webhook 연동**으로 매매 체결 데이터를 Google Sheets에 자동 기록하는 Event-Driven 자동화 파이프라인 구축
- WebSocket 실시간 시세 수신 + `threading` + `queue` 기반 **멀티스레딩 이벤트 처리 엔진** 직접 설계
- **FastAPI** 기반 RESTful API 및 WebSocket 브로드캐스트 서버, 웹 대시보드 구현
- 시장 국면(Bull/Bear/Range) 자동 감지 및 전략 동적 전환, 손절/익절 리스크 관리 모듈 포함

**Tech Stack**: `Python` `FastAPI` `LangGraph` `LangChain` `Gemini API` `OpenAI API` `WebSocket` `n8n` `Pandas` `NumPy`

👉 **[프로젝트 상세 보기](https://github.com/gatsby6060/260616_bitsum)**
<br>
<br>

---



### 🛒 ShopMall - 풀스택 쇼핑몰 (개인 프로젝트)
[![jghshopmall](https://img.shields.io/badge/GitHub-jghshopmall-181717?style=for-the-badge&logo=github&logoColor=white )](https://github.com/gatsby6060/jghshopmall )
[![ShopMall 메인화면](https://github.com/gatsby6060/jghshopmall/blob/main/mobliemain.png?raw=true )](https://github.com/gatsby6060/jghshopmall )

- **Java 21 + Spring Boot 3.5 + Next.js 15** 기반 현대적인 풀스택 쇼핑몰 애플리케이션
- **Docker Compose** 멀티 스테이지 빌드로 Backend / Frontend / DB 전체 컨테이너 오케스트레이션
- JWT + OAuth2(Google, Naver, Kakao) 소셜 로그인, Spring Security 기반 인증/인가
- 토스페이먼츠 결제 위젯 연동, 카카오 지도 API 연동
- 관리자 대시보드(상품·카테고리·주문·회원 관리), 마이페이지, 상품 검색/필터/정렬 구현
- JPA 지연 로딩(LAZY), Zustand 전역 상태 관리, TanStack Query 서버 상태 관리 적용

**Tech Stack**: `Java 21` `Spring Boot 3.5` `Next.js 15` `TypeScript` `Tailwind CSS` `MariaDB` `Docker` `JWT` `OAuth2`

👉 **[프로젝트 상세 보기](https://github.com/gatsby6060/jghshopmall )**
  

  
---


## 📌 Projects

### 🧑‍💼 고객관리시스템 (개인 프로젝트, 소개팅, 결정사)
[![고객관리시스템](https://github.com/gatsby6060/vue_express_20250908/blob/main/resultphotos/login.png?raw=true)](https://github.com/gatsby6060/vue_express_20250908)

- 고객 소개 및 결제 기반 열람 시스템
- Vue + Node.js + Oracle
- 사장/직원/고객 권한 분리, 결제 후 정보 열람
- 주소 기반 위경도 변환 및 지도 표시

👉 **[프로젝트 상세 보기](https://github.com/gatsby6060/vue_express_20250908)**
<br>
<br>
<br>


---

### 🏃 RUNNERS' HOUSE (팀 프로젝트, 쇼핑몰)
[![RUNNERS HOUSE](https://github.com/user-attachments/assets/c1376fb2-4dc3-4f59-9620-8d3e374160c6)](https://github.com/kkomi211/springProject2025)

- 러닝 커뮤니티 + 쇼핑 플랫폼 (5인 팀 프로젝트)
- Spring Boot 기반 관리자/사용자 페이지
- **담당 역할**
  - 마이페이지
  - 결제 API 연동
  - 할인 금액 계산 로직

👉 **[프로젝트 상세 보기](https://github.com/kkomi211/springProject2025)**
<br>
<br>
<br>


---

### 📸 Instagram SNS (개인 프로젝트, SNS)
[![Instagram SNS](https://github.com/gatsby6060/react-sns-jgh251125/blob/main/readmeIMG/%EC%A0%84%EC%B2%B4%ED%99%94%EB%A9%B4.JPG?raw=true)](https://github.com/gatsby6060/react-sns-jgh251125)

- Instagram UI/UX 기반 SNS 웹 애플리케이션
- 피드 · 좋아요 · 댓글 · 검색 · DM · 프로필 기능 구현
- React + Express + MySQL, JWT 인증, 이미지/동영상 업로드

👉 **[프로젝트 상세 보기](https://github.com/gatsby6060/react-sns-jgh251125)**
<br>
<br>
<br>


---

### 🧑‍💼 플루터 (날씨 기반 행동 추천 앱)
[![날씨기반행동추천앱](https://github.com/hyeokjun9035/flutter_image/blob/main/one.png)](https://github.com/hyeokjun9035/flutterproject_team2)

- 날씨기반 행동추천 앱
- Flutter + Firebase
- 사고나 이슈가 발생시 반경 2km 이내 사용자에게 알림
- 본인이 원하는 장소 저장시 최소 시간 루트 확인 가능

👉 **[프로젝트 상세 보기](https://github.com/hyeokjun9035/flutterproject_team2)**
<br>
<br>
<br>


---

## 📫 Contact
- **Email**: uniline123@naver.com
- **GitHub**: https://github.com/gatsby6060
- **portfolio**: https://drive.google.com/file/d/1EMX0Xzde3D5J60Lkyz0twdthFT1sker_/view?usp=sharing
- **경력기술서**: https://drive.google.com/file/d/1enJSb8SvVOcMqhmiQPoL_SK-GLZePTQF/view?usp=sharing
- **Notion 도커+카프카+쇼핑몰**: https://app.notion.com/p/N8N-372d783cc6618069b636d9e54f420d5a
- **Notion n8n**: https://app.notion.com/p/N8N-372d783cc6618069b636d9e54f420d5a
