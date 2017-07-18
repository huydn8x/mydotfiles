# My dot files

### Install vim:

```
cd ~
wget https://raw.githubusercontent.com/huydn8x/mydotfiles/master/vimrc
mv vimrc .vimrc
vim // auto install in first time
vim // manual install type command :PluginInstall
```

### Vim wiki:

- các phím di chuyển
  - trái: h
  - phải: l
  - xuống: j
  - lên: k
- chuyển con trỏ về cuối dòng: $
- chuyển con trỏ về đầu dòng: 0
- di chuyển lên đầu file: gg
- di chuyển xuống cuối file: shift + g
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
- nhân bản cái vừa gõ ra nhiều dòng: ctrl + v để chọn dọc số dòng muốn append, sau đó shift + i để insert mode -> gõ comment hoặc gì đó -> esc 2 lần là ok
- cú pháp kết hợp với phím i:
   - c + i + [ký tự bao ngoài word muốn thay đổi]. for example: c+i+' = change in ' => đổi text trong dấu '
   - Y + i + [ký tự bao ngoài word muốn copy]. for example: Y+i+' = copy in ' => copy text trong cụm dấu '
   - ..etc...cái gì cũng kết hợp dc với + i

### Cách dùng tmux:

- ra bash: ctrl + b + c
- mở tác vụ khác dc lưu: ctrl + b + số