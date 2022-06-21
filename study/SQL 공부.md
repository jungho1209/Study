# SQL 공부

## SQL ?

- 관계형 DB 표준 질의어

### DDL ?

- 데이터 정의어 - 데이터를 정의 , 변경 , 삭제할 때 사용
- DBA 나 DB 설계자가 사용

- CREATE
    - SCHEMA , DOMAIN , TABLE , VIEW , INDEX 를 정의
- ALTER
    - TABLE 에 대한 정의를 변경
- DROP
    - SCHEMA , DOMAIN , TABLE , VIEW , INDEX 를 삭제

### DML ?

- 데이터 조작어 - DB 사용자가 데이터를 실질적으로 처리할 때 사용
- DBA 와 DB 관리 시스템 간의 인터페이스 제공

- SELECT
    - 테이블에서 조건에 맞는 튜플을 검색
- INSERT
    - 테이블에서 새로운 튜플을 삽입
- DELETE
    - 테이블에서 조건에 맞는 튜플 삭제
- UPDATE
    - 테이블에서 조건에 맞는 튜플의 내용 변경

### DCL ?

- 데이터 제어어 - 데이터의 보안, 무결성, 회복, 병행 수행 제어 등을 정의하는데 사용
- DBA 가 데이터 관리를 목적으로 사용

- COMMIT
    - 수행된 결과를 저장하고 , DB 조작 작업이 완료됨을 관리자에게 알려줌
- ROLLBACK
    - DB 조작 작업이 비정상적으로 종료되었을 때 원래 상태로 복구함
- GRANT
    - DB 사용자에게 사용 권한 부여
- REVOKE
    - DB 사용자의 사용 권한 취소