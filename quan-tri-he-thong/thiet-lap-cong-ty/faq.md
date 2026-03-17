---
icon: question
---

# FAQ

<details>

<summary><mark style="color:blue;">1. Thiết lập hệ thống công ty đa cấp</mark></summary>

**Ví dụ:** Tôi muốn quản lý các đơn vị theo nhiều cấp bậc (Tổng công ty -> Chi nhánh miền -> Văn phòng đại diện) để dễ dàng phân quyền.

**Giải pháp:**&#x20;

1. Bước 1: Khi tạo đơn vị cấp dưới, tại mục Parent Company, hãy chọn đúng đơn vị cha cũ quản lý trực tiếp cấp đó.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

1. Bước 2: Tích chọn ô Là nhóm cho các đơn vị đóng vai trò quản lý cấp trung.
2. Bước 3: Nhấn Lưu để hình thành cây sơ đồ đa cấp.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Sử dụng biểu tượng mở rộng ở bảng dữ liệu để kiểm tra tính chính xác của các cấp bậc từ cao xuống thấp.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">2. Quản lý dữ liệu theo công ty nhiều chi nhánh</mark></summary>

**Ví dụ:** Tôi muốn phân loại ứng viên theo từng chi nhánh cụ thể để HR tại địa phương đó tự xử lý hồ sơ.

**Giải pháp:**&#x20;

1. Bước 1: Khai báo đầy đủ danh sách chi nhánh kèm Địa chỉ công ty chi tiết.
2. Bước 2: Khi hồ sơ đổ vào kho ứng viên, sử dụng bộ lọc theo tên chi nhánh để phân loại.

<figure><img src="../../.gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

3. Bước 3: Gán quyền truy cập cho HR chi nhánh chỉ được xem dữ liệu thuộc chi nhánh đó.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo: Tại phần Tổng quan, hãy ghi chú rõ mã vùng của chi nhánh để việc tìm kiếm trong kho ứng viên diễn ra nhanh chóng hơn.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">3. Đồng bộ báo cáo cho toàn bộ chi nhánh</mark></summary>

**Ví dụ:** Tôi muốn xuất dữ liệu của tất cả chi nhánh để so sánh hiệu quả tuyển dụng trên toàn hệ thống.

**Giải pháp:**&#x20;

1. Bước 1: Tại màn hình chính, sử dụng bộ lọc để chọn các chi nhánh cần báo cáo.
2. Bước 2: Nhấn vào Dấu ba chấm (...) và chọn Xuất dữ liệu (Export).

<figure><img src="../../.gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>

3. Bước 3: Sử dụng file dữ liệu để tổng hợp báo cáo tổng.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Hãy kiểm tra và cập nhật Trạng thái của các chi nhánh trước khi xuất dữ liệu để đảm bảo báo cáo chỉ bao gồm các đơn vị đang hoạt động.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">4. Xử lý trùng lặp chi nhánh trên hệ thống</mark></summary>

**Ví dụ:** Hệ thống đang tồn tại nhiều bản ghi cho cùng một chi nhánh, dẫn đến việc ứng viên trong kho ứng viên bị phân tán.

**Giải pháp:**&#x20;

* Bước 1: Dùng công cụ Tìm kiếm để lọc ra các bản ghi trùng tên chi nhánh.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Chọn một bản ghi đầy đủ thông tin nhất, gán lại đơn vị cha cũ.
* Bước 3: Chuyển các bản ghi thừa về trạng thái "Không hoạt động".

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo: Luôn quy định đặt Mã công ty duy nhất cho mỗi chi nhánh để hệ thống tự động cảnh báo nếu có sự trùng lặp trong tương lai.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">5. Điều chỉnh cơ cấu đơn vị đa cấp nhanh chóng</mark></summary>

**Ví dụ:** Một văn phòng đại diện vừa được nâng cấp thành chi nhánh trực thuộc đơn vị cha cũ, tôi cần thay đổi trên hệ thống.

**Giải pháp:**&#x20;

1. Bước 1: Vào phần chỉnh sửa thông tin của đơn vị đó.

<figure><img src="../../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

2. Bước 2: Cập nhật lại mục Parent Company và tích chọn thêm ô Là nhóm (nếu cần).
3. Bước 3: Nhấn Lưu để cập nhật vị trí mới trên sơ đồ đa cấp.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Sau khi thay đổi, hãy dùng tính năng Làm mới (↻) để đảm bảo các báo cáo liên quan đến kho ứng viên cập nhật theo sơ đồ mới.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">6. Đồng bộ dữ liệu từ file Excel</mark></summary>

**Ví dụ:** Tôi muốn đưa danh sách 50 chi nhánh từ đơn vị cha cũ vào hệ thống cùng lúc thay vì tạo lẻ.

**Giải pháp:**&#x20;

1. Bước 1: Nhấn vào biểu tượng Dấu ba chấm (...) ở góc phải.
2. Bước 2: Chọn chức năng Nhập dữ liệu (Import).

<figure><img src="../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

3. Bước 3: Tải lên file Excel theo định dạng mẫu của hệ thống.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Luôn nhấn nút Làm mới (↻) sau khi import để hệ thống cập nhật và hiển thị danh sách mới nhất vừa được đồng bộ.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">7.</mark> <mark style="color:blue;">Xuất dữ liệu để đánh giá định kỳ</mark></summary>

**Ví dụ:** Tôi cần danh sách toàn bộ công ty chi nhánh để làm báo cáo đánh giá chất lượng nguồn ứng viên hàng tháng.

**Giải pháp:**&#x20;

* Bước 1: Thiết lập các bộ lọc cần thiết (theo Ngành nghề hoặc Quy mô).
* Bước 2: Nhấn vào dấu ba chấm (...).
* Bước 3: Chọn Xuất dữ liệu (Export) để tải file Excel về máy.

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Mẹo: Sử dụng tính năng Sắp xếp trước khi xuất để dữ liệu trong file Excel được tổ chức khoa học theo yêu cầu của bạn.
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">8. Khởi tạo hồ sơ công ty nhanh bằng AI</mark></summary>

**Ví dụ:** Tôi muốn tạo nhanh một hồ sơ công ty mà không cần nhập liệu thủ công từng trường thông tin.

**Giải pháp:**&#x20;

1. Bước 1: Nhấn nút \[+ Tạo mới], sau đó chọn biểu tượng AI ở góc trên bên phải.
2. Bước 2: Nhập URL website của doanh nghiệp vào ô địa chỉ.

<figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

3. Bước 3: Nhấn \[Tạo] để hệ thống tự điền tên, ngành nghề và mô tả.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Sau khi AI hoàn tất, hãy kiểm tra lại mục Tổng quan để bổ sung từ khóa đặc thù giúp việc lọc trong kho ứng viên sau này chính xác hơn.</mark>
{% endhint %}

</details>

