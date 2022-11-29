# Some SQL Statements

### Create database
```
CREATE DATABASE SchoolCalendar;
SHOW CREATE DATABASE SchoolCalendar;

DROP DATABASE schoolcalendar;
```

### Create datatable
```
USE SchoolCalendar;
SELECT DATABASE();

CREATE TABLE Student(ID INT NOT NULL,Name VARCHAR(30) NOT NULL,SchoolName VARCHAR(60) NOT NULL,PRIMARY KEY(ID));
DESCRIBE Student;

INSERT INTO Student VALUE ("1", "Person1", "TheSchool");
INSERT INTO Student VALUE ("2", "Person2", "MySchool");

SELECT * FROM Student;
```

Output:
```
mysql> SELECT * FROM Student;
+----+----------+-------------+
| ID | Name     | SchoolName  |
+----+----------+-------------+
|  1 | Person1  | TheSchool   |
|  2 | Person2  | MySchool    |
+----+----------+-------------+
2 rows in set (0.00 sec)

```
