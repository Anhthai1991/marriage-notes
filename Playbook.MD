# Marriage Playbook – Hướng Dẫn Sử Dụng & Cách Gọi Lại Project

Đây là hướng dẫn giúp bạn (hoặc bất kỳ ai) dễ dàng tiếp tục phát triển project **Marriage-Playbook** ngay cả khi đã xoá lịch sử chat hoặc làm việc trên thiết bị mới.

---

## 📌 1. Cách tiếp tục làm việc với ChatGPT

Sau khi xoá lịch sử chat, để ChatGPT hiểu và tiếp tục làm việc với đúng project này, bạn chỉ cần dùng **một trong hai cách**:

### **Cách A – Gửi link GitHub Pages**
Ví dụ:
```
Đây là trang project của mình:
https://anhthai1991.github.io/Marriage-Playbook/
Hãy tiếp tục giúp mình chỉnh mục X.
```

### **Cách B – Gửi link repo GitHub**
Ví dụ:
```
Repo project đây:
https://github.com/anhthai1991/Marriage-Playbook
Hãy sửa phần sidebar cho mình.
```

➡️ ChatGPT sẽ tự đọc cấu trúc dự án, hiểu layout Jekyll, và tiếp tục build đúng format.

---

## 📌 2. Cấu trúc dự án (để ChatGPT nắm được nhanh)

```
Marriage-Playbook/
│
├── _config.yml              # Cấu hình Jekyll
├── _layouts/
│   └── default.html         # Layout chính: sidebar + dark mode + responsive
│
├── index.md                 # Nội dung toàn bộ Playbook
│
└── assets/ (tuỳ chọn)       # Ảnh, file css/js nếu sau này thêm
```

Chỉ cần ChatGPT thấy 3 file trên là có thể tiếp tục phát triển.

---

## 📌 3. Khi bạn muốn ChatGPT chỉnh sửa file nào đó

Bạn có thể nói:
```
Hãy mở và chỉnh sửa file default.html của project.
```
Hoặc:
```
Trong index.md, hãy biến phần 2.3 thành collapsible.
```

➡️ ChatGPT sẽ đọc file, sửa code, rồi gửi lại bản cập nhật để bạn copy vào GitHub.

---

## 📌 4. Khi bạn muốn thêm tính năng mới
Ví dụ:
```
Hãy thêm trang riêng /for-wife.
```
Hoặc:
```
Tạo dark mode nâng cao.
```
Hoặc:
```
Tạo dashboard Harmony Score dạng biểu đồ.
```

Bạn không cần mô tả lại từ đầu — chỉ cần nói yêu cầu và gửi link repo hoặc link site.

---

## 📌 5. Khi bạn muốn ChatGPT build lại ZIP project
Bạn chỉ cần nói:
```
Đóng gói project thành file ZIP.
```
ChatGPT sẽ tạo lại phiên bản ZIP mới nhất.

---

## 📌 6. Tips để dùng project lâu dài
- Luôn giữ repo GitHub → project sẽ tồn tại vĩnh viễn.
- Dùng commit message rõ ràng: `update section 1.1`, `add for-child page`.
- Không cần giữ lịch sử chat.
- ChatGPT luôn có thể “load lại project” nếu bạn cung cấp link GitHub.

---

## 📌 7. Khi muốn nâng cấp project lớn
Chỉ cần nói:
```
Mình muốn chuyển site sang multi-page.
Mình muốn thêm phiên bản tiếng Anh.
Mình muốn thêm mục cho bà ngoại.
Mình muốn làm bản PDF để in.
```
ChatGPT sẽ tiếp tục từ cấu trúc hiện tại.

---

## 🎉 Kết luận
Project của bạn **đã hoàn chỉnh, độc lập, dễ mở rộng**.  
Dù bạn xoá hết lịch sử chat, bạn vẫn có thể khởi động lại bất cứ lúc nào—chỉ cần gửi link repo.

Chúc bạn tiếp tục phát triển Marriage-Playbook thành một cuốn sổ tay hôn nhân – nuôi dạy con thật giá trị và bền vững ❤️
