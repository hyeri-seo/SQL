# SQL이란?
### 1. 정의
✅ SQL = Structured Query Language <br>
- <span style="color:yellowgreen">데이터를 꺼내고, 정리하고, 바꾸는 방법</span>을 공식화한 언어
- 데이터베이스에 저장된 데이터를 정의, 조회, 추가, 수정, 삭제하기 위한 언어
- DBMS에게 명령을 내리는 언어

### * DBMS (DataBase Management System)?
- SQL을 받아들이고 실행
- 실제 데이터를 저장하고 관리하는 시스템
- 예) Oracle, MySQL, PostgreSQL, Microsoft SQL Server 등

### * Client Tool?
- 사용자가 쉽게 SQL을 입력하고 실행할 수 있게 도와주는 GUI 인터페이스
- DBMS에 SQL을 보내고 결과를 보는 일종의 입력창 + 결과창
- 예) DBeaver, SQL Developter, DataGript, HeidiSQL, SSMS 등

✏️ 사용자는 SQL을 작성해서 Client Toll에 입력하고, Client Tool이 SQL을 DBMS로 보냄 <br>
✏️ DBMS는 SQL을 해석하고 처리 후, 결과를 클라이언트에 반환함

<hr>

### 2. 용어 정리
|구분|모델링 용어|DB 용어|설명, 예시|
|------|---|---|---|
|데이터 구조|엔터티|테이블, 릴레이션|관리할 대상: 학생|
|데이터 항목|속성|컬럼, 필드|관리할 대상의 특징: 학번, 이름 등|
|데이터 값|인스턴스|행, 레코드, 튜플|한 학생의 정보|
|데이터 집합|-|릴레이션|테이블 전체|
|식별 요소|식별자|키|학번은 곧 학생을 식별하는 키|
|관계 표현|관계|외래키 + JOIN||
