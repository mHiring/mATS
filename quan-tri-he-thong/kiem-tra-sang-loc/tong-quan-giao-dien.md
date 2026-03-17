# Tổng quan giao diện

## A. Giao diện Quản lý Bài kiểm tra Sàng lọc

Màn hình này cho phép bạn quản lý tập trung toàn bộ các bài kiểm tra được thiết kế để đánh giá ứng viên trước khi đưa họ vào kho ứng viên. Dưới đây là chi tiết các thành phần:

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 091103.jpg" alt=""><figcaption></figcaption></figure>

### 1. Khu vực chức năng chính

* Nút \[+ Bài kiểm tra mới]: Nằm ở góc trên cùng bên phải. Nhấn vào đây để bắt đầu tạo một bộ câu hỏi sàng lọc mới cho vị trí tuyển dụng.

### 2. Danh sách bài kiểm tra (Bảng thông tin)

Giao diện hiển thị danh sách các bài kiểm tra hiện có với các cột thông tin cụ thể:

* Tiêu đề: Tên của bài kiểm tra. Đây là tên giúp bạn phân biệt các bộ câu hỏi khác nhau.
* Điểm số: Hiển thị tổng số điểm hoặc số lượng câu hỏi có trong bài kiểm tra đó.
* Vị trí công việc: Cho biết bài kiểm tra này đang được áp dụng cho vị trí tuyển dụng nào . Điều này giúp hệ thống tự động điều phối ứng viên phù hợp.
* Passing % (Tỉ lệ vượt qua): Ngưỡng điểm tối thiểu (tính theo phần trăm) mà ứng viên cần đạt được để vượt qua vòng sàng lọc. Nếu đạt trên mức này, ứng viên có thể được xem xét chuyển trạng thái trong quy trình tuyển dụng.

### 3. Các công cụ thao tác nhanh

Ở cuối mỗi dòng, bạn sẽ thấy hai biểu tượng điều khiển:

* Biểu tượng Chỉnh sửa: Cho phép bạn thay đổi nội dung câu hỏi, điều chỉnh lại vị trí công việc hoặc thay đổi tỉ lệ % vượt qua. Lưu ý: Khi chỉnh sửa, nếu bạn thay đổi cấu trúc từ một đơn vị cha cũ, hãy kiểm tra lại tính đồng bộ của dữ liệu.
* Biểu tượng Thùng rác: Gỡ bỏ hoàn toàn bài kiểm tra khỏi hệ thống. Hãy cẩn trọng vì thao tác này có thể không hoàn tác được.

## B. Hướng dẫn Tạo Bài kiểm tra Sàng lọc

Giao diện này giúp bạn thiết lập các bộ câu hỏi đánh giá năng lực ứng viên trước khi lưu trữ thông tin vào kho ứng viên.

### Giai đoạn 1: Thiết lập cơ bản (Khởi tạo)

Tại màn hình đầu tiên, bạn cần hoàn thành các thông tin bắt buộc để mở khóa tính năng tạo câu hỏi:

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 091325.jpg" alt=""><figcaption></figcaption></figure>

* Quiz Settings (Cài đặt bài kiểm tra):
  * Tiêu đề bài kiểm tra: Nhập tên gợi nhớ cho bài kiểm tra (Ví dụ: "Kiểm tra tư duy logic").
  * Vị trí công việc: Chọn vị trí tương ứng từ danh sách đã được thiết lập trước đó.
* Nút Create Quiz: Sau khi điền đủ hai thông tin trên, hãy nhấn nút này ở góc trên bên phải để bắt đầu thiết lập chi tiết nội dung.

### Giai đoạn 2: Thiết lập chi tiết và Quản lý câu hỏi

Sau khi nhấn Create Quiz, giao diện sẽ mở rộng với các tùy chọn nâng cao và khu vực soạn thảo nội dung:

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 091418.jpg" alt=""><figcaption></figcaption></figure>

#### **1. Bảng điều khiển Quiz Settings (Bên trái)**

Khu vực này hiển thị tổng quan và các quy định cho bài kiểm tra:

* Thống kê nhanh: Hiển thị tổng số câu hỏi và tổng điểm hiện có.
* Cài đặt nâng cao:
  * Số lần thử tối đa: Giới hạn số lần ứng viên được phép thực hiện bài test.
  * Thời lượng (phút): Thiết lập thời gian đếm ngược cho bài làm.
  * Tỷ lệ đạt: Ngưỡng điểm (%) để ứng viên vượt qua vòng này.
  * Tùy chọn hiển thị: Bạn có thể tích chọn để Hiển thị đáp án, Hiển thị lịch sử nộp bài hoặc Trộn câu hỏi để đảm bảo tính khách quan.

#### **2. Khu vực Quản lý câu hỏi (Bên phải)**

Đây là nơi bạn xây dựng nội dung cho bài kiểm tra:

* Nút \[+ Thêm câu hỏi]: Nhấn vào đây để tự soạn thảo câu hỏi mới.
* Nút \[Tạo bằng AI]: Sử dụng trí tuệ nhân tạo để gợi ý các câu hỏi phù hợp với vị trí công việc đã chọn, giúp làm giàu nhanh chóng kho ứng viên chất lượng.
* Trạng thái câu hỏi: Nếu chưa có câu hỏi nào, hệ thống sẽ hiển thị thông báo "No questions yet".



## C. Hướng dẫn Tạo câu hỏi bằng AI (AI Question Generator)

Tính năng này sử dụng trí tuệ nhân tạo để tự động hóa việc soạn thảo câu hỏi dựa trên các tiêu chí cụ thể của vị trí tuyển dụng.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 091947.jpg" alt=""><figcaption></figcaption></figure>

### 1. Thiết lập các tham số cơ bản

Để AI tạo ra kết quả tốt nhất, bạn cần điền các thông tin sau:

* Số lượng câu hỏi: Nhập số lượng câu hỏi bạn muốn AI tạo ra (Ví dụ: 5, 10...).
* Vị trí công việc: Hệ thống tự động lấy thông tin từ bài kiểm tra bạn đang tạo (Ví dụ: _AI Engineer (Computer Vision/NLP)_).
* Giọng điệu (Tone): Chọn phong cách ngôn ngữ cho câu hỏi:
  * _Professional (Chuyên nghiệp)_, _Casual (Thân thiện)_, _Formal (Trang trọng)_, hoặc _Friendly (Gần gũi)_.
* Cấp bậc / Trình độ: Xác định độ khó của câu hỏi:
  * _Beginner (Sơ cấp)_, _Intermediate (Trung cấp)_, _Advanced (Cao cấp)_, hoặc _Expert (Chuyên gia)_.
* Danh mục (Category): Chọn khía cạnh năng lực muốn đánh giá:
  * _Technical (Kỹ thuật)_, _Behavioral (Hành vi)_, _Situational (Tình huống)_, _Cultural Fit (Sự phù hợp văn hóa)_, hoặc _Problem Solving (Giải quyết vấn đề)_.

### 2. Tùy chỉnh nâng cao

* Bình luận bổ sung: Bạn có thể nhập các yêu cầu cụ thể hoặc các mảng kiến thức trọng tâm để AI bám sát (Ví dụ: "Tập trung vào kiến thức về hệ thống RAG và LLM").
* Tạo câu trả lời mẫu: Tích chọn để AI tự động tạo sẵn các phương án trả lời cho bạn.
* Đánh dấu là Câu hỏi loại trực tiếp: Tích chọn nếu bạn muốn tất cả các câu hỏi do AI tạo ra đều trở thành điều kiện bắt buộc để sàng lọc ứng viên.

### 3. Thực thi

* Nút Tạo câu hỏi: Sau khi thiết lập xong, nhấn nút này để AI bắt đầu quét dữ liệu và đưa ra danh sách câu hỏi đề xuất.
* Nút Hủy bỏ: Nhấn nếu bạn muốn đóng cửa sổ và quay lại thao tác thủ công.

### 4. Kiểm tra và Hoàn tất Câu hỏi AI

Sau khi AI thực hiện quét dữ liệu, hệ thống sẽ hiển thị danh sách câu hỏi tại mục Generated Questions Preview để bạn xem xét kỹ lưỡng.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 092232.jpg" alt=""><figcaption></figcaption></figure>

#### 1. Chi tiết nội dung câu hỏi hiển thị

Mỗi câu hỏi được AI đề xuất sẽ bao gồm các thành phần rõ ràng:

* Nội dung câu hỏi: Được trình bày cụ thể (Ví dụ: Các kỹ thuật trong xử lý ngôn ngữ tự nhiên NLP hoặc kiến thức về CNN).
* Thẻ phân loại: Hiển thị loại câu hỏi (Ví dụ: Choices - Trắc nghiệm) và cấp bậc độ khó đã chọn (Ví dụ: Intermediate).
* Options (Các phương án): Danh sách các câu trả lời lựa chọn được liệt kê theo thứ tự A, B, C, D.
* Correct Answer (Đáp án đúng): Phần này được làm nổi bật với màu xanh lá cây để bạn dễ dàng đối chiếu tính chính xác của kiến thức.

#### 2. Các tùy chọn thao tác

Tại cuối danh sách xem trước, bạn có 3 sự lựa chọn chính:

* Nút Thêm vào bài kiểm tra: Nhấn vào đây nếu bạn đã hài lòng với bộ câu hỏi. Hệ thống sẽ ngay lập tức chuyển các câu hỏi này vào danh sách quản lý chính của bài thi.
* Nút Tạo lại: Nếu cảm thấy nội dung chưa thực sự sát với yêu cầu hoặc muốn đổi sang bộ câu hỏi khác, nhấn nút này để AI thực hiện quy trình tạo mới dựa trên các tham số cũ.
* Nút Hủy bỏ: Đóng giao diện xem trước và quay lại màn hình thiết lập trước đó mà không lưu bất kỳ câu hỏi nào.

***

#### 💡 Lưu ý quan trọng khi kiểm tra:

* Độ chính xác: Mặc dù AI rất thông minh, bạn vẫn nên đọc kỹ lại nội dung và đáp án để đảm bảo tính chuẩn xác chuyên môn trước khi gửi cho ứng viên. Điều này giúp bảo vệ uy tín cho quy trình tuyển dụng từ đơn vị cha cũ đến hiện tại.
* Tính đa dạng: Bạn có thể lặp lại thao tác Tạo lại nhiều lần để tìm ra những câu hỏi ưng ý nhất cho bài đánh giá của mình.

## D. Hướng dẫn Thêm Câu hỏi Sàng lọc (Thủ công)

Hệ thống cung cấp hai lựa chọn linh hoạt để bạn xây dựng nội dung đánh giá ứng viên: Chọn từ ngân hàng câu hỏi hoặc Tự soạn thảo câu hỏi mới.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 092314.jpg" alt=""><figcaption></figcaption></figure>

### Lựa chọn 1: Các câu hỏi hiện có (Chọn từ ngân hàng)

Sử dụng phương thức này khi bạn muốn tái sử dụng các câu hỏi chất lượng đã có sẵn trong hệ thống để nhanh chóng lọc ứng viên vào kho ứng viên.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 092407.jpg" alt=""><figcaption></figcaption></figure>

* Danh sách câu hỏi: Hệ thống hiển thị bảng danh sách các câu hỏi có sẵn bao gồm nội dung và loại câu hỏi (ví dụ: Choices - Trắc nghiệm).
* Thao tác chọn: Tích vào ô vuông đầu mỗi câu hỏi bạn muốn sử dụng.
* Điểm cho các câu hỏi đã chọn: Bạn có thể nhập số điểm chung cho tất cả các câu hỏi vừa chọn tại ô này.
* Cấu hình loại câu hỏi:
  * Câu hỏi loại trực tiếp: Nếu tích chọn ô này, ứng viên sẽ bị loại ngay lập tức nếu trả lời sai câu hỏi này, bất kể tổng điểm các câu khác là bao nhiêu.
* Hoàn tất: Nhấn nút \[Thêm câu hỏi] ở dưới cùng để đưa chúng vào bài kiểm tra.

***

### Lựa chọn 2: Tạo mới (Viết câu hỏi mới)

Sử dụng phương thức này để tạo các câu hỏi đặc thù, chưa có trong hệ thống.

<figure><img src="../../.gitbook/assets/Screenshot 2026-02-04 092429.jpg" alt=""><figcaption></figcaption></figure>

* Nội dung câu hỏi: Nhập nội dung câu hỏi tại ô soạn thảo văn bản. Bạn có thể sử dụng các công cụ định dạng (in đậm, in nghiêng, danh sách...) để câu hỏi rõ ràng hơn.
* Thiết lập thông số:
  * Điểm số: Nhập số điểm dành cho câu hỏi này.
  * Loại câu hỏi: Chọn định dạng câu hỏi (Ví dụ: Choices - Trắc nghiệm).
  * Câu hỏi loại trực tiếp: Tích chọn nếu đây là câu hỏi điều kiện tiên quyết để sàng lọc ứng viên.
* Thiết lập câu trả lời (Dành cho trắc nghiệm):
  * Lựa chọn 1, 2, 3...: Nhập các phương án trả lời.
  * Chọn đáp án đúng: Nhấn vào nút tròn trước mỗi lựa chọn để đánh dấu đó là đáp án đúng.
  * Giải thích (Không bắt buộc): Nhập nội dung giải thích tại sao đáp án đó đúng hoặc sai. Thông tin này giúp ứng viên hiểu rõ hơn sau khi hoàn thành bài test (nếu bạn bật chế độ hiển thị đáp án).

***

#### 💡 Lưu ý quan trọng từ hệ thống:

* Câu hỏi loại trực tiếp: Sẽ loại ứng viên ngay lập tức nếu trả lời sai. Đây là công cụ mạnh mẽ để lọc nhanh những ứng viên không đạt tiêu chuẩn cơ bản.
* Đáp án trắc nghiệm: Phải chọn ít nhất một đáp án đúng cho mỗi câu hỏi.
* Giải thích: Nên cung cấp lời giải chi tiết để nâng cao trải nghiệm của ứng viên khi tương tác với hệ thống tuyển dụng của bạn.

##
