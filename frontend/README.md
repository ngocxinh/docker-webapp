# frontend-example-docker

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
# API_URL=<http://ip-backend:port> npm start
```

(không có dấu < >)

Command sẽ serve ứng dụng với port `5000`

Test project bằng việc truy cập vào <http://ip-fronend:5000>

