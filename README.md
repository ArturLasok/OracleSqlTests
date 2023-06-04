# OracleSqlTests (Windows server 2019)
Oracle Sql Tests

Get:

https://docs.oracle.com/en/database/oracle/oracle-database/21/index.html
https://docs.oracle.com/en/database/oracle/oracle-database/21/install-and-upgrade.html

Connection information provided:

Multitenant container database: localhost:1521 CDB. n\
Pluggable database: localhost:1521/XEPDB1 PDB  n\
EM Express URL: https://localhost:5500/em 

Open port 1521:

https://manifold.net/doc/mfd9/open_a_firewall_port_for_oracle.htm

Login as system user(SQL Plus):

user: system
pass: (in setup)

SQL> SHOW con_name;

CON_NAME
------------------------------
CDB$ROOT

or get:
https://www.oracle.com/database/sqldeveloper/technologies/download/

1. Create pluggable database arturpdb and set admin user artur_adm
2. Set arturpdb open to read and write
3. Create user C#arturlasok and grad all privileges to user 
