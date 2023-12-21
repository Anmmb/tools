# Mot so cong cu lam viec

## Cai dat Node JS
Tai ve tu Nodejs.org

## Kiem tra node js
```node -v``` kiem tra phien ban node js
```npm -v``` kiem tra phien phien ban cua NPM (node package manager)


## Tao may chu HTTP don gian bang package: **http-server**
Cai dat
```
npm install --global http-server
```

Tao may chu HTTP tren thu muc
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
