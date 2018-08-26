# mysql80

## Access first install
```console
$ grep pass /var/log/mysqld.log
```

## Create user, database
```code
# ALTER USER 'root'@'localhost' IDENTIFIED BY 'password';
# CREATE DATABASE test_db CHARACTER SET utf8 COLLATE utf8_general_ci;
# CREATE USER 'user_db'@'%' IDENTIFIED BY 'password';
# GRANT ALL ON user_db.* TO 'test_db'@'%';
# FLUSH PRIVILEGES;
```