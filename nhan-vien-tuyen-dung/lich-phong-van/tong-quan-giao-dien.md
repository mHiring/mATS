# Tổng quan giao diện

Tính năng này giúp bạn quản lý tập trung các buổi phỏng vấn với ứng viên, theo dõi lịch trình của hội đồng tuyển dụng và tự động hóa việc gửi thư mời.

<figure><img src="../../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>

## A. Quản lý giao diện Lịch

Hệ thống hỗ trợ 3 chế độ xem linh hoạt tại góc trên bên phải màn hình:

* Chế độ Tháng (Month): Cái nhìn tổng quan về mật độ phỏng vấn trong cả tháng.
* Chế độ Tuần (Week): Xem chi tiết lịch trình theo từng khung giờ trong tuần.
* Chế độ Ngày (Day): Tập trung vào các mốc thời gian cụ thể trong ngày hiện tại, có vạch đỏ hiển thị thời gian thực.

Bộ lọc nhanh: Bạn có thể lọc lịch theo _Loại phỏng vấn_ (Trực tiếp, Trực tuyến, Bài kiểm tra), _Ứng viên_ hoặc theo từng _Job Opening_ cụ thể.

## B. Tạo mới lịch phỏng vấn

Để thêm mới một lịch hẹn, bạn thực hiện các bước sau:

Bước 1: Chọn thời gian

* Tại giao diện lịch (Ngày/Tuần/Tháng), hãy di chuột vào ô ngày/giờ bạn muốn thiết lập.
* Click vào dấu (+) xuất hiện tại ô đó để mở bảng "Add Schedule".

Bước 2: Thiết lập thông tin bắt buộc (Interview Details)

* Ngày phỏng vấn & Thời gian bắt đầu: Hệ thống sẽ mặc định theo ô bạn đã chọn nhưng bạn có thể chỉnh lại.
* Thời lượng: Nhập số phút dự kiến cho buổi phỏng vấn.
* Tin tuyển dụng (Job Opening): > Lưu ý quan trọng: Bạn bắt buộc phải chọn một tin tuyển dụng cụ thể tại trường này. Sau khi chọn xong, hệ thống mới kích hoạt và hiển thị danh sách Hội đồng tuyển dụng và Ứng viên ở cột bên phải để bạn lựa chọn.

Bước 3: Chọn nhân sự tham gia

* Hội đồng tuyển dụng: Chọn những thành viên sẽ tham gia phỏng vấn.
* Ứng viên: Nhấn "Thêm ứng viên" để chọn người từ kho ứng viên thuộc tin tuyển dụng đó.

Bước 4: Ghi chú và Email thông báo

* Ghi chú: Nhập địa điểm hoặc đường dẫn phỏng vấn trực tuyến.
* Thông báo qua Email:
  * Chọn Mẫu Email (ví dụ: Thư mời tham gia phỏng vấn).
  * Nội dung email sẽ tự động đổ vào trình soạn thảo. Bạn có thể chỉnh sửa thủ công hoặc để nguyên các biến hệ thống như `{{ interview_time }}`, `{{ interview_location }}` để hệ thống tự điền thông tin.

Bước 5: Hoàn tất

* Kiểm tra lại toàn bộ thông tin và nhấn nút Tạo lịch trình ở góc dưới bên phải.
