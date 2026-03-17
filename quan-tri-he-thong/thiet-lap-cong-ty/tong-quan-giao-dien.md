# Tổng quan giao diện

## 1. Giao diện Danh sách Công ty&#x20;

Đây là màn hình chính giúp bạn quản lý tập trung toàn bộ thông tin các đối tác hoặc đơn vị thành viên.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-02 153249.jpg" alt=""><figcaption></figcaption></figure>

### A. Công cụ Tìm kiếm và Bộ lọc

* Tìm kiếm: Nhập tên hoặc mã định danh để truy xuất nhanh công ty.
* Trạng thái: Lọc danh sách theo tình trạng Đang hoạt động hoặc Không hoạt động.
* Nhóm công cụ tùy chỉnh (Góc phải):
  * Làm mới (↻): Cập nhật dữ liệu tức thì.
  * Bộ lọc & Sắp xếp: Tối ưu hiển thị theo nhu cầu quản trị.
  * Cột: Tùy chỉnh ẩn/hiện các trường thông tin trên bảng.
  * Dấu ba chấm (...): Chứa chức năng Nhập dữ liệu (Import) và Xuất dữ liệu (Export) giúp đồng bộ nhanh từ file Excel.

### B. Bảng dữ liệu chính

Hiển thị danh sách các đơn vị đã tạo với các thông tin như ID, Tên, Địa chỉ và Trạng thái. Nếu công ty có cấu trúc phân cấp, bạn có thể thấy biểu tượng mở rộng để xem các đơn vị thành viên.

## 2. Giao diện Thêm mới Công ty

Nhấn nút \[+ Tạo mới] để bắt đầu. Hệ thống cung cấp hai phương thức: Nhập thủ công hoặc Sử dụng Trí tuệ nhân tạo (AI).

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-02 154453.jpg" alt=""><figcaption></figcaption></figure>

### A. Tính năng đột phá: Tạo hồ sơ bằng AI

Đây là cách nhanh nhất để khởi tạo dữ liệu mà không cần gõ phím nhiều.

* Cách thực hiện: Nhấn vào biểu tượng vi mạch (AI) ở góc trên cùng bên phải cửa sổ.
* Thao tác: Nhập URL trang web của doanh nghiệp vào ô "Địa chỉ Website" (Ví dụ: `https://company.com`).
* Kết quả: Nhấn \[Tạo], AI sẽ tự động quét thông tin từ website để điền vào các trường như Tên công ty, Website, Ngành nghề, và Mô tả tổng quan.

### B. Nhập liệu chi tiết (Thủ công)

Nếu không dùng AI, bạn có thể hoàn thiện hồ sơ qua các trường thông tin sau:

| **Trường thông tin** | **Loại** | **Chi tiết**                                                        |
| -------------------- | -------- | ------------------------------------------------------------------- |
| Logo                 | Ảnh      | Nhấn để tải logo đại diện.                                          |
| Mã công ty (\*)      | Bắt buộc | Hệ thống tự sinh mã, có thể tùy chỉnh theo quy tắc riêng.           |
| Tên công ty (\*)     | Bắt buộc | Nhập tên pháp lý đầy đủ của công ty.                                |
| Parent Company       | Lựa chọn | Chọn đơn vị cha cũ (nếu có) để thiết lập sơ đồ tổ chức.             |
| Ngành nghề & Website | Văn bản  | Lĩnh vực hoạt động và liên kết trang web chính thức.                |
| Địa chỉ công ty      | Văn bản  | Ghi nhận trụ sở chính hoặc địa điểm làm việc.                       |
| Quy mô & Trạng thái  | Lựa chọn | Xác định kích cỡ doanh nghiệp và đặt trạng thái Active (Hoạt động). |
| Là nhóm              | Checkbox | Tích chọn nếu thực thể này đóng vai trò là một nhóm/tập đoàn.       |
| Tổng quan            | Văn bản  | Mô tả chi tiết về công ty để hỗ trợ việc lọc trong kho ứng viên.    |

