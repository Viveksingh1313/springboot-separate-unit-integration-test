# springboot-separate-unit-integration-test
Separate unit and integration test cases using mvn profiles in spring boot

Medium Link for explanation of repository :
https://vivek-sinless.medium.com/springboot-separate-unit-integration-test-336abbc38ef4

In this article, we will see how we can separate our unit and integration tests in springboot. 
Unit Test and Integration tests can be run separately using separate commands. 
This can be used for different purposes like in a CICD pipeline where we have two separate stage called 
‘unit test’ and ‘integration test’.


Commands : 
install libraries    :        mvn clean install
run unit-test        :        mvn test -Punit-test
run integration-test :        mvn test -Pintegration-test
run applicaition     :        mvn spring-boot:run
Endpoint             :        http://localhost:8099/user/1 


Medium Link for explanation of repository :
https://vivek-sinless.medium.com/springboot-separate-unit-integration-test-336abbc38ef4