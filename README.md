| Description | Command |
| --- | --- |
|Connect with Postgresql Database|psql -U username[postgres] -h localhost dbname |
| Create Database| create database mydb; |
| List of Database|\l|
| Delete Database|drop database mydb;|
|Connect with Selective Database|psql -U postgres dbname|
|Connect with Selective Database|psql -h localhost -p 5432 -U postgres dbname|
|Change Databases|\c|
|Show All table|\dt|
|Show table structure|\d tablename|
|See Command List|\h|
|Truncate Table with ID|truncate table restart identity or TRUNCATE "products" RESTART IDENTITY CASCADE;|
|Initially Locate Directory(DB Export)|C:\Program files\Postgresql\10\bin|
| Export Database| pg_dump/psql -U postgres dbname > Location[D:\backup.sql] | 
| Import Database|pg_dump/psql -U postgres dbname < Location[D:\backup.sql]|
|Linux/Ubuntu Import database|psql -h hostname -d databasename -U username -f file.sql|
|Linux/Ubuntu Postgresql Install|sudo apt-get install build-dep python-psycopg2 and pip install psycopg2|
|Modify Users Password in Postgresql|ALTER USER user_name WITH PASSWORD 'new_password'
|Linux/Ubuntu Export database|psql -h hostname(localhost) -d databasename -U username(postgres) > filename.sql|



