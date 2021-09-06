# heroku to laravel
Đầu tiên tạo 1 thư mục có tên là **heroku** copy project laravel có tên là **shop** vào như hình bên dưới

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imagea093beaaf149beaf.png)

Mở Git Bash Here

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imagea6a97d492f24752e.png)

`cd shop` : mở project laravel

Chạy lệnh để tạo cho nó 1 **Procfile** `echo web: vendor/bin/heroku-php-apache2 public/ > Procfile` như hình bên dưới

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/image467f87a071a47f18.png)

- `heroku login` Login với heroku

- `git init` Để tạo kho lưu trữ trống.

- `git add .` Đẩy tất cả dữ liệu

- `git commit -m "initial release"` comit bản phát hành đầu

- `heroku git:remote -a huykhangvo2021` kết nối khu lưu trữ heroku tên thư mục

- `git remote -v` Kiểm tra kết nối kho lưu trữ chưa như hình bên dưới đã kết nối thành công.

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imagea6d2e0d4838cc4d2.png)

- `$ git push heroku master` Up lên kho lưu trữ

# Lệnh kết nối env

`heroku config:add APP_DEBUG=true`

`heroku config:add APP_KEY=base64:r4m70a6iE2Q7qgzQCyJHb7OPDRuCO/dWwDUm2yiGYxw=`

`heroku config:add APP_NAME=Laravel`

`heroku config:add APP_ENV=production`

`heroku config:add APP_URL=https://huykhangvo2021.herokuapp.com/` :Thay thế đường dẫn từ localhost lên web.

Resources  tìm **Heroku Postgres**  add csdl vào

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/image83672d193e6182cc.png)

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imageecbad52c70d138e6.png)
heroku pg:credentials:url

FULL cmd ![](https://i0.wp.com/s1.uphinh.org/2021/09/06/image1528ed1bff92c99b.png)
