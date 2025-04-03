# day2 HTMl
* HTML 작성 시 항상 태그 구조 먼저 생각하기
*HTML 작성하면서 유효성 검사 자주 이용하기 (반드시 저장 후)
https://validator.w3.org/#validate_by_upload
### 유효성 검사 오류잡기 TIP
* 유효성 검사기 전채 오류 개수를 보지말고 가장 윗 줄 에러부터 확인 후 고치기
* 고친후 vs code에서 바로 파일 저장 후 다시 유효성 검사하면서 에러잡기
## HTML TREE
* HTML 작성 시 줄바꿈, 들였기를 주의하며 태그를 작성한다.
*관계구조는 부모-자식-자손-형제로 구분된다.
*형제관계는 첬재 자식과 마지막 자식으로도 따로 구분한다.
*형제가 없을시 외동으로 구분한다.
## hTML title 웹접근상
* 사용자가 웹브라우저를 여러 탭으론 하고 봤을때 페이지 구분을 쉽게 할 수 잇는가?
* 페이지명 | 사이트명
* 페이지명에 들거나느 후보 : 상품명, 페이지 경로, 상품 관련 부가정보 등등...
* 사이트명에는 광고문구가 같이 들어갈수있다.: 빠져든다 CGV
* 잘못 예) 네이버 블로그, 네이버 카페
* 잘된 예) 책제목|저자| 출판사 | 교보문구, 쇼핑몰 상품| 쿠팡..
## inline or block
* 태그 사용시 그 태그가 인라인인지 블록인지 먼저 확인하고 사용하기!
* 블록-블록-블록 0
* -인라인-인라인 0
* 블록(인라인) 0
* 인라인(블록) X
* 블록(블록) 0
* 인라인(인라인) 0
## h태그 (heading)
* 제목 태그 h태그는 1~6레벨을 가진다. 1이 가장 중요하다
* 메인페이지, 서브페이지에 따라서 h1이 어디들어가는지부터 확인하고 나머지레벨을 순차적으로 결정한다. 1->2->3->...
* 대표적으로 사이드 로고(h1)와 서브페이지의 페이지제목(h1)이 주로 사용된다.
* 제목은 사용자가 사이트에접속하기 위한 검색키워드 목적도 되므로 신중하게 결정한다.
## 태그 작성 시 주의 사항
* 부모 요소의 기능 밒 디자인은 자식,자손까지 전달된다.
* H태그와 P태그를 사용 시 H태그 안에 P태그를 작성하면 H태그의 '제목'이란 의미가 전달되기 때문에 P는 반드시 H밖에 형제위치로 작성해야 한다.
* br태그는 인라인태그로 블록 태그 안에만 작성할 수 있다.
* 'br태그'는 강제 줄바꿈으로 모바일~태블릿`pc까지 반응하는 반응형웹에 적합하지 않기 때문에 사용 시에는 글자 수가 적은 제목이나 내용 위주로 꼭 필요한 경우에만 사용한다.