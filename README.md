#### 20210510(월) 작업내역
- Git에서 -user.name 및 user.email 을 구성하라고 떠요!(해결책)
- git config --local user.name 이름
- git config --local user.email 이메일
- 업로드 절차 : 1. 커밋(commit) 2. 푸시(push)

- 다운로드 절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 때
- 레포지토리(저장소) 초기화 : git init
- 개발PC(html) 을 깃 저장소와 연결시킨다.
- 포트의 역할이 트렌드로 많이 사용된다
- 포트(port): 포트 번호로 서비스를 만드는것이 트렌드
- 이전에는 80포트에 모든 서비스를 묶어놓음
- 요즘은 모든 서비스를 개별로 분리하는 트렌드가 있다. : 마이크로 서비스라고 부름 == RestAPI로 구현이 된다
- 도메인(https://naver.com:1251241/네이버 인증서비스)
- 외부 인원(네이버직원X)이 위 포트기준으로 제작한 서비스를 가져다 사용
- html : Hyter Text Markup Language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어
#### 20210511(화) 작업내역
- http://127.0.0.1:80[8080/9000/5500/6500]
- 127.0.0.1 = PC의 네트워크 내부주소(공통) == localhost
- 고유주소 : yahoo.com(도메인) == 74.6.143.25(IP주소)
- 서버(응답하는 프로그램=response) = 아파치, 톰캣서버
- 클라이언트(요청하는 프로그램 = request) = 웹브라우저
- HTML은 마크업이 태그로 구성됩니다. <의미있는문자>... </의미있는문자> 
-  ex < h1 > < /h1 > (원래는 공백이 없지만 화면에 보이지 않아 띄어쓰기 넣음)
- IP주소버전 : IPv4, IPv6
- html도 버전이 있음 : HTML5, HTML4.01(old)
- 주석 단축키 Ctrl+/  한 번 더 누르면 주석취소
- html5의 레이아웃 구조 제작합니다
- URL경로(path):/루트, /test/html5.html
- 로렘 입숨 한글 URL :http://guny.kr/stuff/klorem/#/table-html
- 로렘 입숨 영어 URL :https://loremipsum.io/generator/?n=1&t=p
- submit= 전송(서밋)  / 데이터 한개 입력이 끝나면 반드시 ;으로 마무리
#### 20210512(수) 작업내역
-git colne으로 작업물 복사한 경우 concinfig --list 확인에서 유저네임, 이메일 없으면 아래에 추가하기
- git config --local user.name 이름
- git config --local user.email 이메일
프로젝트를 1명이서 제작하는 경우는 없기 때문에, 2명일때 소스 수정한 사람 확인용 정보입니다.
#### 20210513(목) 작업내역
- 픽사베이 이미지 3개: 로고1, 슬라이드 이미지1, NoImage1 받고, 경로 적어놓기
- 로그 이미지 경로 : https://pixabay.com/images/id-6029680/
- 슬라이드 이미지 : https://pixabay.com/ko/photos/%EC%83%88%EB%81%BC-%EA%B3%A0%EC%96%91%EC%9D%B4-%EB%8F%99%EB%AC%BC-%EA%B3%A0%EC%96%91%EC%9D%B4-3669244/
- no_img : https://pixabay.com/ko/vectors/%EB%B9%BC%EA%B8%B0-%EC%A0%9C%EA%B1%B0-%EC%82%AD%EC%A0%9C-%EC%B7%A8%EC%86%8C-38749/
- 작업폴더를 나누는 이유 : 시청(관공서), 대학, 기업의 웹프로그램(or사이트)를 제작할 때, 1년간 무상 유지보수 이후 2천, 리뉴얼 4천 비용이 책정
- home폴더에 기존작업물, 리뉴얼 작업물은 home에 덮어쓰는 방식이 아님
- 리뉴얼 할때 home2022(년도) 폴더에 작업을 하게 된다.
- jQuery 미처리 작업은 다음주에 하고
- 오늘부터는 모바일 메인페이지 1개 만들어서 과제물로 제출 -> 스프링에서 프로그램 입히는 소스로 사용
- 애니데스크(독일산) :팀뷰어(독일산) 사용하는 대신에 애니데스크를 사용.
- html5.html, css.html, js.html 여기까지 jQuery 기본 구조만 실습했습니다.
- 제이쿼리 코어 다운받기 : min버전(압축-속도UP), 일반버전(개발-속도Noraml)
#### 작업예정 : jQuery 제이쿼리 JSON데이터 파싱
- 외부 date.js 파일에서 json데이터를 저장한 후 html에 불러와서 파싱
- 외부 사이트에서 제공하는 (RestAPI 서버) json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
- ReatAPI서버주소(빅데이터) :  https://coroname.me/getdata