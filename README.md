# 🔎 IT Job Finder – ReactJS Project

Dự án **IT Job Finder** là một ứng dụng web được xây dựng bằng **ReactJS**, hỗ trợ người dùng tìm kiếm, lọc và quản lý thông tin việc làm trong lĩnh vực CNTT.  
Ứng dụng hướng đến trải nghiệm đơn giản, hiện đại và trực quan cho người tìm việc.

---

## 🚀 Công nghệ sử dụng

- **ReactJS**
- **React Router** – điều hướng giữa các trang
- **Axios / Fetch API** – gọi API
- **Redux / Context API** – quản lý state (tùy thiết kế)
- **TailwindCSS / SCSS / CSS Modules** – tạo giao diện
- **JSON-server / Mock API** – tạo dữ liệu mẫu khi phát triển

---

## 📂 Cấu trúc thư mục

```bash
project-final-6-v1/
│── public/
│── src/
│   ├── assets/          # Ảnh, icon, media
│   ├── components/      # Component dùng lại
│   ├── pages/           # Các trang của ứng dụng
│   ├── services/        # API services
│   ├── hooks/           # Custom hooks
│   ├── context/         # Global state (nếu có)
│   ├── utils/           # Hàm tiện ích
│   ├── App.js
│   └── main.js
│── package.json
│── README.md
````

---

## ✨ Chức năng chính

### 👨‍💻 Dành cho người tìm việc

* Tìm kiếm việc làm theo từ khóa
* Lọc theo:

  * Vị trí (Frontend, Backend, QA…)
  * Kinh nghiệm
  * Mức lương
  * Hình thức làm việc (Full-time, Remote…)
* Xem chi tiết mô tả công việc
* Lưu công việc yêu thích (bookmark)

### 🛠 Dành cho quản trị (nếu có)

* Tạo mới tin tuyển dụng
* Sửa thông tin công việc
* Xóa công việc
* Quản lý danh sách các tin tuyển dụng

---

## 🏁 Cách chạy dự án

### 1. Clone repository

```bash
git clone https://github.com/lequangtuyen543/project-final-6-v1.git
cd project-final-6-v1
```

### 2. Cài đặt dependencies

```bash
npm install
```

### 3. Chạy dự án

```bash
npm start
```

Ứng dụng chạy tại:
➡ **[http://localhost:3000](http://localhost:3000)**

---

## 🛠 Build dự án

```bash
npm run build
```

---

## 🧪 Nếu sử dụng JSON-Server (tùy chọn)

```bash
npx json-server --watch db.json --port 4000
```

---

## 📌 Yêu cầu hệ thống

* **Node.js ≥ 16**
* **NPM ≥ 8**

---

## 🔗 Liên kết dự án

GitHub Repository:
➡ **[https://github.com/lequangtuyen543/project-final-6-v1](https://github.com/lequangtuyen543/project-final-6-v1)**

---

## 📄 Giấy phép

Dự án thuộc sở hữu của **Lê Quang Tuyến**.
Bạn có thể tự do tham khảo, chỉnh sửa và cải tiến theo nhu cầu cá nhân.

---
