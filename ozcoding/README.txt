윤지우 포트폴리오 — 편집 안내
================================

[폴더 구조]
index.html              본문. 글은 전부 여기서 수정합니다.
assets/img/             페이지에 들어가는 이미지 11장
assets/fonts/           Pretendard Variable 폰트

[여는 법]
index.html 을 더블클릭하면 브라우저에서 바로 열립니다.
폴더 전체를 그대로 유지해야 이미지와 폰트가 보입니다.


[글 수정하기]
index.html 을 메모장, VS Code, Sublime Text 등으로 엽니다.
<body> 아래쪽에 본문이 순서대로 들어 있고, 각 구역 앞에 주석이 있습니다.

  <!-- 1. 프로젝트 개요 -->
  <!-- 2. 문제 정의 -->
  <!-- 3. 전략 -->
  <!-- 4. 실행 -->
  <!-- 5. 성과 -->
  <!-- 6. 콘텐츠 자산 -->
  <!-- 7. 검증 -->
  <!-- 8. 앱 기획 -->
  <!-- 9. 사업화 -->
  <!-- 10. 회고 -->

꺾쇠(< >)로 감싼 부분은 건드리지 말고, 그 사이의 한글만 고치면 됩니다.
예) <h2>같은 포맷, 500배 차이</h2>
       -> <h2>새로 쓸 제목</h2>

수정 후 저장하고 브라우저에서 새로고침(F5)하면 반영됩니다.

아직 비어 있는 곳: 맨 아래 '연락' 구역의 이메일과 전화번호.


[이미지 교체하기]
assets/img/ 폴더에서 같은 파일명으로 덮어쓰면 자동으로 바뀝니다.
파일명을 바꾸고 싶다면 index.html 안의 경로도 함께 고쳐야 합니다.

  hero-background.jpg      맨 위 배경 (흐리게 깔림)
  reels-grid.jpg           릴스 콘텐츠 그리드
  insight-views.jpg        인사이트 - 조회수
  insight-retention.jpg    인사이트 - 시청 유지율
  insight-interactions.jpg 인사이트 - 상호작용
  ir-slide-b2c.jpg         IR 자료 중 계정 운영 슬라이드
  app-home.jpg             앱 홈 화면
  app-chat.jpg             앱 채팅 화면
  app-store.jpg            앱스토어 화면
  apply-screen.jpg         청년창업사관학교 접수 화면
  award.jpg                IR 우수상 상장

권장 가로 크기: 가로형 1100px, 세로형(스크린샷) 560px 안팎.
너무 큰 원본을 그대로 넣으면 페이지가 무거워집니다.


[색상 바꾸기]
index.html 위쪽 <style> 안의 :root 부분에서 한 번에 바뀝니다.

  --indigo   포인트 색 (제목 강조, 숫자 강조)
  --magenta  '훅이 없는 콘텐츠' 카드 상단선
  --paper    배경색
  --ink      본문 글자색


[폰트]
한글은 assets/fonts/Pretendard.woff2 를 사용합니다. 인터넷 없이도 나옵니다.
숫자에 쓰인 세리프 서체(Newsreader)는 구글 폰트에서 불러옵니다.
인터넷이 끊긴 환경에서는 Georgia 로 자동 대체됩니다.


[웹에 올리기]
이 폴더를 통째로 업로드하면 됩니다.
GitHub Pages, Netlify, Vercel 모두 폴더 그대로 올리면 동작합니다.
