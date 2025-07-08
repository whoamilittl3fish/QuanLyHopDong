# 📘 Ứng dụng Quản Lý Cầm Đồ – *v1.2.10*

> Phần mềm quản lý cầm đồ đơn giản, giao diện hiện đại, dễ sử dụng.  
> Phù hợp cho cửa hàng nhỏ đến vừa – tối ưu thao tác, in ấn và quản lý lãi suất.

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

- Quản lý hợp đồng vay: tạo / sửa / in PDF
- Tự động tính lãi theo kỳ, tính số ngày từ kỳ gần nhất
- Ghi nhận lịch sử đóng lãi, hỗ trợ gia hạn thông minh
- Tìm kiếm không dấu, lọc theo tên, mã, loại tài sản, tình trạng, khoảng thời gian
- Quản lý trạng thái: Đang vay, Sắp tới hạn, Quá hạn, Tất toán, Đã chuộc
- In hợp đồng và lịch sử đóng lãi bằng mẫu Word hoặc PDF (QuestPDF)
- Thống kê tổng lãi thu/tháng, tổng hợp đồng, tổng tiền đang vay
- Hệ thống bản quyền vĩnh viễn theo phần cứng
- Hỗ trợ định dạng số tiền và ngày tháng chuẩn quốc tế
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

- **Tạo hợp đồng**: lưu người tạo và thời gian  
- **Sửa hợp đồng**: chỉ khi chưa có kỳ lãi nào  
- **Đóng lãi**: ghi chi tiết từng kỳ  
- **Gia hạn**: tự thêm kỳ tiếp theo, đánh dấu kỳ đầu chưa đóng  
- **Tất toán**: kết thúc hợp đồng, không thể chỉnh sửa

---

## 🖥️ Yêu cầu hệ thống

- Windows 10 trở lên  
- .NET Desktop Runtime 8.0+  
- Không cần cài SQL Server – phần mềm dùng SQLite tích hợp

---

## 📦 Cập nhật tính năng

### 🆕 v1.2.10

- 💰 **Chuẩn hóa định dạng số tiền theo chuẩn quốc tế**
  - Dấu **phẩy `,`** phân cách hàng nghìn, **dấu chấm `.`** cho thập phân
  - Áp dụng cho hợp đồng PDF, lịch sử đóng lãi, và các ô nhập liệu tiền

- 🌐 **Tương thích đa ngôn ngữ hệ điều hành**
  - Hoạt động ổn định trên Windows tiếng Việt, tiếng Anh,...
  - Dữ liệu luôn hiển thị đúng bất kể ngôn ngữ hệ thống

- 📅 **Cải tiến định dạng ngày**
  - Dùng định dạng: **`dd - MM - yyyy`** (ví dụ: `01 - 01 - 2025`)
  - Căn giữa nội dung ngày trong `DateTimePicker`
  - Dễ đọc, đồng bộ giữa giao diện và in ấn

- 🖥️ **Tối ưu giao diện chọn ngày**
  - Định dạng ngày ổn định, hiển thị rõ
  - Có thể chọn nhanh bằng popup hoặc bàn phím

---

### 🕘 Lịch sử phiên bản trước

#### ✅ v1.2.9 – Bảo mật ứng dụng bằng mật khẩu
- Đặt mật khẩu đăng nhập, yêu cầu xác thực khi thực hiện thao tác quan trọng
- Giao diện đổi mật khẩu hiện đại, xác nhận kỹ lưỡng

#### ✅ v1.2.8 – Tự động cập nhật phần mềm
- Cho phép tải & cài đặt bản mới từ GitHub chỉ với 1 nút bấm
- Giao diện cập nhật có hiệu ứng, hiển thị tiến trình

#### ✅ v1.2.7 – Chuẩn hóa định dạng ngày
- Đồng bộ định dạng `dd-MM-yyyy` cho toàn hệ thống
- Lịch sử thao tác rõ ràng, căn lề đều, nhóm theo thời gian

#### ✅ v1.2.6 – Thống kê cố định theo tháng
- Ghi nhận tổng tiền thu & số hợp đồng đã thu trong từng tháng
- Dữ liệu thống kê không thay đổi khi sửa/xoá hợp đồng

#### ✅ v1.2.5 – Tối ưu trải nghiệm người dùng
- Thông báo lỗi rõ ràng hơn, tối ưu bộ lọc hợp đồng
- Cập nhật màu sắc bảng lịch sử dễ nhận biết trạng thái
