# heroku to laravel

Mở project `echo web: vendor/bin/heroku-php-apache2 public/ > Procfile`


Trước tiên, chúng ta cần chạy:  `git init` Để tạo kho lưu trữ trống.
>Đều này rất quan trọng bởi vì chúng ta làm việc với heroku

`git add .` :Đẩy dữ liệu lênh

`git commit -m "initial release"` :comit bản phát hành đầu

`heroku login`

`composer create-project laravel/laravel shop`


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
