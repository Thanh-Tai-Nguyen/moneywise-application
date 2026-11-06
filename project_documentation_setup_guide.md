# 💳 MONEYWISE - Project Setup Guide for VS Code

Chào bạn! Dưới đây là hướng dẫn các bước để bạn mở và chạy ứng dụng **MONEYWISE** trực tiếp trong trình soạn thảo Visual Studio Code (VS Code).

---

## 📂 Cấu Trúc Dự Án (Project Structure)

```text
moneywise-app/
├── index.html     # File mã nguồn duy nhất chứa HTML, CSS (Tailwind) & JS Logic
└── README.md      # Hướng dẫn chạy dự án
```

---

## 🚀 Hướng Dẫn Mở & Chạy Trên VS Code

### Bước 1: Tạo Thư Mục Dự Án Trên Máy Tính
1. Tạo một thư mục mới tên `moneywise-app` trên máy tính của bạn.
2. Lưu 2 file `index.html` và `README.md` từ cửa sổ code editor vào thư mục vừa tạo.

### Bước 2: Mở Thư Mục Trong VS Code
1. Mở phần mềm **Visual Studio Code**.
2. Chọn **File** -> **Open Folder...** (hoặc gõ `Ctrl + O` / `Cmd + O`).
3. Chọn thư mục `moneywise-app` vừa tạo.

### Bước 3: Chạy Web Bằng Extension Live Server (Khuyên Dùng)
1. Trên thanh công cụ bên trái VS Code, nhấp vào biểu tượng **Extensions** (hoặc phím tắt `Ctrl + Shift + X`).
2. Tìm kiếm extension: **Live Server** (của tác giả *Ritwick Dey*).
3. Nhấn **Install** để cài đặt.
4. Sau khi cài xong, mở file `index.html` lên, click chuột phải vào vùng soạn thảo và chọn **Open with Live Server** (hoặc bấm nút *Go Live* ở góc dưới cùng bên phải màn hình).
5. Trình duyệt sẽ tự động mở trang web **MONEYWISE** tại địa chỉ `http://127.0.0.1:5500`.

---

## ⚙️ Tính Năng Chính Trong Web

- **Personal Finance Dashboard**: Quản lý thu/chi thực tế, cập nhật tự động & biểu đồ trực quan.
- **Smart Budget Allocation**: Đề xuất phân bổ ngân sách 50/30/20 và cơ chế Auto Adjust khi quá tay.
- **Savings Goal Planner**: Lập kế hoạch tiết kiệm nhiều mục tiêu, tính số tiền theo tháng và mô phỏng lộ trình.
- **Smart Expense Tracker**: Ghi chép giao dịch, lọc danh mục và scan hóa đơn thử nghiệm.
- **Shared Wallet**: Quản lý quỹ chung / chi phí chuyến đi chơi cùng bạn bè.
- **Spending Personality**: Phân tích kiểu người chi tiêu dựa trên lịch sử thu chi.
- **AI Financial Assistant**: Trợ lý tư vấn tài chính thông minh tích hợp Gemini.
- **Chế độ Light/Dark Mode**: Giao diện Light Mode ngọc trai/vàng trắng sang trọng và Dark Mode hiện đại.

---
✨ *Chúc bạn có trải nghiệm quản lý tài chính hiệu quả cùng MONEYWISE!*