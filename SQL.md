## 1. DDL
1. CREATE
2. ALTER
3. DROP
3. TRANCATE


## 2. DML
1. SELECT
  1. GROUP BY 컬럼명1, 컬럼명2
  
  2. HAVING 그룹조건
  
  3. ORDER BY 속성 ASC | DESC

2. INSERT
  1. 속성명 명시 : 
  
          INSERT INTO 테이블명(속성명1, 2, 3)
  
                    VALUES(값1, 2, 3)
                    
  2. 속성명 미명시 :  
    
          INSERT INTO 테이블명
  
                    VALUES(값1, 2, 3)
                    
3. UPDATE

          UPDATE 테이블명
             SET 속성명 = 데이터, ...
          [WHERE 조건]; //모든 행을 변경할 경우 WHERE문을 포함하지 않는다.
          
4. DELETE
          DELETE FROM 데이블 명
          [WHERE 조건];
## 3. DCL

데이터베이스 관리자가 더이터 보안, 무결성 유지, 병행제어, 회복하기 위해 관리자{DBA)가 사용하는 제여용 언어이다.

1. GRANT(부여)

            GRANT 권한 ON 테이블명 TO 사용자명
 
 2. REVOKE(회수)
            REVOKE 권한 FROM 사용자
            REVOKE 권한 ON 'TABLE NAME' FROM 'USER'
