# pfsense-2.7.2-RELEASE(amd64)
pfsense-lab

Danh sách bài Lab pfSense từ cơ bản đến nâng cao

📦 Phần 1: Cơ bản (Beginner)

1-	  Cài đặt pfSense trên Proxmox, VirtualBox hoặc VMware    ->Làm quen cài đặt, cấu hình ban đầu

2-	  Cấu hình WAN & LAN, NAT mặc định	                      ->Kết nối internet, cấp IP cho client

3-	  Đổi IP LAN và cấu hình DHCP Server	                    ->Thực hành phân phối IP nội bộ

4-	  Tạo firewall rule cơ bản (cho/block ICMP, HTTP)	        ->Làm chủ cơ chế lọc gói

5-	  Cấu hình DNS Resolver/Forwarder	                        ->Quản lý truy vấn DNS qua pfSense

6-	  Sao lưu & khôi phục cấu hình	                          ->Backup định kỳ và khôi phục hệ thống

🔐 Phần 2: Bảo mật & Firewall

7-	  Cấu hình firewall rules nâng cao	                      ->Lọc theo IP, port, time-based rule

8-	  Block truy cập theo quốc gia (GeoIP) với pfBlockerNG	  ->Cài và cấu hình pfBlockerNG

9-	  IDS/IPS với Snort hoặc Suricata	                        ->Phát hiện và ngăn chặn tấn công

10-	Tạo alias IP/group và áp dụng vào rules	                ->Tối ưu quản lý firewall rule

11-	Port Forwarding (camera, web server)	                  ->NAT 1:1, NAT port range

🌐 Phần 3: Dịch vụ mạng (Network Services)

12-	Captive Portal	                                        ->Đăng nhập mạng bằng trang web

13-	Cấu hình Multi-WAN (failover và load balancing)	        ->Internet dự phòng, phân tải băng thông

14-	Static Routing giữa 2 mạng LAN	                        ->Routing cơ bản

15-	Dynamic Routing (OSPF qua FRR package)	                ->Học OSPF dùng FRR

16-	DHCP Relay & DNS over TLS	                              ->Tăng bảo mật dịch vụ mạng

🧱 Phần 4: VPN

17-	OpenVPN: Client-to-Site	                                ->Cho người dùng kết nối từ xa

18-	OpenVPN: Site-to-Site	                                  ->Kết nối 2 văn phòng

19-	IPsec VPN: Site-to-Site	                                ->Dùng IPsec thay OpenVPN

20-	WireGuard VPN (mới, nhanh, nhẹ)	                        ->Cấu hình VPN hiệu năng cao

21-	L2TP/IPsec cho client mobile	                          ->Hỗ trợ thiết bị không cài phần mềm VPN riêng

🧭 Phần 5: VLAN, Routing & Enterprise

22-	Cấu hình VLAN trên pfSense & switch	                    ->Mạng nội bộ tách biệt bảo mật

23-	Routing giữa VLAN	                                      ->Cho phép VLAN giao tiếp an toàn

24-	Lọc truy cập giữa VLAN bằng firewall rule	              ->Kiểm soát chéo VLAN

25-	QinQ (VLAN trong VLAN)	                                ->Triển khai mạng doanh nghiệp lớn

26-	Bridge mode giữa 2 interface	                          ->Cầu nối mạng hoặc IDS bridge

📈 Phần 6: Monitoring, Logging & Hiệu suất

27-	Traffic Graph & Bandwidth Monitoring	                  ->Xem real-time lưu lượng

28-	Sử dụng ntopng để theo dõi lưu lượng chi tiết	          ->Xem top IP/port/dịch vụ

29-	Cảnh báo log qua email	                                ->Log hệ thống gửi mail khi có sự kiện

30-	Giới hạn băng thông bằng Limiter	                      ->QoS cơ bản

31-	Tối ưu hóa cấu hình pfSense	                            ->Phân tích và tinh chỉnh hiệu suất

🔄 Phần 7: Khôi phục & HA (High Availability)

32-	Backup tự động lên cloud/local	                        ->Dùng cron hoặc gắn NAS

33-	Cấu hình CARP (Cluster failover)	                      ->Dự phòng firewall tự động

34-	Đồng bộ cấu hình giữa 2 pfSense	                        ->XML config sync

35-	Cài đặt pfSense trên phần cứng thật	                    ->Dự án triển khai thực tế















