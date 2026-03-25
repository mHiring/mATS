# Tự động hóa Trigger

## 1. Mục tiêu

Tối ưu hóa hiệu suất làm việc bằng cách tự động hóa các tác vụ lặp đi lặp lại. Khi bạn thay đổi trạng thái ứng viên, hệ thống sẽ tự động:

* Gửi Email/SMS: Thư mời phỏng vấn, thông báo kết quả, cảm ơn...
* Lên lịch hẹn: Tự động tạo sự kiện trên lịch làm việc.
* Thông báo: Gửi tin nhắn đến hội đồng tuyển dụng ngay khi có ứng viên tiềm năng vào vòng mới.

## 2. Khi nào sử dụng?

* Tuyển dụng số lượng lớn: Cần gửi thông báo hàng loạt cho ứng viên ở các giai đoạn khác nhau.
* Chuẩn hóa phản hồi: Đảm bảo mọi ứng viên đều nhận được phản hồi chuyên nghiệp và kịp thời.
* Kết nối nhóm: Khi muốn các bộ phận liên quan (Technical Lead, Manager) nhận được thông tin ứng viên ngay lập tức để đánh giá.

## 3. Các bước thực hiện

### Bước 1: Truy cập quản lý quy trình

* Tại danh sách tin tuyển dụng, chọn tin cần thao tác (Ví dụ: Tuyển dụng Frontend Developer).
* Chuyển sang tab Ứng viên để thấy các cột quy trình đã thiết lập.

### Bước 2: Lựa chọn chế độ hiển thị phù hợp

Phần mềm cung cấp hai góc nhìn linh hoạt:

<figure><img src="../../.gitbook/assets/image (308).png" alt=""><figcaption></figcaption></figure>

* Chế độ Kanban: Nhấn biểu tượng thẻ để xem ứng viên dưới dạng các cột (Review, Sàng lọc, Phỏng vấn...). Chế độ này tối ưu cho việc quan sát luồng di chuyển.

<figure><img src="../../.gitbook/assets/image (309).png" alt=""><figcaption></figcaption></figure>

* Chế độ Danh sách: Nhấn biểu tượng bảng để xem chi tiết thông tin liên hệ và ngày ứng tuyển của từng người.

### Bước 3: Thực hiện chuyển vòng để kích hoạt Trigger

Bạn có thể chuyển trạng thái ứng viên theo hai cách:

* Cách 1 (Kéo thả - Ưu tiên): Tại giao diện Kanban, nhấn giữ thẻ ứng viên và kéo từ cột hiện tại sang cột kế tiếp.
* Cách 2 (Nút thao tác): Tại giao diện Danh sách, nhấn vào biểu tượng mũi tên hoặc menu chuyển bước ở cột Hành động và chọn giai đoạn muốn chuyển đến.

### Bước 4: Kiểm tra sự kiện thực thi tự động

Ngay khi ứng viên được "thả" vào bước mới, hệ thống sẽ nhận diện sự kiện:

* Trigger kích hoạt: Các hành động đã cài đặt trước (như gửi Email) sẽ được thực hiện ngay.
* Theo dõi: Bạn có thể kiểm tra lịch sử gửi email hoặc lịch phỏng vấn vừa được khởi tạo tự động trên hệ thống.

## 4. Kết quả mong đợi

* Trạng thái ứng viên được cập nhật chính xác theo thời gian thực.
* Các tác vụ phụ trợ (gửi thư, thông báo) được thực hiện tự động và chính xác, không cần thao tác thủ công.
* Giảm thiểu sai sót và rút ngắn thời gian phản hồi ứng viên.

## 5. Lưu ý quan trọng

* Cấu hình trước: Trigger chỉ hoạt động nếu quy trình tuyển dụng đã được thiết lập các hành động tự động từ trước. Hãy rà soát lại cài đặt của từng bước nếu Trigger không chạy.
* Kiểm tra thông tin: Trước khi chuyển vòng (đặc biệt là vòng Gửi Đề nghị hoặc Từ chối), hãy đảm bảo hồ sơ ứng viên đã đầy đủ thông tin liên hệ để các Trigger gửi Email không bị lỗi.
