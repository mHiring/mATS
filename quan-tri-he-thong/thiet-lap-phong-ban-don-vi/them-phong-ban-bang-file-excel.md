# Thêm phòng ban bằng file Excel

## 1. Mục tiêu

Tối ưu hóa thời gian thiết lập sơ đồ tổ chức bằng cách đẩy dữ liệu hàng loạt từ file Excel lên hệ thống, đảm bảo tính nhanh chóng và đồng bộ cho các doanh nghiệp có quy mô lớn.

## 2. Khi nào sử dụng?

* Khi bắt đầu triển khai hệ thống mới và cần nhập toàn bộ sơ đồ tổ chức từ đầu.
* Khi doanh nghiệp có đợt tái cấu trúc lớn, thay đổi hàng loạt đơn vị cha cũ sang các đơn vị mới.
* Khi cần cập nhật thông tin cho hàng trăm phòng ban cùng một lúc.

## 3. Các bước thực hiện

### Bước 1: Tải file mẫu và chuẩn bị dữ liệu

<figure><img src="../../.gitbook/assets/image (283).png" alt=""><figcaption></figcaption></figure>

* Nhấn vào biểu tượng Tiện ích (...) ở góc phải màn hình, chọn Nhập dữ liệu (Import).
* Tải file biểu mẫu từ hệ thống. Điền đầy đủ thông tin vào các cột: Tên bộ phận, Mã bộ phận, Mã bộ phận cha, Công ty chủ quản...

### Bước 2: Tải file lên hệ thống

* Nhấn nút Chọn tệp hoặc kéo thả file Excel đã chuẩn bị vào vùng yêu cầu.
* Nhấn Tiếp tục để hệ thống bắt đầu quét dữ liệu.

### Bước 3: Khớp nối trường dữ liệu (Mapping)

* Kiểm tra xem các tiêu đề cột trong file Excel đã khớp đúng với các trường thông tin trên hệ thống chưa. Nếu chưa, hãy chọn lại thủ công ở danh sách thả xuống.

### Bước 4: Kiểm tra lỗi và Xác nhận

* Hệ thống sẽ hiển thị bản xem trước. Nếu có dòng dữ liệu bị đỏ (lỗi), hãy sửa trực tiếp trên file và tải lại.
* Sau khi tất cả dữ liệu hợp lệ, nhấn Hoàn tất để kích hoạt lệnh nhập.

## 4. Kết quả mong đợi

* Toàn bộ cấu trúc phòng ban được hiển thị đầy đủ trên hệ thống chỉ sau vài giây.
* Các liên kết giữa đơn vị cha và đơn vị con được thiết lập tự động dựa trên mã tham chiếu trong file.

## 5. Lưu ý quan trọng

* Mã tham chiếu: Để hệ thống hiểu được cấu trúc cây, cột "Mã bộ phận cha" trong file Excel phải khớp hoàn toàn với mã của đơn vị cấp trên đã tồn tại hoặc có trong file.
* Định dạng file: Luôn sử dụng file mẫu của hệ thống và không thay đổi định dạng các cột (Header) để tránh lỗi xử lý dữ liệu.
