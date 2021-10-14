# Frontend-study

## HTML

1. 강조 strong /strong or 헤드 태그 h1 /h1
2. 링크 태그 a href="..."
    - a href="" target="_blank" /a => 새 브라우저를 열어서 링크이동
    - a href="" title="" /a => 링크 위에 마우스를 올려놓으면 title에 있는 문구가 나옴
3. li /li => 리스트 태그, ul /ul => 목록 태그(그룹핑), ol /ol  => 순서가 있는 목록 태그
4. title ... /title 페이지 창의 이름,  meta charset="utf-8"  => 글자가 깨질시
5. (HEAD 태크=나머지 내용,  Body 태그=본문의 내용  )=> HTML
6. DOCTYPE = 문서 형식 선언 ex) !DOCTYPE HTML 
7. p 태그 (단락을 나누는 태그), br 태그 (줄바꿈)
8. img 태그 (img src="...") height = 높이, width = 넓이, alt = 이미지가 깨질시 문구 , title = 사진에 마우스 올릴시 설명
9. table 태그 (표)  table => tr(행) => tb(열) , border = 테두리 외곽선 <br>
thead = 테이블의 헤드, tbody = 테이블의 바디 , tb ==> th로 바꿀시 진한글로 써짐<br>
tfoot = 표 가장 아래쪽에 존재 <br>
rowspan => 여러개의 행을 병합, colspan => 여러개의 col을 병합 
10. form => 입력한 정보를 전송할 때 사용하는 방식<br>
    form action="..." => 어디로 전송할지를 입력 <br>
    input 태그 = 사용자의 정보를 입력받을 수 있는 태그<br>
    type = 입력받는 형식 ex) text , password <br>
    name = 입력받는 input 태그의 이름을 지정해줌.<br>
    value = 기본적으로 입력되어있는 값<br> 
    textarea = 여러줄을 입력받는 태그
    - cols = 가로
    - rows = 세로
    
    select 태그, option 태그 => option 태그 안에있는 항목을 선택할 수 있도록 해주는 태그 <br>
    radio 태그 => 선택할수 있는 태크, name이 같은 라디오 버튼은 한개만 선택가능 (중복 불가)<br>
    checkbox 태그 => 다중 선택 가능<br>
    button 태그 => html로만은 쓸 곳이 x, js로 이벤트를 만들어줘야함 <br>
    reset => 사용자가 입력한 정보를 없애줌<br>
    hidden => 서버로 전송은 하지만 UI가 필요없을 때 사용
    label => 이름표를 부여하기 위해서 사용, 레이블을 선택하면 해당 위치로 이동하게 됨<br>
    method => get 방식(url로 데이터를 전송), post 방식(데이터를 다른곳에 숨겨서 전송), 기본 베이스는 get방식<br>
    form태그를 이용시 post방식을 이용하는 것이 좋음. 서버 개발자와 개발인 경우 서버 개발자의 요청대로 전송<br>
    파일 업로드 => type=file, method="post" enctype="multipart/form-data"(파일업로드시 필수)

11. font  => size 크기, color 색상 등을 지정 =>지금은 사용하지 않음 (css로 대체)
12. meta 태그 => html 파일의 정보를 표시할 때 사용
13. 의미론적 태그 => article = 본문, header = 문서의 전체적인 정보, nav = 문서의 네비게이션 항목 정의 등

## CSS
HTML을 꾸며주는 디자인을 설정하는 문법<br>

1. 여러 스타일 적용시 우선 순서 style > id > class > tag    -> !important 를 적용시 가장 높은 우선순위
## Javascript
