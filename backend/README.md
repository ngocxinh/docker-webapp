# backend-example-docker

Cài đặt Node 10.x:
```
# apt update -y
# apt install curl -y
# curl -sL https://deb.nodesource.com/setup_10.x | bash
# apt install -y nodejs
```

Cài đặt các packages :

```
# npm install
```

Khởi động ứng dụng: 

```
# FRONT_URL=<http://ip-frontend:port> npm start
```

(không có dấu < >)

Command sẽ serve ứng dụng với port `8000`

Test project bằng việc truy cập vào <http://ip-backend:8000>


