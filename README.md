# Verdaccio

## 启动服务

0. `mkdir storage config plugins`
1. `cd config && htpasswd -c passwdFile admin`
2. `sudo chown -R 10001:65533 storage config plugins`
3. `docker-compose up -d`

检查服务是否启动成功： http://127.0.0.1:4873/

- username: admin
- password: admin


## 配置npm

1. `npm set registry http://127.0.0.1:4873/`



