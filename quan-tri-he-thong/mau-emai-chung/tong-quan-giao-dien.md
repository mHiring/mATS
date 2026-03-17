# Tổng quan giao diện

Tính năng này cho phép bạn tạo, quản lý và chuẩn hóa các mẫu email gửi cho ứng viên hoặc thông báo nội bộ, giúp tối ưu hóa quy trình giao tiếp.

<figure><img src="../../.gitbook/assets/image (68).png" alt=""><figcaption></figcaption></figure>

#### 1. Quản lý danh sách Mẫu Email (Giao diện chính)

Tại màn hình danh sách mẫu email, bạn có thể thực hiện các thao tác nhanh:

* Tìm kiếm & Lọc:
  * Template Name: Tìm nhanh theo tên mẫu.
  * Template Type: Lọc theo loại email (ví dụ: `confirm-email`, `invited-email`, `reject-email`, `other-email`).
  * Using unit: Lọc mẫu email theo đơn vị/phòng ban sử dụng (như Khối Back-Office, Phòng Hành chính - Nhân sự...).
* Tùy chỉnh hiển thị: Sử dụng nút Cột để ẩn/hiện các thông tin cần thiết hoặc Sắp xếp để ưu tiên các mẫu hay dùng.
* Trạng thái: Theo dõi mẫu nào đang Hoạt động để sử dụng.

#### 2. Tạo mới Mẫu Email

Để tạo một mẫu mới, nhấn nút \[+ Tạo mới] ở góc trên bên phải.

* Thông tin cơ bản:
  * Tên phiếu đánh giá: Đặt tên gợi nhớ cho mẫu (Ví dụ: Thư mời phỏng vấn vị trí Marketing).
  * Loại: Chọn phân loại email để hệ thống tự động gợi ý đúng ngữ cảnh (Mời phỏng vấn, Từ chối, Nhận việc...).
  * Tiêu đề: Nhập tiêu đề email mà ứng viên sẽ nhận được.
* Thiết kế Nội dung (Trình soạn thảo chuyên sâu):
  * Bạn có thể soạn thảo văn bản thuần túy hoặc sử dụng trình kéo thả HTML.
  * Email Templates (Bên phải): Sử dụng các khung mẫu có sẵn như _Mời phỏng vấn, Nhận việc, Cảm ơn sau phỏng vấn, Từ chối ứng viên, Gửi bài test..._
  * ATS Blocks: Chèn các thành phần chuẩn hóa như _Layout chuẩn Email, ATS Header, Lời chào, Thông tin công việc._
* Ghi chú: Thêm các lưu ý nội bộ về cách dùng mẫu này.
* Lưu: Nhấn nút \[Lưu] để hoàn tất.

#### 3. Xuất và Nhập dữ liệu (Export/Import)

Nếu bạn cần quản lý số lượng lớn mẫu email hoặc chuyển dữ liệu giữa các hệ thống:

* Xuất dữ liệu (Export):
  * Chọn định dạng (Excel).
  * Tích chọn các trường thông tin cần xuất như: _Template ID, Tên mẫu, Chủ thể, Template Type, Bộ phận, Nội dung HTML, CSS..._
* Nhập dữ liệu (Import):
  * Chọn bảng đích (ví dụ: MBW ATS).
  * Tải lên tệp dữ liệu tương ứng để cập nhật hàng loạt mẫu email vào hệ thống.

***

#### Một số mẹo nhỏ cho bạn:

* Phân loại đúng: Luôn chọn đúng `Template Type` để khi gửi email cho ứng viên trong kho ứng viên, hệ thống sẽ lọc ra đúng mẫu bạn cần nhanh nhất.
* Sử dụng Layout chuẩn: Khi soạn nội dung, hãy bắt đầu bằng việc kéo `Layout chuẩn Email` từ cột bên phải vào để đảm bảo email hiển thị đẹp trên cả điện thoại và máy tính.
