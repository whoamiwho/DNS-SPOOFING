# DNS-SPOOFING
DNS spoofer. Drops DNS responses from the router and replaces it with the spoofed DNS response
dnsspoof
DNS spoofer. Drops DNS responses before they hit the router then replaces them with the spoofed DNS response.

Usage
(python dnsspoof.py -r 192.168.0.1 -v 192.168.0.5 -d domaintospoof.com)
Spoof domaintospoof.com to point back to the attack's machine.

python dnsspoof.py -r 192.168.0.1 -v 192.168.0.5 -a -t 80.87.128.67
Spoof all DNS lookup requests to point to 80.87.128.67 (stallman.org). One can also use the -t option with the -d option to redirect just a specific domain to a specific IP rather than redirecting that domain to the attack
(
Máy đánh lừa DNS. Giảm phản hồi DNS trước khi chúng vào bộ định tuyến sau đó thay thế chúng bằng phản hồi DNS giả mạo.

Sử dụng
(python dnsspoust.py -r 192.168.0.1 -v 192.168.0.5 -d domaintospoust.com)
Giả mạo domaintospoust.com để quay lại cỗ máy của cuộc tấn công.

python dnsspoust.py -r 192.168.0.1 -v 192.168.0.5 -a -t 80.87.128.67
Giả mạo tất cả các yêu cầu tra cứu DNS để trỏ đến 80.87.128.67 (stallman.org). Người ta cũng có thể sử dụng tùy chọn -t với tùy chọn -d để chỉ chuyển hướng một tên miền cụ thể sang một IP cụ thể thay vì chuyển hướng tên miền đó sang cuộc tấn công)
