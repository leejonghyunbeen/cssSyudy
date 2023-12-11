# CSS Style sheet
-----
## css 작성위치
* 내부스타일시트 <head><style>여기작성</style></head>`
* 외부스타일시트 style /파일명. css별도 생성 후 
    <link rel="stylesheet" href="./styles/파일명.css>`
    ----------
## font-family 글꼴걸정
* 선택자 {font-family:'대표글꼴','보조글꼴'}
* 모든 사용자에게 동일한 글꼴을 보여줄 수 있도록 웹 글꼴을 사용하는 것이 좋다! 
  fonts.google.com 추천!!
## font-size 글자크기
* 웹브라우저 평균 글자크기는 16px (100%)이다
* px은 절대크기 이므로 모바일 디바이스에 적합하지 않아 em 또는 rem 단위를 사용한다.(%가능)
* 선택자 {font -size :1.0em;}`
* 선택자 {font -size :1.0rem;}`
* 선택자 {font -size :100%;}`
* 글자크기값은 부모에 상속받게 하지 않고 적용 대상 자체한테 작성하는 것이 좋다!(이유: 부모하넽 줄 경우 우선순위에 가로 막혀서 적용안됨)
* ★★개발자도구(F12) 우선순위 CSS를 자주 확인해야 한다!!★★
-----
## color 글자색상
* 글자색상은 단순 테스트 용도로 사용할때는 영문으로 사용한다 ex)aqua,blue
* 실제 디자인 용도로 사용할 때는 rgba, #헥사코드 6자리,3자리를 사용한다
* 선택자{color:#ff0000}
* 선택자{color:rgba(255,0,0,0.8);}
-----
## line-height 행간
* 행간 값은1.0(100%) 또는 50px 방식으로 작성한다.
* 본문 12~18px 내용 글자 크기 기준1.3~1.7 값을 많이 사용한다.(평균1.5)
* 제목 글자의 경우 글자크기에 따라 행간값은 상대적으로 다르기 때문에 자주 체크하며 수정해야한다
------
# project_blog 23/12/08~
## title :한화 이글스
* index.html(main)
* clubteam.html(팀소개)
* player.html(선수소개)
* 모든 html은 서로 '뒤로/앞으로' 기능없이 이동할 수 있어야 한다!!
-----
## 공통영역  HTML,CSS
* 모든 html 공통으로 존재해야하는 HTML-> header,footer (메인내용변경) footer
* css 공통 영역 ->reset, common.css(header ,main ,footer)
* css 개별영역  -> index.html, palyer,club 등의 main영역 
-----






    <header>
        <img src="./images/1686559053812000F6h_bN89w.jpg" alt="">
        <h1>한화 이글스  </h1>
    </header>
    <main>
        <h2>한화이글스는 충청권을 연고로 1985년 한국 프로 야구(KBO)의 <br>
        제7구단으로 출범했습니다.</h2>
        <p>대전광역시 중구 부사동에 위치한 대전 한화생명 EAGLESPARK를 홈 구장으로 이용하고 있으며, 제2구장은 충청북도 청주시 서원구 사직동에 위치한 청주야구장입니다.<br>
            보다 많은 분들이 야구를 관람하며 행복을 느낄 수 있도록 한화이글스는 투혼을 담은 경기를 위해 최선을 다하고 있습니다.<br> 지속적인 강팀으로 발돋움 하고자 내부 육성 시스템을 정비, 중장기 계획을 바탕으로 한화이글스의 감독 및 코칭 스태프, 선수, 프런트 모두가 함께 노력하고 있습니다.<br>
            늘 응원해주시는 팬들의 성원과 기대에 부응할 수 있도록 역동적인 경기와 다양한 마케팅을 전개해 팬과 함께 비상하는 구단이 되겠습니다. </p>
        <h3>로고</h3>
        <div class="rogo">
            <img src="#" alt="로고1">
            <img src="#" alt="로고2">
            <img src="#" alt="로고3">
        </div>