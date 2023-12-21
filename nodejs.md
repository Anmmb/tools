# Một Số Công Cụ Làm Việc

## Cài Đặt Node JS
Tải Về Từ Nodejs.org

## kiểm Tra node js
```node -v``` kiểm Tra Phiên Bản node js
```npm -v``` kiểm Tra Phiên Bản NPM (node package manager)


## Tạo Máy Chủ HTTP Đơn Giản Bằng package: **http-server**
Cài Đặt
```
npm install --global http-server
```

Tạo Máy Chủ HTTP Trên Thư Mục
- Vào Thư Mục
- Gõ Lệnh ```http-server``` Hoặc ```http-server.cmd```
- Mặc Định Cổng Truy Cập Là 8080
- Nếu Muốn Thay Đổi Cổng Thì Thêm Tham Số ```-p PORT``` Ví Dụ ```http-server -p 8081```
- Truy Cập Máy Chủ Bằng ```http:://localhost:port``` Hoặc ```http://127.0.0.1:oort``` Hoặc Bằng Địa Chỉ Ip Của Máy ```http://IP:port```
- Các Máy Cung Mạng Thì Truy Cập Bằng IP: ```http://IP:port```

## browser-sync (https://browsersync.io/)
**browser-sync** Là Công Cụ Đồng Bộ Trình Duyệt Cho Mục Đích Kiểm Thử.
- Cài Đặt
```
npm install -g browser-sync
```
- Chạy browser-sync: Chạy browser-sync như là proxy

```
browser-sync start --proxy "diachitruycap" --files "đường-dẫn-đến-file-theo-dỗi"
```
hoac trong PowserShell
```
browser-sync.cmd start --proxy "diachitruycap" --files "đường-dẫn-đến-file-theo-dỗi"
```
Ví Dụ
```
browser-sync.cmd start --proxy "192.168.1.12:8081" --files *.* 
```
khi truy cập từ máy local dùng địa chỉ: ```localhost:3000```
từ các máy khác mắc phải địa chỉ ```IP:3000```
