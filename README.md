# DBMS
Experiments 1 : DDL Commands – CREATE, ALTER, DROP(https://github.com/Selmeya/DBMS/blob/main/DDL%20Commands%20%E2%80%93%20CREATE%2C%20ALTER%2C%20DROP)
Output:
   
   1) ![Ex1 output 1](https://user-images.githubusercontent.com/112368898/194228232-18088837-96e0-45a9-9847-cb8972c634ff.png)
   
  2)  ![Ex1 output2](https://user-images.githubusercontent.com/112368898/194229246-ca792c1a-f50c-4063-92ab-af7aa8d3b36f.png)
  3)  ![Ex1 output 3](https://user-images.githubusercontent.com/112368898/194229337-ef623d61-0456-4ace-bb3b-0352e537d9fb.png)
  4)  ![Ex1 output 4](https://user-images.githubusercontent.com/112368898/194229504-735baa6c-29a0-44b9-8593-a3753be40275.png)
  5)  ![Ex1 output 5](https://user-images.githubusercontent.com/112368898/194229616-e5166a61-3dfa-45f4-98ec-7896bf8c67a4.png)
Experiment 2 : 
Output:
 1)mysql> desc Stu;
+-----------+-------------+------+-----+---------+-------+
| Field     | Type        | Null | Key | Default | Extra |
+-----------+-------------+------+-----+---------+-------+
| ROLLNO    | int(10)     | NO   | PRI | 0       |       |
| NAME      | varchar(20) | YES  |     | NULL    |       |
| DEPT      | varchar(4)  | YES  |     | NULL    |       |
| GENDER    | varchar(1)  | YES  |     | NULL    |       |
| DOB       | date        | YES  |     | NULL    |       |
| CITY      | varchar(20) | YES  |     | NULL    |       |
| MOBILE_NO | int(10)     | NO   |     | NULL    |       |
+-----------+-------------+------+-----+---------+-------+
7 rows in set (0.01 sec)
2)mysql> desc Faculty;
+------------+-------------+------+-----+---------+-------+
| Field      | Type        | Null | Key | Default | Extra |
+------------+-------------+------+-----+---------+-------+
| FACULTY_ID | varchar(4)  | YES  |     | NULL    |       |
| FAC_NAME   | varchar(15) | YES  |     | NULL    |       |
| GENDER     | char(1)     | YES  |     | NULL    |       |
| DOB        | date        | YES  |     | NULL    |       |
| DOJ        | date        | YES  |     | NULL    |       |
| MOBILE_NO  | int(10)     | YES  |     | NULL    |       |
| Dept       | varchar(4)  | YES  |     | NULL    |       |
+------------+-------------+------+-----+---------+-------+
3)mysql> desc Dept;
+-----------+-------------+------+-----+---------+-------+
| Field     | Type        | Null | Key | Default | Extra |
+-----------+-------------+------+-----+---------+-------+
| DEPT_NO   | varchar(4)  | NO   | PRI |         |       |
| DEPT_NAME | varchar(15) | YES  |     | NULL    |       |
| DEPT_HEAD | varchar(4)  | YES  |     | NULL    |       |
+-----------+-------------+------+-----+---------+-------+
3 rows in set (0.03 sec)
4)mysql> desc Cour;
+-------------+-------------+------+-----+---------+-------+
| Field       | Type        | Null | Key | Default | Extra |
+-------------+-------------+------+-----+---------+-------+
| COURSE_NO   | varchar(3)  | NO   | PRI |         |       |
| COURSE_DESC | varchar(14) | YES  |     | NULL    |       |
| COURSE_TYPE | char(1)     | YES  |     | NULL    |       |
| SEM_NO      | char(1)     | YES  |     | NULL    |       |
| HALL_NO     | varchar(4)  | YES  |     | NULL    |       |
| FAC_NO      | varchar(4)  | YES  |     | NULL    |       |
+-------------+-------------+------+-----+---------+-------+
6 rows in set (0.02 sec)

