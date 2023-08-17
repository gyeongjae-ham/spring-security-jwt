# Spring Security with JWT

- spring boot 3.x 버전 이상
- Java 17 버전

## dependency
- web
- lombok
- mysql driver
- data jpa
- mustache
- devtools
- security

> 해당 환경에서 security 설정하고(학습 내용은 spring boot 2.x 버전이라서 antMatchers 등 설정법 변경 webconfigurer 대신 securityFilter 에서 bean 구현) JWT 방식 인증을 Security filter에 등록해서 사용하기

## 학습 내용
- 세션
- TCP
- CIA
- RSA
- RFC 문서

## Commit 순서
- JWT 프로젝트 세팅
- yml 설정
- security 설정
- Bearer 인증 설정
- Filter 등록 및 테스트
- 임시 토큰으로 테스트
- 로그인
- 강제 로그인
- 응답
- jwt 서버 구축
