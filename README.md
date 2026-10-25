# Hệ Thống Quản Lý Tài Sản
**Mã SV:** DCT24200657
**Họ tên:** Đào Quang Minh

## Mô tả dự án
Triển khai hệ thống quản lý tài sản với các thành phần:
- Web giao diện chính (Nginx Reverse Proxy)
- Cơ sở dữ liệu + phpMyAdmin
- Giám sát: Prometheus + Grafana
- Log tập trung: Loki + Promtail
- Bảo mật & tối ưu hệ thống

## Cách chạy hệ thống
```bash
# Khởi động toàn bộ dịch vụ
docker compose up -d

# Kiểm tra trạng thái
docker compose ps

# Xem log
docker compose logs -f