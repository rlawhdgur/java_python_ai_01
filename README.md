# 🎵 Last Carnival
- [배포 링크]() - 작업 중
- 👉 [발표영상링크]() - 작업 중
- 👉 [데모영상링크]() - 작업 중
***
![image](https://user-images.githubusercontent.com/120995529/230265566-69714b94-2250-49ab-9974-8f7800c69e01.png)

***

## 개요
### 1. 과제
- **Last.Fm**에서 **해외 음원 차트**를 활용한 음원 커뮤니티 사이트

### 2. 상세 설명
- 대부분의 국내 음원 사이트들은 해외 음원을 다루지 않고 있음
- 국내 음원 사이트 이용자들의 경우, 해외 차트도 이용하길 원하는 니즈가 존재하는 것을 확인
- 해외 음원 차트 기능이 포함 된 커뮤니티의 필요성을 통해 프로젝트 진행

### 3. 팀 구성
- 사용언어 : <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white">, <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat&logo=javascript&logoColor=black">, <img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white">, <img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white">, <img src="https://img.shields.io/badge/jquery-0769AD?style=flat&logo=jquery&logoColor=white">(ajax), <img src="https://img.shields.io/badge/SQL-F80000?style=flat&logo=SQL&logoColor=white">
- Framework : <img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat&logo=springsecurity&logoColor=white">, OAuth2, <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white">(v.2.7.9)
- DB : <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white">, <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white">
- 작업툴 : VS code, Eclipse
- 협업Tool : <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white">, Slack, Trello
- 인원 : 8명
- 주요 업무 : Spring Boot 프레임 워크를 이용한 웹 개발 구현 코드 작성
  - 로그인 / 회원가입
  - 이메일, 비밀번호 변경
  - 아이디 / 비밀번호 찾기
  - 유효성 검사
- 기간 : 2023-03-22 - 2023-04-12
***

### 프레임 워크 및 라이브러리 버전
- Java : 17.0.5v
- Spring Boot : 2.7.9v
- MyBatis
- Lombok
- Thymeleaf
- Validation
- Spring Security
- OAuth2 <br>
<details>
<summary> 프레임 워크 및 라이브러리 설명 </summary>

```
Spring Boot : Spring Framework를 기반으로 한 Java 애플리케이션 개발을 더욱 쉽고 빠르게 만들어주는 도구
MyBatis : OMR 프레임 워크, 데이터베이스에 접근, SQL 쿼리와 객체를 쉽게 매핑
Lombok : Java 언어를 위한 라이브러리, 반복적인 코드 작성을 줄여주는 기능(Getter, Setter ..)
Thymeleaf : HTML의 문법에 맞추어 태그를 작성(HTML 파일에 Java 코드 X), 동적인 데이터를 처리
Validation : 데이터 유효성 검사
Spring Security : 인증과 인가를 담당(보안)
OAuth2 : 다른 애플리케이션에서 사용자 데이터에 대한 제한된 액세스 권한을 부여하기 위한 프로토콜, 인증과 원한 부여를 담당
```
</details>

## 사이트맵
![gloomap_6b8307ed](https://user-images.githubusercontent.com/120995529/230279022-86b2a5a4-caa2-4259-90f9-dc9506ac43ca.png)
***

## ERD
![ERD](https://user-images.githubusercontent.com/120995529/230278851-40454da6-0429-418b-a682-198c07c92bea.png)
***

## 구현 이미지
### 메인 화면
- 해외 음원 차트 50개를 보여 줌
![image](https://user-images.githubusercontent.com/120995529/230283352-916d974b-8bd7-46d4-9dc3-83ddd537aa73.png)

- 앨범 이미지, 유튜브 이미지 눌렀을 때 유튜브 링크로 이동
![youtubebutton-1](https://user-images.githubusercontent.com/120995529/230284511-ee522bc3-144a-49ab-acf0-a92e92415fbf.png)
***

### 회원가입
- 중복확인 한개라도 수행 안할 시 등록이 안됨
![회원가입중복확인X](https://user-images.githubusercontent.com/120995529/230286925-78f61c08-d589-4ba3-aef9-e4c7a6e4fc83.png)

- 유효성 검사
![회원가입유효성검사](https://user-images.githubusercontent.com/120995529/230287011-79be95aa-6ce0-4e30-bb70-b4b3442b10f8.png)

- 회원가입 완료 시 자동 로그인
![회원가입후자동로그인1](https://user-images.githubusercontent.com/120995529/230287394-42d1ad03-acf2-40dd-88b2-886e993147ff.png)
***

### 프로필 
![프로필](https://user-images.githubusercontent.com/120995529/230287658-a474c314-aade-43b4-a54f-25b1adce236f.png)

- 내 정보 수정
![개인정보수정](https://user-images.githubusercontent.com/120995529/230287823-183caf22-a069-40d0-bd98-b2776e71bd0c.png)

  - 이메일 변경 시 중복확인 및 유효성 검사
  ![이메일변경](https://user-images.githubusercontent.com/120995529/230290211-f978c6d4-1bef-459a-a8c0-5e4f26c2026f.jpg)


  - 비밀번호 변경 시 유효성 검사
  ![비밀번호변경휴요성](https://user-images.githubusercontent.com/120995529/230287999-6a4df00d-eccf-4e8a-8602-640e2aafd713.png)
***

### 로그인
- 아이디 저장 및 자동 로그인 기능
  - 아이디 저장 : 로그인 시 아이디 자동 입력
- 카카오 로그인
![카카오로그인](https://user-images.githubusercontent.com/120995529/230291839-393ea344-22f5-48b9-bafa-98acf5e455e1.png)
***

### 아이디 / 비밀번호 찾기
- 비밀번호 찾기 수행 시 비밀번호는 임시 비밀번호로 변경
![아이디비밀번호찾기](https://user-images.githubusercontent.com/120995529/230292688-2bff2a72-ed7f-4a5b-a2ec-d51f2a49af61.jpg)
***

### 커뮤니티
- 로그인 여부
![커뮤니티로그인여부](https://user-images.githubusercontent.com/120995529/230293673-de7e9b26-45b4-4430-b69c-7160262494da.jpg)

- 게시글 및 댓글 
![커뮤니티](https://user-images.githubusercontent.com/120995529/230296940-9c449c10-8336-4728-a790-c3a0a280dbf5.jpg)
***

### 관리자
- 회원관리
![회원 관리 - 관리자](https://user-images.githubusercontent.com/120995529/230303135-51701790-0ca4-4318-a178-1f30f0c385d0.png)

- 닉네임 변경 및 회원 삭제
![관리자](https://user-images.githubusercontent.com/120995529/230302072-94051e3b-d8c1-4725-a58b-7212e62b8d7f.jpg)

- 권한 관리
![회원 권한 관리 - 관리자](https://user-images.githubusercontent.com/120995529/230303344-ae97d43b-f4f0-44ec-8336-ff0eb4b082ad.png)

- 게시물 관리
![게시글 보기+댓글 - 관리자](https://user-images.githubusercontent.com/120995529/230303254-7edf9e50-f3a1-43ac-aec9-f2c40f323240.png)
***

## 주요 기능
### 홈페이지
- 해외음원차트
  - 순위, 앨범 이미지, 제목, 가수명
  - 앨범 이미지 및 유튜브 클릭시 유튜브 링크 이동
- 로그인 세션

### 회원가입
- 아이디, 닉네임, 이메일 중복 확인
- 비밀번호 이메일 유효성 검사

### 로그인
- 소셜 로그인(카카오)

### 아이디/비밀번호 찾기
- 임시 비밀번호 발급(알림창)

### 커뮤니티
- 게시판 읽기, 쓰기, 수정, 삭제, 페이징
- 댓글, 대댓글 

### 개인정보 수정
- 자신의 회원 정보 조회 및 수정
  - 이메일, 비밀번호 변경 시 유효성 검사 및 중복 확인
  - 탈퇴

### 관리자
- 회원 관리
- 권한 관리
- 게시판 관리
- 차트 리셋
***
***