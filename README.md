# intermediate_database_assignment_oracle_environment_sqlplus_setup

Oracle Express DB:

docker pull gvenzl/oracle-xe

docker run -d -p 1521:1521 -e ORACLE_PASSWORD=<your password> gvenzl/oracle-xe

![image](https://github.com/user-attachments/assets/fe529db2-b120-4fa0-b0bc-84c9a441e85b)

______________________________________________________________________________________________________________________________________________


SQL Plus with (UBUNTU WSL)

sudo alien -i oracle-instantclient-basic-23.8.0.25.04-1.el9.x86_64.rpm

 sudo alien -i oracle-instantclient-sqlplus-23.8.0.25.04-1.el9.x86_64.rpm

 sudo alien -i oracle-instantclient-devel-23.8.0.25.04-1.el9.x86_64.rpm
 
sqlplus system/123//localhost:1521/XEPDB1

![image](https://github.com/user-attachments/assets/c6dd91da-74a3-44ff-a0c0-a509a89ff96f)
