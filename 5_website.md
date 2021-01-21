# 웹 사이트 제작

## 특강 계획
- 웹 페이지 저작 및 웹 사이트 제작
- 난이도
    - 최대한 쉽게
    - 초보자 수준
- 주제 선정 사유
    - 웹 페이지 저작은 스마트IT과 교육 과정 이수를 위한 기본 토대
    - 기본기 교육만으로도 많은 성과를 거둘 수 있는 내용
    - 코딩의 기본 개념을 체험하기 적당한 분야
- 요청하는 수강 태도
    - 해결하고 싶은 문제를 가진 <u>당사자</u>라고 가정하는 공감력
    - 자신이 (강의 노트를 공유하고 싶어하는) 선생님이라고 가정
    - 코딩은 문제 해결을 위한 것이고,  
    여러분은 문제의 **당사자**이자 **해결사**를 자임해야 함
    - 공부를 위한 공부가 아니라, 문제 해결을 위한 공부  
        <img alt="공부를 위한 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7519.png" width="45%">
        <img alt="문제를 해결하는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7518.png" width="45%">
    - 코딩 공부와 친해지는 계기가 될 수업  
        <img alt="우리를 짓누르는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7520.png" width="45%">
        <img alt="친해지는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7522.png" width="45%">

## 기획
- 기획의 의미
    - 새로운 것을 만들려면, 사전에 준비와 계획이 필요함
    - 문제의 인식에서 출발  
    - 만들려고 하는 것을 상상해보고, 계획하는 과정  
      ![기획자](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7546.png)
- 지금부터 우리는 기획자!  
- 우리가 만들고 싶은 웹 화면  
  ![화면 기획](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7547.png)
    1. 화면 상단에 수업의 제목
    2. 화면 좌측에 수업의 목록(메뉴)
    3. 화면 우측에 선택한 내용(제목/동영상/본문)

## 코딩 (구경하기)
- 유용한 사이트
    - [github.com](https://github.com/)
    - [codepen.io](https://codepen.io//) 
    - [한글입숨](http://hangul.thefron.me/)
- 코딩과 실행
    - HTML 코드 입력과 렌더링의 차이
    - 코딩: 우리는 코드를 작성 
    - 실행: 컴퓨터는 코드를 실행
    - 코드는 원인, 화면은 결과
- 코드와 언어
    - 코드는 컴퓨터에게 지시하는 작업 명령서(지시서)
    - 원천 코드(source code)는 컴퓨터 언어로 사람이 작성함
    - 작성된 코드 덩어리를 애플리케이션, 앱, (응용) 프로그램, 정보 시스템 등으로 부름
    - 컴퓨터 언어도 사람의 언어처럼 매우 다양함
    - 유명한 컴퓨터 언어의 예: HTML, CSS, JavaScript, Python, Java, C, C++, PHP, SQL, ...  
    - [프로그래밍 언어 순위](https://untitledtblog.tistory.com/165)
    ![컴퓨터 언어](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7551.png)
- HTML
    - 우리 수업의 주제
    - 웹 문서를 만드는 컴퓨터 언어
    - 웹 문서의 내용을 정의하는 역할
    - 웹 문서의 모양은 CSS 언어로 작성
    - 웹 문서의 동작은 JavaScript로 작성
- HTML은 배우기 쉬움  
    - 쉽지만, 중요함  
      <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7552.png" width="45%">
      <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7553.png" width="45%">
    - 웹 문서를 작성하는 도구
    - 여러분이 맨 처음 배우는 컴퓨터 언어
- 공공재(public domain)
    - 무료로 쓸 수 있도록, 공개되어 있는
    - 세종대왕은 자신이 창제한 한글에 저작권을 설정하지 않았음  
    - 팀 버너스 리는 자신이 창제한 웹에 저작권을 설정하지 않았음
- 웹 세상에 첫 발을 들여놓은 여러분을 환영함    

## 코딩 준비
- 코드 편집을 위한 SW 종류
    - 윈도: 메모장, Atom
    - 맥: 텍스트 편집기
    - 리눅스: gedit, nano, vim  
    ![notepad](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7574.png)
- Atom 설치
    - 우리 수업에서는 [github.com](https://github.com/)에서 만든 Atom 편집기로 통일  
    - [https://atom.io/](https://atom.io/)에서 프로그램을 다운로드하고 설치  
      ![atom](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7575.png)
- Atom 실행 모습
    - 좌측은 프로젝트(폴더) 파일 목록
    - 우측은 선택한 파일의 편집 영역  
      ![아톰 실행 화면](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7576.png)
- 컴퓨터 화면 배치
    - 좌측: 웹 브라우저
    - 우측: Atom  
      ![화면 배치](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7578.png)
- 실습 폴더 생성  
    - 실습 파일을 저장할 (프로젝트) 폴더를 바탕화면에 WEB라는 이름으로 생성
    - Atom 좌측 화면에 WEB (프로젝트) 폴더가 표시되도록 지정  
      `메뉴 → File → Add project folder`  
      ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7583.png)
- 실습 파일 생성
    - Atom 좌측 화면에서,  
      WEB 폴더를 오른쪽 클릭해서 New File을 선택하고,  
      '1.html' 입력 후 엔터  
      ![Atom new file](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7584.png)
    - 방금 생성한 파일의 확장자는 html
        - MS 워드 파일의 확장자는 doc
        - PDF 파일의 확장자는 pdf
        - 웹 문서 파일의 확장자는 html
- 실습 파일 오픈
    - Atom에서 오픈하려면, Atom 왼쪽 화면에 보이는 `1.html` 파일을 클릭
    - 웹 브라우저에서 오픈하려면, 
        - 윈도우: Ctrl + O(알파벳)
        - 맥: Cmd + O(알파벳)  
      ![파일 열기](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7592.png)
    - 또는 윈도우 탐색기나 맥 파인더에서 `1.html` 파일을 더블클릭해도 웹 브라우저에서 오픈 가능함
- 실습 파일 편집
    - 편집 화면에 'hello web' 입력하고 저장(윈도우: Ctrl + S, 맥: Cmd + S)  
      ![atom에서 편집](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7588.png)
    - 웹 브라우저 새로고침  
      ![웹 브라우저 새로고침](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7590.png)
- 첫 웹 문서 제작을 축하!
    - 이제까지는 웹 문화의 **소비자**로 살아온 시간
    - 이제부터는 웹 문화의 **생산자**로 살아갈 시간
- 자주 묻는 질문
    - Atom 설치 실패: 다른 에디터를 써도 무방하고, 윈도우 메모장을 써도 가능함
    - Atom 자동 줄바꿈: 메뉴에서 `file -> settings -> editor -> Soft Wrap` 항목을 체크

## 기본 문법 - 태그
- 진짜 코딩 시작
    - 기획서 다시 보기  
    ![다시 기획서](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7594.jpeg)
    - "쪼개서 해결하기!" 작전으로, 붉은색 부분부터 작업
    - 문제와 해결의 당사자라는 감정 이입 신공을 발휘하면서
    - 상상력을 발휘해서, 나의 어떤 상황에 응용이 가능할까를 고민하면서 
- `html.html` 파일에 다음 내용을 입력/저장하고, 브라우저 새로고침  
    <p class="codepen" data-height="174" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="GRjYZPW" style="height: 174px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="start html.html">
    <span>See the Pen <a href="https://codepen.io/logistex/pen/GRjYZPW">
    start html.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
- 축하!
![0005720_coming-soon-page_550](https://user-images.githubusercontent.com/10287629/104704273-c6918c80-575b-11eb-9fca-8bff77df20c5.jpeg)

<p class="codepen" data-height="169" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="vYXzxjq" style="height: 169px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="emphasize.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/vYXzxjq">
      emphasize.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    

[![going home](https://user-images.githubusercontent.com/10287629/104793991-511fcd80-57e8-11eb-86c8-27356c8dd83d.png)](https://logistex.github.io/smart_IT/)
