
# Dự án Trung tâm Tiếng Anh

## Giới thiệu dự án
Đây là **mã nguồn quản lý** dữ liệu và học phí dành cho *trung tâm tiếng anh*.

## Cấu trúc thư mục

| Thư mục | Nội dung |
| --- | --- |
| `data/` | Chứa các file Excel quản lý khóa học và học phí |
| `logs/` | Chứa các file log hệ thống (access.log, payment.log) |
| `docs/` | Chứa tài liệu hướng dẫn và báo cáo |

## Quy trình đăng ký học tại TTA
1. Chọn khóa học phù hợp tại sheet Khoa_Hoc.
2. Điền thông tin đăng ký vào sheet Dang_Ky.
3. Thanh toán học phí và nhận xác nhận từ trung tâm.

## Lệnh kiểm tra cấu trúc dự án
```powershell
Get-ChildItem -Recurse
```
## Danh sách công việc

-   [x] Khởi tạo cấu trúc thư mục dự án
    
-   [ ] Lọc báo cáo lỗi trong file log
> **Lưu ý:** Không upload file .env lên repository.
