# TIL
Today I Learned...

## 해볼것
  * [ ] heroku에 heartbeat올려보기
    * [ ] 죽지않게 5분마다 호출하기
  * [ ] PWA : hpminfo에 아이콘, 이름 넣기
  * [ ] landingPage 제대로 동작하기
  * [ ] amplify 써보기
  * [ ] p5pattern에 다운로드 넣기
  * [ ] p5pattern에 파라미터 입력받기
  * [ ] netlify 써보기
  * [ ] glitch에 heartbeat올려보기
  * [ ] 유튜브 스트리밍 이름정하기
  * [ ] 유튜브 스트리밍에 목소리 넣어보기
  * [ ] 유튜브 스트리밍에 웹캠 사용

* 2020/8/29 토
  * github과 heroku 연동. github에 커밋하면 heroku에 자동디플로이 (https://p5pattern.herokuapp.com)
   * heroku의 프로젝트의 deploy탭에서 간단히 설정 가능하다.
  * glitch에서 github으로 코드 보내기 
   * Tools->Import&Export->project선택
   
* 2020/8/28 금
  * leetcode rand10() with ran7() 2시간만에 성공 ㅠㅠ😂
  * glitch.com 재미있다. 
  
* 2020/8/27 :
  * PWA 구글 코드랩 : 팀정보 만들어보자
  * AWS Builder 세미나에서 Amplify 흥미있다. heroku와 비슷? 한번 해보자.
  
* 2020/8/26 :
  * leetcode merge sorted array : ListNode 핸들링 아직 익숙하지 않다. 첫 노드를 dummy로 만들면 처리가 편하다.
  
* 2020/8/25 :
  * leetcode minimum cost of ticket 실패. Dynamic Programming 공부 필요해...
  
* 2020/8/24 : 
  * Github actions의 환경변수 설정법
    * .github/workflow/nodejs.yml 파일에 하기 추가
      ```yml
      env:
        NODE_ENV: development
      ```
  * Wakatime 설치 : 코딩시간 자동기록
  * leetcode daily
    * 재귀함수,이진트리 처리 더 익숙해져야해...
* 2020/8/23 : express-rate-limit 사용, heroku에 p5.js 예제 배포 (https://p5pattern.herokuapp.com/)
  * leetcode daily 
    * split() : 스트링을 배열로 나눈다.
    * slice() : 스트링의 일부분을 자른다.
    * splice() : 리스트의 특정 부분을 교체한다.
* 2020/8/22 : LeetCode 풀기 시작, 유튜브 라이브 스트리밍 테스트해보기(OBS Studio 사용)
* 2020/8/21 : heroku 계정만들고 앱 배포해 보기 (https://pinghere.herokuapp.com/)
  * heroku login
  * heroku create app-name
    * heroku git:remote -a app-name
  * git push heroku master
  * heroku ps:scale web=1
  * heroku open
