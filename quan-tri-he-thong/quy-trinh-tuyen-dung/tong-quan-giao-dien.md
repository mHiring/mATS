# Tổng quan giao diện

## I. Giao diện thiết lập Quy trình tuyển dụng

Giao diện Các quy trình tuyển dụng cho phép bạn quản lý, tùy chỉnh và tạo mới các luồng vận hành cho từng vị trí hoặc phòng ban khác nhau trong công ty.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-03 105811.jpg" alt=""><figcaption></figcaption></figure>

### 1. Tổng quan Giao diện Danh sách

Tại màn hình chính, bạn có thể quản lý tất cả các luồng quy trình hiện có trong hệ thống:

* Nút (+ Tạo quy trình tuyển dụng): Nằm ở góc trên bên phải, dùng để bắt đầu thiết lập một luồng quy trình mới từ đầu.
* Nút (Làm mới): Cập nhật lại danh sách các quy trình để đảm bảo dữ liệu mới nhất.
* Bảng danh sách quy trình: Bao gồm các cột thông tin chính:
  * Tên quy trình: Hiển thị tên cụ thể (ví dụ: Quy trình tuyển dụng Marketing, Lập trình viên MBW...). Các quy trình quan trọng có thể được gắn nhãn Mặc định để hệ thống tự động áp dụng.
  * Trạng thái: Hiển thị tình trạng Hoạt động hoặc tạm dừng của quy trình.
  * Đã tạo: Hiển thị ngày quy trình được thiết lập trên hệ thống.

### 2. Các công cụ quản lý nhanh

Tại mỗi dòng quy trình, bạn có bộ công cụ thao tác nhanh ở cột cuối cùng:

* Biểu tượng bánh răng (Cấu hình): Cho phép bạn đi sâu vào thiết lập các bước (stages) chi tiết trong luồng, ví dụ: từ Sơ loại, Phỏng vấn đến Nhận việc.
* Biểu tượng Nhân bản (Copy): Giúp bạn sao chép nhanh một quy trình hiện có để chỉnh sửa cho vị trí tương tự, tiết kiệm thời gian thiết lập lại từ đầu.
* Biểu tượng Thùng rác (Xóa): Loại bỏ các quy trình không còn sử dụng (Lưu ý: Thường chỉ xóa được khi không có ứng viên nào đang trong luồng này).

### 3. Quản lý dữ liệu Quy trình (Menu mở rộng)

Tương tự như giao diện nhãn, bạn có thể sử dụng menu mở rộng (dấu ba chấm) để thực hiện các thao tác quản lý dữ liệu tập trung:

* Xuất dữ liệu: Trích xuất danh sách các quy trình tuyển dụng ra file bên ngoài.
* Nhập dữ liệu: Đưa danh sách quy trình đã soạn thảo sẵn từ file vào hệ thống một cách hàng loạt.

## II. Giao diện tạo mới Quy trình tuyển dụng

Màn hình này cho phép bạn xây dựng một kịch bản tuyển dụng bài bản, từ lúc tiếp nhận hồ sơ cho đến khi ứng viên trúng tuyển.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-03 144022.jpg" alt=""><figcaption></figcaption></figure>

### 1. Thông tin quy trình (Cấu hình cơ bản)

Đây là nơi bạn xác định danh tính cho luồng quy trình:

* Tên quy trình (\*): Nhập tên phân biệt (ví dụ: Quy trình tuyển dụng Khối kỹ thuật).
* Mô tả: Diễn giải mục đích hoặc đối tượng áp dụng của quy trình này.
* Trạng thái: Bật Đang hoạt động để có thể áp dụng ngay cho các tin tuyển dụng.
* Là mặc định: Nếu chọn, hệ thống sẽ tự động ưu tiên sử dụng luồng này khi bạn tạo tin tuyển dụng mới.

### 2. Các giai đoạn tuyển dụng (Cấu hình luồng)

Phần này giúp bạn hình dung trực quan "hành trình" của ứng viên:

* Luồng quy trình: Hiển thị sơ đồ ngang các bước chính (ví dụ: Đơn ứng tuyển mới → Sàng lọc → Phỏng vấn → Đề nghị nhận việc → Đã tuyển).
* Chi tiết giai đoạn: \* Mỗi giai đoạn (Stage) có số thứ tự (STT) và tên riêng.
  * Một số giai đoạn có trạng thái Cố định / Đã sửa (như Đơn ứng tuyển mới) để đảm bảo tính logic của hệ thống.
  * Thêm bước: Trong mỗi giai đoạn, bạn có thể nhấn "+ Thêm bước vào..." để chi tiết hóa các hành động (như: Gửi bài test, Gọi điện sơ loại).
* Nút (+ Thêm Giai đoạn): Cho phép bạn chèn thêm các vòng thi hoặc vòng phỏng vấn bổ sung nếu cần.

#### A. Thao tác Thêm Giai đoạn Tuyển dụng

Khi quy trình mặc định chưa đủ đáp ứng nhu cầu (ví dụ: cần thêm vòng "Phỏng vấn chuyên môn 2" hoặc "Kiểm tra lý lịch"), bạn có thể chèn thêm các mắt xích mới vào luồng vận hành.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-03 144609.jpg" alt=""><figcaption></figcaption></figure>

Các bước thực hiện:

1. Tại phần Các giai đoạn tuyển dụng, nhấn nút \[+ Thêm Giai đoạn].
2. Một cửa sổ hiện ra, bạn cần hoàn thiện các thông tin sau:
   * Tên Giai đoạn (\*): Nhập tên hiển thị của vòng tuyển dụng này (Ví dụ: _Phỏng vấn kỹ thuật_).
   * Trình tự: Hệ thống sẽ tự động gợi ý số thứ tự tiếp theo. Bạn có thể điều chỉnh số này để chèn giai đoạn vào giữa các bước sẵn có.
   * Mô tả: Ghi chú mục đích hoặc các tiêu chuẩn cần đạt trong giai đoạn này.
   * Tùy chọn "Cho phép chỉnh sửa sau khi tạo": Tích chọn nếu bạn muốn có quyền thay đổi thông tin này trong tương lai.
3. Nhấn \[Thêm Giai đoạn] để hoàn tất.

Hiển thị trên Luồng quy trình: Sau khi lưu thành công, giai đoạn mới sẽ ngay lập tức xuất hiện tại hai vị trí:

* Tại Luồng quy trình (Pipeline Bar): Xuất hiện dưới dạng một điểm nút mới trong sơ đồ ngang, giúp bạn có cái nhìn trực quan về lộ trình của ứng viên trong kho ứng viên.
* Tại Danh sách chi tiết: Một khối (block) mới được tạo ra bên dưới các giai đoạn cũ, sẵn sàng để bạn nhấn "+ Thêm bước" nhằm thiết lập các hành động cụ thể bên trong.

#### Lưu ý quan trọng khi sắp xếp thứ tự:

* Các giai đoạn như "Đơn ứng tuyển mới" (thường là STT 1) và "Đã tuyển" (giai đoạn cuối) thường được thiết lập là Cố định.
* Khi bạn thay đổi số Trình tự, hệ thống sẽ tự động đẩy các giai đoạn có số thứ tự trùng hoặc lớn hơn xuống phía sau để đảm bảo tính liên tục của luồng.

#### **B. Thiết lập Chi tiết các Bước trong Giai đoạn**

Sau khi xác định được các giai đoạn lớn, bạn cần cụ thể hóa các hành động bằng cách thêm các "Bước" (Steps). Đây là đơn vị nhỏ nhất để xử lý hồ sơ ứng viên trong kho ứng viên.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-03 144952.jpg" alt=""><figcaption></figcaption></figure>

#### Thao tác Thêm Bước mới

1. Tại mỗi khối Giai đoạn (ví dụ: _Đơn ứng tuyển mới_), nhấn vào vùng \[+ Thêm bước vào...].
2. Cửa sổ Thêm Bước Mới hiện ra, bạn cần nhập:
   * Tên bước (\*): Nhập hành động cụ thể (ví dụ: "Sàng lọc hồ sơ", "Gửi test IQ").
   * Thứ tự sắp xếp: Xác định vị trí của bước này trong danh sách ưu tiên thực hiện bên trong giai đoạn.
3. Nhấn \[Tạo bước] để hoàn tất. Bạn có thể lặp lại thao tác này để thêm nhiều bước khác nhau cho cùng một giai đoạn.

#### Quản lý và Tối ưu hóa Bước

Sau khi một bước được tạo, hệ thống cung cấp các công cụ quản lý chuyên sâu ngay trên giao diện thẻ của bước đó:

* Chỉnh sửa (Biểu tượng Bút chì): Thay đổi tên hoặc thứ tự sắp xếp của bước.
* Cài đặt (Biểu tượng Bánh răng): Thiết lập các thuộc tính nâng cao như:
  * Phân loại loại hình thực hiện (ví dụ: Manual - Thủ công).
  * Cấu hình các hành động tự động hóa (Gửi email, Thông báo...).
* Nhân bản (Biểu tượng Copy): Sao chép nhanh cấu hình của một bước sang một vị trí khác để tiết kiệm thời gian thiết lập.
* Xóa (Biểu tượng Thùng rác): Loại bỏ bước khỏi quy trình nếu không còn cần thiết.

#### Hiển thị Trạng thái Bước

Mỗi bước sau khi tạo sẽ hiển thị tóm tắt các thông tin quan trọng:

* Số thứ tự: Hiển thị rõ vị trí thực hiện (ví dụ: 1, 2, 3...).
* Nhãn phân loại: Cho biết bước này là thủ công (manual) hay có các hành động đi kèm hay không (Không có hành động).

#### **C. Thiết lập Quy tắc Tự động hóa cho Bước**

Tính năng này giúp bạn rảnh tay bằng cách tự động kích hoạt các phản hồi hoặc tác vụ khi ứng viên trong kho ứng viên đạt đến một điều kiện nhất định. Để bắt đầu, hãy nhấn vào biểu tượng Bánh răng (Cài đặt) tại bước cần thiết lập.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-03 145754.jpg" alt=""><figcaption></figcaption></figure>

#### Bước 1: Xác định thời điểm kích hoạt (Sự kiện Trigger)

Trong cửa sổ Thiết lập quy tắc tự động hóa, bạn cần xác định rõ "Khi nào việc này nên chạy?":

* Sự kiện Trigger: Chọn một trong 5 sự kiện có sẵn từ danh sách thả xuống:
  * Khi có ứng viên vào bước này: Kích hoạt ngay khi hồ sơ được chuyển tới bước hiện tại.
  * Khi hoàn thành bài kiểm tra: Kích hoạt sau khi ứng viên nộp kết quả bài test.
  * Khi hoàn thành phỏng vấn Video/Onsite: Kích hoạt sau khi trạng thái buổi phỏng vấn được cập nhật là hoàn thành.
  * Khi Chấp nhận Offer: Kích hoạt khi ứng viên xác nhận đồng ý nhận việc.
  * Khi hồ sơ cập nhật: Kích hoạt khi có bất kỳ thay đổi thông tin nào trên hồ sơ ứng viên.
* Mô tả: Nhập diễn giải ngắn gọn về mục đích của quy tắc này để dễ dàng quản lý về sau.

#### Bước 2: Cấu hình hành động thực hiện (Actions)

Sau khi có sự kiện kích hoạt, bạn chọn "Hành động nào sẽ được thực hiện?":

* Loại hành động: Hệ thống cung cấp danh mục hành động đa dạng:
  * Giao tiếp: Gửi Email, Gửi thư mời nhận việc, Gửi thư nghiệm.
  * Điều phối: Lên lịch kiểm tra, Lên lịch phỏng vấn (Video hoặc Trực tiếp) qua Email.
  * Nội bộ: Thông báo cho Nhóm, Tạo công việc, hoặc Bắt đầu Chấm điểm/Sàng lọc.
* Thêm nhiều hành động: Bạn có thể nhấn \[+ Add Another Action] để thực hiện chuỗi hành động cùng lúc (ví dụ: vừa gửi email cho ứng viên, vừa thông báo cho nhóm tuyển dụng).

#### Bước 3: Hoàn tất thiết lập

* Sau khi đã cấu hình xong các điều kiện và hành động, nhấn nút \[✓ Thêm Quy tắc] để kích hoạt tự động hóa cho bước này.
* Nếu muốn hủy bỏ các thay đổi, nhấn \[Hủy bỏ] hoặc \[Đóng].

### 3. Phân tích quy trình (Thống kê nhanh)

Bảng phía trên bên phải giúp bạn kiểm soát độ phức tạp của luồng:

* Các giai đoạn: Tổng số vòng thi lớn.
* Tổng số bước: Tổng cộng tất cả các thao tác chi tiết bên trong.
* Hệ thống cũng phân loại rõ bao nhiêu bước là Tự động hóa, Thủ công hoặc Có điều kiện.

### 4. Các mẫu ví dụ (Tải nhanh)

Nếu bạn chưa có ý tưởng, hệ thống cung cấp sẵn các bộ khuôn (Template) phổ biến bên cột phải:

* Complete Pipeline: Quy trình đầy đủ với nhiều giai đoạn và bước chi tiết.
* Basic Pipeline: Quy trình 4-5 giai đoạn đơn giản cho các vị trí phổ thông.
* Tech Recruitment/Startup Quick: Các mẫu chuyên biệt cho khối kỹ thuật hoặc tuyển dụng tốc độ cao.
* Cách dùng: Nhấn vào biểu tượng Tải xuống (mũi tên) ở mỗi mẫu để hệ thống tự động đổ dữ liệu vào trang thiết lập.

