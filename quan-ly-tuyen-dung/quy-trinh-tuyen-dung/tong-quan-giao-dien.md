# Tổng quan giao diện

## 1. Truy cập danh sách ứng viên

* Tại danh sách tin tuyển dụng, nhấn vào Xem chi tiết tin tuyển dụng cụ thể (ví dụ: Tuyển dụng Frontend Developer).
* Chọn tab Ứng viên để quản lý hồ sơ ứng tuyển.

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

## 2. Thiết lập và Hiển thị Quy trình

* Khi bạn thêm Quy trình tuyển dụng đã khởi tạo từ trước vào tin tuyển dụng, hệ thống sẽ tự động hiển thị quy trình này dưới dạng các cột tương ứng trong tab Ứng viên.
*   Bạn có thể thay đổi cách xem theo 2 dạng:

    * Chế độ Kanban: Hiển thị ứng viên dưới dạng thẻ trong các cột quy trình (Review, Sàng lọc, Phỏng vấn...) giúp dễ dàng theo dõi tiến độ.

    <figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

    * Chế độ Danh sách: Hiển thị ứng viên theo hàng ngang với đầy đủ thông tin chi tiết về liên hệ, trạng thái và ngày ứng tuyển.

    <figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

## 3. Thao tác với Ứng viên

* Thêm mới: Bạn có thể trực tiếp thêm ứng viên vào hệ thống bằng nút Tạo mới ngay tại giao diện này.

<figure><img src="../../.gitbook/assets/Screenshot 2026-03-05 094301.jpg" alt=""><figcaption></figcaption></figure>

* Chuyển vòng ứng viên:
  * Dùng chuột kéo thả (Chế độ Kanban): Giữ và kéo thẻ ứng viên từ cột này sang cột khác để cập nhật trạng thái.
  * Sử dụng nút thao tác (Chế độ Danh sách): Nhấn vào biểu tượng mũi tên 4 chiều tại cột Hành động để chọn nhanh bước tiếp theo trong quy trình (ví dụ: Chuyển sang Phỏng vấn, Gửi Đề nghị...).

## 4. Cơ chế Tự động hóa (Trigger)

Việc di chuyển ứng viên giữa các vòng sẽ kích hoạt các thiết lập tự động đã cài đặt trước đó:

* Sự kiện kích hoạt: Khi ứng viên được kéo vào một bước nhất định, hệ thống nhận diện đây là sự kiện "Khi có ứng viên vào bước này".
* Hành động thực thi: Tùy vào thiết lập, hệ thống sẽ tự động thực hiện các tác vụ như:
  * Gửi Email thông báo hoặc thư mời phỏng vấn.
  * Lên lịch kiểm tra hoặc phỏng vấn trực tiếp.
  * Thông báo cho hội đồng tuyển dụng về sự thay đổi trạng thái của ứng viên.
