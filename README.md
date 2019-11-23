| Command | Description |
| --- | --- |
| psql -U postgres -h localhost dbname | Connect with Postgresql Database |
| create database mydb; | Create Database|
|\l |List of Database|
|drop database mydb;|Delete Database|
|psql -U postgres dbname|Connect with Selective Database|
|psql -h localhost -p 5432 -U postgres dbname|Connect with Selective Database|
|\c|Change Databases|
|\dt|Show All table|
|\d tablename|Show table structure|
|\h|See Command List|
|truncate table restart identity|Truncate Table with ID|
|C:\Program files\Postgresql\10\bin | Initially Locate Directory(DB Export) | 
|pg_dump -U postgres dbname > Location[D:\backup.sql] |Export Database|
|pg_dump -U postgres dbname < Location[D:\backup.sql]|Import Database|

