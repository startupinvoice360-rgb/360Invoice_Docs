# Spa - Salon - Massage - Làm đẹp

**Tổng quan chức năng**

Hướng dẫn bạn 3 quy trình cốt lõi để vận hành trơn tru một cơ sở Spa/Salon trên ứng dụng:

1. **Thiết lập danh mục**: Phân loại và khai báo sản phẩm vật lý và gói dịch vụ.
2. **Nhập hàng hóa:** Ghi nhận số lượng mỹ phẩm, vật tư mua từ nhà cung cấp vào kho.
3. **Tạo đơn bán hàng**: Tính tiền dịch vụ và sản phẩm khách đã mua để in hóa đơn.

**Phần 1: Khai báo Sản phẩm và Dịch vụ (Hàng hóa)**

Bước này giúp bạn đưa toàn bộ bảng giá dịch vụ và mỹ phẩm đang kinh doanh vào hệ thống.

**Bước 1: Tạo Nhóm mặt hàng (Danh mục)**

1. Tại trang chủ, chọn mục Hàng hóa

<figure><img src="../../.gitbook/assets/image (319).png" alt="" width="236"><figcaption></figcaption></figure>

2. Nhấn vào dấu (+) ở góc phải, chọn Thêm nhóm mặt hàng.

<div><figure><img src="../../.gitbook/assets/image (320).png" alt="" width="235"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (321).png" alt="" width="236"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (322).png" alt="" width="238"><figcaption></figcaption></figure></div>

3. Lần lượt tạo 2 nhóm: "Sản phẩm vật lý" và "Dịch vụ". Nhấn Tạo nhóm mặt hàng để lưu.

<div><figure><img src="../../.gitbook/assets/image (323).png" alt="" width="235"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (324).png" alt="" width="235"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (326).png" alt="" width="233"><figcaption></figcaption></figure></div>

**Bước 2: Thêm sản phẩm vật  lý (Mỹ phẩm bán lẻ / sử dụng)**

1. **Tại mục Hàng hóa, nhấn dấu (+), chọn Thêm mặt hàng.**

<div><figure><img src="../../.gitbook/assets/image (327).png" alt="" width="236"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (328).png" alt="" width="234"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (329).png" alt="" width="235"><figcaption></figcaption></figure></div>

2. Nhập thông tin mỹ phẩm:

* Tên mặt hàng: Ví dụ "Sữa rửa mặt".
* Đơn vị tính: Nhập "Chai", "Hộp" hoặc "Lọ".

<figure><img src="../../.gitbook/assets/image (330).png" alt="" width="239"><figcaption></figcaption></figure>

* Giá nhập / Giá bán lẻ: Điền mức giá tương ứng (Ví dụ: Nhập 150.000đ, Bán lẻ 200.000đ).
*

    <figure><img src="../../.gitbook/assets/image (331).png" alt="" width="234"><figcaption></figcaption></figure>
* Nhóm hàng: Chọn "Sản phẩm vật lý".

<div><figure><img src="../../.gitbook/assets/image (332).png" alt="" width="236"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (333).png" alt="" width="236"><figcaption></figcaption></figure></div>

3. Cài đặt Kho hàng (Bắt buộc): Kéo xuống dưới, bật công tắc Khởi tạo kho hàng và nhập số lượng hiện đang có sẵn tại cửa hàng (Ví dụ: 12 chai) và nhấn Tạo mặt hàng.

<div><figure><img src="../../.gitbook/assets/image (334).png" alt="" width="234"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (335).png" alt="" width="237"><figcaption></figcaption></figure></div>

**Bước 3: Thêm Dịch vụ Spa / Salon**

1. Tiếp tục thao tác Thêm mặt hàng.

<figure><img src="../../.gitbook/assets/image (336).png" alt="" width="231"><figcaption></figcaption></figure>

2. Nhập thông tin dịch vụ:

* Tên mặt hàng: Ví dụ "Trị mụn", "Gội đầu dưỡng sinh".

<figure><img src="../../.gitbook/assets/image (337).png" alt="" width="234"><figcaption></figcaption></figure>

* Giá bán lẻ: Mức giá thu của khách (Ví dụ: 2.000.000đ). _Bỏ qua Giá nhập._

<figure><img src="../../.gitbook/assets/image (338).png" alt="" width="229"><figcaption></figcaption></figure>

* Nhóm hàng: Chọn "Dịch vụ".

<figure><img src="../../.gitbook/assets/image (339).png" alt="" width="235"><figcaption></figcaption></figure>

3. Cài đặt dịch vụ (Quan trọng): Kéo xuống dưới, bạn phải bật công tắc Cho phép bán âm. Dịch vụ là công sức, không phải hàng hóa nên không bị giới hạn số lượng tồn kho. Và nhấn **Tạo mặt hàng**

<div><figure><img src="../../.gitbook/assets/image (341).png" alt="" width="234"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (340).png" alt="" width="235"><figcaption></figcaption></figure></div>

**Phần 2: Nhập hàng hóa vào kho**

Khi hết mỹ phẩm và cần mua thêm từ nhà cung cấp, bạn thao tác như sau để cộng dồn vào kho:

1. Tại màn hình Trang chủ, chọn nút Nhập hàng (màu xanh lá cây).

<figure><img src="../../.gitbook/assets/image (342).png" alt="" width="233"><figcaption></figcaption></figure>

2. Tại ô nhập tên nhà cung cấp, gõ tên (Ví dụ: "nhà 2") và nhấn Thêm mới nhà cung cấp (điền thêm số điện thoại nếu cần).

<figure><img src="../../.gitbook/assets/image (343).png" alt="" width="234"><figcaption></figcaption></figure>

3. Tại phần Chọn mặt hàng, tìm và chọn mỹ phẩm bạn vừa mua (Ví dụ: "Sữa rửa mặt"). Nhấn Tiếp tục đơn hàng.

<figure><img src="../../.gitbook/assets/image (345).png" alt="" width="247"><figcaption></figcaption></figure>

4. Chạm vào ô số lượng để điền số chai/hộp vừa nhập (Ví dụ: 10 chai). Hệ thống sẽ tự tính Tổng tiền dựa trên Giá nhập bạn đã cài ở Phần 1. ---> Chọn Hình thức thanh toán với nhà cung cấp (Tiền mặt/Chuyển khoản).

<figure><img src="../../.gitbook/assets/image (346).png" alt="" width="238"><figcaption></figcaption></figure>

5. Nhấn nút Tạo hóa đơn. Lúc này, số lượng mỹ phẩm trong kho sẽ tự động được cộng thêm.

<figure><img src="../../.gitbook/assets/image (349).png" alt=""><figcaption></figcaption></figure>

**PHẦN 3: Tính tiền và Tạo hóa đơn cho khách**

Khi khách hàng làm xong dịch vụ và mua thêm sản phẩm mới đem về, bạn thao tác thanh toán:

1. Tại Trang chủ, nhấn vào nút Tạo đơn (màu xanh lá cây).

<figure><img src="../../.gitbook/assets/image (350).png" alt="" width="234"><figcaption></figcaption></figure>

2. Tại ô Nhập tên khách, gõ tên khách hàng (Ví dụ: "Nhi"). _Có thể lưu thêm thông tin khách để chăm sóc hậu mãi. --->_ Tại danh sách bên dưới, chạm để chọn các dịch vụ khách đã làm và sản phẩm khách mua mang về (Ví dụ: chọn cả "Trị mụn" và "Sữa rửa mặt") và nhấn tiếp tục đơn hàng.

<figure><img src="../../.gitbook/assets/image (352).png" alt="" width="238"><figcaption></figcaption></figure>

3. Nhấn dấu (+) hoặc chạm vào ô số lượng để điều chỉnh nếu khách mua nhiều hơn 1 sản phẩm. Hệ thống sẽ tự động cộng dồn Tổng tiền thanh toán. ---> Chọn Hình thức T.Toán của khách.

<figure><img src="../../.gitbook/assets/image (353).png" alt=""><figcaption></figcaption></figure>

4. Nhấn Tạo hóa đơn, sau đó nhấn In hóa đơn để in bill đưa cho khách.

<div><figure><img src="../../.gitbook/assets/image (354).png" alt="" width="234"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (355).png" alt="" width="235"><figcaption></figcaption></figure></div>
