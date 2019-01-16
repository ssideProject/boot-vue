# Boot와 Vue를 이용한 Todo-list CRUD 구현

만들고 있는 <a href ="https://github.com/sstoneju/Boot-JPA-Vue">볼링 평균점수 사이트</a>와 다르게 Boot와 Vue의 프로세스를 따로 작동시켜야한다.


## 목표
1. Spring Boot를 백앤드로 이용하고 Vue를 프론트앤드로 사용한다.
2. 깊은 활용보다는 boot와 vue가 어떻게 같이 사용이 되는지를 파악한다.
3. spring security의 cros방지 기술을 적용한다.

## 주제
Todo-list의 CRUD 기능을 작성한다.

## 구현
#### Server 사용기술
- Spring Boot
- Spring data JPA(Hibernate)
- H2 Database

#### Server 제작 내용
- Repository에 @RepositoryRestResource 어노테이션을 사용해서 따로 Rest의 controller를 따로 작성하지 않아도 간단한 Service를 제공해준다.
- FilterRegistrationBean을 작성해줬다. 다른 주소의 접근을 막아준다. Vue.js로의 데이터 접근만 허용한다.

#### Client 제작 내용
- axios를 사용해서 백앤드와 어떻게 통신이 되는지를 익힌다. 
- webpack을 이용해서 build시키는 법을 익힌다. (<a href ="https://github.com/sstoneju/Boot-JPA-Vue">볼링 평균점수 사이트</a> 미완성)
- Vue-router기능을 사용해서 프론트에서의 페이지 전환을 한다. (<a href ="https://github.com/sstoneju/Boot-JPA-Vue">볼링 평균점수 사이트</a> 미완성)
- Vuex를 이용해서 상태관리를 사용한다. (<a href ="https://github.com/sstoneju/Boot-JPA-Vue">볼링 평균점수 사이트</a> 예정)


