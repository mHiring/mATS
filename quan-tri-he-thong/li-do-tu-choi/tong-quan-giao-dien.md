# Tổng quan giao diện

## I. GIAO DIỆN DANH SÁCH CHÍNH

<figure><img src="../../.gitbook/assets/image (322).png" alt=""><figcaption></figcaption></figure>

Màn hình này hiển thị tất cả các lý do từ chối hiện có trong hệ thống với các cột thông tin:

* Tên lý do từ chối: Tên gọi cụ thể của nguyên nhân (ví dụ: Nội bộ thay đổi yêu cầu, Vị trí đã tuyển đủ...).
* Trạng thái: Hiển thị dưới dạng thẻ màu (Hoạt động - Active) để biết lý do có đang được áp dụng hay không.
* Thao tác: Biểu tượng 3 chấm dọc ở cuối dòng để hiệu chỉnh hoặc xóa.

***

## II. QUY TRÌNH THAO TÁC CHI TIẾT

### **1. Thêm mới Lý do từ chối**

<figure><img src="../../.gitbook/assets/image (323).png" alt=""><figcaption></figcaption></figure>

Tại màn hình danh sách, chọn nút + Tạo mới (màu đen, góc trên bên phải). Trong cửa sổ Add RejectReason, thực hiện các bước:

* Phân loại: Chọn nhóm lý do từ danh sách thả xuống (mặc định hiển thị "Chung").
* Tên Lý do từ chối (\*): Nhập nội dung lý do muốn tạo (ví dụ: Không phù hợp văn hóa).
* Trạng thái (\*): Chọn "Active" để kích hoạt hoặc trạng thái khác từ menu thả xuống.
* Chọn nút Tạo mới (màu đen, góc dưới bên phải) để lưu thông tin.

### **2. Quản lý Nhập và Xuất dữ liệu**

Tính năng này nằm trong menu mở rộng (biểu tượng ... cạnh nút Cột):

* Nhập dữ liệu (Import):
  * Vào menu ... -> chọn Nhập dữ liệu.
  * Tại màn hình cấu hình, chọn bảng dữ liệu (MBW ATS) và tải file mẫu đã điền thông tin lên hệ thống.
* Xuất dữ liệu (Export):
  * Vào menu ... -> chọn Xuất dữ liệu.
  * Trong cửa sổ hiện ra: Chọn định dạng (Excel), tích chọn "Xuất tất cả bản ghi" hoặc tích thủ công vào các trường: _Tên lý do từ chối, ID Lý do từ chối, Trạng thái, Thứ tự, Màu sắc, Biểu tượng, SyncID..._
  * Chọn nút Tải xuống.

### **3. Tùy chỉnh và Hiệu chỉnh hệ thống**

* Chỉnh sửa/Xóa: Tại mỗi dòng dữ liệu, chọn biểu tượng 3 chấm dọc để mở menu phụ, sau đó chọn Chỉnh sửa để thay đổi thông tin hoặc Xóa để gỡ bỏ.
* Chỉnh sửa Bố cục (Layout): Trong cửa sổ Add RejectReason, chọn biểu tượng hình cây bút (góc trên bên phải cạnh dấu X). Tại đây bạn có thể:
  * Kéo thả các trường dữ liệu để thay đổi vị trí hiển thị.
  * Thêm các trường thông tin mới hoặc tùy chỉnh thuộc tính trường.
  * Nhấn Lưu để áp dụng thay đổi giao diện.
* Cấu hình bảng danh sách:
  * Bộ lọc: Lọc nhanh theo Tên hoặc Trạng thái.
  * Sắp xếp: Đảo chiều danh sách hiển thị.
  * Cột: Tích chọn các cột muốn hiển thị hoặc ẩn đi (ID, Using Unit, Thứ tự, Created On...).
