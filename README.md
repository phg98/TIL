# TIL
Today I Learned...

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
