# heroku to laravel

Đầu tiên ta tạo 1 **Procfile** trong thư mục **shop**

![](https://i0.wp.com/s1.uphinh.org/2021/09/05/new-Procfile.gif)
>Procfile Nó trông như thế này

    web: vendor/bin/heroku-php-apache2 public/

Trước tiên, chúng ta cần chạy:  `git init` Để tạo kho lưu trữ trống.
>Đều này rất quan trọng bởi vì chúng ta làm việc với heroku

`git add .` :Đẩy dữ liệu lênh
`git commit -m "initial release"` :comit bản phát hành đầu

`heroku login`

Nhấn Enter để tiếp tục;Gõ q để hủy
![](https://i0.wp.com/s1.uphinh.org/2021/09/05/image9e299697ebb1258f.png)
>Đăng nhập thành công

![](https://i0.wp.com/s1.uphinh.org/2021/09/05/imaged9d772e3aa82508c.png)


