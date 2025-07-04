# 📘 Ứng dụng Quản Lý Cầm Đồ

Phần mềm quản lý cầm đồ đơn giản, giao diện đẹp, dễ sử dụng. Hỗ trợ đầy đủ các chức năng cần thiết cho cửa hàng nhỏ đến vừa.

---

## 🚀 Phiên bản hiện tại: **v1.2.5**

> Cải thiện quản lý hợp đồng, thêm màu và icon trực quan cho lịch sử đóng lãi, sửa lỗi thao tác hợp đồng

---

## ✅ Tính năng chính:
- Quản lý hợp đồng vay: Thêm / sửa hợp đồng nhanh chóng
- Tự động tính lãi theo kỳ, hiển thị số ngày từ kỳ gần nhất
- **Tự động tạo kỳ lãi đầu tiên** ngay khi thêm hoặc sửa hợp đồng
- Lịch sử đóng lãi từng kỳ, hỗ trợ gia hạn thông minh
- **Tìm kiếm hợp đồng không dấu**, chỉ cần gõ 1 từ bất kỳ
- Tìm kiếm và phân trang dữ liệu hợp đồng
- Quản lý tình trạng hợp đồng: Đang vay, Sắp tới hạn, Quá hạn, Tất toán...
- In hợp đồng và lịch sử đóng lãi theo mẫu Word hoặc PDF (QuestPDF)
- Bảo mật bằng key bản quyền vĩnh viễn (gắn với phần cứng)

---

## 🎨 Mã màu trạng thái hợp đồng:

| Trạng thái                     | Màu sắc      |
|-------------------------------|--------------|
| Đang vay                      | Trắng        |
| Sắp tới hạn                   | Vàng         |
| Tới hạn hôm nay               | Xanh lá sáng |
| Tới hạn hôm nay (đã đóng)     | Xanh lá đậm  |
| Quá hạn                       | Đỏ           |
| Đã chuộc (Tất toán)           | Xám đậm      |
| Đã đóng lãi tất cả kỳ         | Xám nhạt     |

---

## ✍️ Ghi chú thao tác hệ thống:

- `Tạo hợp đồng`         → Lưu thời gian tạo, người tạo  
- `Sửa hợp đồng`         → Chỉ được sửa nếu chưa có lịch sử đóng lãi  
- `Đóng lãi`             → Ghi nhận kỳ đóng, số tiền, ngày đóng  
- `Gia hạn kỳ đóng lãi` → Kỳ đầu tiên chưa đóng được đánh dấu là "gia hạn"  
- `Chuộc đồ (Tất toán)` → Cập nhật tình trạng, kết thúc hợp đồng  

---

## 💰 Hiển thị lãi đến hôm nay:

- Phần mềm tự động tính:  
  → Tổng lãi từ ngày vay hoặc từ kỳ đóng gần nhất cho tới hôm nay

- Hiển thị trong bảng để:  
  → Ước tính số tiền cần đóng nếu muốn chuộc  
  → Dễ kiểm soát hợp đồng quá hạn lâu chưa đóng  

---

## 📊 Thống kê nhanh:

- Số hợp đồng đang vay        : XX  
- Tổng tiền đang cho vay      : XXX,XXX,000 VNĐ  
- Tổng lãi đã thu trong tháng : XX,XXX,000 VNĐ  

---

## 🆕 Thay đổi gần đây:

### ✅ v1.2.5:
- 📢 Cảnh báo rõ ràng khi click vào hợp đồng đã bị xoá
- 🧹 Sửa bộ lọc các trạng thái `Đã chuộc`, `Đã chuộc sớm`
- 🎨 Bảng lịch sử đóng lãi có màu sắc nổi bật:
  - 🔴 Quá hạn / tới hạn hôm nay (chưa đóng)
  - 🟢 Tới hạn hôm nay đã đóng, Đang vay
  - 🟡 Sắp tới hạn
  - ⚪ Đã đóng tất cả kỳ
  - ⚫ Đã chuộc / chuộc sớm
- 🖼️ Thêm icon minh hoạ từng dòng trong bảng đóng lãi
- 📅 Thêm cột "Tổng thời gian vay (ngày)" trong lịch sử hợp đồng
- 🔁 Reload lại form lịch sử đóng lãi sau khi gia hạn hoặc chuộc
- 🚫 Không cho gia hạn nếu đã đóng tất cả kỳ

### ✅ v1.2.4:
- Tự động tạo kỳ lãi gần nhất khi thêm hoặc sửa hợp đồng
- Tìm kiếm tên khách hàng không dấu (ví dụ: gõ "khoa" sẽ ra "Việt Khoa")
- Kiểm tra phiên bản phần mềm online nếu có kết nối mạng
- Tự cập nhật cấu trúc CSDL (nếu phát hiện bản cũ) mà không làm mất dữ liệu

### ✅ v1.2.2:
- Sửa lỗi căn chữ trong phần in số tiền bằng chữ (Việt hoá chính xác hơn)
- Cập nhật in lịch sử đóng lãi: hiển thị ngày bắt đầu / ngày kết thúc đúng định dạng `dd/MM/yyyy`

### ✅ v1.2.1:
- Cập nhật logic thống kê: tổng lãi đã thu, số hợp đồng đang vay và tổng tiền đang cho vay chính xác hơn
- In PDF hợp đồng / lịch sử đẹp hơn, căn chỉnh sát mẫu thực tế
- Giao diện “Giới thiệu” mới: thông tin tác giả, liên hệ rõ ràng

---

## 💻 Yêu cầu hệ thống:

- Hệ điều hành: Windows 10 trở lên
- .NET Desktop Runtime **8.0** hoặc cao hơn
- Không cần cài SQL Server (sử dụng SQLite nội bộ)

---

## 📦 Cài đặt và sử dụng:

1. Tải về từ mục [Releases](https://github.com/whoamilittl3fish/QuanLyHopDong/releases)
2. Giải nén và chạy file `QuanLyVayVon.exe`
3. Nhập key bản quyền (liên hệ để nhận)

---

## 🔐 Bản quyền & kích hoạt:

- Hệ thống key bản quyền dựa trên thông tin phần cứng (HWID)
- Hỗ trợ tạo key dùng thử, key vĩnh viễn và kiểm tra offline
- Liên hệ bên dưới để được cấp key

---

## 📞 Hỗ trợ & liên hệ:

- **SĐT**: 0966 346 694  
- **Email**: khoa.ngovoviet@gmail.com

---

> Mọi phản hồi hoặc đề xuất tính năng mới xin gửi về qua email hoặc tạo GitHub Issue.
