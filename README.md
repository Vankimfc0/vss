Như các bài viết trước của mình chia sẻ file để sử dụng internet viettel miễn phí tốc độ rất chậm nên nay mình mod lại để cải thiện tốc độ internet
Phiên bản này mình mod lại tại nguồn https://github.com/aztecrabbit/brainfuck-psiphon-pro-go
Các tính năng của phiên bản Psiphon đường hầm Brainfuck
Sử dụng trạng thái ngẫu nhiên làm trình kích hoạt kết nối (mặc định) nhưng có thể được đặt thành cấu hình
Kết nối lại sau khi đạt 4,2 MB (mặc định) để cải thiện tốc độ.

#####Cài đặt như sau:
B1" mở Termux (link tải https://f-droid.org/packages/com.termux/ ) chạy lệnh sau:
"pkg install git && git clone https://github.com/Vankimfc0/vss.git && clear && cd vss && chmod a+x tun && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/vss"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/vss"' >> $HOME/.zshrc && source $HOME/.zshrc && clear && cd"
***
B2 mở app SocksDroid (link tải https://play.google.com/store/apps/details?id=net.typeblog.socks&pcampaignid=web_share )kéo xuống dưới cùng tích vào 2 ô per-app proxy và bypass mode ,dòng app list nhập là com.termux

####Sử dụng
B1 -mở app Termux gõ lệnh: tun
để kết nối tới đường hầm
B2 - mở app SocksDroid nhấp gốc phải màn hình để kết nối


Xin lưu ý: Phương pháp VPN này rất chậm ∆

một giao thức chống kiểm duyệt, mã hóa lưu lượng dưới dạng các yêu cầu và phản hồi HTTP đơn giản. Điều này cho phép lưu lượng truy cập thâm nhập vào các môi trường mà nếu không nó sẽ bị chặn.

Hiệu suất của nó là thấp. Nó không dành cho các tình huống mà bạn muốn ping nhanh hoặc truyền hàng gigabyte và gigabyte dữ liệu.
