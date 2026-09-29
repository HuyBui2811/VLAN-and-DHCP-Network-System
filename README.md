# VLAN-and-DHCP-Network-System
Thiết kế và triển khai hệ thống mạng VLAN và DHCP cho văn phòng đa chi nhánh
## Mô tả

Đồ án xây dựng mô hình mạng doanh nghiệp gồm trụ sở chính tại Hà Nội
và hai chi nhánh tại Đà Nẵng, Thành phố Hồ Chí Minh.

Hệ thống được mô phỏng trên Cisco Packet Tracer và triển khai các công nghệ:

- VLAN
- DHCP
- Inter-VLAN Routing
- Router-on-a-Stick
- OSPF
- ACL
- Cisco ASA Firewall
- NAT/PAT

## Kiến trúc hệ thống

- Trụ sở chính: Hà Nội
- Chi nhánh: Đà Nẵng
- Chi nhánh: Thành phố Hồ Chí Minh
- Kết nối giữa các chi nhánh: WAN và OSPF
- Phân chia mạng: VLAN
- Cấp phát địa chỉ: DHCP
- Kiểm soát truy cập: ACL
- Bảo vệ kết nối Internet: Cisco ASA Firewall và NAT/PAT

## Địa chỉ mạng

| Khu vực | VLAN | Network |
|---|---:|---|
| Hà Nội – IT | 10 | 192.168.10.0/24 |
| Hà Nội – Kế toán | 20 | 192.168.20.0/24 |
| Hà Nội – Nhân sự | 30 | 192.168.30.0/24 |
| Hà Nội – Server | 50 | 192.168.50.0/24 |
| Đà Nẵng – Kinh doanh | 110 | 192.168.110.0/24 |
| Đà Nẵng – Kế toán | 120 | 192.168.120.0/24 |
| TP.HCM – Kinh doanh | 210 | 192.168.210.0/24 |
| TP.HCM – Nhân sự | 220 | 192.168.220.0/24 |

## Công cụ

- Cisco Packet Tracer
- Microsoft Word
- GitHub
