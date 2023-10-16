# Tables_ETL
Migrating table from Oracle and loading into Snowflake table

![image](https://github.com/ShubhGo21/Tables_ETL/assets/114352465/324f88bd-235f-4dc8-9e51-b5e47a6d6778)

Here we are extracting table from oracle , loading that csv to snowflake internal/external stage and through that stage loading that csv to snowflake table.

Pre-requisites:
  Snowflakes
  Python
  Cx_Oracle lib , boto3 lib, snowflake lib

  1. Initially  we need to create table structure in Snowflakes
  2. Need to create internal/external Staging in snowflakes
       - For External staging we need to create Integration object and file format in snowflake.

That's it !
