# UTH Budget

Web quản lý thu chi sinh viên bằng tiếng Việt, chạy bằng HTML, CSS và JavaScript thuần.

## Chạy cục bộ

```sh
cd /workspace/UTH-BUDGET
python3 -m http.server 3000 --bind 0.0.0.0
```

Mở cổng 3000 bằng công cụ xem trước của môi trường. Không cần cài thư viện hoặc build.

## Chức năng

- Tổng quan thu nhập, chi tiêu, số dư trong kỳ và tỷ lệ tiết kiệm.
- Thêm/xóa giao dịch; tìm kiếm, lọc theo loại và tháng.
- Thiết lập ngân sách tháng theo danh mục và theo dõi mức sử dụng.
- Biểu đồ dòng tiền, phân bổ chi tiêu và xuất báo cáo CSV.
- Giao diện thích ứng điện thoại và máy tính.

Lần đầu mở không có giao dịch; mọi số dư và hạn mức ngân sách đều bằng 0. Có nút xóa toàn bộ dữ liệu để bắt đầu lại. Dữ liệu được lưu bằng localStorage trên trình duyệt hiện tại, chưa đồng bộ giữa thiết bị và chưa có đăng nhập. Dữ liệu có thể mất khi xóa dữ liệu trình duyệt; dùng xuất CSV để lưu bản sao báo cáo. Font Google là tùy chọn; khi không có mạng, giao diện dùng font hệ thống.
