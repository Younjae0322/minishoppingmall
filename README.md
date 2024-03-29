## 🥗FlexshMall🥗
- **SpringBoot를 이용한 식품 온라인 쇼핑몰**

  ![FlexshMall](https://github.com/Younjae0322/minishoppingmall/blob/main/src/main/resources/static/assets/flexshmall2.png)

## 📒개발 목표
- SpringSecurity를 사용하여 보안과 관련된 로직 구현
- 카카오PAY api를 사용하여 잔액 충전 구현
- 카카오MAP api를 사용하여 주소 입력
- SpringDataJPA를 사용하여 C/R/U/D 구현

## 🌈개발 일정
- **2023.11.20 ~ 2023.12.15**

## 👩‍💻개발자
  ![develop](https://github.com/Younjae0322/minishoppingmall/blob/main/src/main/resources/static/assets/develop.PNG)

## 💎기술 스택
### FRONT-END
<div>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white">
</div>

### BACK-END
<div>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white">
  <img src="https://img.shields.io/badge/SpringSecurity-%236DB33F.svg?style=for-the-badge&logo=SpringSecurity&logoColor=white">
  <img src="https://img.shields.io/badge/SpringBoot-%236DB33F.svg?style=for-the-badge&logo=SpringBoot&logoColor=white">
  <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white">
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white">
  
</div>

### DATABASE
<div>
  <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white">
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
</div>

### SERVER
<div>
  <img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black">
</div>

### DEPLOY
<div>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white">
  <img src="https://img.shields.io/badge/cloudtype-007396?style=for-the-badge&logo=cloudtype&logoColor=white">
</div>

### IDE
<div>
  <img src="https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white">
  <img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">
</div>

### VCS
<div>
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/GitKraken-%238A4182?style=for-the-badge&logo=GitKraken&logoColor=white">
</div>

## 🎞프로젝트 전체 구현기능

### 1. 회원가입 및 로그인
  <details> <summary>회원가입 : 이메일 인증을 통한 회원가입</summary>
  </details>

  - 아이디 중복체크 기능 JavaScript사용 alert호출
  - 비밀번호 중복체크 기능 AJAX 사용 비동기 호출으로 화면에서 바로 처리
  - 실제 이메일로 인증번호 발송 후 인증
  - 카카오MAP API 사용으로 주소 입력 받기 가능
<div>
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/14398876-e44e-443f-9e71-5ac1ffce537c" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/c642387b-14f2-4a6c-84f0-2bbad7ba94f0" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/1675e501-0818-4ae6-bfd2-7c60abe3f3f9" width="30%" height="500">
  <p align="center"><strong>클릭시 고화질로 보실 수 있습니다.</p>
</div>

### 2. 상품등록  
  <details> <summary>상품등록 : 관리자 권한 확인 후 관리자만 등록 가능</summary>
  </details>

  - 관리자로 로그인 했을 경우에만 상품등록 조회가능
  - 상품 이미지 여러개 등록 가능
  - 상품 수정시 이미지 재등록 가능
  - 관리자는 등록,수정,삭제 가능 / 일반 사용자는 구매만 가능하도록 설정
  - 상품 등록 완료 시 나중에 등록한 상품이 처음으로 오도록 역순 정렬
<div>
  <img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/dbe9b38b-f03b-4e30-baec-3d36e01d76cf" width="40%" height="500">
  <img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/a3929699-cfba-451f-b2cb-d42ca1f1dd42" width="40%" height="500">
  <img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/7c4028c2-ef18-4a28-ad3f-584084a8d40a" width="40%" height="500">
  <img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/056f50f2-821e-43ae-a807-57ac5f7742a2" width="40%" height="500">
    <p align="center"><strong>클릭시 고화질로 보실 수 있습니다.</p>
</div>

### 3. 잔액충전,상품구매
   <details> <summary>잔액충전 : 카카오PAY API사용 테스트 충전 진행</summary>
  </details>

  - 물품을 구매하기 위한 잔액 충전 기능
  - 소셜로그인 사용자가 아니더라도 카카오페이 충전 가능
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/46030d80-309f-4eaa-8327-064f2119f08f" width="50%" height="500">


  <details> <summary>상품구매 : 구매자 권한 확인 후 구매 가능</summary>
  </details>

  - 상품 카트에 담기 기능 구현 / 재고수량보다 많이 담을 시 JavaScript사용 재고수량 안내 alert호출
  - 한번에 여러 상품 구매 가능, 현재 선택 구매는 불가능
  - 장바구니에서 배송지 정보 입력시 카카오 MAP API사용 주소 불러오기/ 및 회원가입시 기존 사용자의 주소 Script사용하여 가져오기 가능
  - 구매자 잔액 감소 및 관리자 잔액 증가 구현완료.
<div>
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/d40f9597-9302-4f2a-b0d4-5a4817cde6a1" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/11c2168b-9486-4326-9671-ff0444a39618" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/ec320c19-a9d1-4e8c-9b62-1eba4228b9c6" width="30%" height="500">
  <p align="center"><strong>클릭시 고화질로 보실 수 있습니다.</p>
</div>


### 4. 상품배송, 환불처리, 매출현황
<details> <summary>상품배송,환불처리 : 관리자의 권한으로 배송관리 가능</summary>
  </details>

  - 관리자 페이지에서 배송대기, 배송중, 배송완료, 상태 변경 가능
  - 고객 주문내역페이지에서 상품 상태 확인 가능
  - 고객 환불요청 기능 추가
  - 관리자의 승인 후 환불 처리 / 금액 변동 처리 완료.
  - 관리자 페이지 매출현황 Chart.js사용 관리가능.
<div>
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/cc5bb2cd-04d4-4ae4-8e73-17ab0063f0ec" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/8223021c-8aeb-4513-b946-9d541f180d73" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/71ae2cd4-0a60-4c30-8e43-e4eb3511e608" width="30%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/d3d07529-1a19-4335-96c1-680422b11f84" width="40%" height="500">
<img src="https://github.com/Younjae0322/minishoppingmall/assets/141123013/56a13a19-5e1b-4bf6-a3af-6b9a76114aa0" width="40%" height="500">
  <p align="center"><strong>클릭시 고화질로 보실 수 있습니다.</p>
</div>
  

## 협업툴(GitKraken)
- 깃크라켄을 사용하여 진행상황을 공유, 관리함

  ![GitKraken](https://github.com/Younjae0322/minishoppingmall/blob/main/src/main/resources/static/assets/gitkraken.PNG)
