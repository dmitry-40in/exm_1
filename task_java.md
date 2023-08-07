![Alt text](image-38.png)  
![Alt text](image-39.png)  
![Alt text](image-40.png)  
![Alt text](image-41.png)  
```
mysql> CREATE USER 'user'@'%' IDENTIFIED WITH mysql_native_password BY '12345';
mysql> GRANT ALL PRIVILEGES ON pet_db.* TO 'user'@'%';
```