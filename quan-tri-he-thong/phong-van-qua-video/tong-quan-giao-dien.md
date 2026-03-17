# Tổng quan giao diện

### A. Giao diện: Quản lý Câu hỏi phỏng vấn video

Giao diện này cho phép bạn quản lý và phân loại các câu hỏi phỏng vấn theo từng phòng ban và vị trí tuyển dụng cụ thể.

<figure><img src="../../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

#### 1. Thanh công cụ phía trên

* Thêm Câu hỏi: Nút nằm ở góc trên bên phải giúp bạn tạo mới câu hỏi vào hệ thống.
* Bộ lọc Phòng ban/Đơn vị: Cho phép bạn lọc nhanh danh sách câu hỏi theo từng đơn vị cụ thể. Bạn có thể nhấn Xóa bộ lọc để quay lại danh sách tổng quát.

#### 2. Cấu trúc phân cấp dữ liệu

Giao diện được thiết kế theo dạng thẻ phân cấp từ lớn đến nhỏ để dễ dàng quản lý:

* Cấp 1 - Phòng ban/Đơn vị (Màu xanh dương): Hiển thị tên đơn vị trực thuộc (Ví dụ: Khối Back-Office, Team Mobile). Đây có thể là các đơn vị con thuộc một đơn vị cha cũ mà bạn đã thiết lập.
* Cấp 2 - Bộ câu hỏi theo vị trí (Màu xanh lá): Hiển thị chức danh công việc cụ thể (Ví dụ: Chuyên viên Kế toán, Nhà thiết kế giao diện). Tại đây có số lượng tổng câu hỏi có trong bộ (ví dụ: 3 các câu hỏi).
* Cấp 3 - Chi tiết câu hỏi (Màu trắng): Nội dung câu hỏi cụ thể mà ứng viên sẽ nhìn thấy.

#### 3. Chi tiết thông tin trong một câu hỏi

Mỗi dòng câu hỏi bao gồm các thông số quan trọng sau:

* Số thứ tự (ID): Nằm ở vòng tròn bên trái (1, 2, 3...).
* Nội dung câu hỏi: Phần văn bản mô tả chi tiết tình huống hoặc yêu cầu phỏng vấn.
* Loại hình phản hồi: \* `VIDEO`: Ứng viên trả lời bằng cách quay video.
  * `TEXT`: Ứng viên trả lời bằng cách nhập văn bản.
  * `AUDIO`: Ứng viên trả lời bằng bản ghi âm.
* Thời gian giới hạn: Biểu tượng đồng hồ (ví dụ: `120s`, `180s`) hiển thị thời gian tối đa ứng viên được phép trả lời.
* Tính năng AI: Biểu tượng bộ não (AI) cho biết câu hỏi có tích hợp công cụ đánh giá tự động.

### B. Giao diện: Tạo mới Câu hỏi phỏng vấn video

<figure><img src="../../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

#### 1. Thông tin cấu hình cơ bản

* Phòng ban/Đơn vị (\*): Chọn đơn vị cụ thể sẽ sử dụng câu hỏi này. Lưu ý chọn đúng để câu hỏi được phân loại chính xác theo cấu trúc đơn vị cha cũ nếu có.
* Định dạng câu hỏi (\*): Chọn hình thức ứng viên sẽ dùng để trả lời:
  * Text: Trả lời bằng văn bản.
  * Video: Trả lời bằng video ghi hình trực tiếp.
  * Audio: Trả lời bằng bản ghi âm giọng nói.
* Nội dung câu hỏi (\*): Nhập chi tiết câu hỏi hoặc tình huống phỏng vấn bạn muốn đặt ra cho ứng viên.
* Thời gian chuẩn bị (giây): Khoảng thời gian cho phép ứng viên suy nghĩ trước khi hệ thống bắt đầu ghi hình/ghi âm (mặc định thường là 30 giây).
* Thời gian giới hạn trả lời (giây): Tổng thời lượng tối đa mà ứng viên có để hoàn thành câu trả lời (ví dụ: 120 giây).

#### 2. Các tùy chọn thiết lập nhanh

* Cho phép làm lại bài: Nếu tích chọn, ứng viên có thể quay lại video nếu chưa ưng ý.
* Cho phép bỏ qua: Ứng viên có quyền không trả lời câu hỏi này.
* Bật chấm điểm bằng AI: Kích hoạt tính năng phân tích tự động dựa trên tiêu chí bạn thiết lập bên dưới.

#### 3. Tiêu chí đánh giá (AI)

Mục này cực kỳ quan trọng để hệ thống hỗ trợ bạn lọc kho ứng viên hiệu quả hơn:

* Loại câu hỏi: Phân loại mục đích của câu hỏi để AI áp dụng thuật toán phù hợp:
  * _Technical:_ Kiểm tra kiến thức chuyên môn.
  * _Behavioral:_ Kiểm tra hành vi/thái độ.
  * _Situational:_ Kiểm tra khả năng xử lý tình huống.
  * _General:_ Các câu hỏi làm quen/tổng quát.
* Điều người phỏng vấn đang tìm kiếm: Mô tả các kỹ năng, phẩm chất bạn muốn đánh giá qua câu hỏi này.
* Cách trả lời: Gợi ý hướng tiếp cận câu hỏi cho ứng viên (giúp AI hiểu ngữ cảnh tốt hơn).
* Câu trả lời mẫu: Nhập nội dung trả lời lý tưởng để làm "thước đo" cho AI đối chiếu.
* Từ khóa: Thêm các từ chuyên môn hoặc từ khóa then chốt bắt buộc phải có trong câu trả lời. Nhập từ khóa và nhấn Thêm.

***

#### Lưu ý quan trọng:

> Các trường có dấu sao đỏ (\*) là bắt buộc. Sau khi hoàn tất, nhấn Tạo mới để lưu câu hỏi vào hệ thống hoặc Hủy bỏ để đóng cửa sổ mà không lưu thay đổi.
