# erica_samsunginput
한양대에리카학생용 삼성 교과목 자동입력기


#사용법
##다운로드 및 설치
git clone 또는 zip 파일로 다운 받습니다.

파이썬 3.7을 깝니다.

cmd에서 pip install xlrd

를 입력합니다. 끝

##사용법
포탈에서 죄다 긁어서 엑셀에 복붙하신후, 열만 예제파일처럼 짜릅니다.
input.py를 켜시고,
엑셀파일 주소 입력 (input.py와 엑셀파일이 같은 폴더면 파일 이름만 입력)
그리고 삼성 채용 홈페이지 교과목 입력란 가서 임의로,
아무거나 하나 입력 후에,
파이어폭스 기준으로,

메뉴 > 웹개발도구 > 검사기 > HTML 검색에 thead를 입력한 후, 두번째 나오는 것 클릭 후,
복사 > 외부 HTML 클릭해서 복사합니다.

그 후에 그걸 그대로 python 콘솔에 복붙하신 후 엔터 두번 땅땅 하시면,

html과 자바스크립트가 생성되는데,

html은 방금 그 thead라는 태그에 왼쪽 클릭하시고 붙이기 > 외부 HTML 하시구,

자바스크립트는 맨 위에 <body> 라고 되어있는 곳 클릭하신 후 붙이기 > 첫번째 자식으로 합니다.

그런 후에 버튼 누르면 자동으로 수정됩니다.

그리고 마지막으로 꼭 임의의 (그냥 아무거나 적으면됨)과목 하나 적으신후 추가하시고 저장,

저장후에 그 임의의과목은 선택하고 다시 저장하면 끝입니다.