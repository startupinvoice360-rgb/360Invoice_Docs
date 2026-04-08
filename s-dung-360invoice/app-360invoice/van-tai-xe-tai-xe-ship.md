# Vận tải - Xe tải - Xe ship

**Tổng quan chức năng**

Hướng dẫn cách sử dụng ứng dụng để quản lý dịch vụ vận tải, bao gồm 3 phần chính:

1. Thiết lập dịch vụ: Khai báo các loại xe hoặc dịch vụ vận chuyển.
2. Ghi nhận chi phí: Quản lý các khoản chi tiêu phát sinh như tiền đổ xăng, sửa xe.
3. Thu cước vận chuyển: Tạo đơn hàng, tính tiền cước cho khách in hóa đơn.

Phần 1: Khai báo Dịch vụ vận tải (Thêm sản phẩm)

Bước này giúp bạn thiết lập mức giá cước vận chuyển (theo Km hoặc theo chuyến) vào hệ thống.

1. Tại màn hình Trang chủ, chọn mục **Sản phẩm.**

<figure><img src="../../.gitbook/assets/image (167).png" alt="" width="251"><figcaption></figcaption></figure>

2. Nhấn vào biểu tượng dấu (+), chọn Thêm sản phẩm và điền các thông tin của dịch vụ:

* Tên sản phẩm: Nhập tên dịch vụ (Ví dụ: "Thuê xe tải" hoặc "Xe tải biển số A").
* Đơn vị tính: Nhập đơn vị đo lường cước phí (Ví dụ: "km", "chuyến", "giờ").
* Giá bán lẻ: Nhập mức giá tương ứng với 1 đơn vị tính (Ví dụ: "15.000" đồng/km).

<div><figure><img src="../../.gitbook/assets/image (168).png" alt="" width="248"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (170).png" alt="" width="249"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (169).png" alt="" width="249"><figcaption></figcaption></figure></div>

3. Cài đặt Kho hàng (Quan trọng): Kéo xuống dưới, bạn bắt buộc phải bật công tắc Cho phép bán âm (Chuyển sang màu xanh). Do đây là dịch vụ, không phải hàng hóa vật lý nên sẽ không có số lượng tồn kho. Lưu ý: Bỏ qua phần nhập số lượng và giá nhập. Và nhấn nút Tạo SP để lưu lại.

<figure><img src="../../.gitbook/assets/image (171).png" alt="" width="254"><figcaption></figcaption></figure>

**Phần 2: Quản lý chi phí phát sinh (Thu/chi)**

Mô hình vận tải sẽ phát sinh nhiều chi phí hàng ngày như xăng dầu, bến bãi, sửa xe. Bạn cần ghi nhận lại để theo dõi lợi nhuận chính xác.&#x20;

1. Tại màn hình Trang chủ, chọn thư mục **Thu chi**

<figure><img src="../../.gitbook/assets/image (172).png" alt="" width="247"><figcaption></figcaption></figure>

2. Nhấn vào biểu tượng dấu cộng (+) ở góc phải dưới, chọn nút Tạo phiếu chi (Màu đỏ).

<figure><img src="../../.gitbook/assets/image (173).png" alt="" width="249"><figcaption></figcaption></figure>

3. Điền các thông tin chi tiêu:

* Nhóm người nhận: Chọn "Nhân viên" (nếu chi cho tài xế) hoặc "Đối tượng khác".
* Tên người nhận: Nhập tên người nhận tiền (Ví dụ: "Anh Thành").
* Chọn loại phiếu: Nhấn vào và chọn loại chi phí phù hợp (Ví dụ: "Chi phí nguyên vật liệu", "Chi phí khác"...).
* Số tiền chi: Nhập số tiền đã chi (Ví dụ: "500.000").
* Ghi chú: Ghi rõ nội dung chi để sau này dễ kiểm tra (Ví dụ: "Đổ xăng xe tải").

<figure><img src="../../.gitbook/assets/image (174).png" alt="" width="246"><figcaption></figcaption></figure>

4. Đảm bảo đã tick chọn ô Hoạch toán kết quả kinh doanh.
5. Nhấn nút Tạo phiếu chi để lưu lại. Bạn có thể xem lại danh sách tất cả các khoản thu/chi ở màn hình này.

<div><figure><img src="../../.gitbook/assets/image (175).png" alt="" width="251"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (176).png" alt="" width="247"><figcaption></figcaption></figure></div>

**Phần 3: Tính tiền cước vận chuyển (Thao tác bán hàng)**

**Khi hoàn thành di chuyển đi và thu tiền cước của khách, bạn thực hiện các bước sau:**

1. **Tại màn hình Trang chủ, nhấn vào nút Bán hàng.**

<figure><img src="../../.gitbook/assets/image (178).png" alt="" width="251"><figcaption></figcaption></figure>

2. Nhập tên khách hàng vào ô Nhập tên khách (Ví dụ: Quân).
3. Chạm vào dịch vụ vận chuyển khách đã sử dụng (Ví dụ: Thuê xe tải) và nhấn Tiếp tục đơn hàng

<div><figure><img src="../../.gitbook/assets/image (181).png" alt="" width="233"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (182).png" alt="" width="232"><figcaption></figcaption></figure></div>

4. Tại mục số lượng, nhập tổng số đơn vị tính (Km hoặc Chuyến) mà khách đã đi.

* Ví dụ: Xe chở hàng đi 10km, bạn đổi số 1 thành số 10. Hệ thống sẽ tự động nhân với giá cước 15.000đ/km để ra tổng tiền là 150.000đ. Sau đó chọn hình thức thanh toán (Tiền  mặt, Chuyển khoản...). Cuối cùng nhấn nút Tạo đơn.

<figure><img src="../../.gitbook/assets/image (183).png" alt="" width="236"><figcaption></figcaption></figure>

5. Màn hình sẽ hiển thị Hóa đơn bán hàng. Nhấn nút In hóa đơn để xuất biên lai thu tiền gửi cho khách.

<figure><img src="../../.gitbook/assets/image (184).png" alt="" width="234"><figcaption></figcaption></figure>

**Lưu ý và Mẹo cho ngành Vận tải**&#x20;

* Kiểm soát chặt chẽ thu chi: Việc tạo Phiếu chi cho mỗi lần đổ xăng hay sửa xe là cực kỳ quan trọng để hệ thống có thể tính toán chính xác số tiền lãi cuối tháng cho bạn.
* Luôn bật "Bán âm": Giống như mô hình gia sư, dịch vụ vận tải cần được bật tính năng "Cho phép bán âm" khi tạo mới để không bị lỗi báo hết hàng.
