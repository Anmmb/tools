# Ca
```git status```

trạng thái của Repo



```git status -s```
trạng thái của Repo ngắn gọn


git clone path
sao chép một Repository có địa chỉ là path
git add
cập nhật vào staged
git add filename
thêm file vào staged
git add *.c
file có phần mở rộng .c
git add -A
thêm mọi thứ có sự thay đổi (file mới, xóa file, nội dung thay đổi ...)
git add .
thêm mọi thứ trừ loại xóa file
git add -
thêm mọi thứ trừ file mới
git commit -m "Thông báo ..."
commit mới
git commit --amend -m "Thông báo ..."
commit + cập nhật vào commit cuối
git log
lịch sử commit
git log -4
lịch sử 4 commit
git log -4 -p
lịch sử 4 commit + chi tiết thay đổi
git log --pretty=oneline
Hiện thị trực quan trên 1 dòng
git log --oneline
Hiện thị trên 1 dòng
git diff
Xem sự khác biệt giữa thư mục làm việc và staged
git diff --staged
Xem sự khác biệt giữa staged và commit cuối
git rm filename
xóa file
git reset HEAD filename
hủy thay đổi của file
git checkout -- filename
khôi phục thay đổi của file
git checkout [hash] filename
khôi phục từ commit có mã hash
git checkout [hash] .
khôi phục các file từ commit có mã hash
git clean -d -fx .
Xóa các file không được theo dõi, có ích khi muốn xóa bỏ nhanh các file không được theo dõi