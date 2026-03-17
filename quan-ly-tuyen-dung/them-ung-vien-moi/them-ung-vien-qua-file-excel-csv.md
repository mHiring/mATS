# Thêm ứng viên qua file Excel/CSV

## 1. Mục tiêu

* Chuyển đổi nhanh chóng danh sách ứng viên từ các bảng tính (Excel/CSV) vào hệ thống quản lý tập trung.
* Đảm bảo tính thống nhất của dữ liệu khi chuyển đổi từ các nguồn khác nhau.
* Tối ưu hóa việc làm giàu kho ứng viên mà không cần qua bước bóc tách CV từng bước.

## 2. Khi nào dùng?

* Khi bạn có danh sách ứng viên từ các hội chợ việc làm, danh sách cựu nhân viên, hoặc dữ liệu mua từ các đơn vị cung cấp nhân sự.
* Khi bạn muốn chuyển đổi dữ liệu từ một phần mềm quản lý cũ sang hệ thống mới thông qua tệp xuất bản (export file).

## 3. Các bước thực hiện

### **Bước 1: Truy cập tính năng**

Bạn có hai cách để bắt đầu:

<figure><img src="../../.gitbook/assets/Screenshot 2026-03-04 145837 (1).jpg" alt=""><figcaption></figcaption></figure>

* Cách A: Tại giao diện "Tạo ứng viên", chọn ô Tải lên Excel/CSV (biểu tượng bảng tính màu xanh).
* Cách B: Tại màn hình danh sách ứng viên, nhấn vào biểu tượng Nhập dữ liệu (mũi tên hướng lên trên thanh công cụ).

### **Bước 2: Chuẩn bị file dữ liệu**

Để quá trình nhập liệu diễn ra suôn sẻ, tệp của bạn cần đạt các tiêu chuẩn sau:

* Định dạng: Chỉ sử dụng tệp có đuôi .xlsx hoặc .csv.
*   Cấu trúc: Nên có tiêu đề cột rõ ràng (ví dụ: Họ tên, Email, Số điện thoại, Vị trí ứng tuyển...).

    > _Mẹo: Bạn có thể tải file mẫu từ hệ thống (nếu có) để điền thông tin đúng chuẩn ngay từ đầu._

### **Bước 3: Tải tệp và Đối soát dữ liệu (Mapping)**

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* Tải tệp: Kéo và thả tệp từ máy tính vào vùng nhận diện của hệ thống.
* Đối soát cột (Mapping): Đây là bước quan trọng nhất. Bạn cần chọn các trường dữ liệu tương ứng trên hệ thống để khớp với cột trong file Excel.
  * _Ví dụ: Khớp cột "Full Name" trong file với trường "Họ và tên" trên phần mềm._
* Kiểm tra dữ liệu: Hệ thống sẽ tự động quét toàn bộ tệp để phát hiện các lỗi như: Trùng Email, sai định dạng Số điện thoại hoặc thiếu các thông tin bắt buộc.

### **Bước 4: Hoàn tất nhập liệu**

* Sau khi kiểm tra và xác nhận không còn lỗi, nhấn \[Xác nhận/Nhập dữ liệu].
* Hệ thống sẽ chạy tiến trình nạp dữ liệu hàng loạt. Bạn có thể theo dõi tiến độ xử lý tại bảng lịch sử tương tự như khi tải nhiều CV.

## 4. Kết quả

* Toàn bộ danh sách ứng viên trong file được khởi tạo hồ sơ thành công trong kho ứng viên.
* Các thông tin liên hệ và phân loại nguồn được cập nhật chính xác theo đúng bảng tính.
* Hệ thống tự động loại bỏ hoặc cảnh báo các dòng dữ liệu trùng lặp (tùy theo thiết lập của bạn).

## <mark style="color:$primary;">5. Lưu ý quan trọng</mark>

* <mark style="color:$primary;">Kiểm tra trùng lặp: Hãy chú ý các cảnh báo về Email và Số điện thoại để tránh tạo ra các bản ghi trùng lặp trong kho ứng viên.</mark>
* <mark style="color:$primary;">Định dạng ngày tháng: Đảm bảo định dạng ngày tháng trong file Excel (Ngày sinh, Ngày ứng tuyển) đồng nhất với định dạng của hệ thống để tránh lỗi hiển thị.</mark>
* <mark style="color:$primary;">Số lượng dòng: Đối với các file có hàng nghìn dòng dữ liệu, quá trình xử lý có thể mất vài phút. Bạn nên theo dõi cột "Trạng thái" để chắc chắn mọi hồ sơ đều được nhập thành công.</mark>
