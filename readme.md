#  ✏️ JAVA 웹개발자 2인 팀 프로젝트 ✏️ 

## 📚 목차 📚

1. [📂 PPT](#-PPT-)
2. [📖 프로젝트 소개](#-테트리스게임-프로젝트-)
3. [🔧 개발 환경](#-개발-환경-)
4. [💡 개발 목적](#-개발-목적-)
5. [🙋‍♀️ Team_Member](#-Team_Member-)
6. [📋 개발 일지](#-개발-일지-)
7. [🔨 사용 기술](#-사용-기술-)
8. [📹 시연 영상](#-시연-영상-) 


## 📂 PPT 📂

<details><summary>PPT</summary>
      
![](https://velog.velcdn.com/images/ghdlrn/post/e11704f3-2000-4674-9384-59a63bf09b4d/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/5dd834a1-51cc-40a4-9765-da4e7cfca5d3/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/c29bf9e5-d046-4676-bfa6-0e4b984242fa/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/3a569962-8864-485b-9455-f6a974365abe/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/7de13836-bca4-48d5-a6dc-1f9e59403e37/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/e23b541a-471a-43e5-82f3-3110d567d121/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/d9093d87-6818-4a5a-ad61-b7131a3f4a3c/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/f18fe317-c289-4d41-821c-98b2d14e3f61/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/ad1eb660-c0c7-46c0-8d27-9cb2cb36572c/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/33759de3-00fa-49db-a50b-8a5ed6149ead/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/ef3ce459-d4de-4f06-9b68-d3dd87d4fd4f/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/e87c5738-e3d9-46e3-95eb-64e6abb76102/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/bdf1dcf8-1d83-44ef-8231-250fa43f42dd/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/2a9c8db5-dae1-4fdb-b25c-3718b44992f1/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/15173530-69e4-4b41-89f9-bd3ec26e3e9f/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/d85ce7d4-5651-4b56-bc27-5f03f806f9bc/image.png)
![](https://velog.velcdn.com/images/ghdlrn/post/172213f5-e29a-4ae6-979d-97a45bf55128/image.png)

</details>
      
## 📖 테트리스게임 프로젝트 📖
```프로젝트 소개
테트리스 게임을 웹에서 구현
```
## 🔧 개발 환경 🔧
```
언어 : Java(jdk 21.0.2), SpringBoot 3.2.3
프레임워크 : SpringBoot 3.2.3
타입 : Gradle-Groovy (Gradle 8.5)
종속성 : Spring Boot DevTools
		Lombok
		Spring Web
		Thymeleaf
		WebSocket
		JDBC API
		Spring Data JPA
		Spring Data JDBC
		Oracle Driver 11
IDE : 인텔리J
```

## 💡 개발 목적 💡
```
쇼핑몰, Todo리스트는 온갖 입문서적에서 예제 프로젝트로 쓰이거나 다른 국비지원이나 부트캠프 팀에서도 단골로 쓰이는 프로젝트이기에 다른 방향성을 찾아보는걸로 이야기를 진행

공공기관 API활용해서 서비스 홈페이지 제작과 간단한 게임류 제작의 의견이 나왔는데참신한 서비스홈페이지 vs 기술적인 게임류 제작의 구도에서 결국 다방면에 걸친 확장성과 가능성을 생각하여 테트리스 게임을 웹에서 개발.
```

## 🙋‍♀️ Team_Member 🙋‍♀️

#### [😆 이규민 👉 [GitHub](https://github.com/Jincheol-11)](https://github.com/ghdlrn)
<details><summary>제작 클래스</summary>
<details><summary>Java</summary>
	Block,
	IBlock,
	JBlock,
	LBlock,
	OBlock,
	TBlock,
	ZBlock,
	Board,
	GameController,
 	BlockState,
	BoardState,
	GhostBlockState,
	HoldBlockState,
	BlackFatory,
	BlockPool,
	GameService,
	MoveBlock,
	GameControllerWebSocket,
	GameWebSocket,
	WebConfig,
	WebSocketConfig
</details>
<details><summary>Html, css, js</summary>
	index.html
	KeyGuide.html
	GameGuide.html
	KeyGuide.css
	style.css
	main.js
	KeyGuide.js
</details>
</details>
#### [😆 권범준 👉 [GitHub](https://github.com/seokeunpark)](https://github.com/kwonbumjoon)
<details><summary>제작 클래스</summary>
<details><summary>Java</summary>
	LoginController,
 	SignupCOntroller,
  	firstpageController
	User,
	UserRepository,
	UserService
</details>
<details><summary>Html, css</summary>
	firstpage.html
	login.html
	signuppage.html
	index_style.css
	login.css
	signup.css
</details>
</details>

## 📋 개발 일지 📋
   
https://velog.io/@ghdlrn/%ED%85%8C%ED%8A%B8%EB%A6%AC%EC%8A%A4%EA%B2%8C%EC%9E%84-%EA%B0%9C%EB%B0%9C%EC%9D%BC%EC%A7%80-1%EC%9D%BC%EC%B0%A8



## 🔨 사용 기술 🔨
<div>
<img src="https://img.shields.io/badge/Html5-E34F26?style=flat-square&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/css3-1572B6?style=flat-square&logo=CSS3&logoColor=white">
<br>    
<img src="https://img.shields.io/badge/JAVA-C01818?style=flat-square&logo=coffeescript&logoColor=white" />
<img src="https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellijidea&logoColor=white" />
<br>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" />
<img src="https://img.shields.io/badge/Bootstrap-80247B?style=flat-square&logo=Bootstrap&logoColor=white" />
<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">

## 📹 시연 영상 📹



https://youtu.be/cTt5ZwCrwgg



</div>


