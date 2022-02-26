# 학습 내용 정리

---
## 1. 통신 프로토콜 및 에디터

1. http, https : 웹페이지 경로/주소
2. vscode
  - plugin
    - increment selection
    - live server / live server QR
    - px to rem
    - simple alignment
    - material icon theme
  - setting
    - wheel 
    - tab
    - wrap
  - user snippets
    - html.json: https://snippet-generator.app/
3. git 명령어
  - git add 
  - git commit -m "간단한 메모"
  - git push 
  - git pull 
  - git status
4. md파일 사용방법
  - 확장자 : .md
  - 제목 , 내용, list, 구분선, 줄바꿈( `<br />` )
  ``` html
  <!doctype html>
  <html lang="ko-KR">
    <head>
      <meta charset="utf-8">
      <!-- <link> -->
      <title></title>
    </head>
    <body>
      <script></script>
    </body>
  </html>
  ```
---
## html코드

1. 경로 (상대경로, 절대경로)
  - 상대경로 : `./`, `../`
  - 절대경로 : `/`, `http://`, `https://`, `c:`
2. html 형식
  - inline ( inline, inline-block)
  - block
- class, id
- 요소
  - 제목: h1,h2,h3,h4,h5,h6
  - 내용: p, pre, address ...
  - 목록: ul, ol, dl , li, dt, dd
  - 이미지: img
  - 앵커: a
  - 테이블: table
  - form : form, fieldset,legend ,label,input ...
  - 그룹 : div, span
  - 강조 : strong, em, ins, del, mark
  - 기타 : i, b, u, small ....

--- 

## css
  - 선택자 : type, id, class, 자식, 자손, 속성, nth, 형제
  - 크기: width, height, min-width, max-width, ...
  - 단위: px, em, rem, %, vw, vh
  - background: color, image, repeat, posion ...
  - font: face, family, size, weight, style ...
  - overflow, display
  - position : static, fixed, relative, absolute ...
  - css: 변수
  - @media screen and (device-size){}
  - psuedocode
  - float, clear
  - margin, padding, border, outline, box-sizing

---

## js
  - 변수( var )
  - 형타입 ( 숫자, 문자, 객체, 함수, undefined, null )
  - 객체 :  {key:'value'}
  - 배열 :  [0, 2, 3, 5] - 첫번째를 0부터 인식
  - 함수 :  function(){ return X } 
    - 선언식 :  function Fn(){}
    - 표현식 : var Fn2 = function(){}
    - 즉시실행함수 : (function(){})()
  - 연산자 : +, -, *, / , %, +=, -=, *=, /=, --, ++
  - 비교연산: <, >, <=, >=, ||, &&, ===, !, !==
  - 삼항연사: (조건) ? 참실행 : 거짓실행; 
  - 문법 :  
    - 조건(단항) : if(){}else if(){}else if(){}else{}
    - 조건(다항) : switch(){ case: ... break; .. }
    - 반복 : for(최초; 조건비교; 증감){}

---

## [jQuery](https://oscarotero.com/jquery/)
  - jquery코드를 먼저 불러와서 사용
  - (function($){ 기능수행 })(jQuery);
  - 선택자: css선택자와 기본은 같다 단,  $() 내부에 선택자
  - find(), children(), next(), nextAll(), prev(), prevAll()
  - eq(), index()
  - parent(), parentsUntil()
  - siblings()
  - css(), wrap(), contents(), before(), after(), append(), prepend(), text(), html()

---

## figma
  - frame
  - component
  - autolayout
  - constains
  - style
  - layer, export

---
## 작업방법

1. 큰틀에서 부터 작업
  - figma, coding
  - css구분할때도, 주석/ 내용을 큰틀
  - 스타일(컬러, 서체)