# Tổng quan giao diện

## I. GIAO DIỆN DANH SÁCH CHÍNH

<figure><img src="../../.gitbook/assets/image (310).png" alt=""><figcaption></figcaption></figure>

Màn hình này hiển thị tất cả các cấp độ hiện có trong hệ thống với các cột thông tin:

* ID cấp bậc: Mã định danh của cấp độ (ví dụ: LV1, LV2...).
* Tên cấp bậc: Tên gọi cụ thể (ví dụ: Thực tập sinh, Chuyên viên...).
* Sử dụng Đơn vị: Hiển thị đơn vị đang áp dụng cấp bậc này.
* Trạng thái: Hiển thị dưới dạng thẻ màu (Hoạt động/Ngừng hoạt động).
* Sửa đổi lần cuối: Ghi lại thời gian chi tiết lần cập nhật cuối cùng.

## II. QUY TRÌNH THAO TÁC CHI TIẾT

### A. Thêm mới Cấp bậc / Trình độ

<figure><img src="../../.gitbook/assets/image (311).png" alt=""><figcaption></figcaption></figure>

1. Tại màn hình danh sách, chọn nút + Tạo mới (màu đen, góc trên bên phải).
2. Trong cửa sổ Add Level, điền các thông tin:
   * Mã cấp bậc (\*): Hệ thống tự động gợi ý mã (ví dụ: `LVL_2026...`), bạn có thể chỉnh sửa lại.
   * Tên cấp bậc (\*): Nhập tên của cấp độ/trình độ.
   * Mô tả: Nhập thông tin chi tiết giải thích cho cấp độ này.
   * Bộ phận: Chọn bộ phận tương ứng từ danh sách thả xuống.
3. Chọn nút Tạo mới để lưu.

### B. Quản lý Nhập và Xuất dữ liệu

Tính năng này nằm trong menu mở rộng (biểu tượng `...` cạnh nút Cột):

* Nhập dữ liệu (Import):
  * Vào menu `...` -> chọn Nhập dữ liệu.
  * Tại màn hình Nhập dữ liệu, nếu chưa có dữ liệu, hệ thống báo "Không tìm thấy dữ liệu". Chọn nút + Thêm nhập dữ liệu để tải file từ máy tính lên hệ thống.
* Xuất dữ liệu (Export):
  * Vào menu `...` -> chọn Xuất dữ liệu.
  * Trong cửa sổ hiện ra: Chọn định dạng (Excel), tích chọn vào ô "Xuất tất cả bản ghi" hoặc chọn từng trường cụ thể (Mã cấp bậc, Tên cấp bậc, Mô tả, Trạng thái, Thứ tự, Biểu tượng...).
  * Chọn nút Tải xuống.

### C. Tùy chỉnh và Hiệu chỉnh hệ thống

* Chỉnh sửa/Xóa: Tại mỗi dòng dữ liệu, chọn biểu tượng 3 chấm dọc để mở menu phụ, sau đó chọn Chỉnh sửa để thay đổi thông tin hoặc Xóa để gỡ bỏ.
* Chỉnh sửa Bố cục (Layout): Trong cửa sổ Add Level, chọn biểu tượng hình cây bút. Tại đây bạn có thể:
  * Kéo thả các trường dữ liệu (Level ID, Level Name, Level Description, Using Unit...).
  * Thêm Tab hoặc thêm các trường thông tin mới bằng nút + Thêm trường.
  * Nhấn Lưu để áp dụng thay đổi cho giao diện nhập liệu.
*   Cấu hình bảng danh sách:

    * Bộ lọc: Sử dụng để lọc nhanh theo Tên hoặc Trạng thái.
    * Sắp xếp: Đảo chiều hiển thị danh sách.
    * Cột: Tích chọn các cột muốn hiển thị hoặc ẩn đi trên màn hình

