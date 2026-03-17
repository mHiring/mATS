---
icon: question
---

# FAQ

<details>

<summary><mark style="color:blue;">1. Thiết lập sơ đồ tổ chức nhanh từ Excel</mark></summary>

**Ví dụ:** Tôi muốn số hóa toàn bộ sơ đồ tổ chức của công ty gồm 20 phòng ban mà không phải tạo thủ công từng cái.

**Giải pháp:**&#x20;

* Bước 1: Nhấn vào dấu (...) và chọn Nhập dữ liệu (Import).

<figure><img src="../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Tải file Excel chứa danh sách phòng ban, đảm bảo cột "Bộ phận cha" khớp với đơn vị cha cũ đã có trên hệ thống.
* Bước 3: Nhấn Lưu để hệ thống tự động vẽ cây thư mục.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Luôn sử dụng nút Làm mới (↻) sau khi import để đảm bảo Cấu trúc cây hiển thị chính xác các cấp bậc vừa được đồng bộ.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">2. Cá nhân hóa giao diện nhập liệu phòng ban</mark></summary>

**Ví dụ:** Tôi muốn thêm trường "Ngân sách tuyển dụng" vào màn hình thêm mới phòng ban để tiện quản lý.

**Giải pháp:**&#x20;

* Bước 1: Trong cửa sổ Add Unit, nhấn biểu tượng Chỉnh sửa (tờ giấy và bút) ở góc trên bên phải.

<figure><img src="../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Nhấn \[+ Thêm trường], đặt tên là "Ngân sách" và chọn kiểu dữ liệu số.
* Bước 3: Nhấn Lưu để áp dụng cho toàn hệ thống.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Bạn có thể dùng tính năng Thêm phần để nhóm các trường thông tin tự tạo vào một khối riêng, giúp giao diện nhập liệu gọn gàng và dễ nhìn hơn.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">3. Xây dựng cấu trúc đơn vị đa cấp</mark></summary>

**Ví dụ:** Tôi muốn thiết lập hệ thống phòng ban sâu 3 cấp (Khối -> Phòng -> Tổ/Nhóm).

**Giải pháp:**&#x20;

* Bước 1: Tạo đơn vị cấp 1 (Khối), chọn Công ty chủ quản.
* Bước 2: Tạo đơn vị cấp 2 (Phòng), tại mục Bộ phận cha, chọn Khối tương ứng.

<figure><img src="../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

* Bước 3: Lặp lại cho cấp 3 và kiểm tra tại giao diện Cấu trúc cây.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Khi gán Cấp bộ phận, hãy nhất quán để khi lọc báo cáo, bạn có thể xem dữ liệu tổng hợp theo từng cấp độ trên toàn hệ thống.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">4. Phân quyền sàng lọc hồ sơ theo đơn vị</mark></summary>

**Ví dụ:** Tôi muốn trưởng phòng chỉ được xem những hồ sơ ứng tuyển vào đúng phòng ban của mình.

**Giải pháp:**&#x20;

* Bước 1: Tại giao diện Add Unit, chỉ định chính xác Quản lý Bộ phận.

<figure><img src="../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Gán quyền cho tài khoản quản lý này chỉ truy cập vào kho ứng viên thuộc mã đơn vị đó.
* Bước 3: Kiểm tra luồng dữ liệu đổ về từ các tin tuyển dụng gắn với phòng ban này.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Việc gán mã Mã Bộ phận duy nhất giúp hệ thống tự động điều phối ứng viên về đúng "ngăn" trong kho ứng viên, tránh nhầm lẫn giữa các phòng ban cùng tên ở các chi nhánh khác nhau.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">5. Quy trình luân chuyển/Sáp nhập phòng ban</mark></summary>

**Ví dụ:** Công ty thay đổi cơ cấu, tôi cần chuyển một Tổ sản xuất sang dưới quyền quản lý của một Chi nhánh khác.

**Giải pháp:**&#x20;

* Bước 1: Nhấn chỉnh sửa phòng ban đó

<figure><img src="../../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

* Bước 2: Thay đổi mục Bộ phận cha sang đơn vị cha cũ hoặc đơn vị quản lý mới.
* Bước 3: Nhấn Lưu.

{% hint style="success" %}
Mẹo: <mark style="color:green;background-color:green;">Sau khi sáp nhập, hãy dùng chức năng Xuất dữ liệu (Export) để kiểm tra lại tính logic của toàn bộ sơ đồ tổ chức mới trước khi vận hành.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">6.</mark> <mark style="color:blue;">Sơ đồ cấu trúc tập đoàn đa cấp</mark></summary>

**Ví dụ:** Tôi muốn số hóa toàn bộ sơ đồ tổ chức của tổng công ty bao gồm 5 chi nhánh và hơn 50 phòng ban lên hệ thống ngay lập tức mà không phải ngồi nhập liệu thủ công từng đơn vị

**Giải pháp:**&#x20;

1. Bước 1: Chuẩn bị file Excel danh sách đơn vị theo đúng phân cấp _Công ty > Chi nhánh > Phòng ban_.
2. Bước 2: Vào mục (...) chọn Nhập dữ liệu (Import) để đẩy toàn bộ file lên hệ thống.
3. Bước 3: Kiểm tra lại hiển thị tại màn hình Cấu trúc cây để đảm bảo các phòng ban đã nằm đúng chi nhánh chủ quản.&#x20;

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> <mark style="background-color:green;">Luôn kiểm tra cột "Bộ phận cha" trong file Excel để hệ thống tự động vẽ đúng sơ đồ phân cấp ngay sau khi lưu.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">7.</mark> <mark style="color:blue;">Thiết lập luồng phê duyệt hồ sơ theo cấp quản lý</mark></summary>

**Ví dụ:** Tôi muốn hệ thống tự động nhận diện được ai là trưởng bộ phận của từng đơn vị để khi có ứng viên mới, quy trình duyệt hồ sơ trong kho ứng viên được gửi đến đúng người có thẩm quyền.

**Giải pháp:**&#x20;

* Bước 1: Truy cập vào từng đơn vị hoặc sử dụng tính năng import để cập nhật trường Quản lý Bộ phận.
* Bước 2: Xác định Cấp bộ phận (ví dụ: Phòng ban là Cấp 2, Chi nhánh là Cấp 1) để thiết lập phân cấp báo cáo.
* Bước 3: Lưu cấu hình để kích hoạt cơ chế tự động điều hướng thông báo tuyển dụng.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo: Bạn có thể dùng công cụ Cột để hiển thị trường "Trưởng đơn vị" ngay tại danh sách ngoài, giúp rà soát nhanh những phòng ban nào đang bị trống người quản lý.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">8.</mark> <mark style="color:blue;">Tối ưu trải nghiệm làm việc bằng cách tinh gọn giao diện</mark></summary>

**Ví dụ:** Tôi muốn ẩn bớt những trường thông tin không sử dụng đến và sắp xếp lại các ô quan trọng lên đầu để nhân viên của tôi không bị rối mắt khi khởi tạo phòng ban mới.

**Giải pháp:**&#x20;

1. Bước 1: Truy cập giao diện Chỉnh sửa Bố cục (Custom Layout).
2. Bước 2: Nhấn dấu (x) tại các trường không cần thiết và dùng biểu tượng (⠿) để kéo các trường quan trọng lên vị trí ưu tiên.
3. Bước 3: Nhấn Lưu để thay đổi thứ tự xuất hiện của các trường thông tin.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo: Đừng quá lo lắng khi xóa nhầm, bạn luôn có thể thêm lại các trường mặc định thông qua danh sách trường có sẵn trong chế độ chỉnh sửa.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">9.</mark> <mark style="color:blue;">Quản lý tách/nhập phòng ban khi tái cấu trúc doanh nghiệp</mark></summary>

**Ví dụ:** Tôi muốn di chuyển toàn bộ một bộ phận từ Chi nhánh miền Bắc sang Chi nhánh miền Nam trên sơ đồ hệ thống do công ty vừa thay đổi mô hình vận hành.

**Giải pháp:**&#x20;

* Bước 1: Tìm đơn vị cần chuyển trên danh sách và nhấn nút chỉnh sửa.
* Bước 2: Tại trường Bộ phận cha, chọn lại chi nhánh đích (Miền Nam) và cập nhật lại Công ty chủ quản tương ứng.
* Bước 3: Nhấn Lưu để hệ thống tái định vị đơn vị đó trên sơ đồ cây.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo: Khi thay đổi "Bộ phận cha", hãy kiểm tra lại trường Cấp bộ phận để đảm bảo thứ bậc của đơn vị đó vẫn khớp với sơ đồ tổ chức mới.</mark>
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">10.</mark> Tiêu chuẩn hóa quy tắc đặt mã phòng ban toàn hệ thống</summary>

**Ví dụ:** Tôi muốn thiết lập một quy tắc đặt mã bộ phận thống nhất để dễ dàng quản lý và tra cứu nhanh trên hệ thống mà không bị trùng lặp

**Giải pháp:**&#x20;

1. Bước 1: Khi thêm mới đơn vị, kiểm tra trường Mã Bộ phận (hệ thống tự sinh mã duy nhất).
2. Bước 2: Tùy chỉnh mã này theo cấu trúc riêng (ví dụ: BP\_Marketing\_2026).
3. Bước 3: Nhấn Lưu và sử dụng ô Tìm kiếm để thử nghiệm độ chính xác khi tra cứu theo mã.

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark> Mã bộ phận nên bao gồm cả tiền tố của Công ty con hoặc Chi nhánh để khi quản lý tập trung nhiều đơn vị, bạn vẫn nhận diện được phòng ban đó thuộc về đâu chỉ qua mã định danh.
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">1.</mark> </summary>

**Ví dụ:**&#x20;

**Giải pháp:**&#x20;

1. Bước 1:&#x20;
2. Bước 2:&#x20;
3. Bước 3:&#x20;

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark>&#x20;
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">1.</mark> </summary>

**Ví dụ:**&#x20;

**Giải pháp:**&#x20;

1. Bước 1:&#x20;
2. Bước 2:&#x20;
3. Bước 3:&#x20;

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark>&#x20;
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">1.</mark> </summary>

**Ví dụ:**&#x20;

**Giải pháp:**&#x20;

1. Bước 1:&#x20;
2. Bước 2:&#x20;
3. Bước 3:&#x20;

{% hint style="success" %}
<mark style="color:green;background-color:green;">Mẹo:</mark>&#x20;
{% endhint %}

</details>
