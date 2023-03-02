## Thông tin phiên bản các extension và package

PHP apache v8.2

Mysql v8.0

Postgresql v15.0

NodeJs v19.0

Npm v9.0

Adminer latest

## Bắt đầu

Vào file `.env` chỉnh sửa các thông tin cấu hình cho phù hợp

Chạy lệnh build cho lần đầu

```bash
docker-compose up -d --build
```

Mở trình duyệt truy cập vào thử. Mặc định (localhost)[http://localhost]

Link vào adminer mặc định (adminer)[http://localhost:8084]

## Thông tin thêm

Document root của apache sẽ được dẫn đến thư mục `public` vì thế phải bỏ file php trong `public` mới được.
