# 프로그래머스 SQL 문제 풀이

이 레포지토리는 프로그래머스의 SQL 문제 풀이를 저장하고 공유하기 위한 곳입니다.

## 파일 명명 규칙

각 SQL 문제의 해답은 다음 형식의 파일 이름으로 저장됩니다:

```
문제번호.sql
```
`https://school.programmers.co.kr/learn/courses/30/lessons/${문제번호}` 

예: `12345.sql`

## MySQL 기본 문법

### 1. SELECT 문

데이터를 조회할 때 사용합니다.

```sql
SELECT column1, column2 FROM table_name WHERE condition;
```

### 2. INSERT 문

새로운 데이터를 삽입할 때 사용합니다.

```sql
INSERT INTO table_name (column1, column2) VALUES (value1, value2);
```

### 3. UPDATE 문

기존 데이터를 수정할 때 사용합니다.

```sql
UPDATE table_name SET column1 = value1 WHERE condition;
```

### 4. DELETE 문

데이터를 삭제할 때 사용합니다.

```sql
DELETE FROM table_name WHERE condition;
```

### 5. JOIN

두 개 이상의 테이블을 연결할 때 사용합니다.

```sql
SELECT * FROM table1 
INNER JOIN table2 ON table1.column = table2.column;
```

### 6. GROUP BY

데이터를 그룹화할 때 사용합니다.

```sql
SELECT column1, COUNT(*) FROM table_name GROUP BY column1;
```

### 7. ORDER BY

결과를 정렬할 때 사용합니다.

```sql
SELECT * FROM table_name ORDER BY column1 ASC, column2 DESC;
```

## 자주 사용되는 함수들

- COUNT(): 행의 개수를 세는 함수
- SUM(): 합계를 구하는 함수
- AVG(): 평균을 구하는 함수
- MAX(), MIN(): 최대값과 최소값을 구하는 함수
- DISTINCT: 중복을 제거하는 키워드

## 참고 자료

- [MySQL 공식 문서](https://dev.mysql.com/doc/)
- [프로그래머스 SQL 고득점 Kit](https://programmers.co.kr/learn/challenges?tab=sql_practice_kit)
