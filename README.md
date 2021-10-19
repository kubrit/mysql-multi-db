# mysql-multi-db
One mysql container with multiple databases init.

## Root password
change root password to hard to break: `MYSQL_ROOT_PASSWORD: root_password`

### 1. Run docker-compose
```sh
git clone https://github.com/kubrit/mysql-multi-db.git
cd mysql-multi-db
docker-compose -up -d
```