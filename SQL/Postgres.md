 ```bash
 sudo -i -u postgres
```
open the postgres terminal

```bash
q or \q
```
to quite/escape

## Once inside postgres

```bash
psql -f /path/to/sqlfile
```
the command to run the file

```bash 
psql
```
don't know why but you need to do it

```bash
psql -d mydatabase -f /path/to/sqlfile.sql
```
the command to create the table in a specific database

```bash
CREATE DATABASE database_name
```
create database

```bash
\i /path/to/sqlfile.sql
```
to create run a file while inside a database

```bash
\l
```
to list the databases

```bash
\c database_name
```
connect to a database

```bash
\dt
```
to list all tables in the current database (must first connect to a database)

```bash
select verion();
```
to get the version of SQL

```bash
\d table name
```
to see the table

```bash
postgresql://user:password@host:port/dbname
```
format
```bash
postgresql://postgres:1234@localhost:5432/pets
```
example 
how to make a connection URL