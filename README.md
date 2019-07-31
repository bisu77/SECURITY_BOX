# SECURITY_BOX(Web, Android, Arduino)
2016년 11월 안양대학교 소프트웨어학과
졸업작품 '대상' 프로젝트

아두이노를 활용하여 웹과 앱을 통해 원격 제어 가능한 스마트 개인 무인택배함

◆ 개발목적

  택배가 왔을 때 혹은 지인에게 물건을 받을 때 사용자가 부재 중인 경우 스마트 개인 무인 택배함에 보관하는 것을 목적으로 한다.

◆ 개발환경

  - 운영체제 : Windows 7 Professional K (64bit)
  - 개발언어 : Java, JSP, HTML, Javascript, CSS
  - 개발도구  :  Eclipse, Android Studio, Arduino Sketch
  - 프레임워크 : Spirng
  - 데이터베이스 :  MySQL
  - WAS(Web Application Server) : Tomcat 7
  - OPEN API :  SweetTracker API, 우체국 API
  - 라이브러리 : JSONSimple Library, Jerico Library
  
◆ 동작과정
  IMAGE 1 
  
  가) 사용자가 웹/앱을 통해 운송장번호를 Server DB로 전송한다.
  나) 택배직원은 택배에 프린트 되어있는 바코드를 바코드리더기에 인식한다.
  다) 바코드리더기를 통해 읽힌 바코드가 사용자가 전송한 운송장번호와 일치 하는지 비교하여 일치하면 Security Box를 Open한다.
  라) 택배직원이 문을 닫으면 초음파센서를 활용해 자동으로 문이 잠긴다.

  IMAGE 2
  
◆ 비밀번호 암호화

  IMAGE 3
  
◆ 시연영상

https://www.youtube.com/watch?v=PY3BNhXKkGE
