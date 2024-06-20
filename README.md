# Spring Boot Project - 내방공방(팀프로젝트)
온라인 강의 수강(내방 클래스)과 오프라인 강의 예약(공방클래스)을 통합한 **온오프라인 강의 플랫폼**</br></br>
![NBGB](https://github.com/yeooon030/JavaScript-to_do_list/assets/133891777/3f092791-0289-4549-897b-63da45daafe2)
</br></br>
프로젝트 시연 영상(https://youtu.be/ez3YYdofS14?si=9OaodXSLuRK1b6Da)

## 💻 1.프로젝트 소개
- 온라인 강의를 결제하여 일정 기간동안 강의를 수강할 수 있는 사이트입니다.
- 오프라인 강의를 수강하고자 하는 경우 예약 시스템을 통해 예약이 가능합니다.
- 일반회원은 수강 전, 중, 후로 채팅을 통해 강사회원과 소통할 수 있습니다.
- 일반회원은 수강완료 된 강의에 대해 별점 및 내용으로 강의 후기를 남길 수 있습니다.
- 관리자 승인을 통해 누구나 강의를 등록하고 수익을 창출할 수 있습니다.

## 🕑 2.개발기간
- 2024/04 ~ 2024/05(8주)

## ⚙ 3.개발환경
- 개발언어 : <img src="https://img.shields.io/badge/Java8-000000?style=flat&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=white"/>
- 프레임워크 : <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat&logo=springsecurity&logoColor=white"/> 
- 빌드 : <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white"/>
- DB : <img src="https://img.shields.io/badge/ORACLE-F80000?style=flat&logo=oracle&logoColor=white"/>
- ORM : <img src="https://img.shields.io/badge/JPA-FFAE33style=flat&logoColor=white"/> 
- 형상관리 : <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/SourceTree-0052CC?style=flat&logo=sourcetree&logoColor=white"/> 


## 👨‍👧‍👧 4.팀원 및 역할 분담
- **권재후(팀장)**
  - 회원가입 및 로그인(로컬 및 소셜)
  - 아이디/비밀번호 찾기, 회원정보 수정
  - 일반회원 마이페이지 中 결제내역, 결제취소, 찜 내역, 문의글 내역
- **김지수(부팀장)**
  - 채팅
  - 오프라인 강의 中 강의 목록, 강의 상세페이지
  - 강사회원 마이페이지 中 등록 강의 목록, 예약자 목록, 강의 후기 목록, 답변 작성
- **김인화(팀원)**
  - 메인페이지
  - 온라인 강의 中 강의 상세페이지, 강의 결제, 강의글 등록 및 수정
  - 온/오프라인 강의 中 후기글 신고
  - 강사회원 마이페이지 中 강의 삭제
- **박해근(팀원)**
  - 고객센터 中 문의글 작성
  - 관리자 페이지 中 회원상태 관리, 강의 승인 및 반려, 문의글 답변 작성
- **이수연(팀원)**
  - 온라인 강의 中 강의 목록, 강의 재생목록, 강의 재생 기능
  - 일반회원 마이페이지 中 온/오프라인 강의 수강목록, 후기글 작성 및 수정
  - 관리자 페이지 中 신고 접수 및 상태관리

## 👉 5.주요기능
![주요기능1](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/detail(1).PNG)
- - -
![주요기능2](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/detail(2).PNG)
- - -
![주요기능3](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/detail(3).PNG)
- - -
![주요기능4](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/detail(4).PNG)
- - -
![주요기능5](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/detail(5).PNG)

## 📃 6. 산출물
- ERD 다이어그램
  ![ERD다이어그램](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/ERD%20Diagram.png)

- 기능상세도
  ![기능상세도](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/Function%20Diagram(%EA%B8%B0%EB%8A%A5%EC%83%81%EC%84%B8%EB%8F%84).png)

- 플로우차트
  - 회원 기준(일반회원+강사회원)
    ![회원플로우차트](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/FlowChart(%ED%9A%8C%EC%9B%90).png)
  - 관리자 기준
    ![관리자플로우차트](https://github.com/yeooon030/NBGB/blob/master/src/main/resources/static/images/FlowChart(%EA%B4%80%EB%A6%AC%EC%9E%90).png)
