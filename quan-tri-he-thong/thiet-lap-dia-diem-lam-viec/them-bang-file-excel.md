# Thêm bằng file excel

## 1. Mục tiêu

Tối ưu hóa thời gian thiết lập danh sách mạng lưới văn phòng, chi nhánh quy mô lớn bằng cách nhập dữ liệu hàng loạt, đảm bảo tính chính xác và đồng bộ dữ liệu địa lý.

## 2. Khi nào sử dụng?

* Khi bắt đầu triển khai hệ thống và cần nhập toàn bộ danh sách địa điểm hiện có của tổ chức.
* Khi doanh nghiệp mở rộng quy mô nhanh chóng với hàng loạt địa điểm mới tại nhiều khu vực khác nhau.
* Khi cần cập nhật thông tin địa chỉ hàng loạt cho nhiều chi nhánh cùng lúc.

## 3. Các bước thực hiện

### Bước 1: Tải file mẫu và chuẩn bị dữ liệu

* Nhấn vào biểu tượng dấu ba chấm (...) ở góc phải màn hình, chọn chức năng Nhập dữ liệu (Import).
* Tải file biểu mẫu từ hệ thống. Điền đầy đủ thông tin vào các cột tương ứng: Mã địa điểm, Tên địa điểm, Mã công ty, Mã địa điểm cha, Địa chỉ chi tiết...

### Bước 2: Tải file dữ liệu lên hệ thống

<figure><img src="../../.gitbook/assets/image (288).png" alt=""><figcaption></figcaption></figure>

* Nhấn nút chọn tệp hoặc kéo thả file Excel đã chuẩn bị vào vùng yêu cầu trên giao diện Import.

### Bước 3: Đối soát trường thông tin (Mapping)

* Kiểm tra các cột dữ liệu trong file Excel để đảm bảo hệ thống đã nhận diện đúng các trường thông tin (ví dụ: cột "Tên chi nhánh" khớp với trường "Tên địa điểm" trên hệ thống).

### Bước 4: Kiểm tra và Xác nhận nhập liệu

* Hệ thống sẽ kiểm tra tính hợp lệ của dữ liệu (mã trùng, thiếu thông tin bắt buộc).
* Nếu không có lỗi, nhấn Hoàn tất để đưa toàn bộ danh sách địa điểm vào hệ thống quản lý và kho ứng viên.

## 4. Kết quả mong đợi

* Toàn bộ danh sách địa điểm được hiển thị đầy đủ trên bảng dữ liệu chỉ sau một lần thao tác.
* Các mối quan hệ phân cấp (Parent - Child) giữa các địa điểm được thiết lập tự động.

## <mark style="color:$primary;">5. Lưu ý quan trọng</mark>

* <mark style="color:$primary;">Dữ liệu tham chiếu: Đảm bảo "Công ty" và "Parent Location" trong file Excel phải trùng khớp hoàn toàn với các dữ liệu đã tồn tại trên hệ thống để tránh lỗi không nhận diện được đơn vị chủ quản.</mark>
* <mark style="color:$primary;">Trạng thái mặc định: Nếu không điền cột trạng thái, hệ thống có thể mặc định ở trạng thái Active hoặc để trống, vui lòng kiểm tra kỹ file mẫu trước khi thực hiện.</mark>
