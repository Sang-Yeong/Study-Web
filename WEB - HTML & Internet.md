
# [WEB1 - HTML & Internet]

## 코딩과 HTML

 |원인|결과|
 |-|-|
 |code|application|
 |source|program|
 |language|webpage|
 ||website|

- HTML(Hyper Text Markup Language)
	- 쉽다.
	- 중요하다.
	- public domain: 저작권 없음. 팀 버너스리가 이렇게 선언함.


## HTML 코딩 실습 환경 준비
- 에디터(메모장, 텍스트에디터..) + 웹페이지
- 아톰(도구): atom.io
- 필요한 편집기를 찾아낼 수 있는 능력: HTML Editor, best HTML Editor 2019 이렇게 쳐서 찾아봐
- < Ctrl > + < 알파벳 > + O: 파일 열기

## 기본 문법 - 태그(tag)
- 웹을 지배하는 가장 중요한 문법
- 볼드체
```html
 <strong></strong>
```
- 밑줄
```html
<u></u> 	// u: underline
```

## 혁명적인 변화
- W3C: 웹 만드는 곳
```html
<h1>W3C</h1>	html headings h1~h6
```


## 통계에 기반학 학습
- http://www.advancedwebranking.com/html

## 줄바꿈
- html new line tag
```html
<br> * n: 줄바꿈이라는 시각적 부분을 담당하기에 범위가 존재하지 않는다. 따라서 </br>이렇게 닫을 필요가 없다.
```
-  html paragraph tag
```html
<p></p>: 단락이 어디서부터 어디까지인지 표현해야 함.
```

## HTML이 중요한 이유: 검색엔진에 노출 O/X
- 일반인이 제목 작성하는 방법: 시각적으로만 제목처럼 보이게 만들어 놓음.
```html
<span style="font-size:24px">
	coding
</span>
```
- 지식인이 제목 작성하는 방법
```html
<h3>coding</h3>
```
- 접근성; accessibility

## 최후의 문법 속성과 img
- 태그의 심화된 문법: 속성(attribute)
- <img> 태그의 이름만으로는 정보가 부족함. --> 새로운 문법 출현 "속성!!"
- 어떤 이미지 인지 알려주는 속성 
```html
source <img src="원하는 이미지의 주소">
```
- 저작권 구애X 사이트	https://unsplash.com/

## 부모 자식과 목록
- 포함 관계에 의한 태그: 부모태그- 자식태그
- 리스트list 
```html
<li></li>
```
- li의 부모태그 ul
```html
<ul>
	<li></li>
</ul>
- <ul> --> <ol>: 자동으로 넘버링O	Unordered List <----->  Ordered List
```

## 문서의 구조와 슈퍼스타들
```html
<title>WEB - html</title>

- 이 웹페이지를 열때에는 utf-8로 열어야 해.	<meta charset="utf-8">
- <head>와 <body>로 묶어주기
- <!doctype html>
	
<html>
<head>,,,</head>
<body>,,,<body>
</html>
```

## HTML 태그의 제왕
- Hyper Text
```html
<a>	// anchor: 정보의 바다에 정박한다.
```
- 링크!!!(길, 본드, 실)
- 사용설명서 찾을 때		html specification
```html
<h1><a href="https://www.w3.org/TR/html51/">HTML</a></h1>
<a hypertext reference=",,,"></a>

<a href="https://www.w3.org/TR/html51/" 	// 사이트
taget="_blank" 				// 새 창으로 열기
title="html5 specification">		// 커서 올려놓으면 이게 어떤 사이트인지 부가설명O
HTML
</a>
```

## 웹사이트 완성
- 링크생성해둔거 atom에서 파일 복사를 통해 만들어 줌.
- 링크를 통해 해당 페이지로 이동.
	
## 원시웹

|Internet|VS|WEB|
|--|--|--|
|도시, 도로,운영체제|-|건물,자동차,프로그램하나|	   	 
		
- 두가지는 달라
- WEB의 고향은 어디인가? 스위스
- 스위스 제네바이 CERN --> LHC강입자 가속기(아주작은 입자를 보는 장치)
- 팀버너스리 Enquire
- http://info.cern.ch/

## 인터넷을 여는 열쇠: 서버와 클라이언트
- 인터넷이 동작하는 가장 기본적인 원리
- 최소 2대의 컴퓨터 필요

|web browser|<-----internet으로 연결----->|web server(info.cern.ch라는 주소)|
|--|--|--|
|info.cern.ch/index.html|-|index.html|
|정보 요청|-|정보 응답|
|클라이언트(고객)|-|서버(서비스를 제공하는 사람)|
  
 	
## 웹 호스팅
- 호스트(host): 인터넷이 연결되어있는 컴퓨터 한대한대
- hosting: 이런 컴퓨터를 빌려주는 것
	- web hosting: 컴퓨터의 사용 목적이 web일때
  	- static web hosting: html만을 제공할 때
- github
- new repository: 저장하는 공간, 저장소
- Initailaize this repository with a README- checking
- free static web hosting: 무료 서비스
	- https://www.bitballoon.com/
	- https://neocities.org/
	- Amazon S3
	- Google Cloud Storage
	- Azure Blob

## 웹 서버 소개
- 제품군: Apache, IIS
- how to install apache http server ______(os)

## 웹서버 운영: 윈도우 Apache깔기
- how to easy install apache on window
- bitnami wamp stack: window apache mySQL p2p

#### 윈도우에 웹서버 설치
#### 웹서버와 http
- http://127.0.0.1/index.html
- htdocs: hypertext documents
- 127.0.0.1: Internet Protocol Address --> IP주소, 각 컴퓨터의 웹 서버를 가리키는 특수한 주소
- index.html: 웹브라우저가 자기 컴퓨터에 설치되어 있는 웹서버에 접속을 해서 파일을 원한다고 말하는것임.
- C:\Bitnami\wampstack-7.3.10-0\apache2\htdocs
- 주소를 통한 웹페이지 접속 VS. 파일을 통한 웹페이지 접속
질적으로 완전히 다르다. 주소가 다름.

| http://___ |비교| file://___ |
|--|--|--|
|웹브라우저 --> 웹서버 요청|-|웹서버는 전혀 개입하지 않아|
|웹브라우저와 웹서버가 서로 통신하는 것|-|파일에 있는것을 직접 여는거고|

http: Hyper Text Transfer Protocol


#### 웹브라우저와 웹서버의 통신
- 두 대의 컴퓨터가 서로 정보를 주고 받는 과정을 볼것임
- web browser			web server
웹서버의 주소 필요함(IP주소)		
http://____
IPv4Address
- 웹브라우저에서 127.0.0.1을 주소창에 입력한다 == 자기 자신


- 아름답게 웹을 만들고 싶다면 CSS
web publisher, web designer
- 사용자와 상호작용하는 웹페이지 만들고 싶다면 JavaScript
web front end engineer, web interactive designer
- back end: JSP, PHP, Node.js


# 부록: 코드의 힘
1. 동영상 삽입
