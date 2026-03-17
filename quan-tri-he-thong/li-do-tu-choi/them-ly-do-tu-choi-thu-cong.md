# Thêm Lý do từ chối Thủ công

## 1. Mục tiêu

* Khởi tạo các nguyên nhân cụ thể dẫn đến việc dừng quy trình tuyển dụng đối với một hồ sơ (Ví dụ: Không đạt bài test, Kỹ năng chưa phù hợp, Nội bộ thay đổi yêu cầu).
* Giúp chuẩn hóa dữ liệu đầu ra để hệ thống có thể phân tích và báo cáo về nguyên nhân thất thoát ứng viên trong kho ứng viên.

## 2. Khi nào dùng?

* Khi cần bổ sung thêm các lý do từ chối mới phát sinh theo thực tế quy trình tuyển dụng của công ty.
* Khi muốn tùy chỉnh nhanh một lý do cụ thể mà không cần can thiệp vào tệp dữ liệu lớn.

## 3. Các bước thực hiện chi tiết

### Bước 1: Mở giao diện khởi tạo:&#x20;

* Tại màn hình danh sách chính của mục Lý do từ chối, chọn nút + Tạo mới (nút màu đen nằm ở góc trên bên phải).

### Bước 2: Thiết lập thông tin chi tiết:&#x20;

<figure><img src="../../.gitbook/assets/image (324).png" alt=""><figcaption></figcaption></figure>

* Trong cửa sổ Add RejectReason, bạn tiến hành điền và chọn các thông tin sau:
  * Phân loại: Chọn nhóm lý do tương ứng từ danh sách thả xuống (Mặc định hệ thống hiển thị nhóm "Chung").
  * Tên Lý do từ chối (\*): Nhập nội dung chi tiết của lý do (Ví dụ: "Ứng viên từ chối Offer"). Đây là trường thông tin bắt buộc.
  * Trạng thái (\*): Chọn trạng thái Active (Hoạt động) để lý do này có thể áp dụng ngay lập tức khi xử lý hồ sơ.

### Bước 3: Lưu dữ liệu:&#x20;

* Kiểm tra lại nội dung vừa nhập và chọn nút Tạo mới (màu đen, góc dưới bên phải) để hoàn tất.

## 4. Kết quả mong đợi

* Lý do từ chối mới xuất hiện trong bảng danh sách chính với trạng thái Hoạt động.
* Người dùng có thể chọn lý do này trong menu thả xuống khi thực hiện thao tác từ chối ứng viên.

## 5. Lưu ý quan trọng

Đồng bộ Layout: Nếu cần bổ sung thêm màu sắc hoặc biểu tượng nhận diện cho lý do, bạn có thể chọn biểu tượng hình cây bút (Chỉnh sửa Layout) để tùy chỉnh các thuộc tính trường trước khi lưu.
