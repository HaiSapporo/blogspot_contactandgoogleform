# Make contact from Blogger insert into Google Form
Make contact insert into google form. 
## cac cau lenh trong git
 1. touch: tao ra file source lên để code. 
 2. code: tiến hành edit nội dung
 3. git init 
 4. git add có 2 loại git add . -> all file, git add tenfile -> chi dinh cu the 
 5. git commmit -m "noi dung message"
 6. git log  -> xem nội dung file lịch sử. 
 7. git status 

## trạng thái của file 
file unstracted: 
file chưa sửa đổi: 
modified , stagging và commited 
commited -> lên respository , dùng lệnh commit.
stagging -> dùng lệnh add thì sẽ vào stagging trước. 

## restore 
git restore tên file -> restore 1 file. 
git restore. -> restore toàn bộ.

## phục hồi theo revesion nào
git checkout mã HAD 7 ký tự đầu là là đủ. 
ví dụ: 
git checkout abcsss .
git checkout abcsss tên file 

## không theo doi file 
tao file gitignore chứa các file tạm để ko theo dõi ví dụ file build, file tạm... 

## merge commit 
commit vào commit cuối 
git commit --amend  -m nội dung 

## diff 2 mã HAD với nhau 
git diff HAD1 HAD2 

## trường hợp có nhiều brach 
thì commit xong phải xài thêm push 
