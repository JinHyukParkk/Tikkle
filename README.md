# 마인드 맵을 이용한 아이디어 확장 웹


로컬서버에서 테스트 하실 경우 테스트 데이터 및 데이터 베이스 생성을 위해 database/construct.php 를 먼저 실행시켜 데이터베이스 및 테스트 데이터를 넣고 시작해주셔야 합니다. 
데이터 베이스 기본 아이디 및 비밀번호는 root / 0000 로 지정되어 있으나 database/database.php 에서 설정하실수 있습니다.

실행 순서 요약 : database.php 에서 __construct에서 디비 설정 -> construct.php 실행해서 기본 db값 세팅 -> 접속

회원 가입시 필히 존재하는 이메일을 등록하셔서 인증을 받으셔야 가입이 가능합니다.

1. 해당 TIKKLE Web application 은 1440 x 900 해상도 화면에서 최적화되어있습니다.

2. 익스플로러 환경에서는 노드의 생성 및 움직임이 최적화되어있지 않아 깨질수 있습니다.
   크롬 환경에 최적화되어있습니다.

3. 참고 Open Source 
- MindMap * js-mindmap.js / raphael-min.js / sricpt.js 출처 : http://sunshinemisiu.com/ (기존 Code 는 단순 MindMap 을 보여주는 기능 밖에 없어서 필요에 따라 추가적으로 수정 및 추가 하였습니다.)
- Mail Authentication * mail test.php 출처 : http://redqueen-textcube.blogspot.kr/2011/07/php-class.html ( 거의 수정하지 않고 사용하였습니다. )


Amazon url : http://ec2-52-78-89-174.ap-northeast-2.compute.amazonaws.com

GitHub url : https://github.com/WEBTIKKLE/TIKKLE

감사합니다.
