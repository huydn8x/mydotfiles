# my dot files
### vim wiki:

- các phím di chuyển
  - trái: h
  - phải: l
  - xuống: j
  - lên: k
- chuyển con trỏ về cuối dòng: $
- chuyển con trỏ về đầu dòng: 0
- di chuyển đến cuối dòng và chuyển mode insert: shift + a
- w: nhẩy ra khỏi word
- e: nhẩy đến chữ cuối của word
- bôi đen một đoạn: 
  - relative chỉ con trỏ đến điểm cần bôi + v + line k (lên) line j (xuống)
  - line number chỉ con trỏ + v + line gg
- bôi đen xong muốn copy (command mode): y
- paste chỗ vừa chọn (command mode): p
- ctrl + z thoát vim tạm thời
- fg: vào vim code tiếp
- highlight keyword dc chọn: trỏ chuột vào xong shift + # 
- Bỏ highlight, command mode: :nohlsearch
- nhân đôi cửa sổ: ctrl + w + v
- tìm và thay thế: :%s/search/replace/g (có thể dùng regex vd: :%s/UserFav\./Follow\./g)
- xóa từ đằng sau: db (delete back)
- xóa từ đằng trc: de
- muốn ctrl + s để save trên vim 7 thì cho cái này vào .bashrc xong source lại file là dc: stty -ixon
- h: help
- q: quit everything
- bôi đen + shift + > : dịch sang phải 1 tab
- shift + a : dịch cửa sổ code về bên phải hoặc trái
- undo: u
- redo: ctrl + u
- copy 1 dòng ko cần bôi đen: trỏ chuột vào xong yy
- di chuyển đến chỗ cần paste và ấn p
- c + w: change word, xóa chữ ngay con trỏ
- shift + c: xóa từ con trỏ đến cuối, tương tự d + $
- shift + v: bôi đen từ đầu đến cuối
- tạo file mới: m + ...
- bôi đen theo hàng dọc: ctrl + v, bôi hàng dọc xong muốn xóa thì d, xong muốn viết text hàng loạt thì shift + i, viết xong ấn escape 2 lần là nó apply cho tất cả hàng dọc mà mình chọn
- :table [tên file] : mở file bằng tab mới, nếu muốn chuyển thì ấn g+t
- xóa từ con trỏ đến hết dòng: d + shift + $

### Cách dùng tmux:

- ra bash: ctrl + b + c
- mở tác vụ khác dc lưu: ctrl + b + số