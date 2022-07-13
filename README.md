# startship_config
** 처리상황
- format [username],[time],[directory],[git_branch]에 대한 설정

*** format
- prompt의 기본 모양을 설정한다.
- module과 style로 출력형태을 결정할 수 있다. module자체적으로 format과 style을 가지고 있기 때문에 module만 기술해도 된다. ex) $모듈
*** module
- module은 변수와 format 그리고 style을 기지고 있다.
- module에서 중요한 변수는 disabled이다. disabled가 false여야만 화면에 출력된다.
