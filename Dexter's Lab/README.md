# Dexter's Lab

- Mở đầu trang web là 1 form login đập vào mặt...

![home](image/lab1.png)

- Chả cần nghĩ nhiều lắm, có form login thì thử `sql injection` liền thôi.

![sql](image/lab2.png)

- Query đơn giản nhất để thử là `amdin' OR '1' = '1`. Login thử xem có gì xày ra không

![error](image/lab3.png)

- Nhìn sơ qua thì có vẻ `password` cũng bị lỗi luôn. Dễ rồi, thêm query vô phần `password` luôn.

![sql2](image/lab4.png)

- Đọc thêm về lỗi `sql injection` [Link](https://viblo.asia/p/sql-injection-va-cach-phong-chong-OeVKB410lkW)

![sql3](image/lab5.png)
