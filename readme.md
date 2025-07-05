# 📘 Ứng dụng Quản Lý Cầm Đồ – *v1.2.7*

> Phần mềm quản lý cầm đồ đơn giản, giao diện hiện đại, dễ sử dụng. Phù hợp cho cửa hàng nhỏ đến vừa.

---

## 📥 Tải xuống & cài đặt

- 🔗 **Link tải**: [github.com/whoamilittl3fish/QuanLyHopDong/releases](https://github.com/whoamilittl3fish/QuanLyHopDong/releases)
- 🛠 **Cài đặt**:
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
🙏 Cảm ơn bạn đã sử dụng phần mềm!

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

- 📅 **Chuẩn hóa toàn bộ định dạng ngày** về `dd-MM-yyyy` cho:
  - Lịch sử đóng lãi
  - Ghi chú thao tác hợp đồng
  - File PDF hợp đồng

- ✍️ **Lịch sử hợp đồng rõ ràng, dễ tra cứu**:
  - Tiêu đề căn giữa bằng dấu gạch ngang
  - Dòng nội dung căn đều bằng dấu `_____`
  - Thao tác ghi rõ thời gian, kỳ lãi, số ngày gia hạn...

- 📜 Mọi thao tác như `Tạo`, `Sửa`, `Gia hạn`, `Chuộc`, `Đóng lãi`... đều có cấu trúc ghi chú đồng nhất

---

### ✅ v1.2.6

- 📊 **Thống kê cố định theo tháng**
- 🗃️ Không bị ảnh hưởng bởi xóa/sửa hợp đồng sau đó

---

### ✅ v1.2.5 → v1.2.1

- 🎛️ Tối ưu bộ lọc trạng thái, màu sắc lịch sử đóng lãi
- 🔄 Tự động tạo kỳ lãi gần nhất
- 🔍 Tìm kiếm không dấu, kiểm tra phiên bản online
- 🧾 In PDF giống mẫu thật
- 🗃️ Tự cập nhật CSDL không mất dữ liệu

---

## 🖥️ Yêu cầu hệ thống

- Windows 10 trở lên  
- .NET Desktop Runtime 8.0+  
- Không cần cài SQL Server – dùng SQLite tích hợp

