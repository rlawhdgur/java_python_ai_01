# 🎵 Last Carnival
- [배포 링크]() - 작업 중
- 👉 [발표영상링크]() - 작업 중
- 👉 [데모영상링크]() - 작업 중
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
- 사용언어 : Java, JavaScript, HTML, CSS, jQuery(ajax)
- Framework : MyBatis, Spring Security, OAuth2, Spring Boot(v.2.7.9)
- DB : MySQL, MongoDB
- 작업툴 : VS code, Eclipse
- 협업Tool : Github, Slack, Trello
- 인원 : 4명
- 주요 업무 : Spring Boot 프레임 워크를 이용한 웹 개발 구현 코드 작성
  - 로그인 및 회원가입, 이메일, 비밀번호 변경, 아이디/비밀번호 찾기. 유효성 검사.
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