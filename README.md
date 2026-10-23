# Claudia Games 웹사이트

GitHub Pages(`https://ardorsoller-code.github.io/`)로 공개되는 개발자 웹사이트. 공개 저장소라 비밀이나 개인 주소, 전화번호를 넣지 않는다.

- `index.html`: 스튜디오 첫 화면, 게임 목록
- `pixel-coloring/privacy/`: 픽셀 아트 컬러링북 개인정보처리방침(영어, 한국어). 이 파일이 문구의 원본이다(게임 저장소 `store/privacy-policy.md`는 이 자리를 가리키기만 한다)
- `app-ads.txt`: 애드몹 게시자 확인(도메인 맨 위에 있어야 한다)
- `style.css`, `fonts/`: 게임과 같은 흰 종이 틀, 고운돋움(OFL)을 사이트 안에 둔다(바깥 글꼴 서버를 부르지 않는다)
- 올리기 전: `node ../tools/secret-scan.js .`, 이름·주소·전화번호가 없는지 눈으로 다시 읽기 (studio/working.md '보안')
