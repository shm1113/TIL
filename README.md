# TIL(Today - I - Learned)

**오늘 하루 배우고 공부한 내용을 저장하는 공간입니다.**
</br>&#10071; : 중복
</br>📖 : 개념

<br/>



## [2020-06-18](https://github.com/shm1113/TIL/blob/master/20200618.md)

### [jQuery]

-   ##### Class함수 

-   ##### 요소 위치 변경 메서드

-   ##### 요소 추가 및 텍스트 추가

-   ##### HTML로 감싸는 메서드

### [기타 내용]

-   ##### jquery로 만든 객체를 담는 변수앞에 $를 붙여주는 경우도 있다

### [Javascript]

-   ##### javascript  Timing Events(자바 타이밍 이벤트)

    -   ###### **`setTimeout( function , milliseconds )`**

    -   ###### **`setInterval( function , milliseconds )`**

    -   ###### **`clearInterval()`**

### [Servlet]

-   ##### Model, View, Controller

<br/>

## [2020-06-19](https://github.com/shm1113/TIL/blob/master/20200619.md)

### [jQuery]

-   ##### `.find( 선택자 )` 메서드

### [Ajax]

-   ##### Ajax란

-   ##### 비동기(async)방식

-   ##### XMLHttpRequest객체

-   ##### Ajax사용법

-   ##### 콜백 함수

</br>

## [2020-06-22](https://github.com/shm1113/TIL/blob/master/20200622.md)

### [JSP/Servlet]

-   ##### JSP란

-   ##### JSP동작 원리

-   ##### JSP태그

-   ##### 외부 패키지 import하는법

-   ##### JSP에서 JAR파일 넣는법

### [JAVA]

-   ##### Date클래스 java.util과 java.sql의 차이점

-   ##### String타입을 Date타입으로 변환하는법

</br>

## [2020-06-23](https://github.com/shm1113/TIL/blob/master/20200623.md)

### [JDBC]

-   ##### ResultSet객체

### [DB]

-   ##### 시퀀스 변경

### [JSP/Servlet]

-   ##### 다른 JSP페이지에 데이터 보내는 법

-   ##### 쿼리스트링 값 가져오는 법

    -   ###### `request.getParameter("쿼리스트링 키값")`

-   ##### HTML코드의 onclick()속성안에  JAVA코드를 넣으면 이벤트 발생 없이도 실행된다

-   ##### JSP파일 Template 수정하기

-   ##### myinsert.jsp에서 myinsertres.jsp로 다시 한번 보내주는 이유

-   ##### java의 if문과 html,javascript부분을 함께 쓰는 예제

-   ##### 📖 쿼리스트링 안에 " " (공백) 절대 넣으면 안된다

-   ##### 📖 form태그안에 태그들에게 꼭 필요한 속성 "Name = 키값"

### [에러]

-   ##### 500에러

</br>

## [2020-06-24](https://github.com/shm1113/TIL/blob/master/20200624.md)

### [JAVA]

-   ##### PreparedStatement객체는 close()를 따로 안해주는 이유

### [JSP/Servlet]

-   ##### DTO객체 만들 때 생성자

    -   ###### 필요에 따른 생성자 만들기

    -   ###### 생성자 오버로딩 주의

-   ##### JDBCBatch처리(일괄처리)

    -   ###### `.addBatch()`

    -   ###### `.executeBatch()`

    -   ###### PreparedStatement객체`.clearParameters()`를 이용한 반복 쿼리도 가능하다

## [2020-06-25](https://github.com/shm1113/TIL/blob/master/20200625.md)

### [DB]

-   ##### 오라클에서 숫자값은 "(따옴표)를 써도 되고 생략해줘도 된다

-   ##### Dao SQL문 쓸 때 *(all)을 안 쓰는 이유

### [JavaScript]

-   ##### CheckBox 전체선택 예제 &#10071;

-   ##### 최신버전  jQuery가져오는법

### [JSP/Servlet]

-   ##### 웹 프로젝트 (WAR파일) Import,Export하기

-   ##### 여러개의 값을 배열로 받는법 (ex : CheckBox값)

    -   ###### `request.getParametervalues("");`

-   ##### DBCP(Data Connection Pool)개념

-   ##### JDBC Batch처리(일괄처리)(내용추가)&#10071;

### [JDBC]

-   ##### `isConnection()`메서드 (직접만든)

    

## [2020-06-26](https://github.com/shm1113/TIL/blob/master/20200626.md)

### [Servlet]

-   ##### MVC1과 MVC2 차이

-   ##### import static class.* 와 extends

-   ##### 화면 전환방법 2가지

    -   ###### `pageContext.forward()`

    -   ###### `response.sendRedirect("boardwrite.jsp")`

## [2020-06-29](https://github.com/shm1113/TIL/blob/master/20200629.md)

### [JSP/Servlet]

-   ##### Servlet

    -   ###### Servlet이란 

    -   ###### ServletContainer란

-   ##### HttpServlet

-   ##### Request와 Response

-   ##### forward와 sendRedirect의 차이

-   ##### Session

</br>

## [2020-07-01](https://github.com/shm1113/TIL/blob/master/20200701.md)

</br>



### [Servlet]

###### 📖request객체는 목적으로 정한 controller까지이지만 forward해준경우에는 request객체를 공유해서 상관이 없다.

###### 📖 application객체가 null뜨는경우가 있다(오류)

###### 📖client의 요청은 일단 무조건 서버로 가게 되어있다

###### 📖controller에서 다른 jsp가 응답되려면 forward가 되던지 redirect가 되던지 둘중 하나가 되어야한다

###### 📖 Tomcat은 Web Server의 역할과 Web Application Server의 역할을 둘 다 할 수 있다



-   ##### Client의 request객체에 대한이해

-   ##### insert시 dispatch.forward()할 경우 문제 발생

-   ##### forward()두가지

    -   ###### Servlet에서

    -   ###### JSP에서 

-   ##### Servlet &#10071;

    -   ###### Servlet이란

    -   ###### ServletContainer란

-   ##### Wire Shark

-   ###### RequestDispatcher클래스_1(뒤에 또 나옴)

</br>

## [2020-07-02](https://github.com/shm1113/TIL/blob/master/20200702.md)



### [JSP/Servet]

-   ##### JavaBean(자바빈)

-   ##### EL

-   ##### JSTL

-   ##### tomcat 배포

-   ##### JSP API

</br>

## [2020-07-03](https://github.com/shm1113/TIL/blob/master/20200703.md)

### [복습]

-   ##### EL(Expression Language)은 스크립틀릿으로 값을 가져오던방식을 간단하게 사용할 수 있게 하는것 이고 JSTL은 스크립틀릿안의 if문 for문 DB등의 자바 코드들을 태그로 사용할수 있게 한것이다

-   ##### 📖 JSTL안에서는 <u>주석을 사용하면 안된다</u>

    -   ###### JSTL은 JSP에 해당하고 <!--는 HTML에 해당하는데 JSTL이 먼저 작동하기 때문에 문제가 생긴다

    -   ###### 다른 표현을 사용해야한다 ex) lt, gt..

### [JSP/Servlet]

-   ##### JSTL태그의 종류

-   ##### TDD(IT관련지식.md에서 추가 공부)

-   ##### JAVABean(자바빈)&#10071;(내용다름)

</br>

## [2020-07-04](https://github.com/shm1113/TIL/blob/master/20200704.md)

### [ JSP/Servlet]

-   ##### response객체

-   ##### 캐시(cache)없애는 법

-   ##### Get방식과 Post방식

-   ##### 쿠키, 세션, 캐시(IT관련지식.md에 추가)

-   ##### 서블릿 맵핑

    -   ###### @어노테이션

    -   ###### web.xml

-   ##### 서블릿 메소드

    -   ###### init()

    -   ###### service()

    -   ###### destroy

</br>

