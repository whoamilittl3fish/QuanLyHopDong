# 📘 Pawnshop Management App – *v1.4.3*

> A simple, modern, and user-friendly pawnshop management software.  
> Ideal for small to medium-sized shops – optimized for operations, printing, and flexible interest rate management.  
> **Just enter the loan details, and the software will automatically split the terms and calculate due dates. When due, the system will highlight with color alerts (red, yellow, green) for easy tracking.**  
> 👉 Say goodbye to manual bookkeeping – everything is clear, transparent, and easy to search and print.

---

## 📥 Download & Install

- 🔗 [**Download here**](github.com/whoamilittl3fish/QuanLyHopDong/releases)

### Installation Steps:

1. Visit the link above  
2. Scroll down to the **Assets** section of the latest release  
3. Download the **`Setup_QuanLyHopDong.exe`** file  
4. Run the installer  
5. Enter your license key to unlock full features

---

## 📞 Contact & Support

- **Phone**: +84 966 346 694  
- **Email**: khoa.ngovoviet@gmail.com  
- **GitHub**: [Github link](https://github.com/whoamilittl3fish)

> Please send an email or create an Issue on GitHub.  
🙏 Thank you for using the software!

---

## ✅ Key Features

- Manage pawn contracts: create / edit / export to PDF
- **Automatically split terms based on loan date and duration**
- **Color-coded alerts for due dates: red (overdue), yellow (upcoming), green (today)**
- Automatically calculate interest per term and days since last payment
- Record payment history, support smart term extensions
- Search without accents, filter by name, code, asset type, status, date range
- Manage statuses: Active, Upcoming Due, Overdue, Settled, Redeemed
- Print contracts and payment history using Word or PDF templates (QuestPDF)
- Monthly revenue statistics, total contracts, total loaned amount
- Lifetime license system tied to hardware (HWID), with encryption
- Supports international formats for currency and date (`dd-MM-yyyy`)
- Rounded, modern UI optimized for Full HD (1920x1080)

---

## 🎨 Contract Status Colors

| Status                        | Color         |
|------------------------------|---------------|
| Active                       | White         |
| Upcoming Due                 | Yellow        |
| Due Today (unpaid)           | Light Green   |
| Due Today (paid)             | Dark Green    |
| Overdue                      | Red           |
| Redeemed                     | Dark Gray     |
| All Terms Paid               | Light Gray    |

---

## 🖥️ System Requirements

- Operating System: Windows 10 or later  
- Required: [.NET Desktop Runtime 8.0+](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.18-windows-x64-installer) Fixes  
> 📅 *12/08/2025*

- 🖼️ Fixed controls sticking to edges when maximizing the form
- 🔧 Switched from `Dock` to `Anchor` for proper 4-side scaling
- 💡 Smoother UI when resizing the window

---

### ✅ v1.4.2 – Final Term Extension & Interest Rounding  
> 📅 *30/07/2025*

- ✨ Added feature to **extend the final term** without shifting previous ones
- 💰 Rounded payable interest to the **nearest 100**

---

### ✅ v1.4.1 – UI & Installer Improvements  
> 📅 *20/07/2025*

- 🪟 Updated form title display on taskbar
- 📦 Optimized installer: accurate .NET Runtime 8.0 detection & installation
- 🧹 Cleaned up installer code for better deployment stability
---

### ✅ v1.4 – Performance & UX Enhancements  
> 📅 *19/07/2025*

- Automatically reset `LaiDenHomNay` to 0 for redeemed/settled contracts
- Improved input for money and phone numbers (thousand separators)
- Optimized pagination and auto-disable navigation buttons
- Faster contract code validation in database

---

### 🔹 Versions before v1.4 (summary)

- **v1.3.1**: Added tolerance for interest comparison, auto-launch after install  
- **v1.3**: UI improvements, advanced statistics, filter expired contracts  
- **v1.2.x**: Password protection, auto-updates, standardized date & currency  
- **v1.1**: First official release – contract management, interest terms, printing  
- **v1.0**: Internal beta – basic UI, no licensing
