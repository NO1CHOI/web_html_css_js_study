<h1>반응형 웹디자인&웹퍼블리셔 양성과정 버전기록</h1>
<p>ex)날짜-제목-요약</p>
<h2>23.02.13 시작 - HTML</h2>
<p>H1~H6 , P , br , inling, block</p>
<p>h1~h3은 검색키워드로 활용 가능하다. h4~h6 꼭 필요한 경우만 사용하거나 권장하지않음</p>
<p> block과 inline 태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</p>
<hr>
<h2>23.02.14 -html -문서 태그+내비게이션 개념</h2>
<p>&lt;strong&gt;&lt;em&gt;&lt;sub&gt;&lt;sup&gt;&lt;del&gt;&lt;blockquote&gt;&lt;q&gt;&lt;code&gt;&lt;address&gt;&lt;hr&gt;</p>
<p>gnb , lnb , snb , fnb ,  Breadcrumbs</p>
<blockquote cite="https://webty.tistory.com/85"> 유나쌤 블로그 참고= https://webty.tistory.com/85 </blockquote>
<hr>
<h2>23.02.15 - HTML - 순차/비순차,정의형 목록 비교</h2>
<p>ol,ul,li</p>
<h3><em>ol,ul 사용법</em></h3>
<p>OL 이란?</p>
<ol>
<li>ol은 순서가 있는 목록의 틀이다.</li>
<li>li의 <strong>부모는 ol,ul만</strong> 가능하다.</li>
</ol>
<p>UL 이란?</p>
<ul>
<li>ul,ol,li 순서있는 목록 없는 목록 구분 호가실히 해야한.</li>
<li>li의 <strong>형제 태그</strong>는 li만 올 수 있으니 나머지 태그는 그 자식,자손 태그에 삽입 해야한다.</li>
</ul>
<p><em>dl,dt,dd 사용법</em></p>
<dl>
<h2>&lt;dl&gt;&lt;h2&gt;단어·숙어&lt;h2&gt;&lt;dl&gt;</h2>
<dt>&lt;dt&gt;web>&lt;dt&gt;</dt>
<dd>&lt;dd&gt;1.<em>명사</em> (=spider's web)&lt;/dd&gt;</dd>
<dd>2.<em>명사</em> (복잡하게 연결된)=망[거미줄]</dd>
</dl>
<hr>
<div class="study">
  <h2>23.02.16-HTML-시맨틱태크.그릅태그</h2>
  <dl>
    <dt class=skip">Sementic 태그</dt>
    <dd>&lt;header&gt;</dd>
    <dd>&lt;nav&gt;</dd>
    <dd>&lt;aside&gt;</dd>
    <dd>&lt;section&gt;</dd>
    <dd>&lt;footer&gt;</dd>
    <dd>&lt;article&gt;</dd>
    <dd>&lt;figure&gt;</dd>
    <dd>&lt;details&gt;</dd>
    <dd>&lt;main&gt;</dd>
  </dl>
</div>
<hr>
                   <h2>23-02-17-HTML:img,video,a href,하이퍼링크</h2>
                   <p>절대경로란? / 상대경로란?</p>
                   <p>이미지,비디오 태그 넣기</p>
                   <hr>
                   <h2>23-02-18 ~ 23-02-19 복습</h2>
                   <p>0213~0217 배웠던거 복습</p>
                   <hr>
<h2>23-02-20-Html:Table</h2>
<table>
<thead>
<tr>
<th>구분</th>
<th>태그명</th>
<th>의미</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="3">block</td>
<td>&lt;tr&gt;</td>
<td>가로형 태그</td>
</tr>
<tr>
<td>&lt;td&gt;</td>
<td>내용(열)태그</td>
</tr>
<tr>
<td>&lt;th&gt;</td>
<td>제목(열)태그</td>
</tr>
</tbody>
</table>
<hr>
<h2>23-02-21-Html:form</h2>
<form action="#" method="get">
<fieldset>
<legend>form 퀴즈</legend>
<span> 1.다음 중 label for 와 연관된 input 속성은?</span><br>
<label><input type="radio" name="quiz" value="id">1.id</label><br>
<label><input type="radio" name="quiz" value="class">2.class</label><br>
<label><input type="radio" name="quiz" value="name">3.name</label><br>
<span>2.form에서 이 [ ] 를 넣으면 수정이 불가능하다 무엇인가?<br>
<label><input type="radio" name="quiz" value="readonly">1.readonly</label><br>
<label><input type="radio" name="quiz" value="autofocus">2.autofocus</label><br>
<label><input type="radio" name="quiz" value="maxlength">3.maxlength</label><br>
</fiedset>
</form>
<h2>23-02-22-Html:cloncoding</h2>
<div class="login">
                    <p><button type="submit">로그인</button></p>
                </div>
<hr>
<h2><23-02-23:Html /CSS</h2>
<p>reset css 코드</p><br>
<p>html,body,h1,h2,h3,h4,h5,h6,
p,ul,ol,li,blockquote,dl,dt,dd,address,video,
strong,em,del,s,sup,sub,code,q,code,img,a,
table,tr,th,td,thead,tbody,tfoot,
form,fieldset,legend,input,label,textarea,option,section,button,
header,main,footer,article,section,aside,nav,figure,figcaption,div,span<br>
    {<br>
    margin:0; padding:0; <br>
    font-size:1.0rem;<br>
    font-weight:normal;<br>
    font-style:normal;<br>
    line-height:1.0;<br>
    list-style:none;<br>
    }<br>
a {text-decoration: none; color: #000;}
table,tr,th,td {border-collapse:collapse;}
button {cursor:pointer; border:none; background:none;}</p>
<p>css 주석<br> 1.HTML태그 꾸미는 대상 확인 <br>2.위 태그가 가족관계에 속해있는지 확인</p>
<hr>
<h2>23-02-24:HTML/CSS</h2>
<p>폰트 크기<br>
font-size: 16px;<br>
font-size: 1rem;<br></p>

<p>행간<br>
line-height: 1.5;<br>
line-height: 150%;<br>
line-height: 150px;<br></p>

<p>자간<br>
letter-spacing: 0;<br>
letter-spacing: -0.5px;<br>
letter-spacing: -0.05em;<br></p>

<p>단어 사이 자간<br>
word-spacing: 0;<br>
word-spacing: 1px;</p><br>

<p>글자 사이 공백<br>
white-space: normal;<br>
white-space: nowrap;<br>
white-space: pre;<br>
white-space: pre-line;<br>
white-space: pre-wrap;</p><br>

<p>글자 굵기<br>
font-weight: 400;<br>
font-weight: 700;</p><br>

<p>대소문자 변환<br>
text-transform: lowercase;<br>
text-transform: uppercase;<br>
text-transform: capitalize;</p><br>

<p>글자 기울기<br>
font-style: italic;</p><br>

<p>밑줄, 취소선<br>
text-decoration: underline;<br>
text-decoration: line-through;</p><br>

<p>선 넣기<br>
border-top: 1px solid black;<br>
border-bottom: 1px solid black;<br>
border: 1px solid black;<br>
border-left: none;<br>
border-right: none;<br>
</p>
<hr>
<h2> 23-03-02</h2>
<p>clonecording - 웹접근성로그인</p>
<hr>
<h2>23-03-03:html / css 속성 선택자</h2>
<p>text-overflow:ellipsis;/* 외부처 말줄임..... <br>
    white-space:nowrap;/* 한줄처리 (개행X) <br>
    overflow:hidden;/* 정해진 크기안에서만보이기 <br> 
</p>
<p>
점을 선말고 면으로 만들어서 넣기 <br>
.notice ul li::before<br>
{
    content:'';display:inline-block; <br>
    width:4px; height: 4px;<br>
    background-color: gray;<br>
    position:absolute;<br>
    left:-5px; top:13px;<br>
    /* width:5px; height:5px;<br>
    content:'';<br>
    background-color: black; display:inline-block;<br>
    border-radius:50%;<br>
    position:relative;<br>
    right:3px; bottom:3px; */<br>
}<br>
</p>
<hr>
<h2>23-03-06 : HTML</h2>
<p>CSS / Position</p>
<p>position:sticky(필수) / left , right , top , bottom(보조)</p>
<p>position 중첩순서 속성 :  z-index</p>
<p>CSS3 : flex레이아웃( flexible box )기본과 활용</p>
<hr>
<h2>23-3-09:서울시청</h2>
<p>    transform:scale(1.1);<br>
    /* transfrom 속성은 기준점을 요소의 중심으로 인식한다. */<br>
    transition:all 0.3s;<br>
    /* css 수치값이 변화가 일어날때 애니메이션 적용 */<br>
    /* ex) 100-> 220 값변화 0 */<br>
    /* ex) row -> column 값변화 x */<br>
    /* position:absolute; left:50%; top:50%;<br>
    transform: translate(-50%, -50%); */<br>
}
/* width 속성의 경우 -> 왼쪽상단 기준점으로 인해 우측하단으로만 이미지가 확대된다. */</p>
<hr>
<h2>23-3-10:HTML</h2>
<p>CSS : Gradient 다양한 색상 적용(그라디언트)</p>
<hr>
<h2>23-3-13:Git</h2>
<p>반응형웹 미디어쿼리(media queries)</p>
<p>**깃(git)의 주요 개념 키워드 10가지** <br>
1. Respository(저장소) : 코드나 문서를 저장하는 프로젝트 저장공간<br>
2. local Respository(로컬 저장소) : 개발자의 컴퓨터에서 작업되는 프로젝트 저장공간<br>
3. Remote Respository(원격 저장소) : 클라우드 서비스(ex)GitHub)를 통해 인터넷 서버에 저장된 공간<br>
4. Commit(커밋) : 저장소에 변경된 내용 기록, 간단한 메시지와 함께 기록합니다.<br>
5. Branch(브랜치) : 여러 작업을 동시에 협업하며 수행할 때 사용하는 관리 개념<br>
6. Merge : 브랜치 작업 완료 시 기존 코드와 함치는 명령<br>
7. Pull : 원격 저장소에 변경사항을 로컬 저장소에 가져오는 명령<br>
8. Push : 로컬 저장소에 변경사항을 원격 저장소로 업로드하는 명령<br>
9. Pull Request : GitHub 호스팅을 통해 코드 수정을 요구하거나 토론하며 개선하는 개념\<br>
10. Fork : 다른 사용자의 저장소를 나의 계정으로 복제하는 것. (원본 저장소와 독립적 관리 가능)</p>

