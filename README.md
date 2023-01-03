# Whipping_Project
<br/><br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210049100-93844be1-331c-4631-a734-28a5a2708a4e.jpg" width="200" height="200"></p>
<h4 align="center">상품 거래 쇼핑몰</h4>
<h1>WIPPING</h1>
'리액트'기반으로 제작된 실시간으로 변동되는 값을 처리하는 기능을 구현하여 UI로 출력하기 위한 쇼핑몰 프로젝트입니다.
<br/>

<h2>목차</h2>
1. 개발환경<br/>
2. 시스템 흐름도<br/>
3. ERD<br/>
4. 프로젝트 화면구성 및 기능 설명<br/>
5. 참고 주소<br/>

<h2>개발환경</h2>
* OS
   * Window 10
* DevTools
   * HeidiSQL
* Language
   * React
* Frontend
   * HTML5, CSS3, Javascript, Jquery, Bootstrap5
* Backend
   * Mybatis, Iamport(결제모듈)<br/><br/>
   
<h2>시스템 흐름도</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210190282-8fba3927-2aad-4419-9520-85b5ddab7818.png" width="800" height="500"></p>
<h2>ERD</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210190252-e4c6a342-7d61-4e26-8373-b6c2d4807843.png" width="800" height="500"></p>
<h2>프로젝트 화면구성 및 기능 설명</h2>

▶ __메인__ <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210190519-174d6fdc-0ae7-47d4-99de-14a408cd68e6.png" width="900" height="800"></p>
- 추천 컬럼 생성하여 메인페이지에서 종류별로 보여줌<br/><br/>

▶ __로그인 / 회원가입__ <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210191949-6614dfa2-6e40-40d1-a6c2-09ac6be4ea9a.png" width="900" height="500"></p>

▶ __카테고리 및 제품 상세페이지__ <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210191984-1d391de8-da4a-4046-b3c7-ca917ddcb6fd.png" width="700" height="500"></p>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210192106-2d5405ba-d320-4754-a43e-3d13d3d5c590.png" width="300" height="300"></p>
- 카테고리별 제품 분류<br/><br/>

▶ __제품 구매__ <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210192164-3136e770-553c-4730-8224-ae3cffe51232.png" width="700" height="500"></p>
- DB테이블에 재고현황 체크하여 구매 가능<br/><br/>

▶ __제품 판매__ <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/97080437/210192214-df469a47-f9f9-48e9-8259-ca66ad353099.png" width="700" height="500"></p>
<div>
   <img src="https://user-images.githubusercontent.com/97080437/210192241-fb764394-fe96-40bd-a3e2-1dc5ef2c8d0d.png" width="500" height="400">
   <img src="https://user-images.githubusercontent.com/97080437/210192260-f423f26e-34ad-4008-9220-3226555f3030.png" width="500" height="400">
</div>
<div>
   <img src="https://user-images.githubusercontent.com/97080437/210192270-f788aee5-9940-46be-8ca8-f556bf49afa8.png" width="500" height="400">
   <img src="https://user-images.githubusercontent.com/97080437/210192291-3199efe1-85ac-4832-8328-38abb7273a80.png" width="500" height="400">
</div>
- 제품 판매시 원하는 금액을 입력하여 판매 가능<br/>
- 판매신청을 후 마이페이지에서 확인 가능<br/>
- 각 제품의 최저가가 화면에 출력되며, 다른 고객이 해당 제품을 최저가에 구매할 수 있음<br/><br/>

▶ __장바구니 / 결제__ <br/>
<img src="https://user-images.githubusercontent.com/97080437/210192377-7462e5fd-c78e-4f07-87de-106e51fded67.png" width="500" height="400">
<div>
   <img src="https://user-images.githubusercontent.com/97080437/210192389-4c1305d6-c35f-460b-a294-d7abc405cb99.png" width="500" height="400">
   <img src="https://user-images.githubusercontent.com/97080437/210192399-e6b9ec3a-f1c7-4645-8459-476aee45f8d7.png" width="500" height="400">
</div>
- 결제시 제품 상세페이지에서 1개씩 구매 가능 / 장바구니 여러상품 한꺼번에 구매 가능<br/>
- 카카오 API 사용<br/><br/>

<h2>참고 주소</h2>
깃허브 : https://github.com/rhj1216-hochan06/douzoneth3_2team_reactproject <br/>
깃허브 커밋메세지 : https://github.com/rhj1216-hochan06/douzoneth3_2team_reactproject/commits/main


   
