# Tổng quan giao diện

### 1. **Giao diện Phòng ban/Đơn vị**

Màn hình này cho phép bạn xây dựng sơ đồ tổ chức chi tiết của từng công ty, giúp quản lý nhân sự và phân quyền chính xác trong kho ứng viên.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-02 155756.jpg" alt=""><figcaption></figcaption></figure>

#### A. Công cụ Tìm kiếm và Quản lý danh sách

* Tìm kiếm: Tra cứu nhanh theo tên phòng ban hoặc mã đơn vị.
* Bộ lọc Công ty: Chọn một công ty cụ thể để xem danh sách các phòng ban trực thuộc.
* Trạng thái: Lọc theo các đơn vị đang Hoạt động hoặc tạm dừng.
* Cấu trúc cây: Danh sách hiển thị dạng phân cấp (biểu tượng dấu trừ/cộng bên cạnh tên), giúp bạn thấy rõ phòng ban nào thuộc đơn vị nào.

#### B. Nhóm công cụ tùy chỉnh (Góc phải)

* Làm mới (↻): Cập nhật dữ liệu cấu trúc tổ chức mới nhất.
* Cột: Tùy chỉnh hiển thị các cột như Trưởng đơn vị, Công ty chủ quản, Trạng thái danh mục.
* Tiện ích (...): Chứa hai tính năng quan trọng là Nhập dữ liệu (Import) và Xuất dữ liệu (Export) giúp bạn đẩy nhanh quá trình thiết lập sơ đồ tổ chức từ file Excel.



### 2. **Giao diện Thêm mới và Tùy chỉnh Bố cục**

Khi nhấn nút \[+ Create], cửa sổ Add Unit sẽ hiện ra.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-02 160501.jpg" alt=""><figcaption></figcaption></figure>

Bạn có thể thiết lập các trường mặc định hoặc tự tạo thêm trường mới.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-02 160512.jpg" alt=""><figcaption></figcaption></figure>

#### A. Các thông tin mặc định

* Bộ phận cha: Chọn đơn vị cấp cao hơn để tạo cấu trúc phân cấp (Nếu để trống, đây sẽ là đơn vị cấp cao nhất).
* Công ty (\*): Chọn công ty chủ quản mà phòng ban này trực thuộc.
* Tên Bộ phận (\*): Nhập tên chính thức (Ví dụ: Phòng Giải pháp FastCons).
* Mã Bộ phận (\*): Hệ thống tự sinh mã định danh duy nhất (Ví dụ: UNT\_2026...).
* Cấp bộ phận (\*): Xác định vị trí của đơn vị trong sơ đồ (Ví dụ: Cấp 1, Cấp 2...).
* Quản lý Bộ phận: Chỉ định người chịu trách nhiệm chính (Trưởng đơn vị).

#### B. Tính năng Tùy chỉnh Bố cục (Custom Layout)

Đây là tính năng nâng cao giúp bạn bổ sung các trường thông tin đặc thù mà hệ thống chưa có sẵn.

* Cách thực hiện: Nhấn vào biểu tượng Chỉnh sửa (hình tờ giấy và bút) ở góc trên bên phải cửa sổ Add Unit.
* Tại giao diện Chỉnh sửa Bố cục:
  * Thêm trường: Nhấn \[+ Thêm trường] để tạo thêm các ô nhập liệu mới.
  * Thêm phần: Nhấn \[+ Thêm phần] để nhóm các trường thông tin lại theo từng khối.
  * Sắp xếp: Nhấn giữ biểu tượng 6 dấu chấm (⠿) để kéo thả, thay đổi vị trí các trường theo ý muốn.
  * Xóa trường: Nhấn dấu (x) để loại bỏ các trường không cần thiết khỏi giao diện nhập liệu.
* Lưu cấu hình: Nhấn \[Lưu] để áp dụng giao diện mới cho tất cả các lần thêm mới phòng ban sau này.

