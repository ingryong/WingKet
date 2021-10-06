last update 2021.10.02 

# WingKet
- 당근마켓과 유사한 서비스
- Firebase의 각종 서비스를 사용하여 백엔드 / 호스팅 대체
- React나 vue가 아닌 일반 웹 페이지 개발
- node 아님

## 참고한 강좌
- 코딩애플의 Firebase 강좌를 참고

## 강좌 외 추가 사항

### navbar
- 부트스트랩을 사용한 nav바라는 것은 같으나 코드는 강좌와 다름
- 대부분의 페이지에서 매 번 보이는 nav 부분을 한 번에 수정하기 위해 분리하여 관리
- 검색바 추가(실제 검색기능까지 추가 예정)
- 로그인 / 로그아웃 버튼 자동 전환 추가

### home(index page)
- 카드 형식의 UI 채용
- 로그인이 아닐 시 최상단 글작성 버튼이 보이지 않도록 함

### upload(글쓰기)
- 현재까지는 유사함

### sign in / sign up
- 버튼 옆에 로그인 / 회원가입을 이동할 수 있도록 하여 토글로 화면의 display를 on/off

<hr/>

### firebase webHosting

#### firebase 로그인
```
firebase login
```

#### 개발용 서버 실행
```
firebase serve
```

#### firebase 배포하기
```
firebase deploy
```
