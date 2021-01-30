- Overview   
   - [개요](monolithic/overview.md)
   - [실습준비](monolithic/requirement.md)
   
- Develop Guide
  - 벡엔드
  
   - [벡엔드 Overview](monolithic/develop/01.md)
   - [SpringBoot 프로젝트 시작하기와 Gradle 구성](monolithic/develop/02.md)
   - [Mysql 세팅과 Flyway 스키마 관리](monolithic/develop/03.md)
   - [도메인 모델과 JPA Repository](monolithic/develop/04.md)
   - [차량도메인 구현](monolithic/develop/04_1.md)
   - [운행도메인 구현](monolithic/develop/04_2.md)
   - [QueryDSL 을 사용한 쿼리](monolithic/develop/05.md)
   - [FeignClient 를 통한 외부서비스 호출](monolithic/develop/06.md)
   - [비즈니스 로직과 트랜잭션 (차량관리)](monolithic/develop/07.md)
   - [비즈니스 로직과 트랜잭션 (운행관리)](monolithic/develop/08.md)
   - [비즈니스 로직과 트랜잭션 (스케쥴러)](monolithic/develop/09.md)      
   - [SpringSecurity 인증처리 (사용자관리)](monolithic/develop/10.md)
   - [SpringBoot 프로파일과 운영환경 분리](monolithic/develop/11.md)
   
  - 프론트엔드
  
   - [프론트엔드 Overview](monolithic/develop/12.md)
   - [VueJS 프로젝트 시작하기와 모듈구성](monolithic/develop/13.md)
   - [VueJS 컴포넌트와 라우팅을 통한 페이지처리](monolithic/develop/14.md)
   - [VueJS API 통신과 메시지 처리](monolithic/develop/15.md)
   - [VueJS 로그인과 인증처리](monolithic/develop/16.md) 
   - [VueJS 빌드와 패키징](monolithic/develop/17.md)
  
- AWS Guide

   - [데이터베이스 구축 (VPC, AWS RDS)](monolithic/aws/01.md)
   - [어플리케이션 구동 (Nginx 와 static contents)](monolithic/aws/02.md)
   - [어플리케이션 구동 (SpringBoot 와 JVM)](monolithic/aws/03.md)
   - [웹호스팅과 이중화구성 (AWS ALB 와 Route53)](monolithic/aws/04.md)
   - [오토스케일링 설정 (AWS Autoscaling Group 와 AMI)](monolithic/aws/05.md)
   - [부하테스트 실행](monolithic/aws/06.md)
   - [로그수집 (CloudWatch)](monolithic/aws/07.md)
