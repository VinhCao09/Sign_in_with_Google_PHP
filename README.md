# Sign in with Google PHP
In this project-based tutorial, code along with the instructor to integrate Google login in your PHP website. Using the Google OAuth API is an easy way to allow users to sign in using their Google account.

### Khởi động một tool như XAMPP để khởi động môi trường Apache để gói thư viện hoạt động!

## Sử dụng Composer quản lý gói thư viện
Link hướng dẫn cài đặt: https://nentang.vn/app/edu/khoa-hoc/thiet-ke-lap-trinh-web-backend/khoa-hoc-backend-thiet-ke-web-voi-laravel/lessons/cai-dat-composer-de-quan-ly-cac-goi-thu-vien-trong-php

Một số lệnh:

*Lệnh để trỏ tới thư mục chứa code:*
```bash
cd c:\xampp\htdocs\signinwithGoogle
```
*Lệnh để kiểm tra version*
```bash
php composer.phar --version
```
*Cài đặt gói thư viện với composer*

Lưu ý hãy trỏ tới thư mục chứa code rồi nhập lệnh
```bash
composer require google/apiclient
```

Sau đó anh em sẽ được một gói thư viện nằm trong vendor bao gồm autoload.php và một số folder như composer, firebase, google, guzzlehttp, symfony, psr,...

Lưu ý: Khi composer được cài đặt cũng sẽ bao gồm 2 gói là composer.json và composer.lock nằm ở folder gốc.
## Document &  Video
Tham khảo: https://www.youtube.com/watch?v=yi2b9U1kQyc&t=1s

## Giải thích source:
- index.php: Là button chứa nút đăng nhập với google
- dangnhap.php: Xử lý đăng nhập với Google, sau khi đăng nhập thành công sẽ lưu name và email vào session.
- testsession.php: Là file hoạt động độc lập để lấy phiên bao gồm name và email đã lưu từ trước, sau đó hiển thị ra màn hình tên user.

## Địa chỉ tạo OAuth API Google để đăng nhập với google:
https://console.cloud.google.com

Các bước: 
B1: Tạo project

B2: Vào APIs & Services

B3: Credentials và Create credentials

B4: OAuth Client ID

B5: Application chọn Web Application, Authorized redirect URIs thì add URL và thêm domain của anh em vào, ví dụ chạy localhost thì nhập ví dụ: http://localhost:3000/dangnhap.php

B6: Copy 2 thông số là ClientId và ClientSecret

## 🚀 About Me
Hello 👋I am Vinh. I'm studying HCMC University of Technology and Education

**Major:** Electronics and Telecommunication

**Skill:** 

*- Microcontroller:* ESP32/8266 - ARDUINO - PIC - Raspberry Pi

*- Programming languages:* C/C++/HTML/CSS/PHP/SQL and
related Frameworks (Bootstrap)

*- Communication Protocols:* SPI, I2C, UART, CAN

*- Data Trasmissions:* HTTP, TCP/IP, MQTT
## Authors

- [@my_fb](https://www.facebook.com/vcao.vn)
- [@my_email](contact@vinhcaodatabase.com)

## Demo

![Logo](https://codingninja.asia/images/codeninjalogo.png)

## Hướng dẫn

https://www.youtube.com/watch?v=yi2b9U1kQyc&t=1s

