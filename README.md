### 개요
- 2023 3-2 고급모바일프로그래밍 과목 기말 팀 프로젝트로, 파이어베이스를 활용한 매우 간단한 수준의 중고 거래 마켓 앱입니다.
- 프로젝트 이름: SecondHand_Market
- 프로젝트 기간: 2023.10.23 ~ 12.01
- 개발 엔진 및 언어: Android Studio, Kotlin
- 멤버: 김성민, 김수아, 이진욱, 신정인

### 내용
- Firebase Authentication을 활용한 로그인, 회원가입: 이메일 로그인을 통해 사용자 계정을 생성하고 로그인 합니다.
- 실시간 중고 물품 등록 및 게시판: 사용자가 판매하고자 하는 물품의 사진, 제목, 가격, 내용을 작성하여 Firebase Realtime Database에 등록하고 게시판에서 볼 수 있습니다.
- 실시간 채팅 시스템: 구매자와 판매자 간의 거래를 위해 Firebase를 이용한 1:1 채팅 기능을 제공하며, 메시지 전송 시 실시간으로 대화 내용이 업데이트됩니다.
- 게시글 관리 및 수정: 자신이 올린 게시글을 상세 화면에서 확인하고, 필요 시 내용을 수정하거나 삭제할 수 있습니다.
- 이미지 업로드 및 저장: Firebase Storage를 활용하여 물품 사진을 서버에 저장하고, 게시글 로딩 시 Glide 라이브러리를 통해 이미지를 보여줍니다.

### 화면

| **로그인** | **회원가입** | **거래 홈** |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/46f8c1a3-89bc-4cca-8e92-e70c1502720a" width="250"> | <img src="https://github.com/user-attachments/assets/893c9766-5559-4ba5-9afa-f77f2e1059ef" width="250"> | <img src="https://github.com/user-attachments/assets/ee334a1f-a36c-4de5-918d-4af2e954b419" width="250"> |

| **게시글 상세** | **글 작성** | **실시간 채팅** |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/aa83e2be-39ad-4d6d-94e7-a35b227109ba" width="250"> | <img src="https://github.com/user-attachments/assets/2b510d1d-3dbe-49cc-ace6-152a0c5b8968" width="250"> | <img src="https://github.com/user-attachments/assets/c5325f4f-c337-4e04-9d41-dd38514e10f5" width="250"> |

### 기술스택

| **Category** | **TechStack** |
| :---: | :---: |
| **Language** | Kotlin |
| **UI** | XML |
| **Database** | Firebase Realtime Database |
| **Storage** | Firebase Storage |
| **Authentication** | Firebase Auth |
| **Library** | Glide |

### 느낀점
- 기초적인 UI 구조 설계부터 파이어베이스 연동까지 앱 개발 과정을 경험해 볼 수 있었습니다.
- 채팅이나 이미지 업로드 같은 기능을 하나씩 완성해 가며 안드로이드 개발의 즐거움과 팀 프로젝트를 통해 개발 협업을 처음으로 경험하고 배울 수 있었습니다. 
