<h1 align="center">🍲 밀슐랭(Mealchelin): 밀키트 쇼핑몰</h1>
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/logo.png">

<br>

## 📄 개요
KH정보교육원 팀 프로젝트로 진행한 밀키트 쇼핑몰입니다.

2017년 20억원 수준에 불과하던 밀키트 시장은 코로나19 특수를 누리며 2021년 2587억원 수준으로 급성장했습니다. 코로나 확산세가 누그러져도 급격한 외식 물가 상승으로 인해 밀키트 수요가 지속될 것으로 예상됩니다. 다양한 밀키트 제품이 등장하는 상황에 맞춰, 밀키트를 종류별로 비교하고 편리하게 구매할 수 있는 쇼핑몰을 프로젝트로 진행했습니다.

<br>

## 📅 기간
2022.04.18. ~ 2022.08.31.

<br>

## 🛠 개발환경
#### Front-End
<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"> 
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
</p>

#### Back-End
<p>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white">
</p>

#### Database
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white">

#### Server
<img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black">

<br>

## 📚 DB ERD
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/ERD.png">

<br>

## 🔍 주요 기능
### 1. 메인 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func1_main.png">

- 화면 상단에서 로그인 정보에 따라 비회원, 회원, 관리자를 구분하여 다른 메뉴를 제공합니다.
- 중앙의 이미지 슬라이더를 통해 대표 카테고리인 한식, 양식, 중식 등의 밀키트를 볼 수 있습니다.
- 하단에서 최신 밀키트 상품을 볼 수 있습니다.

<br>

### 2. 회원 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func2_member.png">

- 회원가입 시 Ajax를 통해 ID와 이메일 중복검사를 진행합니다.
- 회원가입이나 비밀번호 변경 시 Gmail API를 이용해 이메일 인증을 시행합니다.
- 마이페이지에서 개인 정보를 수정할 수 있습니다.

<br>

### 3. 상품 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func3_product_detail.png">

- 한식, 양식, 중식 등의 분류별로 상품을 볼 수 있습니다.
- 상세 페이지에는 상품 정보, 리뷰, 관련 상품 등이 있습니다.
- 원하는 수량을 입력 후 장바구니에 담을 수 있습니다.

<br>

### 4. 주문 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func4_cart.png">

- 장바구니에 담은 상품 목록과 수량이 나타납니다.
- 상품을 삭제하거나 수량을 변경할 수 있습니다.

<br>

### 5. 게시판 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func5_community.png">

- CRUD, 파일 첨부 기능을 구현한 게시판입니다.
- 제목, 작성자, 내용 등을 기준으로 검색이 가능합니다.

<br>

### 6. 관리자 페이지
<img src="https://github.com/jinseon22/Mealchelin/raw/main/src/main/webapp/resources/readme/func6_admin.png">

- 관리자 계정으로만 사용 가능한 페이지입니다.
- 회원, 상품, 주문, 게시판의 현재 상태를 확인할 수 있으며 CRUD가 가능합니다.

<br>

## ✏ 담당 파트
저는 팀원 1명과 함께 상품 파트를 담당했습니다.
- DB에 상품 등록 후 view로 전송
- SQL을 이용해 카테고리별 상품 정렬, 검색
- 관리자 페이지에서 상품 CRUD, 파일 첨부
