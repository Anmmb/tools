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
- Vao thu muc 
- Go lenh ```http-server``` hoac ```http-server.cmd```
- Mac dinh dinh cong truy cap la 8080
- Neu muon thay doi cong thi them tham so ```-p PORT``` vi du ```http-server -p 8081```
- Truy cap may chu bang ```http:://localhost:port``` hoac ```http://127.0.0.1:oort``` hoac bang dia chi IP cua may ```http://IP:port```
- Cac may cung mang thi truy cap bang IP: ```http://IP:port```

## browser-sync (https://browsersync.io/)
**browser-sync** la cong cu dong bo trinh duyet cho muc dich kiem thu.
- Cai dat
```
npm install -g browser-sync
```
- Chay browser-sync: Chay browser-sync nhu la proxy

```
browser-sync start --proxy "diachitruycap" --files "duong-dan-den-file-theo-doi"
```
hoac trong PowserShell
```
browser-sync.cmd start --proxy "diachitruycap" --files "duong-dan-den-file-theo-doi"
```
Vi du
```
browser-sync.cmd start --proxy "192.168.1.12:8081" --files *.* 
```
Khi truy cap tu may local dung dia chi: ```localhost:3000```
Tu cac may khac trong mac phai dia chi ```IP:3000```
