# OracleSqlTests (Windows server 2019)
Oracle Sql Tests

Get:

https://docs.oracle.com/en/database/oracle/oracle-database/21/index.html
https://docs.oracle.com/en/database/oracle/oracle-database/21/install-and-upgrade.html

Connection information provided:

Multitenant container database: localhost:1521 (CDB) \
Pluggable database: localhost:1521/XEPDB1 (PDB)  \
EM Express URL: https://localhost:5500/em 

Open port 1521(windows server 2019):

https://manifold.net/doc/mfd9/open_a_firewall_port_for_oracle.htm

Login as system user(SQL Plus):

user: system
pass: (in setup)

or get:
https://www.oracle.com/database/sqldeveloper/technologies/download/

1. Create pluggable database arturpdb and set admin user artur_adm
2. Set arturpdb open to read and write
3. Create user C##arturlasok and grad all privileges  
4. Get sample database schema https://www.oracletutorial.com/getting-started/oracle-sample-database/
5. Con as C##arturlasok and execute SQL>@c:\path_to_file\ot_schema.sql

https://www.oracletutorial.com/wp-content/uploads/2017/07/Oracle-Sample-Database.png

6. Exec @c:\dbsample\ot_data.sql
7. QUERIES TO THE DATABASE :) https://github.com/ArturLasok/OracleSqlTests/blob/4f2b87d60374376d1b2ee2e14e6cd4e88097b98d/simpleQueries
