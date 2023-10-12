# flask_4_databases_mysql_vm
Manually setting up and running a database on a cloud VM. You'll get hands-on experience setting up a MySQL instance on a VM, (optional but recommended: integrating it with a Flask app).

## VM & MySQL Setup
1. VM was setup on Microsoft Azure. In the networking table, port 3306 was added
2. In terminal of Google Shell, login using the "ssh<username>@<IP address>" with the username created when making the vm and the I address of the vm. 
3. Use "sudo apt-get update" to update the UBUNTU (OS) Server and install MySQL using "sudo apt install mysql-server mysql-client".
4. Login using sudo mysql
5. Create a new user using "CREATE USER '<user>'@'%'IDENTIFIED BY '<password>'’".
6. Grant the new user to connect using "GRANT ALL PRIVEGES ON*.*TO'<user>'@'%'WITH GRANT OPTION;". Confirm that it shows grants for dba.

## Rationale of Database Schema
I created a new database and created 2 tables using the first 2 categories of my database from assignment 4a. Two tables called "doctors" and "patients" were created. For the doctors table, it is important that there is a primary key, which is the doctor_id, the first and last name of the doctor, their specialization or department, and their contact number. For the 

## Steps and Challenges of database migration process

## Errors/Troubleshooting
