# Tổng quan giao diện

### A. Mẫu tin tuyển dụng

Giao diện Mẫu tin tuyển dụng giúp chuẩn hóa quy trình đăng tin. Thay vì viết lại từ đầu, bạn có thể tạo các bộ khung (template) cho từng vị trí và áp dụng chúng bất cứ khi nào cần.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 142215.jpg" alt=""><figcaption></figcaption></figure>

#### 1. Công cụ Tìm kiếm và Bộ lọc chuyên sâu

Hệ thống bộ lọc giúp bạn quản lý thư viện mẫu tin khổng lồ một cách dễ dàng:

* Tên mẫu: Nhập từ khóa để tìm nhanh mẫu tin (ví dụ: "Marketing", "Kế toán").
* Danh mục: Lọc theo lĩnh vực ngành nghề (ví dụ: Kinh doanh, Kỹ thuật, HR).
* Company & Unit/Department: Lọc mẫu tin dành riêng cho từng công ty thành viên hoặc phòng ban cụ thể.
* Chức vụ: Lọc theo các vị trí công việc đã được thiết lập sẵn trong cài đặt hệ thống.
* Công cụ bổ trợ (Góc phải):
  * Làm mới: Cập nhật lại danh sách mẫu.
  * Sắp xếp: Thứ tự hiển thị theo tên hoặc ngày sử dụng lần cuối.
  * Cột: Tùy chỉnh hiển thị các thông tin như "Mức lương tối đa", "Mức lương tối thiểu".
  * Dấu ba chấm (...): Chứa các tùy chọn Xuất dữ liệu hoặc Nhập dữ liệu mẫu tin từ file Excel.

#### 2. Danh sách Mẫu tin tuyển dụng (Bảng dữ liệu)

Bảng này cung cấp thông tin tổng quan về hiệu quả sử dụng của các template:

| **Tên cột**      | **Ý nghĩa**                                                         |
| ---------------- | ------------------------------------------------------------------- |
| Tên mẫu          | Tiêu đề định danh của mẫu tin nội bộ.                               |
| Danh mục         | Nhãn phân loại ngành nghề (ví dụ: Tài chính, Marketing).            |
| Số lượng sử dụng | Tổng số lần mẫu này đã được dùng để tạo tin tuyển dụng thực tế.     |
| Trạng thái       | Hiển thị mẫu đang ở dạng Hoạt động hoặc tạm ẩn.                     |
| Sử dụng lần cuối | Ghi nhận thời gian gần nhất mẫu này được áp dụng.                   |
| Mức lương...     | Các trường thông tin về khung lương dự kiến đã thiết lập trong mẫu. |

#### B. Khởi tạo mẫu tin tuyển dụng từ vị trí

Cách làm này giúp bạn tự động kế thừa các thông tin đã thiết lập từ danh mục "Vị trí công việc" để tạo mẫu nhanh chóng.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 143832.jpg" alt=""><figcaption></figcaption></figure>

#### Bước 1: Bắt đầu khởi tạo

* Tại giao diện chính của Mẫu tin tuyển dụng, nhấn vào nút \[+ Tạo từ Vị trí] nằm ở góc trên bên phải màn hình.

#### Bước 2: Thiết lập thông tin cơ bản (Cửa sổ Pop-up)

Khi cửa sổ "Tạo mẫu từ Vị trí" xuất hiện, bạn cần hoàn thiện các trường sau:

* Chọn Vị trí (\*): Chọn một vị trí công việc cụ thể đã được định nghĩa sẵn trong hệ thống.
* Tên phiếu đánh giá (\*): Nhập tên cho mẫu tin này (ví dụ: "Mẫu tuyển dụng Chuyên viên GIS").
* Mô tả: Viết một đoạn mô tả ngắn về mục đích hoặc lưu ý cho mẫu này (tùy chọn).
* Danh mục: Chọn nhóm ngành nghề phù hợp hoặc để hệ thống tự động phát hiện từ vị trí đã chọn.
* Sau khi điền xong, nhấn nút \[Tạo mẫu] để chuyển sang bước thiết lập chi tiết.

#### Bước 3: Hoàn thiện nội dung mẫu chi tiết

Sau khi nhấn tạo, hệ thống sẽ mở ra giao diện chỉnh sửa toàn diện. Bạn có thể kiểm tra và điều chỉnh các nhóm thông tin sau:

1. Thông tin cơ bản: \* Xác nhận lại Mẫu chức danh công việc (tên hiển thị cho ứng viên) và Mẫu chức danh nội bộ.
   * Gắn mẫu vào đúng Phòng ban/Đơn vị hoặc đơn vị cha cũ nếu cần thiết.
2. Mô tả tin tuyển dụng: \* Sử dụng trình soạn thảo để tinh chỉnh: Mô tả công việc, Yêu cầu công việc và các Phúc lợi đi kèm.
3. Thông tin tuyển dụng: \* Thiết lập loại hình công việc (Full-time/Part-time), số lượng cần tuyển mặc định và thời hạn nộp hồ sơ (ví dụ: 30 ngày).
4. Lương & Phúc lợi: \* Cài đặt khung lương (Tối thiểu - Tối đa) và quyết định có hiển thị con số này công khai hay không.
5. Vòng tuyển dụng: \* Hệ thống sẽ hiển thị các bước quy trình mà ứng viên sẽ trải qua trước khi được đưa vào kho ứng viên chính thức.

***

Lưu ý cuối cùng: Sau khi đã rà soát tất cả các mục, hãy nhấn nút \[Lưu mẫu] ở góc dưới cùng để hoàn tất quy trình.

#### C. Khởi tạo mẫu mới hoàn toàn

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 150252.jpg" alt=""><figcaption></figcaption></figure>

#### Bước 1: Khởi tạo

* Tại giao diện Mẫu tin tuyển dụng, nhấn nút \[+ Tạo mẫu] ở góc trên cùng bên phải màn hình.

#### Bước 2: Thiết lập Thông tin mẫu

Đây là phần định danh cho mẫu tin trong hệ thống:

* Tên phiếu đánh giá (\*): Nhập tên mẫu tin tuyển dụng bạn muốn tạo (Ví dụ: Mẫu tuyển dụng lập trình viên).
* Danh mục: Chọn ngành nghề phù hợp từ danh sách thả xuống như Engineering, Marketing, Sales, HR, Finance, Operations hoặc General.
* Mô tả: Viết đoạn giới thiệu ngắn gọn về mục đích của mẫu này.
* Trạng thái:
  * Tích chọn Hoạt động để mẫu có thể sử dụng ngay.
  * Tích chọn Mẫu mặc định nếu bạn muốn đây là khung nội dung ưu tiên khi đăng tin.

#### Bước 3: Thiết lập Quy trình tuyển dụng (Pipeline)

* Chọn Quy trình tuyển dụng: Lựa chọn quy trình các bước mà ứng viên sẽ phải trải qua (Ví dụ: _Complete Recruitment Pipeline_) để sau này hệ thống tự động phân loại hồ sơ vào đúng luồng trong kho ứng viên.

#### Bước 4: Organization & Position (Tổ chức & Vị trí)

Tại đây, bạn liên kết mẫu tin với cấu trúc doanh nghiệp:

* Công ty: Chọn pháp nhân/công ty cụ thể áp dụng mẫu này.
* Unit/Department: Chọn phòng ban hoặc đơn vị cha cũ tương ứng.
* Vị trí công việc: Gắn mẫu này với một chức danh cụ thể để đồng bộ báo cáo sau này.

#### Bước 5: Soạn thảo nội dung (Mô tả tin tuyển dụng)

* Sử dụng trình soạn thảo văn bản trực quan để nhập nội dung cho Mẫu mô tả tin tuyển dụng.
* Bạn có thể sử dụng các công cụ định dạng (In đậm, danh sách liệt kê, chèn link...) để làm nổi bật các ý chính như trách nhiệm công việc và quyền lợi.
