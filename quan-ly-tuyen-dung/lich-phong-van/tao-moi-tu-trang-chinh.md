# Tạo mới từ trang chính

## 1. Mục tiêu

* Quản lý tập trung và khoa học toàn bộ các buổi phỏng vấn của doanh nghiệp.
* Tránh xung đột lịch trình giữa ứng viên và hội đồng tuyển dụng.
* Tự động hóa quy trình gửi thư mời, đảm bảo thông tin phỏng vấn chính xác và đồng nhất.

## 2. Khi nào dùng?

* Khi hồ sơ ứng viên trong kho ứng viên đã vượt qua vòng sàng lọc và đủ điều kiện bước vào vòng phỏng vấn/kiểm tra.
* Khi cần sắp xếp lại hoặc theo dõi mật độ các buổi phỏng vấn theo ngày, tuần hoặc tháng.

## 3. Các bước thực hiện

### **A. Sử dụng giao diện Lịch trực quan**

Trước khi tạo lịch, hãy chọn chế độ xem phù hợp tại góc trên bên phải:

* Chế độ Tháng (Month): Theo dõi tổng thể kế hoạch tuyển dụng dài hạn.
* Chế độ Tuần (Week): Quản lý chi tiết khối lượng công việc trong tuần.
* Chế độ Ngày (Day): Tập trung vào các mốc giờ cụ thể, theo dõi sát sao thời gian thực qua vạch đỏ hiển thị trên lịch.
* Bộ lọc nhanh: Sử dụng bộ lọc để phân loại lịch theo _Loại phỏng vấn_ (Online/Offline), theo tên _Ứng viên_ hoặc theo từng _Job Opening_ cụ thể.

### **B. Quy trình Tạo mới lịch phỏng vấn**

#### Bước 1: Chọn thời gian

<figure><img src="../../.gitbook/assets/Screenshot 2026-03-04 154623.jpg" alt=""><figcaption></figcaption></figure>

* Tại giao diện lịch, di chuột vào ô ngày/giờ bạn mong muốn.
* Nhấn vào dấu (+) để mở bảng thiết lập Add Schedule.

#### Bước 2: Thiết lập Chi tiết phỏng vấn (Interview Details)

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

* Thời gian: Kiểm tra lại ngày và giờ bắt đầu, nhập số phút dự kiến cho buổi làm việc tại mục Thời lượng.
* Tin tuyển dụng (Job Opening): > Lưu ý quan trọng: Đây là bước bắt buộc. Bạn phải chọn một vị trí tuyển dụng cụ thể để hệ thống kích hoạt danh sách Hội đồng và Ứng viên tương ứng ở cột bên phải.

#### Bước 3: Chọn nhân sự tham gia

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

* Hội đồng tuyển dụng: Tích chọn các thành viên sẽ tham gia đánh giá.
* Ứng viên: Nhấn "Thêm ứng viên" để chọn người từ kho ứng viên (danh sách sẽ được lọc tự động theo Job Opening đã chọn ở bước 2).

#### Bước 4: Ghi chú và Thiết lập Email thông báo

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

* Ghi chú: Nhập địa điểm văn phòng hoặc dán đường dẫn (link) phỏng vấn trực tuyến.
* Thông báo qua Email:
  * Chọn Mẫu Email phù hợp (ví dụ: Thư mời phỏng vấn).
  * Kiểm tra nội dung email. Lưu ý giữ nguyên các biến như `{{ interview_time }}`, `{{ interview_location }}` để hệ thống tự động điền thông tin chính xác từ lịch trình đã tạo.

#### Bước 5: Hoàn tất

* Rà soát lại toàn bộ thông tin và nhấn \[Tạo lịch trình] để lưu và gửi thông báo.

## 4. Kết quả mong đợi

* Buổi phỏng vấn được hiển thị trên lịch chung của hệ thống.
* Email mời phỏng vấn được gửi tự động đến ứng viên và các thành viên hội đồng.
* Trạng thái của ứng viên trong kho ứng viên được cập nhật gắn liền với lịch hẹn.

## <mark style="color:$primary;">5. Lưu ý quan trọng</mark>

* <mark style="color:$primary;">Kiểm tra kỹ Job Opening: Nếu không chọn Tin tuyển dụng, bạn sẽ không thể chọn được Ứng viên hay Hội đồng phỏng vấn.</mark>
* <mark style="color:$primary;">Biến hệ thống: Không xóa các dấu ngoặc nhọn</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">`{{ }}`</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">trong mẫu email vì đây là mã để hệ thống tự lấy dữ liệu từ lịch đã thiết lập.</mark>
* <mark style="color:$primary;">Đồng bộ hóa: Luôn cập nhật hoặc hủy lịch trình trên hệ thống nếu có thay đổi đột xuất để đảm bảo kho ứng viên luôn hiển thị dữ liệu thời gian thực chính xác nhất.</mark>
