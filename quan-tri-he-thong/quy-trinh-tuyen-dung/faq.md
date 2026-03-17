---
icon: question
---

# FAQ

<details>

<summary><mark style="color:blue;">1. Thiết lập luồng tuyển dụng mới từ đầu</mark></summary>

**Ví dụ:** Tôi muốn xây dựng một hành trình ứng tuyển riêng biệt cho vị trí thực tập sinh để không bị lẫn với nhân viên chính thức.

**Giải pháp:**&#x20;

* Bước 1: Tại màn hình chính, nhấn nút \[+ Tạo quy trình tuyển dụng].
* Bước 2: Nhập tên quy trình và bật trạng thái Đang hoạt động.

<figure><img src="../../.gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>

* Bước 3 Tại phần Các giai đoạn, nhấn \[+ Thêm Giai đoạn] để vẽ lộ trình từ "Nhận hồ sơ" đến "Thử việc".

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo</mark>: <mark style="color:green;background-color:green;">Nếu quy trình thực tập sinh được dùng thường xuyên, hãy tích chọn "Là mặc định" để hệ thống tự động ưu tiên luồng này khi bạn tạo tin tuyển dụng mới.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">2. Nhân bản nhanh quy trình tương tự</mark></summary>

**Ví dụ:** Tôi muốn tạo quy trình cho vị trí "Kế toán" dựa trên khung có sẵn của "Hành chính" để tránh phải nhập lại các bước thủ công.

**Giải pháp:**&#x20;

* Bước 1: Tìm quy trình "Hành chính" trong bảng danh sách.
* Bước 2: Nhấp vào biểu tượng Nhân bản (Copy) ở cột công cụ nhanh.

<figure><img src="../../.gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>

* Bước 3 Chỉnh sửa lại tên và các giai đoạn đặc thù nếu cần.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo</mark>: <mark style="color:green;background-color:green;">Việc nhân bản sẽ giúp bạn sao chép nguyên vẹn các thiết lập tự động hóa (email, bài test) từ quy trình cũ, giúp tiết kiệm 80% thời gian cấu hình.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">3. Chèn thêm vòng đánh giá bổ sung</mark></summary>

**Ví dụ:** Quy trình hiện tại thiếu vòng "Phỏng vấn với Giám đốc", tôi muốn chèn thêm vào giữa mà không làm xáo trộn luồng.

**Giải pháp:**&#x20;

* Bước 1: Nhấn vào biểu tượng Cấu hình (Bánh răng) tại quy trình cần sửa.
* Bước 2: Chọn \[+ Thêm Giai đoạn] và nhập tên "Phỏng vấn với CEO".

<figure><img src="../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

* Bước 3: Điều chỉnh số Trình tự để chèn đúng vị trí mong muốn.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> <mark style="color:green;background-color:green;">Khi bạn thay đổi số trình tự, hệ thống sẽ tự động đẩy các giai đoạn có số thứ tự trùng hoặc lớn hơn xuống phía sau để đảm bảo tính liên tục của luồng.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">4. Tự động gửi bài Test khi nộp hồ sơ</mark></summary>

**Ví dụ:** Tôi muốn ứng viên trong kho ứng viên nhận được đề bài kiểm tra ngay lập tức khi họ vừa nộp đơn thành công.

**Giải pháp:**&#x20;

* Bước 1: Tại giai đoạn "Đơn ứng tuyển mới", nhấn \[+ Thêm bước vào...] để tạo bước "Gửi test IQ".
* Bước 2: Nhấn biểu tượng Bánh răng (Cài đặt) tại bước này để thiết lập tự động hóa.

<figure><img src="../../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

* Bước 3: Chọn Trigger "Khi có ứng viên vào bước này" và chọn hành động "Gửi Email".

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> <mark style="color:green;background-color:green;">Bạn có thể chọn thêm hành động "Thông báo cho Nhóm" để bộ phận tuyển dụng nhận được tin nhắn qua hệ thống ngay khi có ứng viên mới bắt đầu làm bài.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">5. Chuẩn hóa các bước xử lý nội bộ</mark></summary>

**Ví dụ:** Làm sao để nhân viên HR biết chính xác cần làm gì (gọi điện, check hồ sơ) trong từng giai đoạn?

**Giải pháp:**&#x20;

* Bước 1: Tại mỗi Giai đoạn tuyển dụng, nhấn \[+ Thêm bước] để cụ thể hóa các hành động.

<figure><img src="../../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Đặt tên bước rõ ràng (ví dụ: "Sàng lọc hồ sơ", "Check tham chiếu").
* Bước 3 Sắp xếp Thứ tự thực hiện các bước này bên trong giai đoạn.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> <mark style="color:green;background-color:green;">Sử dụng phần Mô tả khi thêm giai đoạn để ghi chú các tiêu chuẩn đạt/loại, giúp toàn đội ngũ HR làm việc thống nhất theo một tiêu chuẩn chung.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">6. Tự động mời phỏng vấn sau bài test</mark></summary>

**Ví dụ:** Nếu ứng viên hoàn thành bài kiểm tra, tôi muốn hệ thống tự động gửi link đặt lịch phỏng vấn Video.

**Giải pháp:**&#x20;

* Bước 1: Vào cài đặt tự động hóa tại bước tương ứng.
* Bước 2: Chọn Trigger là "Khi hoàn thành bài kiểm tra".

<figure><img src="../../.gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>

* Bước 3 Chọn hành động "Lên lịch phỏng vấn Video qua Email".

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> <mark style="color:green;background-color:green;">Hãy thiết lập thêm một hành động "Giao tiếp: Gửi thư mời" đi kèm để ứng viên cảm thấy được quan tâm ngay sau khi họ nỗ lực hoàn thành bài thi.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">7. Phản hồi ứng viên quá chậm</mark></summary>

**Ví dụ:** Ứng viên thường bỏ sang công ty khác vì chúng tôi mất quá nhiều thời gian để gửi thư mời nhận việc (Offer).

**Giải pháp:**&#x20;

* Bước 1: Tại giai đoạn "Đề nghị nhận việc", thiết lập quy tắc tự động hóa.

<figure><img src="../../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Chọn hành động "Gửi thư mời nhận việc" ngay khi hồ sơ chuyển vào bước này.
* Bước 3: Chọn mẫu thư chuyên nghiệp đã soạn sẵn.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Việc tự động hóa giúp bạn phản hồi ứng viên trong "thời điểm vàng", ngay khi họ đang có thiện cảm tốt nhất với công ty sau các vòng phỏng vấn.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">8. Quy trình quá rườm rà</mark></summary>

**Ví dụ:** Tôi không biết quy trình nào đang có quá nhiều bước dư thừa làm chậm tốc độ tuyển dụng.

**Giải pháp:**&#x20;

* Bước 1: Kiểm tra bảng Phân tích quy trình ở góc trên màn hình thiết lập.

<figure><img src="../../.gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Theo dõi tổng số giai đoạn và số lượng bước Thủ công/Tự động.
* Bước 3 Loại bỏ các bước không cần thiết bằng biểu tượng Thùng rác (Xóa).

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Một quy trình hiệu quả nên có sự cân bằng giữa các bước tự động hóa để tăng tốc độ và các bước thủ công để đảm bảo chất lượng đánh giá con người.</mark>
{% endhint %}

</details>
