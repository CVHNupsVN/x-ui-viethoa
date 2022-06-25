# x-ui-viethoa
x-ui cho phép người dùng chỉnh sửa cấu hình của xray

# Ưu điểm:

- Thân thiện, dễ sử dụng với giao diện người dùng web.
- Có thể theo dõi tình trạng hệ thống.
- Hỗ trợ nhiều giao thức: vmess, vless, trojan, shadowsocks, dokodemo-door, socks, http.
- Hỗ trợ cấu hình nhiều cấu hình hơn.
- Thống kê tổng dung lượng đã sử dụng, giới hạn dung lượng, giới hạn thời gian của cấu hình.
- Hỗ trợ chứng chỉ SSL và gia hạn tự động.
- Và còn nhiều chức năng khác.

# Lệnh cài đặt (thủ công):

```
cd /root/
tar zxvf x-ui-linux-amd64.tar.gz
chmod +x x-ui/x-ui x-ui/bin/xray-linux-* x-ui/x-ui.sh
cp x-ui/x-ui.sh /usr/bin/x-ui
cp -f x-ui/x-ui.service /etc/systemd/system/
mv x-ui/ /usr/local/
systemctl daemon-reload
systemctl enable x-ui
systemctl restart x-ui
```

# Yêu cầu hệ thống:

- CentOS 7+
- Ubuntu 16+
- Debian 8+

# Repo gốc (tiếng Trung): [x-ui](https://github.com/vaxilu/x-ui/)
