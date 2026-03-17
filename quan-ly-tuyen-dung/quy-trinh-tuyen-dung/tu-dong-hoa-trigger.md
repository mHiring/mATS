# Tự động hóa Trigger

## 1. Mục tiêu

Giúp nhà tuyển dụng tối ưu hóa hiệu suất làm việc bằng cách tự động hóa các tác vụ lặp đi lặp lại (gửi email, lên lịch hẹn, thông báo) thông qua việc chuyển đổi trạng thái ứng viên trong quy trình.

## 2. Khi nào sử dụng?

* Khi cần gửi thư mời phỏng vấn hoặc thông báo kết quả hàng loạt cho ứng viên.
* Khi muốn thông báo ngay lập tức cho hội đồng tuyển dụng khi có ứng viên tiềm năng vào vòng mới.
* Khi cần chuẩn hóa các bước phản hồi ứng viên trong kho ứng viên để đảm bảo tính chuyên nghiệp.

## 3. Các bước thực hiện

### Bước 1: Truy cập quản lý quy trình

* Tại danh sách tin tuyển dụng, chọn tin cần thao tác (Ví dụ: Tuyển dụng Frontend Developer).
* Chuyển sang tab Ứng viên để thấy các cột quy trình đã thiết lập.

### Bước 2: Lựa chọn chế độ hiển thị phù hợp

<figure><img src="../../.gitbook/assets/image (308).png" alt=""><figcaption></figcaption></figure>

* Chế độ Kanban: Nhấn biểu tượng thẻ để xem ứng viên dưới dạng các cột (Review, Sàng lọc, Phỏng vấn...). Chế độ này tối ưu cho việc quan sát luồng di chuyển.

<figure><img src="../../.gitbook/assets/image (309).png" alt=""><figcaption></figcaption></figure>

* Chế độ Danh sách: Nhấn biểu tượng bảng để xem chi tiết thông tin liên hệ và ngày ứng tuyển của từng người.

### Bước 3: Thực hiện chuyển vòng để kích hoạt Trigger

* Cách 1 (Kéo thả): Tại chế độ Kanban, nhấn giữ thẻ ứng viên và kéo từ bước hiện tại sang bước kế tiếp.
* Cách 2 (Nút thao tác): Tại chế độ Danh sách, nhấn biểu tượng mũi tên 4 chiều ở cột Hành động và chọn bước quy trình muốn chuyển đến.

### Bước 4: Kiểm tra sự kiện thực thi tự động

* Ngay khi ứng viên được thả vào bước mới, hệ thống nhận diện sự kiện "Khi có ứng viên vào bước này".
* Theo dõi các hành động tự động diễn ra như: Email thông báo được gửi đi hoặc lịch phỏng vấn được khởi tạo trên hệ thống.

## 4. Kết quả mong đợi

* Trạng thái ứng viên được cập nhật chính xác theo thời gian thực.
* Các tác vụ phụ trợ (gửi thư, thông báo) được thực hiện tự động và chính xác, không cần thao tác thủ công.
* Giảm thiểu sai sót và rút ngắn thời gian phản hồi ứng viên.

## <mark style="color:$primary;">5. Lưu ý quan trọng</mark>

* <mark style="color:$primary;">Cấu hình trước: Trigger chỉ hoạt động nếu quy trình tuyển dụng đã được thiết lập các hành động tự động từ trước. Hãy rà soát lại cài đặt của từng bước nếu Trigger không chạy.</mark>
* <mark style="color:$primary;">Kiểm tra thông tin: Trước khi chuyển vòng (đặc biệt là vòng Gửi Đề nghị hoặc Từ chối), hãy đảm bảo hồ sơ ứng viên đã đầy đủ thông tin liên hệ để các Trigger gửi Email không bị lỗi.</mark>
