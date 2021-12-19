## sunwoo_first
첫 커밋한 스프링 MVC PROJECT
![화면 캡처 2021-12-20 043346](https://user-images.githubusercontent.com/66655878/146688351-0131cdba-1ecb-460e-9f55-13163f0749b0.png)



### MVC 패턴이란
![화면 캡처 2021-12-20 055003](https://user-images.githubusercontent.com/66655878/146690358-42c1760a-57e6-4ef9-88b6-2be29403de4d.png)

M = Model -> 데이터베이스에 데이터를 가져오거나 변경 또는 저장하는 부분
V = View -> 사용자에게 보여지는 부분
C = Controller -> 사용자 요청에 따른 Model, view를 유기적으로 연결하는 부분
-> 앱 개발을 3가지 역할로 구분한 것
-> 이를 통해 서로 분리되어 각자의 역할에 집중할 수 있게끔하여 개발을 할 수 있다. -> 유지보수용이

- 각자의 역할 
Model에서는 처음에 정의하는 상수, 초기화값, 변수 등을 뜻하며 DATA 정보들의 가공을 책임지는 컴포넌트를 말한다. (데이터베이스)
View에서는 클라이언트 측 기술인 html/css/javascript들을 모아둔 컨테이너로 프론트엔트 부분을 담당한다.
Controller에서는 사용자가 접근한 URL에 따라 요청사항을 파악한 후, 그 요청에 맞는 데이터를 Model에 의뢰 및 View에 반영해서 사용자에게 알려주는 것을 담당한다.
*여기서 든 나의 생각 -> Model은 백엔드, View는 클라이언트, 이둘을 이어주는 Controller 로 정리되는 것 같다.


#### MVC 패턴을 사용하는 이유
- 이번에 공부하면서 알게 되었다. 매우 중요한 부분인 것 같다.
- MVC패턴은 디자인패턴 중 하나이다. 
*디자인 패턴이란 프로그램이나 어떤 특정한 것을 개발하는 중에 발생했던 문제점들을 정리해서 상황에 따라 간편하게 적용해서 쓸 수 있는 것을 정리하여 특정한 "규약"을 통해 쉽게 쓸 수 있는 형태로 만든 것을 말한다.
- 소수의 뛰어난 엔지니어가 해결한 문제를 다수의 엔지니어들이 처리 할 수 있도록 한 규칙이다. 구현자들 간의 커뮤니케이션의 효율성을 높이는 기법이다.
- MVC패턴은 결국 "어떻게 나눌 것인가"에 대한 솔루션을 제시해준다. 어떤 특정한 역할들에 대해 역할분담을 할 때 가이드라인을 제시하는 방법 중 하나가 바로 MVC패턴. 



#### 프로젝트 목적
- 이클립스에 스프링 프레임워크를 깔아서 MVC 패턴을 공부해서 git에 올리는 실습을 수행해보았습니다.
- 깃허브 사용과 프레임워크 개념 등을 알기위해 시작하였습니다 (감사한 선배님 덕분에 시작!!)


#### 어려웠던 점 
#### 정말 많았습니다.... 
- 우선 스프링을 이클립스에 설치하는 과정까지는 괜찮았습니다
- 그이후에 간단한 MVC PROJECT를 만들었는데 그 과정에서 많은 어려움이 있었습니다. 
- 경로설정, 자바 버전알기, 이로부터 파생되는 톰킷 버전들 알기, 무턱대고 next를 넘기면서 놓쳤던 부분으로 일어나는 오류들.... 
- 매우 막막했었습니다. 뭐가 문제지, 왜 이런 오류가 나타나는지 구글링을 해보면 해결법은 무수히 많았지만 어떤 해결법들이 적합한지 추합하기 위해 정말 많은 블로그들, 정보들을
- 알아보는 과정들에서 조금씩 낯선부분에서 익숙해지는 것을 알게 되었습니다
- MVC PROJECT를 만들고 깃허브에 연동하는 과정에서도 많은 어려움을 겪으면서 처음부터 프로젝트를 삭제하고 다시 만들고 수행하는 과정을 거쳤습니다
- 그 이유는 깃허브 아이디와 비밀번호부분에 토큰 설정이라는 것을 해야되는 것이었습니다. 이 토큰 설정이 안되어있다보니 거기서부터도 문제들이 발생하였고 아예 실행 파일 부분에 
- 파일이 없다는 오류들로 고생을 하였습니다. 사소하다는 부분은 없는 것 같습니다. 그로부터 오는 문제들을 해결하는데는 몇십배의 시간도 걸리는 것도 겪어보았습니다



#### 해결방법
- 구글링에 보다 먼저 많은 어려움을 겪은 분들이 원인을 분석해주고 해결해주는 것들을 보게 되었습니다. 
- 소중한 정보들을 나눔하는 것들에서 감동도 느낀 것 같습니다



#### 각종 참고 자료

- [이클립스에 스프링 설치](https://curiousing.tistory.com/17, "tistory link")
- [스프링 프레임워크 설치 참조](https://all-record.tistory.com/154?category=733072)
- [스프링 MVC 참조예제](https://bin-repository.tistory.com/87?category=879445)
- [자바 버전에 맞는 톰캣 고르기 어려움 해결](https://blog.naver.com/PostView.nhn?blogId=bestheroz&logNo=221321296597&parentCategoryNo=&categoryNo=23&viewDate=&isShowPopularPosts=true&from=search)
- [Spring MVC 프로젝트를 생성하여 톰캣에서 실행하기 가장 도움된 사이트](https://www.hanumoka.net/2018/04/08/spring-20180408-spring-start-spring-legacy-project/)
- [깃 설치](https://goddaehee.tistory.com/216)
- [이클립스 깃허브 연동](https://lifere.tistory.com/143)
- [push 시 깃허브 로그인 오류 해결 참조](https://kitty-geno.tistory.com/89)
- [push 시 깃허브 로그인 오류 해결 참조2](https://joytk.tistory.com/58)
- [로그인 오류해결을 위한 토큰발급](https://happycloud-lee.tistory.com/231)
- [완전 도움된 깃허브에 mvc 프로젝트 올리는법 연동](https://lifere.tistory.com/143)
- [개념/ 스프링, 스프링부트, 스프링 mvc 차이](http://dawoonjeong.com/spring-spring_mvc-vs-spring_boot-vs-spring_mvc/)
- [마크다운 작성 요령 참조](https://ffoorreeuunn.tistory.com/226)
- [마크다운 작성 요령 참조2](https://hippogrammer.tistory.com/123)
- [깃허브 이미지 넣기](https://cutemoomin.tistory.com/entry/Readme-%ED%8C%8C%EC%9D%BC%EC%97%90-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EB%84%A3%EA%B8%B0-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EC%9D%B4%EB%AF%B8%EC%A7%80)
