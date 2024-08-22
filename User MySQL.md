# Change User Mysql

```
CREATE USER '<user>'@'localhost' IDENTIFIED BY 'new_password'    
ALTER USER '<user>'@'%' IDENTIFIED BY 'new_password'
```  

INSTALL PLUGIN server_audit SONAME 'server_audit.so';