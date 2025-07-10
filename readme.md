# 📘 Ứng dụng Quản Lý Cầm Đồ – *v1.3*

> Phần mềm quản lý cầm đồ đơn giản, hiện đại, dễ sử dụng.  
> Phù hợp cho cửa hàng từ nhỏ đến vừa – tối ưu thao tác, in ấn, và quản lý lãi suất linh hoạt.

---

## 📥 Tải xuống & cài đặt

- 🔗 **Tải phần mềm tại**: [github.com/whoamilittl3fish/QuanLyHopDong/releases](https://github.com/whoamilittl3fish/QuanLyHopDong/releases)

### 🛠 Các bước cài đặt:

1. Truy cập link trên
2. Kéo xuống phần **Assets** của phiên bản mới nhất
3. Tải file **`Setup_QuanLyHopDong.exe`**
4. Chạy để cài đặt phần mềm
5. Nhập key bản quyền để sử dụng đầy đủ tính năng

---

## 📞 Liên hệ & hỗ trợ

- **SĐT**: 0966 346 694  
- **Email**: khoa.ngovoviet@gmail.com  
- **GitHub**: [github.com/whoamilittl3fish/QuanLyHopDong](https://github.com/whoamilittl3fish/QuanLyHopDong)

> 💬 Mọi ý kiến đóng góp vui lòng gửi email hoặc tạo Issue trên GitHub.  
🙏 Xin chân thành cảm ơn bạn đã sử dụng phần mềm!

---

## ✅ Tính năng chính

- Quản lý hợp đồng vay: tạo / sửa / in PDF
- Tự động tính lãi theo kỳ, tính số ngày từ kỳ gần nhất
- Ghi nhận lịch sử đóng lãi, hỗ trợ gia hạn thông minh
- Tìm kiếm không dấu, lọc theo tên, mã, loại tài sản, tình trạng, khoảng thời gian
- Quản lý trạng thái: Đang vay, Sắp tới hạn, Quá hạn, Tất toán, Đã chuộc
- In hợp đồng và lịch sử đóng lãi bằng mẫu Word hoặc PDF (QuestPDF)
- Thống kê tổng lãi thu trong tháng, tổng hợp đồng, tổng tiền đang cho vay
- Hệ thống bản quyền vĩnh viễn theo phần cứng (HWID), có mã hóa
- Hỗ trợ định dạng số tiền và ngày tháng chuẩn quốc tế (`dd-MM-yyyy`)
- Giao diện bo tròn, dễ dùng, tối ưu cho Full HD (1920x1080)

---

## 🎨 Mã màu hợp đồng

| Trạng thái                     | Màu sắc      |
|-------------------------------|--------------|
| Đang vay                      | Trắng        |
| Sắp tới hạn                   | Vàng         |
| Tới hạn hôm nay (chưa đóng)  | Xanh lá sáng |
| Tới hạn hôm nay (đã đóng)    | Xanh lá đậm  |
| Quá hạn                       | Đỏ           |
| Đã chuộc                      | Xám đậm      |
| Đã đóng lãi tất cả kỳ        | Xám nhạt     |

---

## 💡 Ghi chú sử dụng

- **Tạo hợp đồng**: lưu người tạo và thời gian tạo  
- **Sửa hợp đồng**: chỉ khi chưa có kỳ lãi nào được đóng  
- **Đóng lãi**: ghi chi tiết từng kỳ, cập nhật đúng theo ngày  
- **Gia hạn**: tự động thêm kỳ tiếp theo, đánh dấu kỳ đầu chưa đóng  
- **Tất toán**: kết thúc hợp đồng, không thể chỉnh sửa nữa

---

## 🖥️ Yêu cầu hệ thống

- Hệ điều hành: Windows 10 hoặc cao hơn  
- Cần cài: [.NET Desktop Runtime 8.0+](https://dotnet.microsoft.com/en-us/download/dotnet/8.0/runtime)  
- Không cần SQL Server – phần mềm dùng SQLite tích hợp sẵn

---

## 📦 Cập nhật tính năng

### 🆕 v1.3 (10/07/2025)

- 🖼️ **Cải tiến toàn bộ giao diện**
  - Giao diện thêm hợp đồng, hộp thoại Yes/No, form ghi chú bo góc, hiện đại
  - Tông màu sáng, đồng bộ, hiển thị rõ ràng trên Full HD
  - Cảnh báo chi tiết khi tệp PDF đang bị mở lúc xuất hợp đồng

- 📊 **Thống kê nâng cao khi tìm kiếm**
  - Tổng tiền đang cho vay  
  - Tổng lãi đã thu (bao gồm tiền khác)  
  - Tổng lãi đến hôm nay (đã trừ các kỳ đóng trước)

- ✅ **Thêm checkbox lọc hợp đồng hết hiệu lực**
  - Cho phép hiển thị cả hợp đồng đã chuộc hoặc thanh lý
  - Tối ưu với View riêng và truy vấn transaction nhanh

- 🔄 **Cập nhật dữ liệu `LaiDenHomNay`**
  - Tự động lưu khi đóng lãi
  - Trừ đúng các kỳ đã thanh toán

- ⏳ **Phân trang tối ưu theo thời gian tạo**
  - Truy vấn nhanh hơn, sắp xếp chính xác theo `CreatedAt`

- 🧾 **In ấn chuẩn chỉnh**
  - Hỗ trợ định dạng ngày `dd-MM-yyyy`
  - Đọc số tiền bằng chữ tiếng Việt tự nhiên

---

### ✅ v1.2.10 – Chuẩn hóa tiền tệ & ngày tháng

- 💰 Định dạng số tiền theo chuẩn quốc tế: `1,000,000.00`
- 🌐 Tương thích nhiều ngôn ngữ hệ điều hành
- 📅 Hiển thị ngày kiểu `dd - MM - yyyy`, căn giữa trong DateTimePicker
- 🖥️ Giao diện chọn ngày ổn định, dễ dùng

---

### ✅ v1.2.9 – Bảo mật bằng mật khẩu

- Đặt mật khẩu đăng nhập
- Xác nhận thao tác quan trọng
- Giao diện đổi mật khẩu chuyên nghiệp

---

### ✅ v1.2.8 – Cập nhật phần mềm tự động

- Tải bản mới từ GitHub
- Giao diện cập nhật có hiệu ứng & hiển thị tiến trình

---

### ✅ v1.2.7 – Chuẩn hóa định dạng ngày

- Đồng bộ `dd-MM-yyyy` toàn hệ thống
- Lịch sử rõ ràng, nhóm theo thời gian

---

### ✅ v1.2.6 – Thống kê theo tháng

- Ghi nhận doanh thu theo từng tháng cố định
- Dữ liệu không thay đổi khi sửa hoặc xoá hợp đồng

---

### ✅ v1.2.5 – Tối ưu trải nghiệm người dùng

- Thông báo lỗi rõ ràng
- Màu sắc bảng đóng lãi dễ nhận biết

---

### ✅ v1.1 – Phiên bản chính thức đầu tiên

- Quản lý hợp đồng, kỳ lãi, lịch sử đóng lãi
- Tính lãi tự động
- In hợp đồng, lọc tìm kiếm, thống kê cơ bản

---

### 🔖 v1.0 – Bản thử nghiệm nội bộ

- Giao diện đơn giản
- Chưa có bản quyền
- Quản lý hợp đồng cơ bản

---
