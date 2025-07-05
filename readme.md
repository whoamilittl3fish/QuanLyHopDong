# 📘 Ứng dụng Quản Lý Cầm Đồ

Phần mềm quản lý cầm đồ đơn giản, giao diện hiện đại, dễ sử dụng. Phù hợp cho cửa hàng nhỏ đến vừa.

---

## 🚀 Phiên bản hiện tại: **v1.2.7**

> Lịch sử thao tác hợp đồng hiển thị rõ ràng hơn, đồng bộ định dạng ngày dd-MM-yyyy

---

## ✅ Tính năng chính

- Quản lý hợp đồng vay (tạo / sửa / in)
- Tự động tính lãi theo kỳ, hiển thị số ngày từ kỳ gần nhất
- Tạo kỳ lãi đầu tiên ngay khi thêm hoặc sửa hợp đồng
- Lịch sử đóng lãi chi tiết từng kỳ, hỗ trợ gia hạn thông minh
- Tìm kiếm không dấu, hỗ trợ lọc nâng cao (tên, mã, loại tài sản, tình trạng, thời gian)
- Quản lý trạng thái hợp đồng: Đang vay, Sắp tới hạn, Quá hạn, Tất toán...
- In hợp đồng và lịch sử đóng lãi bằng mẫu Word hoặc PDF (QuestPDF)
- Thống kê tiền lãi, số hợp đồng và tổng tiền đang vay
- Giao diện tối ưu cho màn hình Full HD
- Bảo mật bằng key bản quyền vĩnh viễn (gắn với phần cứng)

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

- **Tạo hợp đồng**: lưu thời gian và người tạo  
- **Sửa hợp đồng**: chỉ khi chưa có kỳ lãi nào  
- **Đóng lãi**: ghi nhận chi tiết từng kỳ  
- **Gia hạn**: tự động thêm kỳ, đánh dấu kỳ đầu chưa đóng  
- **Tất toán**: kết thúc hợp đồng, không thể chỉnh sửa

---

## 📊 Thống kê

- Số hợp đồng đang vay: XX  
- Tổng tiền đang cho vay: XXX,XXX,000 VNĐ  
- Tổng lãi đã thu trong tháng: XX,XXX,000 VNĐ  

---

## 📦 Cập nhật tính năng

### 🆕 v1.2.7

- 📅 **Chuẩn hóa toàn bộ định dạng ngày** về dạng `dd-MM-yyyy`, áp dụng trên:
  - Lịch sử đóng lãi
  - Ghi chú thao tác hợp đồng
  - File PDF hợp đồng in ra

- ✍️ **Lịch sử hợp đồng hiển thị rõ ràng, dễ tra cứu hơn**:
  - Các tiêu đề như `GIA HẠN HỢP ĐỒNG`, `CHUỘC HỢP ĐỒNG`, `TẠO/SỬA HỢP ĐỒNG` được **căn giữa bằng dấu gạch ngang**
  - Các dòng thông tin được căn đều bằng dấu `_____`, giúp nhìn gọn, chuyên nghiệp hơn
  - Mỗi thao tác lưu lịch sử sẽ ghi chi tiết `Thời gian`, `Số ngày gia hạn`, `Kỳ lãi`,… tùy theo loại thao tác

- 📜 Ghi chú thao tác trong hệ thống (`Tạo`, `Sửa`, `Gia hạn`, `Chuộc`, `Cập nhật tình trạng`, `Đóng lãi`) đều có cấu trúc thống nhất – giúp **dễ rà soát lại lịch sử** theo thời gian

---

### ✅ v1.2.6

- 📊 **Thống kê cố định theo tháng**:
  - Ghi lại **tổng tiền đã thu** và **số hợp đồng đã thu** vào thời điểm chọn tháng
  - Dữ liệu **không bị thay đổi** nếu hợp đồng bị xóa hoặc chỉnh sửa sau đó

- 👁️ Chỉ hiển thị thống kê khi chọn một tháng cụ thể

---

### ✅ v1.2.5

- 📢 Cảnh báo rõ ràng khi click vào hợp đồng đã bị xoá  
- 🎛️ Sửa bộ lọc trạng thái `Đã chuộc`, `Đã chuộc sớm`  
- 🎨 Thêm màu sắc + icon minh hoạ cho lịch sử đóng lãi  
- 🔁 Reload form khi gia hạn hoặc chuộc  
- 🚫 Cảnh báo khi gia hạn nhưng đã đóng hết lãi

---

### ✅ v1.2.4

- 🔄 Tự động tạo kỳ lãi gần nhất khi thêm/sửa  
- 🔍 Tìm tên khách hàng không dấu  
- 🌐 Kiểm tra phiên bản online  
- 🗃️ Tự cập nhật cấu trúc CSDL (không mất dữ liệu)

---

### ✅ v1.2.2 – 1.2.1

- 📑 Cải thiện căn lề, định dạng ngày khi in  
- 🧾 Thống kê và in PDF giống mẫu thật  
- 📆 Hiển thị chi tiết số ngày vay, kỳ cuối

---

## 🖥️ Yêu cầu hệ thống

- Windows 10 hoặc cao hơn  
- .NET Desktop Runtime 8.0+  
- Không cần SQL Server – dùng SQLite nội bộ

---

## 🔧 Cài đặt và sử dụng

1. Tải từ [Releases](https://github.com/whoamilittl3fish/QuanLyHopDong/releases)  
2. Giải nén và chạy `QuanLyVayVon.exe`  
3. Nhập key bản quyền để sử dụng đầy đủ tính năng  

---

## 🔐 Bản quyền

- Key bản quyền gắn với phần cứng (HWID)  
- Hỗ trợ key dùng thử và vĩnh viễn  
- Kiểm tra bản quyền offline, không cần mạng

---

## 📞 Liên hệ & hỗ trợ

- **SĐT**: 0966 346 694  
- **Email**: khoa.ngovoviet@gmail.com  
- **GitHub**: [github.com/whoamilittl3fish/QuanLyHopDong](https://github.com/whoamilittl3fish/QuanLyHopDong)

---

> Mọi ý kiến đóng góp xin gửi qua email hoặc tạo GitHub Issue.  
🙏 Cảm ơn bạn đã sử dụng phần mềm!
