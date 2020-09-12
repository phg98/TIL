# TIL
Today I Learned...

## 해볼것
  
  * [ ] heroku에 커스텀 도메인 적용해보기
    * [ ] 적용은 되었는데 http만 되고 https는 안돼서 작동이 안된다. ㅠㅠ  
  * [x] landingPage 보안 처리 (사용자 데이터 밸리데이션, 암호화)
  * [ ] landingPage 예쁘게 만들기
  * [ ] amplify 써보기
  * [ ] p5pattern에 다운로드 넣기
  * [ ] p5pattern에 파라미터 입력받기
  * [ ] netlify 써보기
  * [ ] glitch에 heartbeat올려보기
  * [ ] 유튜브 스트리밍에 목소리 넣어보기
  * [ ] 유튜브 스트리밍에 웹캠 사용
  * 알고리즘 공부
    * [ ] 이진트리
    * [ ] 공약수
    
## TIL
* 2020/9/12 토
  * [x] landingPage 제대로 동작하기
  * shortid 적용 : uuid보다 작은 7~14글자의 id생성기  
  * [x] 유튜브 스트리밍 이름정하기 : 늅코더 라고 지어봤다.
  
* 2020/9/11 금
  * [x] codepen.io 써보기. form validation
  * leetCode 1개성공 2개실패. 이진트리 공부해야겠다.
  * OBS Studio에 크로마키 스크린 사용하여 필터입혀서 Skype

* 2020/9/10 목
  * form validation : https://www.youtube.com/watch?v=rsd4FNGTRBw
  
* 2020/9/8 화
  * heroku에 커스텀 도메인 적용해보기
    * 신용카드정보입력후 도메인이름 넣고, Route53에서 CNAME으로 등록하면 된다.
    * [ ] 적용은 되었는데 http만 되고 https는 안돼서 작동이 안된다. ㅠㅠ
    
* 2020/9/7 월
  * heroku 5분마다 호출하기 : 
    * 확인해보니 free 에서는 18시간밖에 안된다. 대신 hobby (7$/month)를 쓰라고 하네. ㅠㅠ😒
    * 핑날려주는 서비스 사용 Kaffeine(https://kaffeine.herokuapp.com/)
  * 몇가지 서비스 비교해보기
    * heroku : front, back 모두 지원. 즉 서버가 24시간 동작.근데 무료에서는 30분 안쓰면 꺼진다. 안 꺼지려면 7$/month
    * netlify : 정적호스팅만. 
    * vercel(now.sh) : 정적호스팅만.
    * glitch : 모두 지원. 5분 안쓰면 슬립된다.
  * leetcode 2개 품 : 자료형마다 크기구하는 함수가 다 다르다. array.length, set.size(), Oject.values(obj).length 
  
* 2020/9/6 일
  * 크로마키 : ChromaCam프로그램 깔아보았는데 너무 느리고 카메라 연결이 되다 안되다 하여 포기.
  
* 2020/9/5 토
  * heroku heartbeat 문제 해결 : DB에 접속IP제한걸려 있었음.
    * DB connect에 에러처리를 안해서 해결에 오래 걸렸다... 에러처리 꼭 하자.
    * MongoDB Atlas에 IP로만 리스트등록이 가능하다. heroku는 실행될때마다 ip달라지는데. 해결방법못찾아서 일단 모든 IP 접속가능 설정함. (0.0.0.0/0)
    * heroku 재부팅은
      ``` heroku ps:restart -a APP_NAME ```
    * heroku timezone설정 : 세팅에서 환경변수에 TZ, Asiz/Seoul 추가.
    * ~~**html과 js파일을 수정해서 업뎃했는데 js파일이 여전히 구버전이 사용되는 문제 아직 해결 못했다.**~~
      * 하루지나니까 그냥 되었음. 흐음..
      
* 2020/9/4 금
  * OBS Studio : 
    * 크로마키 필터 설정 : 비디오 카메라 소스 우클릭후 필터 선택, 크로마키 선택, 색상 결정 (Custome에서 픽커사용가능)
    * OBS출력을 Skype로 연결 : OBS에서 프러그인 다운받아서 설치, OBS '도구'메뉴에서 Virtual Cam 선택하여 'Start', Skype설정에서 입력을 'OBS Virtual Cam'선택.
    
* 2020/9/3 목
  * :heavy_check_mark:  PWA : hpminfo에 아이콘, 이름 넣기 😎
  * glitch.com에서 로컬PC로 git clone 및 수정후 push : 그냥은 안되고 glitch 터미널에서 하기 명령 입력해야함.
    ```
    git config receive.denyCurrentBranch updateInstead
    refresh
    ```
  * leetcode easy 2개 품. 유튜브 동영상 저장 : 해상도 조정함.

* 2020/9/1  화
  * 알고리즘 공부 : 그리디, 구현 : 유튜브 나동빈채널 https://www.youtube.com/c/dongbinna/videos
  
* 2020/8/31 월
  * Dynamic Programming 공부 : 유튜브 영상 참고 (https://www.youtube.com/watch?v=vRFXpqWDbRU)
  * leetcode 실패! Remove Node from BST : 이진트리 공부 필요해.
  
* 2020/8/29 토
  * github과 heroku 연동. github에 커밋하면 heroku에 자동디플로이 (https://p5pattern.herokuapp.com)
   * heroku의 프로젝트의 deploy탭에서 간단히 설정 가능하다.
  * glitch에서 github으로 코드 보내기 
   * Tools->Import&Export->project선택
   
* 2020/8/28 금
  * leetcode rand10() with ran7() 2시간만에 성공 ㅠㅠ😂
  * :heavy_check_mark: glitch.com 재미있다. 
  
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
