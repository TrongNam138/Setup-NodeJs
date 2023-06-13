`file ẩn: ` file bắt đầu bằng đấu chấm

`/: ` thư mục gốc của hệ thống

`~: ` thư mục gốc của user hiện tại VD: /$ cd ./home/n138 = ~\$

`sudo: ` để thực hiện những lệnh đòi hỏi bạn phải là admin hoặc có quyền root

- viết nhiều lệnh cùng lúc bằng cách sử dụng ; hoặc &&

- có 3 vai trò: chủ sử hữu, nhóm sử hữu, khác

'- --- --- ---' VD: drwxrwxr-x

d: folder
-: file
l: shotcut

9 ký tự còn lại thể hiện các nhóm trên

3 ký tự đầu: own (User)
3 ký tự tiếp: group
3 ký tự cuối: other

r: quyền đọc
w: quyền viết
x: quyền thực thi

| Câu lệnh      | Ý nghĩa                                            |
| :------------ | :------------------------------------------------- |
| `ls`          | liệt các folder và file không bị ẩn                |
| `ls -l`       | liệt kê chi tiết                                   |
| `ls -a`       | liệt kê tất cả bao gồm cả folder và file ẩn        |
| `ls -R`       | liêt kê các cấp con của folder và file không bị ẩn |
| `cd`          | di chuyển đến các thư mục                          |
| `cd -`        | quay về đường dẫn trước đó                         |
| `cd ./`       | đi vào folder con                                  |
| `cd ../`      | quay về folder cha                                 |
| `mkdir`       | tạo folder                                         |
| `rmdir`       | xóa folder trống                                   |
| `mkdir -p`    | tạo thư lồng nhau nhiều cấp                        |
| `touch`       | tạo file                                           |
| `rm`          | xóa file                                           |
| `rm -r`       | xóa folder lồng nhau và file                       |
| `vi`          | mở vim                                             |
| `cat`         | xem nội dung và ghép nối các file                  |
| `>`           | ghi đè                                             |
| `>>`          | ghi thêm                                           |
| `echo`        | in nội dung ra màn hình                            |
| `tail`        | in ra 10 dòng cuối của 1 file                      |
| `grep`        | tìm kiếm                                           |
| `cp`          | sao chép                                           |
| `mv`          | di chuyển hoặc đổi tên                             |
| `chmod`       | phân quyền                                         |
| `man`         | tra cứu lệnh                                       |
| `wget`        | tải tài nguyên trên mạng                           |
| `apt`         | quản lý các cài đặt gói phần mền                   |
| `apt update`  | kéo những thông tin mới về nhưng chưa cài đặt      |
| `apt upgrade` | dựa vào những thông tin được kéo về và cài đặt     |
| `kill`        | kết thúc một tiến trình                            |
| `ping`        | kiểm tra tín hiệu kết nối đến một máy chủ          |
| `passwd`      | đổi mật khẩu                                       |
| `top`         | giống task manager (nếu chưa có thì cài đặt)       |
| `df`          | thông tin ổ cứng                                   |
| `free`        | thông tin ram                                      |
