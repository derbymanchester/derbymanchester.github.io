# Video Edge Detection – HTML5 Canvas

Bài tập: Hiển thị video + canvas edge detection theo thời gian thực.

## Tính năng
- Video gốc bên trái, canvas hiện biên cạnh bên phải (cùng kích thước 600×250)
- 5 bộ lọc: **Sobel grayscale**, **Sobel màu**, **Laplacian**, **Emboss**, **Invert**
- Điều chỉnh ngưỡng (threshold) và độ sáng bằng slider
- Tùy chọn màu viền và màu nền canvas
- Tải video từ máy tính hoặc dùng video mẫu đính kèm (sample.mp4)
- Histogram realtime phân bố độ sáng
- Chụp ảnh canvas thành file PNG
- Hiển thị FPS thực tế

---

## Xem website trực tiếp

**https://derbymanchester.github.io**

---

## Cài đặt & Chạy local với NodeJS

### Bước 1 — Cài Node.js

1. Truy cập **https://nodejs.org**
2. Tải bản **LTS** (nút xanh lá, khuyên dùng)
3. Chạy file cài đặt → Next → Next → Finish
4. Kiểm tra thành công bằng cách mở **Command Prompt** / **Terminal** và gõ:

```bash
node -v
npm -v
```

Nếu hiện số version (ví dụ `v20.11.0`) là thành công 

---

### Bước 2 — Tải project về máy

Vào repo GitHub → nhấn **Code** → **Download ZIP** → giải nén ra thư mục.

---

### Bước 3 — Mở Terminal trong thư mục project

**Windows:** Vào thư mục vừa giải nén → giữ **Shift + chuột phải** → **"Open PowerShell window here"**

**Mac/Linux:**
```bash
cd ~/đường-dẫn-tới-thư-mục
```

---

### Bước 4 — Cài dependencies

```bash
npm install
```

---

### Bước 5 — Khởi động server

```bash
npm start
```

Terminal hiển thị:
```
Open: http://localhost:8080
```

---

### Bước 6 — Mở trình duyệt

Truy cập: **http://localhost:8080**

> Giữ nguyên cửa sổ Terminal, đừng đóng. Nhấn **Ctrl + C** để dừng.

---

> `index.js` chỉ dùng để test local. Toàn bộ xử lý ảnh chạy bằng JavaScript thuần trong trình duyệt, hoạt động bình thường trên GitHub Pages.
