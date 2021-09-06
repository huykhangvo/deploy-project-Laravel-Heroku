# heroku to laravel
Đầu tiên tạo 1 thư mục có tên là **heroku** copy project laravel có tên là **shop** vào như hình bên dưới

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imagea093beaaf149beaf.png)

Mở Git Bash Here

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/imagea6a97d492f24752e.png)

`cd shop` : mở project laravel

Chạy lệnh để tạo cho nó 1 **Procfile** `echo web: vendor/bin/heroku-php-apache2 public/ > Procfile` như hình bên dưới

![](https://i0.wp.com/s1.uphinh.org/2021/09/06/image467f87a071a47f18.png)

Trước tiên, chúng ta cần chạy:  `git init` Để tạo kho lưu trữ trống.
>Đều này rất quan trọng bởi vì chúng ta làm việc với heroku

`git add .` :Đẩy dữ liệu lênh

`git commit -m "initial release"` :comit bản phát hành đầu

`heroku login`

    $ cd my-project/
    
    $ git add .
    $ git commit -am "make it better"

`heroku create`

`git remote -v : xác minh`

`$ git push heroku master`

`heroku config:add APP_NAME=Laravel`
`heroku config:add APP_ENV=production`
`heroku config:add APP_URL=https://stormy-dawn-81482.herokuapp.com/`
Resources  tìm **Heroku Postgres**  add csdl vào
heroku pg:credentials:url
