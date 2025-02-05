### SSAFY(삼성 청년 SW 아카데미)에서 진행한 프로젝트이며, 코드 반출 관련 허가가 승인되지 않는 프로젝트이므로 상세 코드는 확인이 어렵습니다. 양해 부탁드립니다.

# 여행자들을 위한 플래너 앱 ForTripper

---

![001](https://github.com/user-attachments/assets/ed1aacca-6e6b-48fc-b9c0-4615ac34d301)

## 프로젝트 소개

---

- ForTripper는 국내 당일치기부터 해외 장기여행까지 사람들이 쉽게 플랜을 짤 수 있고, 플랜을 서로 공유하며 여행에 대한 정보를 얻을 수 있는 웹사이트입니다.
- 자신의 플랜 페이지에서 쉽게 플랜을 생성하고 여행 계획을 짤 수 있습니다.
- 플랜 공유 게시판을 통해서 다른 사람들의 여행 플랜을 참고할 수 있고, 마음에 드는 플랜을 나의 플랜으로 저장하여 편집할 수 있어 가보지 못한 여행지의 플랜을 쉽게 짤 수 있습니다.
- 축제 정보 게시판을 통해 자신이 여행을 가는 기간에 해당 지역의 축제를 조회하여 축제 정보를 얻을 수 있습니다.

## 팀원 구성

---

- 이은선
- 정한균

## 1. 개발 환경

---

## 📂 **Environment**

- **VS Code**
- **GitLab**
- **IntelliJ IDEA**

## ⚙️ **Config**

- **NPM** (Node Package Manager)

## 🛠 **Development**

- **Frontend**
  - JavaScript
  - Vue.js
  - Vuetify
- **Backend**
  - Java
  - Spring Boot

## 🗂 **Communication**

- **Notion**

## 2. 역할 분담

---

### 이은선

- UI
  - 페이지: 계획 메인, 계획 작성, 계획 상세, 계획 수정, 계획 공유 게시판, 계획 공유 게시판 상세
- 기능
  - 계획 작성 및 수정, 공유 게시판 작성, 공유 게시판 상세, 공유 게시판 게시 계획 저장

### 정한균

- UI
  - 페이지: 회원가입, 비밀번호 찾기, 회원 수정, 프로필 수정, 홈 메인, 축제 게시판
- 기능
  - 회원가입 및 로그인, 유저 비밀번호 찾기, 유저 아이디 유효성 및 중복 검사, 축제 게시판 조회 및 검색

## 3. 개발 기간 (11/15~11/26)

---

![%EC%97%85%EB%AC%B4_%EC%9D%BC%EC%A0%95_%EC%BA%A1%EC%B2%98](https://github.com/user-attachments/assets/769f2841-b242-4120-a29c-a54784b10c0a)

## 4. 페이지 별 기능

---

### [초기 화면]

- 메인 페이지 접속
- 배너, 현재 진행중인 축제 List 등 조회 가능
- 메인 페이지에서 현재 진행중인 축제의 ‘네이버 검색’ 버튼을 누르면 네이버 검색 결과 페이지로 이동

![KakaoTalk_20241201_083652612](https://github.com/user-attachments/assets/5940823b-e7bc-45d4-8ac7-f0c53ca3f24a)
![KakaoTalk_20241201_083652612_01](https://github.com/user-attachments/assets/612f679c-96d2-4ac6-bfe4-1ba1fa34b87b)
![KakaoTalk_20241201_083652612_02](https://github.com/user-attachments/assets/4b538fba-6428-491a-9ad1-e236b12ca797)

### [회원가입, 로그인]

- 이메일, 닉네임 유효성 검사
- 회원가입 시 입력된 이메일로 인증 메일 전송
- 인증 메일 클릭 시 회원가입 완료, 이메일로 로그인

![KakaoTalk_20241201_083652612_03](https://github.com/user-attachments/assets/a720b0e6-6f84-4bf4-a240-0d3a1c31fa05)
![KakaoTalk_20241201_083652612_04](https://github.com/user-attachments/assets/f62a15e5-f4a5-49f6-871a-4ebc14aecda7)
![KakaoTalk_20241201_083652612_05](https://github.com/user-attachments/assets/03a2d15b-6037-413e-a9fb-dd5ee8a86845)

### [비밀번호 재설정]

- 비밀번호 재설정 시 자신이 가입한 이메일로 비밀번호 재설정 링크 전송

![KakaoTalk_20241201_083652612_06](https://github.com/user-attachments/assets/2b0a4ff2-87cb-41f8-b568-430c478fb830)
![KakaoTalk_20241201_083652612_07](https://github.com/user-attachments/assets/224f358c-fa94-4094-9df0-3dbea3253905)

### [프로필]

- 자신의 닉네임, 프로필 사진, 가입일, 여행 계획, 친구 목록 조회 가능
- 프로필 수정 버튼을 통해 자신의 프로필 정보, 비밀번호 수정 가능

![KakaoTalk_20241201_083652612_08](https://github.com/user-attachments/assets/5cbb9abd-2f7d-4b7b-94a5-35a0887d8018)
![KakaoTalk_20241201_083652612_09](https://github.com/user-attachments/assets/58f2118e-0865-4417-9d3f-3f10745d760b)
![KakaoTalk_20241201_083652612_10](https://github.com/user-attachments/assets/f081b44f-5c9f-442f-8832-33b58cc16bc5)

### [유저 검색, 친구 등록]

- 닉네임을 통해 유저 검색 가능
- 특정 유저 페이지의 ‘친구 설정’ 버튼을 통해 친구 추가 가능

![KakaoTalk_20241201_083652612_11](https://github.com/user-attachments/assets/2e78080b-c792-47a2-a2d5-f68d7c2f10fc)
![KakaoTalk_20241201_083652612_12](https://github.com/user-attachments/assets/4bb7bd10-3636-4bec-864e-bf0d4bd0a9a5)

### [축제 정보 게시판]

- 공공데이터 API를 통해 축제 정보 조회
- 키워드 기반/일정 기반 검색 가능, 원하는 지역 선택 시 해당 지역의 키워드/일정에 맞는 축제 검색결과 조회

![KakaoTalk_20241201_083652612_13](https://github.com/user-attachments/assets/11bf10d4-9061-4147-a5ab-f957bbedcf6d)
![KakaoTalk_20241201_083652612_14](https://github.com/user-attachments/assets/f5a63960-434f-41bf-9164-c77040bc16f4)

### [나의 플랜 메인]

- 로그인 후 상단 네비게이션 바의 ‘계획’ 버튼을 통해 접근 가능
- 현재 저장된 개인 여행 플랜 조회 가능
- ‘새 여행 플랜 생성하기’ 버튼을 통해 플랜 생성

![KakaoTalk_20241201_083652612_15](https://github.com/user-attachments/assets/34b89889-3061-41fc-92ac-39ea0dedeb33)

### [나의 플랜 생성]

- 플랜 타이틀, 날짜, 내용 설정 후 플랜 생성
- 플랜 생성 후 플랜 메인 페이지에서 생성 확인 가능

![KakaoTalk_20241201_083652612_16](https://github.com/user-attachments/assets/2610bb08-6f55-4d62-a334-18a99ca2c7cb)

### [플랜 일정 수정]

- 날짜별 List를 클릭해 해당 일자의 계획 추가/수정/삭제 가능
- 드래그 앤 드롭을 이용한 일정 순서 변경 가능
- Google Place API, Google Map API를 이용한 장소 검색, 위치 조회 가능
- 검색 결과 List의 특정 장소 클릭 시 해당 장소의 세부 정보 조회 가능
- 플랜 저장 후 플랜 세부 페이지에서 일자 별 일정 조회 가능, 지도 위에 일정 별 순서대로 마커 표시

![KakaoTalk_20241201_083652612_19](https://github.com/user-attachments/assets/0a838971-ad12-4d41-95c7-6a407bc56e4d)
![KakaoTalk_20241201_083652612_18](https://github.com/user-attachments/assets/a7807a37-d5af-447e-8ca4-b1fcef8354a7)
![KakaoTalk_20241201_083652612_20](https://github.com/user-attachments/assets/7ce3a5dd-c1da-4309-8309-d9fa1facb6a3)

### [AI ChatBot]

- Chat GPT API를 이용한 챗봇
- 해당 챗봇에게 여행지, 일정 등을 입력하고 특정 카테고리의 관광지 추천 질문 시 답변을 통해 관광지 정보를 얻을 수 있음

![KakaoTalk_20241201_083652612_18](https://github.com/user-attachments/assets/92e2ca51-fc02-41dd-b225-b212fb90b21f)

### [플랜 공유 게시판 메인]

- 현재 작성된 다른 유저들의 플랜 조회 가능
- ‘나의 플랜 공유하기’ 버튼을 통해 플랜 공유 게시글 작성 가능

![KakaoTalk_20241201_083652612_21](https://github.com/user-attachments/assets/b7e6079e-a6cd-4606-bcb3-215d87a114bf)
![KakaoTalk_20241201_083652612_22](https://github.com/user-attachments/assets/99a6be15-4e36-4b7d-a12d-0269b6daf386)
![KakaoTalk_20241201_083652612_23](https://github.com/user-attachments/assets/b05494ea-7154-40ec-8e43-e6db93b0eb2c)
![KakaoTalk_20241201_083652612_24](https://github.com/user-attachments/assets/2430fbf7-03f5-46c5-9dbd-91b48ca8ce01)
![KakaoTalk_20241201_083652612_25](https://github.com/user-attachments/assets/d53098aa-88f2-44cb-9267-b4b9c8e2d330)

### [플랜 공유 게시글 조회]

- 게시글 리스트의 특정 게시글 클릭 시 해당 플랜 조회 가능
- 일자 별 일정 조회 가능, 지도 위에 일정 별 순서대로 마커 표시

![KakaoTalk_20241201_083652612_26](https://github.com/user-attachments/assets/f1d5b2d2-3eef-4f92-9e92-3d3d7b8d35d0)

### [플랜 공유 게시글 저장]

- 플랜 공유 게시글 조회 페이지에서 나의 플랜으로 저장하기’ 버튼 클릭 시 원하는 날짜를 지정 후 플랜 저장 가능
- 저장한 플랜은 나의 플랜 페이지에서 조회 가능

![KakaoTalk_20241201_083652612_27](https://github.com/user-attachments/assets/0213dda7-eee4-47ea-9dbf-9d7da8554fad)
![KakaoTalk_20241201_083652612_28](https://github.com/user-attachments/assets/3c91b2d5-ed43-40af-a3d6-d1e88ef80c32)
![KakaoTalk_20241201_083652612_29](https://github.com/user-attachments/assets/4148349b-a15f-4ccb-85ce-2766d852db90)

## 5. 프로젝트 회고

- 약 열흘간의 기간동안 두명이서 기획부터 설계, 개발까지 모두 끝내야 했기 때문에 쉽지 않은 과정이었습니다. 적은 인원, 짧은 개발 기간이라는 제약 때문에 추가적으로 넣고 싶었던 기능들을 넣지 못했다는 아쉬움이 있었지만, 덕분에 사용자에게 필요한 기능들의 우선순위를 끊임없이 고려하고 기능들 자체의 완성도를 높이기 위해 노력할 수 있었고 결과를 낼 수 있었다고 생각합니다.
- 팀원과 저 둘 다 백엔드를 주로 학습했던 개발자였기에 프론트를 구현하는데에 있어서 시행착오를 많이 겪었지만, 이 과정을 통해 클라이언트와 서버의 상호작용에 대해 이해를 넓힐 수 있었고 시스템의 구조에 대해 보다 상세히 파악하며 개발을 진행할 수 있었습니다. 덕분에 아무리 백엔드 개발자라 할 지라도 프론트에 대한 지식이 있는 것과 없는 것의 차이는 크다는 것을 배웠습니다.
- 설계 단계에서 생각지 못했던 부분을 개발 과정에서 깨닫게 되어 DB 구조를 일부 수정해야 했던 적이 있었는데, 이 과정을 통해 꼼꼼하고 치밀한 설계가 얼마나 중요한지에 대해 깨달을 수 있었습니다.
