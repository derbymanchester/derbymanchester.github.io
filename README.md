# Video Edge Detection – HTML5 Canvas

Bài tập: Hiển thị video + canvas edge detection theo thời gian thực.

## Tính năng
- Video gốc bên trái, canvas hiện biên cạnh bên phải (cùng kích thước)
- 3 bộ lọc: **Sobel grayscale**, **Sobel màu**, **Laplacian**
- Điều chỉnh ngưỡng (threshold) bằng slider
- Tải video từ máy tính hoặc dùng video mẫu sẵn có
- Hiển thị FPS thực tế

---

## Cài đặt & Chạy local với NodeJS

### Bước 1 — Cài Node.js

1. Truy cập **https://nodejs.org**
2. Tải bản **LTS** (nút xanh lá, khuyên dùng)
3. Chạy file cài đặt → Next → Next → Finish
4. Kiểm tra cài thành công bằng cách mở **Command Prompt** hoặc **Terminal** và gõ:

```bash
node -v
npm -v
```

Nếu hiện số version (ví dụ `v20.11.0`) là thành công 

---

### Bước 2 — Giải nén project

Giải nén file `video-edge-detect.zip` ra một thư mục, ví dụ:
- Windows: `C:\video-edge-detect\`
- Mac/Linux: `~/video-edge-detect/`

---

### Bước 3 — Mở Terminal trong thư mục project

**Windows:** Vào thư mục vừa giải nén → giữ **Shift + chuột phải** → chọn **"Open PowerShell window here"**

**Mac:** Mở Terminal → gõ:
```bash
cd ~/video-edge-detect
```

**Linux:** Mở Terminal → gõ:
```bash
cd ~/video-edge-detect
```

---

### Bước 4 — Cài dependencies

```bash
npm install
```

Lệnh này tải thư viện `express` về (sinh ra thư mục `node_modules/`). Chờ khoảng 30 giây.

---

### Bước 5 — Khởi động server

```bash
npm start
```

Terminal sẽ hiển thị:
```
Server chay tai: http://localhost:8080
```

---

### Bước 6 — Mở trình duyệt

Truy cập: **http://localhost:8080**

Website sẽ hiện ra! 

> Giữ nguyên cửa sổ Terminal đang chạy, **đừng đóng**.
> Muốn dừng server thì nhấn **Ctrl + C**.

---

> Node.js chỉ dùng để test local. Toàn bộ logic edge detection chạy bằng JavaScript thuần trong trình duyệt, hoạt động bình thường trên GitHub Pages.
