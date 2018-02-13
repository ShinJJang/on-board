# on-board
board with on-board olympic scoreboard

# simple todo
 1. ~~github repo 파기~~
 2. ~~repo에 contributor로 날 invite하기~~
 3. markdown으로 스펙이랑 TODO 쓰기 
 4. node로 hello world 를 출력하는 기본 프로젝트 생성해서 init commit 하기
 5. 데이터 구조 짜기(DB 스키마)
 6. URL 설계하기
 7. 분업하기

# 데이터구조
 (id, date, contents)
 CREATE TABLE posts ( id MEDIUMINT NOT NULL AUTO_INCREMENT, date DATE, contents TEXT, PRIMARY KEY(id));
 
 mysql> desc posts;
+----------+--------------+------+-----+---------+----------------+
| Field    | Type         | Null | Key | Default | Extra          |
+----------+--------------+------+-----+---------+----------------+
| id       | mediumint(9) | NO   | PRI | NULL    | auto_increment |
| date     | date         | YES  |     | NULL    |                |
| contents | text         | YES  |     | NULL    |                |
+----------+--------------+------+-----+---------+----------------+
 https://dev.mysql.com/doc/refman/5.7/en/create-table.html
