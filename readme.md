# 📘 Ứng dụng Quản Lý Cầm Đồ – *v1.4.2*

> Phần mềm quản lý cầm đồ đơn giản, hiện đại, dễ sử dụng.  
> Phù hợp cho cửa hàng từ nhỏ đến vừa – tối ưu thao tác, in ấn, và quản lý lãi suất linh hoạt.  
> **Chỉ cần nhập thông tin khoản vay, phần mềm sẽ tự động chia kỳ, tính ngày đóng lãi. Đến hạn, hệ thống sẽ hiển thị cảnh báo màu (đỏ, vàng, xanh) để bạn dễ dàng theo dõi.**  
> 👉 Không còn ghi sổ thủ công – mọi thứ rõ ràng, minh bạch, dễ tra cứu và in ấn.

---

## 📥 Tải xuống & cài đặt

- 🔗 **Tải phần mềm tại**: [github.com/whoamilittl3fish/QuanLyHopDong/releases](https Các bước cài đặt:

1. Truy cập link trên
2. Kéo xuống phần **Assets** của phiên bản mới nhất
3. Tải file **`Setup_QuanLyHopDong.exe`**
4. Chạy để cài đặt phần mềm
5. Nhập key bản quyền để sử dụng đầy đủ tính năng

---

## 📞 Liên hệ & hỗ trợ

- **SĐT**: 0966 346 694  
- **Email**: khoa.ngovoviet@gmail.com  
- **GitHub**: [github.com/whoamilittl3fish/QuanLyHopDong](https://github.com/whop vui lòng gửi email hoặc tạo Issue trên GitHub.  
🙏 Xin chân thành cảm ơn bạn đã sử dụng phần mềm!

---

## ✅ Tính năng chính

- Quản lý hợp đồng vay: tạo / sửa / in PDF
- **Tự động chia kỳ theo ngày vay và kỳ hạn**
- **Cảnh báo màu khi tới hạn: đỏ (quá hạn), vàng (sắp tới), xanh (hôm nay)**
- Tự động tính lãi theo kỳ, số ngày từ kỳ gần nhất
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

## 🖥️ Yêu cầu hệ thống

- Hệ điều hành: Windows 10 hoặc cao hơn  
- Cần cài: [.NET Desktop Runtime 8.0+](https://dotnet.microsoft.com/en-us/download/dotnet/8.0 sẵn

---

## 📦 Cập nhật tính năng

### ✅ v1.4.2 – Gia hạn kỳ cuối & làm tròn tiền lãi  
> 📅 *30/07/2025*

- ✨ Thêm chức năng **gia hạn kỳ cuối** mà không đẩy kỳ cũ
- 💰 Làm tròn số tiền phải đóng lên **bội số của 100**

---

### ✅ v1.4.1 – Hoàn thiện giao diện & bộ cài đặt  
> 📅 *20/07/2025*

- 🪟 Cập nhật tên form hiển thị đúng trên thanh tác vụ
- 📦 Tối ưu bộ cài đặt: kiểm tra & cài đặt .NET Runtime 8.0 chính xác
- 🧹 Dọn dẹp mã nguồn cài đặt, tăng tính ổn định khi triển khai

---

### ✅ v1.4 – Tối ưu hiệu suất & trải nghiệm người dùng  
> 📅 *19/07/2025*

- Tự động đưa `LaiDenHomNay` về 0 cho hợp đồng đã chuộc/thanh lý
- Cải thiện nhập liệu số tiền, số điện thoại (hiển thị hàng nghìn)
- Tối ưu phân trang khi tìm kiếm, tự động khóa nút chuyển trang
- Tăng tốc kiểm tra mã hợp đồng trong CSDL

---


### 🔹 Các phiên bản trước v1.4 (rút gọn)

- **v1.3.1**: Thêm sai số khi so sánh số tiền đóng lãi, mở ứng dụng sau cài đặt
- **v1.3**: Cải tiến giao diện, thống kê nâng cao, lọc hợp đồng hết hiệu lực
- **v1.2.x**: Bảo mật bằng mật khẩu, cập nhật tự động, chuẩn hóa ngày tháng & tiền tệ
- **v1.1**: Phiên bản chính thức đầu tiên – quản lý hợp đồng, kỳ lãi, in ấn
- **v1.0**: Bản thử nghiệm nội bộ – giao diện đơn giản, chưa có bản quyền

---
