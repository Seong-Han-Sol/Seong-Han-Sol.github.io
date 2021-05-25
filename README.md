#### 작업예정.
- 1달간(프론트엔드)은 주로 UI 계속진행(VS code개발환경) 하면서,
- 피곤할때, 자바|스프링(이클립스-egov전자정부프레임워크개발환경) 기본언어실습진행.
- 피곤할때, 오라클DB(SQL디벨러퍼개발환경) Ansi-SQL(표준SQL)기본언어실습진행CRUD.
- 2달째부터(백엔드), 주로 스프링으로 실습이 진행(납품용-이력서포트폴리오용).
- egov:자바기반 -> JDK(Java Delvelopment Kit 자바개발환경) 설치확인.
- JDK 실행 경로 추가.
- java -version(git--version)
- 자바 오라클바자는 8버전부터 돈을 내야 한다. 이슈때문에, 오픈JDK 회사에서는 변경.
- 그래서, 오라클자바 8~11버전 지우고, 오픈 JDK로 변경 후 이클립스를 사용할 예정.
- OPEN JDK 8버전
- 돔캣 :이클립스에서 웹프로그램 결과를 확인하는 라이브 서버입니다. (localhost:8080)
- 라이브서버(아파치) :VS code에서 HTML결과를 확인하는 라이브서버.(localhost:5500)
- JRE : Java Runtime Environment(자바실행환경) - 자바앱을 실행할때만 사용.
- JDK설치 : 개발하고, 실행할때.
- 점심후 웹프로젝트 1개(헬로월드) - 생성play후 지우고(버리고 나머지는 2달 후까지 계속 가지고 감)
- 스프링프로젝트 1개(헬로자바) -test 폴더에서 자바기초를 실습
- 자바에 익숙해진 후 위 스프링프로젝트를 이용해서
- VS code에서 만든 UI를 JSP로 변경 한 후 스프링웹프로젝트를 진행합니다.

#### 20210525(화) 작업예정.
- board_view.html 댓글 Admin
#### 20210524(월) 작업.
- 시간 형식(Type):data(년월일), dateTime(년월일시분초), TimeStampt(년월일시분초)
- 1970년 생일:타임스탬프가 1970년 1월1일 부터 현재까지의 초를 계산한 결과 값
- 1970년 1월1일부터 16억2천...초가 흐른 시간이 현재시간
- 부트스트랩용어 : grid(12칸 그리드 시스템) modal, xs, sm, md, la, bs=부트스트랩, fa폰트어썸
- 팝업창 : 모달창(modal-필수창:작업후 다음으로 이동 가능), 모달리스트(modalless-작업하고 상관없이 다른창으로 이동가능) 
- 폰트어썸(아이콘웹폰트) : 아이콘을 확대해도 깨지지 않는다.(백터방식의 아이콘)
- 포토샵 디자인으로 아이콘을 만들면 확대시 깨짐(비트맵이미지-스칼라방식의 아이콘)
- 부트스트랩 그리드(모눈종이) 레이아웃 : 화면을 12개의 컬럼으로 분리해서 크기를 반응형으로 만듭니다.
- row(가로줄), col(세로칸) col-md-12(화면 가로 크기를12개로 지정 -100% 조건은 md에서 100%)
- 반응형의 화면크기 : xs엑스트라스몰(~750px), sm스몰(750px~), md미디엄(970px~), lg라지(1170px~)
- col-6 (화면 가로크기를 6으로 지정 -50%) 
- board_view.html 댓글 UI디자인 (부트스트랩) 추가.
- 반응형 서브페이지를 (로그인, 회원가입, 마이페이지)
- 관리자단 AdminLTE적용. (회원가입CRUD, 게시판CRUD, 대시보드)
- 이클립스 헬로월드 실습 1. 다이나믹 웹 프로젝트 (jsp만드는 방식)만든 후 사용자단 UI실행만 하고 삭제.
- jsp(1세대 2000년-게시판) -> 서블렛(2세대 2005년 servelet 게시판) ->스트러츠(3세대 2010년대 프레임워크) ->스프링(4세대 2013년대 프레임워크)
- 스프링(MVC)웹프로젝트 만들예정. 헬로월드 1개 -2달간 이프로젝트로 진행됩니다.
- 위 스프링 프로젝트 자바 기초도 이것으로 실습할 예쩡. ->htmlUI만들것을 jsp변경작업 들어갑니다.

#### 20210521(금) 작업.
- 모바일 게시판페이지(CRUD) CSS 처리 : Create(Update) = board_write.html
- 글쓰기폼 (부트스트랩을 적용): 첨부파일부분, 내용입력부분 웹 에디터 추가.
- 부트스트랩(adminLTE) : 제이쿼리 기반의 UI템플릿 (프레임워크)
-AdminLTE : dist(디스트리뷰트 =배포),pages(더미데이터), plugins(서머노트 등등)
- 대시보드 파일샘플 : index.html,  index2.html, index3.
- board_write.html파일에 bootstrap코어 임포트 + 서머노트 플러그인 임포트
- board_view.html 파일에 UI디자인 (부트스트랩) 추가.
- 반응형 서브페이지들 (로그인, 회원가입, 마이페이지)
- 관리자단 AdminLTE적용. (회원관리CRUD, 게시판CRUD, 대시보드)
- 톰캣(jsp) vs 라이브(아파치 hrml해석)
- 자바소스(.java앱 파일, .jsp웹 파일) ->컴파일 -> class 파일 -> HTML번역(WAS 톰캣) -> 크롬(IE) 화면에 랜더링 결과
- localhost 도메인 - 127.0.0.1 아이피의 바인딩되는 도메인.
- 이클립스 헬로월드 실습. 1.다이나믹 웹프로젝트(jsp만드는 방식) 만든후 사용자단 UI실행만 하고 삭제.
- 백엔드 : 1. 이클립스(스프링-규모가 있는 프로젝트 개발) 2. 인텔리J(스프링부트-규모가 작은 프로젝트 개발)
- 2. 스프링 (MVC)웹프로젝트 만들예정. 헬로 스프링
- 위 스프링 프로젝트에서 자바 기초도 이클립스로 실습할 예정. >htmlUI만든것을 jsp변경작업 들어갑니다.

#### 20210520(목) 작업.
- 메인페이지 시간이 걸리는 부분(프런트엔드): 메뉴처리, 슬라이딩처리OK.
- 모바일 게시판페이지(CRUD) CSS 처리 : Read (list, view페이지)
- Read 리스트형식(다중Map) board_list.html 예: 회원목록
- Read 단일 Map형식, json형식,(key1:value1, key2:value2, key3:value3...):board_view.html(회원상세보기)
- 상세보기 페이지 댓글 디자인은 부트스트랩 디자인시(관리자단 작업시) 추가 할 예정.
- 카멜표기법(낙타등표기법 예, bbsListTbl), _표기법 예, bbs_title
- href(헤르프) : hypertext referance (웹문서참조)
- 정적 (static) 콘텐츠 : heml, css, js
- 동적 (dynamic) 콘텐츠 : jsp(java스프링), PHP, C#(.net), Nodejs(익스프레스)
- 오후에 자바(스프링) 개발환경 설치예정. (이클립스:전자정부표준프레임워크의 개발환경을 설치)
데이터 (변수) 바인딩 : 정적인 콘텐츠에 동적인 데이터를 넣어주는 것을 바인딩이라고 함. (묶어주는 역할)
전자정부표준프레임워크를 제작한 업체 : 삼성SDS, SK C&C, LG CNS 3개가 협업으로 제작
게시물 타이틀 넘치는 부분 CSS처리했음. 스프링가서는 jsp에서 프로그램으로 처리할 예정.
- 모바일 서브페이지 CSS 스타일처리
- 테블릿+PC용 CSS 스타일처리
- 테블릿+PC용 CSS 스타일처리
- 모바일+테블릿+PC 댓글시스템 CSS+제이쿼리+부트스트랩 처리
- AdminLTE(부트스트랩기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
- UI디자인 끝 -------------------------------------------
- UI구현 시작 ------------- 스프링프로젝트 시작(이클립스+자바+오라클+스프링)
- UI구현 ......위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210518(화) 작업.
- 메인페이지 테블릿 메인 CSS 스타일처리, PC용 메인 CSS 스타일처리(반응형으로 제작)
- 반응형 페이지의 핵심기술은 미디어쿼리 명령어 사용 + 가로크기를 % 로 지정(px고정크기가 아닌 비율로 내부 컨텐츠 크기를 지정하는 방법)
- 미디어(PC화면,스마트폰화면,프린터,태블릿화면) + 쿼리(질의어-질문)
- @media 미디어타입(screen, print 등등=all) and (min-width: 801px) {스타일 구현내용}
- 태블릿은 마우스 오버 기능을 넣을 필요가 없습니다.(손가락으로 선택을 하기때문에...)
- 배치1: jQuery코어 임포트 이후 에 사용자가 지정한 js 배치를 해야함.
- 배치2: reset.css, mobile.css 임포트 이후에 사용자가 지정한 tablet.css, pc.css 배치해야 레이아웃이 깨지지 않습니다.

#### 20210517(월) 작업
- jQuery 제이쿼리 JSON 데이터 파싱
- 외부 data.js 파일에서 json데이를 저장한 후 html에서 불러와서 파싱.
- 외부 사이트에서 제공하는(RestAPI서버) json데이터를 html에서 불러와 파싱.
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
- ReatAPI서버주소(빅데이터): https://coroname.me/getdata
- 수업시작전, jsonData 파싱부분에서 append 사용에 2번 반복되는 부분 확인OK.

- 메인페이지에 자바스크립트(jQuery)적용.(VS code+HTML5+CSS+jQuery)
- 제이쿼리적용부분: 메뉴OK, 슬라이드이미지3개 처리 : 모바일 메인페이지만 마무리
- 보통 이미지 슬라이드 처리는 외부 라이브러리(Lib) 사용(니보슬라이드, 캐러셀슬라이드)
- 외부Lib 사용않하고, 우리가 만들어 봅니다.OK.
- 슬라이드2 이미지 :https://pixabay.com/ko/photos/%EA%B3%A0%EC%96%91%EC%9D%B4-%EA%B2%80%EC%9D%80-%EA%B3%A0%EC%96%91%EC%9D%B4-%EC%95%A0%EC%99%84-%EB%8F%99%EB%AC%BC-4541889/
- 슬라이드3 이미지 : https://pixabay.com/ko/photos/%EA%B3%A0%EC%96%91%EC%9D%B4-%EC%83%88%EB%81%BC-%EA%B3%A0%EC%96%91%EC%9D%B4-%ED%8A%B8%EB%A6%AC-1647775/

#### 20210514(금) 작업
- 구문오류: syntex 신텍스(사인텍스)오류(문법오류)
- CSS3, HTML5 : 유효성 검사기준입니다.
- 사용자단 모바일 메인페이지 footer영역 CSS 입히기.
- top상단이동 OK.
- 과제물 제출 준비OK.
- jQuery Json 데이터 파싱 실습
- 8교시에 과제물 다음카페로 제출

#### 20210513(목) 작업내역
- 픽사베이 이미지 3개: 로고1, 슬라이드 이미지1, NoImage 1 받고, 경로 적어놓기
- 로그 이미지 경로 : https://pixabay.com/images/id-6029680/
- 슬라이드 이미지 : https://pixabay.com/ko/photos/%EC%83%88%EB%81%BC-%EA%B3%A0%EC%96%91%EC%9D%B4-%EB%8F%99%EB%AC%BC-%EA%B3%A0%EC%96%91%EC%9D%B4-3669244/
- no_img : https://pixabay.com/ko/vectors/%EB%B9%BC%EA%B8%B0-%EC%A0%9C%EA%B1%B0-%EC%82%AD%EC%A0%9C-%EC%B7%A8%EC%86%8C-38749/
- 작업폴더를 나누는 이유: 시청(관공서), 대학, 기업의 웹프로그램(사이트) 제작 할때, 1년간 무상 유지보수 이후 보통 2천, 리뉴얼 4천 비용이 책정
- home폴더 기존작업물, 리뉴얼 home에 덮어쓰는 방식이 아니고,
- 리뉴얼 할때 home2022 폴더에 작업을 하시게 됩니다.
- 제이쿼리 코어 다운받기: min버전(압축-속도UP), 일반버전(개발-속도Normal)
- jQuery 미처리 작업은 다음주하고, 
- 오늘부터는 모바일 메인페이지 1개 만들어서 과제물로 제출 -> 스프링에서 프로그램 입히는 소스로 사용하게 됩니다.
- 애니데스크(독일산): 팀뷰어(독일산) 사용하는 대신에 애니데스크를 사용.
- html5.html, css.html, js.html 여기까지
- jQuery 기본구조만 실습했습니다.

#### 20210512(수) 작업내역
- git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해 주셔야합니다.
- git config --list 확인에서 user.name, user.email 없으면 아래추가.
- 터미널에서 아래 2가지 실행
- git config --local user.name 영문이름
- git config --local user.email 영문이메일
- 프로젝트를 1명 제작하는 경우 없기때문에, 2명일때 소스수정한 사람 확인용 정보 입니다.

#### 20210511(화) 작업내역
- 로렘 입숨 한글URL: http://guny.kr/stuff/klorem/#/dl-html
- 로렘 입숨 영어URL: https://loremipsum.io/generator/
- URL경로(path): /루트, /test/html5.html
- html5의 레이아웃 구조 제작합니다.
- 서버(응답하는프로그램=response) = 아파치서버, 톰캣서버
- 클라이언트(요청하는프로그램=request) = 웹브라우저
- HTML은 마크업이 태그로 구성. <의미있는문자>...</의미있는문자>
- http://127.0.0.1:80[8080|9000|5500|6500]
- PC의 네트워크 내부주소(공통): 127.0.0.1 == localhost
- 고유주소: yahoo.com(도메인) == 74.6.143.25(IP주소) == 주민번호
- IP주소버전: IPv4, IPv6
- HTML도 버전: HTML5, HTML4.01(old)

#### 20210510(월) 작업내역
- 개발PC(html) 와 깃 저장소와 연결시킵니다. 초기에 연결시 아래와 같은 문제점이 나올 수 있습니다.
- 레포지토리(저장소) 초기화: git init 또는 VS code에서 레포지토리초기화 버튼 이후
- Git에서 'user.name' 및 'user.email'을 구성하라고 떠요!(해결책 아래 2줄)
- git config --local user.name 이름
- git config --local user.email 이메일
- 브랜치(branch)가 없다며 구성하라고 떠요!(해결책 아래 1줄)
- git branch -M master
- 리모트(remote)가 없다며 구성하라고 떠요!(해결책 아래1줄)
- git git remote add origin https://github.com/사용자저장소/사용자저장소.git
- 작업결과는 .git 폴더안의 config 파일에 저장됩니다.
- 이후 VS code 프로그램에서 아래 처럼 작업 하시면 됩니다.
- 업로드절차: 1. 커밋(commit) 2. 푸시(push)
- 다운로드절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 상황
- 주의) 다른 신규 PC에서 작업시 아래 명령어로 깃내용을 새로 가져옵니다.(아래)
- git clone https://github.com/학생저장소/학생저장소.github.io.git
- 안정된 이후 기존 사용자 폴더에서는 작업 시작전에
- git pull 로 어제 작업한 내용을 최신버전으로 업데이트 합니다.
- 포트의 역할이 트렌드로 많이 사용됩니다.
- 포트(port): 포트번호로 서비스를 만드는것이 트렌드
- 이전에는 80포트에 모든 서비스 묶어놓았습니다.
- 모든서비스를 개별로 분리하는 트렌드가 있습니다.: 마이크로서비스라고 합니다. == RestAPI로 구현이 됩니다.
- 도메인(예, https://naver.com:1451241/네이버 인증서비스 개발)
- 외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용
- html : Hyter Text MarkUp Language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어