# Kết nối

bước 1: `git init`  tạo file git trong thư mục

bước 2: `git remote add origin [link git]` // kết nối với project git trên mạng  

bước 3: `git remote -v` // kiểm tra thử kết nối được chưa  

## Chạy lên

bước 1: `git add --all`  thêm tất cả các fille vào bộ nhớ trước khi đẩy lên git

bước 2: `git status` // kiem tra chay đươc chưa  

bước 3: `git commit -m "[chức năng của file này]"` // để thêm chú thích cho file mình đang đẩy lên git

bước 4:  `git log` // ktra thử chạy commit thành công chưa 

bước 5: `gitk // kiem tra file upload lên chưa`  

bước 6: `git push origin [tên nhánh] ` "-f" đẩy file lên nhánh mình muốn  

## Xóa 
`git restore [ten file] `//quay lai phien bản cũ của file đó  

`git reset --hard [link] `// ->link nay la link cua file mà muốn nó quay lại phiên bản đó, xóa những file trước file[link] đó
