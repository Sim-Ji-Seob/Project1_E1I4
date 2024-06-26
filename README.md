![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=100&section=header&text=E1I4의%20팀프로젝트&fontSize=50)

# E1I4TeamProject
<img src="src/main/resources/static/images/readme/mainlogo.png" alt="mainLogo" width="250" height="150">

## 🔍 전체 목차<br>
- [개요](#프로젝트-개요)<br>
- [주요 기능](#-주요-기능-)<br>
- [프로젝트 상세](#-프로젝트-상세-)<br>


<details>
<summary>1차 프로젝트 기본설정</summary>
프로젝트명 : E1i4TeamProject

프로그래밍 언어 : JAVA

프레임워크 : Springboot 2.7.11

라이브러리 DI : Spring WEB(MVC), Thymeleaf, Spring Data JPA, Lombok, SpringSecurity5 
               , websocket, validation, OAuth2, security  

데이터베이스 : MySql8

ORM : Spring Data JPA (JAVA(SQL))

개발툴 : IntelliJ

템플릿 엔진 : Thymeleaf (HTML + Data)

빌드 : Gradle

설정 : application.yml, application-oauth2.yml(google,naver,kakao api 키 필요)

기타 설정: 
1. setting - gradle<br>
<img src="src/main/resources/static/images/readme/img_9.png" width="250px" height="150px"/> <br>
2. project Structure - SDK -> 11 <br>
   <img src="src/main/resources/static/images/readme/img_10.png" width="400px" height="50px"/> <br>

</details>

## 📌 프로젝트 Git 다운로드 주소 📌 
$git clone https://github.com/Sim-Ji-Seob/Project1_E1I4.git  
branch : master

# 📝프로젝트 개요
## 🗓️일정
<img src="src/main/resources/static/images/readme/img.png" width="400px" height="200px"/> <br>

## 📝개요
<details>
<summary>프로젝트 개요</summary>
1차 프로젝트는 강좌를 구매하는 판매사이트를 만들었습니다. 최근 온라인 강의 뿐만 아니라 오프라인강의도 
온라인으로 구매를 하는 경우가 많아졌습니다. 따라서 사용자 입장에서 편리하게 사용하고 
계속해서 이용하고 싶은 사이트를 구현하였습니다.

</details><br>

## 🖱️개발 환경🖱️
### <span style="color: white;">💻사용 프로그램💻</span> <br>
<p>
<img src="https://img.shields.io/badge/notion-white?style=flat-square&logo=notion&logoColor=gray"/>
<img src="https://img.shields.io/badge/mysql-2E64FE?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/visualstudiocode-81BEF7?style=flat-square&logo=visualstudiocode&logoColor=blue"/>
<img src="https://img.shields.io/badge/intellijidea-navy?style=flat-square&logo=intellijidea&logoColor=white"/>
<img src="https://img.shields.io/badge/github-black?style=-square&logo=github&logoColor=white"/>
</p>

### <span style="color: white;">🛠개발 환경 🛠</span> <br>
<p>
<img src="https://img.shields.io/badge/html5-green?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/css3-blue?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/auth0-ccc?style=flat-square&logo=auth0&logoColor=white"/>
<img src="https://img.shields.io/badge/chatbot-orange?style=flat-square&logo=chatbot&logoColor=white"/>
<img src="https://img.shields.io/badge/javascript-yellow?style=flat-square&logo=javascript&logoColor=white"/>
<img src="https://img.shields.io/badge/jquery-light?style=flat-square&logo=jquery&logoColor=white"/>
<img src="https://img.shields.io/badge/json-purple?style=flat-square&logo=json&logoColor=white"/>
<img src="https://img.shields.io/badge/openapiinitiative-FA5858?style=flat-square&logo=openapiinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/thymeleaf-0B610B?style=flat-square&logo=thymeleaf&logoColor=white"/>
<img src="https://img.shields.io/badge/spring-0B610B?style=flat-square&logo=spring&logoColor=white"/>
<img src="src/main/resources/static/images/readme/oAuth2.png" width="20" height="20"/> <br>
</p>

# ⚡ 팀원별 역할 ⚡
- [ ] 박** (팀장) : DB설계, 회원 CRUD, Oauth2, Security, CI/CD
- [ ] 손** (팀원) : 관리자페이지, ChatBot, 강사소개 페이지, 메뉴바, INDEX 애니메이션 기능
- [x] <span style='background-color:green'>_**심지섭 (팀원) : 게시판 CRUD, Naver API**_</span>
- [ ] 이** (팀원) : 상품 CRUD, Cart 담당
- [ ] 조** (팀원) : INDEX 페이지, 1:1 문의내역, Naver API

#  🚀 주요 기능 🚀

| 기능        | 설명                                                                            | 
|-----------|-------------------------------------------------------------------------------|
| 게시글 작성    | 게시글 작성<br> 게시글 종류 선택(자유/질문, 공지사항, 수강후기(4종류) )<br>                             |
| 게시글 수정    | 게시글의 종류와 제목 등 데이터 수정                                        <br/>             |
| 게시글 삭제    | 본인글만 삭제 가능, ADMIN 권한자는 모든 글 삭제 가능                                             |
| 게시글 댓글    | 게시글마다 댓글 기능 구현(작성, 삭제 가능)                                                     |
| 게시글 검색    | 게시글의 제목과 내용 중 하나를 선택하여 해당 키워드를 검색                                             |
| 회원 권한     | 권한에 따라 작성할 수 있는 게시글 종류 제한<br> 권한에 따라 삭제,수정 기능 제한<br> ADMIN 계정은 모든 글, 댓글 삭제 가능 |
| Index 페이지 | Index 페이지에 조회수에 따른 인기 수강후기 게시글 출력                                             |


# 📁 프로젝트 상세 
## 목차
1. [게시글 CRUD](#-게시글-CRUD-)
2. [목록, 검색, 페이징](#2-목록-검색-페이징-기능)
3. [댓글 기능](#-댓글-기능-)
4. [권한에 따른 기능](#-권한에-따른-기능)
5. [Index 페이지](#-Index-페이지-)
6. [사이드바]()


## 1️⃣ 게시글 CRUD  
글 작성시 게시글의 종류를 선택할 수 있습니다. 또한 작성자란에는 로그인한 회원의 이름이 출력되도록 했습니다.<br>
작성시 글의 종류는 카테고리 값으로 설정하여 하나의 Entity에 통합하여 사용하도록 했습니다.
<img src="src/main/resources/static/images/readme/img_1.png" width="300px" height="300px"/> <br>
<br>

파일을 선택해서 넣게 되면 사진처럼 선택된 파일 이름이 나오게 됩니다.<br>
<img src="src/main/resources/static/images/readme/img_8.png" width="300" height="70px"/> <br>

수정과 삭제는 게시글의 Board_Id를 통해 글 정보를 가져오고 서비스를 사용해 실행합니다.
![1차 글 수정 및 삭제](https://github.com/Sim-Ji-Seob/Project1_E1I4/assets/154939602/1f110aca-252b-49ce-8ec9-f630aa77c274)

## 2️⃣ 목록, 검색, 페이징 기능
게시글 목록에서 제목과 내용 중 하나를 선택하여 검색을 할 수 있습니다. 일부의 내용만 포함하더라도 검색이 가능합니다.
또한 글이 많을 시 페이지를 이동할 수 있도록 하는 기능도 구현하였습니다. 맨앞, 맨뒤 페이지도 이동하는 기능도 추가하였습니다.

![1차 검색, 페이징](https://github.com/Sim-Ji-Seob/Project1_E1I4/assets/154939602/b5e879df-11bb-47a3-a7c6-fc44e6ea8d2c)


## 3️⃣ 댓글 기능 
<img src="src/main/resources/static/images/readme/img_3.png" width="400px" height="200px"/> <br>
게시글에는 댓글을 달 수 있도록 기능을 구현했습니다. 로그인의 상태에 따라 댓글 기능사용에 제한을 두었습니다.<br>
또한 권한을 나누어 본인 댓글만 삭제 할 수 있도록 구현하였습니다. ADMIN 권한자는 모든 댓글을 삭제 할 수 있습니다.


## 4️⃣ 권한에 따른 기능 
<img src="src/main/resources/static/images/readme/img_2.png" width="500px" height="300px" /> <br>
권한에 따라서 글 상세보기에서의 버튼들이 다르게 보이도록 설정했습니다. 본인 글이 아니라면 수정, 삭제를 할 수 없습니다.
ADMIN 권한자만 공지사항 게시글을 작성 할 수 있으며 모든 글을 삭제할 수 있습니다.

## 5️⃣ Index 페이지 
<img src="src/main/resources/static/images/readme/img_7.png" width="500px" height="300px" /> <br>
Index Main 페이지에서 수강후기 게시글의 조회수 순위대로 보이도록 하였습니다. 
a태그를 활용하여 상세정보로 이동할 수 있도록 하였으며, 그리드와 리스트로 바꿀 수 있는 버튼도 만들었습니다.

![index-ezgif com-video-to-gif-converter](https://github.com/Sim-Ji-Seob/Project1_E1I4/assets/154939602/e7b9fefe-c0c1-4085-806f-af6eb970f2c6)

## 6️⃣ 사이드바
<img src="src/main/resources/static/images/readme/img_11.png" width="130" height="300px" /> <br>
사이드바 메뉴를 만들어 게시판에서의 이동을 편리하게 만들었습니다.
또한 수강후기에는 4개의 카테고리가 있어서 마우스를 Hover 시에 submenu가 아래로 내려오는 drop 형식을 사용했습니다.

![1차 사이드바 메뉴](https://github.com/Sim-Ji-Seob/Project1_E1I4/assets/154939602/b01fe6a5-a7e2-41c3-aefb-2f9122719690)

[⬆⬆맨위로⬆⬆](#E1I4TeamProject)

