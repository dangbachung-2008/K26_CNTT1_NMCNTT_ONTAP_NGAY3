

# Dự Án Website Trung Tâm Tiếng Anh (TTA)

## Giới Thiệu
Dự án được xây dựng nhằm quản lý thông tin học viên, danh mục khóa học và lập bảng tổng hợp học phí hàng tháng cho Trung tâm Tiếng Anh (TTA).

## Cấu Trúc Thư Mục
Dưới đây là bảng mô tả cấu trúc thư mục của dự án:

| Thư mục / Tệp | Nội dung |
| :--- | :--- |
| `archive/` | Thư mục lưu trữ tài liệu cũ |
| `data/` | Lưu trữ file danh sách học viên và bảng học phí Excel |
| `docs/` | Tài liệu hướng dẫn sử dụng và vận hành |
| `logs/` | Nhật ký ghi nhận hệ thống |
| `media/` | Hình ảnh, tài nguyên truyền thông của trung tâm |

## Quy Trình Đăng Ký Học
1. Học viên đăng ký khóa học tại quầy dịch vụ hoặc hệ thống trực tuyến.
2. Bộ phận kế toán xác nhận thông tin khóa học và tính toán tổng học phí dựa trên số tháng học.
3. Học viên thanh toán học phí và nhận xác nhận nhập học.

## Thao Tác Liệt Kê Thư Mục Dự Án
Sử dụng lệnh PowerShell sau để kiểm tra danh mục tệp và thư mục trong dự án:

```powershell
Get-ChildItem -Recurse