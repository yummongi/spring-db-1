# 🌱 스프링 DB 1편 - 데이터베이스 핵심 원리와 활용

이 리포지토리는 인프런에서 제공하는 김영한 님의 "스프링 DB 1편" 강의를 학습하고 실습하는 공간입니다.

## 📚 강의 개요
- 강사: 김영한
- 플랫폼: 인프런
- 주제: 스프링과 데이터베이스 기본 원리

## 🎯 학습 목표
- JDBC 원리와 동작 방식 이해하기
- 데이터베이스 연결 및 트랜잭션 처리 학습
- 스프링을 활용한 데이터베이스 접근 기술 습득
- 예외 처리와 반복 문제 해결 방법 이해하기
- 데이터소스와 커넥션 풀 개념 학습

## 📋 커리큘럼 및 학습 진행 상황
### 섹션 1: 강의 소개
- [x] 강의 소개
- [x] 수업 자료 다운로드
- [x] 강의 소스 코드 확인

### 섹션 2: JDBC 이해
- [x] 프로젝트 생성
- [x] H2 데이터베이스 설정
- [x] JDBC 이해
- [x] JDBC와 최신 데이터 접근 기술
- [x] 데이터베이스 연결
- [x] JDBC 개발 - 등록
- [x] JDBC 개발 - 조회
- [x] JDBC 개발 - 수정, 삭제
- [x] 정리

### 섹션 3: 커넥션풀과 데이터소스 이해
- [x] 커넥션 풀 이해
- [x] DataSource 이해
- [x] DataSource 예제1 - DriverManager
- [x] DataSource 예제2 - 커넥션 풀
- [x] DataSource 적용
- [x] 정리

### 섹션 4: 트랜잭션 이해
- [x] 트랜잭션 - 개념 이해
- [x] 데이터베이스 연결 구조와 DB 세션
- [x] 트랜잭션 - DB 예제1 - 개념 이해
- [x] 트랜잭션 - DB 예제2 - 자동 커밋, 수동 커밋
- [x] 트랜잭션 - DB 예제3 - 트랜잭션 실습
- [x] 트랜잭션 - DB 예제4 - 계좌이체
- [x] DB 락 - 개념 이해
- [x] DB 락 - 변경
- [x] DB 락 - 조회
- [x] 트랜잭션 - 적용1
- [x] 트랜잭션 - 적용2
- [x] 정리

### 섹션 5: 스프링과 문제 해결 - 트랜잭션
- [x] 문제점들
- [x] 트랜잭션 추상화
- [x] 트랜잭션 동기화
- [x] 트랜잭션 문제 해결 - 트랜잭션 매니저1
- [x] 트랜잭션 문제 해결 - 트랜잭션 매니저2
- [x] 트랜잭션 문제 해결 - 트랜잭션 템플릿
- [x] 트랜잭션 문제 해결 - 트랜잭션 AOP 이해
- [x] 트랜잭션 문제 해결 - 트랜잭션 AOP 적용
- [x] 트랜잭션 문제 해결 - 트랜잭션 AOP 정리
- [x] 스프링 부트의 자동 리소스 등록
- [x] 정리

### 섹션 6: 자바 예외 이해
- [x] 예외 계층
- [x] 예외 기본 규칙
- [x] 체크 예외 기본 이해
- [x] 언체크 예외 기본 이해
- [x] 체크 예외 활용
- [x] 언체크 예외 활용
- [x] 예외 포함과 스택 트레이스
- [x] 정리

### 섹션 7: 스프링과 문제 해결 - 예외 처리, 반복
- [x] 체크 예외와 인터페이스
- [x] 런타임 예외 적용
- [x] 데이터 접근 예외 직접 만들기
- [x] 스프링 예외 추상화 이해
- [x] 스프링 예외 추상화 적용
- [x] JDBC 반복 문제 해결 - JdbcTemplate
- [x] 정리

### 섹션 8: 다음으로
- [x] 다음으로

## 💻 주요 실습 프로젝트
- [x] JDBC를 활용한 데이터베이스 기본 연결
- [x] 커넥션 풀 및 데이터소스 구현
- [x] 트랜잭션 처리 예제
- [x] 예외 처리 및 반복 문제 해결

## 🔗 링크
- [스프링 DB 1편 강의 링크](https://www.inflearn.com/course/스프링-db-1)

## ⚠️ 주의사항
이 리포지토리의 코드는 학습 목적으로 작성되었으며, 실제 프로덕션 환경에서는 추가적인 고려사항이 필요할 수 있습니다.

## 📌 Commit 메시지 규칙
```
[섹션번호] 주제: 상세 내용
- 학습한 주요 개념
- 실습한 내용
- 특이사항 또는 주의점
```

예시:
```
[섹션2] JDBC 기본 원리: 데이터베이스 연결 및 기본 CRUD 구현
- JDBC 기본 개념 이해
- H2 데이터베이스 연결 및 설정
- 데이터 등록, 조회, 수정, 삭제 메서드 구현
- 기본적인 JDBC 연결 및 예외 처리 방법 학습
```

## 📅 학습 일지
| 날짜         | 학습 내용            | 비고                                         |
|------------|------------------|--------------------------------------------|
| 2024-12-15 | 리포지토리 생성 및 학습 계획 수립 | 스프링 DB 1편 학습 시작!                           |
| 2024-12-15 | 섹션 1-2 완료        | 강의 소개 및 JDBC 기본 개념 학습                      |
| 2024-12-18 | 섹션 3 완료          | 커넥션 풀과 DataSource 개념 학습                    |
| 2025-01-03 | 섹션 4 완료          | 트랜잭션과 DB락 개념 학습                            |
| 2025-01-05 | 섹션 5 진행중         | 트랜잭션 매니저와 트랜잭션 템플릿 학습                      |
| 2025-01-11 | 섹션 5 완료          | 트랜잭션 AOP 학습                                |
| 2025-03-11 | 섹션 6,7 일부 완료     | 예외 처리, 이해 학습                               |
| 2025-03-11 | 섹션 7 완료          | JDBCTemplate, SpringExceptionTranslator 학습 |
 

🌱 데이터베이스와 스프링의 핵심을 이해하고, 견고한 데이터 접근 기술을 습득하자!