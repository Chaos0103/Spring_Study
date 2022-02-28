## Project01: 회원 관리 예제

- controller
  - HomeController.java
  - MwmberController.java
  - MemberForm.java
- domain
  - Member.java
- repository
  - MemberRepository.java
  - MemoryMemberRepository.java
  - JdbcMemberRepository.java
  - JdbcTemplateMemberRepository.java
  - JpaMemberRepository.java
  - SpringDataJpaMemberRepository.java
- service
  - MemberService.java
- aop
  - TimeTraceAop.java
- SpringConfig.java
- templates
  - members
    - createMemberForm.html
    - memberList.html
  - home.html
  - application.properties
- test
  - repository
    - MemoryMemberRepositoryTest.java
  - service
    - MemberServiceTest.java
    - MemberServiceIntegrationTest.java
- build.gradle
- sql
  - ddl.sql

## Project02

- member
  - Grade.java
  - Member.java
  - MemberRepository.java
  - MemberService.java
  - MemberServiceImpl.java
  - MemoryMemberRepository.java
- order
  - Order.java
  - OrderService.java
  - OrderServiceImpl.java
- discount
  - DiscountPolicy.java
  - FixDiscountPolicy.java
  - RateDiscountPolicy.java
- MemberApp.java
- OrderApp.java
- AppConfig.java
- resources
  - appConfig.xml
- test
  - member
    - MemberServiceTest.java
  - order
    - OrderServiceTest.java
  - discount
    - RateDiscountPolicyTest.java
  - beanfind
    - ApplicationContextInfoTest.java
    - ApplicationContextBasicFindTest.java
    - ApplicationContextSameBeanFindTest.java
    - ApplicationContextExtendsFindTest.java
  - xml
    - XmlAppContext.java
  - beandefinition
    - BeanDefinitionTest.java
- build.gradle
