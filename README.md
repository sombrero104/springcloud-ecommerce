<br/>

# Service Discovery (Eureka Server) 

application.yml 파일을 아래와 같이 설정한다. <br/>
~~~
server:
  port: 8761

spring:
  application:
    name: discoveryservice

eureka:
  client:
    register-with-eureka: false
    fetch-registry: false
    # 서버로만 실행되는 역할이기 때문에 자기 자신은 유레카에 등록하지 않도록 한다. 
~~~

http://localhost:8761 로 접속하면 유레카 대쉬보드를 확인할 수 있다. <br/>
<img src="./images/eureka_dashboard.png" width="70%" /><br/>

<br/><br/><br/><br/>

