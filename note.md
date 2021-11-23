# Terms

- Repository (Repo)
- Branch
- Conflict: Xung đột
- Local
- Remote

# Commands

- Git init: Thêm dự án thành repository
- Git Status: Xem trang thái của dự án
- Git add: để chuẩn bị lưu lại file đó
- Git add .: để chuẩn bị lưu tất cả các file
- Git reset: Không chuẩn bị lưu nữa
- Git commit: Lưu file lên github
- Git log: Xem lại thời điểm các commit
- Git log --oneline: giống git log và gọn hơn
- Git checkout id: trở lại commit trước đó
  vd: git checkout 406917e trở lại commit 406917e
- Git checkout {brand name} : để trở lại hiện tại
  vd: git checkout master
- Git branch: Xác định Branch
- Git checkout -b {Branch name}: Thoát branch cũ và vào branch mới
- Git merge {branch name}: Tổng hợp branch hiện tại với branch name
  vd : git merge dev
- Git branch -d {branch name}: xóa đi branch name
  vd: git branch -d dev
- Git push: Đẩy dự án lên repository
  vd : git push https://github.com/SUNVToan/Git-control.git master
- Git remote add {name elient} tutorial link: tạo a name elient thay cho đường hướng dẫn
  vd: git remogitte add origin https://github.com/SUNVToan/Git-control.git
- Git clone: lấy dự án trên repository về máy
- git push --set-upstream origin master : khi chúng ta git push thì sẽ code sẽ tự cập nhật lên repository || Giống với khi chúng ta lấy dự án bằng git clone về máy và sử dụng.
  vd : git push origin dev : đưa nhánh lên repository, sau khi đưa nhánh lên bằng origin thì lần sau chỉ cần dùng lệnh git push
- Git fetch origin : tìm những branch mới trên repository
- git checkout -b staging origin/staging : để clone nhánh staging về máy
